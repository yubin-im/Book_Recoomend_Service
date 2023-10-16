# BookRecommendService_MVC2_Project
도서 추천 및 평가 서비스


## 프로젝트 소개
사용자가 관심 있는 장르의 도서를 추천해 주고, 도서 별점 부여와 리뷰를 작성할 수 있습니다.

### 개발 기간
* 2023.09.13 - 2023.10.10

### 참여 인원
  - 임유빈: 메인 페이지, 도서 검색, 도서 추천, 도서 데이터 분석 및 시각화
  - 김락윤: 로그인, 회원가입, 아이디 비밀번호 찾기, 회원정보 변경, 리뷰 찜 기능

### 개발 환경
  - **Language**: Java 8
  - **JDK**: 1.8.0
  - **IDE**: Eclipse
  - **Model**: MVC2
  - **Database**: Oracle DB(11)

### 프로젝트 구조
  - src/book.test
  - WebContent/dataAnalysis
  - WebContent/login
  - WebContent/main
  - WebContent/mypage

### ERD


## 주요 기능
#### 로그인(https://www.notion.so/rakyun/2a02ba0d4a6f40f0a4ba143371b7b656?pvs=4)

#### 회원가입
  - 가입 시 관심있는 장르 두가지 선택

#### 메인
  - 전체 도서 목록 출력
  - 도서 통합 검색

#### 도서 상세
  - 도서 상세 출력
  - 도서 별점과 리뷰 작성
  - 도서 즐겨찾기

#### 추천도서
  - 가입 시 선택한 두 가지 장르의 도서 출력

#### 마이페이지
  - 내가 작성한 리뷰 목록
  - 찜 목록

#### 실시간 트렌드
  - 리뷰 데이터 워드 클라우드
  - 장르 별 도서 수 그래프
  - 출간 연도 별 그래프
