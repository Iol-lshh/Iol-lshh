# portfolio
포트폴리오입니다.

# 자기소개

## 보유 기술 스택
- JAVA(중)
- ES6+(중)
- C#(중)
- 여러 프레임워크 경험(Spring, ASP.NET, NodeJS 기반)
- Vue(하), React(하)
- MSSQL(중)
- 다른 영속성 시스템도 무난히 사용합니다.

Oracle Database AWS EC2 Apache Tomcat Flask Java JavaScript MSSQL(Microsoft SQL Server) Python Spring Google Dialogflow ASP.NET JSP MyBatis


## 그 외,
- OOP에서의 추상화와, 디자인 패턴(GoF)을 항상 고려합니다.
- 넷플릭스 OSS에 관심이 있습니다(MSA)
- 인터페이스 구현에 흥미가 높습니다(RestAPI, DB Link, pub/sub, 메시징 큐 등...)
   
- 가장 중요한 것은 문서작성이라고 생각합니다.
   - 진열된 쓰레기 코드를 방지하고, 분석에 시간을 줄여줘야 합니다.
- 코드로 돈을 벌고 있는 프로개발자라면, 클린 코드를 위해 항상 고심하고, 공부해야 한다고 생각합니다.
- 기본이 가장 화려한 것입니다. 심화된 기본을 갖춰, 항상 흔들림 없는 개발 실력을 위해 노력합니다.


---

# 경력

## 천재교과서
>기간 : 2021.01 ~ (재직중)    
>백오피스 인 CRM, MGT 및 회원, 물류, SMS 시스템을 운영했습니다.   
>
>### 하드코딩된 예외 권한 처리   
>기간 : 2022.02 ~ 2022.03   
>페이지와 프로시저 상에, 직급과 부서에 따라 버튼이나 조회 기능이 막혀있습니다.   
>페이지에 대한 권한은 관리되었으나, 기능에 대한 권한은 기획 단계에 없었던 것 같습니다.   
>때문에, 권한이 필요한 예외의 직원(교사, 물류, 마케팅 등 관리자)들이   
>이 페이지 기능의 권한을 열어달라고 요청하는 경우가 많았고,    
>그럴때마다 페이지와 프로시저는 하드코딩 예외처리로 지저분해졌습니다.   
>이것을 디비로 옮기고, 권한을 가져오도록 개선하였으며, 처리하는 UI 페이지를 구현했습니다.   
>
>### 교사(중학 CRM 회원) 조직 값 추가   
>기간 : 2022.01   
>HUB를 위한 데이터 통합을 위해, 교사 체계에 다른 서비스의 조직 값 컬럼이 필요하여, 해당 값을 적용하고, 페이지를 만들었습니다.   
>
>### HUB 통계 데이터 이관   
>기간 : 2021.12   
>유아, 초, 중고 서비스의 영업 지표 통계를 한 서비스로 통합하는 프로젝트에 따라,   
>SQL Server 데이터를 오라클로 이관하는 작업을 하였습니다.   
>
>### 중고 CRM - 물류 WMS 페이지 새 데이터 테이블 컬럼 추가   
>기간 : 2021.11 ~ 2021.12   
>WMS 서비스와 인터페이스가 API로 이루어진 물류, AS 관리 페이지 상에 기능 및 컬럼이 필요해져서, 중학 CRM에 해당 기능을 만들고,   
>추가하였습니다.   
>
>### 유아 CRM : SMS 관리 페이지 개발   
>기간 : 2021.02 ~ 2021.07   
>페이지 작성 및 프로시저 작성하였습니다. 써드 파티로써 CJ_Msg를 이용하고 있었으며, 디비 링크 방식으로 인터페이스가 이루어집니다.   
>이를 만들고, 원본 클론 기획 페이지인, 기존 중학 CRM의 SMS 기능을 개선했습니다.   
>
>### 데이터 추출 및 적용 전산 업무  
>기간 : 2021.01 ~   
>타 부서의 원하는 조건에 따라, 여러 데이터베이스 객체들과 테이블들에서   
>통계 데이터 추출 및 다량의 데이터 INSERT, UPDATE 작업을 진행하였습니다.   
>또한 기존의 업무 쿼리들의 로직을 분석, 개선하였습니다. (커서 제거, 쿼리 프로시저화)   

---

# 기타 프로젝트

### Spring을 이용한, 도로교통공사 api 활용 커뮤니티 페이지
>기간 : 2020.12   
>Spring + Apache Tomcat + MyBatis   
>전체 구조 기획/설계, 서버 설정/구축, RESTful API 제작(SPA 지향)   
>전체 기여도 35% (3명)   
>[Spring을 이용한, 도로교통공사 api 활용 커뮤니티 페이지.pdf](https://github.com/markhong93/portfolio/blob/main/Spring%EC%9D%84%20%EC%9D%B4%EC%9A%A9%ED%95%9C%2C%20%EB%8F%84%EB%A1%9C%EA%B5%90%ED%86%B5%EA%B3%B5%EC%82%AC%20api%20%ED%99%9C%EC%9A%A9%20%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%20%ED%8E%98%EC%9D%B4%EC%A7%80/Spring%EC%9D%84%20%EC%9D%B4%EC%9A%A9%ED%95%9C%2C%20%EB%8F%84%EB%A1%9C%EA%B5%90%ED%86%B5%EA%B3%B5%EC%82%AC%20api%20%ED%99%9C%EC%9A%A9%20%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%20%ED%8E%98%EC%9D%B4%EC%A7%80.pdf)   
>[Java 프레임웍기반 풀스텍 양성(B) 2차프로젝트발표 - 팀:LTNS (시연 영상)](https://www.youtube.com/watch?v=V1btqGmrHO0&feature=youtu.be)   


### Jsp를 이용한, 게시글 파일 저장방식 커뮤니티 페이지
>기간 : 2020.11   
>JSP + Apach Tomcat   
>전체 구조 기획/설계, 서버 설정/구축, CRUD 기본 페이지 제작, 파일 HTML 파싱   
>전체 기여도 35% (4명)   
>[Jsp를 이용한, 게시글 파일 저장방식 커뮤니티 페이지.pdf](https://github.com/markhong93/portfolio/blob/main/Jsp%EB%A5%BC%20%EC%9D%B4%EC%9A%A9%ED%95%9C%2C%20%EA%B2%8C%EC%8B%9C%EA%B8%80%20%ED%8C%8C%EC%9D%BC%20%EC%A0%80%EC%9E%A5%EB%B0%A9%EC%8B%9D%20%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%20%ED%8E%98%EC%9D%B4%EC%A7%80/Jsp%EB%A5%BC%20%EC%9D%B4%EC%9A%A9%ED%95%9C%2C%20%EA%B2%8C%EC%8B%9C%EA%B8%80%20%ED%8C%8C%EC%9D%BC%20%EC%A0%80%EC%9E%A5%EB%B0%A9%EC%8B%9D%20%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%20%ED%8E%98%EC%9D%B4%EC%A7%80.pdf)   
>[Java 프레임웍기반 풀스텍 양성(B) 1차프로젝트발표 - 팀:LTNS (시연 영상)](https://www.youtube.com/watch?v=tLHih5xjFKA) 


### Java Swing을 활용한, 테블릿 메뉴판 연동 음식점 포스기 
>기간 : 2020.07   
>Java + Java Swing   
>구조 기획/설계, 서버 설정/제작, 프로그래밍   
>전체 기여도 50% (5명)   
>[Java Swing을 활용한, 테블릿 메뉴판 연동 음식점 포스기
.pdf](https://github.com/markhong93/portfolio/blob/main/Java%20Swing%EC%9D%84%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%ED%85%8C%EB%B8%94%EB%A6%BF%20%EB%A9%94%EB%89%B4%ED%8C%90%20%EC%97%B0%EB%8F%99%20%EC%9D%8C%EC%8B%9D%EC%A0%90%20%ED%8F%AC%EC%8A%A4%EA%B8%B0/Java%20Swing%EC%9D%84%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%ED%85%8C%EB%B8%94%EB%A6%BF%20%EB%A9%94%EB%89%B4%ED%8C%90%20%EC%97%B0%EB%8F%99%20%EC%9D%8C%EC%8B%9D%EC%A0%90%20%ED%8F%AC%EC%8A%A4%EA%B8%B0.pdf)   
   

### (한이음) 부동산 실거래가 예측 챗봇
>기간 : 2019   
>Python Flask AWS EC2 Google Dialogflow   
>여러 모델들을 통한 부동산 실거래가 예측   
>Flask를 AWS EC2 위에 올려, Dialogflow에 연결하였습니다.   
>데이터를 KoNLPy를 이용하여 형태소 분석, 감정 분석을 하여 데이터를 가공하고, ARIMA 모델을 통해 실거래가를 예측을 시도합니다.   
   
   
---

# 스터디

### 타입스크립트 프로그래밍 스터디
>기간 : 2022.02 ~ 2022.03   
>타입스크립트에서의 FP와 OOP적 특성에 대한 기능 탐구를 목표로 하고 있습니다.   
   
### 모던 자바스크립트 Deep Dive 스터디(저자 참여)
>기간 : 2021.03 ~ 2022.05   
>ES6+ 에 대한 심화 기본을 쌓았습니다.   
   
   
---

# 기타
>[개인 블로그](https://blog.naver.com/markhong93)   

