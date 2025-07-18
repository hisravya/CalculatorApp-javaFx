# CalculatorApp-javaFx
# Calculator-APP
A simple command-line Java application for performing basic arithmetic operations: addition, subtraction, multiplication, and division.
## Features
* Menu-driven interface
* Supports:
  * Addition
  * Subtraction
  * Multiplication
  * Division
* Input handling via `Scanner`
* Loop continues until user chooses to exit
## Requirements
* Java JDK 8 or later
## How to Run
1. **Compile the source code**
   ```bash
javac --module-path javafx-sdk-21.0.7\lib --add-modules javafx.controls,javafx.fxml javafx1\CalculatorApp.java
   ```
2. **Run the application**
   ```bash
java --module-path javafx-sdk-21.0.7\lib --add-modules javafx.controls,javafx.fxml javafx1.CalculatorApp.
   ```   
3. **Follow on-screen menu**
   Example:
   ```
   1. Add
   2. Subtract
   3. Multiply
   4. Divide
   5. Exit
   ```
## 📁 File Structure
```
CalculatorApp.java   # Main application source file
```
