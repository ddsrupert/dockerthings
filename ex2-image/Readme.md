## A Very Simple Dockerfile

```
cat Dockerfile 
FROM python:latest
RUN pip install numpy
docker build . --tag python-numpy-2
Sending build context to Docker daemon  3.072kB
Step 1/2 : FROM python:latest
 ---> 79e1dc9af1c1
Step 2/2 : RUN pip install numpy
 ---> Using cache
 ---> b5cce790f839
Successfully built b5cce790f839
Successfully tagged python-numpy-2:latest
docker images
REPOSITORY                        TAG                 IMAGE ID            CREATED              SIZE
python-numpy-2                    latest              b5cce790f839        About a minute ago   789M
```
