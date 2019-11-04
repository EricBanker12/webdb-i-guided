## relational database
- has tables (relations)
- tables have rows (records)
- rows have columns (fields)
- resources are stored in tables

## SQL
- manage data
- manage data structure (schema)
- manage server (security, monitor, performance, analysis)

## Relational DB Management Sys (RDBMS)
- server manage relational db (SQLite, PostgreSQL, ...)

## using relational db in node.js
client http(json) -> api proprietory-protocol(SQL) -> dbms server

query builder translates api language to SQL

knex library to database driver

object relational mapper (sequalize, bookshelf, etc...) another way to connect
- more complex, more than a simple query