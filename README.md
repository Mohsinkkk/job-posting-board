# job-posting-board

# Job Posting Board with Email Automation

This is a full-stack **Job Posting Board** application built with the **MERN** stack (MongoDB, Express.js, React.js, Node.js). Companies can register, verify their accounts via email, post jobs, and send automated email alerts to candidates about job postings.

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [File Structure](#file-structure)
- [Setup Instructions](#setup-instructions)
- [Running the Project](#running-the-project)
- [Project Live Link](#project-live-link)
- [License](#license)

## Project Overview

This project allows companies to:
- Register and authenticate via email.
- Post job listings with details like title, description, experience level, and end date.
- Send automated email alerts to candidates regarding job postings.
- Use JWT-based authentication for secure access to job posting functionality.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB (MongoDB Atlas for cloud database)
- **Email Service**: Nodemailer (for email automation)
- **Authentication**: JWT (JSON Web Token)
- **Deployment**:
  - **Frontend**: Vercel (for React app deployment)
  - **Backend**: Heroku (for Node.js/Express backend deployment)

## File Structure

```plaintext
.
├── .env                  # Environment variables (MONGO_URI, JWT_SECRET, EMAIL settings)
├── controllers/           # Backend controllers handling business logic
├── models/                # MongoDB models (schemas for companies, jobs, etc.)
├── node_modules/          # Node.js modules (dependencies)
├── package-lock.json      # Package lock for npm dependencies
├── package.json           # Project dependencies and scripts
├── routes/                # API routes for handling requests
├── server.js              # Main backend file to start the server
├── services/              # Helper services (e.g., email sending)
├── utils/                 # Utility functions (e.g., database connection)
