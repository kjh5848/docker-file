FROM ubuntu

WORKDIR /etc/init.d

RUN apt-get update && apt-get -y install nginx

CMD ["sh", "-c", "./nginx start"]