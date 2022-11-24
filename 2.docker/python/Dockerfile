FROM python:3.9-alpine

RUN pip install django==3.2 && pip install Flask

ADD . /app

EXPOSE 8080

ENTRYPOINT python /app/app.py runserver 0.0.0.0:8080
