## 🚀 How to Set Up This Express Backend Boilerplate

Follow these steps to create and run this backend project from scratch:

---

### 1️⃣ Create a new project folder
```bash
mkdir backend
cd backend
```

## Create the main server file

touch index.js


##  Initialize Node project

npm init -y

>> This generates a default package.json.

## Install Express

npm install express


## Add scripts in package.json

> Open package.json and update the scripts:

"scripts": {
  "start": "node index.js",
  "dev": "nodemon index.js"
}


## Install Nodemon (for auto-restart during development)

npm install nodemon --save-dev


## Write the backend code in index.js

const express = require("express");
const app = express();

app.get('/', (req, res) => {
    res.send("Backend is running");
});

app.listen(5000, () => {
    console.log("Server running at http://localhost:5000");
});


##  Run the server

> Development mode (recommended):

npm run dev


> Production mode:

npm start


## Your backend is now running!

>Open in browser:


http://localhost:5000


>You should see:

Backend is running


#  Tech Used
-Node.js
-Express.js
-Nodemon



## Notes:-

> This Perfect for beginners learning Express.js setup
