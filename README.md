## Setup and Configuration

Before running the client application, it's essential to set up and configure the server and database. Follow these steps to ensure a smooth operation:

### Server Setup

1. Ensure Node.js and npm are installed on your system.
2. Clone the repository and navigate to the project directory as mentioned in the Installation section.
3. Navigate to the server directory:
    ```bash
    cd server
    ```
4. Install the necessary dependencies:
    ```bash
    npm install
    ```
5. Set up environment variables by creating a `.env` file in the root directory of the server. At a minimum, you should define the `DB_USERNAME` and `DB_PASSWORD` variables.
6. Start the server:
    ```bash
    npm run dev
    ```
    The server must be running before you launch the client application.

### Database Configuration

This application requires a database for managing users and messages. Follow these steps to configure your database:

1. Set up your preferred database. This project is configured to use MongoDB by default.
2. Ensure that your database is running and accessible.
3. Update the database connection string in your `.env` file or the relevant configuration file in your project.

### Client Setup

1. Navigate to the client directory:
    ```bash
    cd client
    ```
2. Install the necessary dependencies:
    ```bash
    npm install
    ```
3. Start the client application:
    ```bash
    npm start
    ```

After completing the server setup and database configuration, you can proceed to run the client application. Navigate to `http://localhost:<PORT>` in your browser to access the chat application.
