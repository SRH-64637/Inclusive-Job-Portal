# Job Portal for Neurodivergent People

## Overview

This project is an inclusive web-based job portal designed to support neurodivergent individuals. It enables employers to post accessible job listings and allows job seekers to search, filter, and apply to jobs that align with their specific needs. The platform aims to bridge the employment gap for neurodivergent communities by reducing barriers in the job search and hiring process.

## Features

### User Management
- Register and login with role-based access (job seeker or employer)
- Secure authentication with password hashing
- Profile includes disability-related preferences or support needs

### For Employers
- Post job listings with accessibility details
- View and manage applications received for posted jobs

### For Job Seekers
- Search and filter jobs based on accessibility and role
- Apply for jobs with a cover letter
- View applied jobs and application status

### Additional Features
- Tag-based filtering using accessibility or support tags
- RESTful API integration for seamless frontend-backend communication
- MySQL database design with properly normalized tables and foreign keys

## Tech Stack

- **Frontend**: React (or HTML/CSS/JavaScript)
- **Backend**: Node.js, Express
- **Database**: MySQL (raw SQL)
- **Containerization**: Docker, Docker Compose
- **Tools**: Postman (API testing), dbdiagram.io (ERD), bcrypt (auth)

## Database Schema

The following tables will be created in the `job_portal` MySQL database.
