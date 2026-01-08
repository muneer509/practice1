# User instruction is used to set up a non-root user environment in the Docker container.
# Running containers as a non-root user enhances security by limiting the permissions and access rights of the processes running inside the container.
# This helps to mitigate potential security risks and vulnerabilities that could arise from running applications with elevated privileges.
FROM almalinux:9
CMD ["sleep", "infinity"] \
 ["whoami"] \
 ["id"]
RUN useradd expense
USER expense
CMD ["whoami"] \
 ["id"]