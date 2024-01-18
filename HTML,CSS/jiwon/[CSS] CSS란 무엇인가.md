#CSS란 무엇인가?

## CSS (Cascading Style Sheets)란?
>CSS는 **사용자에게 문서를 표시하는 방법을 지정**하는 언어입니다. (style, layout 등)
- MDN -

- 웹 사이트에서 화면에 표시되는 정보들을 꾸며줌
- **HTML은 문장의 구조**를 만들고, **CSS는 문장을 브라우저에 어떻게 보여줄 지**를 지정

이렇게 해서 `구조`와 `디자인`이 분리되었습니다.

## CSS를 사용하는 방법 3가지

1. HTML 안에서 Style 속성 이용 (인라인 스타일)
2. ```<style>``` 태그를 통해 HTML 문서 내부에서 이용하는 방법 (내부 스타일 시트)
3. 별도로 CSS 파일을 분리하여 HTML의 문서에 연결하는 방법 (외부 스타일 시트)

### 1. 인라인 스타일

<img src="https://velog.velcdn.com/images/qorjiwon/post/1e1e9a11-d409-4b48-a0a0-4db3bab6ae3b/image.png" width="400">

### 2. 내부 스타일 시트

<img src="https://velog.velcdn.com/images/qorjiwon/post/e5c05eab-0609-4e71-9dac-6845c4740586/image.png" width="250">

### 3. 외부 스타일 시트

<img src="https://velog.velcdn.com/images/qorjiwon/post/13890734-2dbc-402a-91ca-5fd73aaddbb9/image.png" width="400">


## 👑 스타일 적용 우선순위

스타일 적용이 중복될 경우, 우선순위에 따라 적용됩니다.
1. 인라인 스타일
2. 내부&외부 스타일 시트
3. 웹 브라우저 기본 스타일

## CSS 기본 구조

<img src="https://velog.velcdn.com/images/qorjiwon/post/a7503f2c-a75a-402f-83e1-037892f10194/image.png" width="400">

### 선택자 (Selector)

**CSS를 적용할 HTML요소**를 가리킵니다.

### 속성 (Property)

셀렉터가 지정한 위치의 **무엇을 바꿀 것인지** 결정합니다.

### 값

속성에 관한 구체적인 값을 결정합니다.

---

### 📍Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)