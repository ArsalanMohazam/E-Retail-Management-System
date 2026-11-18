# E-Retail Management System

A secure, universal, and modular full-stack retail management system built with the MERN stack. Designed to adapt seamlessly to various retail business types (such as pharmacies, grocery marts, and hardware stores) while maintaining strict enterprise-grade security and role-based data integrity.

## Key Architectural Features

* **Universal Design:** Dynamic configuration layout that accommodates multiple retail sectors without hardcoding.
* **Role-Based Access Control (RBAC):** Strict operational separation across 4 distinct user roles:
  * **Admin:** System oversight, user management, and high-level configurations.
  * **Purchaser:** Managing vendor orders, stocking items, and logging wholesaler details.
  * **Seller:** Handling daily point-of-sale transactions and real-time inventory deductions.
  * **Auditor:** Reviewing uneditable master ledgers and financial logs for strict data integrity.
* **Security & Authentication:** 
  * JWT-based authentication securely managed via HttpOnly cookies.
  * Password hashing using Bcrypt.
  * Server-side input sanitization and strict validation loops to prevent frontend manipulation.

## Tech Stack

* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, Mongoose
* **Deployment:** Vercel (Frontend) & Render/Railway (Backend)

## Project Status

Currently in the **Initial Architecture & Planning Phase**. Incremental updates will be logged via commits as core modules are built and verified.
