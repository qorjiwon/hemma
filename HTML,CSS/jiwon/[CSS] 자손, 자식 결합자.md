# 자손, 자식 결합자

## 개념

|선택자|관계|설명|
|-|-|-|
|A B|자손 관계|A 요소에 포함된 B 요소 선택|
|A>B|자식 관계|A 요소의 **직계 자식** 요소인 B 선택|

## 예시

html 코드

```html
<body>
    <div class="parent">
        <p>
            <span>span in p</span>
        </p>
        <span>span</span>
    </div>
</body>
```

css 코드

```css
.parent span {
    color: pink;
}

.parent > span{
    color: blue;
}
```

-> parent의 span 자손들은 모두 pink 글자로 지정하고, 직계 자식만 blue로 지정한다.

그럼 다음과 같은 결과가 나온다.

![](https://velog.velcdn.com/images/qorjiwon/post/d418bef0-05a0-4f8d-b269-6b3012c52edd/image.png)

span in p는 parent의 직계 자손이 아니기 때문에 pink이고 span은 parent의 직계 자손이기 때문에 blue임을 확인할 수 있다.

---

### Reference

- [자손, 자식 결합자 , 속성 선택자](https://connieya.tistory.com/35)