🏦 Project #10 – Argent Bank API

This repository contains the backend code for the Argent Bank project. The backend handles user authentication, user data management, and transaction processing.
🚀 Getting Started
✅ Prerequisites

Ensure you have the correct versions of the following dependencies installed:

    Node.js v12 – JavaScript runtime environment
    MongoDB Community Server – NoSQL database

You can verify the installation with the following commands:

# Check Node.js version
node --version

# Check MongoDB version
mongo --version

📥 Installation & Setup

Follow these steps to set up the project locally:

    Fork this repository.
    Clone the repository to your local machine:

git clone https://github.com/FischKevin/DA-JS-Projet13.git

    Open a terminal in the cloned project folder.
    Install dependencies:

npm install

    Start the development server:

npm run dev:server

    Populate the database with test users:

npm run populate-db

Your server should now be running at:
👉 http://localhost:3001
👥 Test User Data

After running the populate-db script, the following test accounts will be created in your MongoDB database:
First Name	Last Name	Email	Password
Tony	Stark	tony@stark.com	password123
Steve	Rogers	steve@rogers.com	password456
📄 API Documentation

Once the server is running, you can access the API documentation at:
👉 http://localhost:3001/api-docs
🎨 Design Assets

Static HTML and CSS for most of the site are available in the /designs folder.
User Profile Editing

    A wireframe for the user profile editing feature is available at:
    /designs/wireframes/edit-user-name.png

Transaction Model Proposal

    A wireframe for the proposed transaction model can be found at:
    /designs/wireframes/transactions.png

🛠️ Tech Stack

    Node.js – Backend runtime
    Express – Web framework for Node.js
    MongoDB – NoSQL database
    Mongoose – MongoDB object modeling for Node.js
    Swagger – API documentation

📌 Project Status

✅ User authentication – Completed
🔄 Transaction management – In Progress
📄 License

This project is licensed under the MIT License.