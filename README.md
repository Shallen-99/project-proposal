*Name of application

Your World

*Description of application

This is a full-stack MERN application that allows users to visually track and document their travel experiences across the U.S. Users can create multiple tra“Trips” and interact with a clickable U.S. map to mark states as visited or potentially visit. For each visited state, users can leave comments describing what they did and how they felt about the experience.

Backend Route Tree. Example Attached.

Authentication Routes

    *POST    /api/auth/register      → Register new user

    *POST    /api/auth/login         → Login user and return JWT

Trip Routes

    *GET     /api/trips              → Get all trips owned by logged-in user

    *POST    /api/trips              → Create a new trip

    *GET     /api/trips/:tripId      → Get a single trip (owner only)

    *PUT     /api/trips/:tripId      → Update a trip (owner only)

    *DELETE  /api/trips/:tripId      → Delete a trip (owner only)

State Visit Routes

    *GET     /api/trips/:tripId/states

    *POST    /api/trips/:tripId/states

    *PUT     /api/trips/:tripId/states/:stateId

    *DELETE  /api/trips/:tripId/states/:stateId



Create an ERD - Showing the flow of data in your application. You can draw this like you've done on previous projects.

"Check Slack"


Create a Timeline (Trello, google calendar etc. ) detailing dates for reaching major milestones. 
Ex: 2/9 - Complete Frontend, 2/10 - Complete Backend, 2/11 - Met MVP. You can also just list these dates.

Feb 9

    Backend Setup & Authentication

    Initialize backend project structure

    Configure environment variables and .gitignore

    Set up MongoDB Atlas connection

    Implement User model with bcrypt password hashing

    Build authentication routes (register/login)

    Implement JWT authentication middleware

Feb 10

    Trip (Project) API Development

    Create Trip model and schema validation

    Build full CRUD routes for Trips

    Implement ownership-based authorization

    Test all Trip routes using Postman

Feb 11

    StateVisit (Task) API Development

    Create StateVisit model

    Build nested CRUD routes under Trips

    Enforce ownership checks via parent Trip

    Add server-side validation (one state per trip)

    Test nested routes thoroughly

Feb 12

    Frontend Setup & Authentication Flow

    Create React app (Vite)

    Set up routing (login, register, dashboard, trip view)

    Implement Auth Context

    Protect routes based on authentication state

    Connect frontend auth to backend API

Feb 13

    Interactive Map & Core UI

    Implement SVG U.S. map component

    Handle state click interactions

    Create modal for viewing/editing state visits

    Connect map interactions to backend APIs

Feb 14

    Dashboard & UX Enhancements

    Build trip dashboard page

    Display trip statistics (states visited count)

    Implement loading, error, and empty states

    Make UI responsive for mobile/tablet

Feb 15

    Polish & Stretch Features

    UI refinement and accessibility tweaks

    Optional features (ratings, notes, progress indicators)

    Code cleanup and refactoring

    Add comments and improve readability

Feb 16

    Deployment & Documentation

    Deploy backend to Render

    Deploy frontend to Render

    Connect frontend to live backend

    Write complete README.md

    Verify environment variables in production

Feb 17

    Testing & Presentation Prep

    End-to-end testing of live app

    Fix bugs and edge cases

    Prepare demo walkthrough

    Practice explaining architecture & decisions

Feb 18 – FINAL SUBMISSION

    Final Review & Submission

    Final smoke test

    Verify GitHub repo is clean and public

    Submit live URLs

    Submit project for grading