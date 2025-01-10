# FILE-HANDLING-UTILITY

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: PAYAL RAJESH TANGADKAR

**INTERN ID**: CT08GRQ

**DOMAIN**: JAVA PROGRAMMING

**BATCH DURATION**: January 5th, 2025 to February 5th, 2025

**MENTOR NAME**: NEELA SANTHOSH

**DESCRIPTION OF THE TASK**: 
The Task1 Java program demonstrates basic file operations using a menu-driven approach. It allows the user to interact with a text file through several options, including writing, reading, modifying the entire file, and modifying specific content within the file. This program showcases how Java’s standard I/O classes (BufferedWriter, BufferedReader, FileWriter, FileReader, and File) can be used to handle file operations effectively.

Program Overview and Tools Used
The main purpose of the program is to provide an interactive interface for file manipulation. Below are the primary tools and resources used in the program:

Java I/O Classes:
BufferedWriter and FileWriter: For writing text to the file, either appending or overwriting content.
BufferedReader and FileReader: For reading content from the file.
File: To check the existence of the file and handle file-related metadata.

Scanner Class:
This class is used for user input, allowing interaction with the program through a console-based menu.

Control Structures:
A while (true) loop to keep the menu running until the user decides to exit.
A switch statement to handle different menu choices.

Error Handling:
The program includes try-catch blocks to handle exceptions such as FileNotFoundException and IOException. These ensure the program doesn’t crash and provides meaningful error messages when something goes wrong (e.g., file not found or I/O operation fails).

Menu Options and Functionality
The program provides five options through a console menu. Each option corresponds to a specific file operation, as described below:

Write to File:
This option appends user-provided text to the file.
The program prompts the user to enter the text.
It uses BufferedWriter and FileWriter in append mode (FileWriter(filePath, true)) to add the content without overwriting the existing data.

Read from File:
Displays the content of the file on the console.
The program reads the file line by line using BufferedReader and FileReader.
If the file does not exist, it catches the FileNotFoundException and informs the user.

Modify Entire File:
Replaces the existing content of the file with new content provided by the user.
This is achieved by opening the file in overwrite mode (FileWriter(filePath, false)).
The old content is cleared, and only the new content is written.

Modify Specific Content:
Allows the user to replace all occurrences of a specific text in the file with a new text.
The program reads the entire file into a StringBuilder, replacing the target text using the String.replace() method.
The modified content is then written back to the file.

Exit:
Terminates the program gracefully by closing the Scanner and breaking out of the loop.

How the Output is Generated:

Program Startup
The program displays a menu in the console, prompting the user to choose from five file operation options.

User Input
The user enters a number corresponding to their desired operation (e.g., 1 for writing to a file, 2 for reading, etc.).

Menu Processing
The program uses a switch statement to execute the method associated with the selected option.

Option Details:

Option 1: Write to File
Prompts the user for text input.
Appends the input to the file using BufferedWriter.
Outputs a success message.

Option 2: Read from File
Reads the file line by line using BufferedReader.
Prints each line to the console.
If the file doesn’t exist, an error message is shown.

Option 3: Modify Entire File
Prompts the user for new content.
Overwrites the entire file with the new content using BufferedWriter.
Displays a success message.

Option 4: Modify Specific Content
Prompts the user for the text to replace and the new text.
Reads the file content, replaces the target text, and writes the modified content back to the file.
Outputs a success message.

Option 5: Exit
Closes the Scanner and terminates the program.

Error Handling
If an exception occurs (e.g., file not found or I/O error), the program prints an error message without crashing.

Loop Continuation
After executing an option, the menu reappears unless the user selects "Exit."

**OUTPUT OF THE CODE**
![Screenshot 2025-01-10 143456](https://github.com/user-attachments/assets/4969d584-12d7-49cc-a251-ef97214e1845)
![Screenshot 2025-01-10 143517](https://github.com/user-attachments/assets/6e20d281-4791-49c1-9ac7-924cba27069c)
![Screenshot 2025-01-10 143530](https://github.com/user-attachments/assets/ac1f4102-91ac-4eef-896d-62794c451584)



