# Overview
The Multi-Tasker application is a versatile Java-based tool that integrates nine different functionalities. These include a Calculator, Password Generator, Puzzle Game, Tic Tac Toe Game, Word Counter Tool, IP Address Finder, Password Strength Checker, Source Code Generator, and an Exam System. This application provides a user-friendly interface to access these utilities from a single program.


## Table of Contents
1. Getting Started
2. Functionalities
  - Calculator
  - Password Generator
  - Puzzle Game
  - Tic Tac Toe Game
  - Word Counter Tool
  - IP Address Finder
  - Password Strength Checker
  - Source Code Generator
  - Exam System
3. Usage
4. Clearing the Screen


## Getting Started
To run the Multi-Tasker application, ensure you have Java installed on your system. Compile and run the multi_tasker class to access the menu-driven interface.

## Functionalities
###Calculator
The Calculator provides basic arithmetic operations. To use the Calculator, select option 1 from the menu.

###Password Generator
The Password Generator creates strong, random passwords. Select option 2 from the menu to use this feature.

###Puzzle Game
Engage in a fun Puzzle Game by selecting option 3 from the menu.

###Tic Tac Toe Game
Play the classic Tic Tac Toe game by selecting option 4. This will initiate the Tic Tac Toe game.

###Word Counter Tool
Count the number of words in a given text by selecting option 5 from the menu.

###IP Address Finder
Find your IP address by selecting option 6 from the menu.

###Password Strength Checker
Check the strength of a password by selecting option 7 from the menu.

###Source Code Generator
Generate source code snippets by selecting option 8 from the menu.

###Exam System
Take an exam using the Exam System by selecting option 9 from the menu.


## Usage
1. Run the Multi-Tasker application.
2. Read the instructions displayed on the screen.
3. Enter the number corresponding to the functionality you wish to use.
4. Follow the prompts for the selected functionality.


## Clearing the Screen
The application includes a method to clear the console screen. This is useful for maintaining a clean and readable interface.
```
public static void clearScreen() {
    try {
        new ProcessBuilder("cmd", "/c", "cls").inheritIO().start().waitFor();
    } catch (Exception e) {
        System.out.println(e);
    }
}
```
