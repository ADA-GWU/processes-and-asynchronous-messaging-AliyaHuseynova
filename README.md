[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/qg4qXfSB)

Configuration of of the containerized DB server

1. Installation - Docker Container
2. Create YML file with the content for my postgres container
3. create sql file for the tables and additional SQL statements
2. Open two Command Prompts:
    a)first to connect to docker 
    1. cd (directory where the folder with files is located)
    2. docker-compose up ---> the container starts running OR it must be manually turned on VIA local application of container docker
    b)second to enter the container via >docker exec -it ALIYA-container psql -U dist_user -d mydatabase

To check the configuration details, enter the > docker exec -it ALIYA-container bash
