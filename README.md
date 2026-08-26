# Wanderlust

**Wanderlust** is a full-stack web application where users can explore vacation properties and manage their own property listings.

I built this project to get hands-on experience with **Node.js, Express.js, MongoDB, Mongoose, EJS, authentication, CRUD operations, validation, sessions, and image uploads**.

The main idea was to build a simple platform where users can discover properties and also create and manage their own listings.

---

## Features

### User Authentication

* User registration and login
* User logout
* Authentication using Passport.js
* Session management using Express Session
* Authorization for protected actions

### Property Listings

* View all available properties
* View individual property details
* Create new listings
* Edit existing listings
* Delete listings
* Upload images for properties
* Display property information and price

### Form Validation

* Server-side validation using Joi
* Validate listing data before saving it to MongoDB

### Image Upload

* Upload property images using Multer
* Display uploaded images with listing information

### User Experience

* Success messages using Flash
* Error messages for failed operations
* Dynamic pages using EJS
* Reusable layouts using EJS-Mate

---

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

---

## Project Structure

```text
Major-project/
│
├── init/                 # Sample/initial data
├── models/               # Mongoose models
├── views/                # EJS templates
├── app.js                # Main application file
├── package.json          # Project dependencies
├── package-lock.json
└── README.md
```

### Important Files & Folders

* **`init/`** – Contains files used for initializing or adding sample data.
* **`models/`** – Contains Mongoose schemas and models used to interact with MongoDB.
* **`views/`** – Contains EJS templates used to render the application's pages.
* **`app.js`** – Main application file where the Express server, middleware, routes, and database connection are configured.
* **`package.json`** – Contains project information, scripts, and dependencies.

---

## Getting Started

Follow these steps to run Wanderlust locally.

### 1. Clone the Repository

```bash
git clone https://github.com/bkgupta95081/Major-project.git
```

### 2. Move Into the Project

```bash
cd Major-project
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start MongoDB

Make sure MongoDB is installed and running on your system.

### 5. Start the Application

```bash
node app.js
```

### 6. Open in Browser

Visit:

```text
http://localhost:8080
```

---

## Database

Wanderlust uses **MongoDB** as the database and **Mongoose** to communicate with MongoDB.

The database stores information such as:

* User accounts
* Property listings
* Listing images
* Property details

Mongoose schemas help define the structure of the data and make it easier to perform database operations.

---

## What I Learned

Building Wanderlust helped me understand how the different parts of a web application work together.

During this project, I learned:

* How to build a server using Express.js
* How to connect Node.js with MongoDB
* How to create Mongoose schemas and models
* How CRUD operations work
* How to create and handle Express routes
* How middleware works in Express
* How authentication works using Passport.js
* How authorization protects user actions
* How sessions and cookies work
* How to validate data using Joi
* How to handle image uploads using Multer
* How to render dynamic pages using EJS
* How to use Git and GitHub for version control



## Future Improvements

There are still several things I would like to improve in Wanderlust:

* Search and filtering
* Reviews and ratings
* Booking functionality
* Payment integration
* Map integration
* Better error handling
* More responsive UI
* Deployment using a cloud database and hosting service



