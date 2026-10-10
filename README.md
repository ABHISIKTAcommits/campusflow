# CampusFlow — College Life Dashboard

CampusFlow is a lightweight college productivity app that helps students manage academic deadlines and build consistent study habits. It runs entirely in the browser, with no sign-up, server, or installation.

## Features

- **Task tracking:** manage assignments, labs, exams, and projects, with subject, priority, due date, and notes
- **Filters and search:** view tasks by deadline (All, Today, Upcoming, Overdue, Completed) and filter by subject, priority, and status
- **Dashboard:** see task progress, due-today counts, and overdue alerts at a glance
- **Pomodoro study timer:** 25-minute focus sessions and 5-minute breaks, with focus-session tracking
- **Automatic local saving:** tasks, completed focus sessions, and preferences are stored in your browser with `localStorage`
- **Responsive layout:** works on desktop and mobile screens

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript (no frameworks, libraries, or external APIs)

The whole app lives in a single `index.html` file.

## Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser (Chrome, Edge, Firefox, or Safari).

No installation, build step, or server is required.

## Data and Privacy

All data stays on your device. CampusFlow does not use a backend, account system, or cloud sync. Because data is stored in your browser's `localStorage`, clearing site data or switching browsers or devices will remove or hide your saved tasks.

## AI Assistance

Cursor AI helped scaffold the initial implementation and debug issues such as date handling and timer behavior. I tested and refined the features during development.

## Built For

Created for **Global Hack Week: Hacktoberfest** by Major League Hacking, as part of *Challenge 1: Build a Mini App with Cursor*.

