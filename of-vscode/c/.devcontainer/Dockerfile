FROM mcr.microsoft.com/devcontainers/cpp:ubuntu-24.04 

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get -y install --no-install-recommends git && \
    apt-get clean && rm -rf /var/lib/apt/lists/*