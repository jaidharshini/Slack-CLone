# Slack-CLone
A simple Slack clone built with the MERN stack (MongoDB, Express, React, Node.js) that replicates the core functionality of the popular team collaboration tool. 

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

#!/bin/bash

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Configure environment variables
echo "MONGODB_URI=mongodb://localhost:27017/slack-clone" > server/.env
echo "JWT_SECRET=your_jwt_secret" >> server/.env

# Start the MongoDB server
mongod &

# Run the server
cd ../server
npm start &

# Run the client
cd ../client
npm start


