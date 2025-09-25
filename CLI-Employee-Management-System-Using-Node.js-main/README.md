# CLI Employee Management System Using Node.js and Arrays

## Description
A simple command-line interface (CLI) application to manage employees in memory using arrays.
You can **add**, **list**, and **remove** employees interactively through the terminal using Node.js.

## Features
- Add new employees with Name and ID.
- List all employees stored in memory.
- Remove employees by their ID.
- Interactive terminal menu using Node.js `readline`.

## Installation
1. Make sure [Node.js](https://nodejs.org/) is installed on your system.
2. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
3. Navigate to the project folder:
   ```bash
   cd <project_folder>
   ```

## Usage
1. Open terminal in the project folder.
2. Run the application using:
   ```bash
   node employeeManagement.js
   ```
3. Follow the on-screen menu to interact:
   - `1` → Add Employee
   - `2` → List Employees
   - `3` → Remove Employee
   - `4` → Exit

## Example Output

### Adding Employees
![Add Employee](/output/output_1.png)

### Listing Employees
![List Employees](/output/output_2.png)

### Removing Employees
![Remove Employee](/output/output_3.png)

### Exit Application
![Exit Application](/output/output_4.png)

## Notes
- All data is stored in memory and will be lost when the program exits.
- Ensure unique employee IDs when adding a new employee.


