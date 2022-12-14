# LAB - Class 26

## Project: Games API

### Author: Amani M AL-Zoubi

### Links and Resources
- [Django REST framework](https://www.django-rest-framework.org/)

### Setup
- use python version 3.10.7

#### `.env` requirements (where applicable)
- For this lab I did not use .env 

#### How to initialize/run your application (where applicable)
- I used docker , so you need to run it from docker container
    `docker-compose up` to run it from your machine 
- Use `http://127.0.0.1:<PORT>/api/v1/games/` to get Games API 
- you need to sign in, I create four users:
    1. admin: username: Amani , password:amani
    2. staff : username: Eslam, password:eslam12345
    3. normal users : 
        1. username:Eman , password:eman12345
        2. username: Esraa, password: esraa12345
- for specific Game add it's id to your path like `http://127.0.0.1:<PORT>/api/v1/games/1`
-  Use `http://127.0.0.1:<PORT>/api/v1/games/player` to get players comments
    - you can read them even you do not sign in 

#### How to use your library (where applicable)
- I used Django Rest framework , psycopg2 ; docker will install them automatically 


#### Tests
- run command `docker-compose run web python manage.py test ` NOTES: make sure docker is still running 
#### Pull Requests
- [PULL REQUEST LINK](https://github.com/amani51/games-api/pull/1)