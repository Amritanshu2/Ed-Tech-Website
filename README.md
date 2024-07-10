# EdTech Platform

## Main Page

**EdTech Platform** is a comprehensive platform enabling users to create, consume, and rate educational content. Built with the MERN stack (ReactJS, NodeJS, MongoDB, and ExpressJS), it offers an interactive and engaging learning experience for students and a platform for instructors to showcase their expertise globally.

### Table of Contents
1. [Introduction](#introduction)
2. [System Architecture](#system-architecture)
3. [Front-end](#front-end)
4. [Back-end](#back-end)
5. [Database](#database)
6. [API Design](#api-design)
7. [Installation](#installation)
8. [Configuration](#configuration)
9. [Usage](#usage)

### Introduction
The platform aims to provide a seamless learning experience and connect instructors with learners worldwide. This document details the platform's technical aspects, including system architecture, API design, installation, and usage instructions.

### System Architecture
The platform consists of three main components: the front-end, the back-end, and the database, following a client-server architecture.

### Front-end
Built with ReactJS, the front-end creates dynamic and responsive user interfaces and communicates with the back-end via RESTful API calls.

#### Front End Pages
- **For Students:**
  - **Homepage:** Introduction with links to the course list and user details.
  - **Course List:** Displays available courses with descriptions and ratings.
  - **Wishlist:** Shows courses added to the wishlist.
  - **Cart Checkout:** Allows course purchases.
  - **Course Content:** Presents videos and related material for a course.
  - **User Details:** Displays and allows editing of the student's account details.

- **For Instructors:**
  - **Dashboard:** Overview of courses with ratings and feedback.
  - **Insights:** Detailed course metrics.
  - **Course Management:** Create, update, and manage courses and pricing.
  - **Profile Details:** View and edit account details.

**Front-end Tools and Libraries:**
- **ReactJS**
- **CSS & Tailwind**
- **Redux**

### Back-end
Using NodeJS and ExpressJS, the back-end provides APIs for user authentication, course management, and media processing. It handles user data and course content storage.

#### Back-end Features
- **User Authentication:** Email/password login, OTP verification, and forgot password.
- **Course Management:** CRUD operations for courses, content, and media.
- **Payment Integration:** Razorpay for handling payments.
- **Cloud-based Media Management:** Cloudinary for media storage and management.
- **Markdown Formatting:** For course content.

**Back-end Frameworks, Libraries, and Tools:**
- **Node.js**
- **Express.js**
- **MongoDB**
- **JWT**
- **Bcrypt**
- **Mongoose**

### Database
The platform uses MongoDB, a NoSQL database, to store course content, user data, and other relevant information.

### API Design
The RESTful API is built using Node.js and Express.js, utilizing JSON for data exchange and supporting standard HTTP methods (GET, POST, PUT, DELETE).

### Installation
1. Clone the repository: `https://github.com/ankitmalik84/Code_Infinity_`
2. Navigate to the project directory: `cd Code_Infinity_`
3. Install dependencies: `npm install`

### Configuration
1. Set up a MongoDB database and obtain the connection URL.
2. Create a `.env` file in the root directory with the following variables:
   ```
   MONGODB_URI=<your-mongodb-connection-url>
   JWT_SECRET=<your-jwt-secret-key>
   ```

### Usage
1. Start the server: `npm start`
2. Open a new terminal and navigate to the client directory: `cd client`
3. Start the React development server: `npm run start`
4. Access the application in your browser at `http://localhost:3000`.

### Architecture Diagram
A high-level architecture diagram illustrates the system components and their interactions.

---
