# 📚 3월 도서관 (2nd Team Project) - Spring 전환

국비지원 훈련과정 두번째 팀프로젝트 스프링으로 전환한 소스코드 입니다.

둘 이상의 사용자를 가정하고 각 환경에 맞는 통합 웹 환경, 이용 권한이 구분되는 케이스 라는 조건에 만족하는
가상의 도서관 & 도서 통합관리 시스템을 구현하였습니다.
<br><br>

## 🔖 목차
[1. 프로젝트 개요](#-1.-프로젝트-개요)
   - [개발 기간](#-개발-기간)
   - [사용 기술 및 개발 환경](#-사용-기술-및-개발-환경)
   - [팀원 소개](#-팀원-소개)   

[2. 프로그램 구조](#-2.-프로그램-구조)
   - [ER Diagram](#-ER-Diagram)
   - [View](#-View)
   - [Usecase Diagram](#-Usecase-Diagram)
   - [Flow Chart](#-Flow-Chart)

[3. 페이지 기능 안내](#-3.-페이지-기능-안내)
   - [관리자 화면 <통합관리시스템>](#-관리자-화면-<통합관리시스템>)
   - [사용자 화면 <도서관 홈페이지>](#-사용자-화면-<도서관-홈페이지>)

[4. 개선사항 및 후기](#-4.-후기-및-개선점)
   - [후기](#-후기)
   - [피드백 반영 및 개선사항](#-피드백-반영-및-개선사항)

[5. 참고 URL](#-5.-참고-URL)

<br><br>

## 1. 프로젝트 개요
### 🗓 개발 기간
* 2024.04.01 ~ 2024.04.19
* 1주차 : 기존 프로젝트를 스프링 프로젝트로 변환, 기능 테스트 후 추가개발 기능, 에러 등을 바탕으로 회의 진행
* 2주차 : 에러 수정 및 기능 개선, 추가 기능 개발 작업 진행
* 3주차 : 2차 기능 테스트 및 개발작업 마무리, 발표자료 업데이트

<br>

### 🖥 사용 기술 및 개발 환경
* OS : <img src="https://img.shields.io/badge/windows 11-0078D4?style=for-the-badge&logo=windows11&logoColor=white"> 
* Front-end : <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
* Back-end : <img src="https://img.shields.io/badge/Java-34567C?style=for-the-badge&logo=Java&logoColor=white"> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=Oracle&logoColor=white"> <img src="https://img.shields.io/badge/OpenJDK-000000?style=for-the-badge&logo=OpenJDK&logoColor=white"> <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white">
* Tools : <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
* Library : <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jQuery&logoColor=white"> <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=for-the-badge&logo=ApacheTomcat&logoColor=black"> <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=Chart.js&logoColor=white"> <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=JSON&logoColor=white">

<br>

### 👩‍💻 팀원 소개
* [도경민](https://github.com/mindyhere)
* 박미현🙋‍♀️
* [양미영](https://github.com/didaldud)
* [조연우](https://github.com/yunuyununu)
* [홍재희](https://github.com/jh91019)

※ 기존 프로젝트 내용 제외하고 스프링 전환 작업 내용만 작성
![member](https://github.com/Miihyunee/LibraryinMarch_spring.ver/assets/151993240/772f6286-ad43-412f-83e7-cd8706d1f3a1)

<br><br>

## 2. 프로그램 구조
### 🔹 ER Diagram
![erDiagram](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/4ce6cca0-29a9-4622-9053-7c1650431234)

<br>

### 🔹 View
![view](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/a5d8b2cf-63eb-4e81-b617-1d63277b5ef6)

<br>

### 🔹 Usecase Diagram
![usecase](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/231b4dd7-0193-42ab-857f-9368f744c1dd)

<br>

### 🔹 Flow Chart
 - 관리자 
![flow_admin](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/6850b5c1-19c7-42dc-a5aa-039ad6ceb444)

<br>

 - 사용자(회원/비회원)
![flow-user](https://github.com/Miihyunee/LibraryinMarch/assets/151993240/8c42ac33-d93d-418c-9c4a-ea3b85f6611e)

<br><br>

## 3. 페이지 기능 안내
#### 관리자 화면 <통합관리시스템>
![메인](https://github.com/Miihyunee/CafeManagement/assets/151993240/4921ab99-0838-48aa-a651-23780d4722ec)

![메인2](https://github.com/Miihyunee/CafeManagement/assets/151993240/a3e70056-8841-4d46-9a93-6858c4294b2c)

<br>

#### 사용자 화면 <도서관 홈페이지>
![매출](https://github.com/Miihyunee/CafeManagement/assets/151993240/a0f41ccb-cc85-48c7-8cee-25faa2ec7a5b)

![매출2](https://github.com/Miihyunee/CafeManagement/assets/151993240/31d64b66-b10e-401c-a1cf-d9084ef4f76b)


<br><br>

## 4. 후기 및 개선점
### 📝 후기
- 동일 프로젝트를 스프링으로 재구성 하는 것 만으로도 도전적인 과제였습니다. 덕분에 많은 공부가 
  되었고 한층 성장할 수 있는 시간이었습니다.
- 추가 기능 개발을 포함해 미처 확인하지 못했던 에러나, 아쉬웠던 점 등을 보완하여 완성도를
  높은 프로젝트로 발전시킬 수 있었습니다.
- Git을 활용함으로써 SVN과는 다른 방식으로 협업을 경험해 볼 수 있었습니다.

<br>

### 🛠 피드백 반영 및 개선사항
- 회원 등급 개념을 추가 ▶ 서비스 이용시 등급에 따른 각기다른 이용권한 부여
- 비밀번호가 DB에 그대로 저장되었던 문제 ▶ 암호화 방식 적용
- 비밀번호 찾기에서 팝업으로 비밀번호를 알려주는 것이 아닌, 회원가입 시 작성한 메일로 임시 
  비밀번호를 전송하는 방식으로 개선
- 연체 상태에서도 도서 연장이 가능한 오류 발견 ▶ 연체 여부 확인하는 단계를 추가하여 기능 개선
- 개발기간부족으로 기존에 구현하지 못했던 검색어 자동완성 기능 추가
- 희망도서와 관련된 추가 기능 구현 ▶ 오픈API의 적용 및 이용자는 희망도서 신청 및 취소 서비스를 
  이용할 수 있고, 관리자는 이용자가 신청한 희망도서의 상태를 변경 가능하도록 추가 기능 개발완료


<br><br>

## 5. 참고 URL
| No. | Site | URL |
|---|:---:|---:|
| 1 | 노원구 구립도서관 | https://www.nowonlib.kr |
| 2 | 인창도서관 | https://www.gurilib.go.kr/inlib/index.do |
| 3 | 국립중앙도서관 | https://www.nl.go.kr |
| 4 | 알라딘 | https://www.aladin.co.kr/home/welcome.aspx |
| 5 | 교보문고 | https://www.kyobobook.co.kr |
