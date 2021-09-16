# 2021.09.14(TUE) 유튜브 생활코딩 HTML 강의

## 1. 검색엔진최적화 4 : 링크

### 1.1 검색 엔진을 위한 것이 아닌 사용자를 위한 콘텐츠 작성

- 검색 엔진에만 잘 노출되기 위하여 웹사이트내에 없는 내용을 마구잡이로 검색 엔진에 최적화 시키면, 검색 엔진이 이를 웹스캠으로 인지하게 된다. 따라서 적절한 최적화가 필요하다.

### 1.2 보다 나은 앵커 텍스트 작성

- 페이지의 URL을 대부분의 앵커 텍스트로 사용하는 것을 피한다.

- 주제에서 벗어나거나 링크되는 페이지의 콘텐츠와 관련이 없는 텍스트 사용을 피한다.

### Reference
> https://www.youtube.com/watch?v=J_ZQhHpV6PQ&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=35

<br>

## 2. 검색엔진최적화 5 : 이미지와 제목

### 2.1 이미지 사용의 최적화

```HTML
    <body>
        <img src="img.jpg" alt="img 이름">
    </body>
```

- 구글 이미지 검색의 경우, alt 속성을 통해 이미지를 검색하기 때문에 이러한 점을 잘 고려하여 HTML을 구성하도록 한다.

### 2.2 보편적인 이미지 파일 포맷의 사용과 이미지를 위한 특정 디렉토리 설정을 권장합니다.

- 일반적으로 images라는 폴더를 만들어, 이 폴더에 이미지를 보관한다. 이미지를 불러올 때는 아래의 코드처럼 경로만 변경해주면 된다.

```HTML
    <body>
        <img src="images/img.jpg" alt="img 이름">
    </body>
```

### 2.3 간결하면서도 설명적인 파일 이름과 alt 텍스트의 활용

- 의미를 부여한 이미지 이름을 사용한다.

### 2.4 이미지를 링크로 사용할 때 alt 텍스트를 제공하기

```HTML
<html>
    <head>
        <meta charset="UTF-8">
    </head>

    <body>
        <a href="HTML_2_웹사이트 만들기_1.html"><img src="images/img.jpg" alt="img 이름"></a>
    </body>
</html>
```

- 이미지를 클릭하면 링크로 이동한다.

### 2.5 제목 태그의 적절한 활용

- 글씨체의 크기를 키우고 굵게 하는 것과 h1, h2, h3 태그를 사용하는 것은 소스코드에서 큰 차이가 있다. 즉, 의미론적으로 현격한 차이를 보인다. 따라서 제목 태그를 써야할 때는 제목 태그를 써주는 것이 좋다.

### Reference
> https://www.youtube.com/watch?v=jtjyNe1yfOM&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=36