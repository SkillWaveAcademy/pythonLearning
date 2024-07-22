# Python Assignment: Library Management System

### Objective
Create a simple Library Management System to help students revise Python concepts up to Object-Oriented Programming (OOP). The system will allow users to add books, borrow books, return books, and view available books.

### Concepts Covered
- Basic Python Syntax
- Functions
- Lists and Dictionaries
- Classes and Objects
- Methods
- File Handling (optional for extra credit)

### Assignment Description
You are required to create a Library Management System using Python. The system should have the following features:

1. **Add a Book:** Allow the librarian to add new books to the library.
2. **Borrow a Book:** Allow users to borrow books if they are available.
3. **Return a Book:** Allow users to return borrowed books.
4. **View Available Books:** Display all the books currently available in the library.

### Detailed Instructions

#### Define a `Book` Class:
- **Attributes:** `title`, `author`, `isbn`
- **Methods:** `__init__`, `__str__`

#### Define a `Library` Class:
- **Attributes:**
  - `books` (a list to store books)
  - `borrowed_books` (a dictionary to store borrowed books)
- **Methods:** 
  - `add_book`
  - `borrow_book`
  - `return_book`
  - `view_available_books`

#### Implement the Methods:
- **`add_book(book)`**: Adds a book to the `books` list.
- **`borrow_book(isbn, user)`**: Allows a user to borrow a book if it is available. If borrowed, it should move the book from `books` to `borrowed_books`.
- **`return_book(isbn)`**: Allows a user to return a borrowed book. It should move the book back from `borrowed_books` to `books`.
- **`view_available_books()`**: Prints all the books currently in the `books` list.

#### Main Program:
1. Create an instance of `Library`.
2. Provide a menu-driven interface to the user to interact with the system.