# tomcat
![image](https://github.com/jaemok0514/project/assets/94815900/c01d1ec7-48c0-4be6-8b16-beef1d904161)

### tomcat이란
apache 제단의 어플리케이션 서버로 자바 servlet을 실행하고 jsp가 포함된 웹페이지를 만들어줌.

### tomcat의 내부 구조
![image](https://github.com/jaemok0514/project/assets/94815900/0fecb8b2-4f9e-40b3-aee7-bad68855d828)
1. 클라이언트가 브라우저에 url 요청
2. tomcat 내부에서 요청을 받아 connector를 통해 알맞는 요청을 연결
3. Engine에서 알맞는 Host로 접근
4. 해당 호스트의 Context(application)로 접근
5. 해당 context의 url에 알맞는 서블릿에 접근
6. 해당 서블릿이 실행되고 결과를 전송

### 폴더구조
![image](https://github.com/jaemok0514/project/assets/94815900/7a53426b-d10b-4906-b61c-33ba5bd264f8)

- bin : 톰캣 실행 및 종료 스크립트 파일이 있는 폴더
- conf : 서버 설정 파일 폴더(server.xml)
- lib : 톰캣 구성 라이브러리 폴더
- logs : 로그 저장 폴더
- temp : 임시 저장 폴더
- webapps : 웹 어플리케이션 폴더
- work : java파일과 class 파일이 있는 폴더

# Servlet
서블릿이란 클라이언트의 요청을 처리하고, 그 결과를 반환하는 Servlet 클래스의 구현 규칙을 지킨 자바 웹 프로그래밍 기술

mvc 패턴의 controller에 해
