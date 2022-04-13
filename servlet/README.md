# servlet , spring MVC
## 👩🏻‍💻 서블릿
<img width="425" alt="image" src="https://user-images.githubusercontent.com/80495141/159847435-90a4360a-de36-41f4-b1a0-36ac13d1b6bd.png">

- 서블릿 - 프로젝트 생성
- 서블릿 - Hello 서블릿
- 서블릿 - HttpServletRequest - 개요
- 서블릿 - HttpServletRequest - 기본 사용법
- 서블릿 - HTTP 요청 데이터 - 개요
  - http://localhost:8080/hello?username=hi
- 서블릿 - HTTP 요청 데이터 - GET 쿼리 파라미터
  - http://localhost:8080/request-param?username=hello&age=20
  - http://localhost:8080/request-param?username=hello&username=kim&age=20
- 서블릿 - HTTP 요청 데이터 - POST HTML Form
  - http://localhost:8080/basic/hello-form.html
  - content-type: application/x-www-form-urlencoded
- 서블릿 - HTTP 요청 데이터 - API 메시지 바디 - 단순 텍스트 
  - POST http://localhost:8080/request-body-string
  - content-type: text/plain
- 서블릿 - HTTP 요청 데이터 - API 메시지 바디 - JSON
  - http://localhost:8080/request-body-json
  - content-type: application/json
  - message body: {"username": "hello", "age": 20}
- 서블릿 - HttpServletResponse - 기본 사용법
  - http://localhost:8080/response-header
- 서블릿 - HTTP 응답 데이터 - 단순 텍스트, HTML
  - http://localhost:8080/response-html
- 서블릿 - HTTP 응답 데이터 - API JSON
  - http://localhost:8080/response-json
- 서블릿 - 정리

&nbsp;

## 👩🏻‍💻 서블릿, JSP, MVC
<img width="572" alt="image" src="https://user-images.githubusercontent.com/80495141/159847678-5fdeb328-e884-4fe4-87da-b3907f5f8fdc.png">

- 회원 관리 웹 애플리케이션 요구사항
- 서블릿으로 회원 관리 웹 애플리케이션 만들기
- JSP로 회원 관리 웹 애플리케이션 만들기
- MVC 패턴 - 개요
- MVC 패턴 - 적용 
- 한계
- 정리

&nbsp;

## 👩🏻‍💻 프론트 컨트롤러
<img width="257" alt="image" src="https://user-images.githubusercontent.com/80495141/159850204-e93b0569-54c7-424f-825a-90227ed8a038.png">

- 프론트 컨트롤러 패턴 소개 
- 프론트 컨트롤러 도입 - v1
  - 기존 구조를 최대한 유지하면서 프론트 컨트롤러를 도입
- View 분리 - v2
  - 단순 반복 되는 뷰 로직 분리
- Model 추가 - v3
  - 서블릿 종속성 제거
  - 뷰 이름 중복 제거
- 단순하고 실용적인 컨트롤러 - v4
  - v3와 거의 비슷
  - 구현 입장에서 ModelView를 직접 생성해서 반환하지 않도록 편리한 인터페이스 제공
- 유연한 컨트롤러1 - v5
- 유연한 컨트롤러2 - v5
  - 어댑터 도입
  - 어댑터를 추가해서 프레임워크를 유연하고 확장성 있게 설계


## 👩🏻‍💻 SpringMVC 구조

  <img width="835" alt="image" src="https://user-images.githubusercontent.com/80495141/159858977-c9e8ac33-8952-4ac4-896a-f530451f4a95.png">
- 동작 순서

1. 핸들러 조회: 핸들러 매핑을 통해 요청 URL에 매핑된 핸들러(컨트롤러)를 조회한다.
2. 핸들러 어댑터 조회: 핸들러를 실행할 수 있는 핸들러 어댑터를 조회한다.
3. 핸들러 어댑터 실행: 핸들러 어댑터를 실행한다.
4. 핸들러 실행: 핸들러 어댑터가 실제 핸들러를 실행한다.
5. ModelAndView 반환: 핸들러 어댑터는 핸들러가 반환하는 정보를 ModelAndView로 변환해서 반환한다.
6. viewResolver 호출: 뷰 리졸버를 찾고 실행한다.
   - JSP의 경우: InternalResourceViewResolver 가 자동 등록되고, 사용된다.
7. View 반환: 뷰리졸버는 뷰의논리이름을 물리이름으로 바꾸고,렌더링 역할을 담당하는 뷰객체를 반환한다.
   - JSP의 경우 InternalResourceView(JstlView) 를 반환하는데, 내부에 forward() 로직이 있다.
8. 뷰렌더링: 뷰를 통해서 뷰를 렌더링한다.


- http://localhost:8080/springmvc/old-controller
- http://localhost:8080/springmvc/request-handler

  <img width="195" alt="image" src="https://user-images.githubusercontent.com/80495141/159873372-abd63325-82a8-46bf-854d-cbcaa2ffd9ac.png">
