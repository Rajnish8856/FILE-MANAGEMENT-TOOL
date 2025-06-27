# FILE MANAGEMENT TOOL
*COMPANY NAME*:CODTECH IT SOLUTIONS
*NAME*:RAJNISH
*INTER ID*:CT04DF209
*DOMAIN NAME*:C++
*DURATION*:4 WEEKS
*MENTOR*:NEELA SANTOSH KUMAR
#DESCRIPTION OF CODE
The File Management Tool is a simple yet functional C++ console-based application that allows users to perform basic file operations such as writing, reading, and appending data to text files. This program serves as an introduction to file handling in C++, demonstrating the use of input/output file streams, user interaction, and basic control flow.

Purpose and Functionality
The main goal of this tool is to help users manage text files without needing a graphical user interface or external tools like text editors. The program prompts the user to select an action—write, read, or append—to a specified file. Based on the user's choice, it performs the corresponding file operation:

Write to a File:
This option allows the user to write a new line of text to a file. If the file already exists, its content will be overwritten. This is useful for replacing old data or starting a new document.

Read from a File:
This feature reads the contents of an existing file line by line and displays them on the console. It is particularly useful for verifying file contents or retrieving stored information.

Append to a File:
If the user chooses this option, the program allows additional text to be added to the end of the existing file without removing its previous content. This is helpful for adding notes or updating logs.

Each operation checks if the file can be successfully opened. If there is an error, such as the file not existing or permission being denied, the program informs the user accordingly.

Key Components and Structure
The program is structured into three core functions:

writeFile()

readFile()

appendFile()

Each function takes a filename as an argument and performs a specific task using file streams from the <fstream> header. It also includes input/output operations using <iostream> and string handling via <string>.

The main() function acts as the control center of the application. It displays a menu, takes the user's choice, asks for the filename, and then calls the appropriate function using a switch statement. The user must enter the filename with a .txt extension, which the program then uses to open or create the file.

A notable implementation detail is the use of getline() for reading user input. This allows the user to enter full lines with spaces, unlike cin, which stops at whitespace. Additionally, cin.ignore() is used to handle leftover newline characters in the input buffer, ensuring correct input behavior.

Strengths and Usability
The program is simple, clear, and beginner-friendly. It provides direct feedback to the user after every operation, making it easy to understand whether the file handling was successful. The use of standard C++ libraries ensures compatibility and portability.

Furthermore, the modular design makes the code easy to maintain and extend. New features, such as deleting a file, renaming a file, or searching text within a file, could be added with minimal restructuring.

Possible Improvements
While the program works effectively, it has some limitations. Currently, the application exits after performing one operation. Adding a loop to allow multiple operations without restarting the program would improve usability. Input validation could also be strengthened to ensure only valid choices and filenames are accepted. Adding error logging or file existence checks could further enhance reliability.

In addition, a graphical user interface (GUI) could be introduced for a more user-friendly experience, although that would require more advanced C++ libraries like Qt or wxWidgets.

Conclusion
The File Management Tool is a practical application that demonstrates essential file handling in C++. It provides a hands-on example of how to interact with the file system, manage user input, and handle common programming tasks. With a few enhancements, this tool can serve as the foundation for more advanced file management software.
OUTPUT
![Image](https://github.com/user-attachments/assets/b2debb49-b400-44a4-bf6b-a191cbc95e26)
