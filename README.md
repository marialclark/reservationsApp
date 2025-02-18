# Lunchly

## Overview

Lunchly is a restaurant reservation management system that allows users to add, edit, and view customer details and their reservations. Built with **Node.js, Express, and PostgreSQL**, it provides a simple and efficient way for restaurants to manage their customers.

## Tech Stack

- **Backend:** Node.js, Express
- **Database:** PostgreSQL
- **Templating Engine:** Nunjucks
- **Styling:** Bootstrap (Bootswatch Minty theme)

## Installation & Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/Lunchly
   cd Lunchly
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Set up the database**
   - Ensure you have **PostgreSQL** installed and running.
   - Run the following commands to set up the schema and seed data:
     ```sh
     psql < schema.sql
     psql < seed.sql
     ```

4. **Run the server**
   ```sh
   node server.js
   ```
   The application will be available at `http://localhost:3000`

## Features

- **Customer Management:** Add, edit, and view customer details
- **Reservations:** Create, edit, and view reservations for each customer
- **Search Functionality:** Easily search for customers by name
- **Dynamic Templating:** Uses Nunjucks for rendering HTML pages
- **Bootstrap Styling:** Clean and responsive design for an enhanced user experience

## Authentication & Security

- **Middleware for Error Handling:** Ensures robust error responses
- **Input Validation:** Prevents bad data entry

## Contributors

- **Maria L. Clark** - Full-Stack Developer
