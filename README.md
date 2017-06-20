# Node_DockerFile
# A minimal Docker image based on Alpine Linux with a complete package index and only 5 MB in size!
# What is Alpine Linux?
Alpine Linux is a Linux distribution built around musl libc and BusyBox. The image is only 5 MB in size and has access to a package repository that is much more complete than other BusyBox based images. This makes Alpine Linux a great image base for utilities and even production applications. Read more about Alpine Linux here [https://hub.docker.com/_/alpine/] and you can see how their mantra fits in right at home with Docker images.

# Dockerfile2 from node which does not need any installtion.
# how to build docker and run docker image
* docker build -t myapp . 
* docker run -p -it 8080:3000 myapp
# Directory structure
put you docker file in *root* and all the application file in *app* folder


![Directory Structure](https://github.com/Adiii717/Node_DockerFile/blob/master/directory.png)
