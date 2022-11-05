Created at: 2022-10-27 20:21

#VO #OOP #DDD #JAVA 

타입도 같고 내부의 속성값도 같은 두 객체는 동일한 객체로 취급해야 한다.

그러나 같은 속성의 객체를 생성해도 다른 메모리 주소를 갖기 때문에 다른 객체로 취급한다.

속성 값이 같을 때 같은 객체로 취급하도록 [[200-equals 메서드|equals 메서드]]를 재정의 해야하며, 속성 값을 이용하여 같은 해시 값을 갖도록 [[200-hashCode 메서드|hashCode 메서드]]를 재정의 해야한다.

## Reference
---
1. [VO(Value Object)란 무엇일까?](https://tecoble.techcourse.co.kr/post/2020-06-11-value-object/)
<div style="text-align: right"> 202210272021 </div>