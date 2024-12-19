# “المنتقمون: فرع شبكات مصر”

## Team Members
- Hatem Yasser
- Walid Moussa
- Youssef Hesham
- Mariam Ayman
- Aly Tamer

Table of Contents

    •	Project Overview
    •	Features
    •	Project Structure
    •	Installation
    •	Configuration
    •	Usage
    •	Technologies Used
    •	Contributing
    •	License

## Project Overview

Digital Nomads is a web application developed using the MERN stack without React (MERN without the “R”). The project leverages HTML, CSS, JavaScript, Node.js, Express, and MongoDB Atlas. It demonstrates a well-structured web application with server-side rendering using EJS (Embedded JavaScript Templates). The project is designed to showcase core web development concepts and integrate MongoDB Atlas for backend data storage without using an ODM like Mongoose.

## Features

    •	Server-Side Rendering with EJS for dynamic content.
    •	RESTful API endpoints for backend communication.
    •	MongoDB Atlas Integration for database management.
    •	Express.js routing and middleware configuration.
    •	Static Assets served from the public folder.
    •	Basic CRUD Operations implemented for data handling.
    •	Responsive Design using HTML, CSS, and JavaScript.

## Project Setup
1. Initialize MongoDB:
   - Start MongoDB server: `mongod`
   - Launch MongoDB Compass for GUI interface
   - Open new terminal and launch mongo shell: `mongosh`
   - Create database: `use travel-web-app`

2. Project Setup:
   - Install dependencies: `npm install`
   - Ensure Node.js version 20.16.0:

     ```bash
     nvm use
     # or
     nvm use 20.16.0
     ```
   - Start application: `node app.js` or `npm run dev`

## Usage

    •	Running the server: npm run dev
    •	Navigating the app: Open http://localhost:3001

## Technologies Used

    •	HTML, CSS, JavaScript: Frontend structure and design.
    •	Node.js: JavaScript runtime for backend.
    •	Express.js: Web framework for routing and middleware.
    •	EJS: Templating engine for server-side rendering.
    •	MongoDB Atlas: Cloud database service for backend storage.
    •	dotenv: Managing environment variables securely.

## License

This project is created as an academic project for the CSEN503 course at the German University in Cairo. All rights are reserved for academic purposes. This is not an open-source project and does not have a specific license assigned to it.
