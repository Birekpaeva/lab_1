FROM amazonlinux:latest
RUN yum update -y && yum install yum-utils -y
COPY ./script.sh ./script.sh
RUN chmod u+x script.sh
CMD ./script.sh
