# 📚 Library Management System (C++)

A fully featured **console-based Library Management System** developed in C++ using **Object-Oriented Programming (OOP)** principles.  
This project simulates real-world library operations such as book management, user management, borrowing, returns, fines, and advanced search features.

---

## Features

### User Management
- Add, update, and remove users
- Separate roles (Admin / Member)
- User authentication system

### Resource Management
- Manage Books and eBooks
- Add, update, delete resources
- Track availability status

### Borrowing System
- Borrow and return books/eBooks
- Track borrow history
- Extend borrow duration

### Fine Management
- Automatic fine calculation for late returns
- Fine tracking per user

### Advanced Search
- Search books by title, author, category
- Fast filtering system

### Admin Features
- Analytics dashboard
- Borrow statistics
- User activity tracking

### Logging & Exception Handling
- Audit logs for system actions
- Custom system exceptions
- Input validation helpers

---

## OOP Concepts Used

- Classes & Objects
- Inheritance (Book, eBook → Resource)
- Encapsulation
- Polymorphism
- Abstraction
- Operator Overloading
- Exception Handling

---

## Requirements
C++ compiler (GCC / MinGW / MSVC)
C++11 or above

---

## How to Compile & Run

### Using g++:
```bash
g++ *.cpp -o libraryApp
./libraryApp
```bash

## 🏗️ Project Structure
