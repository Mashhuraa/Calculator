# Calculator

## Basic Calculator Program
-------------------------------
This repository contains a simple Python program that performs basic arithmetic operations: addition, subtraction, multiplication, and division. The user is prompted to input an operation and two numbers, and the program outputs the result of the specified operation.

##Features
------------------------
Addition: Adds two numbers.
----------------------
Subtraction: Subtracts the second number from the first number. If the result is negative, a warning message is displayed
----------------------
Division: Divides the first number by the second number. If the second number is zero, a warning message is displayed to prevent division by zero.
----------------------
Multiplication: Multiplies two numbers.
----------------------

##Functions
--'add(y, z)': Returns the sum of y and z.
--'substraction(y, z)': Returns the difference between y and z. Displays a warning if the result is negative.
--'devision(y, z)': Returns the division of y by z.
--Displays a warning multiplication(y, z): Returns the product of y and z.

##Usage
1.Clone the repository:
'''bash
git clone https://github.com/your-username/basic-calculator.git
cd basic-calculator
'''

2. Run the program:
'''bash
python calculator.py
'''
3.Input the desired operation when prompted (+, -, /, *).
4.Input the first number when prompted
5.Input the second number when prompted.
6.The program will display the result of the operation.

##Example
please input operation (+,-,/,*) : +
operation is: +
please input number1: 5
please input number2: 3
your add result is: 8

##Error Handling
--Subtraction: If the result of the subtraction is negative, the program prints a warning message: "please be sure first input is greater than second".
--Division: If the second number is zero, the program prints a warning message: "0 input is unacceptable for second input".

##Code
def add(y, z):
    x = y + z
    return x
def substraction(y, z):
    x = y - z
    if x < 0:
        print('please be sure first input is greater than second')
    return x
def devision(y, z):
    if z != 0:
        x = y / z
        return x
    else:
        print('0 input is unacceptable for second input')
def multiplication(y, z):
    x = y * z
    return x
in_opr = input('please input operation (+,-,/,*) : ')
print('operation is:', in_opr)
in_num1 = int(input('please input number1: '))
in_num2 = int(input('please input number2: '))
if in_opr == "+":
    out_add = add(in_num1, in_num2)
    print('your add result is:', out_add)
elif in_opr == "-":
    out_sub = substraction(in_num1, in_num2)
    print('your sub result is:', out_sub)
elif in_opr == "/":
    out_dev = devision(in_num1, in_num2)
    print('your dev result is:', out_dev)
elif in_opr == "*":
    out_mult = multiplication(in_num1, in_num2)
    print('your mult result is:', out_mult)
else:
    print('please input the right operation')
    
##Notes
--Ensure that the inputs are valid numbers to avoid any runtime errors.
--This program does not handle non-integer inputs or invalid operations gracefully, so additional validation might be necessary for a production environment.

##License
--This project is licensed under the MIT License - see the LICENSE file for details.

##Contributions
--Contributions are welcome! Please feel free to submit a Pull Request.

##Contact
--For any questions or issues, please open an issue in this repository.
