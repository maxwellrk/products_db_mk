# products_db_mk

## Description

This the MariaDB schema for the [Products API](https://github.com/maxwellrk/products_db_mk). It also contains a docker-compose file for easy deployment onto an EC2 instance.
The docker-compose is set up to create a volume for storing the database information. It also links the schema file to auto-generate the products database on compose-up.
The schema was built to store data from multiple CSV files and to be able to be queried in the most efficient way.

## Prerequisites

```
node
docker
docker-compose
```

## Installing

```
git clone https://github.com/maxwellrk/products_db_mk.git
docker-compose up 
```
