# E-Commerce Back End

## Description

I was asked to develop the back-end for an e-commerce website using Node.js, Express.js, MySQL2, and Sequelize. Given some seed data for testing, along with the basic properties of four models and two API endpoints for the Product model, I updated the server code to work with Sequelize, created each of the models and associations, and coded the RESTful API routes for the remaining 13 CRUD endpoints.

## Instructions

### Walkthrough

[This walkthrough video demonstrates how to set up the application and shows the functionality of the API endpoints.](https://drive.google.com/file/d/178C7vg0mLt5Lmg3kz8_yPjcVAxyzu9LI/view?usp=sharing)

### Setup

To use the application, you will need to clone the repo to your local machine, then run `npm i` to install all of the dependencies. You'll also need to add a `.env` file in the root directory that inclues `DB_NAME='your-database-name'`, `DB_USER='your-mysql-username'`, and `DB_PW='your-mysql-password'`.

You'll then need to set up the database by running `mysql -u root -p` followed by `use your-database-name;`. You can then leave the MySQL shell with `quit;`.

Finally, update the seed files in the `seeds` directory with your own data and seed the database with `npm run seed`. Once the application is set up, you can initiate it with `npm start`. 

### API Endpoints

The following Product API endpoints are available:

* GET /api/products - return all products

* GET /api/products/id - return the product with the selected ID

* POST /api/products - create a product with the supplied body object

* PUT /api/products/id - update the product with the selected ID based on the supplied body object

* DELETE /api/products/id - delete the product with the selected ID

The following Category API endpoints are available:

* GET /api/categories - return all categories

* GET /api/categories/id - return the category with the selected ID

* POST /api/categories - create a category with a name based on the supplied body object data

* PUT /api/categories/id - update the name of the category with the selected ID based on the supplied body object data

* DELETE /api/categories/id - delete the category with the selected ID

The following Tag API endpoints are available:

* GET /api/tags - return all tags

* GET /api/tags/id - return the tag with the selected ID

* POST /api/tags - create a tag with a name based on the supplied body object data

* PUT /api/tags/id - update the name of the tag with the selected ID based on the supplied body object data

* DELETE /api/tags/id - delete the tag with the selected ID

Please see the appropriate file in `routes/api` for the correct syntax for POST and PUT body objects.

## Contact

Brett Piper

[GitHub](https://github.com/bpiper91) | [Email](mailto:bpiper91@gmail.com)