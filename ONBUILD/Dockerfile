# ONBUILD instruction is used to add triggers to a base image that will execute specified instructions when the image is used as a base for another build.
# It allows you to define a set of instructions that will be automatically executed in the child image during its build process.
# This is useful for creating reusable base images that can enforce certain configurations or setups in derived images.
# ONBUILD instructions are typically used in scenarios where you want to ensure that specific steps are always performed in child images, such as copying files, installing dependencies, or setting environment variables.
FROM almalinux:9    

ONBUILD RUN echo "This is an ONBUILD instruction executing during the build of a child image."
ONBUILD COPY . /app/    
ONBUILD WORKDIR /app/
ONBUILD RUN echo "Files copied to /app/ directory in the child image."
CMD ["sleep", "infinity"]
# ONBUILD is used to add build instructions that will be executed when the image is used as a base for another build.
