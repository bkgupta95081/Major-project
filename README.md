# Wanderlust 

Wanderlust is a full-stack web application for exploring and managing property listings. Users can browse available properties, view individual listing details, and add their own listings.

The application is built using **Node.js, Express.js, MongoDB, Mongoose, and EJS**. It also includes user authentication, authorization, form validation, image uploads, sessions, and flash messages.

## About the Project

The main goal of Wanderlust is to provide a simple platform for managing vacation property listings.

Users can:

* Browse available property listings
* View details of a particular property
* Create a new listing
* Edit their listings
* Delete their listings
* Register and log in
* Upload images for listings
* Receive success and error messages

Authentication and authorization are used to control access to protected features.

## Features

### User Authentication

* User registration and login
* User logout
* Session management using Express Session
* Authentication using Passport.js
* Authorization for protected operations

### Property Listings

* View all listings
* View individual listing details
* Create new listings
* Edit existing listings
* Delete listings
* Display property images
* Display property information and price

### Form Validation

* Server-side validation using Joi
* Validation of listing data before saving it to the database

### Image Upload

* Image upload functionality using Multer

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

* **`models/`** – Contains the Mongoose models used for database operations.
* **`views/`** – Contains the EJS templates used to render the application's pages.
* **`init/`** – Contains initialization or seed-related files.
* **`app.js`** – Main application file where the Express server and application configuration are handled.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/bkgupta95081/Major-project.git
```

### 2. Navigate to the project directory

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

Open your browser and visit:

```text
http://localhost:8080
```

## Database

The project uses **MongoDB** for storing application data and **Mongoose** for interacting with the database.

The database stores information related to users and property listings.

## What I Learned

While developing this project, I gained practical experience with:

* Building a web server using Express.js
* Connecting Node.js applications with MongoDB
* Creating Mongoose schemas and models
* Implementing CRUD operations
* Creating and handling Express routes
* Working with middleware
* Implementing authentication using Passport.js
* Managing user sessions
* Implementing authorization
* Validating user input using Joi
* Handling image uploads using Multer
* Rendering dynamic pages using EJS
* Using Git and GitHub for version control

## Future Improvements

* Search and filtering
* Booking functionality
* Payment integration
* Improved error handling
* More responsive UI
* Deployment using a cloud database and hosting service


