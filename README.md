# MERN Stack Blog Project
## Introduction
This project is a simple blogging platform built using the MERN stack (MongoDB, Express.js, React, and Node.js). It supports user registration, login with JWT authentication, creating posts, and editing posts.
## Features
- User Registration
- User Login with JWT Authentication
- Create Posts
- Edit Own Posts
- Store User and Post Details in MongoDB
## Technologies Used
- **Frontend**: React, React Router, React Quill (for rich text editing)
- **Backend**: Node.js, Express.js, JWT for authentication
- **Database**: MongoDB, Mongoose
- **Other**: Multer for file uploads, bcrypt for password hashing
## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/ManiKumar004/MERN-Stack-Blog-app.git
    cd mern-blog-project
    ```

2. **Install dependencies:**

    - For the backend:
        ```bash
        cd backend
        npm install
        ```

    - For the frontend:
        ```bash
        cd frontend
        npm install
        ```

3. **Set up environment variables:**

    - Create a `.env` file in the `backend` directory with the following variables:
        ```
        MONGODB_URI=your_mongodb_uri
        JWT_SECRET=your_jwt_secret
        ```

4. **Run the application:**

    - Start the backend server:
        ```bash
        cd backend
        npm start
        ```

    - Start the frontend server:
        ```bash
        cd frontend
        npm start
        ```
## Usage
1. **Register a new user:**
    - Navigate to `/register` and fill out the registration form.

2. **Login:**
    - Navigate to `/login` and fill out the login form. A valid JWT token will be stored in cookies.

3. **Create a post:**
    - Navigate to `/create-post` and fill out the form to create a new post.

4. **Edit a post:**
    - Navigate to `/edit-post/:id` and modify the desired fields of your post.
## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.
