# Assign-2_Control-Structures-in-Python

TASK 1

Functionality of the Program

Takes user input

n = eval(input("Enter the Number :- "))


The program asks the user to enter a number.

The value is stored in the variable n.

Checks the condition

if n % 2 == 0:


The modulus operator % finds the remainder when n is divided by 2.

If the remainder is 0, the number is even.

Displays the result

print(n, "is an Even Number,")


Printed when the number is even.

Handles the odd case

else:
    print(n, "is an Odd Number.")


TASK 2

Functionality of the Program

Takes user input

n = int(input("Enter the number of terms :- "))


The program asks the user to enter how many terms they want.

The input is converted to an integer and stored in the variable n.

Initializes a variable

sum = 0


A variable sum is initialized to store the total sum.

It starts from 0.

Uses a loop to calculate the sum

for i in range(1, n+1):
    sum += i


The for loop runs from 1 to n.

Each number is added to sum.

Displays the result

print("\nSum of first", n, "terms is:", sum)


The program prints the final sum of the first n natural numbers.


If the remainder is not 0, the number is odd.
