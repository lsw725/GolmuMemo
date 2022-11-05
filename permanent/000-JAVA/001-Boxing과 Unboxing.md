Created at: 2022-10-28 04:09

#JAVA #OOP 

Boxing은 Primitive 자료형에서 Wrapper 클래스로의 변환을 의미한다.

Unboxing은 Wrapper클래스에서 Primitive 자료형으로의 변환을 의미한다.

자바에서는 모든 경우는 아니지만 대부분의 경우는 자동으로 boxing / unboxing을 해준다.
```java
int i = 1;
Integer integer = i;    // int -> Integer (Auto boxing)
int i2 = integer;    // Integer -> int (Auto unboxing)

```

## Reference
---
1. [Integer 객체와 int의 차이점](https://includestdio.tistory.com/1)
<div style="text-align: right"> 202210280409 </div>