
# Dockerized PostgreSQL and PgAdmin

This is a flexible and  **streamlined**  version of most dockerized Odoo projects that you'll find. And one that allows you to deploy with two different methods using the same Dockerfile:

-  **Config file**: To configure the Postgresql, we use the **pg_hba.conf** instead of docker environment.



## Requirements
create following folders:
/data/
/data/pgadmin
/data/postgresql

## Running 

```
git pull git@github.com:nimaam/Postgresql_Docker
#Edit the PGAdmin and Postgresql with IP addresses
vi docker-compose.conf
##Add the database credentials 
docker-compose up -d
```
