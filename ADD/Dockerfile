FROM almalinux:8 
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html
ADD https://raw.githubusercontent.com/thulasiguddeti/concepts/refs/heads/main/ansible%20imp%20questions /tmp/concepts.txt
ADD sample-1.tar /tmp/
CMD ["nginx","-g","daemon off;"]  