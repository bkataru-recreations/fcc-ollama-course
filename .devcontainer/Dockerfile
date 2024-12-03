FROM python:3.13

# refresh
RUN apt update -y && apt upgrade -y

# refresh python toolchain
RUN pip install --upgrade pip setuptools wheel

WORKDIR /workspace
COPY .. .

USER root
RUN /bin/bash

