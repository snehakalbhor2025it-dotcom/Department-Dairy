## 📘 Department Diary Management System (C Program)

A simple and efficient Department Diary Management System written in C, designed to store, view, search, and delete diary entries using file handling. This project is useful for beginners who want to learn file operations in C, menu-driven programs, and basic string handling.

🚀 Features
✔ Add Entry

Allows the user to add a diary entry.
Each entry is stored in a file (diary.txt) with a separator line for clarity.

✔ View Entries

Displays all diary entries from the diary file.

✔ Search Entry

Searches entries based on a keyword entered by the user.
Displays all matching lines that contain the keyword.

✔ Delete Entry

Deletes an entry using a keyword.
The program creates a temporary file to remove matching entries safely.

✔ Menu-Driven System

Easy navigation through a clear text-based menu.

📂 File Structure
📁 Department-Diary
 ├── diary.txt      # Automatically created; stores entries
 ├── main.c         # Source code
 └── README.md      # Project documentation

 Concepts Used

File handling (fopen, fclose, fprintf, fgets, fgetc, remove, rename)

String operations (strstr, strcspn)

Loops and conditional statements

Menu-driven programming

🖥 How to Run

Save the code as main.c

Compile:

gcc main.c -o diary


Run:

./diary

📌 Sample Menu
===== Department Diary =====
1. Add Entry
2. View Entries
3. Search Entry
4. Delete Entry
5. Exit
Choose an option:

 Purpose

This project is ideal for:

College practicals

EEL/Programming laboratory submissions

Students learning file handling

Beginners exploring small C-based applications# Department-Dairy
