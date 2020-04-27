FROM ubuntu:bionic-20200403

ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update -y && apt-get install -y --no-install-recommends openjdk-8-jdk-headless awscli && apt-get install -y --no-install-recommends maven && apt-get autoremove --purge -y && apt-get clean && rm -rf /var/lib/apt/lists/*

