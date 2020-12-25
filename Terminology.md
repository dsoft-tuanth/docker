# Docker Terminology
This topic provides a very brief summary of the key terms you need to be familiar with when working with Docker. For more information see _The Docker Documentation site_.

__Container__
>A run-time instance of an image.

>A container is usually completely isolated from the host environment, only able to access host files and ports if it has been configured to do so.

>To run an image in a container you use the docker run command.

__Docker Hub__
>A cloud-based community resource for working with Docker.

>A key use for Docker Hub is hosting images, but it is also used for activities such as user authentication and the automation of image building. Anyone is free to publish images to Docker Hub. No checking or verification is carried out on individuals or organizations who submit images to Docker Hub.

__Docker Store__
>A cloud-based resource that is similar to Docker Hub, but the images on Docker Store have been submitted by commercial entities who have been approved or certified by Docker.

__Dockerfile__
>A text document containing the commands to build a Docker image.

>The commands you can specify in a Dockerfile range from the complex (such as specifying an existing image to use as a base) to the simple (such as copying files from one directory to another). For example, you can create a Dockerfile that uses the ubuntu image as a base, but also installs the Apache web server, your application, and any required configuration options.

>To build an image from a Dockerfile you use the docker build command.

__Image__
> A standalone, executable package that be run in a container.

>A Docker image is a binary that includes all of the requirements for running a single Docker container, as well as metadata describing its needs and capabilities.

> An image includes everything that is needed to run an application, including the application's executable code, any software on which the application depends, and any required configuration settings. You can build your own images (using a Dockerfile) or use images that have been built by others and then made available in a registry (such as Docker Hub).

>To build an image from a Dockerfile you use the docker build command.

>To run an image in a container you use the docker run command.


