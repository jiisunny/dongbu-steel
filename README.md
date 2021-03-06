[![Netlify Status](https://api.netlify.com/api/v1/badges/9f2f756f-e1fc-48d9-9c07-b7d7433d8aaa/deploy-status)](https://app.netlify.com/sites/kind-fermi-b4f9a0/deploys)


# Dongbu Steel λλΆμ μ²  π¨π»βπ§π©π»βπ­

λλΆμ μ²  ννμ΄μ§ μ μ

[λλΆμ μ²  ννμ΄μ§](https://kind-fermi-b4f9a0.netlify.app/index.html)

[λλΆμ μ²  μλΈνμ΄μ§ - νμ¬μκ°](https://kind-fermi-b4f9a0.netlify.app/introduce.html)

![λλΆμ μ² ](https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/_assets/main_screenshot.png)

<br />

## μ€ν κ·Έλν(The Open Graph protocol)

μΉνμ΄μ§κ° μμ λ―Έλμ΄(νμ΄μ€λΆ, μΉ΄μΉ΄μ€ν‘ λ±)λ‘ κ³΅μ λ  λ μ°μ μ μΌλ‘ νμ©λλ μ λ³΄λ₯Ό μ§μ νλ€.

KakaoTalk -

![KakaoTalk Open Graph example](https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/_assets/kakao_opengraph_example.png)

[λ λ§μ μ€ν κ·Έλν μμ± λ³΄κΈ°](https://ogp.me/)

```html
<!-- μ€ν κ·Έλν(The Open Graph protocol) -->
<meta property="og:type" content="website" />
<meta property="og:site_name" content="λλΆμ μ² " />
<meta property="og:title" content="Dongbu Steel Korea" />
<meta property="og:description" content="λλΆμ μ² μ μ€μ² κ°μ¬ μμ°μμ²΄, λμ°, μμ°λ, μ κΈ° μμ°λκΈ, μΉΌλΌ λ° μλ κ°ν λ± μ νμ μ·¨κΈνκ³  μμ΅λλ€." />
<meta property="og:image" content="./images/dongbusteel_seo" />
<meta property="og:url" content="https://kind-fermi-b4f9a0.netlify.app/" />
```

- `og:type`: νμ΄μ§μ μ ν(E.g, `website`, `video.movie`)
- `og:site_name`: μν μ¬μ΄νΈμ μ΄λ¦
- `og:title`: νμ΄μ§μ μ΄λ¦(μ λͺ©)
- `og:description`: νμ΄μ§μ κ°λ¨ν μ€λͺ
- `og:image`: νμ΄μ§μ λν μ΄λ―Έμ§ μ£Όμ(URL)
- `og:url`: νμ΄μ§ μ£Όμ(URL)

## νΈμν° μΉ΄λ(Twitter Cards)

μΉνμ΄μ§κ° μμ λ―Έλμ΄(νΈμν°)λ‘ κ³΅μ λ  λ μ°μ μ μΌλ‘ νμ©λλ μ λ³΄λ₯Ό μ§μ νλ€.

[λ λ§μ νΈμν° μΉ΄λ λ³΄κΈ°](https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started)

```html
<!-- νΈμν° μΉ΄λ(Twitter Cards) -->
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="λλΆμ μ² " />
<meta property="twitter:title" content="Dongbu Steel Korea" />
<meta property="twitter:description" content="λλΆμ μ² μ μ€μ² κ°μ¬ μμ°μμ²΄, λμ°, μμ°λ, μ κΈ° μμ°λκΈ, μΉΌλΌ λ° μλ κ°ν λ± μ νμ μ·¨κΈνκ³  μμ΅λλ€." />
<meta property="twitter:image" content="./images/dongbusteel_seo.jpg" />
<meta property="twitter:url" content="https://kind-fermi-b4f9a0.netlify.app/" />
```

- `twitter:card`: νμ΄μ§(μΉ΄λ)μ μ ν(E.g. `summary`, `player`)
- `twitter:site`: μν μ¬μ΄νΈμ μ΄λ¦
- `twitter:title`: νμ΄μ§μ μ΄λ¦(μ λͺ©)
- `twitter:description`: νμ΄μ§μ κ°λ¨ν μ€λͺ
- `twitter:image`: νμ΄μ§μ λν μ΄λ―Έμ§ μ£Όμ(URL)
- `twitter:url`: νμ΄μ§ μ£Όμ(URL)

## Favicon(νλΉμ½, favorites icon)

μΉνμ΄μ§λ₯Ό λνλ΄λ μμ΄μ½, μΉνμ΄μ§μ λ‘κ³ λ₯Ό μ€μ νλ€.<br/>
λλΆλΆμ κ²½μ° λ£¨νΈ κ²½λ‘μ `favicon.ico` νμΌμ μμΉνλ©΄ μλμΌλ‘ λ‘λ©νκΈ° λλ¬Έμ `<link />`λ₯Ό μμ±ν  νμκ° μλ€. `favicon.png` νμΌμ μ¬μ©νλ €λ©΄ λ€μκ³Ό κ°μ΄ `<link />`λ₯Ό μμ±ν΄μΌνλ€.

> νλΉμ½ μ΄λ―Έμ§λ λ£¨νΈ κ²½λ‘μ μμ΄μΌ νλ€
```html
<!--<link rel="shortcut icon" href="favicon.ico" />-->
<link rel="icon" href="./favicon.png" />
```

- `favicon.ico` 64 x 64 (px) λλ 32 x 32 λλ 16 x 16
- `favicon.png` 500 x 500 (px)

<img src="https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/favicon.png" alt="dongbu-steel" width="16" /><br />
<img src="https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/favicon.png" alt="dongbu-steel" width="200" />

### .ico νμΌ μ μ

μ΄λ―Έμ§λ₯Ό μλ‘λνλ©΄ μμ½κ² `.ico` νμΌμ μ μν  μ μλ€.

[iconifier.net](https://iconifier.net/)

## Reset.css

κ° λΈλΌμ°μ μ κΈ°λ³Έ μ€νμΌμ μ΄κΈ°ν ν  μ μλ css νμΌ λ§ν¬

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
```

## HTML select νκ·Έ

HTML `<select>` μμλ μ΅μ λ©λ΄λ₯Ό μ κ³΅νλ μ»¨νΈλ‘€μ λνλΈλ€.

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
`<select>` μμλ CSSλ₯Ό μ¬μ©ν΄ λ°μ€λͺ¨λΈ, κΈμ¨μ²΄ λ± μΌλΆλΆμ λ€λ₯Έ μμμ²λΌ μ€νμΌ μ μ©μ΄ κ°λ₯νλ€. <br />

> κΈ°λ³Έ μμ€ν μΈν μ κ±°νκΈ° : [appearance (en-US)](https://developer.mozilla.org/en-US/docs/Web/CSS/appearance)

## CSS Background img hover ν¨κ³Ό

![λλΆμ μ²  hover ν¨κ³Ό](https://raw.githubusercontent.com/jiisunny/dongbu-steel/master/_assets/main_hover_screenshot.png)

`<div class="bg"></div>` λ₯Ό μμ±ν΄ hover μ λνλ  λ°°κ²½μ΄λ―Έμ§λ₯Ό λ£μ΄μ€λ€.

```html
<!-- CONTENTS -->
<section id="wrap">
  <!-- λμ° -->
  <article id="con1">
    <div class="bg"></div>
    <div class="contents">
        <h3>λμ°</h3>
        <p>μ©κ΄λ‘, μ λ‘, μ΄μ°κ³΅μ μ κ±°μ³ μμ°λ Hot Coilμ νμ μνλ₯Ό κ°ν΄ μκ² λ§λ  κ°νμΌλ‘ μλμ°¨, κ°μ μ ν λ± λ€μν μ©λλ‘ μ¬μ©λλ κΈ°μ΄μ² κ°μ¬μλλ€. </p>
    </div>
    <div class="text">
        <h3>μ νμ©λ</h3>
        <p>μλμ°¨ μ°¨μ²΄, TVλΈλΌμ΄κ΄, μ»΄ν¨ν° λͺ¨λν°μ© λΆν, λμ₯κ³ , μμ΄μ»¨, κ°μ μ ν Body λ± </p>
        <a class="more">λλ³΄κΈ°</a>
    </div>
  </article>
  <!-- μμ°λ -->
  <article id="con2">
    <div class="bg"></div>
    <div class="contents">
        <h3>μμ°λ</h3>
        <p>κΈ°μ΄μμ¬μΈ λμ°κ°νμ μμ°μ λκΈν κ²μΌλ‘ λμ°κ°νμ λΉν΄ λΆμμ΄ μ λμ§ μλλ€λ νΉμ±μ κ°μ§κ³  μμ΅λλ€.</p>
    </div>
    <div class="text">
        <h3>μ νμ©λ</h3>
        <p>κ±΄μΆμ© λ΄/μΈμ₯μ¬, μλμ°¨μ© λΆν, κ°μ μ©, κΈ°ν / μ‘°κ΄ λ° μΉΌλΌλμ₯μ© λ±</p>
        <a class="more">λλ³΄κΈ°</a>
    </div>
  </article>
  <!-- μλ -->
  <article id="con3">
    <div class="bg"></div>
    <div class="contents">
        <h3>μλ </h3>
        <p>λμ°κ°νμ μ£Όμμ λκΈν κ°νμΌλ‘ μλ¦λ€μ΄ κΈμκ΄νμ κ°μ§λ©°, κ°κ³΅μ± λ° λ΄μμ±μ΄ λ°μ΄λκ³  μΈμ²΄μ λ¬΄ν΄ν κ°νμλλ€.</p>
    </div>
    <div class="text">
        <h3>μ νμ©λ</h3>
        <p>DR TP & TFS, κ·Ήλ° TFS κ°ν, κ΄ν­ TP/TFS λ±</p>
        <a class="more">λλ³΄κΈ°</a>
    </div>
  </article>
  <!-- PEB -->
  <article id="con4">
    <div class="bg"></div>
    <div class="contents">
        <h3>PEB</h3>
        <p>λλΆ PEBμμ€νμ κ³΅κ°κ³νμμ λΆμ¬μ€κ³, μ μκΉμ§μ μ  κ³΅μ μ΄ μΌκ΄ μ€κ³ νλ‘κ·Έλ¨μ μν΄ μν κ΄λ¦¬λλ μ²¨λ¨μ² κ³¨κ±΄μΆμμ€νμλλ€.</p>
    </div>
    <div class="text">
        <h3>μ νμ©λ </h3>
        <p>κ³΅μ₯, λ¬Όλ₯μΌν°, μμμ© κ±΄λ¬Ό, λν μ ν΅μκ°, μ²΄μ‘κ΄ λ±</p>
        <a class="more">λλ³΄κΈ°</a>
    </div>
  </article>
  <!-- μΉΌλΌ -->
  <article id="con5">
    <div class="bg"></div>
    <div class="contents">
        <h3>μΉΌλΌ</h3>
        <p>λμ°κ°ν, μμ°λκΈκ°ν, μλ£¨λ―Έλκ°ν λ±μ νμΈνΈλ₯Ό μνκ±°λ μΈμνλ¦μ μ μ°©μμΌ νλ©΄μ μκΉ, λλ λ¬΄λ¬λ₯Ό μν κ°νμλλ€.</p>
    </div>
    <div class="text">
        <h3>μ νμ©λ</h3>
        <p>κ±΄μΆλ΄μΈμ₯μ¬, κ°μ μ ν(λμ₯κ³ , μΈνκΈ°, μμ΄μ»¨ λ±), Show-case λ±</p>
        <a class="more">λλ³΄κΈ°</a>
    </div>
  </article>
  <!-- κ°κ΄ / νκ° -->
  <article id="con6">
    <div class="bg"></div>
    <div class="contents">
        <h3>κ°κ΄ / νκ°</h3>
        <p>κ°νμΌλ‘ λ§λ  μμ‘μ©/κ΅¬μ‘°μ© λΆκ°μ νμΌλ‘, κ°μ’ μ€λΉμΈνλΌ λ° κ±΄λ¬Όμ κΈ°μ΄λ₯Ό λ΄λΉνκ³  μμ΅λλ€.</p>
    </div>
    <div class="text">
        <h3>μ νμ©λ</h3>
        <p>κ°κ΄ : μΌλ° λ°°κ΄ μ©μ κ΄, μλμ© μμ°λ κ°κ΄ λ±<br />
        νκ° : μ² κ³¨κ΅¬μ‘°λ¬Ό, μννΈ μ₯μ μ‘°νλ¬Ό, μννΈ μ§λΆμ² κ³¨ λ±</p>
        <a class="more">λλ³΄κΈ°</a>
    </div>
  </article>
</section>
```

<br />

bg ν΄λμ€μ μμΉλ₯Ό `bottom: 976px;`λ‘ μ μ©ν΄ νμ΄μ§μμ μ¨κ²¨μ€λ€.

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

hoverμ μ¨κ²¨μ€ λ°°κ²½μ΄λ―Έμ§κ° λνλλλ‘ μμΉκ°μ `bottom: 0;`λ‘ μλ ₯ν΄μ€λ€.

```css
#wrap > article:hover > .bg {
  bottom: 0;
}
```