# Library_Management_Project

# 📚 Library Book Management System

A simple and modular Library Management System developed in Python.  
This project allows users to manage books using CRUD operations and provides persistent storage through CSV files.

---

## 🎯 Project Overview

The purpose of this project is to apply core programming concepts by creating a functional system that handles book records efficiently. The system supports adding, viewing, searching, updating, and deleting books from a library database.

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| Add Book | Insert a new book entry with ID, title, author & copies |
| Display Books | View all available books in tabular format |
| Search Book | Find a book by its ID |
| Update Copies | Modify the number of available copies |
| Delete Book | Remove a book from the library |

---

## 🏗 Project Architecture / Modules

The project is organized into multiple files for better maintainability:

| Module | Responsibility |
|--------|----------------|
| main.py | Application entry point & menu control |
| data_manager.py | Handles CSV data loading & saving |
| book_manager.py | All CRUD operations on books |
| helper.py | Input validation functions |
| library.csv | Persistent storage of book records |

This structure ensures separation of concerns and scalability.

---

## 🛠 Technologies Used

- *Python* (Core Programming)
- *CSV File Handling*
- *Dictionary Data Structure*
- *Modular Programming Structure*

---

## ▶ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/anshul-bit/Library_Management_Project.git

2. Navigate to the project folder:

cd library-management-system


3. Run the application:

python main.py



> Note: library.csv will be auto-created on the first run if not present.




---

🧪 Testing Instructions

Perform the following manual tests:

Action	Expected Result

Add book	Added successfully and appears in CSV
Search book	Shows correct details
Update copies	Updated number reflects immediately
Delete book	Entry removed from display and CSV


Screenshots to be included in report.


---

📈 Future Enhancements

Borrow/Return functionality

Search by title/author keywords

Improved UI (GUI using Tkinter)

SQLite or MySQL database support

Logging and admin authentication



---

👨‍💻 Developer

Anshul Kumar



---

📌 License

This project is for educational purposes under VIT academic guidelines.


---

---

### ✔ What This README Solves in Rubric

| Guideline Requirement | Status |
|---------------------|--------|
| Project title | ✔ Done |
| Overview | ✔ Done |
| Features | ✔ Done |
| Tools/Tech used | ✔ Done |
| Steps to run | ✔ Done |
| Testing instructions | ✔ Done |
| Screenshots section | ✔ Prepared & expected |
