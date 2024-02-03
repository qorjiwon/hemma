# Animation

- 애니메이션을 사용하면 요소를 한 스타일에서 다른 스타일로 점진적으로 변경할 수 있다.


- CSS 애니메이션을 사용하려면 먼저 애니메이션에 대한 몇 가지 키프레임 keyframes 을 지정해야 한다.


- 키프레임(keyframe)은 특정 시간에 요소의 스타일을 유지한다.

|속성|설명|
|:--:|--|
|**animation-name**|`@keyframes` 애니메이션의 이름 지정.|
|**animation-duration**|애니메이션 한 주기를 완료하는 데 걸리는 시간 지정.|
|**animation-timing-function**|애니메이션의 속도 곡선 지정.<br> ex) `linear`, `ease`, `ease-in` ...|
|**animation-delay**|애니메이션 시작 지연 지정.|
|**animation-iteration-count**|애니메이션을 재생 횟수 지정.|
|**animation-direction**|애니메이션을 앞으로, 뒤로 또는 번갈아 재생해야 하는지 여부 지정. <br> ex) `normal`, `alternate`, `reverse`... <br> https://www.w3schools.com/cssref/playit.asp?filename=playcss_animation-direction&preval=alternate|
|**animation**|모든 애니메이션 속성을 설정하기 위한 **약식 속성**|

## animation-direction

|속성 값|설명|
|:--:|--|
|`normal`|기본값. 애니메이션이 정상적으로 재생됩니다(forwards).|
|`reverse`|애니메이션이 역방향으로 재생됩니다.(backwards)|
|`alternate`|애니메이션이 먼저 앞으로 재생된 다음 뒤로 재생됩니다.|
|`alternate-reverse`|애니메이션이 먼저 뒤로 재생된 다음 앞으로 재생됩니다.|



---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)