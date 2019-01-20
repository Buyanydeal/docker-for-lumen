FROM ubuntu:18.04
LABEL maintainer="ruud.vanengelenhoven@gmail.com"

RUN apt-get update && apt-get install -y  --no-install-recommends \
    apt-utils=1.6.6 \
    cron=3.0pl1-128.1ubuntu1 \
    curl=7.58.0-2ubuntu3.5 \
    git=1:2.17.1-1ubuntu0.4 \
    openssl=1.1.0g-2ubuntu4.3 \
    ssh=1:7.6p1-4ubuntu0.1 \
    sudo=1.8.21p2-3ubuntu1 \
    supervisor=3.3.1-1.1 \
    unzip=6.0-21ubuntu1 \
    vim=2:8.0.1453-1ubuntu1 \
    wget=1.19.4-1ubuntu2.1 \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*