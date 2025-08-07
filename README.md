# Python Employee Management System

A simple desktop application for managing employee records, built with Python and the Tkinter GUI library. This project allows users to add, view, and search for employee information, which is stored locally in an Excel file.

## Features

* **Add New Employees**: Easily add new employees by providing their ID, full name, and salary.
* **View All Employees**: Display a complete list of all employees stored in the data file.
* **Search Functionality**: Search for specific employees based on their **ID** or **Name**.
* **Data Persistence**: All records are saved to an `employees.xlsx` file, ensuring data is not lost when the application is closed.
* **User-Friendly Interface**: A clean and straightforward graphical user interface built with Tkinter.
* **Dynamic UI**: The interface is organized with frames and layout managers to be responsive and tidy.

## How to Run the Application

1.  **Prerequisites**:
    * Ensure you have Python 3 installed on your system.
    * Install the required library, `openpyxl`, for Excel file manipulation.
        ```bash
        pip install openpyxl
        ```

2.  **Execution**:
    * Clone or download this repository to your local machine.
    * Navigate to the project directory in your terminal.
    * Run the main script:
        ```bash
        python employee_manager.py
        ```
    * The application window will appear, and an `employees.xlsx` file will be created in the same directory upon saving the first employee.

## Future Development (Planned Features)

* **Update Employee Records**: An interface to select and edit the information of an existing employee.
* **Delete Employee Records**: Functionality to remove an employee from the records.
* **Dynamic File Path**: Allow the user to specify the path and name of the data file through the GUI, instead of using a hardcoded path.

## Project Structure

* `employee_manager.py`: The main Python script containing the `EmployeeManager` class and all application logic.
* `employees.xlsx`: The Excel file where employee data is stored (created automatically).
* `.gitignore`: Specifies files to be ignored by Git, such as the data file and Python cache.
* `README.md`: This file.