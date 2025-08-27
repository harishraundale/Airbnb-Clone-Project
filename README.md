🌍 WanderLust Project 🏡
Project Summary
WanderLust is a comprehensive Full Stack Web Development project designed to facilitate the browsing and booking of vacation accommodations, including houses, villas, and farmhouses. This platform allows users to add their own properties to the listing, providing a diverse range of options for potential renters. Key features include a seamless booking system that simplifies the reservation process and real-time property location views via Mapbox API. To enhance user experience and security, the application supports fast login options through Google OAuth and GitHub OAuth. The application also boasts a dynamic server for responsive performance and an intuitive, aesthetically pleasing user interface, ensuring an engaging and efficient user experience.

Front-end 🌐
Technologies Used: HTML, CSS, JavaScript, Bootstrap, EJS
Frameworks: React.js
Features:
📱 Responsive Design: Optimized for various devices
🔍 User-friendly Interface: For searching and listing properties
🗺️ Mapbox API Integration: For location-based search and property mapping
Back-end 🛠️
Technologies Used: Node.js, Express.js
Features:
🧩 RESTful API: Handles user interactions
🔒 User Authentication and Authorization: Using Passport.js and JWT (JSON Web Tokens)
📄 Endpoints: For property listing, login/sign up, and user management
🏷️ Seamless Booking System: Simplifies the reservation process
Database 🗄️
Database Management System: MongoDB Atlas
Features:
🗂️ Structured Database Schema: For efficient data management
🔍 Database Queries: To retrieve and store property and user information
Cloudinary Image Storage ☁️
Image Hosting: All listing images are securely stored on Cloudinary, providing reliable and efficient image hosting. This ensures that images are easily accessible, optimized for performance, and enhance the overall user experience.

# Wanderlust Web Project Installation Guide

This guide will walk you through the installation process for the Wanderlust web project. Follow the steps below to set up the project locally on your machine.

## Prerequisites

Before you begin, make sure you have the following installed on your system:

- Node.js (version 18 recommended)
- MongoDB
- Nodemon (installed globally)

## Installation Steps

1. Clone the Wanderlust repository from GitHub:

   ```
   git clone https://github.com/gawandeabhishek/Wanderlust-Major-Project.git
   ```

2. Set up the database:
   - Create a `.env` file in the root directory of the project.
   - Add the following line to the `.env` file:

     ```
     ATLASDB_URL=mongodb://127.0.0.1:27017/wanderlust
     ```

3. Set up Cloudinary:
   - Go to [Cloudinary](https://cloudinary.com/) and sign up for a free account.
   - Once logged in, obtain your Cloudinary `CLOUD_NAME`, `CLOUD_API_KEY`, and `CLOUD_API_SECRET`.
   - Add these values to the `.env` file:

     ```
     CLOUD_NAME=your_cloud_name
     CLOUD_API_KEY=your_api_key
     CLOUD_API_SECRET=your_api_secret
     ```

4. Set the secret for your Cloudinary storage:
   - Add a `SECRET` key to your `.env` file and set it to a secure value:

     ```
     SECRET=your_cloudinary_secret
     ```

5. Install project dependencies using npm:

   ```
   npm install
   ```

6. Run the application using Nodemon:

   ```
   nodemon app.js
   ```

7. Access the project:
   - Once the server is running, you can access the project at [http://localhost:8080](http://localhost:8080).

That's it! You have successfully installed and set up the Wanderlust web project on your local machine. If you encounter any issues during the installation process, feel free to reach out for assistance. Happy traveling! 🌍✈️
