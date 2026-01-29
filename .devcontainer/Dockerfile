FROM mcr.microsoft.com/devcontainers/python:1-3.12


RUN rm -f /etc/apt/sources.list.d/yarn.list \
    && rm -f /etc/apt/trusted.gpg.d/yarn.gpg /usr/share/keyrings/yarn*.gpg \
    && apt-get update -y
