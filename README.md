# Task Management Web Application

## Installation

To run this application locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/task-management-app.git
   ```

2. Navigate to the project folder:

   ```bash
   cd task-management-app
   ```

3. Install dependencies for the frontend and backend:

   ```bash
   # Install frontend dependencies
   cd client
   npm install # or yarn install

   # Install backend dependencies
   cd ../server
   npm install # or yarn install
   ```

4. Configure the environment variables for the backend:

   - Create a `.env.development` file in the `server` directory containing
     ```
       ACCESS_TOKEN_SECRET, REFRESH_TOKEN_SECRET, DATABASE_URL = mongodb://localhost:27017/mern-task-management, and FRONTEND_URL
     ```
   - Create a `.env` file in the `client` directory containing
     ```
       REACT_APP_BASE_API_URL
     ```

5. Run the backend and frontend applications:

   ```bash
   # In the backend directory
   npm start # or yarn start

   # In the frontend directory
   npm start # or yarn start
   ```

6. The application should now be running. Access it in your web browser at `http://localhost:3000`
