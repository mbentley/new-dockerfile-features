# An Opinionated View of Building Docker Images and Pipelines
Docker Indy Meetup - May 29,2018

### Build & run the "bad" image
```
docker build -f Dockerfile.bad -t test:bad .
docker run -it --rm test:bad
```

### Build & run the "good" image
```
docker build -f Dockerfile.good -t test:good .
docker run -it --rm test:good
```

### Compare the size
```
docker images test
```

### Live Demo
The `Dockerfile.live` was the live conversion we did from `Dockerfile.bad` to try to get close to `Dockerfile.good`
