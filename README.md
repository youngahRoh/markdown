<!-- 마크다운언어 -->

# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4

# 문장(paragraph)

동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Breaks)
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산  
대한사람 대한으로 길이 보전하세

<!-- 뒤에 띄어쓰기 두번하거나 <br/> -->

# 강조(Emphasis)
_이텔릭_ <br/>
**두껍게**  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u>  


# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록(순서가 알아서 바뀜)
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

# 링크(Links)

<a href="http://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](http://naver.com) "NAVER로 이동!" 

<a href="https://naver.com" title="NAVER로 이동!" target="_black">NAVER</a>

# 이미지(Images)

![]()
<!-- 느낌표가 있어야 이미지가 출력됨 -->
<!-- 이러한 구조 -->
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](http://naver.com)
<!-- 이미지를 클릭하게 되면 그 주소로 이동하게 됨 -->

# 인용문(BlockQuote)

>남의 말이나 글에서 직접 또는 간접으로 따온 문장.
>(네이버 국어 사전)
<!-- > 넣으면 됨 -->

> 인용문을 작성하세요
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조
CSS에서 `background` 혹은
`backgrooudn-image` 속성으로 요소에 배경이미지를 삽입할 수 있습니다.
<!-- 백틱기호, 문장을 드래그 해서  백틱누르면 편하게 사용됨 -->

# 블럭(block)코드 강조

```html
<a href="http://www.google.co.kr/" target="_blan">GOOGLE</a>
```

```javascript
function func() {
    var a = 'AAA';
    return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```
```plaintext
동해물과 백두산이 마르고 닳도록
```

<!-- ```세번 -->

# 표(Table)

position 속성

값 | 의미 | 기본값  
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

<!-- :--: (가운데 정렬) --: (오른쪽 정렬) 간단한 표만 가능-->

# 원시 HTML(Raw HTML)
<!-- 마크다운에서 실제 html태그를 사용하는 것 -->

동해물과 <span style="text-decoration: underline;"><u>백두산</u></span>이 마르고 닳도록  
하느님이 보우하사 우리나라 만세

<a href="http://naver.com" title="NAVER로 이동!" target="_black">
NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEPRPY">

# 수평선(Horizontal Rule)

---
***
___
