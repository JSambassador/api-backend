# AI Portfolio Manager

A Node.js application with user authentication, profile management, password reset, input validation, error handling, and basic front-end integration using Express, Mongoose, Passport, and EJS.

## Features

- User Registration
- User Login
- Profile Management
- Password Reset
- Portfolio Management
- Input Validation
- Error Handling
- Basic Front-End Integration

## Setup

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/ai-portfolio-manager.git
    cd ai-portfolio-manager
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file with your email credentials for password reset functionality:
    ```
    EMAIL_USER=your-email@gmail.com
    EMAIL_PASS=your-email-password
    ```

4. Start the MongoDB server:
    ```sh
    mongod
    ```
    or
   
4.1. To connect your Node.js application to MongoDB Atlas, follow these steps:

Create a MongoDB Atlas Account:

Sign up at MongoDB Atlas.
Create a new cluster and get the connection string.

6. Start the application:
    ```sh
    npm start
    ```

7. Open your browser and go to `http://localhost:3000`.

## Testing

Run the tests using:
```sh
npm test
