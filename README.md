Name: Ballewar Janhvi Devendra
Domain: Full Stack Web Development
Duration: 25th July to 25th September 2024
Task Name: Develop a calculator using JavaScript, HTML, CSS

OUTPUT: 
<img width="960" alt="mainflowtask4 calculator" src="https://github.com/user-attachments/assets/8381450e-ca76-4c9a-8313-0d950e160431">

OVERVIEW OF THE TASK:
To build a basic calculator with a user-friendly interface that performs arithmetic operations like addition, subtraction, multiplication, and division.

Key Responsibilities:
Frontend Development using HTML and CSS:
1.HTML: Structure the calculator layout with buttons for digits (0-9), arithmetic operators (+, -, *, /), and functions (clear, delete, decimal, equals).
CSS: Style the calculator to make it visually appealing and responsive. CSS defines the size, spacing, colors, and hover effects of the buttons and the display area.

2.JavaScript for Calculator Logic:
Appending Numbers and Operators: Functions to append numbers and operators to the display.
Handling Special Operations: Functions to handle clearing the display (C), deleting the last character (DEL), and appending a decimal point.
Performing Calculations: A function to evaluate the expression and display the result, handling errors gracefully.

Components and Code Structure:
HTML Layout:
The <div class="calculator"> contains the entire calculator.
An <input> element represents the display area where the input and output are shown.
<button> elements for numbers, operators, and functionalities like C, DEL, . (decimal), and = (equals).

CSS Styling:
Uses CSS Grid to organize the buttons into a 4x5 layout.
Basic styles for buttons and the display input field.
Hover and active states for better user interaction feedback.

JavaScript Logic:
Functions like appendNumber(), appendOperator(), clearDisplay(), deleteChar(), appendDecimal(), and calculateResult() control the behavior of the calculator.
Uses eval() to evaluate mathematical expressions. While eval() is convenient for small-scale tasks, it's used cautiously and with basic input sanitization to prevent any security issues.

Execution:
Combine HTML, CSS, and JavaScript into a single HTML file.
Open the file in a web browser to see the calculator in action.
Users can click buttons to perform calculations and see results instantly.

Benefits of this Approach:
Simplicity: Keeping everything in one file makes it easy to manage and test.
Compact Codebase: Ideal for quick prototyping and learning purposes.
Accessibility: Works on any modern web browser without additional setup.

SUMMARY:
This task provides a foundational understanding of web development by integrating HTML, CSS, and JavaScript to create a functional application.
