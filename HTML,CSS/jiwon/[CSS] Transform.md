# Transform

|속성|설명|
|:-:|:-:|
|transtion|선택자가 변화되는 것을 시간의 흐름을 줘서 변화시킵니다.|
|animation|하나의 줄거리(@keyframes)를 구성하여 줄거리 내에서 세부 움직임을 `시간 흐름 단위로 제어`하여 `요소의 움직임을 표현`합니다.|
|`transform`|- CSS transform 속성으로 요소에 회전(rotate), 크기 조절(scale), 기울이기(skew), 이동 (translate)효과를 부여할 수 있습니다. transform은 CSS 시각적 서식 모델의 좌표 공간을 변경합니다.<br>- 애니메이션 효과를 제공하지는 않습니다. 그래서 정의된 프로퍼티가 바로 적용되어 화면에 표시됩니다.<br>- 트랜스폼은 애니메이션 효과를 위해 사용하여야 하는 것은 아니지만 애니메이션 효과를 부여할 필요가 있다면 트랜지션이나 애니메이션과 함께 사용해야 합니다.|

>참고: [mozilla - CSS/transform](https://developer.mozilla.org/ko/docs/Web/CSS/transform)

## Transform 문법

```transform: none | transform-functions | initial | inherit;```

|속성|설명|
|:-:|:-:|
|none|변환이 없어야 함을 정의합니다.|
|initial|이 속성을 기본값으로 설정합니다.|
|inherit|부모 요소에서 이 속성을 상속합니다.|

## transform-functions 

- `scale()`: 요소의 `크기에 영향`을 줍니다. 이는 요소의 글꼴 크기, 패딩, 높이 및 너비에도 적용됩니다. scaleX 및 scaleY 함수의 약식 함수이기도 합니다.

- `skewX()` 및 `skewY()`: 요소를 왼쪽 또는 오른쪽으로 `기울입`니다. skew()는 두 값을 모두 수용하여 skewX()와 skewY()를 결합한 축약형입니다.

- `translate()`: 요소를 `옆으로 또는 위아래로` 이동합니다.

- `rotate()`: 요소를 현재 위치에서 `시계 방향으로 회전`합니다.

- `matrix()`: 손으로 작성하도록 의도된 것은 아니지만 `모든 변환을 하나로 결합`하는 함수입니다.

- `perspective()`: 요소 자체에는 영향을 미치지 않지만 하위 요소의 3D 변환에 영향을 미치므로 모든 요소가 일관된 깊이 관점을 가질 수 있습니다.

### Skew

skew(x-angle, y-angle), skewX(x-angle)

X축은 좌/우로, Y축은 상/하로 기울이는 효과를 준다. 

![](https://velog.velcdn.com/images/qorjiwon/post/91f51375-27e3-4da3-9767-013767ae8291/image.png)

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)