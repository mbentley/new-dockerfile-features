# Dockerfile features & best practices

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
