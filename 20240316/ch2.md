## MVC 장점 

<pre>
  프레젠 테이션(화면) 로직과 비즈니스 로직을 분리할 수 있다.
</pre>

## 스프링 MVC의 개념

<pre>
 처음에 디스페처 서블릿이 받음 ->
 hander mapping 한테 보냄 이 hander mapping은 어떤 컨트롤러인지 알아서 그걸 다시 디스페처 서블릿에게 보냄 ->
 그럼 그게 handler adapter를 지나서 컨트롤러에게 보냄 ->
 그럼 컨트롤러가 다시 반대로 view의 정보를 보냄 ->
 그럼 view 객체를 만들어주는 view resolver에게 view 컨트롤러가 준 view의 정보를 보내고 view를 디스페처 서블릿한테 보냄으로 view를 client에게 보여줌
</pre>
