# Nyanza Regional Job Application & Recruitment Management System

A full-stack enterprise web platform engineered to digitize, streamline, and centralize the talent acquisition and employment recruitment pipeline for regional logistics and operations at Nyanza. This system replaces fractured, paper-based application submissions with a secure, highly scalable automated hiring database.

## 🚀 Key Features

- **Multi-Role User Authentication:** Formulated distinct, JWT-protected portal dashboards with custom route privileges for Job Seekers (profile creation, document uploads), HR Recruiters (job creation, filtering), and Interview Panels (evaluations).
- **Dynamic Application Tracker:** Built a live status-tracking matrix that updates applicant pipelines in real-time (e.g., Applied, Under Review, Interview Scheduled, Shortlisted, Rejected).
- **Secure Document & Portfolio Management:** Integrated secure backend logic to handle, store, and link candidate resumes, certifications, and technical portfolios safely to their primary profile schemas.
- **Advanced Query Filtering:** Implemented server-side data sorting and filtering mechanics allowing HR administrators to parse hundreds of incoming records by specific criteria such as skills, education level, or years of experience.

## 🛠️ Technical Architecture

- **Frontend Interface:** React.js, Vite, Tailwind CSS *(or Laravel Blade if built with PHP)*
- **Backend Architecture:** Node.js, Express.js RESTful API endpoints *(or Laravel PHP MVC)*
  *(Note: Leave only the technologies you actually used for this specific project!)*
- **Database Layer:** MongoDB (Mongoose ODM) / PostgreSQL / MySQL  
  *(Note: Delete the database engines you did not use for this project!)*
- **Security Protocols:** Bcrypt password hashing, session tokens, and strict server-side form validation to prevent malformed text injections.

## 📈 Engineering Scope

The primary objective of this repository was to handle complex user access control and manage multi-layered file metadata without data leakage. The core focus was placed on optimizing database query speeds during high-volume applicant filtering and providing a clean, accessible interface for candidates navigating the regional recruitment pipeline.
