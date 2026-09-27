# 📱 Mobile Shop Management System (Python CRUD)

A lightweight, terminal-based **Mobile Shop Management System** built using Python. This application demonstrates fundamental CRUD (Create, Read, Update, Delete) operations using Python's list data structures, conditional logic, loops, and pattern matching (`match-case`).

---

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Concepts Covered](#-concepts-covered)
- [How to Run](#-how-to-run)
- [Usage Guide](#-usage-guide)
- [Future Enhancements](#-future-enhancements)

---

## ✨ Features

- ➕ **Add Mobile Record:** Input unique Mobile ID, Brand, Model, Price, and Quantity with duplicate ID prevention.
- 📋 **Display All Mobiles:** Output all saved mobile inventory items in a formatted table.
- 🔍 **Search Mobile:** Find specific mobile details using the unique Mobile ID.
- ✏️ **Update Mobile:** Modify existing records (Brand, Model, Price, Quantity) by ID.
- 🗑️ **Delete Mobile:** Remove records safely with a confirmation prompt (`Y/N`).
- 🖥️ **Interactive Console Dashboard:** A simple menu-driven system powered by Python's `match-case` statement.

---

## 📂 Project Structure
├── mobile_shop.py     # Main application script containing CRUD functions and CLI menu
└── README.md          # Project documentation

## 🛠️ Concepts Covered

- **Data Structures:** 2D Lists (`list` of `lists`) for storing record fields.
- **Control Flow:** `while` loop, `if-elif-else`, early function exits (`return`), `break`.
- **Modern Python Syntax:** Structural Pattern Matching (`match-case`) introduced in Python 3.10+.
- **Input Formatting:** Standard String Formatting and f-strings (`f"{price:<15.2f}"`).
- **Data Types & Casting:** Operations involving `int`, `float`, and `str`.

---

## 🚀 How to Run

### Prerequisites
- **Python 3.10 or higher** (required for `match-case` statement syntax).

Check your Python version:
```bash
python --version
