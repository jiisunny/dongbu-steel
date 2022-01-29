# Dongbu Steel 동부제철 👨🏻‍🔧👩🏻‍🏭

동부제철 랜딩페이지(홈페이지) 실습 예제

<br />

[동부제철 홈페이지](https://kind-fermi-b4f9a0.netlify.app/index.html)

[동부제철 회사소개 서브페이지](https://kind-fermi-b4f9a0.netlify.app/introduce.html)

<br />

## 오픈 그래프(The Open Graph protocol)

웹페이지가 소셜 미디어(페이스북, 카카오톡 등)로 공유될 때 우선적으로 활용되는 정보를 지정한다.

KakaoTalk -

![KakaoTalk Open Graph example](https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/_assets/kakao_opengraph_example.png)

[더 많은 오픈 그래프 속성 보기](https://ogp.me/)

```html
<!-- 오픈 그래프(The Open Graph protocol) -->
<meta property="og:type" content="website" />
<meta property="og:site_name" content="동부제철" />
<meta property="og:title" content="Dongbu Steel Korea" />
<meta property="og:description" content="동부제철은 스철강재 생산업체, 냉연, 아연도, 전기 아연도금, 칼라 및 석도 강판 등 제품을 취급하고 있습니다." />
<meta property="og:image" content="./images/dongbusteel_seo" />
<meta property="og:url" content="https://kind-fermi-b4f9a0.netlify.app/" />
```

- `og:type`: 페이지의 유형(E.g, `website`, `video.movie`)
- `og:site_name`: 속한 사이트의 이름
- `og:title`: 페이지의 이름(제목)
- `og:description`: 페이지의 간단한 설명
- `og:image`: 페이지의 대표 이미지 주소(URL)
- `og:url`: 페이지 주소(URL)

## 트위터 카드(Twitter Cards)

웹페이지가 소셜 미디어(트위터)로 공유될 때 우선적으로 활용되는 정보를 지정한다.

[더 많은 트위터 카드 보기](https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started)

```html
<!-- 트위터 카드(Twitter Cards) -->
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="동부제철" />
<meta property="twitter:title" content="Dongbu Steel Korea" />
<meta property="twitter:description" content="동부제철은 스철강재 생산업체, 냉연, 아연도, 전기 아연도금, 칼라 및 석도 강판 등 제품을 취급하고 있습니다." />
<meta property="twitter:image" content="./images/dongbusteel_seo.jpg" />
<meta property="twitter:url" content="https://kind-fermi-b4f9a0.netlify.app/" />
```

- `twitter:card`: 페이지(카드)의 유형(E.g. `summary`, `player`)
- `twitter:site`: 속한 사이트의 이름
- `twitter:title`: 페이지의 이름(제목)
- `twitter:description`: 페이지의 간단한 설명
- `twitter:image`: 페이지의 대표 이미지 주소(URL)
- `twitter:url`: 페이지 주소(URL)

## Favicon(파비콘, favorites icon)

웹페이지를 나타내는 아이콘, 웹페이지의 로고를 설정한다.<br/>
대부분의 경우 루트 경로에 `favicon.ico` 파일을 위치하면 자동으로 로딩하기 때문에 `<link />`를 작성할 필요가 없다. `favicon.png` 파일을 사용하려면 다음과 같이 `<link />`를 작성해야한다.

> 파비콘 이미지는 루트 경로에 있어야 한다
```html
<!--<link rel="shortcut icon" href="favicon.ico" />-->
<link rel="icon" href="./favicon.png" />
```

- `favicon.ico` 64 x 64 (px) 또는 32 x 32 또는 16 x 16
- `favicon.png` 500 x 500 (px)

<img src="https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/favicon.png" alt="dongbu-steel" width="16" /><br />
<img src="https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/favicon.png" alt="dongbu-steel" width="200" />

### .ico 파일 제작

이미지를 업로드하면 손쉽게 `.ico` 파일을 제작할 수 있다.

[iconifier.net](https://iconifier.net/)

## Reset.css

각 브라우저의 기본 스타일을 초기화 할 수 있는 css 파일 링크

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
```

## HTML select 태그

HTML `<select>` 요소는 옵션 메뉴를 제공하는 컨트롤을 나타낸다.

```html
<label for="pet-select">Choose a pet:</label>

<select name="pets" id="pet-select">
    <option value="">--Please choose an option--</option>
    <option value="dog">Dog</option>
    <option value="cat">Cat</option>
    <option value="hamster">Hamster</option>
    <option value="parrot">Parrot</option>
    <option value="spider">Spider</option>
    <option value="goldfish">Goldfish</option>
</select>
```

```css
label,
footer {
    font-family: sans-serif;
}

label {
    font-size: 1rem;
    padding-right: 10px;
}

select {
    font-size: .9rem;
    padding: 2px 5px;
}

footer {
    font-size: .8rem;
    position: absolute;
    bottom: 30px;
    left: 30px;
}

.output {
    background: center/cover no-repeat url('/media/cc0-images/hamster.jpg');
    position: relative;
}

```
`<select>` 요소는 CSS를 사용해 박스모델, 글씨체 등 일부분은 다른 요소처럼 스타일 적용이 가능하다. <br />

> 기본 시스템 외형 제거하기 : [appearance (en-US)](https://developer.mozilla.org/en-US/docs/Web/CSS/appearance)

## CSS Background img hover 효과

`<div class="bg"></div>` 를 작성해 hover 시 나타날 배경이미지를 넣어준다.

```html
<!-- CONTENTS -->
<section id="wrap">
  <!-- 냉연 -->
  <article id="con1">
    <div class="bg"></div>
    <div class="contents">
        <h3>냉연</h3>
        <p>용광로, 전로, 열연공정을 거쳐 생산된 Hot Coil제품에 압하를 가해 얇게 만든 강판으로 자동차, 가전제품 등 다양한 용도로 사용되는 기초철강재입니다. </p>
    </div>
    <div class="text">
        <h3>제품용도</h3>
        <p>자동차 차체, TV브라운관, 컴퓨터 모니터용 부품, 냉장고, 에어컨, 가전제품 Body 등 </p>
        <a class="more">더보기</a>
    </div>
  </article>
  <!-- 아연도 -->
  <article id="con2">
    <div class="bg"></div>
    <div class="contents">
        <h3>아연도</h3>
        <p>기초소재인 냉연강판에 아연을 도금한 것으로 냉연강판에 비해 부식이 잘 되지 않는다는 특성을 가지고 있습니다.</p>
    </div>
    <div class="text">
        <h3>제품용도</h3>
        <p>건축용 내/외장재, 자동차용 부품, 가전용, 기타 / 조관 및 칼라도장용 등</p>
        <a class="more">더보기</a>
    </div>
  </article>
  <!-- 석도 -->
  <article id="con3">
    <div class="bg"></div>
    <div class="contents">
        <h3>석도 </h3>
        <p>냉연강판에 주석을 도금한 강판으로 아름다운 금속광택을 가지며, 가공성 및 내식성이 뛰어나고 인체에 무해한 강판입니다.</p>
    </div>
    <div class="text">
        <h3>제품용도</h3>
        <p>DR TP & TFS, 극박 TFS 강판, 광폭 TP/TFS 등</p>
        <a class="more">더보기</a>
    </div>
  </article>
  <!-- PEB -->
  <article id="con4">
    <div class="bg"></div>
    <div class="contents">
        <h3>PEB</h3>
        <p>동부 PEB시스템은 공간계획에서 부재설계, 제작까지의 전 공정이 일관 설계 프로그램에 의해 수행 관리되는 첨단철골건축시스템입니다.</p>
    </div>
    <div class="text">
        <h3>제품용도 </h3>
        <p>공장, 물류센터, 상업용 건물, 대형 유통상가, 체육관 등</p>
        <a class="more">더보기</a>
    </div>
  </article>
  <!-- 칼라 -->
  <article id="con5">
    <div class="bg"></div>
    <div class="contents">
        <h3>칼라</h3>
        <p>냉연강판, 아연도금강판, 알루미늄강판 등에 페인트를 입히거나 인쇄필름을 접착시켜 표면에 색깔, 또는 무늬를 입힌 강판입니다.</p>
    </div>
    <div class="text">
        <h3>제품용도</h3>
        <p>건축내외장재, 가전제품(냉장고, 세탁기, 에어컨 등), Show-case 등</p>
        <a class="more">더보기</a>
    </div>
  </article>
  <!-- 강관 / 형강 -->
  <article id="con6">
    <div class="bg"></div>
    <div class="contents">
        <h3>강관 / 형강</h3>
        <p>강판으로 만든 수송용/구조용 부가제품으로, 각종 설비인프라 및 건물의 기초를 담당하고 있습니다.</p>
    </div>
    <div class="text">
        <h3>제품용도</h3>
        <p>강관 : 일반 배관 용접관, 수도용 아연도 강관 등<br />
        형강 : 철골구조물, 아파트 옥상 조형물, 아파트 지붕철골 등</p>
        <a class="more">더보기</a>
    </div>
  </article>
</section>
```

<br />

bg 클래스의 위치를 `bottom: 976px;`로 적용해 페이지에서 숨겨준다.

```css
#wrap > article > .bg {
  width: 200px; height: 976px;
  position: absolute;
  left: -10px; bottom: 976px;
  transition-duration: 0.5s;
  transition-timing-function: ease-in-out;
}
```

<br />

hover시 숨겨준 배경이미지가 나타나도록 위치값을 `bottom: 0;`로 입력해준다.

```css
#wrap > article:hover > .bg {
  bottom: 0;
}
```