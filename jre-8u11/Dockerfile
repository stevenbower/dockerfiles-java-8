FROM centos

MAINTAINER Lothar Wieske <lothar.wieske@gmail.com>

RUN yum update -y

RUN curl --insecure --junk-session-cookies --location --remote-name --silent --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u11-b12/jre-8u11-linux-x64.rpm

RUN yum localinstall -y jre-8u11-linux-x64.rpm
RUN rm jre-8u11-linux-x64.rpm

ENV JAVA_HOME /usr/java/default
