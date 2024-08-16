# BASIC AUTHENTICATION SYSTEM
Name: HIMJYOTI TALUKDAR
Company: CODTECH IT SOLUTIONS
ID: CT6WDS528
Domain: BACKEND DEVELOPMENT
Duration: June to August 2024

## Flask User Authentication System

## Overview of the project

The objective of this project is to create a basic user authentication system using Flask, a lightweight web framework for Python. The system allows users to register, log in, and access a protected home page. It also ensures that user passwords are securely stored using bcrypt hashing, and user sessions are managed to keep track of logged-in users.

## Key Features

- **User Registration**: Allows new users to create an account with a unique username and password.
- **User Login**: Users can log in using their registered credentials.
- **Session Management**: Once logged in, users are remembered across pages using session management.
- **Password Hashing**: Passwords are stored securely using bcrypt, a hashing algorithm designed for secure password storage.
- **Protected Routes**: Only authenticated users can access certain routes, like the home page.
- **User Logout**: Users can securely log out, clearing their session.

## Technology Stack

- **Python**: The core programming language used to build the application.
- **Flask**: A lightweight web framework for Python, used to handle routing, templates, and session management.
- **Flask-Bcrypt**: A Flask extension that integrates the bcrypt hashing algorithm for secure password storage.
- **HTML**: For creating the front-end templates of the registration, login, and home pages.
- **CSS**: (optional) For styling the front-end templates.

## Project Structure

/flask_auth_system
/templates
login.html # HTML template for the login page
register.html # HTML template for the registration page
home.html # HTML template for the home page (protected)
app.py # Main Flask application script

## Usage
- Register: Create a new user account by visiting /register.
- Login: Log in using your registered credentials by visiting /login.
- Home: Access the protected home page by visiting /home (after logging in).
- Logout: Log out from the application by visiting /logout.
