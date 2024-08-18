
# Library Management System

## Introduction

The Library Management System is a Python-based program that provides an efficient way to manage a library's book inventory, including issuing, returning, adding, removing, and modifying books. The system supports two types of users: faculty and students, each with their own set of functionalities.

## Features

- **User Authentication:**  
  Faculty and student users must log in with their credentials.
  
- **Book Management:**  
  - Faculty can add, remove, and modify books in the library.
  - Both faculty and students can issue and return books.
  
- **Search and Display:**  
  - Search for books by title, author, or subject.
  - Display available books sorted by title or author.

- **Error Handling:**  
  - The program handles invalid login attempts and provides user-friendly error messages.

## Usage

1. **Start the Program:**
   - Run the program to start the Library Management System.
   - Choose between faculty or student login.

2. **Faculty Options:**
   - After logging in, faculty can issue books, add new books, remove existing books, modify book details, search for books, display available books, and return books.

3. **Student Options:**
   - After logging in, students can issue books, search for books, display available books, and return books.

4. **Exiting:**
   - Choose the "Exit" option from the menu to close the program.

## Program Structure

- `LibraryManagementSystem`: The main class that manages the entire library system.
  - **Methods:**
    - `__init__()`: Initializes the system with sample users and books.
    - `faculty_login()`: Handles faculty login attempts.
    - `student_login()`: Handles student login attempts.
    - `authenticate_faculty()`, `authenticate_student()`: Verify user credentials.
    - `issue_book()`: Issues a book to a user.
    - `add_book()`: Adds a new book to the library.
    - `remove_book()`: Removes a book from the library.
    - `modify_book()`: Modifies book details.
    - `return_book()`: Returns a book to the library.
    - `search_books()`: Searches for books in the library.
    - `sort_books()`: Sorts books by title or author.
    - `display_books()`: Displays available books.
    - `start()`: Starts the system and displays the menu.

## Dependencies

This program is built using Python and does not require any external libraries.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear and concise messages.
4. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

