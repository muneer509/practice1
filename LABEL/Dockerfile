#Lable add meta data to image like maintainer, version, description etc.
FROM almalinux:9
LABEL maintainer="developer@example.com"
LABEL version="1.0"
LABEL description="This is an Almalinux 9 image with Nginx installed."
LABEL Owner="Dev Team"
LABEL Created_Date="2024-06-15"
LABEL Creator="Muneer"
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]