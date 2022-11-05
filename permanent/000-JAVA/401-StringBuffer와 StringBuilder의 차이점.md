Created at: 2022-10-30 18:08

#StringBuffer #StringBuilder #JAVA #OOP 

StringBuffer는 동기화 키워드를 지원한다. 그러므로 멀티쓰레드 환경에서 안전하다.

String도 불변성을 가지기 때문에 멀티쓰레드 환경에서 안전하다.

StringBuilder는 동기화를 지원하지 않는다. 그러므로 멀티쓰레드 환경에서 객체가 망가질 수 있으나, 단일 쓰레드에서의 성능은 StringBuffer보다 뛰어나다.

## Reference
---
1. [String, StringBuffer, StringBuilder 차이 및 장단점](https://ifuwanna.tistory.com/221)
<div style="text-align: right"> 202210301808 </div>