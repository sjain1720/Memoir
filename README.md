# Memoir

Memoir is a minimalist social media platform designed to provide essential functionalities such as creating, updating, deleting, and liking posts. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js), Memoir ensures efficient data management and seamless user interaction.

## Features
- **Create Posts:** Share your thoughts and experiences by creating new posts.
- **Update Posts:** Edit your existing posts to keep them up-to-date.
- **Delete Posts:** Remove posts that are no longer relevant.
- **Like Posts:** Show your appreciation for posts by liking them.

## Technologies Used
- **MongoDB:** Database management and storage.
- **Express.js:** Server-side framework for building web applications and APIs.
- **React.js:** Client-side library for building user interfaces.
- **Node.js:** JavaScript runtime environment for executing server-side code.

## Setup

To get started with Memoir, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/memoir.git
    cd memoir
    ```

2. **Install dependencies for both client and server:**
    ```sh
    cd client
    npm install
    cd ../server
    npm install
    ```

3. **Start the development server:**
    - For the client:
        ```sh
        cd client
        npm start
        ```
    - For the server:
        ```sh
        cd server
        npm start
        ```

4. **Environment Variables:**
    Create a `.env` file in the root of the server directory and add the following environment variables:
    ```sh
    PORT=your_port_number
    MONGODB_URI=your_mongodb_connection_string
    ```

## Usage
Once the setup is complete, you can access the application in your browser at `http://localhost:3000` for the client and `http://localhost:your_port_number` for the server.

## Preview
This is how the website will look after running:
![image](https://github.com/sjain1720/Memoir/assets/68539305/9872cebf-ee6f-499a-8837-6cadc11e32d2)

