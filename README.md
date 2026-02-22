This repository contains two basic Python programs:
Check if a number is Even or Odd
Sum of integers from 1 to 50 using a loop

Task 1: Check if a Number is Even or Odd
Write a Python program that:
Takes an integer input from the user.
Checks whether the number is even or odd using an if-else statement.
Displays the result. 
Code
Python
Copy code
# Task 1: Check if a Number is Even or Odd

number = int(input("Enter a number: "))

if number % 2 == 0:
    print(f"{number} is an even number.")
else:
    print(f"{number} is an odd number.")
▶ Example Output

Enter a number: 7
7 is an odd number.
Copy code

Enter a number: 12
12 is an even number.

Task 2: Sum of Integers from 1 to 50 Using a Loop
Problem Statement
Write a Python program that:
Uses a for loop to iterate from 1 to 50.
Calculates the sum of all integers in this range.
Displays the final sum.
Code
Python
# Task 2: Sum of Integers from 1 to 50 Using a Loop

total = 0

for number in range(1, 51):
    total += number

print("The sum of numbers from 1 to 50 is:", total)
▶ Expected Output
Copy code

The sum of numbers from 1 to 50 is: 1275
