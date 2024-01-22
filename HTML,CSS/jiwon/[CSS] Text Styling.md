# Text Styling

## 텍스트 색상: color

`텍스트 색상을 지정`하는데 사용됩니다. blue와 같은 명명된(named) 색상, `#ff0000`와 같은 색상 코드, 그리고 `rgb()`, `hsl()`과 같은 색상 함수도 사용할 수 있습니다.

## 텍스트 크기: font-size

`텍스트의 크기를 조절`할 때 사용합니다. `pt`나 `px`와 같은 **절대 단위**를 사용할 수도 있고 `rem`나 `em`과 같은 **상대 단위**를 사용할 수도 있습니다. 다양한 크기의 화면을 지원하기 위한 적응형(adaptive) 웹디자인을 할 때는 일반적으로 상대 단위가 유리합니다.

## 텍스트 글꼴: font-family

`텍스트의 글꼴 또는 서체를 변경`할 때 사용합니다. 속성값으로 사용자의 컴퓨터에 미리 설치된 시스템 폰트나 웹에서 다운로드 받을 수 있는 웹폰트를 사용할 수 있습니다.

### e.g

```css
p:first-of-type {
  font-family: serif;
}

p:last-of-type {
  font-family: monospace;
}
```

### font-family 글꼴 스택

```css
font-family: Roboto, Verdana, Arial;
```

`글꼴 스택` : Roboto를 사용할 수 없는 경우 Verdana로, Verdana를 사용할 수 없는 경우 Arial로 대체됩니다.

## 텍스트 굵기: font-weight

`텍스트의 굵기를 조정`할 때 사용합니다. `300`과 같은 숫자나 `bold`와 같은 키워드를 속성값으로 사용할 수 있습니다. 사용하는 글꼴에서 해당 텍스트 굵기를 지원하지 않으면 브라우저에서 임의로 효과를 만들어주는데 부자연스러운 경우가 있습니다.

## 텍스트 스타일: font-style

`기본체에서 약간 변형된 스타일을 사용`하고 싶을 때 사용합니다. font-weight 속성과 마찬가지로 사용하는 글꼴에서 해당 스타일을 지원하지 않으면 브라우저에서 임의로 효과를 적용합니다.

## 텍스트 장식: text-decoration

`text-decoration` 속성을 사용해서 `텍스트에 간단한 장식`을 추가할 수 있습니다. 보통 텍스트에 `밑줄(underline)`이나 `취소선(line-through)`을 그리기 위해서 사용합니다.

## 텍스트 변형: text-transform

`text-transform` 속성을 이용해서 `텍스트의 대소문자 변환`과 같은 간단한 변형을 줄 수도 있습니다.

## 텍스트 정렬: text-align

`좌, 우, 중앙 등 다양한 방향으로 텍스트 정렬`할 수 있습니다.

## 글자 간격: letter-spacing

`글자 간의 간격을 조정`하기 위해서 사용합니다. font-size 속성과 마찬가지로 절대 단위와 상대 단위를 모두 속성값으로 사용할 수 있습니다.

## 행 높이: line-height

`행 높이를 설정`할 때 사용합니다. 특이하게도 `단위없이 숫자로 설정`할 수 있으며 `현재 font-size 값 기준으로 상대값이 적용`됩니다.

예를 들어, 현재 font-size가 16px일 때, line-height를 2로 설정하면, 32px의 행 높이가 설정됩니다. 그리고 em과 같은 상대값으로도 설정이 가능합니다.

## font-family와 글꼴 스택

font-family

```css
font-family: Roboto, Verdana, Arial;
```

글꼴 스택 :Roboto를 사용할 수 없는 경우 Verdana로, Verdana를 사용할 수 없는 경우 Arial로 대체됩니다.

## ☃️ Google Font 사용하기

1. [google font 사이트](https://fonts.google.com/)로 이동
2. 폰트 이름 검색
3. 구글에서 제공하는 code 복사

### e.g.

#### html

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100&display=swap" rel="stylesheet">
```

#### css

```css
font-family: 'Noto Sans KR', sans-serif;
```

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)

- [텍스트 스타일링을 위한 10가지 CSS 속성](https://www.daleseo.com/css-typography/)