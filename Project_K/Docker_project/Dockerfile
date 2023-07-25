FROM ubuntu:20.04
RUN apt update -y
RUN apt-get install nginx -y 
RUN  systemctl enable nginx
CMD [ "/usr/sbin/init" ]