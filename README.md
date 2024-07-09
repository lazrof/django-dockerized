# General Notes
- Dockerfile and docker-compose.yml created from https://github.com/docker/awesome-compose/blob/master/official-documentation-samples/django/README.md


# Useful Commands

To create a new django project:
```
docker compose run web django-admin startproject composeexample .
```

To run migrations
```
docker compose run web python manage.py migrate
```

To run python inside docker container
```
docker compose run web python
```
