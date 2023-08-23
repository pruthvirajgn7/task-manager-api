# task-manager-api

Task Manager API

    Task-manager-API is a powerful and user-friendly Task Manager API built using Node.js, Express, 
    MongoDB, and various cutting-edge technologies.It provides a seamless and efficient solution for 
    managing tasks and users, with features like api-authentication, email notifications, file uploads, and more.

Installation

    Clone the repository: git clone https://github.com/pruthvirajgn7/task-manager-api.git
  
    Navigate to the project directory: cd task-manager-api

    Install dependencies: npm install

Authentication

    The API uses JSON Web Tokens (JWT) for user authentication. Only authorized users can access protected routes.

API Endpoints: 

User API

    POST /users
    POST /users/login
    POST /users/logout
    POST /users/logoutAll
    POST /users/me/avatar
    GET /users/me
    GET /users/:id/avatar
    PATCH /users/me
    DELETE /users/me
    DELETE /users/me/avatar

Tasks API

    POST /tasks
    GET  /tasks
    GET  /tasks/:id
    PATCH /tasks/:id
    DELETE /tasks/:id
    
File Uploads

    Users can upload files, such as profile images, using the API. Uploaded files are stored   
    securely and associated with the respective user's profile.

Email Notifications

    The API utilizes the SendGrid service to send welcome and thank you emails to users upon 
    registration and task completion.

Thank you
