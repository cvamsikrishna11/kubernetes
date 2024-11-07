# kubernetes


For mac builds and runs
```
docker build --platform=linux/amd64 . -t IMAGE_NAME

docker run --platform=linux/amd64 -d -p 8081:8081 IMAGE_NAME
```