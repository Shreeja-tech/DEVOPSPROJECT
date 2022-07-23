#giving multiple entrypoints
FROM ubuntu:latest
ENTRYPOINT ["/bin/echo","Aloha 1"]
ENTRYPOINT ["/bin/echo","Aloha 2"]
ENTRYPOINT ["/bin/echo","Aloha 3"]
ENTRYPOINT ["/bin/echo","Aloha 4"]
CMD ["/bin/echo","Aloha 5"]
#it will execute the last entrypoint function with the CMD command as argument
ENTRYPOINT ["/bin/echo","Aloha 1"]
CMD ["/bin/echo","Aloha 2"]
CMD ["/bin/echo","Aloha 3"]
CMD ["/bin/echo","Aloha 4"]