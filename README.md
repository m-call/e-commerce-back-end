# E-Commerce Back End

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Screenshot](#screenshot)
- [License](#license)
- [Credits](#credits)
- [Questions](#questions)

## Description

This application is the back end portion of an e-commerce application. The application allows the user to create, retrieve, update, and delete items from a MySQL database for their e-commerce store. The application uses the dotenv module to hide the user's sensitive data such as their MySQL user, password, and database, the Express module for setting up the server on localhost, the MySQL2 module to set up a connection to the local MySQL database, and the Sequelize module for added ease of implementation for back end functionality pertaining to the MySQL database. Finally, Insomnia Core is used to make the get, post, put, and delete requests to the database through the live server's API routes.

## Usage

To use this application, the user would need to have Node, MySQL, and Insomnia installed on their computer. Then, the user would run npm i in the console to install all of the NPM modules that are included in the application. The user should then create their database on their local machine in MySQL shell. After that, they should create a .env file inside the application and update it with their database name, username, and password for MySQL. If the user wants to, they can pre-populate their database with provided seed data in the seeds folder by running node seeds in the terminal. Once all of that is set up, the user can run npm start in the console to start the application which will be hosted on their localhost at port 3001. The user should then open Insomnia and can navigate to the specified routes for categories, products, and tags. Once navigated to the correct route path, the user can do a get request to get all of the database data in JSON format, a post request in JSON format to add a new dataset to the database, a put request to update a dataset, or a delete request to delete something from the database. Finally, the user can check that their request was performed by running another get request to see an updated version of the database.

### Example of How to Use This Application

An mp4 file is included in this repository if you want to view the demonstration in video format.
![Usage Gif](./assets/image/e-commerce-back-end-walkthrough.gif)

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Credits

This application was an assignment for the GA Tech Full Stack Web Development Coding Bootcamp. Starter code was provided for this assignment. Credit to Rob Perez and Instructor Jung Hoon Yoon for help with associations, specifically cascade deleting.

## Questions

If you have any questions about the repo, open an issue or contact me directly:

- Please contact me directly at my [GitHub](https://github.com/mcall0147)
- Or contact me by email at [mcallahanx93@gmail.com](mailto:mcallahanx93@gmail.com)
