# Calculator
Java Console calculator app:

A simple command-line calculator written in Java. It reads two numbers and an operation from the user, then displays the result. This beginner project demonstrates console input, arithmetic operators, and conditional statements.

Features
- Supports addition, subtraction, multiplication, and division.
- Accepts whole numbers and decimal numbers using the double data type.
- Checks for division by zero before dividing.
- Displays a message when the operation number is outside the supported range.
  
Requirements
- A Java Development Kit (JDK) installed, with java and javac available in your terminal.
- No external libraries are required; the program uses java.util.Scanner.
  
Setup and Run
1. Create a project folder and save the supplied code as day3/Calculator.java inside it. The day3 folder matches the code's package day3; declaration. Save this README in the project folder.
2. Open a terminal in the project folder, which contains the day3 directory.
3. Compile the program:
   javac day3/Calculator.java
4. Run the program from the same folder:
   java -cp . day3.Calculator

Usage
Enter the first number, the second number, and an operation number when prompted. Press Enter after each input.
Choice	Operation	Calculation
1	Addition	First number + second number
2	Subtraction	First number − second number
3	Multiplication	First number × second number
4	Division	First number ÷ second number

Example
For the following inputs:
- First number: 10
- Second number: 5
- Operation: 1
The final output is:
Result: 15.0
The program also prints each number and the selected operation after reading them.
Error Handling
Selecting division with a second number of 0 prints:
Error: Divison by zero is not allowed
Entering an integer operation choice outside 1–4 prints:
Invalid choice
These messages match the current source code, including the spelling of Divison.
Current Limitations
- Performs one calculation per run. Restart the program for another calculation.
- Expects numeric inputs and an integer operation choice. Invalid input, such as letters instead of numbers, is not caught and may terminate the program with an InputMismatchException.
- Uses floating-point arithmetic, so some decimal results may contain small rounding differences.
Concepts Practiced
- Reading console input with Scanner.
- Storing values in double and int variables.
- Using arithmetic operators and if / else if / else statements.
- Checking a divisor before division.
