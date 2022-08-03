FROM python:3.9-slim as build

RUN apt-get update && apt-get install -y libcairo2-dev python3-dev libffi-dev git libmagic1

COPY . /home/python/app/

WORKDIR  /home/python/app
ENTRYPOINT ["/entrypoint.sh"]
