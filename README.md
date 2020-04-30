# docker-jdk-utils
Docker Images for building JDK projects with AWS CLI

- Uses Ubuntu 18.04
Packages:
- openjdk-{8|11}-jdk-headless
- maven
- awscli

Images can be pulled from [Dockerhub](https://hub.docker.com/repository/docker/rrampage/docker-jdk-utils)

e.g:

Java 8:
```
docker pull rrampage/docker-jdk-utils:jdk-8
```

Java 11:
```
docker pull rrampage/docker-jdk-utils:jdk-11
```
