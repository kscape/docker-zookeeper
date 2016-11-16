# Resources

[Dockerize Zookeeper](http://sookocheff.com/post/docker/containerizing-zookeeper-a-guided-tour/) tutorial for setting up the Dockerfile and container.

# Building and Running
```
docker build -t kscape/docker-zookeeper:latest .
```

```
docker run -it -p 2181:2181 kscape/docker-zookeeper:latest
```
