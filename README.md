# 🌌 Practice React, TypeScript, Redux with News API

## 👀 Libraries

| 라이브러리               | 버전       |
| ------------------------ | ---------- |
| react (with 🎣**Hooks**) | **^16.11** |
| react-dom                | **^16.11** |
| react-router             | **^5.1**   |
| react-scripts            | **3.3**    |
| styled-components        | **^4.4**   |
| typescript               | **3.6**    |
| antd                     | **4.1.5**  |

## News API
https://newsapi.org/

# 11기 2차 프로젝트: StockX 클론코딩(front-end)

## 프로젝트 소개 및 목적

- 소개: News API를 사용하여 Redux와 TypeScript를 연습해보려는 Toy project 🧸

면접 과제로 받았던 테스트인데 2일 이라는 짧은 시간에 구현하려다보니 코드가 너무 지저분했고 리펙토링도 하지 못했다.
아쉬움이 많이 남아서 공부도 할 겸 천천히 이것 저것 시도해볼 예정!

- 목적
  1. TypeScript에서 요구하는 모든 타입을 타이핑 한다.
  2. React: 함수형 React 컴포넌트, Hook을 사용하여 데이터 통신, 컴포넌트 분리 및 관리, 컴포넌트 간 데이터 바인딩을 적용해 본다.
  3. Effect Hook을 깊게 이해한다.
  4. Network: fetch나 axios를 사용하여 서버 api에 요청하고 응답받은 데이터를 화면에 보여준다.
  5. 상태값을 Redux로 전역관리한다.
  6. 미들웨어를 사용해본다.
  
- 기능 구현 목표
  1. 사용자가 검색어를 입력하면, News API를 이용해 기사를 검색하고, 결과를 보여준다.
    - https://newsapi.org/
  2. 검색 결과의 양에 따라, 페이지네이션 기능이 있어햐 한다. (페이지 버튼 혹은 유저의 스크롤)
  3. 기사 클릭시, 새로운 탭을 열어 해당 페이지로 이동해야 한다.
   - 기사 리스트는 다음 항목을 포함한다.
     - 제목
     - 내용 (컨텐츠가 많은 경우 일부만 표현)
     - Thumbnail Image
     - 작성자
     - 작성날짜
     - 출처
  4. 로그인 기능
    - 서버와의 연동이 아닌 브라우저 내에서 입력한 ID, Password 검증을 통해 로그인 여부를 판단한다.
    - 테스트 계정
      - ID : seobie
      - PW : seobie123
    - 테스트 계정으로만 로그인 가능
    - 로그인 여부에 따른 기능 구현
      - 로그인 : 기사검색 및 즐겨찾기 기능
      - 로그아웃 : 기사검색만 가능
    - 기사 정렬
      - 정렬 방식은 작성 날짜 혹은 출처를 기준으로 한다. (API 자체 기본값은 최신순)
      - 페이지네이션과 동시에 구현이 어려운 경우 해당 페이지에 한해 기능을 구현
    - 특정 기사 즐겨찾기 기능
      - 특정 기사를 즐겨찾기에 추가 혹은 즐겨찾기에서 삭제할 수 있어야 한다. (브라우저의 즐겨찾기가 아님)
      - 즐겨찾기에 추가한 기사들은
        - 즐겨찾기 페이지에서 확인 가능
        - 웹페이지 재접속시에도 그 내역이 유지
      - 저장한 기사에 한해, 기사 내용을 직접 수정할 수 있다.
        - 즐겨찾기 페이지에서, 사용자가 특정 기사 편집 버튼을 클릭하면 내용을 수정하고 저장할 수 있다.
    
  

## 개발 기간

- 2020년 11월 6일 ~ 🤷🏻‍♂️

## 개발 인원

- 1명 🙋🏻‍♂️

## 구현 페이지 및 기능

### 기술 스택

- HTML5, CSS3, JavaScript, TypeScript
- React/Hooks, Styled-Components

### 구현 기능

- 아직..
