# gtsTracker
## Overview
The GTS Tracker is a portfolio project designed with the sole purpose of tracking a specific Porsche 911 GTS that belonged to a friend's father. Queries can be handled by simply pressing the button, or automatically via scheduled requests that are logged to the UI. Once the GTS has been located, an alert is sent via email to any user who decides to track it.
## Features
- **VIN Search**: In contrast to most other VIN trackers on the web, this web app's primary purpose is to search for a specific Porsche 911 through more than just one API. 
- **Automated and Manual Searches**: The user can search on their own time by pressing the button (helping keep the VIN more 'secure'), or  automated searches scheduled at regular intervals.
- **Email Notifications**: Sends email notifications with unique links for viewing confirmation, helping to avoid repeat notifications for already viewed listings.
- **Database**: Utilizes Firebase Firestore for storing search results and user data.
- **Caching**: Implements Redis for efficient performance in search requests and results handling.
- **Frontend Design**: Pays homage to the Porsche brand with React.
- **Interactive UI**: Provides real-time updates, display of search results, and notification status.

## Technologies Used
- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: Firebase Firestore
- **Caching**: Redis
- **Email Service**: Nodemailer (or similar)
- **Others**: Axios, dotenv, node-cron

## Setup and Installation
- Under Construction 

### Prerequisites
- Node.js
- npm or yarn
- Redis server
- Firebase account



