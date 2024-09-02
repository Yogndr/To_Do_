# To-Do App
## Overview
This project is a full-stack To-Do application built using modern web technologies. It allows users to create, manage, and organize their tasks efficiently. The application features a backend built with 
Node.js and MongoDB, and a frontend using React with CSS.
## Features
- **Create, Read, Update, Delete (CRUD) Operations**: Users can perform all CRUD operations on tasks.
- **Express Framework**: The backend is built using the Express.js framework.
- **MongoDB Integration**: Data is stored in a MongoDB database.
- **Environment Variables**: Managed using Dotenv.
- **CORS Enabled**: Cross-Origin Resource Sharing (CORS) is enabled to allow interaction between the frontend and backend.
- **Development Server**: Nodemon is used to automatically restart the server on code changes.
- **API Testing**: Postman is used for testing API endpoints.
- **Frontend Development**: The frontend is developed using React with CSS.
- **Code Quality**: ESLint is configured to maintain code quality and consistency.
## Technologies Used
### Backend:
- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **Nodemon**: Tool for automatically restarting the server.
- **Dotenv**: Module to load environment variables from a `.env` file.
- **CORS**: Middleware to enable CORS.
- **Postman**: API testing tool.
- **ESLint**: Linter for identifying and fixing code quality issues.
### Frontend:
- **React.js**
- **CSS3**
## Installation
### Prerequisites
- **Node.js** (v14.x or later)
- **MongoDB** (v4.x or later)
### Setup
1. **Clone the repository**:
 ```bash
 git clone https://github.com/yourusername/todo-app.git
 cd todo-app
 ```
2. **Install dependencies**:
 ```bash
 npm install
 ```
3. **Configure environment variables**:
 - Create a `.env` file in the root directory of your project.
 - Add the following variables:
 ```plaintext
 MONGODB_URI=your_mongodb_uri
 PORT=your_preferred_port
 ```
4. **Run the development server**:
 ```bash
 npm run dev
 ```
 The application will be available at `http://localhost:<PORT>`.
## Usage
- **Create a Task**: Submit a new task through the input form.
- **View Tasks**: All tasks are displayed in a list.
- **Update a Task**: Edit an existing task by clicking the edit button.
- **Delete a Task**: Remove a task by clicking the delete button.
## Code Quality
ESLint is used to ensure the code follows best practices and maintains consistency. To check for linting issues, run:
```bash
npm run lin
