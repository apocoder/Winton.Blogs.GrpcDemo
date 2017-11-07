FROM openjdk:8
RUN \
  curl -L -o sbt-2.11.8.deb http://dl.bintray.com/sbt/debian/sbt-2.11.8.deb && \
  dpkg -i sbt-2.11.8.deb && \
  rm sbt-2.11.8.deb && \
  apt-get update && \
  apt-get install sbt && \
  sbt sbtVersion
