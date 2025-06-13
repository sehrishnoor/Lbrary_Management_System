
# 📚 Library Management System

This is a C++ console-based Library Management System developed as a semester project. It provides basic library functionalities such as adding books, borrowing and returning them, and displaying the current book list. The purpose of this project is to apply foundational C++ programming skills in a real-world scenario, using structured programming, user input, and data handling.

🧠 **Project Description**

The Library Management System allows users to:

Add a new book to the library by entering its name and author. The system ensures no duplicate books are added.

Borrow a book by providing the book title. If the book exists, it simulates borrowing by displaying a confirmation message.

Return a book by title. If the book exists in the system, it confirms the return.

View the entire collection of books available in the library along with their authors.

Initially, the system is preloaded with 10 popular books and their respective authors, which demonstrate how book records are handled.

🛠 **Technologies and Concepts Used**

Language:C++

Environment: Console

Core Concepts:

struct for defining book objects

Arrays to store multiple books

Functions for modularity

cin and getline() for user input

Loops and conditionals for menu-based interaction

Basic validation and error-checking

📚 **Sample Book Records Included**

The system starts with the following pre-added books:

The Lord of the Flies by William Golding

The Hunger Games by Suzanne Collins

The Game of Thrones by George R.R. Martin

The Alchemist by Paulo Coelho

The Hobbit by J.R.R. Tolkien

Abu Jinns by Ayesha Muzaffar

Sapiens by Yuval Noah Harari

Crime and Punishment by Fyodor Dostoevsky

Frankenstein by Mary Shelley

Great Expectations by Charles Dickens

🎯 **Objectives of the Project**

Strengthen understanding of C++ data structures and user input/output handling.

Demonstrate ability to build a simple yet functional program for a real-life use case.

Implement a user-friendly menu system and manage a dynamic book list.

Practice data validation, searching through arrays, and modular program design.

✅ **How It Works**

Once the program is executed, a menu is displayed offering the following options:

Add Book – Prompts for the name and author of a new book. If it doesn't already exist in the system, it is added to the library.

Borrow Book – Asks for the title of a book the user wants to borrow. If the book is found, a success message is shown.

Return Book – Requests the title of the book to return. If it exists in the system, a return confirmation is shown.

Display Books – Shows a list of all books and their authors currently stored in the system.

Exit – Ends the program.

Each action leads the user back to the main menu until they choose to exit.

🔮 **Possible Future Improvements**

While this project focuses on basic logic, several improvements could be added in the future:

Add a proper tracking system to differentiate between borrowed and available books.

Use file handling to store and retrieve books persistently across sessions.

Implement user roles (Admin and Member) with separate permissions.

Refactor code to use classes and object-oriented programming for better structure.

Introduce a graphical user interface (GUI) using frameworks like Qt or SFML for better usability.

📌 **Final Notes**

This Library Management System is a beginner-friendly C++ project that provides a strong foundation in logic building and structured programming. It can serve as a stepping stone to more advanced systems involving databases, file handling, and OOP.
