# Getting Started react app with docker

Dockerfile을 통해 간단한 react application을 구동하기 위한 샘플 프로젝트 입니다.

## Check docker version

```shell
docker version
```

## Build Docker image

```shell
docker build -f Dockerfile.dev -t <도커 허브 계정명>/docker-react-app-test ./
```

### Check Docker image

```shell
docker images
```

### Run Docker Container

```shell
docker run -it -d -p 3000:3000 <도커 허브 계정명>/docker-react-app
```

### Check Docker container process

```shell
docker ps
```

### Enter local web service

```
localhost:3000
```