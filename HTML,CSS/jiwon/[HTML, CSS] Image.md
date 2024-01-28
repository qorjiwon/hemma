# Image

## HTML

```html
<img class="image" src="image.jpeg" alt="이미지 이름">
```

### src

이미지 소스의 URL을 명시합니다.

### alt

이미지를 보여줄 수 없을 때 해당 `이미지를 대체할 텍스트`를 명시합니다. 

이러한 alt 속성은 사용자가 느린 네트워크 환경이나 src 속성 값의 오류, 시각 장애인용 스크린 리더의 사용 등 어떤 이유로든 사용자가 이미지를 볼 수 없을 때 이미지 대신 제공할 대체 정보를 제공합니다.

## CSS

### object-fit

컨테이너에 맞게 ```<img>``` 또는 ```<video>``` `크기를 조정하는 방법을 지정`하는 데 사용됩니다.

|속성값|설명|
|:--:|--|
|fill|기본값입니다. 이미지는 주어진 치수를 채우도록 크기가 조정됩니다. 필요한 경우 이미지에 맞게 늘어나거나 찌그러집니다.|
|contain|이미지는 종횡비를 유지하지만 주어진 치수에 맞게 크기가 조정됩니다.|
|cover|이미지가 종횡비를 유지하고 주어진 치수를 채웁니다. 이미지에 맞게 잘립니다.|
|none|이미지의 크기가 조정되지 않습니다.|
|scale-down|이미지가 none 또는 포함의 가장 작은 버전으로 축소됩니다.|

### 예시

![](https://velog.velcdn.com/images/qorjiwon/post/42e461c7-7700-4083-8a38-2639b9738fa3/image.png)
![](https://velog.velcdn.com/images/qorjiwon/post/ca438ad6-e270-4268-aca1-9285e9b1b063/image.png)
![](https://velog.velcdn.com/images/qorjiwon/post/5a7f024f-4ae4-4b40-8a01-9ac4e66f3978/image.png)
![](https://velog.velcdn.com/images/qorjiwon/post/8a232b05-72d9-4f0d-b8ab-7ebfa0617481/image.png)

---

### object-position

컨테이너 내에서 ```<img>``` 또는 ```<video>```를 `배치하는 방법을 지정`하는 데 사용됩니다.

#### 원본 이미지

![](https://velog.velcdn.com/images/qorjiwon/post/ad89cd22-4d49-4da7-b027-ab1ea9196e2c/image.png)

**object-position:left**
![](https://velog.velcdn.com/images/qorjiwon/post/e9a929f3-c851-48a1-861e-ba43cd3afd1e/image.png)

**object-position:right**
![](https://velog.velcdn.com/images/qorjiwon/post/1435db89-04a5-4d4b-a97d-1d7e91201aad/image.png)

---

### Reference

- [따라하며 배우는 HTML, CSS](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-html-css/dashboard)