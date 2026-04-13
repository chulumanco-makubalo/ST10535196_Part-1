# ChatApp
Overview

ChatApp is a simple Java-based console application that allows users to register and login with secure credentials. It demonstrates basic concepts of user validation, including username formatting, password complexity, and phone number verification.

This project is ideal for learning Java classes, methods, conditional logic, and unit testing with JUnit.
## Features
User Registration
Validates that the username contains an underscore and is no longer than 15 characters.
Enforces password complexity:
Minimum 8 characters.
At least 1 uppercase letter.
At least 1 number.
At least 1 special character.
## Validates South African phone numbers (+27) with correct length.
## User Login
Checks if the entered username, password, and phone number match registered credentials.
Returns a friendly login message upon success or failure.
Unit Testing
Unit tests to validate username, password, and phone number rules.
Technologies Used
## Setup
Clone the repository or download the project files.
Open in your IDE (NetBeans, IntelliJ, Eclipse, etc.).
Compile and run Main.java to use the app.
Run LoginTest.java to verify all validation rules with JUnit tests.

## Usage
### Registration
Enter a username (must include an underscore and ≤ 15 characters).
Enter a password (must meet complexity rules).
Enter a phone number (must start with +27 and have 12 digits).
The system will confirm if registration was successful.
Login
Enter your registered username, password, and phone number.
The system will display a personalized welcome message if successful, or an error message otherwise.
Example Console Session
=== USER REGISTRATION ===
Enter a username: Chulu_
Enter a password: CMANCO7_!
Enter your South African cellphone number (+27): +27607790384
User registered successfully.

=== USER LOGIN ===
Enter your username: Chulu_
Enter your password: CMANCO7_!
Enter your phone number (+27): +27607790384
Welcome Chulu_, it is great to see you again.
Notes
Currently, the app supports a single user at a time.
Future improvements can include:
Multiple users with persistent storage.
Password hashing for security.
Graphical User Interface (GUI)
