# html 기본 태그와 역할

## Heading

Heading 태그는 ```<h1>```~```<h6>```이며, 주로 웹 페이지에 표시하려는 제목으로 사용됩니다.
```<h1>```는 하나의 페이지에서 제일 큰 주제를 위해 한 번만 사용하는게 좋습니다.
![](https://velog.velcdn.com/images/qorjiwon/post/e7ac690c-a5f6-4406-af60-e0d518b7c7d3/image.png)


## Paragraphs

문단을 정의할 때 사용됩니다.
![](https://velog.velcdn.com/images/qorjiwon/post/ea2faa90-bcae-4b79-9c65-e92f7d1cfe6d/image.png)


## Preformatted Text

미리 정의된 형식(preformatted)의 텍스트를 정의할 때 사용합니다. 
요소 내의 텍스트는 시스템에서 미리 지정된 고정폭 글꼴(fixed-width font)을 사용하여 표현되며, 텍스트에 사용된 여백과 줄 바꿈이 모두 그대로 브라우저 화면에 나타납니다. (원래는 공백하나로 인식)
이러한 요소를 사용하면,
독특한 서식의 텍스트나 컴퓨터 코드 등을 HTML 문서에 그대로 표현할 수 있습니다.

![](https://velog.velcdn.com/images/qorjiwon/post/eab0b33b-00e3-4fa0-9215-44f74dd8201d/image.png)

## List

HTML 문서에서 목록을 나타내는 목록 태그이며 크게 3가지로 나누어집니다.

### 순서가 있는 목록 ( Ordered List )

HTML ordered 목록에서 모든 목록 항목은 `기본적으로 숫자`로 표시됩니다.

숫자 항목 오름차순
![](https://velog.velcdn.com/images/qorjiwon/post/084b8771-295c-47a2-843a-fd129f1dafc1/image.png)

5부터 시작 (오름차순)
![](https://velog.velcdn.com/images/qorjiwon/post/dca70c71-bb7c-47b3-bc62-ea7b42cf9dfa/image.png)

내림차순
![](https://velog.velcdn.com/images/qorjiwon/post/be7b5ee4-2e8b-40f1-9ce6-0ff07929de86/image.png)

알파벳 오름차순
![](https://velog.velcdn.com/images/qorjiwon/post/59e5876c-5bc4-4ee0-a719-7fce16d336b0/image.png)

대문자 알파벳 오름차순
![](https://velog.velcdn.com/images/qorjiwon/post/e9cad6f3-60b8-4369-a602-b040e6dce417/image.png)




### 순서가 없는 목록 ( Unordered List )

HTML Unordered 목록에서 모든 목록 항목은 `글머리 기호로 표시`됩니다. 정렬되지 않은 목록은 ```<ul>```태그로 시작하고 목록 항목은 ```<li>``` 태그로 시작합니다.

### 설명 목록 ( Description List )

HTML 설명 목록은 HTML 및 XHTML에서 지원하는 목록 스타일이기도 합니다. 사전이나 백과사전처럼 항목이 나열되는 `정의 목록`이라고도 합니다.

정의 목록은 용어집, 용어 목록 또는 기타 이름-값 목록을 제시할 때 매우 적합합니다.

HTML 정의 목록에는 다음 세 가지 태그가 포함됩니다.

```<dl>``` 태그는 목록의 시작을 정의합니다.

```<dt>``` 태그는 용어를 정의합니다.
```<dd>```태그는 용어 정의(설명)를 정의합니다.
![](https://velog.velcdn.com/images/qorjiwon/post/22e838d1-a080-48e3-b866-0ca66b52ec6b/image.png)


## Break (개행)

```＜br＞```태그를 이용해서 줄바꿈을 구현합니다.
![](https://velog.velcdn.com/images/qorjiwon/post/fc62709f-99ff-4afe-ac2d-0b9f02e59786/image.png)



## Horizontal Rule

```＜hr＞```태그를 이용해서 수평선을 구현합니다.
![](https://velog.velcdn.com/images/qorjiwon/post/81ee0484-744a-4b2f-91e0-0bd55409ed02/image.png)


## 텍스트 서식

![](https://velog.velcdn.com/images/qorjiwon/post/997f6ae1-c0b5-4d1f-ab31-472b204ddf93/image.png)

```html
<strong>strong</strong>
<b>b</b>
<em>em</em>
<i>i</i>
<small>small</small>
<mark>mark</mark>
<sub>sub</sub>
<sup>sup</sup>
```

<strong>strong</strong>

<b>b</b>

<em>em</em>

<i>i</i>

<small>small</small>

<mark>mark</mark>

<sub>sub</sub>

<sup>sup</sup>

## 인용

![](https://velog.velcdn.com/images/qorjiwon/post/c508b02e-2ce5-46fb-b1ef-0556964c064c/image.png)

```html
<blockquote>blockquote</blockquote>
<q>q</q>
```

<blockquote>blockquote</blockquote>

<q>q</q>

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)