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
Validates South African phone numbers (+27) with correct length.
User Login
Checks if the entered username, password, and phone number match registered credentials.
Returns a friendly login message upon success or failure.
Unit Testing
Unit tests to validate username, password, and phone number rules.

