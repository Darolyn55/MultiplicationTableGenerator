
---

# Multiplication Table Generator

A simple Java console application that generates and prints the multiplication table for a user-specified number.

## Features
- Prompts the user to input a number.
- Displays the multiplication table for the input number from 1 to 10.

## How to Run

1. **Ensure you have Java installed.**  
   You can check by running:
   ```bash
   java -version
   ```
   If Java is not installed, download it from [Oracle's website](https://www.oracle.com/java/technologies/javase-downloads.html) or install it via your package manager.

2. **Compile the program:**
   ```bash
   javac day6/MultiplicationTableGenerator.java
   ```

3. **Run the program:**
   ```bash
   java day6.MultiplicationTableGenerator
   ```

## Example Usage

```text
Enter a number to print its multiplication table
5
Multiplication Table for 5:
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

## Project Structure
```
day6/
└── MultiplicationTableGenerator.java
```

## Notes
- The program reads an integer from the user input.
- It uses a `for` loop to calculate and print the multiplication table up to 10.
- Basic input validation is not implemented; entering non-integer values will cause the program to crash.

