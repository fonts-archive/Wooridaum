# 우리다움체

[배포처 바로가기](https://www.woorifg.com/kor/company/ci/font/contentsid/581/index.do)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Wooridaum`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Wooridaum';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Light.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Light.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Light.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Wooridaum';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Regular.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Regular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Regular.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Regular.ttf') format('truetype');
}
@font-face {
  font-family: 'Wooridaum';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/Wooridaum-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/subsets/Wooridaum-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/Wooridaum/subsets/Wooridaum-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Wooridaum", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
· 우리다움체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료 제공되며, 자유롭게 사용하실 수 있습니다. (단, CI 및 BI 제작에 사용 불가) 
· 우리다움체의 지식재산권은 우리은행에 있습니다. 
· 어떠한 이유로도 지식재산권자 이외의 사용자가 수정 및 유료로 판매하는 행위를 금지하며, 배포되는 형태 그대로 사용해야 합니다.
```
