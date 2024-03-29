# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세  

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록 (들여쓰기 두번)
    - 순서가 필요하지 않은 목록 (들여쓰기 두번)
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

타겟에 대한 속성은 제공하지 않는다.

# 이미지(Images)
![대체텍스트](이미지 url)
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)  
[![대체텍스트](이미지url)](이동할 url)
해당이미지를 누르면 밑의 블로그로 이동할 수 있는 형태

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2
>>> 중중첩된 인용문3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
`bacground-image` 속성으로 요소에 배경 이미지를 삽이할 수 있습니다.  
위는 ''가 아니라 1의 왼쪽에 있는 `입니다.

# 블록(block) 코드 강조

```html
<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>
```

```css
.list > li{
  position: absolute;
  top: 40px;
}
```

```javascript
function func(){
  var a = 'AAA';
  return a;
}
```

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
-- | :--: | --: |
static | 기준없음 | 0
relative | 요소 자신 | x
absolute | 위치 상 부모 요소 | x
fixed | 뷰포트 | x

기본적으로 왼쪽정렬인데 구분해주는 - 선에  
: : 하면 가운데 정렬  
오른쪽에만 : 하면 오른쪽 정렬

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보웃하사 우리나라 만세

---

<a href="https://naver.com" 
title = "NAVER로 이동!"
target = "_black">NAVER</a>

<img width="70" src ="https://heropy.blog/css/images/logo.png"
alt = "HEROPY"/>

# 수평선 (Horizontal Rule)

---
***
___ 