Payroll Management System

The payroll management system is a Python program designed to manage employee information, department, salaries, and, incentives efficiently within an organization. The system allows administrators to perform various employee management and compensation tasks. The system also interacts with the MySQL database to store and retrieve data, providing a user-friendly interface for managing payroll-related tasks.

Some of the core features of this management system are:

    User Authentication: The system offers user authentication through a login and sign-up process, ensuring secure access to authorized users.

    Employee Management: The application allows users to add new employees to the database, including their personal details (name, gender, contact information) and employment details (date of joining, department, designation, projects).

    Department and Designation: Users can specify the department and designation of each employee, allowing for easy categorization and organization of the workforce.

    Salary Calculation: The system calculates employee salaries based on provided inputs, including basic salary, HRA (House Rent Allowance), DA (Dearness Allowance), and tax deductions.

    Incentive Calculation: The application supports the calculation of incentives for employees. Default incentives and department-based incentives can be set, and net incentive values are automatically updated.

    Data Manipulation and Reporting: Users can update employee details, department information, and salary components. The system provides options to view employee details based on various criteria (designation, department, salary, projects). Comprehensive reports for individual employees or all employees can be generated.

Getting Started:

    Clone the repository to your local machine:

    git clone https://github.com/your-username/payroll-management-system.git

    Install the required dependencies. Make sure you have Python and MySQL installed:

    pip install mysql-connector-python pip install tabulate

    Set up the MySQL database: Create a MySQL database named "project." Run the provided SQL script to set up the required tables and sample data

    Run the program: Final.py

Usage

    Login or Sign Up: Choose between logging in if you have an account or signing up if you are a new user.

    Main Menu: Once logged in, you'll be directed to the main menu. Select options to perform tasks such as adding/deleting employees, updating details, generating reports, and managing salaries, and incentives.

    Employee and Department Management: You can add new employee records, assign departments and designations, update employee details, or delete employee records.

    Salary Management: Update employee salaries and view salary details, including basic, HRA, DA, tax, and net salary.

    Incentive Management: Calculate and update employee incentives based on default rates or by the department.

    Reports: Generate reports to view employee details based on different criteria like designation, department, salary, and number of projects.

    Logout: Exit the system and log out from your account.

Acknowledgments This project was developed by Nitish Kumar Yarlagadda and Lohith R Gowda.

Note:

    MySQL Database Setup Install MySQL on your system if you haven't already. Open your MySQL command-line client or a MySQL GUI tool (such as phpMyAdmin). Create a new database named "project":

    CREATE DATABASE project;

Running SQL Script Open your MySQL command-line client or a MySQL GUI tool. Connect to the "project" database:

USE project;

    Run the provided SQL script (included in the project files) to create the necessary tables and sample data. This script will create tables for employee records, departments, salaries, incentives, and login credentials.

Note: During the setup process, you will be prompted to enter passwords and other data. Make sure to remember the password you set up for your MySQL database. The password created by you must be changed in line number 4 by filling the quotes of passw with your new password.

    Pre-defined login details can be found on lines 53 and 54.
