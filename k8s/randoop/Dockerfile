FROM maven:3.5.4-ibmjava-8-alpine

RUN apk add --no-cache \
         git \
&& git clone https://github.com/zaplatynski/randoop-maven-plugin.git \
&& cd randoop-maven-plugin \
&& mvn clean install


CMD ['ls -l']
