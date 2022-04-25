# html introduction

1. <body>
   <hnumber>에 따른 폰트 변화(헤딩)

<div> to group, no visualization, apply same styles
  attribute: <div id = "intro">

<p>문단의 글 표현, <span>으로 특정 구간 나누기

<em>, <strong> : 이탈릭, 볼드체

다음줄 <br />(스스로 열고 닫음.)

<ul>, <ol> : 점으로 나누기 , 숫자로 나누기
  <li>로 항목 묶어준다.

<img src = "link" alt = "description" /> 
  //스스로 열고 닫음
  descrption은 image crawling 및 시각장애를 위한

<video src = "name" width = "320" height = "240" controls>
  Video not supported //안나올 때 나옴
</video>
  controls는 비디오 기본 조작 탑재

2. <head>
   <title> : 탭에 표시되는

<a href = "link" target = "_blank"></a> : 하이퍼링크 텍스쳐
target -> 새 탭상에서 열기
href = #name ->div id 상 표시해뒀던 name로 이동.

-같은 폴더 안에 있을 때
<a href = ./contact.html">Contact</a> : ./은 현재 폴더 위치를 뜻한다.
<a> 사이에 글자 대신 img 형식 집어넣기 가능

<!--Coments-->

3. <table>
   <tr> -> 행
   <th scope = "col"> 테이블 헤딩
   <td> -> 데이터

<td colspan = "2">col로 해당 숫자만큼 차지 //rowspan 같은 개념

<tbody> , <thead>, <tfoot>

4.

<form action = "/example.html" method = "POST>
  <label for  = "meal">What do you want to eat</label>
  <input type = "text" name = "food" id = "meal">
  </form>

//label 태그의 for 값과 input의 id 값을 일치시켜 쓴다.

<input type = "password"> //패스워드 입력창 점으로 표시

   <input id = "amount" name = "amount" type = "number" step = "1">
   // 안에 순서는 중요하지 않은 모양이다.

   <section class = "">

   <input type = "range" max min step>

  <input checklist>
  input 안에 value 값은 초기값을 의미한다.

  <input type = "radio">
  <label id = "">

<select id = "" name = "">과 <datalist id = ""> 차이
◎ select 안에 option value는 안보이는데 반해 datalist option value는 보인다
◎ datalist는 입력 가능한데, 만약 항목에 없으면 그거대로 보내진다.

<input type = "submit" value = "Send">

<textarea id = "extra" name rows cols></textarea>
