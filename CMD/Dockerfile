FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello my migga" > /usr/share/nginx/html/hello.html
# damon off command makes our container running and attached to screen
CMD [ "nginx", "-g", "daemon off;" ]