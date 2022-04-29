FROM python:3.9

WORKDIR /app

RUN apt-get update

RUN pip install --upgrade pip
RUN pip install --upgrade setuptools

RUN python -m pip install "fastapi[all]"

COPY . ./