# 가상 클래스와 가상 요소

### 가상 클래스(Pseudo-Class)

- 별도의 class를 지정하지 않아도 지정한 것처럼 요소를 선택할 수 있습니다. 
- `의사 클래스` 라고도 부릅니다.

### 가상 요소(Pseudo-Element)

- 가상 클래스처럼 선택자(selector)에 추가되며, 존재하지 않는 요소를 존재하는 것처럼 부여하여 문서의 특정 부분 선택이 가능합니다.
- `의사 요소` 라고도 부릅니다.


## 가상 클래스(Pseudo-Class) 의사 클래스

|Selector|description|
|:-:|:-:|
|:hover|마우스를 **롤오버** 했을 때|
|:active|마우스를 **클릭**했을 때 |
|:focus|input 태그 등이 **포커스** 되었을 때|
|:first-of-type|모든 자식 요소 중 **첫 번째**에 등장하는 특정 **요소**를 선택|
|:last-of-type|모든 자식 요소 중 **마지막**으로 등장하는 특정 **요소**를 선택|
|:first-child|모든 자식 요소 중 **첫 번째**에 위치하는 **자식**을 선택|
|:last-child|모든 자식 요소 중 **마지막**에 위치하는 **자식**을 선택|

<br>

### ❗:first-child와 first-of-type 비교❗

아래와 같이 코드를 작성한다고 가정합니다.
![](https://velog.velcdn.com/images/qorjiwon/post/a07f3ae0-53eb-4623-aedf-98e7e2b627cf/image.png)

#### 결과는?

![](https://velog.velcdn.com/images/qorjiwon/post/18ae0623-3e5b-46aa-98f8-8a4584204e94/image.png)

parent의 첫 번째 자식은 span이므로 아래 코드는 실행되지 않습니다.

```css
.parent p:first-child {
	color: lightpink;
}
```

따라서 아무 글자도 lightpink가 되지 않습니다.

반면, first-of-type은 p 타입 중 첫 번째 요소를 얘기하므로 parent의 p 타입 자식은

```html
<p>B<p>
```

와

```html
<p>C<p>
```

이고, 이 중 첫 번째 요소인 B 글자의 색이 lightskublue가 됩니다.

## 가상 클래스

|Selector|description|
|:-:|:-:|
|::before|요소의 콘텐츠 시작부분에 생성된 콘텐츠를 추가합니다.|
|::after|요소의 컨텐츠 끝 부분에 생성된 콘텐츠를 추가합니다.|
|::selection|마우스 드래그로 선택한 텍스트 콘텐츠 영역을 선택합니다.|
|::marker|목록 아이템 앞에 붙는 마커를 선택합니다.|
|::first-letter|현재 웹 브라우저에 보이는 상태를 기준으로 요소의 텍스트 콘텐츠 첫 글자를 선택합니다.|
|::first-line|현재 웹 브라우저에 보이는 상태를 기준으로 요소의 텍스트 콘텐츠 첫 줄 내용을 선택합니다.|

### 예시

![](https://velog.velcdn.com/images/qorjiwon/post/5f1d273c-a166-4541-a70b-3468af11a370/image.png)

::before와 ::after는 반드시 `content`와 같이 쓰여야 하며, 이 content 는 ‘가짜’ 속성입니다. 

HTML 문서에 정보로 포함되지 않은 요소를 CSS에서 새롭게 생성시켜주는 역할을 합니다.

#### 결과

![](https://velog.velcdn.com/images/qorjiwon/post/bf5f1dcb-2513-4017-8c68-34634df22cf6/image.png)


---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)

- [의사 요소](https://developer.mozilla.org/ko/docs/Web/CSS/Pseudo-elements)