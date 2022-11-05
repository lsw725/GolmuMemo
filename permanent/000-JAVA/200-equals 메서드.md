Created at: 2022-10-27 21:31

#VO #OOP #DDD #JAVA 

equals메서드를 재정의 함으로써 두 객체의 [[200-동일성과 동등성의 차이|동일성]]을 비교 할 수 있다. 

```java
	@Override
    public boolean equals(final Object o) {
        if (this == o) return true;
        if (o == null || getClass() != o.getClass()) return false;
        final Point point = (Point) o;
        return x == point.x &&
                y == point.y;
    }
```

## Reference
---
1. [VO(Value Object)란 무엇일까?](https://tecoble.techcourse.co.kr/post/2020-06-11-value-object/)
<div style="text-align: right"> 202210272131 </div>