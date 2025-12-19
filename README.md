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



#To build the project run the following command from the root folder:
    npm run build
This will install all dependencies and create a production build of the frontend inside the backend folder.

#To start the server run the following command from the root folder:
    npm run start
This will start the backend server which will serve the production build of the frontend.


also install npm install @clerk/clerk-react