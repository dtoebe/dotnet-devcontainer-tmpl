# [ CHOICE ] DOTNET_VERSION = 6.0, 7.0, 8.0
ARG DOTNET_VERSION=8.0
FROM mcr.microsoft.com/vscode/devcontainers/dotnet:${DOTNET_VERSION}

USER root
RUN . /usr/local/share/nvm/nvm.sh; nvm install lts/*

# [ OPTIONAL ] Uncomment if you want to install additional deps
# RUN apt-get update && \
#     export DEBIAN_FRONTEND=noninteractive \
#     apt-get -qy full-upgrade && \
#     apt-get -qy curl wget