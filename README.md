## Dockerfiles for Oracle Java 8

jdk+jre+server-jre 8u00+8u05+8u11+8u20+8u25+8u31+8u40


**Dockerfiles** for [Oracle Java 8](http://www.oracle.com/technetwork/java/index.html)
for Docker Automated/Trusted Builds.

### GitHub Repository

* [dockerfiles-java-8](https://github.com/lwieske/dockerfiles-java-8)

### Dependencies

* [centos](https://registry.hub.docker.com/_/centos/)

### Usage Java 8

    docker run -i -t lwieske/java-8 bash

### Java 8 Example

    docker run -i -t lwieske/java-8 bash

    $ java -version

### Vagrantfile

The Vagrantfile can be used for local builds (development/test).
