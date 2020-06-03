# Codebase Django

- Codebase Django is a guide to boost ready-to-use Django code.
- Powered by [Cookiecutter ](https://github.com/cookiecutter/cookiecutter "Cookiecutter ").
- Thanks to [Pablo Trinidad](https://github.com/pablotrinidad "Pablo Trinidad")

#### Features
- For Django 2.2.12
- Works with Python 3.8
- Work with PostgreSQL 10.5, but customizable.
- Work with Celery
- Work with Redis 5.0
- Realizar pruebas con undátest o pytest
- Optimized development and production settings.
- Send emails via [Anymail](https://github.com/anymail/django-anymail "Anymail") (using [Mailgun](https://www.mailgun.com/ "Mailgun") by default).
- Docker support using [docker-compose](https://github.com/docker/compose "docker-compose") for development.
- Default integration with pre-commit for identifying simple issues before submission to code review.

#### Optional Integrations
- Configuration for [Celery](http://www.celeryproject.org/ "Celery") and [Flower](https://github.com/mher/flower "Flower") (the latter in Docker setup only)

#### Constraints
- Only maintained 3rd party libraries are used.
- Uses PostgreSQL everywhere.
- Environment variables for configuration (This won't work with Apache/mod_wsgi).


#### Development
I will try to update and improve this codebase as I learn more.
To get started on this project, I recommend you check out the [Django](https://docs.djangoproject.com/es/2.2/ "Django"), [Cookiecutter](https://github.com/pydanny/cookiecutter-django "Cookiecutter") [pydanny](https://github.com/pydanny "pydanny") documentation on how to make this project run locally. Thanks to [Pablo Trinidad](https://github.com/pablotrinidad "Pablo Trinidad")
If you don't want to, just run:

Warning: This code is in development, we know that nothing is perfect, but it can already be used. I am improving it.

Create a git repo and push it there:

#### Contributing
I will be happily accepting pull requests from anyone.

#### Development

```
docker-compose -f local.yml build
docker-compose -f local.yml up
```

#### Do you want to use this project as yours?
Please stick to the [LICENSE](https://github.com/LhernerRemon/Codebase_/blob/master/LICENSE "LICENSE").

I learned a lot by modifying the original project and adapting it to different needs. Feel free to modify, distribute, use privately, etc; since please just include the copyright and the license.

#### Collaborators
Lherner Remón | UNSCH Systems Engineering Student | lherner.remon.27@unsch.edu.pe
