### 1. spring project 생성 후 pom.xml에서 java version 및 spring verison 수정
java 1.8 및 spring 2.6.6 version으로 수정
![image](https://github.com/jaemok0514/project/assets/94815900/ad7d9fe9-898a-4457-860c-5029e698185e)
> spring project 생성 시 지원하는 version은 java 1.8을 지원하지 않음 -> java를 올려서 설치 후 버전 다운

### 2. src/main/resources/static 아래에 index.html 생성
![image](https://github.com/jaemok0514/project/assets/94815900/2cf03ada-c686-439c-971f-3de56efc2e7e)

### 3. backend application 실행
![image](https://github.com/jaemok0514/project/assets/94815900/37e570c2-319e-4403-974f-7c19baf6e377)
![image](https://github.com/jaemok0514/project/assets/94815900/9f6709fb-b6b2-410b-8f5e-507af35869f8)
> index.html에 입력한 문구 확인 가능

### 4. maven package 실행
$ mvn package -DskipTests
명령어 실행
![image](https://github.com/jaemok0514/project/assets/94815900/e85581d1-71c7-46af-874c-9372e17dc88c)
> target 아래에 test2-0.0.1-SNAPSHOT.jar 파일 생성 확인 <
![image](https://github.com/jaemok0514/project/assets/94815900/994fadd2-0bc0-4202-88db-8790bfd19ee0)

### 5. jar 파일 실행
target 폴더로 이동 후 jar 파일 실행 <br>
$ java -jar test2-0.0.1-SNAPSHOT.jar
![image](https://github.com/jaemok0514/project/assets/94815900/3e1757d7-ad81-47c9-8421-e169bf8f975b)
