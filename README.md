# Interview-Platform
Video Calling Interview Platform with React &amp; Node.js


inside frontend folder run:
    npm create vite@latest .
    npm install
    npm run dev
inside backend folder run:
    npm init -y
    npm install express mongoose cors dotenv
    npm install -D nodemon
    (change type to module in package.json and add dev script for nodemon )
        //server file is inside the src folder so also change the script to "dev": "nodemon src/index.js"
        //also change the main to "main": "src/index.js"
    npm run dev