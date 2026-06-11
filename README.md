# Library Management System

A simple Python library management system that demonstrates core operations for managing books and members.

## Overview

This project implements a small in-memory library system with the following components:

- `Book` class: represents a book in the library
- `Member` class: represents a library member
- `Librarian` class: a subclass of `Member` for future extension
- `Library` class: manages book storage, borrowing, returning, and availability tracking

## Features

- Add new books to the library
- Display all library books
- Check whether a book is available
- Borrow a book if it is available
- Return a borrowed book
- Track the current status of all books

## Running the project

Run the script using Python from the project directory:

```bash
python Library_management_system.py
```

The script includes example usage of adding books, checking availability, borrowing, returning, and tracking book status.

## Example behavior

The current example flow in `Library_management_system.py`:

1. Adds four books: Python, Java, C++, HTML
2. Shows available books
3. Checks availability for `CSS` and `Python`
4. Borrows `Python` and `HTML` for two members
5. Checks availability for `Python` again
6. Returns `Python`
7. Displays the borrow status for all books

## Notes

- This is an in-memory implementation and does not persist data between runs.
- The current script is designed for demonstration and can be expanded with user input, file persistence, or a command-line interface.
