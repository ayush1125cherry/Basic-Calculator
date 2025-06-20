# Basic-Calculator
"calculator using html,css and js"

COMPANY: CodTech IT Solutions
NAME: Ayush Rawat
INTERN ID: CS25RY62853
DOMAIN: Web Development
DURATION: 4 Weeks
MENTOR: Neela Santosh

#Description About the Task
Task number 3
I have created a basic calculator using HTML, CSS, and JavaScript. The calculator features an interactive interface with buttons for addition, subtraction, multiplication, and division operations. It also includes decimal input, backspace functionality, and numeric buttons from 0 to 9, with an additional "00" button for convenience.
To enhance usability, I implemented keyboard support using JavaScript, allowing users to input numbers and operations via their keyboard. The project was developed using VS Code as the primary code editor.

index.html Description
The HTML structure begins with the basic boilerplate code, linking both the JavaScript (app.js) and CSS (style.css) files. Inside a calculator class, I created an input field for the display. Under a button class, I added all the necessary buttons, including:
Numbers (0-9 and 00)
Decimal point (.)
Backspace
Basic arithmetic operations (+, -, *, /)
Each button has an onClick attribute that triggers corresponding functions in app.js.

style.css Description
This file contains all the styling rules to make the calculator visually appealing and user-friendly.

app.js Description
The JavaScript file includes two main functions:
toDisplay() – Handles input display logic, including clearing the screen, backspacing, and preventing consecutive operations.
calculate() – Computes and displays the result of the arithmetic operations.
Additionally, an eventListener with keydown is implemented to enable keyboard input for numbers and operations

#Tools and Technologies Used
VS Code:
Primary code editor for writing HTML, CSS, and JavaScript.
HTML5:
Structured the calculator layout (buttons, display input).
CSS3:
Styled the calculator (grid layout, hover effects, responsive design).
JavaScript :
Implemented core functionalities:
toDisplay(): Handles input logic (clearing, backspace, operator validation).
cal(): Evaluates expressions using eval().
Keyboard support via keydown event listener.
Browser Developer Tools:
Used for debugging and testing responsiveness.

#Output 
![Image](https://github.com/user-attachments/assets/71465f23-2da2-4f16-996e-bc4d469716e4)
