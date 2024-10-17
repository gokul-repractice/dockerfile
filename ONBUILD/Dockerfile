FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# Here we are remiving default html page.
ONBUILD ADD index.html usr/share/nginx/html/
# Here we are forcing everyone should have index.html on their own and should be copied to /usr/share/nginx/html/.Otherwise we will get error.
CMD ["nginx","-g","daemon off;"]