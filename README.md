# Job-Portal-Using-Python-Django-

# Project Statement - Job Portal Django

The Job Portal System is a web application that was built using Python and Django framework. It is intended to serve as a portal/intermediary between the job seeking students/users and those seek in to employ. It is an effective platform for employment posting and search.
# Objective
The primary purpose of this project is to design a centralized system where:
Potential employees are able to browse jobs and apply for potential opportunities.
Can post jobs and view applications.
How Admin can monitor and control the system.

# Modules in the System
1. Admin Module
Secure login for admin users
View and manage all users and recruiters
Approve or reject recruiter registrations
Monitor job postings
Change system settings and passwords
2. User (Student) Module
User registration and login
Profile management (mobile, photo, sex etc.)
Search available jobs
See job details (pay, skills, location, experience)
Apply for jobs
3. Recruiter Module
Recruiter registration and login
Account approval by admin (access based on status)
Post, update, modify and remove jobs.
View applicants
Manage company profile
Database Structure (Key Models)
StudentUser
Linked with Django User
Personal details:mobile,gender and image source store.9. Personal details image.11 stores.
Recruiter
Stores recruiter/company details
Includes approval status (pending/accepted/rejected)
Job
Job title, salary, description
Required skills, experience, location
Start date, end date
Core Functionalities
User Access (Login/Logout through Django auth)
Role-based access (Admin, User, Recruiter)
Job posting and management
Recruiter approval workflow
Write dynamic web pages with Django templates.
File upload support (images)

# Technologies Used
Backend: Python, Django
Frontend: HTML, CSS, Bootstrap, JavaScript
Database: SQLite (default Django DB)
Authentication: Django built-in authentication Job Portal 

