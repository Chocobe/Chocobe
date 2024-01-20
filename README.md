### 안녕하세요! 4년차 Front-End 개발자 입니다. 👋

* Nextjs 를 메인 프레임워크로 개발중 입니다.
* Nextjs 스터디는 참고 자료의 저작권에 의해, 당분간 `Github` 대신 `Notion` 을 활용합니다. (비공개)
* [블로그 v2 (개발중)](https://chocobe.github.io)

<br />

* 🏙 Deepnatural 에서 Front-End 를 담당하고 있습니다.
    * `NextJS` 환경의 신규 서비스 개발
        * 생성형 AI 서비스, `Lave` 프로젝트를 개발중 입니다.
        * 학습 데이터 구축을 위한 `레이블러 콘솔 v2` 를 개발 (`Lave` 개발을 위해 개발 중지 상태)
    * `데이터 가공 작업도구` 개발
        * `NextJS` 환경의 작업도구 개발
        * `Vue 2` 환경의 작업도구 개발
* 🤗 `React` 와 `Typescript` 를 좋아합니다.
* 🤔 요즘은 코드의 가독성 & 전달력 을 높일 수 있도록 `Custom Hook (React)`, `Composable (Vue)` 설계에 대한 고민중 입니다.
* 🫠 2024년에는 `Three.js` 스터디와 블로그 Profile 페이지를 3D 로 구현하는 것을 목표중 하나로 선정하였습니다.

<br />

### Skill

* 언어: <img src="https://img.shields.io/badge/Javascript----blue"> <img src="https://img.shields.io/badge/Typescript----blue">
* 프레임워크: <img src="https://img.shields.io/badge/Vue-2-brightgreen"> <img src="https://img.shields.io/badge/Vue-3-brightgreen"> <img src="https://img.shields.io/badge/React----brightgreen"> <img src="https://img.shields.io/badge/Nextjs----brightgreen">
* 비동기처리: <img src="https://img.shields.io/badge/RxJS----green">
* 다국어: <img src="https://img.shields.io/badge/i18next----ff1493">
* 테스트유닛: <img src="https://img.shields.io/badge/Jest----red"> <img src="https://img.shields.io/badge/VueTestUtils----red">
* 비전개발: <img src="https://img.shields.io/badge/Canvas----lightgrey"> <img src="https://img.shields.io/badge/SVG----lightgrey">
* 다이어그램 툴: <img src="https://img.shields.io/badge/Mermaid.js----f0f400">

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Chocobe&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

<br />

### 자격증

* 정보처리기사 (2019. 8. 16 취득)

<br />

### 경력 (4년차)

### Deepntarual: 2021. 08 ~ 재직중

* 근무 지역: 서울 신논현

<br />

1. **(개발중) 신규 서비스, `Lave`**
    * [Lave 링크: https://lave.ai](https://lave.ai)
    * 생성형 AI 서비스
        * 챗봇 서비스
        * 한복 프로필 이미지 생성 서비스
    * 프레임워크: `Nextjs`
    * 상태관리: `@reduxjs/toolkit`, `redux-saga`
    * 스타일시트: `styled-components`
    * UI 프레임워크: `@chakra-ui`
    * 현재 구현된 기능
        * 새로운 상태관리 구조 고안 및 적용
            * API state: `Redux`
            * Layout state: `React Context API`
        * `Google Oauth2` 연동 및 `인증 Token` 상태 관리
        * `i18next` 와 `dayjs` 연동으로 다국어 지원 기능 강화
        * `redux-saga` 를 사용하여 주기적인 데이터 조회 `polling` 기능 구현
        * `Google Analytics 4` 연동
        * 챗봇 서비스 개발 완료 및 출시
   ---
3. **(개발중지) 신규 서비스, `레이블러 콘솔 v2` 구현**
    * 신규 서비스를 구현하며, 장기적으로는 기존의 `Vue2` 플랫폼의 마이그레이션 까지 예정 입니다.
    * 프레임워크: `Nextjs`
    * 상태관리: `@reduxjs/toolkit`, `redux-saga`
    * 스타일시트: `styled-components`
    * UI 프레임워크: `@chakra-ui`
    * 현재 구현된 기능
        * 서버 응답에 따라 동적으로 입력 요소 렌더링
        * 중첩 레이아웃 및 레이아웃 조합
        * `accessToken` 및 `refreshToken` 을 활용한 세션 유지
        * `i18next` 와 `Google Spreadsheet` 를 사용한 `다국어`
        * `styled-components` 에 `디자인 시스템` 적용
        * `Github actions` 를 사용한 `CI/CD`
    ---
4. **모바일 광고 메시지 수집 작업도구 구현**
    * 텍스트를 수집하는 작업도구 입니다.
    * 프레임워크: `Nextjs`
    * 주요 기능
        * 텍스트 입력
        * 유형 카테고리 선택 (예: 통신사, 보험)
    ---
5. **심전도 그래프 라벨링 작업도구 구현**
    * 심전도 그래프 라벨링 작업도구 입니다.
    * 프레임워크: `Vue2`
    * 주요 기능
        * `Y 축` 좌표값 데이터를 `SVG 그래프` 로 변환
        * `SVG 그래프` 의 특정 좌표 선택
        * 선택한 `Y축` 태깅
        * 태그 제약조건 (예: `T_on 라벨` - `T_off 라벨` 의 순서)
        * 그래프의 `X축`, `Y축` 개별 `확대/축소`
        * 그래프 `X축` 이동
        * 그리드 배경
    ---
6. **이미지 수집 작업도구 구현**
    * 복수의 사진 업로드 작업도구 입니다.
    * 프레임워크: `Nextjs`
    * 주요 기능
        * 이미지 최대 사이즈
        * 개별 이미지 업로드 진행률에 대한 `로딩바` 제공
        * 업로드 실패 시, 해당 이미지들만 일괄 재업로드
        * 모든 이미지 업로드 완료 시, 제출 가능
    ---
7. **기계독해 작업도구 구현**
    * 숫자, 날짜 연산 및 원문의 특정 택스트 추출 작업도구 입니다.
    * 프레임워크: `Vue2`
    * 주요 기능
        * 숫자의 자리수(쉼표) 표기
        * 숫자를 한글로 변환 (예: 1억 2천 3백)
        * 작업자가 입력한 `수식(텍스트)` 를 함수로 변환하여 연산 (예: `a * (a / b)`, `(a - b) / (a + b)`)
        * 원문 클릭 시, `완전한 문장` 으로 추출
        * 원문에 존재하는 모든 숫자에 `하이라이트`
    ---
8. **`Canvas API` 를 이용한 `Line` 기능 추가**
    * `Canvas API` 로 구현된 작업도구에 `Line` 을 그리는 기능을 추가 하였습니다.
    * 프레임워크: `Vue2`
    * 주요 기능
        * `Line` 의 좌표값 추출
        * 확대/축소 에 대한 좌표값 보정
    ---
9. **작업도구 공용 단축키 구현 (제출, 검수, 반려, 보류 등..)**
    * `Rxjs` 를 사용하여 observer 패턴 사용
    * 프레임워크: `Vue2`
    * 주요 기능
        * 상황별 단축키 Observer 구독 및 해제
    ---
10. **감성분류2 작업도구 구현**
    * 화자의 발화에 대하여 어떠한 감성인지 분류하는 작업도구 입니다.
    * 프레임워크: `Vue2`
    * 주요 기능
        * `원문에서 특정 발화 선택 -> 감성 태그 선택` 으로 각 발화에 대한 감성을 지정합니다.
        * 발화에 감성 선택 시, 다음 미지정 발화 자동 선택
        * 방향키를 이용한 발화 선택 가능
        * 단축키로 발화 선택 가능
        * 선택한 발화가 화면 중앙에 위치하도록 자동 스크롤 이동
        * 감성 분류가 누락될 시, 제출 불가
    ---
11. **감성분류1 작업도구 구현**
    * 원문의 부분 택스트에 태그를 하여, 해당 텍스트의 `태그`, `텍스트`, `start/end index` 를 추출하는 작업도구 입니다.
    * 프레임워크: `Vue2`
    * 주요 기능
        * `원문의 부분 텍스트 드래그 -> 태그 선택` 으로 원문에 태그 삽입
        * 태그를 지정한 텍스트는 다음과 같은 구성으로 가공 합니다.
            * `text`: 원문에서 선택한 텍스트
            * `start`: 원문 기준, 텍스트의 시작 `index`
            * `end`: 원문 기준, 텍스트의 끝 `index`
    ---
12. **문서분류 작업도구 구현**
    * 원문을 읽고, `주제`, `인물`, `조직/기관`, `제품` 에 대한 분류 작업도구 입니다.
    * 프레임워크: `Vue2`
    * 주요 기능
        * 태그 클릭으로 문서에 대한 상세 분류 작성
        * 태그 카테고리는 `통합 태그` 와 `하위 태그` 로 구성되며, `통합 태그` 선택/해제 시, `하위 태그` 일관 선택/해제
        * 각 태그 카테고리의 개수 제한
    ---
13. **자유대화1 작업도구 구현**
    * 원문을 읽고, 작업자는 화자 2명의 대화를 창작하는 작업도구 입니다.
    * 프레임워크: `Vue2`
    * 주요 기능
        * 발화 입력 기능
        * 교차 대화 방식을 위한 화자의 턴 변경 (자동)
        * 발화 사이에 지정된 태그 입력 (태그 목록 클릭)
        * 화자의 턴 개수에 대한 제출 조건 (미충족 시, 제출불가)
        * 특정 태그에 한해 사용 개수 제한 및 제출 조건 (미충족 시, 제출불가)
        * 각 발화의 `trim` 보정

<br />

[[-Project-study-time-checking]](https://github.com/Chocobe/-Project-study-time-checking) 토이 프로젝트: 2022. 05. 10 ~ 2022. 05.29

<br />

### 제르메스: 2020. 04 ~ 2021. 04 (1년)

* 근무 지역: 부산 사상

<br />

1. MES (생산 관리 시스템) 구현 (Vue2)
2. 회사 홈페이지 구현 (Vue2)

<br />

### 최근 관심사

* ``Nextjs`` 에 관심이 있으며 `SEO` 에 초점을 둔 블로그 개발을 진행하며 SSR, CSR, SSG 를 혼합하여 사용해보고 있습니다.
* 단일 기능의 Custom Hook 으로 분리하여 구현, 조합하는 방식을 시도중입니다.
* `Three.js` 스터디를 진행중이며, 3D 인터렉션 블로그 구현을 첫번째 목표로 세웠습니다.
