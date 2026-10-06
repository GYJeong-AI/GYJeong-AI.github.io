[![English](docs/images/language-en-idle.svg)](README.md) [![한국어 — 현재 언어](docs/images/language-ko-active.svg)](README.ko.md)

# GY.JEONG

웹·앱·게임 프로젝트를 소개하는 GY.JEONG의 포트폴리오 웹사이트입니다.

- 사이트: [gyjeong-ai.github.io](https://gyjeong-ai.github.io/)
- 문의: [gyjeongai@gmail.com](mailto:gyjeongai@gmail.com)

## 파일 구성

- `index.html`: 페이지 내용, 스타일, 인터랙션
- `assets/images/`: 프로젝트 카드와 상세 화면에 사용하는 WebP 이미지
- `og-image-v1.png`: 링크 공유 미리보기 이미지
- `robots.txt`, `sitemap.xml`: 검색 엔진 안내
- `.nojekyll`: GitHub Pages에서 Jekyll 처리 비활성화
- `app-ads.txt`: 앱 광고 판매자 정보
- `googlef8298d34093e4625.html`: Google Search Console 소유권 확인
- `motionsports-kart-v1.png`, `motionsports-tennis-v1.png`: 기존 링크 호환성을 위해 루트에 보관한 원본 이미지

## 수정과 확인

별도 빌드 도구 없이 HTML, CSS, JavaScript로 구성되어 있습니다. 페이지는 `index.html`에서 수정하고, 프로젝트 이미지는 `assets/images/`에 둡니다. 이미지 파일명을 바꾸면 `src`, `srcset`, `data-full-src` 경로도 함께 확인합니다.

저장소 루트에서 `python3 -m http.server 8000`을 실행한 뒤 [localhost:8000](http://localhost:8000/)에서 확인할 수 있습니다. 수정 후에는 모바일·데스크톱 화면과 프로젝트 상세 이미지가 정상적으로 열리는지 확인합니다.

## 배포

GitHub Pages로 제공하는 정적 사이트입니다. 변경 사항을 검토한 뒤 저장소의 GitHub Pages 배포 설정에 따라 반영합니다.

사이트 주소와 검증 경로가 유지되도록 저장소 이름과 `.nojekyll`, `app-ads.txt`, `googlef8298d34093e4625.html`, `robots.txt`, `sitemap.xml`, `og-image-v1.png`의 루트 경로를 유지합니다.
