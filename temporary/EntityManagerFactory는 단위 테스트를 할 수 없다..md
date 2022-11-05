# EntityManagerFactory는 단위 테스트를 할 수 없다.
---
Created at: 2022-10-15 04:23

EntityManagerFactory는 PersistanceUnit의 설정이 필요하다. 해당 설정은 Spring boot의 경우 application.properties에 지정되어 있다.

xml이였다면 이름을 지정해주고 그 값을 인자로 넣으면 됐지만 properties Spring boot가 관리하므로 @PersistanceUnit 으로 DI해준다.

따라서 @SpringBootTest가 있는 통합 테스트에서만 EntityManagerFactory를 사용할 수 있다.

## Reference
---
1. [EntityManager를 사용하는 Repository의 단위 테스트는 어떻게 수행하나요?](https://www.inflearn.com/questions/46858)
