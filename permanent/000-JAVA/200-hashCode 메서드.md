Created at: 2022-10-27 20:25

재정의 하지 않으면 메모리 주솟값을 사용해서 해시값을 만든다. 재정의를 한다면 특정 값을 기준으로 하는 해시 코드를 얻을 수 있다.
```java
	@Override
    public int hashCode() {
        return Objects.hash(x, y);
    }
```

## Reference
---
1. [VO(Value Object)란 무엇일까?](https://tecoble.techcourse.co.kr/post/2020-06-11-value-object/)
<div style="text-align: right"> 202210272025 </div>