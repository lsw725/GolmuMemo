# 컨테이너는 host와 다른 모든 프로세스들과 독립된 machine에서 작동하는 샌드박스화된 프로세스이다.
---
생성일시: 2022-09-20 22:33

컨테이너의 고립을 위해 kernel namespaces와 cgroups이 사용된다.

예전부터 있었던 위의 기능을 바탕으로 host machine과 다른 컨테이너들과 분리되어 작동하는 프로세스 환경을 만들 수 있다.

## 레퍼런스
---
1. [도커 Docs - Docker Overview](https://docs.docker.com/get-started/overview/)
