# Student Management System

## Project Overview
The Student Management System is a simple web application
developed using HTML, CSS, and JavaScript.

It helps users manage student records through a simple
and user-friendly interface.

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Browser Local Storage
- Git and GitHub

## Features
- Add new student records
- View all student records
- Search students by ID, name, email, course, or city
- Delete student records
- Prevent duplicate student IDs
- Store records in browser Local Storage
- Responsive design for mobile and desktop

## Project Structure

student-management/
├── index.html
├── style.css
└── README.md

## Installation and Setup

1. Install Git on your computer.
2. Create a folder named `student-management`.
3. Create the three project files in that folder.
4. Copy the provided code into each file.
5. Open `index.html` in your web browser.
6. Add student details and test the features.

No server or database installation is required.

## How to Use
1. Open the application.
2. Enter the student ID, name, email, phone number,
   course, and city.
3. Click the Add Student button.
4. Search for a student using the search box.
5. Click Delete to remove a student record.

## Git Commands

Configure Git:

    git config --global user.name "Your Name"
    git config --global user.email "your-email@example.com"

Initialize the repository:

    git init
    git status
    git add index.html style.css README.md
    git commit -m "Initial commit: Student Management System"

View commit history:

    git log

## GitHub Setup

1. Create a public repository named `student-management`
   on GitHub.
2. Connect the local repository to GitHub:

    git branch -M main
    git remote add origin https://github.com/YOUR-USERNAME/student-management.git
    git push -u origin main

Replace `YOUR-USERNAME` with your GitHub username.

## Update and Push Changes

After modifying the project files, run:

    git add .
    git commit -m "Update student management project"
    git push

## Clone the Repository

To copy the GitHub repository into another directory:

    git clone https://github.com/YOUR-USERNAME/student-management.git

## Limitations
- Data is stored in the current browser's Local Storage.
- Data is not shared between different browsers or devices.
- This project does not use a backend server or database.

## Conclusion
The Student Management System demonstrates basic web
development concepts and practical Git and GitHub workflows,
including repository initialization, commits, pushing changes,
and cloning a repository.
Version 1.0
