---
title: "FastAPI Social Media API"
excerpt: "A FastAPI-based API for a social media platform with features like user authentication, post creation, and voting on posts. It utilizes PostgreSQL for data storage, Alembic for database migrations, and includes unit tests with pytest."
collection: portfolio
---

To check out the project documentation, [click here](https://dnl0037.github.io/FastAPI-API/)

To check out the source code, [click here](https://github.com/dnl0037/FastAPI-API)

A FastAPI-based API for a social media platform with features like user authentication, post creation, and voting on posts. It utilizes PostgreSQL for data storage, Alembic for database migrations, and includes unit tests with pytest.

The most important folders in this project are:

- **app**: This folder contains the following Python files: config.py, database.py, main.py, models.py, oauth2.py, schemas.py, and utils.py.
    - In addition, there's a subfolder named routers with login.py, users.py, votes.py, and posts.py. Each of these routers handles specific API endpoints.
    - `config.py` defines application settings using the Settings class.
    - `database.py`: This file configures the database connection and session handling using SQLAlchemy.
    - `models.py`: This file defines the data models for the application, including Post, User, and Votes.
    - `oauth2.py`: This file contains OAuth2 authentication settings, including SECRET_KEY, ALGORITHM, and ACCESS_TOKEN_EXPIRE.
    - `schemas.py`: This file defines Pydantic models used for request and response payloads.
    - `utils.py`: This file contains utility functions, such as password hashing and validation.

- **tests**: This folder contains unit tests for the application.
    - Inside this folder, you will find various test files that cover different aspects of the application's functionality.

The application can be deployed on Heroku, Docker, and an Ubuntu server, with continuous integration and continuous deployment (CI/CD) pipelines.
