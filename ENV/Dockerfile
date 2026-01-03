# ENV instuction sets environment variables in the container. These variables can be used by applications running inside the container or during the build process.
FROM almalinux:9    
ENV NGINX_VERSION=1.20.1
ENV NGINX_USER=nginx
ENV NGINX_PORT=8080
ENV NGINX_WORKER_PROCESSES=auto
ENV NGINX_WORKER_CONNECTIONS=1024
ENV NGINX_LOG_DIR=/var/log/nginx
ENV NGINX_HTML_DIR=/usr/share/nginx/html
ENV NGINX_CONF_DIR=/etc/nginx
ENV NGINX_PID_FILE=/var/run/nginx.pid
ENV NGINX_SBIN=/usr/sbin/nginx
ENV NGINX_DEFAULT_CONF=/etc/nginx/conf.d/default.conf
ENV NGINX_INDEX_FILE=index.html
ENV NGINX_ERROR_LOG=error.log
ENV NGINX_ACCESS_LOG=access.log
ENV NGINX_ENV=production
ENV PATH=$PATH:/usr/sbin/nginx
