🎓 Student Marks Display System

A web-based Student Marks Display System designed to simplify the management and display of student academic results.

The system allows administrators and teachers to manage student, teacher, subject, and marks information, while students can securely view their marks and feedback through a user-friendly interface.

🚀 Features
👨‍💼 Admin
Add, update, and delete students
Add, update, and delete teachers
Manage subjects
Manage grades/classes
Manage system users
👨‍🏫 Teacher
Add student marks
Update student marks
Add and update student feedback
Manage subject-related marks
👨‍🎓 Student
Secure login
View examination marks
View subject-wise results
View grades
View teacher feedback
🛠️ Technologies Used
HTML – Web structure
CSS – User interface and styling
JavaScript – Client-side functionality and validation
PHP – Backend development
MySQL – Database
phpMyAdmin – Database management
WampServer – Local development environment
🏗️ System Architecture
             ┌──────────────────┐
             │    Frontend      │
             │  HTML / CSS / JS │
             └────────┬─────────┘
                      │
                      ▼
             ┌──────────────────┐
             │     Backend      │
             │       PHP        │
             └────────┬─────────┘
                      │
                      ▼
             ┌──────────────────┐
             │     Database     │
             │      MySQL       │
             └──────────────────┘
🗃️ Database

The system stores and manages:

Student information
Teacher information
Admin information
Subject information
Grade/Class information
Student marks
Student feedback
📊 Main Modules
Authentication & Login
Admin Dashboard
Student Management
Teacher Management
Subject Management
Grade Management
Marks Management
Feedback Management
Student Dashboard
Result Display
🔐 Security

The system includes:

User authentication
Role-based access
Password protection
Restricted access to user information
Input validation
Database-based access control
⚙️ Installation
1. Clone the Repository
git clone https://github.com/your-username/student-marks-display-system.git
2. Setup WampServer

Install and start:

Apache
MySQL

Copy the project folder into:

C:\wamp64\www\
3. Setup Database

Open:

http://localhost/phpmyadmin

Create the required database and import the provided .sql file.

4. Configure Database Connection

Update the database connection details in the PHP configuration file:

$host = "localhost";
$username = "root";
$password = "";
$database = "student_marks";
5. Run the Project

Open the following URL in your browser:
http://localhost/student-marks-display-system/

📈 Future Improvements
Parent/Guardian login
Student performance analytics
Graphs and charts
PDF result generation
Email notifications
Password reset
Cloud deployment
Mobile application
Advanced reporting
🎯 Purpose

The main purpose of this system is to replace traditional paper-based mark management with a more efficient digital solution.

It helps reduce manual work, improve accessibility to student results, minimize data-entry errors, and provide a centralized platform for managing academic information.

📄 License

This project is developed for educational purposes.
