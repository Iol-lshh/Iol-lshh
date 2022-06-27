# portfolio
포트폴리오입니다.

# 자기소개

## 보유 기술 스택
- JAVA(중)
	- Young/Old 영역, 여러 GC 작동의 기초를 설명할 수 있습니다.
- ES6+(중)
	- 동적 타입, 실행컨텍스트, 비동기 관리에 대해서 설명할 수 있습니다.
- C#(하)
- Spring MVC 서블릿 기반 WAS
- Flask, NodeJS 이벤트 루프 기반 WAS
- Vue(하), React(하)
- [MSSQL(중)](https://github.com/Iol-lshh/portfolio/tree/main/MSSQL)
- 다른 영속성 시스템도 실행계획을 보며, 자유롭게 쿼리 작성 가능할 정도로 사용가능합니다.
- EC2, ELB, ES3, Lambda 등의 AWS 서비스 경험(하)

Oracle Database, AWS EC2, Apache Tomcat, Flask, Java, JavaScript, MSSQL(Microsoft SQL Server), Python, Spring, Google Dialogflow, ASP.NET, JSP, MyBatis, NginX, RabbitMQ


## 그 외,
- OOP에서의 추상화와, 디자인 패턴(GoF)을 항상 고려합니다.
- 서블릿 기반과 이벤트 루프 기반 웹 서버의 차이를 명확히 압니다.
- 인터페이스 구현에 흥미가 높습니다(RestAPI, DB Link, pub/sub, 메시징 큐 등...)
   
- 프로개발자라면, 클린 코드를 위해 항상 고심하고, 공부해야 한다고 생각합니다.   
   - 여러 팀 프로젝트를 하면서 느꼈던 것은,  
   아무리 잘 짜여진 코드이더라도, 로직이 커지면 더럽혀지기 일수였습니다.  
   그러곤 난감해진 코드만 남아있었습니다.  
   기준을 정립해야겠다고 생각했습니다.   
   베스트 프렉티스에 대해 끊임없는 고민을 하였고,     
   디자인 패턴 및 클린 코드를 공부하여 기준을 잡았습니다.  
   
- **기본이 가장 화려한 것입니다.** 
	기술의 부채를 쌓지 않는 것을 뛰어넘어, 심화된 기본을 갖춰, 항상 흔들림 없는 개발 실력을 위해 노력합니다.   
- **닌자가 되지 않고자 합니다.**
	여러 추측만 내놓고 사라지는 개발자는 되지 않겠습니다.  
	테스트와 정량화 도구를 통한 객관적 수치 활용을 공부중입니다.   

---

# 경력

## 천재교과서
>기간 : 2021.01 ~ (재직중)    
> 백오피스 인 CRM, MGT 및 회원, 물류, SMS 시스템을 운영했습니다.(풀스택)    
>    
>### 서울런 크로스 플랫폼 자동 로그인   
> 기간 : 2022.06    
> 서울런 서비스로 밀크T가 포함되었습니다.    
> 모바일 환경에서 밀크T 접속시에, WWW에서 모바일로 자동 로그인을 구현했습니다.   
>    
>### 특정 사용자의 권한 예외 처리 리팩토링   
>기간 : 2022.02 ~ 2022.03   
>페이지와 프로시저 상에, 직급과 부서에 따라 버튼이나 조회 기능이 막혀있습니다.    
>각 페이지에 대한 접근 권한은 DB 상으로 관리 되었으나, 각 페이지의 CRUD 권한은 코드 상에서 관리 되었습니다.    
>때문에, 권한이 필요한 예외의 직원(교사, 물류, 마케팅 등 관리자)들이 이 페이지 CRUD 권한을 열어달라고 요청하는 경우가 많았고,   
>그럴때마다 페이지와 프로시저는 하드코딩 예외처리로 지속적으로 수정해줘야 했습니다.     
>이것을 DB로 옮기고, 권한을 가져오도록 개선하였으며, 관리하는 기능을 추가했습니다.    
>   
>### 분산화 된 사용자 정보 재설계   
>기간 : 2022.01    
>파편화된 데이터 통합을 위해, 회원 체계에 조직 값을 추가하고, 해당 관리 기능을 만들었습니다.    
>   
>### 프로젝트 HUB - 통계 데이터 이관   
>기간 : 2021.12   
>사내 영업 지표 통계 서비스 통합에 따라, SQL Server 데이터를 Oracle로 이관하는 작업에 참여했습니다.   
>(ETL - 데이터 샘플링 및 검증 과정)    
>   
>### 중고 CRM - 물류 WMS 간, 인터페이스 고도화 작업   
>기간 : 2021.11 ~ 2021.12   
>  인터페이스가 API로 이루어진 물류/AS 기능에, 추가 속성 및 기능 추가 작업하였습니다.   
>
>### 유아 CRM : SMS 전송 관리 기능 개발 참여   
>기간 : 2021.02 ~ 2021.07   
>써드 파티로써 CJ_Msg를 이용하고 있었으며, DB link 방식으로 인터페이스가 이루어집니다.  
>이를 신규 서비스인 유아의 것을 만들고, 기존 로직을 개선하였습니다.   
>또한 기존 기능인, 중학 CRM의 SMS 기능을 개선했습니다.   
>
>### 데이터 추출 및 적용 전산 업무  
>기간 : 2021.01 ~   
>타 부서의 원하는 조건에 따라, 여러 데이터베이스 객체들과 테이블들에서   
>통계 데이터 추출 및 다량의 데이터 INSERT, UPDATE 작업을 진행하였습니다.   
>또한 기존의 업무 쿼리 스크립트들의 로직을 분석, 개선하였습니다. (커서 제거, 스크립트 프로시저화)  
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
>데이터를 KoNLPy를 이용하여 
>형태소 분석, 감정 분석을 하여 데이터를 가공하고, 
>ARIMA 모델을 통해 실거래가를 예측을 시도합니다.   
   
   
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


---

# 목표
- 주도적인 모듈 구현 경험       
- MSA를 위한 심화 기반 쌓기
	(lb7에서 오토스케일링을 이용한 부하 처리 기법 등.. with Django)         
- JAVA 최적화(GC 튜닝 등의 코어단)에 대한 고민과 공부
- Spring WebFlux, Spring Cloud에 대한 학습

