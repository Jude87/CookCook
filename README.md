# CookCook
<div align="center">
  <img src="https://user-images.githubusercontent.com/107044598/214289986-de6d2f11-96ca-4d04-a85c-a9c4da7b52f9.png">
</div>

<br>
매일매일 다른 오늘의 레시피를 추천하고, 직관적으로 레시피를 검색하며, <br>
이용자들이 등록한 레시피를 서로 공유할 수 있는 웹사이트를 제작
<hr>

- 개발 목표 : 오늘의 레시피 추천 웹 사이트

- 수행기간 : 2022년 10월 07일 ~ 2022년 11월 16일 (약 6주)

- 개발 인원 : 6명

- 기여도 : 20%

# 팀 전체 구현 기능

  + 로그인, 회원가입, 아이디 저장
  + 마이페이지 / 회원정보 수정, 삭제
  + 자유게시판 글 등록, 수정 삭제, 댓글 등록, 삭제
  + 레시피 게시판 글 등록, 수정, 삭제
  + <b>Q&A게시판 글 등록, 수정, 삭제 / 댓글 등록, 수정, 삭제</b> 
  + 공지사항 게시판
  + 레시피 검색, 레시피 등록
  + 관리자 게시판 / 회원정보관리, 전체 게시판 글 등록, 수정, 삭제
  + 관리자 게시판 / 재료 및 정량 데이터 관리

<hr>

# 개발 환경

  + OS : Window 10
  + Development Tool : Eclipse, Visual Studio Code
  + DBMS : Oracle DB-SQLDeveloper
  + Server : Apache Tomcat v8.5
  + Language : Java 1.8, JavaScript5, HTML5, CSS3
  + Application Tool : JSP 3.2
  + Design Tool : BootStrap 4.6.1
  + Library : jQuery 3.4.1
ㅇ
- ER Diagram

![CookCook_ER_Diagram](https://user-images.githubusercontent.com/107044598/214287109-eb05c3ed-2308-42c1-8f7a-f91e6a654ff9.png)

<hr>

# 담당 역할 및 기능 설명

- 프로젝트 주제 선정 및 미팅 주관, 유스케이스 다이어그램 작성

<div align="center">
  <img src="https://user-images.githubusercontent.com/107044598/214303946-41210899-c993-42f9-9e0b-e86ad8a8f06b.png">
</div>
<br>

- Q&A 게시판 리스트 페이지
  + 게시글 리스트 페이징 처리
  + 글 등록, 수정, 삭제

<div align="center">
  <img src="https://user-images.githubusercontent.com/107044598/214463815-1d3b300e-1642-4a42-8529-1a6764d82859.png">
</div>
<br>

- Q&A 게시판 상세보기 페이지
  + 로그인 유저 댓글 등록, 수정, 삭제

<div align="center">
  <img src="https://user-images.githubusercontent.com/107044598/214464024-852ed112-4c58-47d8-b6d3-c8679357eb56.jpg">
  <img src="https://user-images.githubusercontent.com/107044598/214464199-2d2b0f57-f3c6-499a-b0d8-8a4c9b16459d.jpg">
</div>
<br>

- 이달의 레시피 게시판
  + 사용자가 접속한 해당 월의 좋아요가 가장 많은 순으로 1~3위 표시 기능

<div align="center">
  <img src="https://user-images.githubusercontent.com/107044598/214464566-88600d94-128e-4993-9fdb-cb6d48cae17d.png">
</div>
<br>
