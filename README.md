# postgres-hasura
A Docker compose template to spin up postgres db and hasura

### Installation
Confirm and update the env variables (ports,login) with your preference.

Just run the following command below:

```sh
$ docker-compose up
```

This will initialize 3 services:
* [postgres] - The postgres database server.
* [pgAdmin] -  A Web admin for the postgres server.
* [graphql-engine] - The hasura graphql-engine server.
