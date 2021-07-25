a# 제목(Header)
<!-- #뒤에 띄어쓰기 하기★ -->
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6


# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
<!-- 줄바꿈을 원하는 곳에서 띄어쓰기 두번  or 이게 안되면 <br /> 태그활용-->
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산 <br />
대한 사람 대한으로 길이 보전하세


# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  <!--html에선 권장하지 않는 태그!-->

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록  <!-- 들여쓰기 두번 -->
    1. 순서가 필요한 목록
1. 순서가 필요한 목록


- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록


# 링크(Link)

<!-- [텍스트](주소 "마우스호버시출력될텍스트") : 텍스트 클릭시 해당 주소로 이동 -->

<!-- <a href="https://goolgle.com">GOOGLE</a>   -->
[GOOGLE](https://goolgle.com)

<!-- <a href="https://naver.com" title="NAVER로 이동!">NAVER</a>   -->
[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a> 
target속성은 마크다운에서 제공하지 않기 때문에 원시HTML문법을 활용하여야한다.


# 이미지(Image)
<!-- ![대체텍스트](이미지주소) : 기본이미지 -->
![markdown](https://heropy.blog/css/images/vendor_icons/markdown.png)

<!-- [![기본이미지](이미지주소)](주소) : 이미지클릭시해당주소로이동 -->
[![markdown](https://heropy.blog/css/images/vendor_icons/markdown.png)](https://heropy.blog)


# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)

> 인용문을 작성하세요!
>> 중첩된 인용문1
>>> 중중첩된 인용문2
>>>> 중중중첩된 인용문3

# 인라인(Inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경이미지를 삽입할 수 있습니다.

# 블럭(Block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
li {
  position : absolute;
  top : 40px;
}
```

```javascript
function func(){
  var a = 'AAA';
  return a;
}
```

<!-- 터미널 -->
```bash
$ git commit -m 'Study Markdown'
```


```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|--|--
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

왼쪽(기본) | 가운데정렬 | 오른쪽정렬
--|:--:|--:
OOO | OOO | OOO

# 원시 HTML(Raw HTML)
마크다운은 브라우저에서 출력이 되어야하기 때문에 당연하게 표준의 HTML로 변환이 된다.  
그래서 HTML의 문법을 그대로 사용할 수 있다.


```html
동해물과 <u>백두산</u>이 마르고 닳도록 <br />
하느님이 보우하사 <span style="text-decoration:underline;">우리나라</span> 만세
```
동해물과 <u>백두산</u>이 마르고 닳도록 <br />
하느님이 보우하사 <span style="text-decoration:underline;">우리나라</span> 만세


```html
<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>
```
<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>


```html
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />
```
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />


# 수평선(Horizontal Rule)

<!-- 수평선1   -->

---

<!-- 수평선2 -->

***

<!-- 수평선3 -->

___





