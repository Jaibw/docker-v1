FROM ubuntu
MAINTAINER DevOps Team it@abc.com
RUN mkdir /data
RUN apt update && apt install vim nano curl wget -y 
RUN echo "echo 'Welcome to ABC company' " >> /root/.bashrc
EXPOSE 80
VOLUME /data
CMD ["/bin/bash"]
