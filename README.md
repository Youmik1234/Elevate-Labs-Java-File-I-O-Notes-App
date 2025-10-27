Objective

A simple text-based Notes Manager built in Java that demonstrates how to read and write files using FileWriter and BufferedReader.

Features

 Create and save notes directly from the terminal
 Read all saved notes anytime
 Data stored permanently in a notes.txt file
 Simple menu-driven CLI interface

Concepts Used

Java File I/O (FileWriter, FileReader, BufferedReader)

Loops and Conditional Statements

Exception Handling (try-catch)

User Input using Scanner

Modular programming with methods

Project Structure
NotesApp.java   → Main source code
notes.txt       → Automatically created file to store notes
README.md       → Project documentation

How to Run
1️ Clone this repository
git clone https://github.com/<your-username>/<your-repo-name>.git

2️ Navigate to the project folder
cd <your-repo-name>

3️ Compile the Java file
javac NotesApp.java

4️ Run the program
java NotesApp

Example Usage
===== Notes App =====
1. Write a Note
2. View Notes
3. Exit
Enter your choice: 1

Enter your note (type 'END' on a new line to finish):
Learned Java File Handling today.
FileWriter and BufferedReader are very useful!
END

Note saved successfully to notes.txt

💡 Future Enhancements

Add delete or search feature

Add date & time for each note

Save notes in different files by topic
