# Tech Blog

## Description

The Tech Blog is a CMS-style web application that allows users to publish and manage blog posts. It includes full CRUD (Create, Read, Update, Delete) functionality for blog entries and user accounts, along with user authentication and authorization to ensure secure access.

Registered users can log in, create new posts, edit or delete their own posts, and view content created by others. The application is designed to follow the MVC (Model-View-Controller) architecture and leverages modern web development practices and tools.

## Features

- User authentication with session management
- Secure password hashing with bcrypt
- Blog post creation, editing, and deletion
- User dashboard for managing content
- Handlebars.js for dynamic templating
- Sequelize ORM for database operations
- Authorization checks to restrict actions to the appropriate users

## Technologies Used

- Node.js
- Express.js
- MySQL
- Sequelize
- Handlebars.js
- bcrypt
- express-session
- connect-session-sequelize

## Installation and Setup

1. Clone the repository to your local machine.
2. Install all dependencies using your preferred package manager.
3. Create a `.env` file using the provided sample format and update it with your database credentials.
4. Use Sequelize to sync and seed the database.
5. Start the application using the configured start script.

Make sure MySQL is installed and running locally before attempting to start the server.

## Usage

Once the application is running, open it in your browser. Users can:

- Register and log in
- Create new blog posts
- Edit or delete their own posts
- Browse posts created by other users on the homepage

The application is ideal for developers or tech enthusiasts who want a simple and secure platform to share knowledge and technical writing.

