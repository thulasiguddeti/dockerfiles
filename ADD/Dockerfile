FROM almalinux:8 
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/thulasiguddeti/concepts/refs/heads/main/ansible%20imp%20questions /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]