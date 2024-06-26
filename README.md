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
### Calculator
The Calculator provides basic arithmetic operations. To use the Calculator, select option 1 from the menu.
The Calculator application allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, division, exponentiation, remainder calculation, and square rooting.
*Usage*
1. Run the application.
2. Enter two numbers.
3. Select the operation to perform from the following options:
  - '+' for addition
  - '-' for subtraction
  - '*' for multiplication
  - '/' for division
  - '^' for power
  - '%' for remainder
  - '~' for square rooting (only uses the first number)
4. The result will be displayed.
*Key Features*
- Supports multiple arithmetic operations.
- Simple text-based user interface.

### Password Generator
The Password Generator creates strong, random passwords. Select option 2 from the menu to use this feature.
The Password Generator application generates a strong, random password of a specified length.
*Usage*
1. Run the application.
2. The application will generate and display a password of the specified length (default length is 8).
*Key Features*
- Generates a random password containing uppercase and lowercase letters, numbers, and special characters.
- Ensures the generated password meets standard security criteria.

### Puzzle Game
Engage in a fun Puzzle Game by selecting option 3 from the menu.
The Password Generator application generates a strong, random password of a specified length.
*Usage*
1. Run the application.
2. The application will generate and display a password of the specified length (default length is 8).
*Key Features*
- Generates a random password containing uppercase and lowercase letters, numbers, and special characters.
- Ensures the generated password meets standard security criteria.

### Tic Tac Toe Game
Play the classic Tic Tac Toe game by selecting option 4. This will initiate the Tic Tac Toe game.
The Tic Tac Toe Game application allows two players to play the classic Tic Tac Toe game.
*Usage*
1. Run the application.
2. Players take turns entering the coordinates for their move.
3. The game checks for a win or a tie after each move.
4. The game ends when a player wins or all cells are filled.
*Key Features*
- Two-player game.
- Simple text-based user interface.
- Checks for win conditions and displays the winner.

### Word Counter Tool
Count the number of words in a given text by selecting option 5 from the menu.
The Word Counter application counts the number of words, characters, and lines in a given text file.
*Usage*
1. Run the application.
2. Select the text file for which you want to count the words, characters, and lines.
3. The application will display the total number of words, characters, and lines in the file.
*Key Features*
- Reads a text file and counts the number of words, characters, and lines.
- Provides a summary of the counts.
- Simple text-based user interface.

### IP Address Finder
Find your IP address by selecting option 6 from the menu.
The IP Finder application allows users to find the IP address of a given website URL.
*Usage*
1. Run the application.
2. Enter the website URL in the provided text field.
3. Click the "Find IP" button.
4. The application will display the IP address of the entered URL.
*Key Features*
- GUI-based application using Swing.
- Retrieves and displays the IP address of a website.

### Password Strength Checker
Check the strength of a password by selecting option 7 from the menu.
The Password Strength Checker application evaluates the strength of a given password based on various criteria.
*Usage*
1. Run the application.
2. Enter the password to be checked.
3. The application will evaluate the password and categorize it as "strong", "moderate", or "weak" based on the criteria.
*Key Features*
- Checks for uppercase and lowercase letters, numbers, special characters, and length.
- Provides feedback on how to improve a weak password.

### Source Code Generator
Generate source code snippets by selecting option 8 from the menu.
The Source Getter application fetches and displays the HTML source code of a given website URL.
*Usage*
1. Run the application.
2. Enter the website URL in the provided text field.
3. Click the "Get Source Code" button.
4. The application will display the HTML source code of the entered URL.
*Key Features*
- GUI-based application using Swing.
- Retrieves and displays the HTML source code of a website.

### Exam System
Take an exam using the Exam System by selecting option 9 from the menu.
The Exam System application is a simple quiz program that asks users multiple-choice questions and evaluates their answers.
*Usage*
1. Run the application.
2. Answer the displayed multiple-choice questions by typing the corresponding option (e.g., a, b, c, or d).
3. After all questions are answered, the application will display your score.
*Key Features*
- Predefined set of multiple-choice questions.
- Evaluates user responses and calculates the score.


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
