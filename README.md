This is the README file for the final project
README / User Manual
We Go to Cal State LA Application
Version 1.0

1. Jira Project Board
All team task management and sprint planning were completed in Jira.
Jira Link: https://calstatela-cs3338.atlassian.net/jira/software/projects/CFP/boards/169

2. Formal Objective Breakdown

Snapshot 1– Start Objective


Establish core system architecture.
Set up frontend, backend, and database structure.
Implement basic role-based authentication.
Begin initial UI layout (Home, Categories, Activities).
Create first drafts of SDD, SRS, and README.
Snapshot 2– Checkpoint 1



Added wellness surveys and response tracking.
Implemented event calendar system.
Expanded resource categories.
Updated SDD, SRS, and README.
Snapshot 3– Checkpoint 2


Implemented Achievement Dashboard.
Added AI-powered assistant.
Added multilingual support (English & Spanish).
Updated all documentation.


Snapshot 4– Final Checkpoint

Improved UI/UX and accessibility.
Completed final testing and fixes.
Prepared final documentation and deliverables.


Why This Software Matters
The We Go to Cal State LA application provides a centralized digital platform for students,
families, and staff by combining academic tools, wellness assessments, resource libraries,
achievement tracking, and event scheduling.

Supports Academic Success: Provides guided learning, study tools, and career
development resources.
Promotes Wellness: Includes emotional wellness surveys and reflective tools.
Engages Families: Gives parents and guardians direct access to helpful information.
Ensures Accessibility: Bilingual support and WCAG-compliant UI.
Centralizes Resources: Brings multiple student services into one platform.

How to Download or Access the Application
4.1 Requirements

- Node.js 18+ (for frontend and backend)
- npm or yarn
- PostgreSQL/MySQL or SQLite for development

4.2 Running the Frontend

cd frontend
npm install
npm run dev
Access the app at: http://localhost:3000

4.3 Running the Backend
cd backend
npm install
npm run start
API available at: http://localhost:5000/api

4.4 Database Setup
Create Database
CREATE DATABASE wegotocsla;
Migrate Schema
npm run migrate
Seed Demo Data
npm run seed

4.5 Accessing the Application

Student Portal: http://localhost:3000
Parent Portal: http://localhost:3000/parent
Staff Portal: http://localhost:3000/staff
