# hello-world
Spring Boot를 이용하여 웹 상에 'Hello world'를 출력하는 프로그램

## 서버 실행 방법
HelloApplication class를 실행시키면, 내부 Tomcat 서버가 작동합니다.
그러면 localhost:8080에 접속할 수 있습니다. 8080은 default port number입니다.

## API 실행 방법
API는 HelloController class에 구현하였습니다.
localhost:8080/hello로 request가 들어오면 HelloController는 request에 대한 response로 "Hello world"라는 텍스트를 반환하도록 하였습니다.
해당 API는 HelloApplication class를 실행하면 함께 실행됩니다.
<br/>

![image](https://user-images.githubusercontent.com/92534037/208239528-f8d4f231-21f7-403e-9fdd-3d3d6a6f8498.png)
