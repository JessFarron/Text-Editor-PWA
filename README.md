# Text-Editor-PWA [![Github license](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
* [Description](#description)
* [Installation and Setup](#installation-and-setup)
* [Usage](#usage)
* [Heroku Deploy](#heroku-deploy)

## Description
The "Text Editor" project is a browser-based application designed to function as a single-page application, adhering to the Progressive Web Application (PWA) criteria. This text editor comes equipped with data persistence techniques to ensure data redundancy and operates efficiently offline.

To achieve this, the project utilizes the IndexedDB database, allowing the user to create and store notes or code snippets seamlessly. The application employs the lightweight "idb" package, a convenient wrapper for the IndexedDB API, which is widely used by companies such as Google and Mozilla.
## Installation and Set Up
1. Clone the Starter Code Repository:
Before you start, clone the starter code repository provided. However, make sure to create your own repository with the starter code instead of forking it. 
```
git clone <URL_of_starter_code_repository>
cd <project_folder>
```
2. Install Dependencies:
Once you have cloned the repository, navigate to the project folder and install the required dependencies using npm.
```npm install```
## Usage
Starting the Application
1. Ensure you have the required dependencies installed (as mentioned in the "Installation and Set Up" section).
2. Open the project in your preferred code editor and observe the client-server folder structure.
3. From the root directory, run the following command to start the backend and serve the client:
```npm start```
Running the Text Editor Application
1. With the application running, the JavaScript files will be bundled using webpack automatically.
2. Upon running the webpack plugins, you will find that the application generates an HTML file, a service worker, and a manifest file.
3. The text editor will still function smoothly in the browser even when using next-gen JavaScript, without any errors.

Using the Text Editor
1. Upon opening the text editor, IndexedDB will immediately create a database storage.
2. As you enter content in the text editor and subsequently click off the DOM window, the content will be automatically saved using IndexedDB.
3. If you close the text editor and reopen it later, you will find that the content is seamlessly retrieved from IndexedDB.

Installing the Web Application
1. When you click on the "Install" button, the web application will be downloaded as an icon on your desktop.
2. Upon loading the web application, a registered service worker using Workbox will be activated.
3. The service worker will pre-cache your static assets upon loading, along with subsequent pages and static assets.
4. 
## Deploy
Check the app at [Heroku](https://pochita-jate-aa9048e6f2d7.herokuapp.com/)
