FROM ubuntu
MAINTAINER James Hunt <james@niftylogic.com>
EXPOSE 80

RUN apt-get update \
 && apt-get install -y openssh-client \
 && rm -rf /var/lib/apt/lists/*

COPY assets /shield

CMD ["/shield/init"]
