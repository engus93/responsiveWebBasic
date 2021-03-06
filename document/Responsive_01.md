# Responsive 01

## Semantic Tag

### Semantic Tag란?

> **시맨틱(Semantic)은 "의미의, 의미론적인"이라는 뜻이다.**
> 
> 예를 들어, `<div>` 태그는 **non-semantic** 태그라고 할 수 있고, `<table>`, `<article>` 등의 태그는 **semantic** 태그라고 볼 수 있다. 일반적으로 `<div>` 태그만 보고는 이 태그 안에 들어간 내용의 의미를 알 수가 없으나 `<table>`, `<article>` 등의 태그는 안에 대략 어떠한 것들이 들어갔을지 유추를 할 수가 있다.

![Semantic Tag Example](https://t1.daumcdn.net/cfile/tistory/22690B335887451A3B)

출처 : [궁금해요! 너를 알려줘! HTML5의 시맨틱 구조](https://seonueo.tistory.com/32)

### Semantic Tag 왜 사용해야 하는가?

> 검색 엔진이 파악하기 더 수월해지고 또한 SEO와 밀접한 연관이 있다.

### Semantic Tag 종류

#### 자주 쓰이는 몇가지

#### 1. `<header>`

```
<header> 태그는 웹 문서의 소개 컨텐츠 및 네비게이션 링크를 정의합니다.
```

##### 정의(Definition)

- `<header>` 태그는 웹 문서의 소개 컨텐츠 및 네비게이션 링크를 정의합니다.
- `<header>` 태그는 제목, 로고, 아이콘, 저자 정보등을 포함합니다.
- `<header>` 태그는 섹션의 제목 태그를 포함하기 위한 것이지만 필수사항은 아닙니다.

---

#### 2. `<nav>`

```
<nav> 태그는 웹 문서에 네비게이션 링크를 정의합니다.
```

##### 정의(Definition)

- `<nav>` 태그는 웹 문서에 네비게이션 링크를 정의합니다.
- `<nav>` 태그는 모든 링크가 `<nav>` 태그일 필요는 없지만, 주요 네이게이션 링크는 태그를 사용합니다.
- `<nav>` 태그는 일반적으로 `<footer>` 영역에 링크는 `<nav>` 태그를 사용하지 않습니다.
- `<nav>` 태그는 웹 문서에 여러개 있을 수 있지만 주로 사이트 탐색용과 페이지 탐색용으로 사용합니다.

---

#### 3. `<aside>`

```
<aside> 태그는 웹 문서 내에 사이드 컨텐츠를 정의합니다.
```

##### 정의(Definition)

- `<aside>` 태그는 웹 페이지의 메인 콘텐츠와 관련된 사이드의 정보, 광고 등 부분적인 정보를 그룹화 할 때 사용합니다.

---

#### 4. `<section>`

```
<section> 태그는 주제별 그룹의 콘텐츠 섹션을 정의합니다.
```

##### 정의(Definition)


- `<section>` 태그는 주제별 그룹의 콘텐츠 섹션을 정의합니다.
- `<section>` 태그는 탭 페이지, 홈페이지의 소개, 연락처, 뉴스항목 등과 같이 주제별로 분할 할 수 있습니다.
- `<section>` 태그에는 제목을 나타내는 `<h1>` ~ `<h6>` 태그가 포함되어야 합니다.
- `<section>` 태그는 문장이나 문서의 스타일링 요소가 아닙니다. 스크립트의 편의나 영역을 위함이라면 div가 좋습니다.
- `<section>` 태그가 일반적인 영역의 주제가 아니라면 구체적인 요소(`<article>`, `<aside>`, `<nav>`)를 대신 사용하는 것이 더 적절합니다.

---

#### 5. `<article>`

```
<article> 태그는 웹 문서 내에 독립적인 컨텐츠를 정의합니다.
```

##### 정의(Definition)

- `<article>` 태그는 포럼, 신문기사, 잡지, 블러그 항목, 게시판 글 등 콘텐츠의 독립적인 항목을 나타냅니다.
- `<section>`은 하나의 주제를 나타낸다면, `<article>`은 주제를 묶는 독립적인 콘텐츠를 나타냅니다.
- `<section>` 요소 안에 `<article>` 요소를 쓸 수 있으며, `<article>` 요소 안에도 `<section>` 요소를 쓸 수 있습니다.

---

#### 6. `<footer>`

```
<footer> 태그는 웹 문서의 바닥글 영역을 정의합니다.
```

##### 정의(Definition)

- `<footer>` 태그는 사이트와 관련된 정보(저작권자, 연락처, 사이트 맵, 관련된 문서 링크)가 포함됩니다.
- `<footer>` 태그는 한 문서에서 여러번 사용할 수 있습니다.
- `<footer>` 태그는 섹션을 구성하는 태그가 아니가 때문에 섹션을 잡기 위해서 사용하는 위한 태그로는 적절하지 않습니다.
- `<footer>` 태그안에는 `<address>` 요소가 포함될 수 있습니다.


## 참고 사이트

- [어제 오늘 내일](https://hianna.tistory.com/278)
- [HTML5에서의 시맨틱 웹과 시맨틱 태그(Semantic Web, Semantic tag)](https://takeuu.tistory.com/147)
- [WEB'S - HTML Reference](https://webzz.tistory.com/235)