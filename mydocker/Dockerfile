FROM centos:7.7.1908
MAINTAINER "Gaush Arshad Ali gausharshadali@gmail.com"

RUN yum install httpd wget  openssh net-tools bind-utils unzip vim -y && \
    yum clean all && \
    rm -rf /var/cache/yum/*

RUN mkdir -p /var/www/html/myapp
COPY  index.html /var/www/html/myapp
WORKDIR /var/www/htm/myapp
EXPOSE 80
EXPOSE 443
CMD ["/user/sbin/httpd","-D","FORGRUND"]


