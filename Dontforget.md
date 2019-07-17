# 잊어버리기 쉬운 Tag의 속성들 정리

## 1.LIST Tag
>리스트 모양 변경: 
```html
<li type="circle / square"> (O)
<li style="circle / square"> (X)
```
* ol : 순서가 있는 태그 (Unorder list)
* ul : 순서가 없는 태그 (Order list)
* dl : 정의형 태그 (Define list)
```html
<dl>
  <dt>제목</dt>
  <dd>리스트1</dd>
  <dd>리스트2</dd>
</dl>
```




## 2.img Tag
* src 작성 후 alt 속성 빠뜨리지 말 것. (+ title은 마우스 오버 시 나타남)
```html
<img src="img/img1.jpg" alt="이미지1" title="이미지1">
```




## 3.a Tag

```html
새 탭에서 열기
<a href="#" target="_blank">

바로 열기
<a href="#" target="_self">
```




## 4.Table Tag
* 기본 필수 태그
```html
<table>
  <tr> <!--tr = 열 생성--> 
    <td>1열 1행</td> <!--td = 행 생성-->
    <td>1열 2행</td>
    <td>1열 3행</td>
    <td>1열 4행</td>
  <tr>
  
  <tr> 
    <td>2열 1행</td>
    <td>2열 2행</td>
    <td>2열 3행</td>
    <td>2열 4행</td>
  <tr>
```

* 테이블 셀 속성 변경
 ```html
 <table border="외부 borderline 굵기" cellspacing="테이블 borderline끼리의 간격" cellpadding="셀 내부 패딩 간격 조정">
 ```
 
* 가로병합: colspan
```html
<td colspan="2">
```

* 세로병합: rowspan
```html
<td rowspan="2">
```

## input type
*라디오버튼은 중복선택이 불가능하다.
>여러 개의 라디오버튼 중 하나만 선택이 가능하도록 하기 위해서는 name 속성 값을 동일하게 주어 하나의 그룹으로 인식되도록 하여야 한다. 
    
```html
    <input type="radio" name="gender"> 남성
    <input type="radio" name="gender"> 여성
```


## Style 속성 이어 붙일 땐 중간에 ";" 사용
```html
<div style="width:500px ; background:red">
```


