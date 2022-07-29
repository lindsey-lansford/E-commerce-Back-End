# E-commerce Back End
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The application acts as a back end for a hypothetical e-commerce retail site. The app is operational from the command line and allows a retail store owner to create, update, delete and display all of their products in a MYSQL database. I used Insomnia for test and validating results of the RESTful API. This app was written in JavaScript and powered by Node.js, Express.js and Sequelize.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributions](#how-to-contribute)
* [Tests](#tests)
* [Questions](#questions)

## Installation

To install this application, you will need to clone the repo and run a few commands into the terminal. 

**Installs include**:

* ``npm init`` followed by ``npm install`` (These commands will install the dependencies needed for the package.json)

* ``npm install express`` (The webserver framework for Node.js)

* ``npm install mysql`` (Establishes a connection to the database via Node.js)

* ``npm install sequelize`` (Establishes communication with a MySQL database)

* ``npm install dotenv`` (This package is a zero-dependency module that loads environment variables from a .env file into process.env. This will help keep your sensitive info [ie passwords] hidden from open source platforms.)

  * Make sure to fill out the ``.env.EXAMPLE`` file with your ``mysql`` login credentials, and rename the file to ``.env``

>_If you want to learn more about any of these npm packages, [click here](https://www.npmjs.com/)._

## Usage

The application runs via the root directory by typing ``node server.js`` into your terminal, followed by ``node seeds/index.js``. However, before that, you will need to run ``source schema.sql`` from the /db directory. 

To test out the CRUD API routes, I used Insomnia.

## License

This project is licensed under **MIT** license.

## How to Contribute

When creating an open source project on GitHub, there is always the option for other developers to contribute to your projects. | If you would like to contribute, please contact me at the email listed below.

## Tests

At this time, no tests have been documented for this application.


## Questions

Please reach out with any questions you may have about this application.

* :octocat: GitHub: [@lindsey-lansford](https://github.com/lindsey-lansford)
* :envelope: Email: lindsey.lansford@gmail.com

-------------------------------------------------------
## Walkthrough Demonstration Videos

*--->* [Intro + Category Routes](https://drive.google.com/file/d/13tA5unjIIJ2C1ApHzEIg5dCWLUhSeNEt/view?usp=sharing)

*--->* [Product Routes](https://drive.google.com/file/d/1qNeubHQCB9JVGKNpeDmP65HO3KBTxVxY/view?usp=sharing)

*--->* [Tag Routes](https://drive.google.com/file/d/1pW-1jauY3cjjPQgdf6rTjjOaWkun6y7F/view?usp=sharing)