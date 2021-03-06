[![Docker Stars](https://img.shields.io/docker/stars/dmreiland/alpine-tomcat8.svg?style=flat-square)](https://hub.docker.com/r/dmreiland/alpine-tomcat8/)
[![Docker Pulls](https://img.shields.io/docker/pulls/dmreiland/alpine-tomcat8.svg?style=flat-square)](https://hub.docker.com/r/dmreiland/alpine-tomcat8/)


# Tomcat 8 and Oracle JRE 8 Docker image

This image is based on Alpine Linux image, which is only a 5MB image, and contains:
[Oracle JRE 8](http://www.oracle.com/technetwork/java/javase/overview/index.html)
[Apache Tomcat 8](https://tomcat.apache.org/download-80.cgi)

You must accept the
[Oracle Binary Code License Agreement for Java SE](http://www.oracle.com/technetwork/java/javase/terms/license/index.html)
to use this image.

The JRE bundle contains lots of unnecessary kit for a Docker container, so we cleaned it up: source tarballs and desktop components are removed.

`latest` (`master` branch) download image size is:

Because I'm opinionated, and don't care for the default logging that Tomcat as, I have replaced it with [SLF4J Logback](https://github.com/tomcat-slf4j-logback/tomcat-slf4j-logback).

[![](https://images.microbadger.com/badges/image/dmreiland/alpine-tomcat8:latest.svg)](http://microbadger.com/images/dmreiland/alpine-tomcat8:latest "Get your own image badge on microbadger.com")
