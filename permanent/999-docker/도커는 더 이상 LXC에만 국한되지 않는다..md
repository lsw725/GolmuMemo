# 도커는 더 이상 LXC에만 국한되지 않는다.
---
생성일시: 2022-09-07 02:08

#도커 #클라우드 #컨테이너 #리눅스 #LXC

[[901b1-LXC는 Linux Container를 잘 사용 하게 만드는 오픈소스 컨테이너 플랫폼이다.]] 

도커의 첫번째 구현도 LXC를 그대로 사용했으나 [[901b1-LXC는 Linux Container를 잘 사용 하게 만드는 오픈소스 컨테이너 플랫폼이다.|LXC는 Linux Container를 제공하는 플랫폼 이며, ]] [[901a1-Linux Container는 Linux환경에서 작동하는 경량화된 VM의 구현이 목적이다.|Linux Container는 Linux환경에서 작동하는 경량화된 VM의 구현이 목적이다.]] 

도커는 랩톱 및 Linux 배포판 전반에 걸쳐 개발자 커뮤니티에 컨테이너의 혜택을 제공하려는 목적으로 만들어졌다.

이를 위해 LXC에 대한 지원을 기본 실행 환경으로 지정하지 않고 자체 구현으로 대체했다.

## 레퍼런스
---
1.  [도커가 무엇이고 어디에 쓰이는가?](https://www.ctl.io/developers/blog/post/what-is-docker-and-when-to-use-it/) 
2.  [Docker vs LXC 비교](http://wiki.rockplace.co.kr/pages/viewpage.action?pageId=3868344) 
