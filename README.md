# E-Commerce_Back_End  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit/)
The back end for an e-commerce site


  ## Description

  E-Commerce Back End was created for UCF bootcamp class as an application to manage a database. The user will be able to get, push, put, and delete from the database using its api calls. The application was designed to go along with learning and display student ability to utilize knowledge on JavaScript, node.js, and sequelize.


  ## Table of Contents

  1. [Installation](#installation)
  2. [Usage](#usage)
  3. [Credits](#credits)
  4. [License](#license)
  5. [Contributing](#contributing)
  6. [Tests](#tests)
  7. [Questions](#questions)


  ## Installation <a id="installation"></a>

  N/A


  ## Usage <a id="usage"></a>

  To use the E-Commerce Back End, first, add a .env file with the name of the database as DB_NAME = "ecommerce_db" with your MySQL username and password as DB_USER and DB_PASSWORD, respectively.
  Then use the provided schema to create the database and also seed it using the provided seeds folder.
  After the database has been created and seeded, go into an API platform such as Insomnia or Postman. 
  Access the different sections of the database using the following GET URLs: "http://localhost:3001/api/tags/", "http://localhost:3001/api/categories/", and "http://localhost:3001/api/products/". 
  Add an id number after the previous links to get the results for a specific item in that category, for example: "http://localhost:3001/api/products/1".
   Add to the database by using the same urls from above (without the id number) as a POST. 
   Update a specific item in any of the sections by adding an id number and making it a PUT.
   Delete a specific item in any section by adding an id number and making it a DELETE.

  ## Credits <a id="credits"></a>

  Base code provided by the boot camp creators at [UCF Boot Camps](https://bootcamp.ce.ucf.edu/).


  ## License <a id="license"></a>

  Licensed under [MIT](LICENSE)


  ## Contributing <a id="contributing"></a>

  To contribute, fork the project into your GitHub account and create a pull request.


  ## Tests <a id="tests"></a>

  N/A


  ## Questions <a id="questions"></a>

  Github: [SienkC](https://github.com/SienkC)
  
  For any questions please reach out to me at sienkiewichc@gmail.com.
