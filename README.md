# ExpendiXpert - MERN Expense Tracker

## Overview
ExpendiXpert is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack that helps users track their income and expenses effectively. The app provides an intuitive and interactive UI for users to manage their financial transactions, categorize them, and visualize their spending habits.

## Features
- User authentication and secure login/logout functionality
- Add, edit, and delete income and expense transactions
- Categorization of expenses for better financial insights
- Interactive dashboard with graphical representation of expenses
- Responsive UI for seamless experience across devices
- RESTful API for efficient backend operations
- MongoDB database for scalable data storage

## Tech Stack
### Frontend:
- React.js
- Redux (if used)
- Tailwind CSS for UI styling
- Axios for API requests

### Backend:
- Node.js with Express.js
- MongoDB with Mongoose for database management
- JWT authentication for user security

## Installation & Setup
### Prerequisites:
Ensure you have the following installed on your system:
- Node.js
- MongoDB
- npm or yarn

### Steps to Run the Project:
1. Clone the repository:
   ```bash
   git clone https://github.com/shayan625/ExpendiXpert-main.git
   cd ExpendiXpert-main
   ```

2. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

3. Configure environment variables in a .env file in the backend directory:
   ```bash
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```

4. Start the backend server:
   ```bash
   npm start
   ```

5. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

6. Start the frontend:
   ```bash
   npm start
   ```

7. Open the application in your browser at:
   ```bash
   http://localhost:3000
   ```


