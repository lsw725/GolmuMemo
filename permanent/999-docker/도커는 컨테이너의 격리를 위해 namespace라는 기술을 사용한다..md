# 901h1b-도커는 컨테이너의 격리를 위해 namespaces라는 기술을 사용한다.
---
생성일시: 2022-09-15 02:26

도커는 컨테이너를 실행할 때, 컨테이너에 대한 namespace set를 생성하는데, 이런 namespace는 격리 계층을 제공한다. 컨테이너의 각 측면은 별도의 namespace에서 실행되며, 접근 또한 해당 namespace로 제한되기 때문이다.

## 레퍼런스
---
1.  [도커 Docs - Docker Overview](https://docs.docker.com/get-started/overview/)
