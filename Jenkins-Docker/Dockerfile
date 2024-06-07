FROM jenkins/jenkins:latest-jdk17

USER root

RUN apt-get update && apt-get install -y docker.io

RUN apt update && apt install tzdata -y

ENV TZ='America/Chicago'

RUN date

USER jenkins