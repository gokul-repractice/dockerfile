FROM almalinux:8
RUN yum install nginx -y
EXPOSE 80/tcp
# This image opens port 80 in TCP ptotocol, i.e nothng but Internet protocol.
CMD ["nginx","-g","daemon off;"] # this is executable format. We give every word in seperate quotes.
