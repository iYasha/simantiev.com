+++
title = "FastAPI Template"
date = "2023-06-19T19:52:00+03:00"
author = "Ivan Simantiev"
authorTwitter = "" #do not include @
cover = ""
tags = ["FastAPI", "Python", "Template"]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
+++


## FastAPI Template: A template for creating FastAPI projects with best practices.
FastAPI is a modern, fast and high-performance web framework for building APIs with Python. It is based on standard Python type hints and has many features to help you create robust and scalable applications.

However, setting up a new FastAPI project can be tedious and time-consuming, especially if you want to use some common tools and best practices such as:

-  Pydantic for data validation and serialization

-  SQLAlchemy for database access and migrations

-  JWT for authentication and authorization

-  Alembic to manage database migrations

-  A settings file to configure your application

-  A manage.py cli for runnig the application, making migrations, migrating and creating users

•  A clean architecture folder structure to organize your code

That's why I created https://github.com/iYasha/fastapi-template, a template that gives you a ready-to-use FastAPI project with all these features and more.

## How to use FastAPI Template.
Using FastAPI Template is very simple. You just need to clone the repository, install the dependencies, and run the manage.py command. Here are the steps:

Clone the repository:
```bash
git clone https://github.com/iYasha/fastapi-template.git
```

Install the dependencies:
```bash
pip install -r requirements.txt
```

Run the manage.py command:
```bash
python manage.py runserver
```

This will start the application at http://localhost:8000.

For more details, check the README file in the repository.

## What's included in FastAPI Template
FastAPI Template comes with a lot of features and tools that will help you develop your FastAPI project faster and easier. Here are some of them:

-  A backend API using FastAPI, Uvicorn and Gunicorn

-  A PostgreSQL database with SQLAlchemy ORM and Alembic migrations

-  A Pydantic model for user data validation and serialization

-  A JWT authentication and authorization system with middlewares

-  A settings file to configure your application using environment variables

-  A clean architecture folder structure to organize your code into models, repositories, services, schemas, routers and utils

-  A Swagger UI documentation for the API endpoints at http://localhost:8000/docs

## Why use FastAPI Template
FastAPI Template is not the only template for FastAPI. There are other options such as https://github.com/tiangolo/full-stack-fastapi-postgresql by Tiangolo (the creator of FastAPI) or https://github.com/tiangolo/full-stack-fastapi-postgresql by Sebastián Ramírez (the author of this article).

However, I think FastAPI Template has some advantages over them, such as:

-  It is simpler and more minimalistic, focusing on the essential features and tools for a FastAPI project

-  It is more flexible and customizable, allowing you to choose your own frontend framework, database engine, ORM library, or tool that you want

-  It follows a clean architecture pattern, separating the different layers of your application into models, repositories, services, schemas, routers and utils

-  It uses Pydantic for data validation and serialization, which is more consistent and compatible with FastAPI than other libraries such as Marshmallow or Serpy

-  It uses Alembic for database migrations, which is more powerful and reliable than other libraries such as Flask-Migrate or Django-Migrate

Of course, these are just my personal preferences and opinions. You may have different ones, and that's totally fine. The beauty of FastAPI is that it lets you use any template engine, database, frontend framework, or tool that you want.

That's why I encourage you to check out FastAPI Template and see if it suits your needs and preferences. And if you have any feedback, suggestions, or issues, please feel free to open an issue or a pull request on GitHub. I would love to hear from you and improve the template.

Conclusion
FastAPI Template is a template that gives you a ready-to-use FastAPI project with best practices. It can save you a lot of time and effort when starting a new FastAPI project, and help you create robust and scalable applications.

I hope you find it useful and enjoy using it. And if you do, please consider giving it a star on GitHub and sharing it with your friends and colleagues. Thank you!
