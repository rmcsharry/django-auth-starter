# django-auth-starter
A simple API repo that can be used as a starter to provide authentication to any DRF project.

# Linting
docker-compose run --rm app sh -c "flake8"

# Run tests
docker-compose run --rm app sh -c "python manage.py test"

# Created django with
docker-compose run --rm app sh -c "django-admin startproject app ."
