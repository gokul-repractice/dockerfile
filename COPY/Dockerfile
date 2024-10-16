FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html 
# This will remove default html page.
COPY index.html /usr/share/nginx/html
#This will add index.html, which we created.
CMD ["nginx","-g","daemon off;"] # this is executable format. We give every word in seperate quotes.
