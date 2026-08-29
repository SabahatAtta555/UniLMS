# Northbridge University LMS — Standalone Demo

A complete, responsive university learning management system demo rebuilt from the uploaded LMS project into standalone HTML, CSS and vanilla JavaScript. The functional screens run through `index.html` using hash routing so one browser storage area is shared reliably; the other `.html` files are convenience entry points that redirect to the corresponding screen.

## Run
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Use one of the demo accounts below.

No Node.js, npm, backend, database, API keys, Docker, or local server is required.

## Demo accounts

| Role | Email | Password |
|---|---|---|
| Student | `student@northbridge.edu` | `Student123` |
| Instructor | `instructor@northbridge.edu` | `Faculty123` |
| Administrator | `admin@northbridge.edu` | `Admin123` |

## Main pages
- Dashboard
- My Courses
- Course Detail / Lessons / Progress
- Assignments with obtained/total marks and instructor grading and local submissions
- Quizzes and scoring
- Grades
- Attendance
- Calendar + personal events
- Messages
- Announcements
- Digital Library
- Profile
- Settings
- Instructor Workspace
- Administrator Workspace

## Working features
- Demo login validation, masked passwords, show/hide password, logout, protected pages
- Role-aware student, instructor and administrator experiences
- Course search and filters
- Persistent lesson completion and course progress
- Assignment submission state and file-name tracking
- Interactive quizzes and stored scores
- Messaging with persistent local conversation history
- Announcement read/unread state
- Instructor/admin announcement publishing
- Personal calendar events
- Profile editing for the student account
- Persistent notification/display preferences
- Demo data reset
- Responsive desktop/tablet/phone navigation

## Storage and privacy
All interactive demo state is stored in browser `localStorage` under `northbridgeLmsStateV1`. No credentials, files, messages, or profile data are sent to a server. File submissions store only the selected file name in the demo state.

## Notes
This is an unofficial educational/demo LMS project. It does not represent a real university or production student information system.


## Marks & Examination Results

- Graded assignments display obtained marks, total marks, percentage, grade, and instructor feedback.
- Grades includes separate Assignment Marks and Exam Marks tables.
- Sessional, Midterm and Final exam marks support Published/Pending status.
- The instructor demo account can add or edit assignment marks and publish exam marks; changes persist in localStorage and appear in the student views.

## Portfolio-Style Project Structure

This copy has been reorganized for simple portfolio/GitHub Pages deployment:

- Stylesheet: `css/styles.css`
- JavaScript: `js/app.js`
- Avatars: `images/avatars/`
- Branding: `images/brand/`
- Course artwork: `images/courses/`

All application logic and LMS pages are preserved.
