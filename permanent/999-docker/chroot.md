# chroot
---
생성일시: 2022-09-16 06:24

컨테이너 즉, 격리된 프로세스를 생성하기 위한 방법 중 가장 오래되고 기본이 되는 것은 프로세스가 실행되는 root를 변경하는 것이다.

chroot는 프로세스가 실행되는 root를 변경시켜 해당 프로세스를 실행시키는 시스템 콜이다.

사용법은 아래와 같다.
```shell
chroot [OPTION] NEWROOT [COMMAND [ARG]...]
```

root로 사용할 디렉토리를 지정하고 그 뒤에 해당 root를 기반으로 실행할 명령어를 입력하는 방식이다.

```shell
chroot /home/jun/new_root /bin/bash
```
⚠️ 위의 명령어는 실행되지 않을 것이다. ``/bin/bash``프로그램에 대한 의존성이 있기 때문에 의존성을 확보해주어야한다.

## 레퍼런스
---
1. [컨테이너 기초 - chroot를 사용한 프로세스의 루트 디렉터리 격리](https://www.44bits.io/ko/post/change-root-directory-by-using-chroot)
