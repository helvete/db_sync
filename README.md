# Postgres dump & restore script

* dump remote DBs and import them locally (or vice versa)
* script is capable of dumping specific DB schemata at once
* it also handles a slight weirdness of `pg_dump` not including a clause `CREATE SCHEMA public;` into the dumpfile of `public` schema

## How to use
* fill in the `DBCRED` file using source and target DB credentials; inspect `DBCRED.vcs` file for inspiration - or copy and change its contents
* run the script
