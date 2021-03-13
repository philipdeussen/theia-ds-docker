# Docker image with Theia IDE and Python/R packages

This is a ready-to-run docker image containing Theia IDE alongside some R and Python packages.

## Quick Start

Docker needs to be installed on your machine to try the image. 
If you have Docker installed you can now run the image with the following command:

docker run -it --init -p 3000:3000 --rm -v $("pwd"):/home/theia/project/ philipdeussen/theia-ds

This will pull the latest image from DockerHub and run it. 
