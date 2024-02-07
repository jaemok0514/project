# Spring
### Spring이란
java의 웹 프레임워크, 자바 개발을 편하게 해주는 오픈소스 프레임워크.

### Spring의 특징
- 컨테이너 역할 : 자바 객체의 라이프 사이클을 관리
- DI 지원 : 의존 관계를 설정
- AOP 지원 : 관점 지향 프로그래밍을 지원, 즉 공통된 기능을 재사용하는 기법
- POJO 지원 : 컨테이너에 저장되는 자바 객체는 상속받지 않고 사용 가능 (ex getter, setter)
- 영속성과 관련된 api 지원 : 데이터 베이스 처리를 위해 사용되는 라이브러리를 연동 지원
  
spring aop 예시 : https://devlog-wjdrbs96.tistory.com/398

spring pojo 예시 : https://ittrue.tistory.com/211

### Spring의 구조 및 동작
![image](https://github.com/jaemok0514/project/assets/94815900/d84b1d38-af23-4e47-a260-dcd2266b916d)

### aop란?
![image](https://github.com/jaemok0514/project/assets/94815900/3e232e62-b1d9-4490-9a8b-aeeb1f9d5575)

o2admin 예시
![image](https://github.com/jaemok0514/project/assets/94815900/9b03df15-f6e5-4446-ba64-ed9cc9f79a6b)
![image](https://github.com/jaemok0514/project/assets/94815900/80162681-6cf1-4651-8796-46deec78a905)

@Target과 @Retention은 spring aop 사용할 때 주로 사용하는 annotation
![image](https://github.com/jaemok0514/project/assets/94815900/0806be7f-1f06-48d0-a751-89603462b005)

@Target annotation은 해당 annotation이 위치할 곳을 결정 (ex ElementType.PARAMETER의 경우 메소드의 파라미터로 선언된 객체에서만 사용 등)

@Retention은 해당 annotation이 어느 시점까지 유지할 지 결정 (ex CLASS, RUNTIME, SOURCE)

@Documented는 javadoc 문서 생성시 현재 어노테이션 설명추가

### IoC란?
