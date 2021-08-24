### 2일차 공부
  + 프로젝트 
    + UI 구현부터 확실하게 해야함 꼭!!!!!
    + 변수명은 명확하고 정확히 기술
    + 프로젝트간 간단한 기능도 정확히 구현
    + php POST, GET 방식으로 넘길 때 name으로 해야할 것 ( post방식을 id를 넘겼을 때 오류 --> name을 넘겼더니 오류 해결)
    + 클래스 이름 구별 ( 식별 가능해야함)
    + js처리할 때 복잡하지 않고 일회용이라면 html 문서 안에 작성 가능(복잡하고 반복적으로 사용할 때는 따로 js파일 생성)
    + localstorage는 유효기간이 없고 문자열만 받을 수 있음
    + localstorage.setItem("key","value")으로 저장, localstorage.getItem("key")로 꺼내옴 꺼내 올때는 "value"값이 나옴

  + query
    + group by는 그룹화 하는 것임 예) A~Z라는 학교가 운동시합을 한다면 A학교의 100명의 학생은 A학교라는 공통점, B라는 학교의 120명은 B라는 학교의 공통점을 갖고 있음.
      "공통딘 기준을 가지고 묶어주는 것"
    + group by는 그룹 함수와 같이 사용해야함 ex) count, sum
    + 외부 조인은 합집함, 내부 조인은 교집합
    + 조인 함수는 뒤에 on이라는 조건을 달 수 있음
    + NVL("null을 없애고 싶은 컬럼명", Null을 바꾸고 싶은 값)
  
  + javascript(js)
      + js에서 document는 웹 페이지 그 자체
      + html 요소에 접근하고자 할 때는 document 객체로 시작해야함
      + document(요소 선택, 요소 생성, 이벤트 핸들러 추가, 객체의 선택) 메서드 가능
      + document.getElementsByTagName(태그이름) :  해당 태그 이름의 요소를 모두 선택함
      + document.getElementById(아이디) : 해당 아이디의 요소를 선택함
      + document.getElementsByClassName(클래스이름) : 해당 클래스에 속한 요소를 모두 선택함
      + document.getElementsByName(name속성값)	: 해당 name 속성값을 가지는 요소를 모두 선택함
      + document.querySelectorAll(선택자) :	해당 선택자로 선택되는 요소를 모두 선택함


   
  + 해야할 것
    + 팀 프로젝트 ID찾기, PW찾기 구현 완료
    + 개인 프로젝트 "보호수 항목 조회" 완료
    + 사용자 DB 재정의




    
