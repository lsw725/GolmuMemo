Created at: 2022-10-27 19:57

#VO #Entity #OOP #DDD #JAVA 

Entity는 기본 키로 식별 값을 갖으나 VO는 기본 키 없이 속성 값 자체로 각 개체를 구분한다.

대표적인 차이는 아래와 같다.
1. [[109-VO는 equals 메서드와 hash code 메서드를 재정의 해야 한다.|VO는 equals 메서드와 hash code 메서드를 재정의 해야 한다.]]
2. [[100-VO는 수정자(Setter)가 없는 불변 객체여야한다.|VO는 수정자(Setter)가 없는 불변 객체여야한다.]]

## Reference
---
1. [VO(Value Object)란 무엇일까?](https://tecoble.techcourse.co.kr/post/2020-06-11-value-object/)
<div style="text-align: right"> 202210271957 </div>