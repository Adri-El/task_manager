# Task manager Backend Project

## Overview
This project is a Task Manager application. 

## Features
- User-friendly interface for managing tasks
- Create new tasks
- Update existing tasks
- Delete tasks
- Real-time data fetching with Apollo Client

## Online access
You can access the app online by using this link: https://task-manager-client-dmuv.onrender.com

You can also access the project repository via this link: https://github.com/Adri-El/task_manager.git

## Tech-STACK
This application was built using  the following technologies:
Backend:
1. Javascript as the base programming language
2. Node.js framework called Express.js for the server. 
3. SQL for the database.
4. Sequelize as the ORM.
5. GraphQL for the API. The database is hosted on AWS RDS.

Frontend
1. Typescript as the base language
2. React.js framework called Next.js
3. Apollo client for making API calls

## Getting Started
## BACKEND:
### Prerequisites
Before you begin, ensure you have met the following requirements:
- You have installed [Node.js](https://nodejs.org/).
- You have a Windows, Mac or Linux machine.

### Installation
To install this project, follow these steps:

1. Clone the repository:
   bash
   git clone https://github.com/Adri-El/task_manager_backend.git

2. Navigate to the project directory:
  bash
  cd task_manager_backend

3. Install the dependencies:
  bash
  npm install

4. Configuration
  Create a .env file in the root directory and add the following variables:

plaintext
jwtKey=your-jwt-key
databaseName=your-database-name
databaseHost=your-database-host
databaseDialect=your-database-dialect
databasePassword=your-database-password
databaseUsername=your-database-username

### Usage
To use this project, follow these steps:

Start the server:

bash
npm run dev
Access the API endpoints at http://localhost:5000 (or your designated port).

API Endpoints
http://localhost:5000/graphql (for login and signup)
http://localhost:5000/graphql/auth (for protected routes)


Example Queries/Mutations
To get all tasks:

graphql
{
  tasks {
    id
    title
    description
    status
  }
}


Deployment
The backend is deployed on render.


## Frontend:

## Installation
To set up this project locally, follow these steps:

1. Clone the repository:
    git clone https://github.com/Adri-El/task_manager_client.git

2. Navigate to the project directory: cd task-manager-frontend
    cd task_manager_client

3. Install the dependencies:
    npm install

## Usage
To run the development server:
    npm run dev

Open http://localhost:3000 with your browser to see the result.

## Building for Production
To build the application for production, run:
    npm run build

To start the production server, run:
npm start


Contributing
To contribute to this project, follow these steps:

Fork the repository.

Create a new branch:

bash
git checkout -b feature-branch
Make your changes and commit them:

bash
git commit -m 'Add some feature'
Push to the branch:

bash
git push origin feature-branch
Create a pull request.

Contact
If you want to contact me, you can reach me at adrielamadi7@gmail.com.

