FROM ubuntu:18.04
LABEL maintainer="ruud.vanengelenhoven@gmail.com"

RUN apt-get update && apt-get install -y  --no-install-recommends \
    apt-utils \
    cron \
    curl \
    git \
    openssl \
    ssh \
    sudo \
    supervisor \
    unzip \
    vim \
    wget \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*