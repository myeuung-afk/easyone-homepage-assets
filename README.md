# EasyOne Homepage Assets

이지원플랫폼 홈페이지 운영에 필요한 정적 리소스와 독립형 웹 기능 페이지를 관리하는 저장소입니다.

## 주요 용도

- PAGE24 홈페이지 삽입용 이미지 관리
- PC/모바일 반응형 배너 이미지 관리
- 라이브커머스 서비스 페이지 이미지 관리
- 자동 견적서 등 독립형 HTML/CSS/JS 기능 페이지 배포
- GitHub Pages 기반 공개 URL 제공

## Repository Description

- 국문: 이지원플랫폼 홈페이지 운영용 정적 리소스 및 기능형 페이지 관리 저장소
- 영문: Static assets and standalone web tools for EasyOne Platform homepage

## 폴더 구조

```text
images/
  main/
    메인 화면 PC/모바일 이미지
  live-commerce/
    라이브커머스 서비스 페이지 이미지

quote/
  standalone_quote_app.html
  page24_quote_button_section.html
  README.md
```

## GitHub Pages URL 구조

메인 이미지 예시:

`https://myeuung-afk.github.io/easyone-homepage-assets/images/main/main-hero-pc.png`

자동 견적서:

`https://myeuung-afk.github.io/easyone-homepage-assets/quote/standalone_quote_app.html`

## 운영 원칙

1. 파일명은 영문 소문자와 하이픈을 사용한다.
2. 한글, 공백, 특수문자 파일명은 사용하지 않는다.
3. 홈페이지 삽입용 이미지는 웹 최적화 후 업로드한다.
4. 기능형 페이지는 독립 실행 가능한 HTML 파일로 관리한다.
5. PAGE24에서 JavaScript가 필요한 기능은 직접 삽입하지 않고 GitHub Pages 외부 페이지로 연결한다.
6. PAGE24에는 이미지 URL 또는 외부 기능 페이지 링크만 연결한다.
