FROM ubuntu:20.04
RUN apt-get upgrade 
RUN apt-get update
RUN apt-get update \
  && apt-get install -y python3-pip python3-dev \
  && cd /usr/local/bin \
  && ln -s /usr/bin/python3 python \
  && pip3 install --upgrade pip 
CMD tail -f /dev/null
