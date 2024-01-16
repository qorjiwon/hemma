# 시맨틱 태그(Semantic Tag) 에 대해서

## Semantic 요소란?
![](https://velog.velcdn.com/images/qorjiwon/post/4f1bd37c-94c5-4317-96ab-c359e0c6f6b9/image.png)
<br>
Semantic은 의미론의 라는 뜻으로
Semantuc Element는 `의미가 있는 요소`를 말하며 `브라우저와 개발자 모두에게 의미를 명확하게 설명`합니다.

#### Non-Semantic 요소의 예
```<div>``` 및 ```<span```은 내용에 대해 아무것도 알려주지 않습니다.
이 태그들의 이름만 보고는 어떠 내용인지 유추할 수 없습니다.

#### Semantic 요소의 예
```<form>```, ```<article>``` 및 ```<table>```은 내용을 명확하게 정의합니다.

## HTML에서 사용되는 Semantic 요소들
```html
<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>
```
![](https://velog.velcdn.com/images/qorjiwon/post/89718869-376d-4be4-8bcc-2e0ceb308fd7/image.png)


### 1. header
주로 제목과 소개 내용을 포함합니다.
요소에는 일반적으로 다음이 포함됩니다.

- 하나 이상의 제목 요소 (h1 ~ h6)
- 로고 또는 아이콘
- 저작권 정보
- 작성자 이름
...

>참고 : 하나의 HTML 문서에는 여러 `<header>`요소가 사용될 수 있지만, `<footer>`와 `<address>` 또는 다른 `<header>` 안에는 배치될 수 없습니다.

  
### 2. secition
문서의 섹션을 정의합니다.

W3C의 HTML 문서에 따르면,
`섹션은 일반적으로 제목이 있는 주제별 콘텐츠 그룹입니다.`

```<section>``` 요소를 사용할 수 있는 위치의 예:
- 장
- 소개
- 뉴스 항목
- 연락처 정보

### 3. main
body의 주요 콘텐츠를 나타냅니다.
주요 콘텐츠 영역은 문서의 핵심 주체나 앱의 핵심 기능에 직접적으로 연결됐거나 확장하는 콘텐츠로 이루어집니다.

### 4. nav
네비게이션 링크 정의합니다.
주로 목차, 메뉴 등에 사용됩니다.

### 5. footer
문서 또는 섹션의 바닥글을 정의합니다.

```<footer>``` 요소에는 일반적으로 다음이 포함됩니다.
- 저작권 정보
- 연락처 정보
- 사이트맵

### 6. article
문서, 페이지, 애플리케이션, 또는 사이트 안에서 **독립적으로 구분**하여 배포하거나 재사용할 수 있는 구획을 나타냅니다.

### 7. aside
문서의 주요 내용과 간접적으로만 연관된 부분을 나타냅니다.
주로 사이드바 혹은 콜 아웃 박스로 표현합니다.

### 8. details
사용자가 보거나 숨길 수 있는 추가 세부 정보를 정의합니다.

예시
>
```html
<details>
  <li>detail 1</li>
  <li>detail 2</li>
  <li>detail 3</li>
</details>
```
<details>
  <li>detail 1</li>
  <li>detail 2</li>
  <li>detail 3</li>
</details>

### 9. figcaption
```<figure>``` 요소의 캡션(표제, 제목, 머리말)을 정의합니다.

### 10. figure
일러스트, 다이어그램, 사진, 코드 목록 등 자체 콘텐츠를 지정합니다.

### 11. mark
표시/하이라이트된 텍스트를 정의합니다.

### 12. summary
```<details>```요소에 대한 가시적인 표제를 정의합니다.

### 13. time
```<time>``` 날짜 및 시간을 정의합니다.

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)