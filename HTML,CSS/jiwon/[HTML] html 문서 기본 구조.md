# html 문서 기본 구조

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## DOCTYPE

```html
<!DOCTYPE html>
```

- html 문서 맨 처음에 명시해서 이 문서의 버전을 나타냅니다.
- 반드시 작성해줘야 합니다.
- <!DOCTYPE html>은 HTML5버전을 나타냅니다

## HTML

```html
<html lang="en">
  
</html>
```

- 이 문서가 html로 작성됐음을 브라우저에게 알립니다.
- 문서의 시작과 끝을 알리는 태그입니다.
- lang 속성으로 문서의 언어를 설정할 수 있습니다.

## Head

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
```

- 메타 데이터와 타이틀을 넣어주는 곳입니다.
- 메타 데이터는 웹 페이지에서 직접적으로 보이지는 않지만 페이지 인코딩 방식이나 검색엔진에 관한 정보 등, 많은 설정들을 할 수 있습니다.
- 타이틀은 브라우저 창 제목에 나타납니다.

## Body

```html
<body>
    
</body>
```

- 주로 브라우저 화면에 보이는 것이 들어갑니다.
- HTML 문서의 이미지, 리스트, 비디오 등과 같은 모든 콘텐츠를 나타내는데 사용됩니다.
- HTML 문서에서 단 하나의 ```<body>``` 만이 존재 합니다.
  

## link

- 현재 문서와 외부 리소스의 관계를 명시합니다.
- CSS를 연결할 때 제일 많이 사용하지만, 사이트 아이콘("파비콘"과 홈 화면 아이콘) 연결 등 여러 가지로 쓰일 수 있습니다.

## meta

`base`, `link`, `script`, `style`, `title`과 같은 다른 메타 관련 요소로 나타낼 수 없는 Metadata를 나타냅니다.

## title

`브라우저의 제목 표시줄`이나 페이지 탭에 보이는 `문서 제목`을 정의합니다.

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)