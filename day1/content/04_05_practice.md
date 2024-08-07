# HTML & CSS를 사용한 정적인 자기소개 페이지 만들기

## 목차
- [HTML \& CSS를 사용한 정적인 자기소개 페이지 만들기](#html--css를-사용한-정적인-자기소개-페이지-만들기)
  - [목차](#목차)
  - [목차](#목차-1)
  - [1. 프로젝트 소개](#1-프로젝트-소개)
    - [필수 요소:](#필수-요소)
  - [2. HTML 기초](#2-html-기초)
    - [HTML 기본 구조](#html-기본-구조)
    - [주요 태그](#주요-태그)
  - [3. CSS 기초](#3-css-기초)
    - [CSS 기본 문법](#css-기본-문법)
    - [주요 속성](#주요-속성)
  - [4. 자기소개 페이지 만들기](#4-자기소개-페이지-만들기)
    - [4.1 HTML 작성](#41-html-작성)
      - [힌트](#힌트)
    - [4.2 CSS 작성](#42-css-작성)
      - [힌트](#힌트-1)
    - [4.3 파일 구조](#43-파일-구조)
  - [5. 마무리](#5-마무리)
  - [다음](#다음)

---

이 실습에서는 HTML과 CSS를 사용하여 기본적인 자기소개 페이지를 만드는 방법을 배웁니다. 실습을 통해 사진, 메뉴바 등을 포함한 다양한 요소를 배치해볼 것입니다.

## 목차
1. 프로젝트 소개
2. HTML 기초
3. CSS 기초
4. 자기소개 페이지 만들기
5. 마무리

---

## 1. 프로젝트 소개
이번 실습에서는 자기소개 페이지를 만들어 봅니다:

### 필수 요소:
- **메뉴바**: Home, About, Contact 메뉴
- **프로필 사진**: 자기소개 사진
- **소개 문구**: 간단한 자기소개
- **배경색**: CSS로 설정

---

## 2. HTML 기초

### HTML 기본 구조
HTML은 웹 페이지의 구조를 정의하는 마크업 언어입니다. 모든 HTML 문서는 기본적인 구조를 가지고 있습니다. 다음은 HTML 문서의 기본적인 골격입니다.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>자기소개 페이지</title>
</head>
<body>
    <!-- 여기에 내용을 작성합니다 -->
</body>
</html>
```

### 주요 태그
- `<!DOCTYPE html>`: HTML5 문서 선언
- `<html>`: HTML 문서의 루트 요소
- `<head>`: 메타데이터 포함 (문서 제목, CSS 링크 등)
- `<body>`: 실제 내용이 들어가는 부분

---

## 3. CSS 기초

### CSS 기본 문법
CSS는 HTML 요소의 스타일을 정의하는 데 사용됩니다. CSS 파일은 `.css` 확장자를 가지며, HTML 파일과 연결하여 사용합니다.

```css
/* styles.css 파일 */
body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
}

h1 {
    color: #333;
    text-align: center;
}
```

### 주요 속성
- `background-color`: 배경색 설정
- `font-family`: 폰트 설정
- `color`: 글자색 설정
- `text-align`: 텍스트 정렬

---

## 4. 자기소개 페이지 만들기

### 4.1 HTML 작성

아래의 내용을 참고하여 HTML 파일을 작성합니다.

1. **HTML 파일 생성**: `index.html`
2. **헤더 추가**: 제목, 메타데이터, CSS 파일 링크 추가
3. **메뉴바 추가**: 네비게이션 바를 추가하여 Home, About, Contact 메뉴 생성
4. **섹션 추가**: Home, About, Contact 섹션 추가

#### 힌트
- `<nav>` 태그와 `<ul>`, `<li>` 태그를 사용하여 메뉴바를 만드세요.
- `<section>` 태그를 사용하여 각 섹션을 만드세요.
- `<img>` 태그를 사용하여 프로필 사진을 추가하세요.

### 4.2 CSS 작성

아래의 내용을 참고하여 CSS 파일을 작성합니다.

1. **CSS 파일 생성**: `styles.css`
2. **기본 스타일 설정**: 배경색, 폰트, 기본 마진 및 패딩 제거
3. **메뉴바 스타일**: 배경색, 텍스트 색상, 레이아웃 설정
4. **섹션 스타일**: 텍스트 정렬, 패딩 설정
5. **이미지 스타일**: 크기, 원형으로 만들기

#### 힌트
- `nav`와 `ul`, `li` 태그에 스타일을 적용하여 메뉴바를 꾸미세요.
- `section` 태그에 패딩과 텍스트 정렬 스타일을 적용하세요.
- `img` 태그에 크기와 모양을 조절하는 스타일을 적용하세요.

### 4.3 파일 구조
```
project-folder/
│
├── index.html
└── styles.css
└── profile.png
```

---

## 5. 마무리
이제 브라우저에서 `index.html` 파일을 열어 결과를 확인해봅니다. 실습을 통해 HTML과 CSS에 익숙해지기를 바랍니다.

---
## [다음](./06_JS_기초.md)