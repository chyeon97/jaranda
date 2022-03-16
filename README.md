<p align='middle'>

<h1 align="middle"><a  href='https://jaranda.netlify.app/'>https://jaranda.netlify.app/</a></h1>
<p align='middle'><img alt="GitHub top language" src="https://img.shields.io/github/languages/top/six-sense/jaranda?color=blueviolet"> <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/six-sense/jaranda">

<br/>

## 📌 프로젝트 소개

### 프리온보딩 코스 Jaranda 기업 과제

> ❕ **회원가입, 로그인 / 로그아웃 기능과 다양한 메뉴를 가지고 있는 홈페이지, 관리자 페이지 구현하기**❗

<br/>

## 👨‍💻 실행 방법

### 설치

`npm install`

### 실행

`npm start`

### 데모 로그인

`Admin : admin1 / admin123!`

`User : user1 / user123!`

<br/>

## 📑 구현 목록

`회원 가입`

- 아이디, 비밀번호, 이름, 나이, 주소, 신용카드 등록을 통한 회원 가입 기능
- 각 `input`(아이디, 회원가입, 카드)에 대한 Validate 설정(유효성 검사, 중복 검사, 비밀번호 확인)
- 모든 input 값이 존재할 때 회원가입 완료 (미흡 입력 존재 시 해당 인풋으로 cursor 이동)
- 주소 등록은 다음 API 활용, 카드 등록은 팝업창 구현.

`로그인`

- 아이디, 패스워드 유효성 검사
- 유효성 검사 후 존재하는 유저 인증 후 token 발급
- 발급된 token으로 admin, user 페이지 이동

`관리자`

- localStorage에 존재하는 userData 출력
- 검색기능으로 name, userId에서 키워드 검색
- localStorage에 존재하는 userId의 menuItem 수정 가능
- 관리자 혹은 유저로 계정 추가

`메뉴바`

- 관리자 페이지에서 계정별 메뉴 설정 시 해당 계정에게 선택된 메뉴만 보여짐
- 유저가 권한이 없는 페이지주소를 입력하면 페이지 접근불가, 메인페이지로 이동
- Not Found 페이지

`라우트` && `접근 권한`

- 로그인 전
  - 로그인 없이 접근 가능한 메뉴 렌더링 (로그인/회원가입 페이지)
- 로그인 후
  - 관리자 계정으로 로그인시 Admin 페이지 렌더링
  - 일반 계정으로 로그인시 게스트메뉴에서 유저별 허가된 메뉴 렌더링
  - 로그인 후에는 로그인/회원가입 페이지 접근 불가
- 로그아웃

<br/>

## 📂프로젝트 구조

| 폴더 / 파일 | 설명                               |
| ----------- | ---------------------------------- |
| Assets      | jaranda 로고 및 아이콘.            |
| Components  | 각 Page에 사용되는 Component 모음. |
| Modal       | 팝업창 Modal.                      |
| Pages       | Route를 위한 Page 목록.            |
| Services    | 권한별 인가 책정.                  |
| Styles      | 기본 공통 Style.                   |
| Utils       | localStorage 접근 및 공통 함수.    |
| App.js      | public, private Route 정리.        |
| routes.js   | 계정별 페이지 권한 구분.           |

<br/>
