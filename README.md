# E‑Voting System (Demo)

## Overview

This project is a prototype web-based E‑Voting system designed to demonstrate the core functionalities of a secure and transparent electronic voting platform. Developed as a proof of concept, this demo serves to showcase how digital technologies can modernize and streamline the electoral process by providing a reliable, accessible, and tamper-resistant voting experience.

**Note:** This is a demo version of the E‑Voting system, developed as part of a submission for the **Google Developer Group (GDG)** community event. While it demonstrates essential features such as voter authentication, ballot casting, and result tallying, it is intended for conceptual and academic purposes. It can be improved and redesigned into a production-grade system with enhanced security, scalability, and features.

👉 **Live Demo (Temporary Hosting):**
[https://dattathemaster.github.io/E-Voting/](https://dattathemaster.github.io/E-Voting/)

## Project Vision

The core idea behind this E‑Voting system is to digitize and simplify the election process while maintaining integrity, transparency, and accessibility. It addresses common challenges in traditional voting systems, such as manual errors, physical infrastructure, time delays, and limited access.

### Key Objectives:

* Ensure secure and authenticated access for each voter
* Provide a clean and user-friendly interface for casting votes
* Enable election administrators to manage elections with minimal overhead
* Display real-time or post-election results instantly
* Lay the foundation for future integration with blockchain or biometric verification systems

## Features

* Voter Authentication – Secure login and identity verification for voters
* Vote Casting – One vote per person per election with clear ballot UI
* Election Management – Admins can create, schedule, and manage elections and candidates
* Result Generation – Accurate, real-time result calculation and display
* Auditability (Demo) – Vote logs and summaries visible to admin for basic transparency
* Extensible Architecture – Can be redesigned or extended into more robust models (e.g., blockchain, smart contracts, decentralized ID)

## Technologies Used

* Frontend: HTML, CSS, JavaScript
* Backend: PHP / Node.js *(update based on actual tech stack)*
* Database: MySQL
* Hosting/Deployment: Localhost or web server *(can be adapted to cloud platforms)*

## How to Run (Local Setup)

1. Clone the repository

   ```
   git clone https://github.com/DattaTheMaster/E-Voting.git
   cd E-Voting
   ```

2. Install dependencies *(if applicable)*

3. Set up the database

   * Import the provided SQL file into MySQL
   * Update database credentials in the config file

4. Start the server

   * Run on XAMPP/LAMP or your local web server

5. Access the website

   * Open browser and go to `http://localhost/E-Voting/`

## User Roles

**Admin:**

* Login to create/manage elections, candidates, and voter data
* Monitor vote counts and download reports

**Voter:**

* Login to view active elections and cast a single vote
* View results once published

## Future Enhancements

This demo project can evolve into a full-fledged e-voting platform with:

* Blockchain integration for tamper-proof records
* Biometric/OTP-based voter validation
* Role-based access and encryption for high security
* Mobile/responsive design and accessibility improvements
* Integration with government ID verification APIs

## Contributing

We welcome suggestions and contributions! If you're interested in improving or extending this system:

1. Fork the repository
2. Create a new branch (`feature/improvement-name`)
3. Commit your changes
4. Submit a Pull Request
