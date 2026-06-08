Python Login System
Overview

This project is a simple Python-based Login System that allows users to:

Register with an email and password
Log in using registered credentials
Validate usernames and passwords
Recover forgotten passwords
Reset passwords
Store user credentials in a local text file

The project demonstrates basic concepts of Python programming, file handling, regular expressions, and user authentication.

Features
User Registration
Accepts email-based usernames
Validates username format
Prevents duplicate registrations
Password Validation

Password must:

Be between 6 and 16 characters
Contain at least one uppercase letter
Contain at least one lowercase letter
Contain at least one digit
Contain at least one special character
Login System
Verifies username and password
Allows access only with valid credentials
Forgot Password
Retrieves stored password
Allows users to reset their password
Credential Storage
Stores user credentials in a text file (credentials.txt)
Loads saved credentials during login
Technologies Used
Python 3
Regular Expressions (re)
File Handling
OS Module (os)
Project Structure
python-login-system/
│
├── main.py
├── credentials.txt
└── README.md
How to Run
1. Clone the Repository
git clone https://github.com/your-username/python-login-system.git
2. Navigate to the Project Folder
cd python-login-system
3. Run the Program
python main.py
Sample Menu
Welcome to the Python Login System!

Choose action:
(R) Register
(L) Login
(Q) Quit
Example Password
Password@123

This password satisfies all validation rules:

Uppercase letter ✓
Lowercase letter ✓
Number ✓
Special character ✓
Learning Outcomes

Through this project, you can learn:

Python Functions
Input Validation
Regular Expressions
File Operations
Dictionary Handling
Authentication Logic
Error Handling
Future Improvements
Encrypt passwords using hashing
Store data in a database
Add email verification
Create a graphical user interface (GUI)
Implement OTP-based password recovery
