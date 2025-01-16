<h2 align="center">
  <img src="https://github.com/user-attachments/assets/41e1d543-453a-498c-8fcd-169e7956886c" alt="CIS" width="300px">
  <br>
  Company Communication Integrated System
  <br>
  [ CIS : 사내 커뮤니케이션 통합 시스템 ]
  <br>
</h1>

<br>

## 📌 목차
1. [🖥️ 프로젝트 개요](#-프로젝트-개요)
2. [📕 담당 파트 구현](#-담당-파트-구현)<br>
  2-1. [📆 개발기간](#-개발기간)<br>
  2-2. [🔖 프로젝트 주제](#-프로젝트-주제)<br>
  2-3. [⚙️ 개발환경 및 도구](#-개발환경-및-도구)<br>
  2-4. [🧑‍🤝‍🧑 멤버 구성](#-멤버-구성)<br>
3. [🖌️ 화면 설계](#-화면-설계)
4. [📄 정의서 및 명세서](#-정의서-및-명세서)
5. [🏗️ ERD](#-ERD)
6. [📽️ 영상](#-영상)
7. [📂 발표자료](#-발표자료)

<br>

## 🖥️ 프로젝트 개요
### 📆 개발기간
  - 2024.11.14 ~ 2024.12.13 개발
  - [(👋 Click) WBS](https://docs.google.com/spreadsheets/d/1XxBHsajXqKLqZKJlitl2uBngqueQwipY1n8iQVUgjJI/edit?usp=sharing)
  ![WBS](https://github.com/user-attachments/assets/52301a40-a326-4cc9-b68a-7ba0957de4fe)

### 🔖 프로젝트 주제
  - 주제 : 사내 커뮤니케이션 통합 시스템
  - 구성원 : 4인 프로젝트
  - 선정 이유
    <br>
    ① 자신을 포함한 회사 내 다른 직원들 간 커뮤니케이션 및 업무와 관련된 웹 페이지를 구현하고자 함
    <br>
    ② 사용자가 커뮤니티를 이용해 업무적인 소통을 이뤄내고 개인 근무를 관리할 수 있는 기능을 구현하고자 함
  - 목표
    <br>
    ① Spring Framework의 구조를 이해하고 CRUD 작업에 대한 기술을 숙달하는 것에 의의를 둠
    <br>
    ② 새로운 개발 환경 및 툴을 사용하는 것으로 새로운 것에 대한 사용법과 이해를 높이고자 함

### ⚙️ 개발환경 및 도구
![개발환경](https://github.com/user-attachments/assets/a57e7365-0ca1-46cf-b069-1b9bc4d49e3b)
  - IDE :
    ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?&style=for-the-badge&logo=intellijidea&logoColor=white)
    ![VSCode](https://img.shields.io/badge/VSCode-2599ED.svg?&style=for-the-badge&logo=visualstudiocode&logoColor=white)
  - Language :
    ![Java 17.0.2 (JDK 17v)](https://img.shields.io/badge/Java%2017.0.2%20(JDK%2017v)-007396.svg?&style=for-the-badge&logo=java&logoColor=white)
  - Framework :
    ![Spring Boot 3.3.5](https://img.shields.io/badge/Spring%20Boot%203.3.5-6DB33F.svg?&style=for-the-badge&logo=springboot&logoColor=white)
  - Persistence Framework :
    ![Mybatis 3.0.3](https://img.shields.io/badge/Mybatis%203.0.3-DD0700.svg?&style=for-the-badge&logo=mybatis&logoColor=white)
  - Build :
    ![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?&style=for-the-badge&logo=gradle&logoColor=white)
  - DBMS :
    ![MySQL 8.0.4v](https://img.shields.io/badge/MySQL%208.0.4v-4479A1.svg?&style=for-the-badge&logo=mysql&logoColor=white)
  - DB Tool :
    ![DBeaver](https://img.shields.io/badge/DBeaver-382923.svg?&style=for-the-badge&logo=dbeaver&logoColor=white)
    ![ERD Cloud](https://img.shields.io/badge/ERD%20Cloud-6B46C1.svg?&style=for-the-badge&logo=erdcloud&logoColor=white)
  - WAS :
    ![Apache Tomcat 10.1.31](https://img.shields.io/badge/Apache%20Tomcat%2010.1.31-F8DC75.svg?&style=for-the-badge&logo=apachetomcat&logoColor=white)
  - View Template :
    ![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F.svg?&style=for-the-badge&logo=thymeleaf&logoColor=white)
  - Library :
    ![JQuery](https://img.shields.io/badge/JQuery-0769AD.svg?&style=for-the-badge&logo=jquery&logoColor=white)
    ![JDBC](https://img.shields.io/badge/JDBC-3C5280.svg?&style=for-the-badge&logo=jdbc&logoColor=white)
    ![Lombok](https://img.shields.io/badge/Lombok-EC1C24.svg?&style=for-the-badge&logo=lombok&logoColor=white)
  - VCS :
    ![GitHub](https://img.shields.io/badge/Github-181717.svg?&style=for-the-badge&logo=github&logoColor=white)
    ![Git Bash](https://img.shields.io/badge/Git%20Bash-F05032.svg?&style=for-the-badge&logo=git&logoColor=white)

### 🧑‍🤝‍🧑 멤버 구성
|팀원명|프로필|역할|담당업무|
|---|---|---|---|
|[박진우](https://github.com/J1NU2)|<p align="center"><img src="https://avatars.githubusercontent.com/u/104364437?v=4" width="100px"></p>|<p align="center">이메일<br>개인 근무 관리<br>프로젝트 구조 설계</p>|메인 페이지 및 Base Layout View 설계<br>이메일 및 근무관리 테이블 설계 및 샘플 데이터 작성, CRUD 및 View 구현<br>이메일 파일 첨부 기능, 이메일 및 근무관리 리스트 페이징 기능 구현<br>MySQL 데이터베이스 Sequence 기능 정의 및 원격 접속 관리|
|[김시온](https://github.com/KIMMZN)|<p align="center"><img src="https://avatars.githubusercontent.com/u/89295607?v=4" width="100px"></p>|<p align="center">게시판 관리</p>|게시판 테이블 설계 및 샘플 데이터 작성, CRUD 및 View 구현<br>게시판 검색, 리스트 페이징, 파일 첨부 기능 구현<br>관리자 : 공지사항 등록 및 게시판 관리 기능 구현<br>MySQL 데이터베이스 Sequence 기능 정의|
|[원진호](https://github.com/weonjinho)|<p align="center"><img src="https://avatars.githubusercontent.com/u/158018895?v=4" width="100px"></p>|<p align="center">로그인 및 회원가입<br>직원 관리</p>|직원 및 관리자 테이블 설계 및 샘플 데이터 작성, CRUD 및 View 구현<br>Session을 활용한 로그인, 로그아웃 기능 구현<br>직원 목록 페이징 기능 구현<br>MySQL 데이터베이스 원격 접속 관리|
|[심지수](https://github.com/Abyssmash)|<p align="center"><img src="https://avatars.githubusercontent.com/u/174307257?v=4" width="100px"></p>|<p align="center">프로젝트 GitHub 관리</p>|CIS 프로젝트 GitHub Repository 관리<br>Git Branch 전략 사용 및 프로젝트 코드 병합 관리|

<br>

## 📕 담당 파트 구현
<details>
  <summary><b>① MySQL Sequence 생성</b></summary>
  <ul>
    <li>1. 시퀀스 정보를 저장할 테이블 생성</li>
    <ul>
      <li>name : 시퀀스 이름 컬럼</li>
      <li>currval : 순차적으로 증가될 숫자를 저장할 컬럼</li>
      <img src="https://github.com/user-attachments/assets/cc87f903-b054-4a44-9a02-fe7bb5e3c71b">
    </ul><br>
    <li>2. 시퀀스 생성을 위한 프로시저 설정</li>
    <ul>
      <li>프로시저 실행 시 입력받은 텍스트를 기준으로 시퀀스 생성</li>
      <li>만약, 동일한 이름의 시퀀스 존재 시 해당 시퀀스 삭제 후 생성</li>
      <img src="https://github.com/user-attachments/assets/36626340-e288-4a24-908d-f0baaad7958c">
    </ul><br>
    <li>3. 시퀀스 번호를 순차적으로 상승시킬 함수 선언</li>
    <ul>
      <li>함수 실행 시 입력받은 텍스트와 동일한 시퀀스의 숫자 증가(+1)</li>
      <li>시퀀스 숫자 증가(+1) 후 해당 시퀀스 숫자 반환</li>
      <img src="https://github.com/user-attachments/assets/0fd95df2-9a05-4942-bdf2-ae483fd777a7">
    </ul><br>
    <li>4. 시퀀스 생성 및 실행</li>
    <ul>
      <li>CALL문을 사용하여 프로시저를 실행해 시퀀스를 생성</li>
      <li>생성된 시퀀스명을 기준으로 시퀀스 함수 실행</li>
      <img src="https://github.com/user-attachments/assets/2e86d75f-9cc1-4a1f-83e8-7a8942f52042">
    </ul>
  </ul>
  <br>
</details>
<details>
  <summary><b>② </b></summary>
</details>
<details>
  <summary><b>③ </b></summary>
</details>
<details>
  <summary><b>④ </b></summary>
</details>
<details>
  <summary><b>⑤ </b></summary>
</details>
<details>
  <summary><b>⑥ </b></summary>
</details>
<details>
  <summary><b>⑦ </b></summary>
</details>
<details>
  <summary><b>⑧ </b></summary>
</details>
<details>
  <summary><b>⑨ </b></summary>
</details>

<br>

## 🖌️ 화면 설계
  - 담당 파트 화면 설계 (Figma)
![MyPart_Mockup](https://github.com/user-attachments/assets/a5f3e6cc-c785-4de8-8750-6d7b173027b6)

<br>

## 📄 정의서 및 명세서
[(👋 Click) 프로젝트 정의서 및 명세서](https://docs.google.com/spreadsheets/d/1XxBHsajXqKLqZKJlitl2uBngqueQwipY1n8iQVUgjJI/edit?usp=sharing)

<br>

## 🏗️ ERD
[(👋 Click) ERD Cloud](https://www.erdcloud.com/d/Fmmb2eLa5ApoemFQc)
<br>
![CIS_ERD](https://github.com/user-attachments/assets/312c4dd9-7116-43a6-90f2-8ba7ed721156)

<br>

## 📽️ 영상
[(👋 Click) 프로젝트 동영상](https://drive.google.com/file/d/16RYkYfFLMOTpY1IXXF25Dkt7Avgh9re7/view?usp=sharing)

<br>

## 📂 발표자료
[(👋 Click) PPT 발표자료](https://www.canva.com/design/DAGZhwdv7Po/yTeb8CQPf3wReItMkH6Kug/edit?utm_content=DAGZhwdv7Po&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
