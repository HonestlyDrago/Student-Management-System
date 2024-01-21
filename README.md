**Overview**

This student record management system (SRMS) is a C++ program designed to manage student data effectively. It enables users to add, display, modify, search for, and delete student records. It utilizes a text file ("student_records.txt") to store student information persistently.

**Key Features**

User-friendly interface: Menu-based system for easy interaction.
Data validation: Verifies email addresses and contact numbers before entry.
Authentication: Requires a username and password for access (consider security enhancements).
Basic CRUD operations: Create, read, update, and delete student records.
**Installation**

Ensure a C++ compiler (e.g., Clang, GCC) is installed on your system.
Create a new C++ project and copy the provided code into a .cpp file.
Include necessary header files (mentioned in the code).
Build and run the project.
Code Structure

** Using Classes**

student: Models a student object, storing attributes like name, roll_no, course, email_id, contact_no, and address.
Public member functions:
menu(): Launches the main menu for interaction.
insert(): Adds a new student record.
display(): Presents all student records.
modify(): Edits an existing student record.
search(): Finds a student record based on roll_no.
deleted(): Removes a student record.
Functions

Emailcheck(string email): Validates email addresses using a regular expression.
main(): Entry point of the program. Creates a student object and initializes the system.
**Data Storage**

student_records.txt: Text file where student data is stored.
Authentication

The program requires a username and password to access the menu.
Important Security Note: Hardcoded credentials are not secure. Employ robust authentication mechanisms for production use.
**User Guide**

Run the program.
Provide the correct username and password (prompted at start).
Choose options from the menu using corresponding numbers:
Add New Student
Show All Students
Modify Student
Search Student
Remove Student
Exit

**CONTRIBUTORS**
23-NTU-CS-1241   ABDULLAH AHMAD
23-NTU-CS-1278   RAJA MUHAMMAD AYYAZ
23-NTU-CS-1241   MUHAMMAD BILAL

