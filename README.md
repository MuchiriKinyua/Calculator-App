![calculator](https://github.com/user-attachments/assets/3376fd8c-e1a4-45ff-8d07-0a53904ae899)

# Calculator App </br>

This is a simple Calculator App built using HTML, CSS, and JavaScript. The app allows users to perform basic arithmetic operations, including addition, subtraction, multiplication, and division. Additionally, it includes functionality for inserting the value of Pi (\u03C0) into calculations. </br>

# Features </br>

Basic Arithmetic: Perform addition (+), subtraction (-), multiplication (*), and division (/). </br>

Pi Button: Insert the mathematical constant Pi (\u03C0) into calculations. </br>

Clear Display: Reset the calculator display with the AC button. </br>

Delete Button: Remove the last entered character from the display. </br>

Responsive UI: A user-friendly interface styled with CSS. </br>

# How to Run the App </br>

Clone or download this repository to your local machine. </br>

Open the index.html file in any modern web browser (e.g., Chrome, Firefox, Edge). </br>

# Code Explanation </br>

## HTML (index.html) </br>

The main structure of the app, including: </br>

Input Display: A text input field to show the current calculation. </br>

Buttons: Buttons for numbers, operations, and special functions like AC and DEL. </br>

Pi Button: Adds the value of Pi (\u03C0 \u2248 3.14159) to the calculation. </br>

## CSS (style.css) </br>

The styling for the calculator, including: </br>

A centered layout with a gradient background. </br>

Styled buttons and a display field with consistent sizing and spacing. </br>

## JavaScript </br>

Embedded in the onclick attributes of buttons to provide functionality: </br>

Adding numbers and operators to the display. </br>

Evaluating the expression using eval() for the = button. </br>

Clearing the display or removing the last character. </br>

# Usage Instructions </br>

Enter Numbers and Operators: Click the numeric buttons (0-9) and operator buttons (+, -, *, /) to build your calculation. </br>

Pi Button: Use the π button to add the value of Pi to your calculation. </br>

Evaluate: Press = to compute the result. </br>

Clear Display: Use the AC button to reset the display. </br>

Delete Characters: Use the DEL button to remove the last entered character. </br>

# Example Calculations </br>

## Basic Calculation: </br>

Input: 7 + 3 </br>

Output: 10 </br>

## Using Pi: </br>

Input: \u03C0 * 2 </br>

Output: 6.28318530718 </br>

## Complex Expressions: </br>

Input: (10 / 2) + 3 * \u03C0 </br>

Output: 15.42477796076938 </br>

# Limitations </br>

The app uses the eval() function to evaluate expressions, which may pose security risks if extended to accept user-generated input. Use with caution in a production environment. </br>

Limited to basic arithmetic operations. </br>

# Recommendations </br>

Add support for advanced mathematical operations (e.g., square root, exponentiation). </br>

Implement keyboard input support for a seamless user experience. </br>

Refactor JavaScript to improve code structure and security. </br>

Add error handling for invalid expressions.
