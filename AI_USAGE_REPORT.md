# Mandatory AI Usage Report

## AI Tool Used

ChatGPT / Codex was used as a development assistant during this assignment.

## How AI Was Used

I used AI support mainly for planning, implementation guidance, debugging, and documentation. The final project direction, stack selection, deployment decisions, testing, and validation were reviewed and confirmed by me.

The assignment selected was Assignment 4: Student Support & Ticket Management System.

## Most Useful Prompt

Assignment 4: Student Support & Ticket Management System

Build a complete deployable prototype for managing student administrative support requests such as fees, attendance, ID cards, documents, certificates, and other college operations.

The system should allow students to create and track support tickets, staff members to take ownership of tickets and update their progress, and managers to monitor ticket workload, SLA health, ageing, priority distribution, category trends, and resolution status.

The application should include role-based access, ticket statuses, priority levels, category-based SLA due dates, overdue and at-risk ticket indicators, owner assignment, comments, activity history, resolution tracking, dashboard metrics, README documentation, and deployment notes.

Use React for the frontend, Express.js for the backend, and PostgreSQL for the database.

## AI-Assisted Work

AI helped with the following parts of the project:

1. Understanding the assignment PDF and identifying the expected scope for Assignment 4.
2. Comparing possible tech stacks and finalizing React, Express, and PostgreSQL based on my comfort level.
3. Creating the initial project structure for the frontend and backend.
4. Designing the PostgreSQL schema for users, tickets, comments, and activity history.
5. Creating Express API routes for authentication, tickets, comments, dashboard data, and workflow updates.
6. Building the React interface for login, ticket listing, dashboard charts, filters, ticket details, comments, and resolution flow.
7. Adding JWT-based authentication and role-aware access for student, staff, and manager users.
8. Preparing seed data and demo accounts for testing.
9. Debugging local setup, database connection, deployment configuration, CORS, and environment variable issues.
10. Drafting README and deployment instructions.

## Code Reviewed And Modified By Me

I reviewed the implementation and made decisions or changes around:

1. Using PostgreSQL instead of MySQL for deployment compatibility with Neon.
2. Keeping React for the frontend and Express for the backend because I am comfortable explaining this stack.
3. Setting up the hosted PostgreSQL database and updating backend environment variables.
4. Testing the complete flow locally before deployment.
5. Verifying login, ticket creation, ticket status updates, comments, dashboard metrics, and deployed frontend/backend communication.
6. Confirming that demo credentials and deployment links work before submission.

## AI Output That Needed Correction

Some early suggestions were too broad and included stack options before the final stack was confirmed. I corrected the direction to use React, Express, PostgreSQL, Vercel for frontend deployment, Render for backend deployment, and Neon for the PostgreSQL database.

There were also deployment-related issues, especially around environment variables and frontend-to-backend API connection. I tested these issues manually, updated the required deployment settings, and confirmed the app worked locally before proceeding with deployment.

## How I Validated The Work

I validated the project by:

1. Running the application locally.
2. Logging in with demo users for different roles.
3. Creating a new support ticket.
4. Checking that tickets appeared in the dashboard and list view.
5. Testing ticket status, owner assignment, comments, and resolution flow.
6. Confirming that the frontend communicates with the deployed backend.
7. Checking the deployed frontend URL after configuration changes.

## Final Responsibility

AI was used as an assistant to speed up development and debugging. I reviewed the implementation, selected the final stack, configured the database and deployments, tested the main workflows, and prepared the final submission.
