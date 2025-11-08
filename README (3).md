# pr.7 moduler.ipynb — Multi‑Utility Toolkit

This repository contains the **Multi‑Utility Toolkit**, a Python notebook project designed to demonstrate modular programming and the use of built‑in Python modules through a menu‑driven interface.

---

## 📘 Project Overview

The notebook implements a **command‑line style toolkit** that allows users to perform several operations interactively — including date and time calculations, mathematical operations, random data generation, unique identifier creation, file handling, and module inspection.

---

## ⚙️ Features

### 1. Datetime and Time Operations
- Display the current date and time
- Calculate the difference between two dates or times
- Format dates into custom formats
- Simple stopwatch and countdown timer

### 2. Mathematical Operations
- Perform addition, subtraction, multiplication, division
- Calculate power, square roots, and factorials

### 3. Random Data Generation
- Generate random integers, floats, and strings

### 4. UUID (Unique Identifiers)
- Generate universally unique identifiers

### 5. File Operations (Custom Module)
- Create, read, write, and delete files
- Example filename: `example.txt`

### 6. Explore Module Attributes
- Use Python’s `dir()` to explore available methods and attributes in modules

---

## 🧠 Code Structure

| Module / Section | Purpose |
|------------------|----------|
| **main_menu()** | Displays the main options and routes user input |
| **datetime_operations()** | Handles date/time calculations and formatting |
| **math_operations()** | Performs mathematical operations |
| **random_operations()** | Generates random numbers and strings |
| **uuid_operations()** | Generates UUID values |
| **file_operations()** | Provides file management functions |
| **explore_module()** | Uses `dir()` to inspect modules |
| **stop condition** | Typing `'stop'` exits the program |

---

## 💻 How to Run

1. Open the file **`pr.7 moduler.ipynb`** in **Jupyter Notebook** or **VS Code**.
2. Run all cells sequentially.
3. Use the numbered menu to choose an operation.

Example:
```
Welcome to Multi‑Utility Toolkit
1. Datetime and Time Operations
2. Mathematical Operations
3. Random Data Generation
4. Generate Unique Identifiers (UUID)
5. File Operations (Custom Module)
6. Explore Module Attributes (dir())
7. Exit
Type 'stop' to exit program
```

---

## 🧩 Example Output

```
Datetime and Time Operations:
Enter first date (YYYY-MM-DD): 2024-12-25
Enter second date (YYYY-MM-DD): 2025-01-04
Difference: 10 days
```

```
File Operations:
Enter data to write: test
Data written successfully!
```

---

## 📦 Requirements

- Python 3.8 or above  
- Standard libraries only (no external dependencies):
  - `datetime`
  - `math`
  - `random`
  - `uuid`
  - `os`
  - `time`

---

## 👩‍💻 Author

**Kajal Harijan**  
Python Mini Project — *Multi‑Utility Toolkit (pr.7 moduler.ipynb)*

License: MIT

---
