# COPY instuction is used to copy files and directories from the host machine (the machine where the Docker build is being executed) into the filesystem of the Docker image being built.
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]