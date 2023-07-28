# 제목(Header)

# 제목 1

## 제목 2

_이텔릭_ <br>
띄어쓰기 두번으로 줄바꿈!  
**이텔릭**  
**\_이텔릭 + 두껍게**
~~취소선~~  
<u>밑줄</u>

# 목록

1. 순서가 필요한 목록
1. 순서가 필요한 목록2
1. 순서가 필요한 목록3
   1. 순서가 필요한 목록  
      !들여쓰기 2번!
   1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록

# 링크(Links)

<a href= "https://google.com"> GOOGLE </a>

[GOOGLE](https://google.com)

<a href= "https://naver.com" title="NAVER로 이동!"> NAVER </a>

[NAVER](https://naver.com 'NAVER로 이동!')

<a href= "https://naver.com" title="NAVER로 이동!" target="_blank"> NAVER </a>

# 이미지(Iamges)

![대체 텍스트](이미지 경로)

[![대체 텍스트](이미지 경로)](https://웹주소)

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접적으로 따온 문장.  
> 출처: 네이버 국어 사전

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문1
> > > 중중첩된 인용문2
> > > 중중첩된 인용문3

# 인라인(inline) 코드 강조

css에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank"></a>
```

```css
.list > li {
	position: absolute;
	top: 40px;
}
```

```javascript
function func() {
	var a = 'AAA';
	return a;
}
```

> 터미널에 입력하는 내용도 가능하다

```bash
$ git commit -m 'Study Markdown'
```

> 강조하는 코드가 아닌 경우 : paintext

```plaintext
동해물과 백두산이 마르고 닳도록
하나님이 보우하사 우리나라 만세
```

# 표(Table)

#### position 속성

| 값        | 의미              | 기본값 |
| --------- | ----------------- | ------ |
| static    | 기준 없음         | O      |
| releative | 요소 자신         | X      |
| absolute  | 위치 상 부모 요소 | X      |
| fixed     | 뷰포트            | X      |

#### 표 가운데 정렬 방법 :

-- | :--: | --

#### 표 오른쪽 정렬 방법 :

-- | -- | --:

# 원시 HTML (RAW HTML)

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고 닭도록<br/>
하느님이 보우하사 우리나라 만세

but, 더 간단한 방법으로 'u'태그를 더 많이 사용한다.

<img width="70" src="이미지경로" alt="대체텍스트" />

<br><br>

# 수평선 3가지 방법: 
<br>

---

<br>

***

<br>

___

