# WORKDIR instruction is used to set the working directory for any subsequent instructions in the Dockerfile.
# It establishes the context in which commands will be executed within the container.
# Setting a WORKDIR helps to organize files and ensures that commands are run in the correct directory, making it easier to manage file paths and maintain consistency throughout the Dockerfile.
# If the specified directory does not exist, WORKDIR will create it.
FROM almalinux:9
RUN mkdir -p /app/
run cd /app/
run pwd
run echo "This is the WORKDIR /app directory" hello.txt
cmd ["sleep", "infinity"]