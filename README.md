# MERN Stack User Management Dashboard

This is a simple, responsive User Management Dashboard built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. It features user authentication (Login/Register) and an administrative panel for managing users (CRUD operations).

**Note:** This is a basic demonstration project with client-side user management for simplicity. In a full MERN application, user data would be persisted in a MongoDB database, and authentication would involve more robust methods like JWTs and hashed passwords. This current version uses in-memory state for user data.

## Features

* **User Authentication:**
    * User Registration (Sign Up)
    * User Login (Sign In)
* **Role-Based Access Control:**
    * **User Dashboard:** A personalized dashboard for regular users displaying their information.
    * **Admin Dashboard:** A powerful panel for administrators to:
        * View all users.
        * Search for specific users.
        * Add new users.
        * Edit existing user details (name, email, role).
        * Delete users.
* **Responsive Design:** Built with Tailwind CSS for a modern and adaptive user interface across various devices.
* **Interactive UI:** Smooth transitions and modal dialogs for a better user experience.

## Technologies Used

* **Frontend:**
    * React.js (with `create-react-app` or similar setup)
    * Tailwind CSS
    * Lucide React (for icons)
* **Backend:** (Placeholder for future integration - currently client-side data)
    * Node.js
    * Express.js
    * MongoDB

## Installation and Setup (Local Machine)

To get a copy of this project up and running on your local machine for development and testing purposes, follow these steps:

### Prerequisites

Make sure you have the following installed:

* [Node.js](https://nodejs.org/en/download/) (LTS version recommended)
* [npm](https://www.npmjs.com/get-npm) (comes with Node.js) or [Yarn](https://yarnpkg.com/getting-started/install)

### Steps

1.  **Clone the Repository:**
    Open your terminal or Git Bash and clone the project to your local machine:
    ```bash
    git clone [https://github.com/AhmedZagral/mern-stack-app.git](https://github.com/AhmedZagral/mern-stack-app.git)
    ```

2.  **Navigate to the Project Directory:**
    Change into the project folder:
    ```bash
    cd mern-stack-app
    ```

3.  **Install Dependencies:**
    Install the necessary Node.js packages for the React frontend:
    ```bash
    npm install
    # OR
    yarn install
    ```

4.  **Start the Development Server:**
    Once the dependencies are installed, you can start the React development server:
    ```bash
    npm start
    # OR
    yarn start
    ```
    This will open the application in your default web browser at `http://localhost:3000` (or another available port).

## Admin Login Credentials (for Demo)

For demonstration purposes, you can use the following credentials to log in as an administrator:

* **Email:** `ahmed@gmail.com`
* **Password:** `123`

You can also register new users from the login page with any email and password.

## Project Structure (Frontend)
mern-stack-app/
├── public/                 # Public assets (e.g., index.html template)
├── src/
│   ├── App.js              # Main application component
│   ├── index.js            # React app entry point
│   └── styles.css          # Custom CSS for gradients, glass effect, etc.
├── package.json            # Project dependencies and scripts
└── README.md               # This file
