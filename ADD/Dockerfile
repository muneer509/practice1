# ADD instuction is used to copy files, directories, or remote file URLs from the host machine (the machine where the Docker build is being executed) into the filesystem of the Docker image being built.
FROM almalinux:9
RUN dnf install nginx -y
ADD https://www.imdb.com/title/tt0944947/ /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]