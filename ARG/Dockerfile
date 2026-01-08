# ARG is used to define build-time variables that can be passed to the Docker build process.
# These variables can be used to customize the build process and provide flexibility in configuring the Docker image
# without hardcoding values directly into the Dockerfile.
# ARG variables are only available during the build stage and cannot be accessed at runtime within the container.
# This allows for dynamic configuration of the build process, such as specifying versions, paths, or other parameters that may vary between different builds.
# ARG instruction before the FROM instruction will define variables that can be used in the FROM line, but will not be available after that line.
# to use ARG values inside the container at runtime, you need to use ENV instruction to set environment variables based on ARG values.
ARG image_version=latest
FROM almalinux:${image_version:-9}
ARG APP_VERSION=1.0.0
ARG APP_ENV=${APP_ENV:-test}
ARG APP_COMPONENT=${APP_COMPONENT:-web}
RUN echo "Image version: ${image_version}"
RUN echo "Building application version: $APP_VERSION"
RUN echo "Application environment: $APP_ENV"
CMD ["sleep", "infinity"]