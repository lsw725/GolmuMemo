# Dockerfile은 image에 계층을 만든다.
---
생성일시: 2022-09-15 01:57

도커는 image를 가볍고 작고 빠르게 만들기 위해 image에 계층을 만들었다.

Dockerfile이 바뀌고 image를 다시 빌드하면,  변경된 계층에 대한 부분만 다시 빌드된다.

``` Dockerfile
FROM centos:7

RUN yum -y update && yum -y install httpd

EXPOSE 80

ADD run-httpd.sh /run-httpd.sh

RUN chmod -v +x /run-httpd.sh

CMD ["/run-httpd.sh"]

```
각 명령어에 대해서 계층이 만들어진다. 위의 파일을 아래와 같이 변경하고 빌드하면,
``` Dockerfile
FROM centos:7

RUN yum -y update && yum -y install httpd

EXPOSE 8080 # 변경된 사항에 대한 계층만 변경되어 빌드된다.

ADD run-httpd.sh /run-httpd.sh

RUN chmod -v +x /run-httpd.sh

CMD ["/run-httpd.sh"]

```

Port를 여는 부분에 관련된 계층만 변경되어 빌드되므로 [[901e-도커는 가볍고 빠르다|굉장히 빠르다]].

## 레퍼런스
---
1. [도커 Docs - Docker Overview](https://docs.docker.com/get-started/overview/)
