# Weather_mern
Built a weather app with ReactJS and MongoDB, integrating external APIs for real-time data. Enhanced API handling, data display, and error management skills. Created a functional single-page app with search functionality and a user-friendly interface. Simulated complex data to ensure all features work before using real APIs.

## What is this?
This is a weather web app to get the current weather data of the  pincode that you submit into the form. This project consists of 4 main components

- Header
- Form to input pincode, to choose temperature metric, and a save button
- A left side panel to Display weather data
- A right side panel that shows 10 most recent weather queries

## Setup 

You need to have git and Node already installed in your device

Clone the repo: 
```
git clone https://github.com/pavaneshwar18/weather_mern.git
```

Go to the project directory
```
cd weather-mern-app
```
Install dependencies
```
⁠npm install
```
Go to client directory
```
cd client/
npm install
```

Start the server
```
npm run start
```
Start the Client
```
//open now terminal
cd frontend
npm start
```
### .env file
Add two credentials. Weather api and mongo connection string.

## Run Locally

You can now run your local.  
Go to your root directory and start your web app:
```javascript
npm run dev
```
This is command will your client and server concurrently. 
- client - localhost:3000
- server - localhost:5000

The service will auto-watch both frontend and backend, so no need to restart to see your changes.  
Once you save your changes, it'll auto-refresh to view your changes.
