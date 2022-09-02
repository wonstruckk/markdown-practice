# 제목(Header)
<!-- h1태그와 비슷한 기능임. -->
# 제목 1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6


# 문장(paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(line breaks)
<!-- 띄어쓰기 두번하면 줄바꿈으로 해석 -->
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~<br/>
<u>밑줄</u>

# 목록(list)
<!-- OL태그와같다. -->
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크(links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로이동!")
<!-- target속성으로 이페이지에서 열지 다른페이지에서열지
사용이 불가능함 그래서 a태그로 해라. -->
<a href="https://naver.com" title="NAVER로이동!" target="_blank">NAVER</a>

# 이미지(image)
![HEROPY](https://heropy.blog/css/images/logo.png)
<!-- img눌러서 링크처럼이동. -->
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)


# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어 사전)

<!-- 중첩기능 -->
> 인용문 작성하세요.
>> 중첩1
>>> 중첩2
>>> 중첩3
>>> 중첩4

# 인라인(inline) 코드 강조
<!-- 한번에 ``기호넣으려면 드래그로 선택 후 사용 -->
CSS에서 `background`혹은 `background-image` 속성으로</br>  요소에 배경 이미지를 삽입할 수 있습니다.

# 블럭(block) 코드 강조

```html
    <a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
    h1 {
        color:black;
        background-color:white;
        top : 40px;
    }
```

```javascript
    function() {
        var a = 'aaa';
        return a;
    }
```

```bash
$ git commit -m 'study-cafe'
```

```plaintext
    동해물과 백두산이 마르고 닳도록
    하느님이 보우하사 우리 나라 만세!
```

# 표(table)
<!-- 복잡한 구성의 표는 마크다운으로 제작 불가함. -->
position 속성
<!-- 행만큼 버티컬바로 구분 -->
<!-- 콜론기호는 정렬을 의미함. -->
값 | 의미 | 기본값
--|:--:|--:
static | 배치기준없음 | O
relative | 요소자기자신 | X
absoulte | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)
<!-- <u>tag 사용안하고 span으로 css사용 -->
동해물과 <span style="text-decoration:underline;">백두산</span>이 마르고 닳도록</br>
하느님이 보우하사 우리 나라 만세!

<a href="https://naver.com" title="NAVER로이동!" target="_blank">NAVER</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***

___

