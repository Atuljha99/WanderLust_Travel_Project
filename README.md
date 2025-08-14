<<<<<<< HEAD
"WanderLust (Tour and Travels Project)" 
=======
# WanderLust_Travel_Project
The Wanderlust Project is a full-stack travel listing web application designed to help users explore, view, and manage travel destinations. It allows travelers to browse available destinations, see details about each location, and manage their own listings.

Key Features:

Dynamic Travel Listings: Users can view travel destinations stored in a MongoDB database, including images, descriptions, and prices.

User Authentication: Implemented a login and registration system using hashing for secure password storage.

Add / Edit / Delete Listings: Authenticated users can create new travel listings, edit their existing ones, or delete them.

Responsive UI: Designed with EJS templates, CSS, and JavaScript for a mobile-friendly and user-friendly interface.

Database Management: Integrated Mongoose to interact with MongoDB for storing travel data and user accounts.

Scalable Structure: Built using Node.js and Express.js to handle future feature expansion.

Tech Stack:

Frontend: HTML, CSS, JavaScript, EJS

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Security: Password hashing using bcrypt

Purpose of the Project:
The goal of the Wanderlust Project is to create a functional and secure travel platform that provides real-time travel listings with user authentication and admin capabilities, making it easy for travelers and property owners to connect.

how to install:
1. Clone the Wanderlust repository from GitHub:
   git@github.com:Atuljha99/WanderLust_Travel_Project.git


2. Set up the database:

Create a .env file in the root directory of the project.
Add the following line to the .env file:
ATLASDB_URL=mongodb://127.0.0.1:27017/wanderlust



3.Set up Cloudinary:
Go to Cloudinary and sign up for a free account.
Once logged in, obtain your Cloudinary CLOUD_NAME, CLOUD_API_KEY, and CLOUD_API_SECRET.
Add these values to the .env file:
CLOUD_NAME=your_cloud_name
CLOUD_API_KEY=your_api_key
CLOUD_API_SECRET=your_api_secret


4.Set the secret for your Cloudinary storage:
Add a SECRET key to your .env file and set it to a secure value:
SECRET=your_cloudinary_secret


5. Install project dependencies using npm:
npm install


6. Run the application using Nodemon:
nodemon app.js


7.Access the project:
Once the server is running, you can access the project at http://localhost:8000.






>>>>>>> ac8cccdaad41a549302684223bc9f2798bf05a24


