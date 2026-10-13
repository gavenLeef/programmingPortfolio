
# [Gaven's Calculator]
![Calculator](https://github.com/gavenLeef/programmingPortfolio/blob/main/images/Calc.png?raw=true)
## Overview
[I have built a graphical calculator equipped with a digital display and an interactive button layout. Users can perform standard addition, subtraction, multiplication, and division along with additional functions like square roots, sine calculations, and sign toggles. this calculator allows users to operate the it either by clicking on screen buttons with a mouse or by typing directly on the keyboard.]

## Current Status
Working:
- [Basic arithmetic operations: Addition (+), Subtraction (-), Multiplication (×), and Division (÷).]
- [Special function operations: Clear (C), Sign Toggle (±), Square Root (√), and Sine in degrees (s).]

Still in progress:
- [Still working on coding in the decimal input.]

## How to Run
Built with Processing.
Processing version: [4.5.6]

[After the project files are uploaded, identify the
project folder and main .pde file to open and run.]

## Controls
Mouse:
[+ , - , × , ÷ Buttons: Set the active arithmetic operator and prepare for right-operand entry.= Button: Triggers calculation and prints the calculated result.C Button: Resets left operand, right operand, operator, and display back to 0.0.± Button: Inverts the sign (+ / -) of the active operand.√ Button: Calculates the square root of the active operand.s Button: Calculates sine (converting active value from degrees to radians).. Button: Decimal point button (currently pending logic implementation).]

Keyboard:
[Every key viable from the keyboard works in the program.]

## Project Files
[Calculator.PDE
Button.PDE]

## Testing
[Testing the calculators arithmatic functions and keyboard use.]

## Next Step
[Implement decimal point processing inside handleEvent so pressing . allows floating point entries like 3.14, and add keyboard binding for the period key in keyPressed.]
