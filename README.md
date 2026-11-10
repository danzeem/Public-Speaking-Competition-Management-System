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

<img width="1067" height="507" alt="image" src="https://github.com/user-attachments/assets/89d7a8a1-9d0c-4423-9e30-0ad0827a6483" />

**Participant competition login**

<img width="965" height="462" alt="image" src="https://github.com/user-attachments/assets/d5f99a4e-1c42-44cb-8ef0-5e4b699a779c" />

### Organizer and registration workflow

**Add a participant** — Enter participant information and assign the relevant judge and organizer.

<img width="483" height="235" alt="image" src="https://github.com/user-attachments/assets/8dd3ad95-57ab-4035-8e32-5f00704bea74" />


**Register organizer and judge accounts**

| Organizer registration | Judge registration |
| --- | --- |
|<img width="490" height="232" alt="image" src="https://github.com/user-attachments/assets/41dc6692-cffc-4d59-9fae-6909c4365144" /> | <img width="486" height="233" alt="image" src="https://github.com/user-attachments/assets/3a048944-a550-4635-954e-268032d1f43d" /> |

**Assessment criteria management**

<img width="1200" height="585" alt="image" src="https://github.com/user-attachments/assets/8c3214ae-561f-4498-a110-caf4cd04e4fe" />

### Importing and finding records

| Import records | Find a participant |
| --- | --- |
| <img width="712" height="330" alt="image" src="https://github.com/user-attachments/assets/088d1d75-fdbe-49ad-8678-ebe9f2886585" />
| <img width="557" height="248" alt="image" src="https://github.com/user-attachments/assets/87e2351e-7278-4c1e-9fd9-25de78700525" /> |

### Judging and reports

**Results shown to judges** — A tabular view of scores for assessed participants.

<img width="725" height="355" alt="image" src="https://github.com/user-attachments/assets/69cd7894-3e10-4336-ab6d-92d5f6fa3993" />

**Select and print a report**

| Report selection | Print preview |
| --- | --- |
| <img width="640" height="312" alt="image" src="https://github.com/user-attachments/assets/989e2a7b-661d-4ada-8e94-75e946b39d59" /> | <img width="1073" height="520" alt="image" src="https://github.com/user-attachments/assets/5a9c2911-4943-4e3a-8e0e-faf086e0db98" />
|

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
