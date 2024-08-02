# 해피니스 산스 Title

[배포처 바로가기](https://thehyundaifont.com/#download)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Happiness Sans Title`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/HappinessSansTitle.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/HappinessSansTitle.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Happiness Sans Title';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/HappinessSansTitle.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/HappinessSansTitle.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/HappinessSansTitle.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/HappinessSansTitle.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/subsets/HappinessSansTitle-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HappinessSansTitle/subsets/HappinessSansTitle-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Happiness Sans Title", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
해피니스 산스 글꼴의 지식재산권은 (주)현대백화점이 보유합니다. 
현대백화점 전용서체 해피니스 산스(Happiness Sans)는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 수정・변경하여 재배포하실 수 있습니다. 
 
단, 글꼴 자체를 유로로 판매하는 것은 금지하며, 해피니스 산스는 본 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어와 번들하거나 재배포 또는 판매가 가능합니다. 해피니스 산스 라이선스 전문을 포함하기 어려울 경우, 해피니스 산스 출처 표기를 권장합니다. 예) 이 페이지에는 현대백화점 서체 해피니스 산스가 적용되어 있습니다. 
 
해피니스 산스를 사용한 인쇄물, 광고물(온라인 포함)의 이미지는 현대백화점 프로모션을 위해 활용될 수 있으며, 당사의 자료 수집 및 연구 목적으로 사용될 수 있습니다. 이를 원치 않는 사용자는 언제든지 당사 고객센터로 요청 부탁드립니다. 정확한 사용 조건은 아래 해피니스 산스 라이선스 전문을 참고하시기 바랍니다. 
 
아래 "지식재산권 안내 및 라이선스" 전문을 표시하는 경우 다른 소프트웨어와 번들, 재배포 또는 판매하실 수 있습니다. 
 
본 폰트 소프트웨어는 SIL 오픈 폰트 라이선스 버전 1.1에 따라 라이선스 취득을 하였습니다. 
본 라이선스는 하단에 복사되었고 http://scripts.sil.org/OFL의 FAQ란에서도 열람가능합니다. 
 
사용 가능 범위 
간판 , 현수막 브로슈어 , 포스터 , 책 , 잡지 , 명함 , 스티커 패키지 , 제품 , 웹 페이지 , 광고 배너 , 브로슈어 , 영상 자막 , 영화 , TV광고 , 웹툰 , 게임 UI , 앱 UI , 뉴스 레터 웹진 , 프리젠 테이션 , E-book , 메신저 스티커 , 로고 , 마크 , 신문 광고 , 잡지 광고 , 지면 광고 컵 홀더 부채 , 쇼핑백 , 컵 홀더 , 포장지 , 핸드폰 케이스 , 노트 , 가방 , 신발 , 옷 등 상업적 비상업적 목적 의 제작물 등 
 
사용 불가능 범위 
폰트파일(oft/ttf)의 유료 판매
```
