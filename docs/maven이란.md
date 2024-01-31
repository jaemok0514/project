# maven
프로젝트의 의존성 관리, 라이브러리 관리, 라이프 사이클 관리 기능 등을 제공하는 프로젝트 관리 도구

### lifecycle
- clean : 빌드 시 생성된 파일을 삭제하는 단계
- validate : 프로젝트가 정상적인지 확인하는 단계
- compile : 소스코드를 컴파일하는 단계
- test : 유닛 테스트를 진행하는 단계 
- package : 컴파일된 소스와 리소스들을 jar or war 등 파일 형태로 만드는 단계
- verify : 테스트 결과에 대한 검사를 실행하여 적합한지 확인하는 단계
- install : 패키지를 로컬에 설치하는 단계
- site : 프로젝트 문서와 사이트를 작성, 생성하는 단계
- deploy : 만들어진 패키지를 원격 저장소에 release하는 단계

### 관련 파일 
- pom.xml : project object model 프로젝트 최상위에 존재하는 파일, maven의 정보를 담고있는 파일
- setting.xml : maven setting 정보를 담고있는 파일 프로젝트에 존재하지 않음
