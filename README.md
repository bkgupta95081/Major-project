# Wanderlust 

Wanderlust is a full-stack web application for exploring and managing property listings. Users can browse available properties, view listing details, and add their own properties.

I built this project using **Node.js, Express.js, MongoDB, Mongoose, and EJS**. It helped me gain practical experience in building a complete web application with authentication, CRUD operations, validation, sessions, and image uploads.

## About the Project

The idea behind Wanderlust is to create a simple platform where users can find and manage vacation property listings.

Users can:

* Browse available properties
* View details of a property
* Create a new listing
* Edit a listing
* Delete a listing
* Register and log in
* Upload images for listings
* Get success and error messages

The application also uses authentication and authorization to protect certain actions.

## Features

### User Authentication

* User registration and login
* User logout
* Session management using Express Session
* Authentication using Passport.js
* Authorization for protected actions

### Property Listings

* View all listings
* View individual listing details
* Create new listings
* Edit existing listings
* Delete listings
* Add images to listings
* Display property information and price

### Form Validation

* Server-side validation using Joi
* Validation before saving listing data to the database

### Image Upload

* Image upload using Multer

### User Experience

* Flash messages for success and error notifications
* Dynamic pages using EJS
* Reusable layouts using EJS-Mate

## Technologies Used

### Frontend

* HTML
* CSS
* EJS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* Passport.js
* Passport-Local
* Passport-Local-Mongoose

### Other Technologies

* Joi
* Multer
* Express Session
* Connect Flash
* Cookie Parser
* Method Override

## Project Structure

```text
Major-project/
│
├── init/
├── models/
├── views/
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

### Main folders and files

* **`init/`** – Contains files used for initializing or adding sample data.
* **`models/`** – Contains the Mongoose models used to work with MongoDB.
* **`views/`** – Contains the EJS templates used to display the application pages.
* **`app.js`** – Main application file where the Express server and routes are configured.
* **`package.json`** – Contains project information and required dependencies.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/bkgupta95081/Major-project.git
```

### 2. Navigate to the project folder

```bash
cd Major-project
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start MongoDB

Make sure MongoDB is running on your system.

### 5. Start the application

```bash
node app.js
```

### 6. Open the application

Open your browser and go to:

```text
http://localhost:8080
```

## Database

This project uses **MongoDB** to store application data and **Mongoose** to interact with the database.

The database is used to store information about users and property listings.

## What I Learned

While working on this project, I learned how different parts of a full-stack application work together.

Some of the main things I learned are:

* Creating a server using Express.js
* Connecting Node.js with MongoDB
* Creating Mongoose schemas and models
* Performing CRUD operations
* Creating and handling Express routes
* Working with middleware
* Implementing authentication using Passport.js
* Managing user sessions
* Implementing authorization
* Validating data using Joi
* Uploading images using Multer
* Rendering dynamic pages using EJS
* Using Git and GitHub for version control

## Future Improvements

Some features I would like to add in the future are:

* Search and filtering
* Reviews and ratings
* Booking functionality
* Payment integration
* Map integration
* Improved error handling
* More responsive UI
* Deployment using a cloud database and hosting service

