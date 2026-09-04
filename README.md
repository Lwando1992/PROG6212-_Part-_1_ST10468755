# RaceDay Event Management System
 ## Project Description
RaceDay is a comprehensive event management platform designed to streamline the organization and participation in road running, walking, and cycling events across South Africa. It addresses the challenges of event registration, participant management, and result tracking, providing a user-friendly interface for both Organisers and Participants.

### User Roles
Organiser
Organisers have the ability to create, update, and delete events. They can manage categories for each event and view enrolments and results, ensuring a smooth operation of the events they oversee.

### Participant
Participants can register for events, select categories, and view their enrolments and results. This role is designed to enhance the user experience, making it easy for individuals to engage in their preferred activities.

## Part 1
ERD: The ERD outlines the relationships and attributes of the system's entities.
API Endpoint Plan: A structured plan for the API endpoints that facilitate user interactions.
SQL Database Script: A script to create the necessary database structure and seed it with initial data.
Repository Structure
The /docs folder will contain documentation related to the project, including API specifications, user guides, and architectural decisions, ensuring that all stakeholders have access to essential information.

Database Setup
To open and run the SQL script in SQL Server Management Studio (SSMS), follow these steps:

Open SSMS and connect to your database server.
Create a new database for the RaceDay system.
Open a new query window and paste the SQL script.
Execute the script to create the tables and seed the data.
CI/CD
The GitHub Actions workflow will check for code quality, run tests, and ensure that the application builds successfully. This automated process helps maintain the integrity of the codebase and facilitates continuous integration and deployment practices. 
