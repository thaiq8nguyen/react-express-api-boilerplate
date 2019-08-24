# Instructions

## Server Side Initialization
- Run  *npm install*
- Configure knexfile.js to setup database connections
- Create a migration using *knex migrate:make migration_name* (See  [^1])
- Once finished writing the migrations, run *knex migrate:latest* to update the database


### Aside
[^1]: Install knex CLI globallly with *npm install knex -g*




