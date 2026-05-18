## Calculator Project
I'm Michael, a young coder learning Python.
I want people to see what I did over the past week.
This is one project I really enjoyed.

## How to Run
Copy the code into any Python compiler or editor that supports user input.

## Current Features
Asks for two numbers
Adds them together
Shows the result

## Future Updates (June–September)
Add subtraction
Add multiplication
Add division
(I'm working on it, but it's hard!)

## Known Bug
If you type something that is NOT a number, the program will stop and crash.
I plan to fix this later with error handling.

## Code
print("Hello this is my cool calculater")
print("is this good for a young person that started 1 week ago")

num = float(input("enter the first number "))
num_2 = float(input("enter the second number "))
answer = float(num) + float(num_2)
print(f"the addition answer is {answer}")







## Dice Roller Project
I'm Michael, a young coder learning Python.
This is another project I made while practicing my skills.
I wanted to try something simple but fun.

## How to Run
Copy the code into any Python editor that supports user input.

## Current Features
Rolls a random number from 1 to 9
Shows the result of the roll
Gives a message depending on what number you get

## Future Updates (June–September)
Add more dice sizes (like 6‑sided or 12‑sided)
Add a replay option
Add a small scoring system

## Known Behavior
If you roll 1–5, the program tells you to try again and aim higher.
If you roll 6–9, it challenges you to try for a lower number next time.

## Code
import random
roll = random.randint(1, 9)
print(f" you got {roll} on your roll")
if roll <= 5:
    print("")
    print(" try again and try to get 5+")
else:
    print("")
    print("try to get 2 or 1!")
