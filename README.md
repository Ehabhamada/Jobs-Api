# Jobs API
The Jobs API is a powerful MERN (MongoDB, Express.js, React.js, Node.js) stack application that provides secure authentication alongside CRUD (Create, Read, Update, Delete) functionality for job listings.


#### Setup
- install dependencies

```sh
npm install
```

- create .env and provide correct values
.env

```
MONGO_URI=
JWT_SECRET=
JWT_LIFETIME=
```
Features
Authentication: Includes secure registration and login routes for users.
Job Operations:
Create: Add new job listings.
Read: Retrieve all jobs or a single job by ID.
Update: Modify existing job details.
Delete: Remove a job entry from the database.
Technologies Used
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT-based authentication for secure user access.
Getting Started
Clone the repository.
Install dependencies using npm install.
Set up MongoDB and configure the database connection.
Run the application using npm start.
API Routes
Authentication
POST /api/auth/register: Register a new user.
POST /api/auth/login: Log in and receive an authentication token.
Job Operations
POST /api/jobs: Create a new job listing.
GET /api/jobs: Retrieve all job listings.
GET /api/jobs/:id: Get a single job by ID.
PATCH /api/jobs/:id: Update details of a specific job.
DELETE /api/jobs/:id: Delete a job entry.
Usage
Ensure you have MongoDB running. Modify the configuration files as necessary to connect to your database.

bash
Copy code
# Start the server
npm start
Save to grepper
Contributing
Contributions are welcome! Feel free to fork the repository and create a pull request with your improvements.

License
This project is licensed under the MIT License.
