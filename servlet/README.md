# servlet , spring MVC
## ๐ฉ๐ปโ๐ป ์๋ธ๋ฆฟ
<img width="425" alt="image" src="https://user-images.githubusercontent.com/80495141/159847435-90a4360a-de36-41f4-b1a0-36ac13d1b6bd.png">

- ์๋ธ๋ฆฟ - ํ๋ก์ ํธ ์์ฑ
- ์๋ธ๋ฆฟ - Hello ์๋ธ๋ฆฟ
- ์๋ธ๋ฆฟ - HttpServletRequest - ๊ฐ์
- ์๋ธ๋ฆฟ - HttpServletRequest - ๊ธฐ๋ณธ ์ฌ์ฉ๋ฒ
- ์๋ธ๋ฆฟ - HTTP ์์ฒญ ๋ฐ์ดํฐ - ๊ฐ์
  - http://localhost:8080/hello?username=hi
- ์๋ธ๋ฆฟ - HTTP ์์ฒญ ๋ฐ์ดํฐ - GET ์ฟผ๋ฆฌ ํ๋ผ๋ฏธํฐ
  - http://localhost:8080/request-param?username=hello&age=20
  - http://localhost:8080/request-param?username=hello&username=kim&age=20
- ์๋ธ๋ฆฟ - HTTP ์์ฒญ ๋ฐ์ดํฐ - POST HTML Form
  - http://localhost:8080/basic/hello-form.html
  - content-type: application/x-www-form-urlencoded
- ์๋ธ๋ฆฟ - HTTP ์์ฒญ ๋ฐ์ดํฐ - API ๋ฉ์์ง ๋ฐ๋ - ๋จ์ ํ์คํธ 
  - POST http://localhost:8080/request-body-string
  - content-type: text/plain
- ์๋ธ๋ฆฟ - HTTP ์์ฒญ ๋ฐ์ดํฐ - API ๋ฉ์์ง ๋ฐ๋ - JSON
  - http://localhost:8080/request-body-json
  - content-type: application/json
  - message body: {"username": "hello", "age": 20}
- ์๋ธ๋ฆฟ - HttpServletResponse - ๊ธฐ๋ณธ ์ฌ์ฉ๋ฒ
  - http://localhost:8080/response-header
- ์๋ธ๋ฆฟ - HTTP ์๋ต ๋ฐ์ดํฐ - ๋จ์ ํ์คํธ, HTML
  - http://localhost:8080/response-html
- ์๋ธ๋ฆฟ - HTTP ์๋ต ๋ฐ์ดํฐ - API JSON
  - http://localhost:8080/response-json
- ์๋ธ๋ฆฟ - ์ ๋ฆฌ

&nbsp;

## ๐ฉ๐ปโ๐ป ์๋ธ๋ฆฟ, JSP, MVC
<img width="572" alt="image" src="https://user-images.githubusercontent.com/80495141/159847678-5fdeb328-e884-4fe4-87da-b3907f5f8fdc.png">

- ํ์ ๊ด๋ฆฌ ์น ์ ํ๋ฆฌ์ผ์ด์ ์๊ตฌ์ฌํญ
- ์๋ธ๋ฆฟ์ผ๋ก ํ์ ๊ด๋ฆฌ ์น ์ ํ๋ฆฌ์ผ์ด์ ๋ง๋ค๊ธฐ
- JSP๋ก ํ์ ๊ด๋ฆฌ ์น ์ ํ๋ฆฌ์ผ์ด์ ๋ง๋ค๊ธฐ
- MVC ํจํด - ๊ฐ์
- MVC ํจํด - ์ ์ฉ 
- ํ๊ณ
- ์ ๋ฆฌ

&nbsp;

## ๐ฉ๐ปโ๐ป ํ๋ก ํธ ์ปจํธ๋กค๋ฌ
<img width="257" alt="image" src="https://user-images.githubusercontent.com/80495141/159850204-e93b0569-54c7-424f-825a-90227ed8a038.png">

- ํ๋ก ํธ ์ปจํธ๋กค๋ฌ ํจํด ์๊ฐ 
- ํ๋ก ํธ ์ปจํธ๋กค๋ฌ ๋์ - v1
  - ๊ธฐ์กด ๊ตฌ์กฐ๋ฅผ ์ต๋ํ ์ ์งํ๋ฉด์ ํ๋ก ํธ ์ปจํธ๋กค๋ฌ๋ฅผ ๋์
- View ๋ถ๋ฆฌ - v2
  - ๋จ์ ๋ฐ๋ณต ๋๋ ๋ทฐ ๋ก์ง ๋ถ๋ฆฌ
- Model ์ถ๊ฐ - v3
  - ์๋ธ๋ฆฟ ์ข์์ฑ ์ ๊ฑฐ
  - ๋ทฐ ์ด๋ฆ ์ค๋ณต ์ ๊ฑฐ
- ๋จ์ํ๊ณ  ์ค์ฉ์ ์ธ ์ปจํธ๋กค๋ฌ - v4
  - v3์ ๊ฑฐ์ ๋น์ท
  - ๊ตฌํ ์์ฅ์์ ModelView๋ฅผ ์ง์  ์์ฑํด์ ๋ฐํํ์ง ์๋๋ก ํธ๋ฆฌํ ์ธํฐํ์ด์ค ์ ๊ณต
- ์ ์ฐํ ์ปจํธ๋กค๋ฌ1 - v5
- ์ ์ฐํ ์ปจํธ๋กค๋ฌ2 - v5
  - ์ด๋ํฐ ๋์
  - ์ด๋ํฐ๋ฅผ ์ถ๊ฐํด์ ํ๋ ์์ํฌ๋ฅผ ์ ์ฐํ๊ณ  ํ์ฅ์ฑ ์๊ฒ ์ค๊ณ


## ๐ฉ๐ปโ๐ป SpringMVC ๊ตฌ์กฐ

  <img width="835" alt="image" src="https://user-images.githubusercontent.com/80495141/159858977-c9e8ac33-8952-4ac4-896a-f530451f4a95.png">
- ๋์ ์์

1. ํธ๋ค๋ฌ ์กฐํ: ํธ๋ค๋ฌ ๋งคํ์ ํตํด ์์ฒญ URL์ ๋งคํ๋ ํธ๋ค๋ฌ(์ปจํธ๋กค๋ฌ)๋ฅผ ์กฐํํ๋ค.
2. ํธ๋ค๋ฌ ์ด๋ํฐ ์กฐํ: ํธ๋ค๋ฌ๋ฅผ ์คํํ  ์ ์๋ ํธ๋ค๋ฌ ์ด๋ํฐ๋ฅผ ์กฐํํ๋ค.
3. ํธ๋ค๋ฌ ์ด๋ํฐ ์คํ: ํธ๋ค๋ฌ ์ด๋ํฐ๋ฅผ ์คํํ๋ค.
4. ํธ๋ค๋ฌ ์คํ: ํธ๋ค๋ฌ ์ด๋ํฐ๊ฐ ์ค์  ํธ๋ค๋ฌ๋ฅผ ์คํํ๋ค.
5. ModelAndView ๋ฐํ: ํธ๋ค๋ฌ ์ด๋ํฐ๋ ํธ๋ค๋ฌ๊ฐ ๋ฐํํ๋ ์ ๋ณด๋ฅผ ModelAndView๋ก ๋ณํํด์ ๋ฐํํ๋ค.
6. viewResolver ํธ์ถ: ๋ทฐ ๋ฆฌ์กธ๋ฒ๋ฅผ ์ฐพ๊ณ  ์คํํ๋ค.
   - JSP์ ๊ฒฝ์ฐ: InternalResourceViewResolver ๊ฐ ์๋ ๋ฑ๋ก๋๊ณ , ์ฌ์ฉ๋๋ค.
7. View ๋ฐํ: ๋ทฐ๋ฆฌ์กธ๋ฒ๋ ๋ทฐ์๋ผ๋ฆฌ์ด๋ฆ์ ๋ฌผ๋ฆฌ์ด๋ฆ์ผ๋ก ๋ฐ๊พธ๊ณ ,๋ ๋๋ง ์ญํ ์ ๋ด๋นํ๋ ๋ทฐ๊ฐ์ฒด๋ฅผ ๋ฐํํ๋ค.
   - JSP์ ๊ฒฝ์ฐ InternalResourceView(JstlView) ๋ฅผ ๋ฐํํ๋๋ฐ, ๋ด๋ถ์ forward() ๋ก์ง์ด ์๋ค.
8. ๋ทฐ๋ ๋๋ง: ๋ทฐ๋ฅผ ํตํด์ ๋ทฐ๋ฅผ ๋ ๋๋งํ๋ค.


- http://localhost:8080/springmvc/old-controller
- http://localhost:8080/springmvc/request-handler

  <img width="195" alt="image" src="https://user-images.githubusercontent.com/80495141/159873372-abd63325-82a8-46bf-854d-cbcaa2ffd9ac.png">
