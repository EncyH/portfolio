# portfolio
개인 포트폴리오
***
**디자인된 템플릿을 사용하지않은 웹페이지 개발과 학습에 목적을 두고 있습니다.**   
[2020.03.19]   
~~디자인된 템플릿을 사용합니다. 디자인 포기 ㅠㅠ~~   
웹 프론트 디자인과 백엔드 개발 후 디자인 사용 여부 결정   
[2020.04.15]   
[네이버 부스트코스](https://www.edwith.org/boostcourse-ui/joinLectures/20901)의 웹 프로그래밍 강의를 수강하며 진행  
*** 
**html문서 구조**   
> ```
><!DOCTYPE html>
><html lang="ko">
>  <head>
>     <meta charset="UTF-8">
>     <title>HTML</title>
>  </head>
>  <body>
>     <h1>Hello, HTML</h1>
>  </body>
></html>
>```
>- ```<!DOCTYPE html>```   
>: 최상단에 작성하여 문서의 타입을 정의함, 문서의 버전과 타입을 브라우저에 알려주는 선언문   
>- ```<html>```   
>: 문서 타입 선언 후 작성하는 태그, ```<head>와 <body>```의 자식 태그가 있다.   
>- ```<head>```   
>: ```<head>```태그에 위치하는 태그들은 브라우저 화면에 표시되지 않는다. 대신 문서의 기본 정보 설정이나 외부 스타일 시트 파일 및 js 파일을 연결하는 등의 역할을 한다.   
>- ```<meta>```   
>: 태그의 charset 속성은 문자의 인코딩 방식을 지정한다. 브라우저에서 한국어를 지원하기 위해선 "UTF-8" 형식을 지정해야한다.   
>- ```<body>```   
>: 실제 브라우저 화면에 나타나는 내용이 들어간다.   
>**위 코드는 가장 기본적인 문서 구조로, 보통은 이보다 더많은 태그가 들어간다.**   

**시멘틱 마크업**   
>- 시맨틱 마크업하기(의미론적 차이)   
>```
><b>굵은</b> vs <strong>중요한</strong>
><i>기울어진</i> vs <em>강조하는</em>
><u>밑줄친</u> vs <ins>새롭게 추가된</ins>
><s>중간선이 있는</s> vs <del>삭제된</del>
>```   
>: 위 코드의 vs줄의 좌우 코드는 브라우저 상에 동일하게 보이지만 의미론적으로 다르다. 예를 들어 ```<b>```태그는 단순히 텍스트를 굵게 만드는 것이며, ```<strong>```태그는 브라우저가 텍스트의 중요도를 높게 인식한다. 마찬가지로 아래의 다른 태그들 또한 서로다른 의미를 가진다.   

