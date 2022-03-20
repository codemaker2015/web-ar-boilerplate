# Web AR Boilerplate

This is the project repository for the Medium post "Develop your first Web AR app using WebXR and three.js".

The `master` branch contains the project starter code, which is intended for use together with the written guide in the post.

The `production` branch contains the full completed project code, with some added comments to explain key points.

## Running the app

To get up and running, clone the repo and run the following commands to install dependencies and start the app using [localtunnel](https://github.com/localtunnel/localtunnel).

    npm install
    npm run start:live

This will install the app dependencies, start an instance of webpack-dev-server and expose the local web server to the internet using. The localtunnel URL will be printed to your terminal.

## A note on debugging

 For development and debugging, attach the device to your machine using a cable and access the url `chrome://inspect/#devices` in your desktop version of Chrome. Allow debug access when prompted on your device. You should then be able to see your device appear in the inspection window you opened earlier, where you can use the `inspect` functionality to get access to the running app instance for debugging.