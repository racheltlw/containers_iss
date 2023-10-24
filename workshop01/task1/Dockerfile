FROM python:3.10-slim-buster

LABEL name=task1-app

ARG APP_DIR=/app

WORKDIR ${APP_DIR}

COPY python/. . 

RUN pip install -r requirements.txt

ENV PORT=3000

ENV INSTANCE_NAME = ''

ENV INSTANCE HASH = ''

EXPOSE ${PORT}

ENTRYPOINT ["/bin/bash", "-c", "./run.sh"]


