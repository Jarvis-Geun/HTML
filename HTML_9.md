# 2021.09.14(TUE) 유튜브 생활코딩 HTML 강의

## 1. Semantic : 의미론적인 태그

- header tag : 화면의 상단에 위치하는 사이트나 문서의 전체적인 정보를 정의하는 태그
- footer tag : 화면의 하단에 위치하는 사이트나 문서의 전체적인 정보를 정의하는 태그
- nav tag : 어떤 것이 이 웹페이지를 탐색할 때 사용하는 네비게이션인지를 의미론적으로 알려주는 태그
- article tag : 해당 부분이 본문이라는 것을 의미론적으로 알려주는 태그. 본문이 여러개인 경우 article 태그를 여러개 정의해주면 된다.
- section tag : 문석의 구획(=section)을 정의해주는 태그
- 이외의 태그는 아래의 Reference를 참고한다.

### Reference
> https://opentutorials.org/module/1892/10954

> https://www.youtube.com/watch?v=uDmNhHYecL4&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=34

<br>

## 2. 검색엔진최적화 1

- HTML을 사용하여 웹사이트를 구현할 때, 검색엔진에 노출되도록 하는 것이 중요하다. 대표적인 검색엔진인 구글에서, 제공하는 검색엔진최적화 가이드를 참고하여 웹을 구현하면 검색엔진에 더 원활하게 노출될 수 있다.

- 다만 주의할 사항은, 검색엔진에 과하게 최적화를 할 경우 스팸으로 인식되어 검색에서 제외될 수 있음을 주의한다.

### Reference
> https://www.youtube.com/watch?v=owK8xxL7pps&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=32

<br>

## 3. 검색엔진최적화 2

- 사이트의 내용을 잘 표현할 수 있는 title 태그를 사용하는 것이 검색엔진 노출에 도움이 된다.

- 페이지마다 고유한 title 태그 작성

- title과 함께 meta 태그(description)를 잘 활용하는 것이 중요하다. 사이트의 내용을 한~두단락으로 요약하여 meta 태그를 사용하는 것이 좋다.

- URL의 주소를 알아보기 좋은 형태로 만들면, 검색엔진 최적화에 도움이 될 뿐만 아니라, 방문자가 보고있는 웹페이지(혹은 공유할 때)가 어떤 정보를 가지고 있는지 쉽게 알 수 있다.

- URL에 단어 사용

- 단순 디렉토리 구조 만들기

- 특정 문서에 도달하기 위한 한 가지 형태의 URL 제공

```HTML
<link rel="canonical" href="http://localhost/1.html" />
```
검색엔진이 2.html 이라는 특정 주소에 도착하면, 위의 코드를 보고 2.html 페이지가 1.html 페이지와 같은 내용이라는 것을 알 수 있다. 검색하면 1.html 을 보여주게 된다.

- [301 Redirect vs Canonical URL](https://www.ascentkorea.com/canonical-url-vs-301-redirect/) : 301 Redirect의 경우 HTML에서는 구현이 불가능하다.

### Reference
> https://www.youtube.com/watch?v=-G2aDXiF8zE&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=33

<br>

## 4. 검색엔진최적화 3

- 사이트 내에서 이동하기 쉽게 만들기 : 크롤링, 링크가 잘 정돈되어 있어야 검색엔진이 더 원활하게 돌아다닐 수 있다.

- '사이트 이동 경로'의 사용으로 방문자에게 편리를 제공하기 : Breadcrumb(=빵부스러기), 하위경로 표시해주기

- 사용자가 URL의 일부를 제거하는 경우 발생할 상황을 고려하기 : 사용자가 URL의 일부를 제거하여 다른 페이지로 이동할 경우를 대비하여, 웹페이지가 뜨지않는 것이 아니라 해당 URL로 자유롭게 이동할 수 있도록 구현한다.

- 이동 경로를 위해 텍스트 링크(하이퍼텍스트)를 사용

### Reference
> https://www.youtube.com/watch?v=TDSmp-QxVRU&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=34