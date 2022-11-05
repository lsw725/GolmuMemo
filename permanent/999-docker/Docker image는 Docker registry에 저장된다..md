# Docker image는 Docker registry에 저장된다.
---
생성일시: 2022-09-15 01:40

기본적으로, 도커는 Docker Hub라는 public registry에서 image를 찾아서 구성한다.

``docker pull`` 이나 ``docker run`` 명령을 실행하면, 구성된 registry에서 image를 찾아서 작업한다.

``docker push``명령은 구성된 registry로 이미지를 업로드한다.

나 자신의 private registry를 구성하는 것도 가능하다.

git의 동작방식과 유사하다.

## 레퍼런스
---
1.  [도커 Docs - Docker Overview](https://docs.docker.com/get-started/overview/)
