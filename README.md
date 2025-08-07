# Python Employee Management System

A simple desktop application for managing employee records, built with Python and the Tkinter GUI library. This project allows users to add, view, and search for employee information, which is stored locally in an Excel file.



---

## ✨ Features

This application provides the following core functionalities:

- **Add New Employees**: Easily add new employees by entering their ID, full name, and salary.
- **View All Employees**: Display a complete list of all saved employees in a clear, scrollable listbox.
- **Save Data to Excel**: All employee records are persistently stored in an `employees.xlsx` file in the project directory. The file is created automatically if it doesn't exist.
- **Search Functionality**:
    - Search for employees by their **Employee ID**.
    - Search for employees by their **Full Name**.
    - The search is case-insensitive and supports partial matches.
- **User-Friendly Interface**: A clean and intuitive graphical user interface built with Tkinter.

---

## 🛠️ Technologies Used

- **Python**: The core programming language.
- **Tkinter**: Python's standard library for creating graphical user interfaces.
- **Openpyxl**: A Python library used to read from and write to Excel 2010 (`.xlsx`) files.

---

## 🚀 Getting Started

To run this project on your local machine, follow these steps.

### Prerequisites

Make sure you have Python 3 installed on your system. You will also need to install the `openpyxl` library.

You can install the required library using pip:
```bash
pip install openpyxl