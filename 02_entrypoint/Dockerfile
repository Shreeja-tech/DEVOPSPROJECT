# Example -2 - entrypoint 
# base image
FROM ubuntu:latest          
#Entrypoint cannot be overwritten , anythin written after entrypoint command will be treated as an argument for the command
#if command is written as entrypoint, secondary person cannot access the container and overwrite the command . Whatever he runs in the container will be taken as argument.
ENTRYPOINT ["/bin/bash"]
#base image - nginx
FROM nginx:latest
