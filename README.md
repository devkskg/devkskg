
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=200&section=header&animation=fadeIn&fontAlignY=40&text=안녕하세요.%20강성관입니다.&fontSize=60" />

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=devkskg)](https://github.com/anuraghazra/github-readme-stats)

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=devkskg&theme=merko&theme=transparent)](https://github.com/anuraghazra/github-readme-stats)

## 보유기술
| 언어 | DB | IDE | 빌드 | 배포 | 기술 |
| --- | --- | --- | --- | --- | --- |
|<img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=flat-square&logo=openjdk&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/css3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/javascript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E">|<img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white">&nbsp;|<img src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=flat-square&logo=intellij-idea&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/Eclipse-FE7A16.svg?style=flat-square&logo=Eclipse&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=flat-square&logo=visual-studio-code&logoColor=white">|<img src="https://img.shields.io/badge/Apache%20Maven-C71A36?style=flat-square&logo=Apache%20Maven&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/Gradle-02303A.svg?style=flat-square&logo=Gradle&logoColor=white">|<img src="https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=flat-square&logo=apache-tomcat&logoColor=black">&nbsp;<img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/jenkins-%232C5263.svg?style=flat-square&logo=jenkins&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/github-%23121011.svg?style=flat-square&logo=github&logoColor=white">|<img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=flat-square&logo=spring&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/spring%20boot-%236DB33F.svg?style=flat-square&logo=springboot&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/Mybatis-181717.svg?style=flat-square&logo=Mybatis&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/jquery-%230769AD.svg?style=flat-square&logo=jquery&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=flat-square&logo=bootstrap&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/JSP-3776AB.svg?style=flat-square&logo=JSP&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/JSON-3776AB.svg?style=flat-square&logo=JSON&logoColor=white">|

## 세미 프로젝트
### LumoDiem(원데이클래스 예약 웹 서비스)
* 핵심 기술 :
  - **Backend**: Java 17, Servlet/JSP, EL/JSTL, Tomcat
  - **Frontend**: HTML5, CSS3, JavaScript (ES6), Bootstrap 5, jQuery
  - **Database**: MariaDB, MyBatis, JDBC
  - **Authentication**: SHA-512 단방향 해시 암호화
  - **API & Tool**: Eclipse, HeidiSQL, GitHub, Daum Address API, KAKAOPAY API
* 핵심 기능 :
  - 회원 관련 기능
      - 회원 가입 기능
      - 로그인 기능
      - 회원 탈퇴 기능
  - 클래스 상세 페이지
      - 좋아요 등록, 조회, 삭제
      - 실시간 채팅방(Polling 방식)
      - 카카오페이 API를 이용한 결제 시스템
  - 마이페이지
      - 주최자 마이페이지(주최 클래스 조회, 주최 클래스별 리뷰 조회)
      - 참여자 마이페이지(수강 클래스 조회, 작성 리뷰 조회)
      - 공통 기능(좋아요 클래스, 좋아요 리뷰, 작성 댓글 조회)

  
## 파이널 프로젝트
### Eroom(개발자 전용 그룹웨어)
* 핵심 기술 :
  - **Backend**: Java 17, Spring Boot 3, Spring MVC, Spring Security
  - **Frontend**: HTML5, CSS3, JavaScript (ES6), Bootstrap 5, Thymeleaf, jQuery
  - **Database**: MariaDB
  - **Authentication**: Spring Security 암호화
  - **배포 환경**: Ubuntu, Docker, Docker Compose, Jenkins
      (아마존 사용시 : AWS EC2, RDS, S3, Docker, Docker Compose, Jenkins)
  - **기타**: WebSocket(실시간 알림), Puppeteer(HTML → PDF 변환), SignaturePad, List.js, OpenAI GPT API 연동

- 핵심 기능 :
  - 결재 시스템
    - 결재 상태 관리 (승인, 진행, 반려, 회수)
    - 서명(SignaturePad) 기능
    - 트리 구조 기반 결재자 정보 관리
    - 파일 첨부 기능 (문서, 이미지 등 업로드/다운로드)
    - WebSocket을 활용한 실시간 결재 알림 기능
    - Puppeteer를 이용한 결재 문서 PDF 출력 (HTML → PDF 변환)
    - 연차 신청 결재 승인 시 연차 이력 및 캘린더에 자동 반영
    - 재기안 기능
  - 조직도 및 주소록 기능
    - 트리 구조 및 드롭다운을 통한 사원 목록 조회
    - 관리자 부서/팀 관리
    - 프로필 카드
    - 협력업체 주소록 관리
  - GPT 챗봇 기능
    - OpenAI GPT API 기반 챗봇 기능


## 자격
* 정보처리 기사(필기합격)
* SQLD(SQL 개발자)(최종합격)
  
