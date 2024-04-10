## Project Structure

The repository is structured into two main folders:

1. **Client**: A Next.js application located in the `/client` folder, designed to run on `localhost:3000`.
2. **Backend**: A server located in the `/backend` folder, running on `localhost:4000`.

Both components are crucial for the demo's functionality and should be run concurrently.

## Prerequisites

Before starting, ensure you have installed:

- Node.js (latest stable version recommended)

- npm (usually installed with Node.js)

## Installation and Setup

### General Setup

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the cloned repository's root directory.

### Backend Server

1. Change directory to the backend folder: `cd backend`.
2. Run `npm install` to install all necessary dependencies.
3. Start the server by executing `npm run dev`.
4. Verify that the server is active on `localhost:4000`.

**Important**: Initialize the backend server first before starting the client.

### Client Application

1. Open a new terminal and navigate to the repository's root directory.
2. Change to the client folder: `cd client`.
3. Execute `npm install` to install dependencies.
4. After confirming the backend server is running, start the client with `npm run dev`.
5. Access the client at `localhost:3000`.

## Usage

With both the server and client running, you can now explore the functionalities of the Media Soup Learning Demo via your web browser
on `localhost:3000`.
This setup allows you to understand the interaction between client and server in real-time media communication.

