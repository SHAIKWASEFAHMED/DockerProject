FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf cd /usr/share/nginx/html/index.html
COPY Electric Commercial Vehicle Group.html /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]