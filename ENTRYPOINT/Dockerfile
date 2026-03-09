FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "hello my GIGGA CHAD" > /usr/share/nginx/html/index.html
ENTRYPOINT ["nginx","-g","daemon off;"]
