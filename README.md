# Course Book

This project serves as a simple back-end for managing courses. It includes basic CRUD operations for courses and user authentication.

## Installation

1. Clone the repository:

   ```bash
   https://github.com/StanSNS/NodeJS-HandleBars.git

2. Navigate to the project directory:
    ```bash
   cd Course-Book

3. Install dependencies:
    ```bash
   npm install

## Usage 
- To start the server, run:
    ```bash
    npm start
This will start the server using nodemon, allowing for automatic restarts on file changes.

## Endpoints 
- GET /courses: Retrieve all courses.
- GET /courses/:id: Retrieve a specific course by ID.
- POST /courses: Create a new course.
- PUT /courses/:id: Update an existing course.
- DELETE /courses/:id: Delete a course by ID.

## Dependencies
- bcrypt: Library for hashing passwords securely.
- cookie-parser: Middleware to parse cookies in Express.
- express: Web framework for Node.js.
- express-handlebars: Handlebars view engine for Express.
- jsonwebtoken: Implementation of JSON Web Tokens for user authentication.
- mongoose: MongoDB object modeling for Node.js.
- nodemon: Utility to automatically restart the server on file changes.

## License
This project is licensed under the ISC License. See the LICENSE file for details.




