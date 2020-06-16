# Socket.io with react

This is a tryout of the example given in [https://www.valentinog.com/blog/socket-react/](https://www.valentinog.com/blog/socket-react/)

## Usage

start server:

    cd socket-io-server && node app.js

Open a browser on http://localhost:4001/ if you want to check if app's running


start client:

    cd socket-io-client && yarn start

Opens a browser on http://localhost:3000/


## Step 1: create server

    mkdir react-socketio
    cd react-socketio/
    ls
    git init
    mkdir socket-io-server && cd $_
    npm init -y
    npm i express socket.io
    atom app.js
    mkdir routes
    atom routes/index.js

## Step 2: add socket.io (Socket.IO, React and Node.js: designing the server)

(see edit in app.js)

## Step 3: create client

    npx create-react-app socket-io-client
    yarn add socket.io

copy App.js from website
