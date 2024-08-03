Here's a concise documentation for the provided code:


# Overview

This C++ program performs basic arithmetic operations on two integers based on user input. It defines a `BasicMath` class with methods for addition, subtraction, multiplication, division, and modulus operations. The user interacts with the program through the console to select an operation and input numbers.


# `BasicMath` Class

Methods:
  - `int addnum(int x, int y)`
    - **Description:** Returns the sum of `x` and `y`.
  - `int subnum(int x, int y)`
    - **Description:** Returns the difference between `x` and `y`.
  - `int multnum(int x, int y)`
    - **Description:** Returns the product of `x` and `y`.
  - `int divnum(int x, int y)`
    - **Description:** Returns the quotient of `x` divided by `y`. If `y` is zero, it outputs "Invalid Numbers."
  - `int modnum(int x, int y)`
    - **Description:** Returns the remainder of `x` divided by `y`.

# `main` Function

Description
  - Prompts the user to input two integers and select a mathematical operation.
  - Based on the user’s choice, it calls the appropriate method from the `BasicMath` class to perform the operation and displays the result.

  Inputs:
  - Two integers: `x` and `y`.
  - A character to select the operation:
    - `A` for addition
    - `S` for subtraction
    - `M` for multiplication
    - `D` for division
    - `G` for modulus

  Outputs:
  - Result of the chosen arithmetic operation.
  - If division is selected and either `x` or `y` is negative, it outputs "Invalid Numbers."
  - If an invalid operation choice is entered, it outputs "Invalid Choice."

