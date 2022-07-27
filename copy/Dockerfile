FROM ubuntu:latest
#nginx is used to run as the web server
RUN apt-get -y update nginx
COPY index.html /var/www/html


#EXPOSE the port to HTTP :80
EXPOSE 80/tcp
CMD ["/bin/bash"]
