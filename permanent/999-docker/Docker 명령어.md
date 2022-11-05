# Docker 명령어
---
생성일시: 2022-09-21 00:06

## Docker Image 빌드
``` shell
docker build -t <image-tag> <path>
```

## Docker Container 실행
```Shell
docker run -dp 3000:3000 <image-tag>
```

## Container 조회
``` shell
docker container ls
docker container ls -a #모든 Container 조회
```

## Container 삭제
```shell
docker rm <container-id>
docker rm -f <continer-id> #강제 삭제(실행중이던 뭐던...)
```


## 레퍼런스
---
1. [도커 Docs - Get started](https://docs.docker.com/get-started)
