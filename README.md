
# Wanderlust 

Wanderlust is a web application where users can explore different places to stay and add their own property listings.

I built this project to understand how a full-stack web application works using **Node.js, Express.js, MongoDB and EJS**. The project includes user authentication, listing management, image uploads, form validation and session handling.

## About the Project

The main idea behind Wanderlust is to provide a simple platform where users can:

* Browse available property listings
* View details of a particular property
* Add a new property listing
* Edit and delete listings
* Create an account and log in
* Upload images for listings
* See useful success and error messages

The project also uses authentication and authorization so that users can access features according to their login status.

## Features

### User Authentication

* User signup and login
* User logout
* Session management using Express Session
* Authentication using Passport.js

### Listings

* View all listings
* View individual listing details
* Add new listings
* Edit existing listings
* Delete listings
* Display property images
* Display price and property information

### Validation

* Form validation using Joi
* Server-side validation to prevent invalid data

### Image Upload

* Image upload using Multer

### User Experience

* Flash messages for success and error notifications
* EJS templates for dynamically displaying pages
* Reusable layouts using EJS-Mate

## Technologies Used

**Frontend**

* HTML
* CSS
* EJS

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB
* Mongoose

**Authentication**

* Passport.js
* Passport-Local
* Passport-Local-Mongoose

**Other Technologies**

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

The `models` folder contains the database models, while the `views` folder contains the EJS pages used to display the application.

The main application logic is handled through `app.js`.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/bkgupta95081/Major-project.git
```

### 2. Go inside the project folder

```bash
cd Major-project
```

### 3. Install the required packages

```bash
npm install
```

### 4. Start the application

```bash
node app.js
```

### 5. Open the application

Open your browser and visit:

```text
http://localhost:8080
```

## Database

This project uses **MongoDB** as the database and **Mongoose** to communicate with MongoDB.

The application stores information such as users and property listings in the database.

Make sure MongoDB is running before starting the application.

## What I Learned

Some of the important things I learned are:

* Creating a server using Express.js
* Connecting an application to MongoDB
* Creating Mongoose schemas and models
* Performing CRUD operations
* Creating routes in Express
* Using middleware
* Implementing user authentication with Passport.js
* Managing sessions
* Validating user input
* Uploading images using Multer
* Rendering dynamic pages using EJS
* Using Git and GitHub to manage the project

## Future Improvements

* Map integration
* Booking functionality
* Payment integration
* Deployment with a cloud database and hosting service

