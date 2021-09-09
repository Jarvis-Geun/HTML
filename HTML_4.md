# 2021.09.08(WED) 유튜브 생활코딩 HTML 강의

## 표1 : 기본

### table tag : 웹페이지에 표를 만들어주는 태그

- \<td>table data tag\</td> : 표의 column(열)을 나타내는 태그. 각 열마다 태그를 선언해주어야 한다.

- \<tr>table row tag\</tr> : 표의 row(행)을 나타내는 태그. 각 행마다 태그를 선언해주어야 한다.

- \<table>table tag\</table> : 표의 맨 앞과 맨 뒤에 table 태그를 선언해주어야 표가 만들어진다.

- \<table border='2'>table border 속성\</table> : 표의 경계선을 표시해주는 속성

- 원래는 표를 만들기 위해 사용하는 태그이지만, 과거에는 웹페이지의 레이아웃을 표현하기 위해 사용되기도 했다. 지금까지도 몇몇 웹페이지에서는 표를 이용하여 레이아웃을 사용하는 경우가 종종 있다. 표를 이용하여 레이아웃을 만드는 것이 아닌, CSS를 사용하여 레이아웃을 만드는 것을 표준으로 한다.

Reference : https://www.youtube.com/watch?v=XUTFXu0f4qo&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=16
<br>

---
## 표2 : 구조

- \<thead>표의 제목부분\</thead> : 표의 제목부분에 해당하는 행의, 맨 앞과 맨 뒤에 태그를 선언한다.

- \<tbody>표의 본문부분\<tbody> : 표의 본문부분에 해당하는 행의, 맨 앞과 맨 뒤에 태그를 선언한다. 본문이 여러 개일 경우, 한번에 선언하는 것이 가능하다.

- \<tfoot>표의 마지막부분\</tfoot> : 표의 마지막부분에 해당하는 행의, 맨 앞과 맨 뒤에 태그를 선언한다.

- 위와 같은 태그들을 선언하는 이유는 표의 제목, 본문, 마지막부분에 해당하는 내용을 순서에 상관하지 않고 선언할 수 있기 때문이다. 기존에는 \<thead> 태그를 사용하지 않으면 해당 행을 무조건 제일 위에 위치시켜야 했으나, \<thead> 태그를 사용함으로써 tbody 태그나 tfoot 태그의 아래에 위치시켜도 표는 정상적으로 만들어진다. 같은 이유로 \<tbody>, \<tfoot> 태그를 사용한다.

Reference : https://www.youtube.com/watch?v=H84fuDj1Jxs&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=17
<br>

---
## 표3 : 병합

\<td>총 예상기간\</td>\<td>\</td>\<td>\</td>\<td>약 3달\</td>

병합하려는 열의 개수만큼 colspan을 사용하여 병합시켜준다. 이 때 표의 공백에 해당하는 부분은 지워주어야 병합이 된다. 해당 코드는 아래와 같다.<br>

\<td colspan="3">총 예상기간\</td>\<td>약 3달\</td>
<br>

마찬가지 방법으로 rowspan 속성을 선언해주면 된다. 그 과정은 생략한다.

- \<td colspan='2'>병합할 내용\</td> : 2개의 열 병합
- \<td rowspan='2'>병합할 내용\</td> : 2개의 행 병합

Reference : https://www.youtube.com/watch?v=i7oKd-eKvdw&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=18
<br>

---
