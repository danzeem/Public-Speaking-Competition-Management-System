# Public Speaking Competition Management System (Private project)

**A school competition management system built with PHP, MySQL, HTML, CSS, and JavaScript.**

**Year:** 2022  
**Project:** SPM Computer Science · SMK Kuhara, Tawau, Sabah  
**Repository:** Public project showcase — source code is kept private

## About the project

This was one of my school Computer Science projects: a web-based management system for a **Malay-language public speaking competition** (*Pertandingan Syarahan Bahasa Melayu*).

The goal was to bring common competition activities — participant registration, judging, score recording, and results reporting — into a database-backed application instead of handling each step separately.

Building it introduced me to full-stack web development, relational database design, and the challenge of connecting different users and workflows within one system.

## Key features

| Feature | Description |
| --- | --- |
| **Three user roles** | Separate login flows and interfaces for organizers, judges, and participants |
| **Participant management** | Registration and administrative tools for managing participant records |
| **Judge assignment** | Participant records associated with assigned judges |
| **Scoring** | Judges enter marks for assessment criteria and calculate totals |
| **Results** | Participants can view their assessment breakdown and standing |
| **Reports** | Organizers can view overall or judge-filtered results and print them |
| **Record management** | Administrative tools for managing judges, organizers, and assessment criteria |
| **Data import** | Import support for comma-separated participant or judge records |

These features describe the original school prototype. It is an archived project, not a currently hosted or production-ready service.

## Technology stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL (relational tables and foreign-key relationships)
- **Database access:** PHP `mysqli`
- **Other concepts:** PHP sessions, CRUD operations, SQL queries, form handling, dynamic reporting

## How it works

The application follows three main user journeys:

**Organizers** manage competition records, assessment criteria, and results reports.

**Judges** select participants assigned to them, enter scores for the defined criteria, and submit the results.

**Participants** sign in to view their marks, total score, and standing.

The data is stored in a relational database connecting participants, judges, organizers, assessment criteria, and results.

## Screenshots

*Screenshots can be added here once sample data has been anonymized.*

Suggested screenshots:

1. Login page
2. Organizer dashboard and participant management
3. Judge scoring form
4. Results or printable report using fictional participant data

> For privacy, any screenshots shared publicly should exclude real students' personal details, passwords, identity numbers, and telephone numbers. Review school logo usage before publishing images.

## What I learned

This project helped me move beyond static websites and understand how a complete web application is organized.

I gained experience with:

- Designing related tables in a MySQL database
- Connecting PHP pages to a database and displaying queried data
- Implementing basic create, read, update, and delete (CRUD) operations
- Designing different workflows for different users
- Capturing and processing form input
- Presenting scores and generating printable reports
- Structuring a multi-page web project

It was an early project, and I would approach authentication, security, and maintainability differently today. Nevertheless, it represents an important step in learning how to build database-driven applications.

## Source code availability

The **source code is maintained in a private repository** because this was a school coursework project.

This public repository is intended to document the system and demonstrate what I built. A project walkthrough may be provided on request, subject to applicable school and academic-integrity requirements.

## Author

**Mohd Danish Radzeem**  
SMK Kuhara · SPM Computer Science Project · 2022
