# Quiz
print('Welcome to my computer quiz!')
play = input('Do you want to play? ')
score = 0

if play != 'yes':
    quit()

print("Okay, let's play!")

answer = input('What does CPU stand for? ')
if answer.lower() == 'central processing unit':
    print('Correct answer!')
    score += 1
else:
    print('Oops! Incorrect answer')

answer = input('What does GUI stands for? ')
if answer.lower() == 'graphic user interface':
    print('Correct answer!')
    score += 1
else:
    print('Oops! Incorrect answer')

answer = input("What does RAM stand for? ")
if answer.lower() == "random access memory":
    print('Correct answer!')
    score += 1
else:
    print("Oops! Incorrect answer")

answer = input("What does PSU stand for? ")
if answer.lower() == "power supply":
    print('Correct answer!')
    score += 1
else:
    print("Oops! Incorrect answer")

answer = input("How many basic components are there in a computer? ")
if answer.lower() == "three" or answer == "5":
    print('Correct answer!')
    score += 1
else:
    print("Oops! Incorrect answer")

print('You got ' + str(score) + ' questions correct!' )
print ('You got ' + str(score/4 * 100) + '%')
