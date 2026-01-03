# EXPOSE instructs Docker to expose a specific port at runtime. it does not publish the port to the host machine; it simply serves as documentation and a hint to users of the image about which ports are intended to be published.    
 # it won't actually make the port accessible from outside the container unless you explicitly publish it using the -p or -P flag when running the container.
FROM almalinux:9    
RUN dnf install nginx -y
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]