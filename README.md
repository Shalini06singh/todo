# React Todo App with Firebase Backend

#Project Live Link:   https://todo-dusky-ten-70.vercel.app/


This is a React-based Todo Application integrated with Firebase as the backend for database management. The app allows users to create, read, update, and delete their tasks efficiently. With a user-friendly interface and real-time database synchronization, this project is ideal for beginners looking to explore React and Firebase integration.

#Features

Add Tasks: Create new tasks with ease.
Edit Tasks: Modify existing tasks as needed.
Delete Tasks: Remove completed or unwanted tasks.
Real-time Updates: Data is synced with Firebase in real-time.
Responsive Design: Fully optimized for desktop and mobile views.


#Tech Stack


Frontend:
React.js: For building the user interface.
CSS: For styling components.


Backend:
Firebase: For real-time database management and hosting.


#Prerequisites
Before you start, ensure you have the following installed:

Node.js (v14 or higher)
Firebase CLI (for deployment and configuration)

#Installation
1.Clone the repository
2.cd todo
3.Install dependencies
```
yarn install
```
4.Setup Firebase

Go to the Firebase Console and create a new project.
Enable Firestore Database for real-time data handling.
Get your Firebase config credentials from the Project Settings.
Create a .env file in the root directory and add your Firebase configuration:
```
REACT_APP_FIREBASE_API_KEY=your-api-key
REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
REACT_APP_FIREBASE_PROJECT_ID=your-project-id
REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
REACT_APP_FIREBASE_APP_ID=your-app-id
```
5.Start the development server
```
yarn start
```


## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
