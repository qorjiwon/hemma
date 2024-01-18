# transition 사용하기

## transition?

- 스타일 변경 시 부드럽게 전환하도록 합니다.
- 선택자가 변화되는 것을 시간의 흐름을 줘서 변화시키는 속성

사용 방법

```css
.a {
	transition: <property> <duration> <function>
}
```

```<property>```와 ```<function>```는 생략 가능합니다.
function 기본 값은 ease입니다.

예시1

```css
.a {
	transition: opacity 0.2s linear;
}
```

opacity가 0.2s에 걸쳐 변환됩니다.

## function들

|property|효과|그래프|
|:--:|--|:--:|
|ease|**기본값**. 느리게 시작한 다음 빠르게 전환한 다음 천천히 종료|![](https://velog.velcdn.com/images/qorjiwon/post/fb1c4a1c-58e7-4c61-a84b-b975e0c15c34/image.png)|
|linear|처음부터 끝까지 같은 속도로 전환|![](https://velog.velcdn.com/images/qorjiwon/post/f800cc74-56d3-453d-aa6a-5925348ec667/image.png)|
|ease-in|느리게 시작한 후 일정한 속도에 다다르면 그 상태로 등속 운동.|![](https://velog.velcdn.com/images/qorjiwon/post/2d3a5902-3457-4d96-96f4-ad787d770119/image.png)|
|ease-out|일정한 속도의 등속으로 시작해서 점점 느려지며 종료|![](https://velog.velcdn.com/images/qorjiwon/post/583c2e7e-bee8-4086-9ae4-68f0fdd2e53f/image.png)|
|ease-in-out|ease와 비슷하게 느리게 시작하여 다시 느려지면서 종료|![](https://velog.velcdn.com/images/qorjiwon/post/c582a4a7-6f25-4650-86d3-c8a8d91b532e/image.png)|
|cubic-bezier(n,n,n,n)|3차 베지어 함수에서 자신의 값을 임의적으로 정함. https://cubic-bezier.com| -|


---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)

- [transition / transform / animation 속성 사용법
출처: https://inpa.tistory.com/entry/CSS-📚-트랜지션-트랜스폼-애니메이션 [Inpa Dev 👨‍💻:티스토리]](https://inpa.tistory.com/entry/CSS-%F0%9F%93%9A-%ED%8A%B8%EB%9E%9C%EC%A7%80%EC%85%98-%ED%8A%B8%EB%9E%9C%EC%8A%A4%ED%8F%BC-%EC%95%A0%EB%8B%88%EB%A9%94%EC%9D%B4%EC%85%98)