FROM centos:latest

ENV TERM xterm
VOLUME ["/data"]
EXPOSE 443

RUN yum install -y git bzip2

# Local Registry Credentials
COPY .npmrc /root/
COPY .netrc /root/

# Basic tools install
# RUN npm install -g jspm gulp eslint karma-cli@0.1.2
