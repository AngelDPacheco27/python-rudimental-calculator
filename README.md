Designed and Developed by Angel Pacheco, August 2024

Rudimental Python Calculator

A robust command-line interface (CLI) calculator built with Python that supports basic and advanced arithmetic operations. This project demonstrates clean functional programming, strict input validation, and loop-based logic for continuous calculations.  

&nbsp;  

🚀 **Features**:

**Comprehensive Operations**: Supports Addition, Subtraction, Multiplication, Division, Exponentiation, Modulus, and Floor Division.

**Input Validation**: Ensures the program doesn't crash by verifying that inputs are positive whole numbers and valid operation letters.

**Zero-Division Protection**: Includes a custom check to prevent mathematical errors when a user attempts to divide by zero.

**State Persistence**: Allows users to perform sequential operations on the previous result (e.g., 10 + 5 = 15 => 15 x 2 = 30).

**User-Friendly Flow**: Clear prompts and the ability to restart a fresh calculation or exit the program gracefully.

&nbsp;

🛠️ **Tech Stack**
**Language**: Python 3.x

**Environment**: VS Code

&nbsp;

🏗️ **Logic Flow**
The program follows a modular structure to ensure code reusability and readability:

**verify_num()**: Sanitizes user input to ensure only numeric values are processed.

**verify_oper()**: Maps user string input to specific mathematical functions.

**check_zero()**: A safety guard specifically for Division, Modulus, and Floor Division.

**calculate_ans()**: The core engine that processes the math based on the selected operator.

&nbsp;

💡 **Lessons Learned**
This project helped me solidify my understanding of:

**Nested While Loops**: Managing program state (restarting the app vs. continuing a calculation).

**Error Handling**: Proactively catching ZeroDivisionError scenarios before they occur.

**Input Sanitization**: Transforming string inputs into floats to ensure mathematical accuracy.

<!---
AngelDPacheco27/AngelDPacheco27 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
