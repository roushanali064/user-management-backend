# User Management

## Overview

User management is a Node.js application built with TypeScript, Express, and MongoDB. This guide provides instructions on setting up and running the application locally.

## Getting Started

Setup the project locally follow the instruction

## Prerequisites

Before you begin, ensure that you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 14 or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [MongoDB](https://www.mongodb.com/) (Ensure MongoDB is installed and the server is running)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/roushanali064/user-management-backend.git

2. Navigate to the project folder

    ```bash
    cd user-management-backend

3. Install dependencies

    ```bash
    npm install

### Configuration

1. Create a .env file

    ```bash
    PORT=5000
    MONGODB_URI=mongodb://localhost:27017/assignment2

## Running the Application

1. Development Mode
    ```bash
    npm run start:dev

2. Production Mode

    ```bash
    npm run build
    npm run start:prod

## Code Quality

1. linting

    ```bash
    npm run lint
    //to automatic fixed lint issues use
    npm run lint:fix


## Code Formatting

1. Prettier

    ```bash
    npm run prettier
    To automatically fix formatting issues
    npm run prettier:fix
