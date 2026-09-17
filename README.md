Placement Management System

A responsive College Placement Management System built as a single-file web application using HTML, CSS and JavaScript.


Live Demo

GitHub Pages:


https://swethamaharaja776-max.github.io/placement-management-system/


Overview

This project provides a simple digital portal for a college Placement Cell. It helps manage:



Dashboard statistics

Student records

Recruiting companies

Job / placement drives

Student applications

Final placements

Basic reports and analytics


Main Features

Dashboard


Total students

Total companies

Open placement drives

Placed students

Placement overview chart

Quick summary


Students


Add student

Edit student

Delete student

Search students

CGPA validation from 0 to 10

Unique roll-number validation

Email validation


Companies


Add, edit and delete companies

Search companies

Industry, location and package details


Jobs / Drives


Add, edit and delete placement drives

Search drives

Deadline and status tracking


Applications


Track student applications

Status options: Applied, Shortlisted, Selected, Rejected

Search and CRUD operations


Placements


Store final placement details

Search, edit and delete records


Reports


Basic placement metrics

Placement-rate summary

Technology and storage information


Technology Stack

Layer	Technology
Frontend	HTML5
Styling	CSS3
Logic	JavaScript
Storage	Browser localStorage
Hosting	GitHub Pages

Project Structure

placement-management-system/
│
├── index.html
└── README.md

How It Works

User
  ↓
Responsive HTML/CSS Interface
  ↓
JavaScript CRUD Logic
  ↓
Browser localStorage

The application is intentionally designed as a simple GitHub Pages demo, so it does not require a server to run.


Data Storage

The current GitHub Pages version uses localStorage.


This means:



Data can remain after refreshing the page.

Data is stored only in the current browser/device.

Data is not shared between different users.

Clearing browser site data can remove the stored records.

There is no central SQL database in this static version.


CRUD Operations

The application demonstrates:



Create — Add records

Read — Display records in tables

Update — Edit existing records

Delete — Remove records


Validation

Client-side validation includes:



Required fields

Valid email format

CGPA range: 0–10

Unique student roll number

Confirmation before deletion


Deployment on GitHub Pages


Create or open the repository.

Keep index.html and README.md in the repository root.

Go to Settings → Pages.

Under Build and deployment, choose:
Source: Deploy from a branch
Branch: main
Folder: /(root)

Save.

Wait for the GitHub Pages deployment to finish.

Open the generated Pages URL.


Important

index.html must be in the root of the selected branch. README.md can remain in the same folder; GitHub Pages uses index.html as the website entry point.


Testing Checklist


 Dashboard loads

 Navigation works

 Add student

 Edit student

 Delete student

 Search records

 Add company

 Add job drive

 Add application

 Add placement

 Form validation

 Responsive layout

 localStorage persistence


Future Enhancements

For a full production-style Placement Management System, the next version can add:



Django REST Framework or Spring Boot backend

MySQL / PostgreSQL database

REST API endpoints

Admin authentication

Role-based access

Server-side validation

Postman API testing

Centralized student/company database

Resume upload

Email notifications

Advanced placement analytics

Export to CSV/PDF


Project Status

Status: Frontend CRUD demo deployed with GitHub Pages.


Author

Swetha M


Artificial Intelligence / Data Science Student


License

This project is created for educational and academic purposes.

