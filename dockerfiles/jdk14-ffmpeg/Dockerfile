FROM alpine AS release
#install ffmpeg openjdk
RUN         apk add --no-cache --update --repository http://nl.alpinelinux.org/alpine/edge/testing openjdk14-jdk ffmpeg
#java
ENV JAVA_HOME=/usr/lib/jvm/java-14-openjdk
ENV CLASSPATH=.:$JAVA_HOME/lib
ENV PATH=$PATH:$JAVA_HOME/bin

ENTRYPOINT  ["sh"]
