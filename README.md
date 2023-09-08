<h1 align="center"><img width="40" height="40" src="https://img.icons8.com/stickers/100/project-management.png" alt="the project's icon"/> Project Name</h1>

Write a description of the project..

This repository serves as a valuable resource for creating README files for your projects. A well-crafted README is crucial for effective project communication and collaboration. A README file is often the first point of contact for users, contributors, and collaborators. It helps them understand what your project is about, how to use it, and how to contribute. Using a well-designed template ensures consistency and makes your project more accessible and user-friendly.

<aside>ℹ️ Feel free to customize this README to suit your preferences.</aside>

<nav>
  <h2>Table of Contents</h2>
  <ul>
    <li><a href="#section-1">Features</a></li>
    <li><a href="#section-2">Folder Structure</a></li>
    <li><a href="#section-3">Folder/File Explanations</a></li>
    <li><a href="#section-4">Technologies Used</a></li>
    <li><a href="#section-5">Run Locally</a></li>
    <li><a href="#section-6">Environment Variables</a></li>
    <li><a href="#section-8">npm Packages</a></li>
    <li><a href="#section-9">License</a></li>
  </ul>
</nav>
<br/>
<br/>

<section id="section-1">
  <h2>Features</h2>

  - First Feature
  - Second Feature
  - Third Feature
  - ...

  <br/>

  <h2>API Features</h2>

  - Authentication
    - Register a new user
    - Verify a user's account
    - User login
  - ...
</section>
<br/>
<br/>

<section id="section-2">
    <h2>Folder Structure</h2>

   ```
    📂 config
      📄 config.js
      📄 mongoose.js

    📂 controllers
      📄 auth.controller.js

    📂 healthcheck
      📄 healthcheck.js

    📂 helpers
      📄 mailer.js

    📂 middlewares
      📄 authenticate.js

    📂 models
      📄 user.model.js

    📂 routes
      📂 v1
          📄 index.js
          📄 user.routes.js
      📄 index.js

    📂 services
      📄 error.js

    📂 utils
      📄 apiResponse.js

    📂 validations
      📄 auth.schema.js

    📄 .env
    📄 docker-compose.yaml
    📄 Dockerfile
    📄 server.js
   ```

</section>
<br/>
<br/>

<section id="section-3">
  <h2>Folder/File Explanations</h2>

  **📂 config** This folder contains configuration files for the application including,
  
  1. **📄 config.js**, which sets up environment variables and loads other configuration files, 
  2. **📄 mongoose.js** for connecting to a MongoDB database.

  **📂 controllers** This folder contains controller files, which handle incoming requests and send back responses.

  **📂 healthcheck** This folder contains a single file named healthcheck.js, which is responsible for checking the health of the application and returning a response indicating whether the application is running properly.

  **📂 helpers** This folder contains helper files, which contain utility functions that are used throughout the application.
  
  1. **📄 mailer.js**, which handles sending emails.

  **📂 middlewares** This folder contains middleware files, which are functions that can modify the request or response objects or terminate the request-response cycle.
  
  1. **📄 authenticate.js**, which handles authentication middleware.

  **📂 models** This folder contains model files, which define the structure and behavior of data stored in a database.

  **📂 routes** This folder contains route files, which define the application's API routes and their associated controller functions. There are two files in this folder:
  
  1. **📄 index.js**, which imports and exports all route files, 
  2. **📂 v1**, which is a subfolder containing route files for version 1 of the API. These files include v1 routes.

  **📂 services** This folder contains service files, which contain code that is responsible for interacting with external services or APIs.
  
  1. **📄 error.js**, which handles error response.

  **📂 utils** This folder contains utility files, which contain miscellaneous utility functions.

  1. **📄 apiResponse.js**, which handles API response formatting.

  **📂 validations** This folder contains schema files, which define the schema for request body validations.

  **📄 .env** This file contains environment variables used by the application, such as database connection strings and API keys.

  **📄 docker-compose.yaml** This file defines the services that are needed to run the application using Docker Compose.

  **📄 Dockerfile** This file defines the Docker image that the application runs on.

  **📄 server.js** This file contains the main code for the application, including setting up the Express.js server and connecting to the database and other services.

</section>
<br/>
<br/>

<section id="section-4">
  <h2>Technologies Used</h2>

  <p align="left">
    <h3>
      <a href="https://nodejs.org/en/" target="_blank" rel="noreferrer" align="center">
        <img align="center" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="NodeJS" />     
      </a>
      Node.js  
    </h3>
    <br/>

  - A JavaScript runtime. It allows developers to run JavaScript code outside of a web browser. 
  - To install Node.js, go to the official Node.js website, download the installer for your operating system, and follow the installation instructions.
  
  <br/>

  <h3>
    <a href="https://expressjs.com/" target="_blank" rel="noreferrer" align="center">
      <img align="center" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/express-colored.svg" width="36" height="36" alt="Express" />     
    </a>
    Express.js  
  </h3>
  <br/>

  - A popular Node.js framework for building web applications and APIs. It provides a robust set of features for handling HTTP requests, routing, and middleware. 
  - To install Express.js, open a terminal window, navigate to your project directory, and run the following command: `npm install express`.
  
  <br/>

  <h3>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer" align="center">
      <img align="center" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mongodb-colored.svg" width="36" height="36" alt="MongoDB" />
    </a>
    MongoDB 
  </h3>
  <br/>

  - A popular NoSQL document-oriented database that stores data in JSON-like documents. 
  - To install MongoDB, go to the official MongoDB website, download the installer for your operating system, and follow the installation instructions.
  <br/>

  <h3>
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer" align="center">
      <img align="center" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="36" height="36" alt="Git" />
    </a>
    Git 
  </h3>
  <br/>

  - A distributed version control system for tracking changes in source code during software development. 
  - To install Git, go to the official Git website, download the installer for your operating system, and follow the installation instructions.
  
  <br/>

</section>
<br/>

<section id="section-5">
  <h2>Run Locally</h2>

  Clone the project using the following command in your terminal:

  ~~~bash  
    git clone <repository_link>
  ~~~

  Navigate to the project directory:

  ~~~bash  
    cd <project_directory>
  ~~~

  Install the dependencies using the following command:

  ~~~bash  
    npm install
  ~~~

  Start the server using the following command:

  ~~~bash  
    npm start
  ~~~
  <br/>

  Alternatively, you can run the server using Docker by running the following command:

  Navigate to the project directory:

  ~~~bash  
    cd <project_directory>
  ~~~

  ~~~bash  
    docker-compose up -d --build
  ~~~

  This will build the Docker image and start the container for the application. You can then access the application by navigating to http://localhost:3000/api in your web browser.
</section>
<br/>

<section id="section-6">
  <h2>Environment Variables</h2>

  Fill up the .env.example file with your environment variables. Also, don't forget to remove the `.example` extension from the file name and rename it to just .env before running the application.
</section>
<br/>

<br/>

<section id="section-8">
  <h2>npm Packages</h2>

  | Package Name           | Version      | Link                                                |
  | ----------------------| -------------| --------------------------------------------------- |
  | body-parser            | ^1.20.2      | [npm](https://www.npmjs.com/package/body-parser)     |
  | cors                   | ^2.8.5       | [npm](https://www.npmjs.com/package/cors)            |
  | dotenv                 | ^16.0.3      | [npm](https://www.npmjs.com/package/dotenv)          |
  | express                | ^4.18.2      | [npm](https://www.npmjs.com/package/express)         |
  | helmet                 | ^6.0.1       | [npm](https://www.npmjs.com/package/helmet)          |
  | http                   | ^0.0.1-security | [npm](https://www.npmjs.com/package/http)          |
  | joi                    | ^17.8.3      | [npm](https://www.npmjs.com/package/joi)             |
  | jsonwebtoken           | ^9.0.0       | [npm](https://www.npmjs.com/package/jsonwebtoken)    |
  | mongoose               | ^7.0.0       | [npm](https://www.npmjs.com/package/mongoose)        |
  | multer                 | ^1.4.5-lts.1 | [npm](https://www.npmjs.com/package/multer)          |
  | nodemailer             | ^6.9.1       | [npm](https://www.npmjs.com/package/nodemailer)      |

</section>
<br/>

<section id="section-9">
  <h2>License</h2>

  [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) 

  This project is licensed under the MIT License. Feel free to contribute to this project by opening issues and pull requests.
</section>