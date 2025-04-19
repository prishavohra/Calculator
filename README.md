# Java Calculator

Welcome to my basic **Java Calculator** project! This program lets users perform simple mathematical operations with a clean console menu interface. It also handles edge cases using **exception handling** like a 

Project Structure

This project includes the following classes, each dedicated to a specific mathematical operation:

- `Addition.java` – Adds two numbers
- `Subtraction.java` – Subtracts one number from another
- `Multiplication.java` – Multiplies two numbers
- `Division.java` – Divides one number by another (handles division by zero)
- `Square.java` – Calculates the square of a number
- `Cube.java` – Calculates the cube of a number
- `SquareRoot.java` – Computes the square root (handles negatives)
- `Main.java` – Brings everything together with a menu-driven interface

## 🛠 How It Works

1. Launches a console menu on startup.
2. User selects an operation from the list.
3. Inputs are taken via `Scanner`.
4. Relevant class method is invoked.
5. Displays the result, and loops until exit.

### Example Menu:

```text
===== Calculator Menu =====
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Square
6. Cube
7. Square Root
8. Exit
