# Bakery Recipes
I’ve developed a Bakery Recipes dynamic website ,using MVC architecture, for finding recipes using AJAX and a foreign API (https://forkify-api.herokuapp.com) reciving them and saving them on the local storage. Also used here a JavaScript ecosystem, some 3rd-party packages of node.js, npm, libraries, and dev tools.

## Packages installed
- babel-core,which contains the core functionality of the compiler.
- babel-preset-env, will take care that all the modern JavaScript features are converted back to ES5 so all browsers would be capable of understanding it.
- babel-loader, needed for Webpack in order to actually load babel files.
- babel-polyfill, this will implement like a promise in ES5.
- webpack-dev-server, provides us with a developement server, which will automatically bundle all our JavaScript files, and then reload the app in a browser when ever we change a file.
- axios, a promise based HTTP client for the browser and node.js, automatic transforms for JSON data.
- fractional, library to deal with fractions (4.5 ➡️ 4 1/2) and convert them. - uniqid, API to generate to each item on the ingredient list a unique identifier.

## How To RUN it
- write ``` $ npm run start ``` in order to run the project. 
