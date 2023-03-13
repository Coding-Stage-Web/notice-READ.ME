# README.md 작성하기

## 과제 작성 페이지 

💙 README.md 

# ✨땡땡파트 코슷테✨
 

<img src="https://user-images.githubusercontent.com/93020734/224770541-810ae061-8d17-46c7-8076-7a927fdc3f17.png" width="600" height="300" />

#### 💻 과제

|**week**|과제주제|과제링크(week브랜치링크첨부)|
|:---:|:---:|:---:|
|1주차|spring mvc 아키텍쳐|링크1|
|2주차|typescriprt|링크2|
|3주차|styled-component|링크3|
|4주차|FAST API|링크4|
|5주차|jquery|링크5|
|6주차|java servelet|링크6|
|7주차|usestate와 useffect|링크7|
|8주차|프로토콜|링크8|


## 프로젝트 소개 페이지

전체 💙 README.md 

    <img src="여러분의 서비스 소개 첫페이지 화면">

#### 서비스를 소개해주세요.✨✨

    발표하면서 만든 피피티의 기능 소개 페이지를 여기에 하나하나 업로드해주시면 됩니다.
    


Client&Server 리포지토리의 💙 README.md (각각의 리포지토리 안에 작성해야 합니다! )

### 🙌팀원 소개

|**본인을 표현할 수 있는 사진과 깃헙 링크**|본인을 표현할 수 있는 사진과 깃헙 링크|본인을 표현할 수 있는 사진과 깃헙 링크|본인을 표현할 수 있는 사진과 깃헙 링크|
|:---:|:---:|:---:|:---:|
|🧚🏻Web FE|👼Web FE|👼Web FE|😽Web FE|

### Tech Stack

<img width="615" alt="image" src="https://user-images.githubusercontent.com/93020734/224799811-e0ca5ed5-04d7-4e4c-8fbe-7bb043207467.png">

** 예시입니다. 

### 📂Directory Structure

폴더 구조와 폴더 설명 작성해주세요.

    💙CodingStage-Client
    ┣ 📂.github //이슈,PR 템플릿 등 깃허브 관련 파일 관리
    ┣ 📂.next
    ┣ 📂.vscode
    ┣ 📂.yarn
    ┣ 📂api //axios 라이브러리 기반으로 비동기 통신하는 함수들, axios instance 파일로 구    성
    ┣ 📂apiHooks //api의 함수들을 이용하여 react-query를 반환하는 함수들로 구성
    ┣ 📂components //페이지를 구성하는 컴포넌트들로 구성
    ┃ ┣ 📂common // 공통적으로 사용하는 컴포넌트
    ┃ ┣ 📂handleinfo // 전화번호, 배송지 최초등록 페이지에서 사용하는 컴포넌트 
    ┃ ┣ 📂layout // app.tsx에서 사용하는 레이아웃 컴포넌트
    ┃ ┣ 📂matching // 매칭중/매칭완료 페이지에서 사용하는 컴포넌트
    ┃ ┣ 📂myBuy // 내판매 페이지에서 사용하는 컴포넌트 
    ┃ ┣ 📂myInfo // 내정보 페이지에서 사용하는 컴포넌트 
    ┃ ┣ 📂mySell // 내구매 페이지에서 사용하는 컴포넌트 
    ┃ ┣ 📂offer // 가격 제시 및 구매 페이지에서 사용하는 컴포넌트
    ┃ ┣ 📂profile // 유저 정보를 불러오는 컴포넌트
    ┃ ┣ 📂sell // 판매글 관련 페이지에서 사용하는 컴포넌트 
    ┃ ┣ 📂suggests // 구매 제안 목록 페이지에서 사용하는 컴포넌트  
    ┃ ┗ 📜index.d.ts // .git export를 위한 파일
    ┣ 📂constants // 환경변수 및 상수 파일을 저장하는 폴더
    ┣ 📂hooks // 리액트를 기반으로 자주 사용되는 커스텀 훅들로 구성
    ┣ 📂mocks // msw라이브러리를 통한 서버 모킹을 위한 파일들로 구성
    ┣ 📂pages // 페이지 컴포넌트들로 구성
    ┃ ┣ 📂handleinfo
    ┃ ┃ ┣ 📜adddelivery.tsx // 전화번호 최초등록
    ┃ ┃ ┗ 📜addphonenumber.tsx // 배송지 최초등록
    ┃ ┣ 📂login
    ┃ ┃ ┣ 📜check.tsx // 로그인 성공 페이지
    ┃ ┃ ┗ 📜index.tsx // 로그인 요청 페이지
    ┃ ┣ 📂matching
    ┃ ┗ 📜[id].tsx // '매칭 중인 목록','매칭 완료 목록 페이지
    ┃ ┣ 📂my // GNB 페이지
    ┃ ┃ ┣ 📜alarm.tsx // 내알람 페이지
    ┃ ┃ ┣ 📜buy.tsx // 내구매 페이지
    ┃ ┃ ┣ 📜info.tsx // 내정보 페이지
    ┃ ┃ ┣ 📜infoFix.tsx // 내정보 수정 페이지
    ┃ ┃ ┗ 📜sell.tsx // 내판매 페이지
    ┃ ┣ 📂offer //  가격 제시 페이지
    ┃ ┣ 📂profile // 유저 정보 페이지
    ┃ ┣ 📂sell // 판매글 관련 페이지
    ┃ ┣ 📂suggests // 구매 제안 목록 페이지
    ┃ ┣ 📜_app.tsx
    ┃ ┣ 📜_document.tsx
    ┃ ┗ 📜index.tsx
    ┣ 📂public // 정적 이미지 에셋들을 저장하는 폴더
    ┣ 📂recoil // recoil로 관리할 상태로 구성
    ┣ 📂styles // 전역 스타일 및 여러 컴포넌트에서 공유하는 스타일 파일을 저장하는 폴더
    ┃ ┣ 📜globalStyle.ts
    ┃ ┗ 📜theme.ts
    ┣ 📂types // 여러 컴포넌트에서 공통적으로 사용되는 타입들로 구성
    ┃ ┣ 📂axios // 정적 이미지 에셋들을 저장하는 폴더
    ┃ ┣ 📂recoil // recoil로 관리할 상태로 구성
    ┃ ┣ 📜container.ts // children interface 타입 지정
    ┃ ┗ 📜page.d.ts // AppLayout 타입 지정
    ┣ 📂utils //여러 컴포넌트에서 사용되는 유틸함수들로 구성
    ┃ ┗ 📜price.ts // 가격에 1000단위마다 ,(콤마) 찍히도록하는 유틸함수
    ┣ 📜.babelrc
    ┣ 📜.eslintrc.json
    ┣ 📜.gitignore
    ┣ 📜.pnp.cjs
    ┣ 📜.pnp.loader.mjs
    ┣ 📜.prettierrc
    ┣ 📜.yarnrc.yml
    ┣ 📜README.md
    ┣ 📜next-env.d.ts
    ┣ 📜next.config.js
    ┣ 📜package.json
    ┣ 📜tsconfig.json
    ┗ 📜yarn.lock
 
** 이걸 어떻게 하나하나 다 작성하냐구요...? 저도 했으니 여러분도 할 수 있습니다^^ (힘들어 죽을거같아요....)

### 🤝 Dependencies

<pre><code> 
  "dependencies": {
    "@tanstack/react-query": "^4.20.4",
    "@testing-library/jest-dom": "^5.14.1",
    "@testing-library/react": "^13.0.0",
    "@testing-library/user-event": "^13.2.1",
    "@types/jest": "^29.2.4",
    "@types/react-dom": "^18.0.9",
    "axios": "^1.2.1",
    "next": "12",
    "react": "^18.2.0",
    "react-daum-postcode": "^3.1.1",
    "react-dom": "^18.2.0",
    "react-is": "^18.2.0",
    "react-slick": "^0.29.0",
    "recoil": "^0.7.6",
    "slick-carousel": "^1.8.1",
    "styled-components": "^5.3.6",
    "styled-reset": "^4.4.4",
    "supports-color": "^9.3.1",
    "typescript": "^4.9.4",
    "web-vitals": "^2.1.0"
  },
  "devDependencies": {
   "@svgr/webpack": "^6.5.1",
    "@types/eslint": "^8",
    "@types/node": "^18.11.17",
    "@types/prettier": "^2",
    "@types/react": "^18",
    "@types/react-slick": "^0.23.10",
    "@types/slick-carousel": "^1",
    "@types/styled-components": "^5.1.26",
    "@typescript-eslint/eslint-plugin": "^5.47.0",
    "@typescript-eslint/parser": "^5.47.0",
    "@yarnpkg/sdks": "^3.0.0-rc.34",
    "babel-plugin-styled-components": "^2.0.7",
    "eslint": "^8.30.0",
    "eslint-config-prettier": "^8.5.0",
    "eslint-plugin-import": "^2.26.0",
    "eslint-plugin-jsx-a11y": "^6.6.1",
    "eslint-plugin-prettier": "^4.2.1",
    "eslint-plugin-react": "^7.31.11",
    "eslint-plugin-react-hooks": "^4.6.0",
    "prettier": "^2.8.1"
  }


</code></pre>

### ⭐️핵심 기능 구현

노션사이트 바로가기 or 추가 설명 및 기능 아키텍처 유아이 첨부

### 웹기초의 💙 README.md

### 🙌팀원 소개

|**본인을 표현할 수 있는 사진과 깃헙 링크**|본인을 표현할 수 있는 사진과 깃헙 링크|본인을 표현할 수 있는 사진과 깃헙 링크|본인을 표현할 수 있는 사진과 깃헙 링크|
|:---:|:---:|:---:|:---:|
|🧚🏻Web BA|👼Web BA|👼Web BA|😽Web BA|

### 📂Directory Structure

폴더 구조와 폴더 설명 작성해주세요.

### ⭐️핵심 기능 

노션사이트 바로가기 or 추가 설명 및 기능 아키텍처 유아이 첨부

