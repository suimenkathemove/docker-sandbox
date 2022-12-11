FROM --platform=linux/x86_64 ubuntu:23.04

ARG WORK_DIR="/workdir"

COPY . ${WORK_DIR}

RUN apt-get update && apt-get install -y \
  curl \
  unzip \
  sudo
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN unzip awscliv2.zip
RUN sudo ./aws/install

WORKDIR ${WORK_DIR}
