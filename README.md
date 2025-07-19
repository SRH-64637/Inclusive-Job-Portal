# Inclusive Job Portal for Neurodivergent Individuals

## Project Overview

This web application is a job portal specifically designed to support neurodivergent individuals (such as those with ADHD, autism, dyslexia, etc.). The goal is to provide an inclusive and accessible platform that not only lists jobs but also ensures compatibility between job environments and user needs. The project is built using Node.js, Express.js, raw MySQL, and HTML/CSS.

## Key Objectives

- Promote inclusive hiring by connecting neurodivergent job seekers with suitable employers.
- Allow employers to specify accommodations and work environments.
- Match job seekers to roles based on their stated preferences and needs.
- Focus on essential database functionality, adhering to the goals of a DBMS course.

---

## Core Features (Essential Functional Requirements)

These are the non-negotiable features that define the core functionality of the system. Without them, the platform cannot fulfill its intended purpose.

1. **Job Posting by Employers**
   - Employers can create detailed job listings, including work type (remote/hybrid), required skills, and accommodations offered.

2. **Job Browsing and Filtering**
   - Job seekers can browse and filter jobs based on keywords, company, location, work mode, and accessibility support.

3. **Neurodivergent Profile & Preferences**
   - Job seekers can create profiles where they specify preferences such as remote work, flexible hours, and necessary accommodations.

4. **Job Application System**
   - Users can apply to jobs directly through the platform, which creates an application record linked to both job and user.

5. **Application Status Tracking**
   - Employers can update application status (e.g., “pending,” “shortlisted,” “rejected”), and users can view this in their dashboard.

6. **Employer Dashboard**
   - Employers can view and manage the jobs they've posted and monitor incoming applications with applicant details.

7. **User Dashboard**
   - Users can see the jobs they’ve applied to, view their status, and edit their profile and preferences.

8. **Skill Matching or Compatibility Indicator**
   - Basic algorithm or logic to suggest jobs that best match a user’s skills and preferred accommodations.

---

## Suggested Database Schema (MySQL)

### Tables Overview

| Table Name        | Purpose                                               |
|-------------------|-------------------------------------------------------|
| `users`           | Stores both job seekers and employers                 |
| `profiles`        | Additional data specific to job seekers               |
| `employers`       | Additional data specific to employers                 |
| `jobs`            | Job listings created by employers                     |
| `applications`    | Stores job applications made by users                 |
| `skills`          | List of technical and soft skills                     |
| `user_skills`     | Many-to-many table connecting users to skills         |
| `job_skills`      | Many-to-many table connecting jobs to required skills |
| `accommodations`  | Optional accommodations employers offer               |
| `user_preferences`| Accommodations and work settings preferred by job seekers |

