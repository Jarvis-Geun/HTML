# 2021.09.12(SUN) 유튜브 생활코딩 HTML 강의

## form : button
```HTML
<form action="http://localhost/form.php">
    <input type="submit" value="전송">
</form>
```
- 전송(=submit, 제출) 버튼 구현
- 전송 버튼을 누르면 form 태그의 action 속성에서 사전에 설정해놓은 링크로 이동

```HTML
    <input type="button" value="버튼" onclick="alert('hello world')">>
```
- 버튼 생성
- 자바스크립트에서 활용 가능
- 버튼을 누르면 새로운 창(hello world 출력)이 뜬다.

```HTML
    <input type="reset">
```
- 재설정 버튼 구현
- 재설정 버튼을 누르면 사용자가 적어놓은 정보들이 리셋된다(text 속성과 동시에 사용할 경우).

```HTML
<html>
    <head>
        <meta charset="UTF-8">
    </head>

    <body>
        <form action="http://localhost/form.php">
            <p>
                <input type="text">
            </p>
            
            <input type="submit" value="전송">
            <input type="button" value="버튼" onclick="alert('hello world')">
            <input type="reset">
        </form>
    </body>
</html>
```
- 전체코드

### Reference
> https://www.youtube.com/watch?v=LnlIrDXwEr0&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=23