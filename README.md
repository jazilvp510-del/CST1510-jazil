student name : Jazil VP
student ID : M01096016
Course: CST1510 -CW2 - Multi-Domain Intelligence Platform

#project description
This project is a simple command-line authentication system that uses bcrypt to securely hash and verify passwords. It supports user registration, login, basic input validation, and stores user data in a local text file. The system demonstrates secure password handling and file-based user management in Python.

##Features
- Secure password hashing using bcrypt with automatic salt generation
- User registration with duplicate username prevention
- User login with password verification
- Input validation for usernames and passwords
- File-based user data persistence

#Technical Implementation
Hashing Algorithm: bcrypt with automatic salting
Data Storage: Plain text file (users.txt) with comma-separated values
Password Security: One-way hashing, no plaintext storage
Validation:
Username: 3–20 alphanumeric characters
Password: 6–50 characters
