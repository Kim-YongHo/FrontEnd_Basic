# Form



## <**form**>

- 웹 페이지에서 특정한 형태를 사용할 수 있게 도와주는 태크

```html
<form [속성="속성값"]> 여러 폼 요소 </form>

<form action = "" autocomplete = "off"> 자동 완성은 기본 ON </form>
```



## <**fieldset**>, <**legend**>

- 하나의 form 태그 안에 구역을 나누어서 사용할 때 활용

```html
<form action="">
    <fieldset>
        <legend>상품 선택</legend>

    </fieldset>
    <fieldset>
        <legend>배송 정보</legend>

    </fieldset>      
</form>
```



## <**label**>

- 같은 폼에서 input 태그에  label를 붙이기 위해 사용

```html
<form>
    <label>아이디(6자 이상) <input type="text"></label>

    <br>

    <label for="user-id">아이디(6자 이상) </label>
    <input type="text" id="user-id">
</form>
```



## <**input**>

- 웹 페이지에서 정보를 입력할 때 사용하는 태그

```html
<form>
    <fieldset>
        <label>아이디: <input type="text" id="user_id" size="10"></label>
        <label>비밀번호: <input type="password" id="user_pw" size="10"></label>
        <input type="submit" value="로그인">
    </fieldset>
</form>
```





## for - id

- for - id를 사용해서 분리되도 연결 가능

```html
<label for="fullname">*이름</label><br>
<input id="fullname" name="fullname" type="text">
```





## placeholder

- 사용자에게 input 값에 뭘 입력해야 할지 전달 해주는 기능

```html

```



## <**fieldset**>

- .....

```html

```







# 동영상

---

## <**object**>

- 오디오, 비디오, pdf 등 다양한 멀티미디어 파일 사입 가능

## <**embed**>

- audio, video, object 태그를 사용할 수는 곳에 활용

```html
<embed src = "이미지/동영상 경로"  width = "너비" height = "높이">
```

## <**audio**>, <**video**>

- 동일한 방법으로 사용 가능



# 하이퍼링크

---

## 하이퍼링크

- 하이퍼텍스트 문서 내의 단어/그림 등 클릭할 경우 문서 내의 다른 요소로 연결해주는 기능

## <**a**>

```html
<a href = "링크할 주소"> 텍스트 or 이미지 </a>
<a href = "링크할 주소" target = "_blank"> 텍스트 or 이미지 </a>
```

- target = "_blank"
  - 새로운 브라우저 창에 연결

