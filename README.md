Basic Calculator Program
---------------------------------------------
This repository contains a simple Python program that performs basic arithmetic operations: addition, subtraction, multiplication, and division. The user is prompted to input an operation and two numbers, and the program outputs the result of the specified operation.

Features

Addition: Adds two numbers.

Subtraction: Subtracts the second number from the first number. If the result is negative, a warning message is displayed.

Division: Divides the first number by the second number. If the second number is zero, a warning message is displayed to prevent division by zero.

Multiplication: Multiplies two numbers.

Functions
---------------------------------------------
'add(y, z)': Returns the sum of y and z.

'substraction(y, z)': Returns the difference between y and z. Displays a warning if the result is negative.

'devision(y, z)': Returns the division of y by z. Displays a warning if z is zero.

'multiplication'(y, z): Returns the product of y and z.

Usage
---------------------------------------------
Clone the repository:
git clone https://github.com/your-username/basic-calculator.git
cd basic-calculator

Run the program:
---------------------------------------------
python calculator.py

Input the desired operation when prompted (+, -, /, *).

Input the first number when prompted.

Input the second number when prompted.

The program will display the result of the operation.

Example
---------------------------------------------
please input operation (+,-,/,*) : +

operation is: +

please input number1: 5

please input number2: 3

your add result is: 8

Error Handling
---------------------------------------------
Subtraction: If the result of the subtraction is negative, the program prints a warning message: "please be sure first input is greater than second".

Division: If the second number is zero, the program prints a warning message: "0 input is unacceptable for second input".
    
Notes
---------------------------------------------
Ensure that the inputs are valid numbers to avoid any runtime errors.

This program does not handle non-integer inputs or invalid operations gracefully, so additional validation might be necessary for a production environment.

License
---------------------------------------------
This project is licensed under the MIT License - see the LICENSE file for details.

Contributions
---------------------------------------------
Contributions are welcome! Please feel free to submit a Pull Request.

Contact
---------------------------------------------
For any questions or issues, please open an issue in this repository.
