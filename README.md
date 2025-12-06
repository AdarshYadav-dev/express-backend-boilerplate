##  How to Set Up This Express Backend Boilerplate

Follow these steps to create and run this backend project from scratch:


##  Create a new project folder
```bash
mkdir backend
cd backend
```

## Create the main server file
```bash
touch index.js
```

##  Initialize Node project
```bash
npm init -y
```

> This generates a default package.json.

## Install Express
```bash
npm install express
```

## Add scripts in package.json

> Open package.json and update the scripts:
```bash
"scripts": {
  "start": "node index.js",
  "dev": "nodemon index.js"
}

```


## Install Nodemon (for auto-restart during development)
```bash
npm install nodemon --save-dev
```

## Write the backend code in index.js
```bash
const express = require("express");
const app = express();

app.get('/', (req, res) => {
    res.send("Backend is running");
});

app.listen(5000, () => {
    console.log("Server running at http://localhost:5000");
});

```
##  Run the server

> Development mode (recommended):
```bash
npm run dev
```

> Production mode:
```bash
npm start
```

## Your backend is now running!

>Open in browser:

```bash
http://localhost:5000
```

>You should see:

**Backend is running**


#  Tech Used
- Node.js
- Express.js
- Nodemon



## Notes:-

> This Perfect for beginners learning Express.js setup
