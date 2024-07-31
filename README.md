# Slack-CLone
A simple Slack clone built with the MERN stack (MongoDB, Express, React, Node.js) that replicates the core functionality of the popular team collaboration tool. 

# **Slack Clone**

A simple Slack clone built with the MERN stack (MongoDB, Express, React, Node.js) that replicates core functionality of the popular team collaboration tool.

## **Table of Contents:**
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)

## **Features:**
- **Real-time Messaging**: Send and receive messages in real-time.
- **Channels**: Create and join channels for team discussions.
- **Direct Messages**: Send private messages to other users.
- **User Authentication**: Secure login and registration.
- **Message History**: View past messages in channels and direct messages.

## **Technologies Used:**
- **MongoDB**
- **Express.js**

## **Install server dependencies:**
cd server
npm install

##**Install client dependencies:**
cd ../client
npm install

##**Configure environment variables:**

Create a .env file in the server directory with the following content:

MONGODB_URI=mongodb://localhost:27017/slack-clone
JWT_SECRET=your_jwt_secret

**Replace your_jwt_secret with a secret key of your choice.**

**Start the MongoDB server:**

mongod

**Run the server:**
cd srver
npm start

**Run the client:**
cd client
npm start


