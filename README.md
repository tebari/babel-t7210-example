# T7210 - Babel Sourcemap issue example
This repo demonstrates the issue reported in https://phabricator.babeljs.io/T7210

## Instructions

- Clone this repo
- `npm install` to install all dependencies
- `npm start` will build the files and start a webserver
- Open Chrome at `http://localhost:8080/`, open dev tools and refresh

Chrome won't let you to set a break point on line 4 of babelCurrent/demo.js, but it will let you do it for babel644/demo.js
