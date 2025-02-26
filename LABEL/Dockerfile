#Base os
FROM almalinux:9
#using run command can install packages, configureation on top of base image and executes commands
RUN dnf install nginx -y
#labels used to give the metadata and also using filteration(0functionality won't change just informational)
LABEL project="expense"\
      environment="dev"\
      component="backend"\
      author="Lakshman"