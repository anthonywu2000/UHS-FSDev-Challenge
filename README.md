# Web Developer Take Home Test Level 2 - Challenge

## Goal
The goal of this project is to load the data objects generated in the lab. This includes the data objects loaded from the ORCESTRA API and from MongoDB.

## Technology Stack
JavaScript, Node.js, Express.js, React.js, Cascading-Style Sheets (CSS), Material-UI

## Installation
Run `yarn dev` to host the server on localhost:3000. Then run `cd client` to naviagte to the frontend application and run `yarn start` on localhost:3001 to run the full application (note: the Terminal will prompt you to run the frontend on localhost:3001, select yes).

Additionally, you may want to install all the dependencies in Material-UI and React Router DOM. The scripts for installing them can be found in `package.json` of the client directory. Just simply type `npm install <package-name>`.

## Some File Structure Details
• `routes.js` contains the API endpoints for ORCESTRA API and MongoDB.

• `app.js` contains the middleware and the set up routes for the server.

• `./client/src/components` contains all the refactored and reusable components that are used in the application.

• `./client/src/utils` contains the reusable code and functions used in the application.

• `./client/src/PsetAPI.jsx` and `./client/src/PsetDB.jsx` contain the rendering pages for data retrieved from ORCESTRA API and data retrieved from MongoDB respectively.

• `./client/src/App.js` contains the entry code to the full application.

• `./client/src/App.css` contains the CSS classes used for the frontend.

## Design/Styling Methodology
Since this is an internal tool, simplicity in the design is the key! 

## Futhur Discussions and Considerations
Due to time constraints for this project, I believe some stylings and designs can be furthur improved. Additionally, I hope to make the individual reusable components more generalized (ie. make them able to be used in multiple projects, but this could be out-of-scope). Also, I would like to dive deeper into React.js design patterns, as this would ensure good code quality and support furthur refactoring.