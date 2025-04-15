# Web Template
A Node.js/Express.js based template for building (extremely) simple web apps.

## Contents
### Backend
A simple backend RESTful API service that runs on Node.js with Express.js. All of the data gets saved into the sqlite driver that is included in the dependencies. Only an `index.js` file is included with one API endpoint, to serve as an example.
### Frontend
Frontend is served on nginx as static HTML + CSS + JS. It has no frameworks built into it.

## Usage
The template can be run both locally and with `docker`. To start, navigate to the `/backend` directory in the terminal. Run the command: `npm install` to get all of the needed dependencies. 

### To run the app locally:
Navigate to the `/backend` directory in the terminal. Run the command `npm start:dev`, to see the changes you make to the code immediately.

If you wish to see the website, open the `index.html` file inside of the `/frontend` directory with your prefered browser.

### To run the app with Docker:
Navigate to the root directory of the template in the terminal. Run the command `docker compose up` or `docker compose up -d` if you don't wish to see the status of the containers. The website should be visible on the address: `http://localhost:8080`.




