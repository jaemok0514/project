### servlet이란
웹페이지를 동적으로 생성하는 서버 측 프로그램
즉 클라이언트의 요청에 맞춰 동적인 결과를 만들어주는 자바 웹 프로그램이 기술 (java code안에 html을 포함)

### 특징
- 클라이언트 요청에 동적으로 응답하는 웹 어플리케이션 컴포넌트
- HTML을 사용하여 응답
- JAVA 쓰레드를 이용
- MVC패턴에서는 controller의 역할

### life cycle
- init : 서블릿이 메모리에 로드될 때 한번만 호출
- doGet : get 방식으로 데이터 전송 시 호출
- doPost : post 방식으로 데이터 전송 시 호출
- service : 모든 요청은 service를 통해 메서드로 이동
- destroy : 서블릿에 메모리에서 해제되면 호출

![image](https://github.com/jaemok0514/project/assets/94815900/9a883f78-b348-4993-808f-4fad70efb7bb)


### servlet container란
서블릿을 관리해주는 컨테이너(서블릿의 생성 및 파괴)
대표적인 예로 tomcat이 있다.

![image](https://github.com/jaemok0514/project/assets/94815900/e57cd0d8-6526-4ea5-88d0-eaf59213a2d6)

### servlet container의 역할
- 웹서버와의 통신 지원 : 웹 서버와 소켓을 열어 손쉽게 통신 가능
- 서블릿 생명 주기 관리
- 멀티쓰레드 지원
