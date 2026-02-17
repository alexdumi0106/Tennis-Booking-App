This repository contains my personal copy/portfolio version of a collaborative project developed with a teammate.

**Tennis Booking Web Application** is a full-stack web platform designed to simplify the process of reserving tennis courts in sports complexes. The system allows users to view available courts, select a time slot, and confirm their booking through a secure and intuitive interface.
The application was built using React for the frontend and Node.js (Express) for the backend, with PostgreSQL as the main database. The architecture follows a clean, layered structure, with separate modules for controllers, services, models, and routes, ensuring scalability and maintainability.
# Main Features:
## Court listing and details 
- Users can browse available tennis courts and view specific details such as location, surface type, and hourly availability.
## Online booking 
- Reservations can be made by selecting a date and time slot, entering user information, and confirming the booking.
## Email confirmation workflow 
- Users receive a confirmation email with a secure link. The booking is finalized only after the user confirms via that link, ensuring authenticity and preventing duplicate reservations.
## PIN code generation: 
- Each confirmed booking generates a unique 6-digit PIN for access verification at the sports facility.
## Admin dashboard 
- Administrators can manage courts and sports complexes, including adding, updating, and deleting entries.
# Technical Overview
## Frontend: React, Tailwind CSS, Axios
## Backend: Node.js, Express.js, PostgreSQL
## Architecture: MVC-style (controllers, services, models, routes)
## Database: PostgreSQL with relational schema (courts, sports_complexes, reservations)
## Email service: Nodemailer (with token-based verification)
## Version control: GitHub
