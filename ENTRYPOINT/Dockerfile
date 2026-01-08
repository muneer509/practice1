# ENTRYPOINT instructions is used for specifying the default command to run within a container when the container starts up. It allows you to define a command that will always be executed when the container starts, regardless of any command passed in during the docker run command.
# ENTRYPOINT can't be overridden at runtime like CMD can.
# ENTRYPOINT is often used to set up the main application or service that the container is intended to run.
# ENTRYPOINT is useful when you want to ensure that a specific command is always executed when the container starts, regardless of any additional commands or arguments provided at runtime.
# FROM almalinux:9
# RUN dnf install nginx -y
# ENTRYPOINT ["ping"]
# CMD ["google.com"]
FROM almalinux:9
# CMD ["ping", "google.com"]
ENTRYPOINT ["ping"]
CMD ["terraform.io "]

