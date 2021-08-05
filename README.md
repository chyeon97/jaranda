# Jaranda 기업 과제

<br/>

>  📌 **Wanted 프리온보딩 코스 (프론트 엔드) 기업 과제**
>
>  <br/>
>
>  📗 **회원가입, 로그인 / 로그아웃 기능과 다양한 메뉴를 가지고 있는 홈페이지, 관리자 페이지 구현하기 **

<br/>

**결과물은 `배포 링크`, 진행 과정과 세부 사항은 `노션 미팅 로그`를 클릭해주세요!**

| 🎈[배포 링크](https://jaranda.netlify.app) | 🧐[노션 미팅 로그](https://first-english-d5d.notion.site/d789f1ad2e434084be98bb6c54a006b2) |
| ----------------------------------------- | ------------------------------------------------------------ |

<details>
    <summary><STRONG>
       📚 과제 요구사항 보기
        <STRONG></summary>
    <div markdown="1">
<h3>1. 아래 정보를 입력받아 회원가입 페이지를 구현하고 로그인/로그아웃 기능을 구현해주세요.</h3>
- 이름<br/>
- 주소 (팝업을 이용해서 입력받음)<br/>
- 신용카드 정보 (팝업을 이용해서 입력받음)<br/>
- 나이<br/><br/>
1.1 관리자 로그인을 하면 등록한 계정 정보를 아래 방법을 이용하여 시각화 해 주세요.<br/>
- 테이블 Component 페이지 만들기<br/>
- Data Table 구현<br/>
- 페이지네이션 구현<br/>
- 검색기능 구현<br/><br/>
1.2 정보는 로컬 저장소 등 자유롭게 저장해도 됩니다.<br/><br/>
1.3 주소는 다음에서 제공하는 입력창을 사용해도 무방합니다.<br/><br/>
1.4 관리자 계정은 임의로 정의해도 됩니다.<br/><br/>
<h3>2. 다양한 메뉴를 가지고 있는 홈페이지 관리자 페이지를 구현해 주세요.</h3>
2.1 계정, 비밀번호만 입력하면 로그인이 되어야 합니다.<br/><br/>
2.2 로그인 된 계정은 자신에게 허용된 메뉴만 보여야 합니다.<br/><br/>
2.3 관리자는 계정을 임의로 생성할 수 있고 계정별로 볼 수 있는 메뉴를 설정할 수 있습니다.<br/><br/>
2.4 관리자 계정은 임의로 정의해도 됩니다.<br/><br/>
2.5 정보는 로컬 저장소 등 자유롭게 저장해도 됩니다.<br/><br/>
2.6 메뉴는 임의대로 정의해도 되며 메뉴를 선택했을 때 나오는 화면에는 메뉴명이 출력되면 됩니다.<br/><br/>
2.7 관리자 로그인을 하면 등록한 계정 정보를 아래 방법을 이용하여 시각화 해 주세요.<br/>
- 테이블 Component 페이지 만들기<br/>
- Data Table 구현<br/>
- 페이지네이션 구현<br/>
- 검색기능 구현<br/>
</div>
</details>
<br/>

## 📑 구현 목록

`회원 가입`

- 아이디, 비밀번호, 이름, 나이, 주소, 신용카드 등록을 통한 회원 가입 기능
- 각 `input`(아이디, 회원가입, 카드)에 대한 Validate 설정(유효성 검사, 중복 검사, 비밀번호 확인) 
- 모든 input 값이 존재할 때 회원가입 완료 (미흡 입력 존재 시 해당 인풋으로 cursor 이동)
- 주소 등록은 다음 API 활용, 카드 등록은 팝업창 구현.

`로그인`

- 작성 요망 

`관리자`

- 작성 요망 

`메뉴바`

- 작성 요망

`라우트`

- 작성 요망

`접근 권한`

- 작성 요망

<br/>

## 👨‍💻 실행 방법

### 설치 

`npm install`

### 실행

`npm start`

<br/>

## 📂프로젝트 구조

```
.src
+-- Assets
+-- Components
|	+--Layout
|		--index.js
|		--Layout.js
|		--LayoutStyle.js
|	:
|	:
+-- Modal       
+-- Pages
|	+--AdminPage
|		--index.js
|		--AdminPage.js
|		--AdminPageStyle.js
|	:
|	:
+-- Styles
+-- Utils
|	+--storage
|		--storage.js
|		--userDataForm.js
|	--checkValid.js
|	--constants.js
|	:
App.js
index.js
routes.js
```

| 폴더 / 파일 | 설명      |
| ----------- | --------- |
| Assets      | 작성 요망 |
| Components  | 작성 요망 |
| Modal       | 작성 요망 |
| Pages       | 작성 요망 |
| Styles      | 작성 요망 |
| Utils       | 작성 요망 |
| App.js      | 작성 요망 |
| index.js    | 작성 요망 |
| routes.js   | 작성 요망 |



