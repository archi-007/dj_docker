FROM python:3.6.9
LABEL maintainer = "admin@localhost"

COPY ./core /core

WORKDIR /core

RUN pip install -r requirements.txt


CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]



