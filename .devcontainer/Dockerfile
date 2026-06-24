FROM mcr.microsoft.com/devcontainers/python:3.13

ENV PYTHONUNBUFFERED=1

RUN apt-get update && \
    apt-get install -y curl poppler-utils

RUN pip install --upgrade pip