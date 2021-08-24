# GSITM-Web
### 개인 프로젝트 목표

+ 보호수를 관리하는 페이지를 구현하는 것을 목표
+ DB에 있는 데이터 활용(임의의 데이터)




### 기능

- Admin과 (일반, 관리자) 사용자로 나눠서 구현

  - 사용자

    - 보호수의 종류, 특징을 볼 수 있음

    - 사용자는 일반 사용자와 수목 전문가로 나눔

    - 사용자가 키우는 보호수에 (임의로 생성한) 센서 데이터 볼 수 있음

    - 관리자에게 질문할 수 있는 게시판

      ​

  - 관리자

    - 사용자 추가 or 삭제
    - 나무 종류,특징 수정
    - 사용자 정보, 사용자 보호수 종류, 센서 데이터  
    - 사용자에게 답변할 수 있는 게시판 

### 활용기술

+ html
+ css
+ php
+ javascript



### 1일차

+ admin 사용자 관리 구분 완료(일반, 전문가)
+ admin 사용자 수정페이지 완료
+ admin 사용자 상세보기 완료

##=======================================

### 팀 프로젝트 목표

- 도서관 자리 현황을 알려주는 페이지 구현
- 도서관 자리 예약 및 유저간 쪽지 기능 구현



### 기능

- 사용자 페이지 구현

  - 회원가입 페이지

    - 이름, 아이디, 비밀번호, 주소, 핸드폰번호, 이메일로 회원가입

      ​

  - 로그인 페이지

    - Local_storage에 저장된 아이디와 비밀번호 대조 후 로그인

  ​

  - 아이디/비밀번호 찾기 페이지

    - 기존 입력했었던 이름과 주소, 핸드폰 번호, 이메일 대조 후 기존 아이디 알림

    - 아이디, 이름, 이메일 대조 후 새로운 비밀번호 생성

      ​

  - 메인 페이지

    - Local_storage에 저장된 아이디와 비밀번호 대조 후 로그인
    - 기존 예약좌석 및 사용좌석 표출 
    - 예약하기(button), 쪽지(popup), 쪽지함(button), 로그아웃(button), 예약현황(popup) 구현

    ​

  - 예약하기

    - 지정 좌석 클릭 후 원하는 날짜 선택 후 시간 선택

    - 예약완료(popup)

      ​

  - 쪽지

    - 지정 좌석 클릭 후 사용자 ID에게 쪽지 보내기 클릭
    - 발신자 수신자 구분
    - 내용과 시간 표기

  ​

  - 쪽지함

    - 쪽지를 주고 받았던 사용자 ID, 날짜, 간략한 내용 표기

      ​

  - 로그아웃

    - 로그아웃 클릭시 기존에 있던 쿠키값 제거 후 로그인 페이지로 이동

    ​

  - 예약 현황

    - 메인 페이지에서 테이블 형식으로 좌석 현황 표출

      ​

### 활용기술

- html
- css
- javascript
- git_localstorage

##===========================================================================================
### 개인 프로젝트

### 2일차

- post방식 에러 해결 ( id를 post로 넘기기에서 name을 post로 넘기니 error 해결)
- 보호수 항목 쿼리 해결
- 관리자 DB 정정 ( 70% )

##=======================================

### 팀 프로젝트

### 2일차

- 로그인 페이지, 아이디/비밀번호 찾기 페이지 UI설계
- login 페이지 구현
