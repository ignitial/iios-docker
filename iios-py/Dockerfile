FROM ubuntu:16.04

# Install required packages and remove the apt packages cache when done.
RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y \
    git \
    python3 \
    python3-dev \
    python3-setuptools \
    python3-pip && \
    pip3 install -U pip setuptools && \
    rm -rf /var/lib/apt/lists/*
