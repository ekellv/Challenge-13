
  
# E-Commerce Backend

## Description 

This application uses the Sequelize ORM and MySQL to create a backend for an ecommerce website.

![Github license](http://img.shields.io/badge/License-MIT-yellow.svg)

[A demonstration of the MySQL setup can be found here.](https://drive.google.com/file/d/1647sSZJdHbEbQhREy9MWFfy65cjy3iwO/view)

[A demonstration of the Category route and model functionality can be found here.](https://drive.google.com/file/d/1unzixS0UkUCQzANH03sPxgFj21CAhyPh/view)

[A demonstration of the Product route and model functionality can be found here.](https://drive.google.com/file/d/1232GVEkNs4hXgM_MKHTwtj3020BP1tmA/view)

[A demonstration of the Tag route and model functionality can be found here.](https://drive.google.com/file/d/1Jj-ZHRsUHEgSC-NSOwfyUT9JPJ-NoE0y/view)

## Contents
1. [About](#about)
      1. [User Story](#user%20story)
      2. [Acceptance Criteria](#acceptance%20criteria)
      3. [Visuals](#visuals)
      4. [Technologies](#technologies)
2. [Installation](#installation)
3. [License](#license)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [Testing](#testing)
7. [Authors and Acknowledgements](#authors%20and%20acknowledgements)

## About

Using a working Express.js API configured to use Sequelize, the application interacts with a MySQL database to create a backend for an e-commerce site. The user can interact with the database with the created models and routes, and perform CRUD operations on the backend. Because the application uses dotenv, the user can safely work without worrying about the security of their password. 

## User Story

``AS A manager at an internet retail company

I WANT a back end for my e-commerce website that uses the latest technologies

SO THAT my company can compete with other e-commerce companies``

## Acceptance Criteria 

``GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file

THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands

THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application

THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia Core for categories, products, or tags

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core

THEN I am able to successfully create, update, and delete data in my database``

## Visuals: 

![E-Commerce-Backend-Screenshot](https://user-images.githubusercontent.com/103372188/186549049-0ff6831c-8ade-4f58-aa8c-d9a12ec5b3f7.png)

## Technologies

* [Node.js](https://nodejs.org/en/)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [DotEnv](https://www.npmjs.com/package/dotenv)

## Installation 

Please run the following dependencies to install the application: 

`
npm i
`

## License 

This reposititory is licensed under the MIT license. 

For more information about this license or any others, please visit: [https://choosealicense.com/](https://choosealicense.com/).

## Usage 

In the root of the project's file system, run ``mysql -u root -p`` and enter your password when prompted. Once logged in, run ``source db/schema.sql`` and then ``exit`` once the database has been created. 


After this, run ``npm run seed`` to seed the database and finally ``npm start`` to begin the application. 

## Contributing 

This repository is not currently accepting contributions. 

## Testing 

This application does not currently have any testing implemented. 

## Authors and Acknowledgements

Built by: Erin Voelker

## Contact Information

* GitHub: [ekellv](https://github.com/ekellv)
* Email: [erinkvoelker@gmail.com](mailto:erinkvoelker@gmail.com)

