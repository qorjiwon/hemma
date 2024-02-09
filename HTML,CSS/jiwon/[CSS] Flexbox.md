# Flexbox

## Flexbox 란
CSS Flexbox는 요소를 효율적이고 `동적으로 배열`할 수 있는 레이아웃 모델입니다.
요소를 반응형으로 만들어 요소를 표시하는 장치의 종류에 따라 요소의 동작이 변경되도록 합니다.
컨테이너의 항목을 보다 효율적이고 동적으로 정렬하기 위해 CSS 버전 3에 도입되었습니다.
이 레이아웃은 `1차원`이며 공간이 균등하게 분산된 컨테이너 내부에 요소를 배치할 수 있습니다.

Flexbox 이전에는 아래에 나열된 네 가지 레이아웃 방법이 있었습니다.

|display 속성 값|설명|
|:--:|--|
|block|웹 페이지에서 섹션을 생성하기 위해 블록 레이아웃이 사용됩니다.|
|inline|텍스트에 사용되는 레이아웃 방법입니다.|
|table|2차원 데이터가 있는 테이블에 사용됩니다.|
|positioned|요소의 특정 위치에 사용됩니다.|

## Flexbox Components

Flexbox는 아래에서 설명한 두 가지 구성 요소로 구성됩니다.

![](https://velog.velcdn.com/images/qorjiwon/post/e334a775-99c6-4dcb-9cb4-65cee9770340/image.png)

### Flex 

Flexbox의 이 구성 요소는 표시를 flex 또는 inline-flex로 설정하여 상위 요소의 속성을 정의합니다.

```css
display: flex
```

### Flex Items

Flex 아이템은 플렉스 컨테이너의 직계 자식입니다.

## Flexbox Properties

### Flex Container Properties

flex-direction
flex-wrap
flex-flow
justify-content
align-items
align-content

### Flex Items Properties

order
flex-grow
flex-shrink
flex-basis
align-self

## 두 개의 축 Main, Cross Axis

flexbox로 작업할 때 두 축, 즉 주축(Main Axis)과 교차축(Cross Axis)을 생각해야 합니다.
주축은 flex-direction 속성에 의해 정의되고 교차축은 수직으로 진행됩니다.
flexbox로 수행하는 모든 작업은 이러한 축을 다시 참조하므로 처음부터 작동 방식을 이해하는 것이 좋습니다.

![](https://velog.velcdn.com/images/qorjiwon/post/b8c66c8a-aaaf-4ca2-8417-26e0bdf5cbee/image.png)

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)