FROM ubuntu
MAINTAINER 312012733 "312012733@qq.com"
RUN apt-get update
RUN apt-get -y upgrade
RUN apt-get install -y nginx
RUN apt-get install -y net-tools
RUN apt-get install -y vim
RUN apt-get install -y lsof
RUN apt-get install -y inetutils-ping

#COPY page/index.html /var/www/html/
#COPY page/index.html /var/www/html/test.html
#ADD page/dockerFile.tar /var/www/html/tmp
#ADD page/dockerFile.tar /var/www/html/tmp2/

EXPOSE 80

#CMD ["/usr/sbin/nginx","-g","daemon off;"]
#CMD /usr/sbin/nginx -g "daemon off;"

#ENTRYPOINT ["/usr/sbin/nginx","-g","daemon off;"]
#ENTRYPOINT /usr/sbin/nginx -g "daemon off;"

#ENTRYPOINT ["/usr/sbin/nginx"]
#CMD ["-g","daemon off;"]

#ENTRYPOINT ["/usr/sbin/nginx"]
#CMD ["-g","daemon off;"]
