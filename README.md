Name : RAJ PATIL 
compony : CODTECH IT SOLUTIONS 
ID : CT4PP2843
Domain : Python Programming
Duration: JUNE to JULY 2024 
Mentor : Neela santosh kumar
Project Overview: Simple Grade Calculator
Objective:
The objective of this project is to create a simple command-line application in Python that allows users to calculate and display grades based on input marks for a student's subjects.

Key Features:

Clear Screen Functionality:

Uses os.system to clear the console screen, providing a clean interface for user interaction.
Menu-Driven Interface:

Presents a menu with two options:
Option 1: Calculate grades
Option 2: Exit
Calculate Grades Functionality:

Prompts the user to enter the student's roll number, name, and number of subjects.
Allows the user to input grades for each subject.
Calculates the total marks and percentage.
Determines the grade based on predefined grade boundaries (A+, A, B+, B, C+, C, FAIL).
User Interaction:

After calculating grades or choosing to exit, prompts the user to press Enter to continue.
Input Handling and Validation:

Ensures inputs are validated (e.g., numeric roll number, valid grades).
Handles errors gracefully (e.g., division by zero for percentage calculation).
Exit Functionality:

Allows the user to exit the program cleanly.
Implementation Details:
Modules Used: Utilizes the os module for clearing the screen and basic input/output functions (input, print) for user interaction.

Main Function (main()):

Executes an infinite loop (while True:) to keep the program running until the user chooses to exit (break statement).
Clears the screen using clear_screen() at the start of each loop iteration.
Displays a menu and processes user input to perform the desired action (calculate grades or exit).
Calculate Grades Function:

Collects student details and subject grades via user input.
Computes the total marks, calculates the percentage, and determines the corresponding grade.
Prints a detailed summary of the student's information and their grades.

Conclusion:
This simple grade calculator project provides a foundational example of basic Python programming concepts such as functions, loops, conditional statements, and input/output operations. It demonstrates how to create an interactive application that performs educational calculations while providing clear feedback and maintaining a user-friendly interface.
