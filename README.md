#Project Description: Student Database Management System (SQLite)

This project is a menu-driven Student Database Management System developed using Python and SQLite.
It allows the user to store, search, insert, and delete student records from a database using simple keyboard inputs.

The program connects to an SQLite database named Student_data.db and performs operations on a table called moiz.

⚙️ Features of the Project

The system runs continuously using a loop-based menu and provides the following options:

🔹 1. Fetch student by Roll Number

User enters a roll number

The program retrieves and displays the corresponding student record from the database

🔹 2. Fetch student by Name

User enters a student name

The program searches the database and shows the matching record

🔹 3. Add New Student Record

User enters:

Name

Roll Number

Subject

Email

The data is inserted safely into the database using parameterized queries

🔹 4. Delete Student Record

User enters a roll number

The corresponding student record is deleted from the database

🔹 5. Exit Program

The program terminates safely and closes the database connection

🧠 Technical Concepts Used

SQLite Database (sqlite3)

Cursor and SQL Queries

Parameterized Queries (SQL Injection Safe)

Loops and Menu-Driven Programming

match-case (Python switch statement)

Exception-free controlled input flow

✅ Conclusion

This project demonstrates how Python can be used with SQLite to create a real-world database application.
It is suitable for beginners and helps in understanding CRUD operations (Create, Read, Delete) in databases.
