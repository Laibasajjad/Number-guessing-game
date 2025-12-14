# Number Guessing Game – COAL Semester Project

**Author:** Laiba Sajjad

**Course:** Computer Organization and Assembly Language (COAL)

**Project Type:** Assembly Language (MASM)

**Library Used:** Irvine32.inc



## Project Overview

The **Number Guessing Game** is implemented in **MASM Assembly Language** for the COAL course. This project demonstrates fundamental concepts of **assembly programming**, including:

* Procedure calls and modular design
* Stack usage and parameter passing
* Loops and conditional branching
* Console input/output using the **Irvine32** library

The game allows the user to **guess a randomly generated number** within a limited number of attempts, providing feedback after each guess. It also tracks the **history of guesses**, illustrating how data is managed at the assembly level.



## Features

* **Random Number Generation:** Generates a secret number using the `GenerateNumber` procedure.
* **User Input Handling:** Prompts the user to enter guesses via the console.
* **Guess Checking:** Compares the user input with the secret number and provides feedback (too high, too low, or correct).
* **Life/Attempt Tracking:** Limits the number of guesses; the game ends when attempts run out.
* **Guess History:** Stores all guesses in memory, demonstrating stack and array handling.
* **Stack Demonstration:** Clearly shows how parameters and local variables are pushed to and popped from the stack.



## Learning Outcomes

By completing this project, you will learn:

1. How to use the **stack for parameter passing** and local variable storage.
2. How to write **modular assembly code** using procedures.
3. How to implement **loops and conditional branching** in assembly.
4. How to interact with the console using the **Irvine32 library**.
5. How to debug assembly programs and analyze **stack behavior** step by step.



## Prerequisites

* **MASM32** or **Visual Studio** with MASM support
* **Irvine32.inc** library
* Basic knowledge of x86 assembly and stack operations



## Files in the Repository

* `NumberGuessingGame.asm` – Main source code
* `Coal Project Report.pdf` – Project report
* `.vs/` – Visual Studio project files (optional, can be ignored)
* `Debug/` – Compiled binaries (optional)


## How to Run

1. Open the project in **MASM-compatible IDE** (e.g., Visual Studio).
2. Assemble and link the program.
3. Run the executable.
4. Enter your guesses when prompted.
5. Try to guess the number before your attempts run out.



## GitHub Repository

[Number Guessing Game Repository](https://github.com/Laibasajjad/Number-guessing-game)



## Future Improvements(you may implement)

* Add difficulty levels (easy, medium, hard) with varying ranges.
* Store multiple players’ scores and display a leaderboard.
* Add graphical interface using Windows API (optional for advanced users).



## License

This project is **for educational purposes** and **COAL semester assignment**. You may freely use it as a reference, but credit the author.
