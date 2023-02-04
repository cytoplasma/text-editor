# Just Another Text Editor (JATE)

## Description 

This is a text editor app available online, which highlights text with JavaScript syntax decorations to assist users in taking JavaScript notes. The app is powered by webpack service workers, manifest, and indexedDB, making it possible to download the website, run it offline, and securely cache user data inputs.

## Table of Contents 

* [Installation](#installation) 

* [Usage](#Usage) 

* [License](#license) 

## Installation 

No installation is required for the web application. 
If you want to access the website locally, you may clone the git repository and run ```npm run install``` and ```npm run start``` to install required dependencies, build the application, and start the server.

## Usage 

Web app here: https://fathomless-sea-36472.herokuapp.com/

To take notes, simply type your notes in the editor. Sometimes the editor may lose focus. Therefore, clicking on the editor before exiting the page will ensure the entered text gets saved to the database. 

Once notes are saved, users may exit or reload the page how many times they woud like and the notes would stay. 

You can also download the text editor as a web app by clicking on the "Install" button on the upper left corner or by clicking the download icon in the chrome search bar. A prompt would pop up to confirm your installation and the application would automicatically open. The downloaded web application shares the same server and database as the website, therefore, all your notes should remain the same. 

## License 

MIT

