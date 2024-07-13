# Password_Generator
This is a Java-based Password Generator and Strength Checker. The system allows users to generate secure passwords based on user-defined criteria and evaluate the strength of existing passwords. The program features a command-line interface for user interaction.

1. Features :
    1) Password Generator: Users can generate passwords based on specific criteria such as including uppercase letters, lowercase letters, numbers, and special characters. The user can also specify the desired length of the password.
    2) Password Strength Checker: Users can check the strength of an existing password based on its length and the variety of character types included.
    3) Useful Information: Provides guidelines for creating strong passwords.
    4) User-Friendly Interface: Simple command-line interface to interact with the system.

2. Technologies Used :
    1) Java: The primary programming language used for the application.
    2) Scanner: Used for taking user inputs from the command line.

3. File Structure :
    1) Alphabet.java: Defines the character sets used for generating passwords (uppercase, lowercase, numbers, symbols) and allows customization of these sets.
    2) Generator.java: Manages user interactions, including generating passwords and checking password strength.
    3) Password.java: Represents a password and includes methods to evaluate its strength.
    4) Main.java: The entry point of the application, starting the command-line interface.

4. User Interface :
    The Generator class provides a command-line interface with the following options:

    1) Password Generator: Prompts the user to specify password criteria and generates a password.
    2) Password Strength Check: Checks the strength of a user-provided password.
    3) Useful Information: Displays guidelines for creating strong passwords.
    4) Quit: Exits the application.

5. License :
This project is licensed under the MIT License.
