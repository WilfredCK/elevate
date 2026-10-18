# Elevate — Workplace Digital Learning Prototype

A responsive, browser-based mock-up for corporate digital awareness and literacy training.

## Run it
1. Extract `elevate_learning_platform.zip`.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox or Safari).
3. No build tools or server are required. An internet connection is only needed for the optional Google Fonts; the system font fallback will work offline.

## What to explore
- Overview dashboard with progress, recommended courses and learning reminders.
- Course catalogue with search, category and difficulty filters.
- Course detail pages with sample lesson content, lesson-by-lesson progress and interactive multiple-choice quizzes.
- Pass mark of 70%; passing issues a demo certificate that can be viewed/printed.
- My Learning and Certificates pages.
- Manager team-progress table, employee search/filter, reminder feedback and CSV export.
- Required learning: create and edit assignments, select a course, audience, due date and mandatory/recommended priority.
- Responsive layout, hover states, navigation, toast messages and mobile sidebar.
- Progress and demo assignments persist in browser `localStorage`. Use the browser's site-data controls to reset the demo.

## Files
- `index.html` — page structure.
- `styles.css` — visual design and responsive behaviour.
- `app.js` — interactions, navigation, quizzes, progress, assignments and certificates.
- `data.js` — editable sample courses, lessons, quiz questions, employees and assignments.

## Important prototype boundaries
This is a front-end demo with illustrative content and sample learner counts/ratings. It does not authenticate real employees, send real reminders, enforce mandatory learning across devices, provide a secure manager/employee permission model, or issue accredited certificates. Those require a backend, identity provider, access controls, central database, notification service, audit logs and production-approved course content. Browser-local data can be cleared by the user.

## Suggested production essentials
- Employee SSO and role-based learner/manager/admin access.
- Course publishing, versioning, accessibility and multilingual content.
- Secure central progress tracking and deadline reminders.
- Assignment targeting by department, role, location and onboarding status.
- Assessment randomisation, retake rules, question banks and audit trail.
- Verifiable certificates, reports and LMS/LRS integration (e.g. SCORM/xAPI where needed).
- Privacy controls, retention rules, backups and organisation-specific security guidance.
