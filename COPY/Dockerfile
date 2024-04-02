FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /user/share/nginx/html/index.html
COPY index.html /user/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]
