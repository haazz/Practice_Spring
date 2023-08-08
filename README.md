# SpringBoot Q&A Site Project

## 서비스 설명
springboot로 구현한 Q&A 사이트 입니다.  
연습을 위해 제작한 사이트이기에 DB는 H2를 사용하였습니다.

## 기술 스택
### Front End
- thymeleaf
- html, css, js
- bootStrap

### Back End
- SpringBoot
- JPA

### DB
- H2

## View Page

### 메인
- 간단한 Q&A 사이트이기에 메인 페이지에 바로 질문 리스트가 보이게 만들었습니다.
- 이 페이지에서는 글 상세페이지로 가기, 로그인, 검색, 글 작성을 진행할 수 있습니다.
<img width="832" alt="스크린샷 2023-08-08 오후 4 36 37" src="https://github.com/haazz/Practice_Spring/assets/127824457/5bb9cb15-c24d-4325-a049-00f0b9b3ce1f">

### 회원가입
- 메뉴바에 있는 회원가입 버튼을 통해 회원가입을 진행할 수 있습니다.
- 만약 중복된 ID로 회원가입을 시도하면 다음과 같은 경고문이 나오게 됩니다.
<img width="788" alt="스크린샷 2023-08-08 오후 4 17 39" src="https://github.com/haazz/Practice_Spring/assets/127824457/ad2954e6-16d3-4e2a-a6ed-9d2cb2006763">
<img width="832" alt="스크린샷 2023-08-08 오후 4 49 29" src="https://github.com/haazz/Practice_Spring/assets/127824457/57968996-dead-474d-9e0d-7aaf331cbe77">

### 로그인
- 메뉴바에 있는 로그인 버튼을 통해 로그인을 진행할 수 있습니다.
- 아이디와 비밀번호가 틀리면 경고문이 나오고 로그인에 실패합니다.
- 만약 로그인에 성공하였다면 기존 메뉴바에 있던 로그인, 회원가입 버튼이 아닌 로그아웃 버튼이 나오게 됩니다.
<img width="832" alt="스크린샷 2023-08-08 오후 4 15 15" src="https://github.com/haazz/Practice_Spring/assets/127824457/2a8a9c82-e44c-48e8-931c-b94b6912f565">

### 글 작성
- 글 작성은 로그인이 된 상태에서만 가능합니다.
- 로그인이 되어있지 않은 상태에서 글 작성을 시도하면 로그인 페이지로 이동합니다.
- 제목 혹은 내용을 작성하지 않으면 작성하라는 경고문이 나오게 됩니다.
- 작성자와 생성날짜는 자동으로 저장되게 됩니다.
<img width="832" alt="스크린샷 2023-08-08 오후 4 15 03" src="https://github.com/haazz/Practice_Spring/assets/127824457/b9561c98-861a-4821-8588-22faf81167e4">

### 글 상세 페이지
- 글 상세 페이지에서는 글 추천, 수정, 삭제, 댓글 작성, 수정, 삭제, 추천 기능을 사용할 수 있습니다.
- 글과 댓글의 수정, 삭제 버튼은 현재 로그인된 사용자와 작성자가 같을 때만 보이게 됩니다.
- 추천 기능은 한 번 누르면 추천 수가 올라가고 같은 사용자로 한 번 더 누르면 추천이 취소 됩니다.
<img width="832" alt="스크린샷 2023-08-08 오후 4 36 40" src="https://github.com/haazz/Practice_Spring/assets/127824457/e9242a99-b363-4f2f-a88d-7ceed887105d">

### 검색
- 검색창에 검색어를 넣으면 글 제목 혹은 내용에 검색어가 포함된 모든 글을 보여줍니다.
<img width="832" alt="스크린샷 2023-08-08 오후 4 45 05" src="https://github.com/haazz/Practice_Spring/assets/127824457/7457577d-583d-4d41-830d-2b07dc24e8fe">



## 참고 사이트
점프 투 스프링부트(https://wikidocs.net/book/7601)
