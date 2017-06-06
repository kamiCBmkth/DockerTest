# setting base image
FROM centos:centos6

# Author
MAINTAINER kamiCBmkth

# install Apache http server
RUN ["yum",  "-y", "install", "httpd"]

# start httpd
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
