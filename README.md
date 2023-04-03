# J.A.T.E. (Just Another Text Editor)

This is a text editor web application that allows you to write and save text content in your browser. It includes a client server folder structure and is built with next-gen JavaScript and Webpack.

## Requirements

To use this text editor web application, you'll need to have the following installed on your computer:

- Node.js
- NPM

## Getting Started

To get started, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the root directory of the project in your terminal.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm run start` to start up the backend and serve the client.
5. Open the text editor in your browser by navigating to `http://localhost:3000`.

## Building with Webpack

This text editor web application uses Webpack to bundle and optimize its JavaScript files. To run Webpack, follow these steps:

1. Navigate to the root directory of the project in your terminal.
2. Run `npm run build` to run the Webpack build process.
3. Check the `dist` folder for the generated HTML file, service worker, and manifest file.

## Using IndexedDB

This text editor web application uses IndexedDB to store text content locally in the browser. To use IndexedDB, follow these steps:

1. Open the text editor in your browser by navigating to `http://localhost:3000`.
2. Enter text content into the text editor.
3. Click off of the DOM window to save the text content to IndexedDB.
4. Close the text editor.
5. Reopen the text editor and see that your text content has been retrieved from IndexedDB.

## Installing as a Web App

This text editor web application can be installed as a web app on your desktop for easy access. To install the web app, follow these steps:

1. Open the text editor in your browser by navigating to `http://localhost:3000`.
2. Click on the "Install" button in the top right corner of the page.
3. Follow the prompts to install the web app on your desktop.

## Service Worker with Workbox

This text editor web application uses Workbox to register a service worker and pre-cache static assets. To use Workbox, follow these steps:

1. Open the text editor in your browser by navigating to `http://localhost:3000`.
2. Check that the service worker has been registered in your browser's developer tools.
3. Check that static assets have been pre-cached by refreshing the page and seeing that the text editor still functions without errors.

## Deploying to Heroku

To deploy this text editor web application to Heroku, follow these steps:

1. Set up a Heroku account and create a new app.
2. Configure your Heroku app to use Node.js.
3. Set up a remote Git repository for your Heroku app.
4. Add a build script to your `package.json` file to build the project with Webpack.
5. Push your code to the remote Git repository.
6. Deploy your app on Heroku using the Heroku CLI or the Heroku web interface.
