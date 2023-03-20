# InStock

Instock is a full stack CRUD inventory management application. The app allows users to view current inventory, add or delete inventory and update existing items. The project was built together with three other developers and Jira was used for agile project management.

https://user-images.githubusercontent.com/97055104/214982067-40802963-5775-4c3e-8579-26239a854757.mp4

## How It's Made

**HTML, SASS, JavaScript, React.js, Node.js, Express.js, MySQL, Knex.js, Axios**

**React**: JavaScript library to build out user interfaces<br>
**MySQL**: Relational Database Management System<br>
**Node**: JavaScript runtime environment<br>
**Express**: Web application framework for Node.js<br>
**Knex.js**: SQL query builder used to model schema creation, table migrations, connection pooling and seeding. <br>
**Axios**: Promise-based HTTP client for Node.js

## The Team

Natalia and I were responsible for building out the backend of this project with Node, Express and MySQL.

This frontend was built in collaboration with:

Natalia (https://github.com/Awatanka) <br>
Su (https://github.com/Su0112) <br>
Caty (https://github.com/Caty115)<br>

## Installation:

1. Clone this repository - [instock-duncan](https://github.com/ldietz08/instock-duncan) <br>
   and the backend respository [instock-api-duncan](https://github.com/ldietz08/instock-backend)

2. Install the required dependencies using: `npm i`

### Environment Variables

**Frontend:**
Add the following variables in .env file:

`REACT_APP_API_URL=https://localhost:8080`

**Backend:**

`PORT = 8080`
`DB_LOCAL_DBNAME="Warehouse"`<br>
`DB_LOCAL_USER="YOUR DB USER NAME"`<br>
`DB_LOCAL_PASSWORD="YOUR DB PASSWORD"`<br>

3. Run the frontend and backend using: `npm start`.

## How to work with Knex.js

Knex is a SQL query builder, mainly used for Node.js applications with built in model schema creation, table migrations, connection pooling and seeding.

### Install Knex and Knex Command Line Tool

Install `knex` **globally** on your local computer.

```bash
$ npm install knex -g
```

This will allow us to use `knex` as a command line tool that helps you create and manage your knex files.

In addition, you will need to also install the `knex` module **locally** to use in your project.

```bash
$ npm install knex --save
```

## Configuring your database

We're going to be connecting to a MySQL database, we'll need to install the `mysql` module.

```
$ npm install mysql --save
```

We can start by creating a `knexfile.js` in the root of your project which will act as our configuration for different environments, (e.g. – local development vs production).

```
$ knex init
```

This will create a `knexfile.js` with the different configurations for the different environments.
