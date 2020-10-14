# Desctiption

Demo of ruby on rails project running inside a docker container.

## Installation
Clone the project.

Build and start the project. Create the DB
```
$ docker-compose up --build
$ docker-compose exec web-rails rake db:create
```
Go to https://localhost:1339

