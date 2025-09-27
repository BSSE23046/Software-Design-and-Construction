# Software-Design-and-Construction
Software Design and Construction / Fall 2025

Project README FILE
Payroll Management System - README

Overview

This is a comprehensive Payroll Management System built with HTML, CSS, JavaScript, and Bootstrap. The system allows administrators to manage employee records, process payroll, and generate reports - all stored locally in the browser's localStorage.

Group Members:

M.Daniyal Hammad 


Features

User Authentication
- Secure login with username/password (admin/admin123)
- Session management using localStorage
- Protected routes for all payroll pages

Employee Management

- Add new employees with complete details
- View and edit existing employee records
- Delete employees when needed
- Automatic email and phone number generation

Payroll Processing

- Track basic salary, allowances, and deductions
- Calculate net pay automatically
- Maintain payment history for each employee

Reporting & Analytics

- Dashboard with key metrics (employee count, payroll totals)
- Visual charts for salary and department distribution
- Recent payroll activities table
- Export payroll data to CSV

Technical Details

File Structure

/payroll-system/
├── index.html          # Dashboard
├── login.html          # Login page
├── employee.html       # Employee details
├── add.html            # Add employee form
├── list.html           # Employee list
├── reports.html        # Reports dashboard
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   ├── script.js       # Main application logic
│   ├── employee.js     # Employee-specific functions
│   ├── login.js        # Authentication logic
│   └── logout.js       # Session management
└── img/                # Image assets

Dependencies

- Bootstrap 5.3.0 (CSS & JS)
- Font Awesome 6.4.0 (icons)
- Chart.js (data visualization)

Setup Instructions

- Clone or download the repository
- Open login.html in a web browser


- Use credentials:

  Username: admin
  Password: admin123

- All data is stored in browser localStorage (no backend required)

Usage Notes

- The system works entirely client-side
- Data persists between sessions but is browser-specific
- For production use, consider adding a backend database
- Tested on modern browsers (Chrome, Firefox, Edge)

