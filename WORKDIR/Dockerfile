# WORKDIR instruction is used to set the working directory for any subsequent instructions in the Dockerfile.
# It establishes the context in which commands will be executed within the container.
# Setting a WORKDIR helps to organize files and ensures that commands are run in the correct directory, making it easier to manage file paths and maintain consistency throughout the Dockerfile.
FROM almalinux:9
RUN mkdir -p /app/logs
RUN mkdir -p /app/data
RUN cd /app/data && touch datafile.txt
CMD ["sleep", "infinity"]