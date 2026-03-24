# Mini-Library-Management.Python

A simple command-line based Library Management System built using Python.  
This project demonstrates basic Object-Oriented Programming (OOP) concepts and allows users to manage books efficiently.

---

## 🚀 Features

- 📖 View all books
- 👤 View all users
- 📕 Borrow a book
- 📗 Return a book
- 📊 Track borrowed books
- 🧭 Menu-driven interface

---

## 🛠️ Technologies Used

- Python
- Object-Oriented Programming (OOP)

---

## 📂 Project Structure

### Classes
- **Book**
  - Stores book ID, title, author
  - Tracks availability and borrower

- **User**
  - Stores user ID and name
  - Keeps record of borrowed books

### Functions
- `show_books()` → Displays all books  
- `show_users()` → Displays all users  
- `borrow_book()` → Allows user to borrow a book  
- `return_book()` → Allows user to return a book  
- `show_borrowed()` → Shows borrowed books  
- `find_user()` → Finds user by ID  
- `find_book()` → Finds book by ID  

---

## 📌 How It Works

- Each book has a unique ID and availability status.
- Each user can borrow multiple books.
- When a book is borrowed:
  - It becomes unavailable
  - It is assigned to the user
- When returned:
  - It becomes available again

---
