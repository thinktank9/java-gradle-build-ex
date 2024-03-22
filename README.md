# java-gradle-build-ex

Java Spring Gradle Build Dockerfile example

## Exercise

- Build the docker image using the multistage dockerfile.
    - The first stage builds the java project using Gradle
    - The second stage runs the WAR file generated from the build stage
- Run the container with port 8080 mapped to the host port.
- The application will fail to run, you need to find the error, fix it and rebuild the image to get it to work.