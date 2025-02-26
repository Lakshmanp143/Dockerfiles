#Base os
FROM almalinux:9
#using run command can install packages, configureation on top of base image
RUN dnf install nginx -y
#labels used to give the metadata and also using filteration
LABEL project="expense"\
      environment="dev"\
      component="backend"\
      author="Lakshman"