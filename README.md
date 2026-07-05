# easyone-homepage-assets

이지원플랫폼 홈페이지 이미지 에셋 저장소

PAGE24 홈페이지에서 사용하는 PC용/모바일용 이미지 URL을 안정적으로 관리합니다.

## 이미지 URL 사용법

이 저장소는 GitHub Pages로 서비스됩니다.

```
https://[GitHub계정명].github.io/easyone-homepage-assets/images/main/main-hero-pc.png
```

## 폴더 구조

```
images/
  main/
    main-hero-pc.png        ← 메인 히어로 (PC용, 가로형)
    main-hero-mobile.png    ← 메인 히어로 (모바일용, 세로형)
  live-commerce/
    live-section-01.png     ← 라이브커머스 섹션 1
    live-section-02.png     ← 라이브커머스 섹션 2
    live-section-03.png     ← 라이브커머스 섹션 3
```

## 파일명 규칙

- 영문 소문자 + 하이픈만 사용
- 공백, 한글 파일명 사용 금지
- 예시: `main-hero-pc.png` (O) / `메인히어로.png` (X)

## 이미지 최적화 기준

| 용도 | 권장 크기 | 포맷 |
|---|---|---|
| PC 히어로 | 1920×1080px, 1~3MB | PNG 또는 JPG |
| 모바일 히어로 | 750×1334px (9:16), 1~2MB | PNG 또는 JPG |
| 섹션 이미지 | 1200×800px 내외, 500KB~2MB | PNG 또는 JPG |

## 업로드 방법

1. 이미지를 해당 폴더에 복사
2. `git add .` → `git commit -m "이미지 추가"` → `git push`
3. 약 1~2분 후 GitHub Pages에서 URL로 접근 가능
