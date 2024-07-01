NAME : SARTHAK SINGH NEGI
Organisation Name :	CODTECH IT SOLUTIONS
ID : CT12PD161
DOMAIN : PYTHON PROGRAMMING
DURATION : 14th MAY to 1st JULY
MENTOR : SRAVANI GOUNI

Project Overview: Simple Calculator GUI

1. Introduction:
Objective: Develop a graphical user interface (GUI) application using Python's tkinter library for a simple calculator.
Functionality: Allow users to perform basic arithmetic operations (addition, subtraction, multiplication, division) and clear/reset calculations.

2. Features:
Entry Widget (self.entry): Displays the current input and results of calculations.
Numeric Buttons: 0-9 for entering numbers.
Operation Buttons: +, -, *, / for arithmetic operations.
Other Buttons: Decimal point (.), equals (=) to calculate the result, clear (Clear) to clear the input, and delete (Del) to delete the last character.
Error Handling: Displays "Error" in self.entry if an invalid expression is entered (e.g., division by zero).

3. Implementation Details:
Class Structure: Utilizes a single class SimpleCalculator encapsulating all GUI elements and logic.
Initialization (__init__ method):
Sets up the tkinter window (root) with a title ("Simple Calculator").
Creates an Entry widget (self.entry) for input/output display.
Initializes buttons (self.buttons) for numbers, operations, and special functions (clear and delete).
Button Click Handling (click method):
Responds to button clicks by appending the clicked button's text to self.entry for numeric and operation buttons.
Evaluates the expression in self.entry and displays the result using eval() when '=' button is clicked.
Handles errors (e.g., division by zero) with a try-except block and displays "Error" in self.entry.
Utility Methods:
clear(self): Clears the contents of self.entry.
delete(self): Deletes the last character from self.entry.

4. Usage:
Launch the application by running the Python script.
Enter numbers using numeric buttons.
Perform calculations by clicking operation buttons (+, -, *, /).
Use equals (=) button to compute and display the result.
Clear (Clear) button resets the input field, and delete (Del) button removes the last character.

5. Potential Enhancements:
Input Validation: Implement stricter validation to prevent invalid input (e.g., characters other than numbers and operators).
Memory Functions: Add memory storage (M+, M-, MR) for storing and recalling numbers.
Scientific Calculator: Extend functionality to include advanced operations like trigonometric, logarithmic functions, etc.
Improved UI/UX: Enhance the visual design, layout, and responsiveness of the calculator interface.

6. Conclusion:
The Simple Calculator GUI provides a straightforward tool for performing basic arithmetic operations through a user-friendly interface. It showcases fundamental GUI programming skills using Python's tkinter library and serves as a starting point for more complex calculator applications.
