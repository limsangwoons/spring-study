## MVC 장점 

<pre>
  프레젠 테이션(화면) 로직과 비즈니스 로직을 분리할 수 있다.
</pre>

## 스프링 MVC의 개념

<pre>
 처음에 디스페처 서블릿이 받음 ->
 hander mapping 한테 보냄 이 hander mapping은 어떤 컨트롤러인지 알아서 그걸 다시 디스페처 서블릿에게 보냄 ->
 그럼 그게 handler adapter를 지나서 컨트롤러에게 보냄 ->
 그럼 컨트롤러가 다시 반대로 view의 정보(view의 이름)를 보냄 ->
 그럼 view 객체를 만들어주는 view resolver에게 view 컨트롤러가 준 view의 정보(view 이름)를 보내고 view를 디스페처 서블릿한테 보냄으로 view를 client에게 보여줌
</pre>
![image](https://github.com/limsangwoons/spring-study/assets/116055397/890453d6-1079-43d3-866c-bf4456d0aa84)

## 프레임워크는?
<pre>
 1.뼈대, 어플리케이션의 아키텍처에 해당하는 골격 코드를 말한다. 
 2.사용하는 이유는 아키텍처와 결합할 비즈니스 로직 개발에만 집중할 수 있기 때문이다. 
 3.프레임워크의 구조
  1) presentation (view)
  2) bussiness (서비스를 구현하는 영역 - 기능 구현의 영역)
  3) persistence  (jpa - presentation 과 bussines를 연결해주는 영역이라고 생각하면 된다.)
 4. POJO(Plain Old Java Object) - model를 만드는 프레임워크라고 생각하세욤.
</pre>

## Spring boot의 장점이란
<pre>
  1) 라이브러리 관리 자동화
  2) 설정의 자동화 (실행에 필요한 환경을 자동 설정해줍니다.)
  3) 라이브러리 버전 자동관리 
  4) 테스트 환경과 내장 톰캣
  5) 독립적으로 실행 가능한 JAR - 짜르~ 
     웹은 원래는 WAR로 하는데 
</pre>
