FROM ubuntu:trusty

RUN apt-get update \
&& apt-get install -y git 
RUN git clone https://github.com/facebook/fbctf \
&& cd fbctf \
&& ./extra/provision.sh -m prod -s .

CMD ["/bin/bash"]
