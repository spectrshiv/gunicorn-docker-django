# gunicorn-docker-django

Just a simple docker container setup using gunicorn and django
This is not using nginx as a proxy. Not recommended for use by humans.

requirements
docker.io and docker-compose
no standards


1. Rename app name in /src/manage.py to your django folder name
2. Place django folder in /src/
3. Update /config/requirements.pip with your required python modules
4. Run `docker-compose up --build -d` to start