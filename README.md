# Blog API Project

This is a simple Blog API project developed as part of the Web Development Udemy course. The project demonstrates the creation of a RESTful API using Node.js, Express, and MongoDB.

## Features

- User authentication and authorization
- CRUD operations for blog posts
- Commenting system
- Error handling and validation

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- JWT (JSON Web Tokens)
- bcrypt

## Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/rajbhai129/Blog-Web-Application.git
2. Navigate to the project directory:
    cd Blog-Web-Application
 3. Install the dependencies:
        npm install
Configuration:
1. Create a .env file in the root directory and add the following environment variables:
     PORT=3000
  MONGODB_URI=your_mongodb_uri
  JWT_SECRET=your_jwt_secret
2. Start index.js to run the API on localhost:4000:
    node index.js
3. Start server.js to use the API on localhost:3000:
    node server.js
4. The API will be available at http://localhost:3000.

API Endpoints:
GET /posts - Retrieve all posts
GET /posts/:id - Retrieve a specific post by ID
POST /posts - Create a new post
PATCH /posts/:id - Update a specific post by ID
DELETE /posts/:id - Delete a specific post by ID
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Thanks to the Udemy course instructor Angela Yu Ma'am for the guidance and support.