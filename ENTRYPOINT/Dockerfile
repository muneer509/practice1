# ENTRYPOINT instructions is used for specifying the default command to run within a container when the container starts up. It allows you to define a command that will always be executed when the container starts, regardless of any command passed in during the docker run command.
FROM almalinux:9
RUN dnf install nginx -y
CMD ["ping", "google.com"]