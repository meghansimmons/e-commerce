# e-commerce

![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description

The application **e-commerce** allows a user to become familiar with a database containing tables with information about products, product categories and product tags. Also, information about the associations between the different data points are included.

Because this application is not deployed, the following walkthrough videos  demonstrate the **e-commerce** application's functionality:

[e-commerce: Create db, Seed db, Start server](https://drive.google.com/file/d/1hOWHM_AbpaTRtRY9UJ3UKlDa8nTk7QQn/view)

[e-commerce: Categories - GET, POST, PUT, DELETE](https://drive.google.com/file/d/17GTr2zM07aSSHJaVA0vMaohu3ATeQiTt/view)

[e-commerce: Products - GET, POST, PUT, DELETE](https://drive.google.com/file/d/1rnKp4pS0NqmS6Koqn6l14Lle8mm-Z7zU/view)

[e-commerce: Tags - GET, POST, PUT, DELETE](https://drive.google.com/file/d/1lMXXrD_Ic9SqkaoPokKOk8Y0-o5vAFw8/view)

## Installation

This application requires Node.JS to be installed. The user should  run ```npm install``` in their terminal to load the following npm packages: Express.js (version 4.17.1), mysql2 (version 2.1.0), and sequelize (version 5.21.7).

## Usage
From the MySQL shell, create the database ecommerce_db. 

To load the table data, run the following command in the terminal to start the server and create the tables.

```node server.js```

Next to seed the database, type the following in the command line 

```node seeds/index.js```

Now you can manipulate the data in the database using various commands including: GET, POST, PUT and DELETE in Insomnia until the front end of the application has been finished.

## Credits

Starter code was supplied for the e-commerce application. 

The bootcamp Unit 13 ORM Mini Project was referenced to assist in building the models and routes.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Questions
For any further information about this application or questions you might have, please visit my GitHub profile
[meghansimmons](https://github.com/meghansimmons/e-commerce).