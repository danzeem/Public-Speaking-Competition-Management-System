# Public Speaking Competition Management System

**A database-backed web application for organizing and judging a school public speaking competition.**

**Year:** 2022  
**Context:** SPM Computer Science project · SMK Kuhara, Tawau, Sabah, Malaysia  
**Built with:** PHP · MySQL · HTML · CSS · JavaScript  
**Repository:** Public project showcase; implementation is stored separately in a private repository

## Overview

I developed this web-based system for *Pertandingan Syarahan Bahasa Melayu*, a Malay-language public speaking competition at my secondary school. The idea was to bring registration, judge assignment, assessment, result tracking, and report generation into a single database-backed application.

The system was designed around three user groups — **Urusetia (organizers)**, **Hakim (judges)**, and **Peserta (participants)** — each with its own workflow. It was my early introduction to connecting a web interface, backend processing, and relational data.

> **Project status:** Archived 2022 school project. The screenshots document the original prototype rather than a currently hosted or production-ready service.

## Main features

| Area | Features |
| --- | --- |
| Role-specific workflows | Login interfaces and pages for organizers, judges, and participants |
| Record management | Registration and management forms for organizers, judges, and participants |
| Assessment setup | Administer assessment criteria and scoring fields |
| Judging | Enter marks for participants and calculate totals |
| Results | Display participant marks and results tables |
| Reporting | Select reports and generate printable results |
| Data import and search | Import structured records from a text file and search participant records |

## Project screenshots

All images below show the archived application interface. Identifying values in selected screenshots have been obscured for public sharing.

### Authentication and participant access

**General login interface**

![General login form](screenshots/login.png)

**Participant competition login**

![Participant login form](screenshots/participant-login.png)

### Organizer and registration workflow

**Add a participant** — Enter participant information and assign the relevant judge and organizer.

![Add participant form](screenshots/add-participant.png)

**Register organizer and judge accounts**

| Organizer registration | Judge registration |
| --- | --- |
| ![Organizer form](screenshots/add-organizer.png) | ![Judge form](screenshots/add-judge.png) |

**Assessment criteria management**

![Assessment criteria form](screenshots/add-criteria.png)

### Importing and finding records

| Import records | Find a participant |
| --- | --- |
| ![Import data interface](screenshots/import-data.png) | ![Participant search with identifying data redacted](screenshots/participant-search.png) |

### Judging and reports

**Results shown to judges** — A tabular view of scores for assessed participants.

![Judge results table with names redacted](screenshots/judge-results.png)

**Select and print a report**

| Report selection | Print preview |
| --- | --- |
| ![Report selection interface](screenshots/report-selection.png) | ![Report and print preview](screenshots/report-print-preview.png) |

## Technology stack

| Layer | Tools / concepts |
| --- | --- |
| Frontend | HTML, CSS, JavaScript |
| Backend | PHP |
| Database | MySQL, relational tables, SQL queries |
| Data access | PHP `mysqli` |
| Other | PHP sessions, CRUD forms, data import, browser printing |

## How the application works

1. **Organizers** manage users, participants, judges, assessment criteria, imports, and reports.
2. **Judges** work with assigned participants and record scores across evaluation criteria.
3. **Participants** use a dedicated interface to access their assessment information.
4. **MySQL** stores related records for participants, judges, organizers, scoring criteria, and results.

## What I learned

- Designing a relational database and connecting it to PHP pages.
- Implementing different user flows within a multi-page web application.
- Using forms and SQL queries to create, retrieve, edit, and present data.
- Building scoring interfaces and printable reporting views.
- Working through the design and testing of a larger project independently.

I built this as a secondary-school student. In a contemporary application, I would redesign parts of the security, authentication, and code organization; this project is included as a record of my development and learning.

## Source code

The implementation is maintained separately in a **private repository**, as this was a school coursework project. The public repository contains documentation and project screenshots only.

A walkthrough of the implementation may be available on request, subject to applicable school rules and academic-integrity requirements.

## Author

**Mohd Danish Radzeem**  
SPM Computer Science · SMK Kuhara, Tawau · 2022
