# Workout Buddy

**Workout Buddy** is a fitness tracking app built with the MERN (MongoDB, Express, React, Node.js) stack. It helps users log their workouts and track the exercises they perform, including load (in kg) and reps. This application also allows users to easily add and delete new exercises in their workout logs.

## Features
- Add and log workout exercises
- Record load (in kg) and reps for each exercise
- View recent workout logs with timestamps
- Simple and intuitive user interface
- Built using the MERN stack

## Tech Stack
- **MongoDB** - Database to store workout data
- **Express.js** - Backend framework to handle API requests
- **React.js** - Frontend framework to create the interactive user interface
- **Node.js** - JavaScript runtime to power the backend server

## Getting Started

### Prerequisites
To run this project locally, you will need:
- **Node.js** and **npm** installed on your machine
- **MongoDB** (either locally or use MongoDB Atlas for cloud-based database)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Workout-Buddy.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Workout-Buddy
    ```

3. Install backend dependencies:

    ```bash
    cd backend
    npm install
    ```

4. Install frontend dependencies:

    ```bash
    cd frontend
    npm install
    ```

5. Set up your environment variables:
   - Create a `.env` file in the `backend` directory.
   - Add your MongoDB URI and other required variables (e.g., port).

6. Start the application:
    - For the backend (Node.js and Express):

    ```bash
    cd backend
    npm start
    ```

    - For the frontend (React):

    ```bash
    cd frontend
    npm start
    ```

7. Open the app in your browser:

    ```bash
    http://localhost:3000
    ```

## Usage

- **Adding a Workout**: Fill in the exercise title, load (in kg), and reps, then click the **Add Workout** button to log a new workout.
- **Viewing Workouts**: View previously added exercises, including their load and rep details, along with timestamps of when they were logged.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## Acknowledgements

- MERN Stack for enabling fast web development.
- [React](https://reactjs.org/) for the user interface.
- [Node.js](https://nodejs.org/en/) for the server-side platform.
- [Express](https://expressjs.com/) for API handling.
