# Killbase

**Killbase** is a service that allows international assassins and their clients to create, book, and execute contracts.

## Build Tools

Killbase is a full stack web application built with EJS on the front-end, Knex.js for CRUD operations and PostgreSQL for the back-end database. Materialize was used for styling, in addition to implementing the Typed.js library for typing effects.

## Project Links

Deployed site: https://killbase-stevenfiero.herokuapp.com/

Github repo: https://github.com/ssfiero/killbase-app

Project/Issue tracker: https://github.com/ssfiero/killbase-app/issues

For project details including user stories and wireframes: https://github.com/ssfiero/killbase-app/blob/master/Instructions-README.md

## Project Start Commands

Knex database migration: ```knex migrate:latest``` or ```knex migrate:rollback```

Knex database seed: ```knex seed:run```

PostgreSQL database: ```psql killbaseApp```

List database tables: \dt Query database table: select * from tablename; Exit out of database: \q

Server: ```node server.js```

## Heroku DB Commands

Heroku db migration: ```heroku run knex migrate:latest```

Heroku db seed: ```heroku run knex seed:run```

## Application Screenshots

Homepage
![Alt](/public/kb1.png)

Assassins
![Alt](/public/kb2.png)

![Alt](/public/kb3.png)

![Alt](/public/kb4.png)

Contracts
![Alt](/public/kb5.png)

![Alt](/public/kb6.png)
