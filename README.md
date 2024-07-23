# RegiPro
Follow the link for the sketches: https://drive.google.com/file/d/18AlN6B4dcHC_LkZAJ_3YH8HqX1eaJjJ7/view?usp=sharing
#Login Details for the app are email === 'john.doe@example.com' && password === 'password123';

#Employee Management Application
Description
The Employee Management Application (RegiPro) is a React-based web application designed to manage a list of employees. Users can add, edit, delete, and search for employees. The application uses localStorage to persist data across page reloads.

#Features
Add new employees with details including image, name, email, phone, position, and status.
Edit existing employee details.
Delete employees from the list.
Search employees by their ID.
Employee count displayed at the top.

#Installation
Clone the repository:
git clone https://github.com/yourusername/employee-management-app.git
cd employee-management-app
Install dependencies:
npm install
Run the application:
npm run dev
The application will start on http://localhost:5173.

Components
Tbl
The main component of the application, responsible for rendering the employee table and managing the state.

EmployeeCount
Displays the total count of employees.

AddEmployee
A form to add new employees to the list.

Edit
A form to edit the details of an existing employee.

Usage
Adding an Employee:

Fill out the form at the top of the table with the employee's details.
Click the "Add" button to add the employee to the list.
Editing an Employee:

Click the edit icon next to the employee you wish to edit.
Update the details in the form that appears and click "Change" to save the changes.
Deleting an Employee:

Click the delete icon next to the employee you wish to delete.
Searching for an Employee:

Use the search box at the top to filter employees by their ID.
Code Structure
Tbl.js: Main component containing the table and logic for managing employees.
EmployeeCount.js: Component for displaying the total number of employees.
Edit.js: Component for editing an existing employee.
AddEmployee.js: Component for adding a new employee.
Dependencies
react: JavaScript library for building user interfaces.
react-icons: Library for including icons in React applications.
react-scripts: Configuration and scripts for Create React App.
License
This project is licensed under the MIT License. See the LICENSE file for details.

#Example Usage
import React from 'react';
import ReactDOM from 'react-dom';
import Tbl from './Tbl';

ReactDOM.render(<Tbl />, document.getElementById('root'));
