# Linux Container는 Linux환경에서 작동하는 경량화된 VM의 구현이 목적이다.
---
생성일시: 2022-09-07 02:30

#컨테이너 #리눅스 #VM
Linux Container는 동일한 운영체제 커널을 공유하고 시스템의 나머지 부분으로부터 애플리케이션 프로세스를 격리한다.

하이퍼바이저를 통한 가상화와 달리 기존 OS의 커널을 공유하여 "운영체제 수준의 가상화"를 만들어 낸다.
따라서 하이퍼바이저 위에서 게스트 OS전체가 올라가지 않기 때문에 더욱 가볍게 VM과 비슷한 가치를 경험할 수 있다.

## 레퍼런스
---
1. [Docker vs LXC 비교](http://wiki.rockplace.co.kr/pages/viewpage.action?pageId=3868344) 
2. [리눅스 컨테이너란 무엇인가?](https://www.redhat.com/en/topics/containers/whats-a-linux-container)
3. [도커를 공부하는 초보자를 위한 안내서 1편 - 컨테이너 개념](https://tech.ktcloud.com/69?category=465864)