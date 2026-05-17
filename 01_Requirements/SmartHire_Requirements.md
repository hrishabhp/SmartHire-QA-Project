# SmartHire Requirements Document

## Project Overview
SmartHire is a web-based recruitment platform designed to connect candidates and recruiters efficiently.

The application allows candidates to apply for jobs, recruiters to manage hiring, and admins to monitor platform activities.

---

# Modules & Requirements

## 1. Authentication Module

### Features
- User should be able to register using email and password
- User should be able to login with valid credentials
- Invalid login should display proper error message
- Forgot password functionality should send reset link
- User should be able to logout successfully

---

## 2. Candidate Module

### Features
- Candidate can create profile
- Candidate can upload resume in PDF/DOC format
- Candidate can search jobs
- Candidate can apply for jobs
- Candidate can track application status

---

## 3. Recruiter Module

### Features
- Recruiter can create job postings
- Recruiter can edit/delete jobs
- Recruiter can view applicants
- Recruiter can shortlist/reject candidates

---

## 4. Interview Scheduling Module

### Features
- Recruiter can schedule interview
- Candidate receives interview notification
- Recruiter can reschedule interview

---

## 5. Admin Module

### Features
- Admin can view all users
- Admin can block/unblock accounts
- Admin can monitor job postings

---

# Non-Functional Requirements

- Application should load within 3 seconds
- System should support modern browsers
- Password should be masked
- Session should expire after inactivity
- Unauthorized users should not access protected pages

---

# Assumptions

- Email notifications are simulated
- Payment gateway is not included
- Mobile responsiveness is basic