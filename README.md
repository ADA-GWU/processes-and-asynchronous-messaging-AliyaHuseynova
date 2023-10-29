[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/qg4qXfSB)

Configuration of of the containerized DB server

1. Installation - Docker Container
2. Create Docker Compose File (YML) with the configuration content of PostgreSQL container
3. Create sql file for the tables and additional SQL statements
4. Starting the Container:
    a)Open command prompt and navigate to the directory containing the assignment files.
    b)To start the container, run this:
    "docker-compose up"
    ALTERNATIVELY start the container manually using a Docker application
5. Enter the PostgreSQL Database
    a)Open new command prompt and navigate to the directory containing the assignment files
    b)Connect to the PostgreSQL container via:
docker exec -it ALIYA-container psql -U dist_user -d mydatabase #TABLES are already created during the setup
6. To check the configuration details, enter the following:
docker exec -it ALIYA-container bash