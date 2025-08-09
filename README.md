# Python-OOP-Library-Management-System

A simple Object-Oriented Programming (OOP) based library management system built in Python.
This project demonstrates how to design and implement a library system with classes, methods, and attributes, while enforcing borrowing limits and book availability rules.

## Features

- Add Books to the library with title, author, and ISBN.
- Register Members with unique IDs.
- Borrow Books (limit of 3 books per member).
- Return Books to the library.
- Check Availability before borrowing.
- Search Books by title.
- Display All Books with availability status.

## Classes & Methods

## 1. Book
Represents a book in the library.
### Attributes:

- title (str) – Book title.
- author (str) – Book author.
- isbn (str) – ISBN number.
- available (bool) – True if available, False if borrowed.

### Methods:

__str__ – String representation showing book details and availability.

## 2. Member
Represents a library member.
### Attributes:

- name (str) – Member’s name.
- member_id (str) – Unique member ID.
- borrowed_books (list) – Books borrowed by the member.

### Methods:

- borrow_book(book) – Borrow a book if available and limit not exceeded.
- return_book(book) – Return a borrowed book.

## 3. Library
Manages books and members.
### Attributes:

- books (list) – All books in the library.
- members (list) – All registered members.

### Methods:

- add_book(book) – Add a new book to the library.
- register_member(member) – Register a new member.
- find_book_by_title(title) – Search for books by title.
- display_all_books() – Show all books with availability status.

