Employee Management System
The Employee Management System is a comprehensive solution designed to streamline and enhance human resource operations within organizations. This system offers a user-friendly interface that facilitates efficient management of employee profiles, tracking of leave and attendance, task assignment, and performance evaluations. By centralizing these essential HR functions, the system empowers administrators to optimize workforce management, boost productivity, and ensure accurate data-driven decision-making.

Table of Contents
Introduction
Live Preview
User Interface
Technologies Used
Usage
Features
User Authentication
Dashboard
Employee Profiles
Leave and Attendance
Performance Evaluation
Task Assignment
Payroll Management
Getting Started
Prerequisites
Installation
AdminKit Admin Panel
Contributors
Want to Contribute
License
Introduction
The Employee Management System is a comprehensive and user-friendly application designed to streamline and simplify the process of managing employees within an organization. This system provides an efficient and organized way to handle various employee-related tasks, from onboarding and attendance tracking to performance evaluation and payroll management.

Live Preview
To preview this project please visit https://hrms.shawon-khan.com/

User Interface
Welcome

Login

Dashboard

Users

New User

Employees

New Employee

Schedule

Daily Attendance

AttendanceReport

Payroll

Technologies Used
The following technologies have been used in the development of Employee Management System (HRMS):

Laravel : A popular PHP web application framework known for its elegant syntax and feature-rich ecosystem.
Laravel Blade : The templating engine provided by Laravel for designing and rendering views.
MySQL : The database management system used to store application data.
Bootstrap : A CSS framework for creating responsive and attractive UI components.
FontAwesome: A popular icon library that provides a wide range of icons for web projects.
Usage
Log in to access the admin dashboard.
Add employees and provide necessary details.
Manage leave requests, assign tasks, and perform other administrative functions.
Employees can log in to view their profiles, submit leave requests, and update task statuses.
Features
01. User Authentication
Securely manage user access with a robust authentication system. Different user roles (admin, manager, hr etc) ensure appropriate permissions and access levels.

02. Dashboard
Upon logging in as an administrator, you will be welcomed to the Admin Dashboard. The dashboard provides an insightful overview of vital statistics, including the total count of employees, ongoing projects, and recent activities. This central hub offers swift access to critical sections of the Employee Management System, empowering you to efficiently oversee employee profiles, leave requests, task assignments, and more.

03. Employee Profiles
Maintain detailed profiles for each employee, including personal information, contact details, job history, and more.

04. Leave and Attendance
Easily manage employee attendance and leave requests, allowing for accurate tracking and efficient planning.

05. Performance Evaluation
Conduct performance reviews and evaluations within the system, facilitating timely feedback and goal setting.

06. Task Assignment
Assign tasks and projects to employees, set deadlines, and track progress, enhancing collaboration and productivity.

07. Payroll Management
Streamline payroll processing by automating salary calculations, tax deductions, and generating paystubs.

08. Reports and Analytics
Generate insightful reports and analytics on various aspects of employee management, aiding data-driven decision-making.

Getting Started
Follow these instructions to get a copy of the Employee Management System project up and running on your local machine for development and testing purposes.

Prerequisites
Before you proceed, ensure you have the following software installed:

PHP (Version 8.2)
Composer (Version 2.5)
MySQL (Version 8.2)
Laravel (Version 10.16)
Installation
Clone the Employee Management System repository to your local machine using the following command:
git clone https://github.com/MOHONA678/employee-management-system.git
Navigate to the project directory:
cd employee-management-system
Install the required PHP dependencies using Composer:
composer install
Install Node.js dependencies
Using npm:
npm install
or,

using Yarn:
yarn
Generate Vite serve manifest:
Using npm:
npm run build
or,

using Yarn:
yarn build
Create a new MySQL database for Employee Management System and update the .env file with your database credentials:
cp .env.example .env
Generate a unique application key:
php artisan key:generate
Run the database migrations and seed the database with initial data:
php artisan migrate --seed
Start the development server:
php artisan serve
Congratulations! Employee Management System should now be up and running at http://localhost:8000.

AdminKit Admin Panel
Our Employee Management System incorporates the AdminKit Admin Panel to streamline administrative tasks. AdminKit is a flexible and modern admin dashboard template built with Bootstrap and other front-end technologies. Its customizable components and UI elements enable efficient management of various HRMS functionalities.

Get it from here: AdminKit

Contributors
Mohona Akter
GitHub: MOHONA678
Contributions: Multirole Authentication with Persmission, User Management, Attendance System.
Mst.Shorifa Akter
GitHub: Shorifa1234
Contributions: Staff Management, Leave Management, Payroll system.
Muhammad Nasir Uddin Khan Shawon
GitHub: shawonk007
Contributions: Database Design & Management.
Want to Contribute?
We welcome contributions from the community! If you'd like to contribute to the Employee Management System project, please follow these steps:

Fork the repository.
Create a new branch for your feature/bug fix.
Make your changes and test thoroughly.
Submit a pull request explaining your changes and the problem they solve.
License
This Employee Management System is distributed under the GNU General Public License version 3.0 (GPL-3.0). You can find the full text of the license in the LICENSE file.