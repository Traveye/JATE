# Just Another Text Editor

### Table of Contents
* [Goals](#goals)
* [Implementation](#implementation)
* [Credits](#credits)
* [Usage](#usage)
* [License](#licene)

## Goals

As a developer, I want to create a text editor web application that allows me to create and store notes or code snippets with or without an internet connection so that I can reliably retrieve them for later use.


## Implementation

To complete this project, I used the following technologies:

- ![Node.js](https://img.shields.io/badge/Node.js-16.9.1-green?logo=node.js)
- ![Concurrently](https://img.shields.io/badge/Concurrently-^5.2.0-black?logo=Concurrently)
- ![nodemon](https://img.shields.io/badge/nodemon-^2.0.4-black?logo=nodemon)
- ![Express.js](https://img.shields.io/badge/Express.js-^4.17.1-black?logo=express)
- ![if-env](https://img.shields.io/badge/if--env-^1.0.4-black)
- ![CodeMirror](https://img.shields.io/badge/CodeMirror-^1.0.0-black?logo=codemirror)
- ![IndexedDB](https://img.shields.io/badge/IndexedDB-^6.1.2-black?logo=indexeddb)
- ![babel-core](https://img.shields.io/badge/babel--core-^7.15.0-black?logo=babel)
- ![babel-plugin-transform-runtime](https://img.shields.io/badge/babel--plugin--transform--runtime-^7.15.0-black?logo=babel)
- ![babel-preset-env](https://img.shields.io/badge/babel--preset--env-^7.15.0-black?logo=babel)
- ![babel-runtime](https://img.shields.io/badge/babel--runtime-^7.15.3-black?logo=babel)
- ![babel-loader](https://img.shields.io/badge/babel--loader-^8.2.2-black?logo=babel)
- ![css-loader](https://img.shields.io/badge/css--loader-^6.2.0-blue)
- ![html-webpack-plugin](https://img.shields.io/badge/html--webpack--plugin-^5.3.2-blue)
- ![http-server](https://img.shields.io/badge/http--server-^0.11.1-black?logo=http-server)
- ![style-loader](https://img.shields.io/badge/style--loader-^3.2.1-blue)
- ![webpack](https://img.shields.io/badge/webpack-^5.51.1-blue?logo=webpack)
- ![webpack-cli](https://img.shields.io/badge/webpack--cli-^4.8.0-blue?logo=webpack)
- ![webpack-dev-server](https://img.shields.io/badge/webpack--dev--server-^4.0.0-blue?logo=webpack)
- ![webpack-pwa-manifest](https://img.shields.io/badge/webpack--pwa--manifest-^4.3.0-black?logo=webpack)
- ![workbox-webpack-plugin](https://img.shields.io/badge/workbox--webpack--plugin-^6.2.4-black?logo=webpack)

A majority of the code was provided by the University of Berkeley Coding Bootcamp. I added the following features:

- Added a service worker to enable offline functionality using InjectManifest from Workbox Webpack Plugin.
- Added IndexedDB to store notes and code snippets.
- Added a manifest file to enable the application to be installed as a PWA.
- Completed the `database.js` file to handle IndexedDB functionality.

## Credits
This project was proved by the University of Berkeley Coding Bootcamp.

## Usage
To use this application, visit the deployed application at [https://just-another-text-editor.herokuapp.com/](https://just-another-text-editor.herokuapp.com/). You can also clone the repository and run the application locally by running the following commands in your terminal:

```
git clone
npm install
npm start
```

## License
MIT