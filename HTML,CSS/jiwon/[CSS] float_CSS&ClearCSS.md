# float CSS & Clear CSS

## float CSS

float CSS 속성은 컨테이너의 왼쪽 또는 오른쪽에 요소를 배치하여 텍스트 및 `인라인 요소가 주위를 둘러쌀 수 있도록` 합니다. 요소는 페이지의 정상적인 흐름에서 제거되지만 여전히 흐름의 일부로 남아 있습니다.

![](https://velog.velcdn.com/images/qorjiwon/post/678c5013-8788-4d9d-b235-188abda4f4c3/image.png) ![](https://velog.velcdn.com/images/qorjiwon/post/df871b16-294f-4af0-9330-022e94c16f14/image.png)

### Float 속성을 이용한 Layout 구현

float css는 여전히 ​​레이아웃에 사용할 수 있지만 요즘에는 웹 페이지에서 레이아웃을 만들기 위한 훨씬 강력한 도구 Flexbox 및 Grid를 사용합니다.

![](https://velog.velcdn.com/images/qorjiwon/post/33f50077-6b2d-4249-8d0e-9ac506d6a9cc/image.png)

## Clear CSS

clear CSS 속성을 이용해서 `float의 영향을 받지 않도록` 할 수 있습니다.

float 속성을 사용하고 아래(오른쪽이나 왼쪽이 아닌) 다음 요소를 원할 때 clear 속성을 사용해야 합니다.

clear 속성은 float 요소 옆에 있는 요소에 어떤 일이 발생해야 하는지 지정합니다.

### clear 속성 값

clear 속성은 다음 값 중 하나를 가질 수 있습니다.

- `none` : 기본값입니다. 요소가 왼쪽 또는 오른쪽 부동 요소 아래로 푸시되지 않습니다.
- `left` : 요소가 왼쪽 부동 요소 아래로 푸시됩니다.
- `right` : 요소가 오른쪽 부동 요소 아래로 푸시됩니다.
- `both` : 요소가 왼쪽 및 오른쪽 부동 요소 아래로 푸시됩니다.
- `inherit` : 요소는 부모로부터 clear 값을 상속합니다.

float를 지울 때(clear) 플로트(float)와 클리어(clear)를 일치시켜야 합니다.
요소가 왼쪽으로 플로트되어 있으면 왼쪽으로 지워야 합니다. float: left;   =>  clear: left
플로팅된 요소는 계속 플로팅되지만 지워진 요소는 웹 페이지에서 그 아래에 나타납니다.

![](https://velog.velcdn.com/images/qorjiwon/post/7258162b-4c04-4edb-9650-3ddec09a5cb8/image.png)

```css
.div1 {
    float: left;
    padding: 10px;
    border: 3px solid #73AD21;
}

.div2 {
    padding: 10px;
    border: 3px solid red;
}

.div3 {
    float: left;
    padding: 10px;
    border: 3px solid #73AD21;
}

.div4 {
    padding: 10px;
    border: 3px solid red;
    clear: left;
}
```

```html
<div>
        <h2>Without clear</h2>
        <div class="div1">div1</div>
        <div class="div2">div2 - Notice that div2 is after div1 in the HTML code. However, since div1 floats to the left 
            the text in div2 flows around div1.</div>
            <br><br>

            <h2>With clear</h2>
            <div class="div3">div3</div>
            <div class="div4">div4 - Here, clear: left; moves div4 down below the floating div3. The value "left" clears
                elements floated to the left. You can also clear "right" and "both".
            </div>
    </div>
```

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)