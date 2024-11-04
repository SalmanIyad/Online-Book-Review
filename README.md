# Online Book Review - BackEnd App - IBM Project

Welcome to the IBM Project Online Book Review - BackEnd App, a project developed as part of the IBM Course **"Developing Back-End Apps with Node.js and Express."** This application provides a RESTful API for book enthusiasts, enabling them to manage books, share reviews, and interact seamlessly with book-related data. The application is built using **Node.js**, **Express.js**, and **MySQL** with **Sequelize.js** as the ORM.

---

## Overview

The Online Book Review Server-Side Application allows users to:
- **Register** and manage their accounts.
- **Add, update, and delete** books from the collection.
- **Write, edit, delete, and read** reviews for books.

Whether you are an avid reader looking to share your insights or a developer exploring the power of back-end development with Node.js and Express, this application offers a structured and robust foundation.

---

## Prerequisites

Before running the application, ensure you have the following installed on your system:
1. **Node.js**: Download it from [nodejs.org](https://nodejs.org/).
2. **MySQL**: Download MySQL from [mysql.com](https://www.mysql.com/) and make sure it is running.

---

## Getting Started

Follow these steps to set up and run the application:

### 1. Clone the Repository
   ```bash
   git clone https://github.com/SalmanIyad/ibm-final-project
   ```
   
### 2. Navigate to the Project Directory
   ```bash
   cd book-review-ibm-project
   ```
   
### 3. Install Dependencies
   Using **Bun** (your chosen package manager), install the project dependencies:
   ```bash
   bun install
   ```

### 4. Configure Environment Variables
   - Create a new MySQL database named `book_reviews` or use your preferred name.
   - Open the `.env` file in your project folder and configure it with your MySQL credentials:
     ```env
     PORT=3000
     DATABASE_NAME=book_reviews
     DATABASE_USERNAME=your_mysql_username
     DATABASE_PASSWORD=your_mysql_password
     DATABASE_HOST=localhost
     SALT_ROUNDS=10
     TOKEN_SECRET_KEY=your_strong_secret_key
     ```
   
### 5. Start the Application
   To run the server, use:
   ```bash
   bun run start
   ```
   or, for automatic server restarts during development, use:
   ```bash
   bun run dev
   ```

---

## API Documentation

For a complete guide on using the API, visit our detailed [API Documentation](https://documenter.getpostman.com/).

---

## Core Features

- **User Management**: Easily register, log in, and manage your user account.
- **Book Management**: Add new books, update existing ones, delete books, and browse the complete collection.
- **Review Management**: Write detailed reviews, edit or delete your reviews, and read reviews from other users.

---

## Technologies Used

- **Node.js**: High-performance JavaScript runtime environment.
- **Express.js**: Minimalist and powerful web framework for Node.js.
- **MySQL**: Reliable and efficient relational database management system.
- **Sequelize.js**: A promise-based ORM for Node.js, simplifying MySQL operations.

---

## Contact Information

For questions, support, or to contribute to the project, please feel free to reach out:

- **Email**: [SalmanIyad@ieee.org](mailto:SalmanIyad@ieee.org)
- **GitHub**: [SalmanIyad at GitHub](https://github.com/SalmanIyad)
- **LinkedIn**: [SalmanIyad at Linkedin](https://www.linkedin.com/in/SalmanIyad)
- **Twitter**: [SalmanIyad at Twitter](https://www.twitter.com/EngSalmanIyad)

---

Enjoy using the Online Book Review Server-Side Application, and feel free to contribute or provide feedback to help improve the project!


