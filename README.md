# task-manager-api

Task Manager API

Task-manager-API is a powerful and user-friendly Task Manager API built using Node.js, Express, MongoDB, and various cutting-edge technologies. It provides a seamless and efficient 
solution for managing tasks and users, with features like api-authentication, email notifications, file uploads, and more.

Installation
Clone the repository: git clone https://github.com/pruthvirajgn7/task-manager-api.git
Navigate to the project directory: cd task-manager-api
Install dependencies: npm install

Authentication
The API uses JSON Web Tokens (JWT) for user authentication. Only authorized users can access protected routes.

API Endpoints
User API
POST /users

Create a new user.
Required fields: name, email, password.
POST /users/login

User login.
Required fields: email, password.
GET /users/me

Get user profile.
PATCH /users/me

Update user profile.
Allowed fields: name, email, password, ...
DELETE /users/me

Delete user account.
Task API
POST /tasks

Create a new task.
Required fields: description.
GET /tasks

Get a list of tasks.
Optional queries: completed, sortBy, limit, skip.
GET /tasks/:id

Get task by ID.
PATCH /tasks/:id

Update task by ID.
Allowed fields: description, completed.
DELETE /tasks/:id

Delete task by ID.
File Uploads
Users can upload files, such as profile images, using the API. Uploaded files are stored securely and associated with the respective user's profile.

Email Notifications
The API utilizes the SendGrid service to send welcome and thank you emails to users upon registration and task completion.

Thank you
