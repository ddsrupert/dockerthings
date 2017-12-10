## Run some simple containers


```
# download a small test image and run it
docker run hello-world

# view information about the image
docker images hello-world
REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
hello-world         latest              f2a91732366c        2 weeks ago         1.85kB 

# dump meta-data from the image
docker inspect hello-world

# view all running & stopped processes
docker ps -aq

CONTAINER ID        IMAGE               COMMAND             CREATED             STATUS                     PORTS               NAMES
e0d9086f7af4        hello-world         "/hello"            4 seconds ago       Exited (0) 3 seconds ago                       priceless_heisenberg

# remove the container
docker rm priceless_heisenberg


```

## Links
[Entry in Docker Hub Repository](https://hub.docker.com/_/hello-world/)
[Source code on Github](https://github.com/docker-library/hello-world)