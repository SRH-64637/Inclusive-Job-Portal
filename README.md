Inclusive Community, Career, and Wellness Platform

## Project Summary

The is an all-in-one platform designed to support neurodivergent individuals (such as those with ADHD, dyslexia, autism, or anxiety) by offering a secure, skill-based, and stigma-free environment for professional development, mental wellness, and social connection.

The platform combines features such as an inclusive job board, wellness tools, digital planners, and community forums, making it suitable for regular daily or weekly use.

---

## Objective

To empower neurodivergent individuals by:
- Connecting them to inclusive, understanding employers
- Providing access to wellness tools and counseling
- Creating peer-driven community spaces
- Ensuring privacy, user choice, and skill-first engagement

---

## Core Features

1. **User Dashboard**  
   Central hub for managing jobs, routines, wellness logs, and messages.

2. **Inclusive Job Board**  
   Employers tag their job environments (e.g., "quiet workspace", "flexible hours") and commit to fair hiring practices.

3. **Routine Planner with Reminders**  
   Custom planners with optional notifications for daily structure and habit-building.

4. **Peer Forums and Group Chats**  
   Interest-based and anonymous spaces for discussion, support, and advice.

5. **Counseling and Support Booking**  
   Schedule sessions with licensed professionals or verified peer mentors.

6. **Daily Wellness Check-ins**  
   Track mood, energy, focus, and reflect with private logs.

7. **Achievement Tracker**  
   Visual progress through badges for engagement (e.g., attending events, applying to jobs).

8. **Personalized Resource Feed**  
   Curated materials including coping strategies, job prep, and easy-read guides.

---

## Security and Privacy

- Encrypted login and password storage (bcrypt, JWT)
- Role-based access control (users, employers, mentors, admins)
- Journal and counseling data encrypted at rest
- Moderation system for reporting and flagging content
- Full anonymity control in public and semi-public spaces

---

## Tech Stack

- Backend: Node.js with Express.js  
- Database: MySQL (with raw SQL queries)  
- Frontend: HTML, CSS  
- Authentication: JWT and bcrypt  
- Deployment: (To be configured based on host)

---

## Database Overview

### Key Tables
- `users` – User details with roles (job seeker, counselor, employer)
- `jobs` – Inclusive job listings with optional accommodations
- `applications` – Job applications and statuses
- `messages` – Forum posts and private messages
- `checkins` – Wellness logs by date
- `routines` – Daily planner entries
- `sessions` – Counseling and support appointments
- `resources` – Knowledge base and external tools
- `badges` – User achievements and progress markers

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neuroverse.git
   cd neuroverse
