# Image, Input 요소

## image

### HTML

```html
<img class="image" src="image.jpeg" alt="이미지 이름">
```

### src

이미지 소스의 URL을 명시합니다.

### alt

이미지를 보여줄 수 없을 때 해당 이미지를 대체할 텍스트를 명시합니다. 

이러한 alt 속성은 사용자가 느린 네트워크 환경이나 src 속성 값의 오류, 시각 장애인용 스크린 리더의 사용 등 어떤 이유로든 사용자가 이미지를 볼 수 없을 때 이미지 대신 제공할 대체 정보를 제공합니다.

### object-fit

컨테이너에 맞게 ```<img>``` 또는 ```<video>``` 크기를 조정하는 방법을 지정하는 데 사용됩니다.

- `fill` : 기본값입니다. 이미지는 주어진 치수를 채우도록 크기가 조정됩니다. 필요한 경우 이미지에 맞게 늘어나거나 찌그러집니다.
- `contain` : 이미지는 종횡비를 유지하지만 주어진 치수에 맞게 크기가 조정됩니다.
- `cover` : 이미지가 종횡비를 유지하고 주어진 치수를 채웁니다. 이미지에 맞게 잘립니다.
- `none` : 이미지의 크기가 조정되지 않습니다.
- `scale-down` : 이미지가 none 또는 포함의 가장 작은 버전으로 축소됩니다.

### object-position

컨테이너 내에서 ```<img>``` 또는 ```<video>```를 배치하는 방법을 지정하는 데 사용됩니다.

## input

![](https://velog.velcdn.com/images/qorjiwon/post/a3291b4f-bf1b-4069-a2ee-5765a4eecc37/image.png)

```html
<div>
    <input type="text" placeholder="텍스트를 입력하세요."><br>
    <input type="password"><br>
    <input type="checkbox"><br>
    <input type="radio"><br>
    <input type="file"><br>
</div>
```

HTML에서는 다양한 타입의 input 요소를 사용하여 사용자로부터 입력을 받을 수 있습니다.

대표적인 input 요소의 타입은 다음과 같습니다. 

    1. 텍스트 입력(text) 
    2. 비밀번호 입력(password) 
    3. 라디오 버튼(radio) 
    4. 체크박스(checkbox) 
    5. 파일 선택(file) 
    6. 선택 입력(select) 
    7. 문장 입력(textarea) 
    8. 버튼 입력(button) 
    9. 전송 버튼(submit) 
    10. 필드 셋(fieldset)

<br>

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)