# 13 Object Relational Mapping (ORM): E-commerce Back End

## Description

A backend App for an e-Commerce application. Allows users to manipulate a database of products, categories, and tags. Demonstrates the use of the Sequelize package and functionality with a SQL database. Can be accessed and interacted with the API client [Insomnia](https://insomnia.rest/products/insomnia).

## Installation

1. Clone this repo. Install dependencies by running `npm install`.

2. Create a local database called `ecommerce_db` by running the `schema.sql` file from the MySQL shell.

3. Exit the database and seed it with some starter data by running `npm run seed`

4. Create a `.env` file in the root directory with the following variables:

```
DB_NAME=ecommerce_db
DB_USER=root
DB_PW=password
```

## Usage

- Run `node server` to start the program.

- Submit requests to any of the endpoints using the API client.

## GitHub Link and Screencastify recording

https://github.com/bilcon/e-commerce-back-end

https://watch.screencastify.com/v/LnenFLmLCH4KuG2eM2EZ
