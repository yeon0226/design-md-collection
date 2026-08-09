---
version: alpha
name: onjeon-beauty-lounge-design-analysis
description: "핑크 파스텔 배경 위에 뉴트럴 차콜 타이포가 얹힌 프라이빗 뷰티 라운지 시스템. 더스티 핑크 단일 포인트 컬러가 CTA·탭·별점·불릿에만 제한적으로 쓰이고, 텍스트는 브랜드 색조에 물들지 않는다. 섹션 배경은 핑크 3단계 + 웜 크림 + 화이트가 교차하며 리듬을 만들고, 딥 차콜 푸터가 페이지를 앵커한다. 디스플레이는 웰컴체, 본문·UI는 Pretendard의 2서체 체계."

colors:
  primary: "#C1798B"
  ink: "#3D3535"
  canvas: "#FFFFFF"
  bg-blush: "#F4D9DE"
  surface-blush-soft: "#FAF1F3"
  surface-cream: "#F8F1EB"
  surface-rosewater: "#F4E1E5"
  near-white: "#FDFDFD"
  on-dark: "#F4EDEA"
  on-dark-soft: "#EDEDED"
  divider: "#F0E4E1"
  border-light: "#E9E9E9"
  neutral-placeholder: "#E2E2E2"
  map-neutral: "#D9D9D9"

typography:
  display:
    fontFamily: "WelcomeOTF Bold"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.45
    letterSpacing: -1.6px
  title:
    fontFamily: "WelcomeOTF Regular"
    fontSize: 30px
    fontWeight: 400
    lineHeight: 43px
    letterSpacing: 0
  title-strong:
    fontFamily: "WelcomeOTF Bold"
    fontSize: 30px
    fontWeight: 700
    lineHeight: 43px
    letterSpacing: -0.6px
  logo:
    fontFamily: "WelcomeOTF Bold"
    fontSize: 18px
    fontWeight: 700
    letterSpacing: -0.36px
  subhead:
    fontFamily: "Pretendard"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 33px
    letterSpacing: 0
  body:
    fontFamily: "Pretendard"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 29px
    letterSpacing: -0.36px
  body-strong:
    fontFamily: "Pretendard"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 29px
    letterSpacing: -0.36px
  body-sm:
    fontFamily: "Pretendard"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 27px
    letterSpacing: -0.32px
  quote:
    fontFamily: "Pretendard"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: -0.34px
  price-item:
    fontFamily: "Pretendard"
    fontSize: 17px
    fontWeight: 600
    letterSpacing: -0.34px
  info-label:
    fontFamily: "Pretendard"
    fontSize: 15px
    fontWeight: 600
    letterSpacing: -0.3px
  info-value:
    fontFamily: "Pretendard"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 26px
    letterSpacing: -0.3px
  caption:
    fontFamily: "Pretendard"
    fontSize: 13px
    fontWeight: 400
    letterSpacing: -0.26px
  step-label:
    fontFamily: "Pretendard"
    fontSize: 12px
    fontWeight: 600
    letterSpacing: -0.24px
  button:
    fontFamily: "Pretendard"
    fontSize: 18px
    fontWeight: 500
    letterSpacing: -0.36px
  button-sm:
    fontFamily: "Pretendard"
    fontSize: 16px
    fontWeight: 500
    letterSpacing: -0.32px
  pill:
    fontFamily: "Pretendard"
    fontSize: 12px
    fontWeight: 600
    letterSpacing: -0.24px
  nav:
    fontFamily: "Pretendard"
    fontSize: 16px
    fontWeight: 400
    letterSpacing: 0
  footer-label:
    fontFamily: "Pretendard"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: -0.24px
  footer-value:
    fontFamily: "Pretendard"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: -0.26px

rounded:
  xs: 5px
  sm: 9px
  md: 10px
  lg: 12px
  pill: 9999px
  fillet: 184px

spacing:
  xs: 8px
  sm: 12px
  md: 16px
  lg: 20px
  xl: 24px
  2xl: 32px
  3xl: 40px
  4xl: 48px
  5xl: 56px
  section: 96px ~ 120px
  side-gutter: 200px

components:
  gnb:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav}"
    height: 72px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.canvas}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.xs}"
    padding: 9px 20px
  button-soft:
    backgroundColor: "{colors.surface-blush-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.xs}"
    padding: 12px 24px
  button-outline:
    backgroundColor: transparent
    border: "1px {colors.primary}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.xs}"
    padding: 12px 24px
  pill-link:
    backgroundColor: transparent
    border: "1px {colors.primary}"
    textColor: "{colors.primary}"
    typography: "{typography.pill}"
    rounded: "{rounded.pill}"
    padding: 6px 16px
  tab-bar:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.canvas}"
    rounded: "9px 9px 0 0"
    height: 70px
  tab-content-panel:
    backgroundColor: "{colors.near-white}"
    rounded: "0 0 9px 9px"
    padding: 40px
  step-card:
    backgroundColor: "{colors.canvas}"
    labelColor: "{colors.primary}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: 32px 28px
  review-card:
    backgroundColor: "{colors.canvas}"
    border: "1px {colors.border-light}"
    starColor: "{colors.primary}"
    typography: "{typography.quote}"
    rounded: "{rounded.lg}"
    padding: 28px
  price-board:
    backgroundColor: "{colors.canvas}"
    rowDivider: "1px {colors.divider} (하단, 마지막 행 제외)"
    typography: "{typography.price-item}"
    rounded: "{rounded.sm}"
    padding: 28px 48px
  photo-frame:
    rounded: "{rounded.sm} ~ {rounded.md}"
  photo-hero-fillet:
    rounded: "우상단 {rounded.fillet}, 페이지당 1개소"
  map-frame:
    backgroundColor: "{colors.map-neutral}"
    rounded: "{rounded.lg}"
  footer:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    accentColor: "{colors.primary}"
    typography: "{typography.footer-value}"
    padding: 56px 200px
  top-button:
    border: "1px {colors.primary}"
    rounded: "{rounded.pill}"
    size: 56px
---

## Overview

핑크 파스텔을 배경 언어로, 뉴트럴 차콜을 텍스트 언어로 분리한 프라이빗 뷰티 라운지 시스템이다. 브랜드 컬러 {colors.primary}(더스티 핑크)는 배경을 물들이는 데 쓰이지 않고 CTA 버튼, 탭 바, 별점, STEP 라벨, 이력 불릿, 아웃라인처럼 시선이 가야 할 포인트에만 등장한다. 모든 텍스트는 {colors.ink} 하나로 통제되어, 파스텔 배경 위에서도 가독성이 흔들리지 않는다.

섹션 배경은 같은 색이 반복되지 않도록 톤 변주로 설계됐다: 히어로 {colors.bg-blush} → 화이트 → 블러시 {colors.surface-blush-soft} → 화이트 → 웜 크림 {colors.surface-cream} → 로즈워터 {colors.surface-rosewater} → 화이트 → 다시 {colors.bg-blush}, 그리고 마지막에 {colors.ink} 딥 차콜 푸터가 페이지 전체를 눌러 앵커한다. 서체는 2단 체계 — 30px 이상 디스플레이 계층과 로고는 웰컴체(WelcomeOTF), 본문·버튼·캡션·UI 전반은 Pretendard가 담당한다.

**Key Characteristics:**

- 포인트 컬러 원칙: {colors.primary}는 버튼·탭·별점·라벨·불릿·테두리 전용 — 텍스트와 대면적 배경에는 사용하지 않는다
- 텍스트 단일색: 제목부터 캡션까지 전부 {colors.ink}, 위계는 서체 전환(웰컴체↔Pretendard)과 굵기(400↔500·600·700)로만
- 배경 5톤 변주: {colors.bg-blush} / {colors.surface-blush-soft} / {colors.surface-cream} / {colors.surface-rosewater} / {colors.canvas} 교차 리듬
- 시그니처 부분 필렛: 히어로 이미지 우상단 {rounded.fillet} 1개소 — 페이지의 유일한 대형 곡률 포인트
- 저곡률 radius 체계: {rounded.xs}(버튼) ~ {rounded.lg}(리뷰·지도), 그림자 없이 배경 명도 차로만 층위 구분
- 딥 차콜 푸터 앵커: 파스텔 페이지의 마무리를 {colors.ink} 배경 + {colors.on-dark} 텍스트 + {colors.primary} 액센트로 잠근다
- 표 행 구분선 허용: 가격표에만 1px {colors.divider} — 장식 라인은 그 외 어디에도 없다

## Colors

### Brand & Accent

- **Dusty Pink** ({colors.primary}): 유일한 브랜드 포인트. GNB 예약 버튼, 탭 바 배경, 별점, STEP 라벨, 이력 불릿, 아웃라인 버튼·pill 테두리, 푸터 심볼·탑 버튼. 대면적 배경으로는 쓰지 않는다.

### Surface

- **Canvas** ({colors.canvas}): 기본 페이지 배경, 브랜드 스토리·포트폴리오·원장 소개 섹션, 카드·보드 표면
- **Blush Strong** ({colors.bg-blush}): 히어로와 최종 CTA 섹션 — 브랜드 무드를 여닫는 대문 색
- **Blush Soft** ({colors.surface-blush-soft}): 3-Step 섹션 배경, 소프트 버튼 배경
- **Warm Cream** ({colors.surface-cream}): 리뷰 섹션 — 핑크 연속을 끊는 보조 온도
- **Rosewater** ({colors.surface-rosewater}): 프라이스 보드 섹션
- **Near-White** ({colors.near-white}): 탭 콘텐츠 패널
- **Map Neutral** ({colors.map-neutral}) / **Placeholder** ({colors.neutral-placeholder}): 콘텐츠 대기 영역 전용

### Text

- **Ink** ({colors.ink}): 모든 텍스트의 단일 색. 푸터에서는 배경색으로 반전 사용
- **On Dark** ({colors.on-dark}) / **On Dark Soft** ({colors.on-dark-soft}): 딥 차콜 푸터 위 라이트 텍스트

### Semantic

- **Divider** ({colors.divider}): 가격표 행 구분선 1px — 유일하게 허용된 라인
- **Border Light** ({colors.border-light}): 리뷰 카드 1px 테두리

## Typography

### Hierarchy

| Token | Family | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|---|
| {typography.display} | WelcomeOTF Bold | 32px | 700 | 1.45 | -1.6px | 히어로 헤드라인 |
| {typography.title} | WelcomeOTF Regular | 30px | 400 | 43px | 0 | 섹션 타이틀 |
| {typography.title-strong} | WelcomeOTF Bold | 30px | 700 | 43px | -0.6px | 전환 섹션 타이틀 (원장·예약) |
| {typography.logo} | WelcomeOTF Bold | 18px | 700 | — | -0.36px | GNB·푸터 워드마크 |
| {typography.subhead} | Pretendard | 20px | 600 | 33px | 0 | 카드 타이틀, 탭 소제목 |
| {typography.body} | Pretendard | 18px | 400 | 29px | -0.36px | 기본 본문 |
| {typography.body-strong} | Pretendard | 18px | 600 | 29px | -0.36px | 본문 강조 |
| {typography.body-sm} | Pretendard | 16px | 400 | 27px | -0.32px | 카드 설명, 이력 리스트 |
| {typography.quote} | Pretendard | 17px | 400 | 28px | -0.34px | 리뷰 인용문 |
| {typography.price-item} | Pretendard | 17px | 600 | — | -0.34px | 가격표 항목·금액 |
| {typography.info-label} | Pretendard | 15px | 600 | — | -0.3px | 운영 정보 라벨 |
| {typography.info-value} | Pretendard | 15px | 400 | 26px | -0.3px | 운영 정보 값 |
| {typography.caption} | Pretendard | 13px | 400 | — | -0.26px | 소요 시간, 리뷰 작성자, 안내 문구 |
| {typography.step-label} | Pretendard | 12px | 600 | — | -0.24px | STEP 라벨 ({colors.primary}) |
| {typography.button} | Pretendard | 18px | 500 | — | -0.36px | CTA 버튼 |
| {typography.button-sm} | Pretendard | 16px | 500 | — | -0.32px | GNB 버튼 |
| {typography.pill} | Pretendard | 12px | 600 | — | -0.24px | 아웃라인 pill 링크 |
| {typography.nav} | Pretendard | 16px | 400 | — | 0 | GNB 메뉴 |
| {typography.footer-label} | Pretendard | 12px | 600 | 20px | -0.24px | 푸터 라벨 |
| {typography.footer-value} | Pretendard | 13px | 400 | 20px | -0.26px | 푸터 값·링크 |

### Principles

- 2서체 체계: 30px 이상 디스플레이 계층 + 워드마크만 웰컴체, 그 외 전부 Pretendard — 감성과 가독성의 역할 분리
- 자간은 크기에 비례해 조인다: display -1.6px → body -0.36px → caption -0.26px. 양수 자간은 어디에도 없다
- 위계는 색이 아니라 서체 전환과 굵기 대비로: 텍스트 색은 {colors.ink} 하나
- 본문 행간 29px(1.61), 정보성 텍스트 20px — 읽는 텍스트와 스캔하는 텍스트의 밀도를 다르게

## Layout

### Spacing System

- 섹션 상하 패딩: {spacing.section} (96~120px)
- 좌우 거터: {spacing.side-gutter} (1440px 기준, 콘텐츠 폭 1040px)
- 섹션 제목 ↔ 콘텐츠: {spacing.3xl} ~ {spacing.4xl}
- 카드 그리드 거터: {spacing.lg} ~ {spacing.xl}
- 카드 내부 패딩: {spacing.2xl} 안팎 (28~32px)
- 가격표 행 상하: 18px

### Grid & Container

- 풀와이드 섹션 배경(1440px) + 중앙 콘텐츠 1040px
- 3-Step 카드 3컬럼 / 포트폴리오 사진 3컬럼 / 리뷰 2×2 그리드 / 가격표 1컬럼 보드
- 2단 분할 섹션(브랜드 스토리·원장 소개)은 이미지 420~440px + 텍스트 필

### Whitespace Philosophy

배경 톤이 섹션을 구분하므로 콘텐츠는 라인 없이 여백만으로 분리된다. 파스텔 톤 사이에 화이트 섹션이 끼어들어 호흡을 만들고, 섹션 패딩 96~120px이 스크롤 리듬을 유지한다.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 (flat) | 그림자·테두리 없음 | 모든 섹션 배경, 버튼, 탭 바 |
| 1 (hairline) | 1px {colors.border-light} | 리뷰 카드 |
| 1 (divider) | 1px {colors.divider} 하단 | 가격표 행 |
| 2 (tone shift) | 배경 명도 차 | 섹션·패널 층위 구분 (그림자 대체) |

그림자를 쓰지 않는 시스템이다. 깊이는 배경 5톤의 명도 차와 radius로만 표현한다.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| {rounded.xs} | 5px | 모든 버튼, 서명 프레임 |
| {rounded.sm} | 9px | 스텝 카드, 포토 프레임, 탭 바(상단만), 프라이스 보드 |
| {rounded.md} | 10px | 인물·스토리 포토 프레임 |
| {rounded.lg} | 12px | 리뷰 카드, 지도 프레임 |
| {rounded.pill} | 9999px | pill 링크, 탑 버튼(원형) |
| {rounded.fillet} | 184px | 히어로 이미지 우상단 1개소 — 시그니처 |

### Image Geometry

- 히어로 이미지: 484×440, 우상단 {rounded.fillet} 부분 필렛
- 세로형 포토: 4:5 내외 ({rounded.sm}~{rounded.md})
- 이미지 톤: 자연광 실사, 웜톤 저채도 — 파스텔 배경과 온도를 맞춘다

## Components

### Buttons

- **button-primary** — {colors.primary} 배경 + 화이트 텍스트, {rounded.xs}. GNB 예약하기 등 최상위 전환 버튼 전용
- **button-soft** — {colors.surface-blush-soft} 배경 + {colors.ink} 텍스트. 파스텔 섹션 위 CTA (히어로·예약)
- **button-outline** — 1px {colors.primary} 테두리 + {colors.ink} 텍스트. 보조 CTA (카카오톡 상담)
- **pill-link** — {rounded.pill} + 1px {colors.primary} 테두리 + {colors.primary} 텍스트 12px. 인스타그램 더보기 등 외부 링크

### Tabs

- **tab-bar** — {colors.primary} 배경, 상단만 9px 라운드, 높이 70px. 활성 탭은 화이트 Bold + 하단 4px 도트, 비활성은 라이트 60%
- **tab-content-panel** — {colors.near-white} 배경, 하단만 9px 라운드, 패딩 40px

### Cards

- **step-card** — 화이트 {rounded.sm}, 패딩 32×28. {colors.primary} STEP 라벨 + {typography.subhead} 타이틀 + {typography.body-sm} 설명
- **review-card** — 화이트 + 1px {colors.border-light}, {rounded.lg}, 패딩 28. {colors.primary} 별점 + {typography.quote} 인용 + {typography.caption} 작성자

### Price Board

- 화이트 보드 {rounded.sm}, 패딩 28×48. 행마다 항목({typography.price-item}) + 소요 시간({typography.caption}) + 금액({typography.price-item})
- 행 사이 1px {colors.divider} 하단 구분선 (마지막 행 제외) — 이 시스템에서 유일하게 허용된 라인

### Navigation & Footer

- **gnb** — 화이트 72px, 로고({typography.logo}) + 메뉴 5개({typography.nav}) + button-primary
- **footer** — {colors.ink} 배경 앵커. 로고 행(심볼 {colors.primary} + 워드마크) + 라벨/값 2컬럼 그리드({typography.footer-label}/{typography.footer-value}, {colors.on-dark}) + SNS·법적 고지 행. 우상단 56px 원형 탑 버튼(1px {colors.primary})

## Do's and Don'ts

### Do

- {colors.primary}는 버튼·탭·별점·라벨·불릿·테두리에만 — 등장할 때마다 "행동 지점"이라는 신호가 되도록 희소성을 지킨다
- 섹션 배경은 5톤({colors.bg-blush}·{colors.surface-blush-soft}·{colors.surface-cream}·{colors.surface-rosewater}·{colors.canvas})을 교차 — 인접 섹션에 같은 색을 반복하지 않는다
- 텍스트는 {colors.ink} 단일색 유지, 위계는 웰컴체↔Pretendard 전환과 굵기로만
- 디스플레이 계층(30px+)과 워드마크에만 웰컴체, 나머지는 전부 Pretendard
- 부분 필렛 {rounded.fillet}은 페이지당 1개소만 — 시그니처는 희소해야 시그니처다
- 이미지는 자연광 실사·웜톤 저채도로 통일해 파스텔 배경과 온도를 맞춘다
- 페이지 마지막은 {colors.ink} 딥 푸터로 앵커한다

### Don't

- 텍스트를 핑크 계열로 물들이지 않는다 — 브랜드 컬러는 포인트 요소 전용
- {colors.primary}를 대면적 섹션 배경으로 쓰지 않는다
- 그림자 금지 — 층위는 배경 명도 차와 radius로만
- 제목-본문 사이 장식 구분선 금지 (표 행 구분선 {colors.divider}만 예외)
- 영문 텍스트에 양수 letter-spacing 금지
- 고채도 원색(파랑·초록·빨강) 추가 금지 — 보조 톤이 필요하면 웜 크림처럼 저채도 웜 계열로
- 같은 파스텔 톤을 연속 섹션에 반복하지 않는다

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Desktop | 1440px (시안 기준) | 콘텐츠 1040px, 3-Step·포트폴리오 3컬럼, 리뷰 2×2 |
| Tablet | 확인 불가 — 시안 미제작 | — |
| Mobile | 확인 불가 — 시안 미제작 (기획안 기준: GNB는 햄버거 메뉴로 축약, 하단 고정 예약 버튼 별도 노출) | — |

### Collapsing Strategy

- 데스크톱 단일 시안 기준. 모바일 전개 시 기획안 지침을 따른다: 헤더는 햄버거로 축약, 예약 CTA는 하단 고정 바로 분리
- 타이틀 축소는 원 시스템 비율(30px → 24~25px, 약 80~83%)을 권장 기준으로 계승

