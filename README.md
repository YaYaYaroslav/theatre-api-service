# Theatre Project

This project is designed to manage a theatre, including actors and genres.

## Technology stack

* Backend:
  - Language: Python 3 
  - Framework: Django 
  - Database: Postgresql 
* Dependency Management: pip
* Containerization: Docker
* Virtual Environment: venv
* Database Migrations: Django Migrations
* Collaboration and Version Control:
  - Version Control System: Git
  - Repository Hosting: GitHub
* API Documentation: Swagger
* Authentication:
  - Framework: Django Authentication
  - Token-based: JWT
* Testing: Unittest
* Environment Variables: .env
* Other: requirements.txt


## Installation

Make sure Python 3 is installed on your machine.

```shell
git clone git@github.com:YaYaYaroslav/theatre-api-service.git
cd theatre-api-service

python3 -m venv venv

venv\Scripts\activate

source venv/bin/activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```
```shell

git clone git@github.com:YaYaYaroslav/theatre-api-service.git

cd theatre-api-service

docker-compose build

docker-compose up

docker-compose down
```

## How to Obtain a JWT Token

To access protected endpoints in this Theatre API, you need to authenticate and obtain a JSON Web Token (JWT). Follow these steps:

1)Register an account.

2)Use your registered email and password to log in and obtain your JWT token.

3)After sending the login request, you will receive a JSON response containing your token.

4)Include the obtained access_token in the Authorization header when making requests to protected API endpoints.

5)If your access token expires, use the refresh_token to obtain a new one without logging in again.

## Features

* Management of the theater hall, genres and actors
* Play Management
* Performance Scheduling
* Reservation System
* Admin Panel and User Authentication
* API endpoints for interacting with theatre data programmatically
* Pagination and Filtering
* Docker Support
* Documented API endpoints for frontend developers

## User credentials

```shell
Email: admin@admin.com
password: admin
```