FROM mcr.microsoft.com/devcontainers/java:17-bullseye

RUN rm -f /etc/apt/sources.list.d/yarn.list \
    && apt-get clean \
    && apt-get update \
    && apt-get install -y openssh-server \
    && mkdir -p /run/sshd \
    && ssh-keygen -A
