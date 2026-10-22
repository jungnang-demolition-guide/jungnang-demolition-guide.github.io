# 중랑 철거·원상복구 가이드 — GitHub Pages 업로드 안내

이 ZIP에는 **이미 배포된 홈페이지가 아닌**, GitHub Pages에 올릴 정적 웹사이트 파일이 있습니다.

- 선택한 사이트 주소: https://jungnang-demolition-guide.github.io/
- Organization 이름: `jungnang-demolition-guide`
- Repository 이름: `jungnang-demolition-guide.github.io`
- 저장소 Visibility: **Public**
- 기본 브랜치: **main**
- Pages Source: **Deploy from a branch**
- Pages Branch / Folder: **main** / **/(root)**

## 초보자용 업로드 순서

1. ZIP 파일을 PC에서 **압축 해제**합니다.
2. GitHub에 로그인하고 `jungnang-demolition-guide` 이름의 Organization을 만듭니다. 이미 있다면 그 Organization을 선택합니다.
3. 해당 Organization에 `jungnang-demolition-guide.github.io`라는 **Public 저장소**를 만듭니다. 저장소명은 오타 없이 정확해야 합니다.
4. 저장소 화면의 **Add file → Upload files**를 누릅니다.
5. 압축 해제한 폴더 자체를 업로드하지 말고, **그 안의 `index.html`, `assets` 폴더, `robots.txt`, `sitemap.xml`, `.nojekyll`, `README.md`, `favicon.png`를 모두 저장소 최상위(root)** 에 업로드합니다. `index.html`이 저장소 첫 화면에 보여야 합니다.
6. 하단 **Commit changes**로 파일을 저장합니다.
7. 저장소에서 **Settings → Pages**를 열고 **Source = Deploy from a branch**, **Branch = main**, **Folder = /(root)**로 설정하고 Save합니다.
8. 배포 처리가 완료된 후 브라우저에서 https://jungnang-demolition-guide.github.io/ 에 접속해 확인합니다. 주소가 뜨지 않으면 Repository 이름과 Pages 설정, 배포 상태를 다시 확인합니다.
9. 내용을 수정할 때는 PC에서 파일을 바꾼 다음 같은 파일 경로로 재업로드하고 Commit합니다.

## 반드시 확인할 항목

- 랜딩 이미지: `assets/images/landing.webp` — **원본 936×7593px**, 재압축·리사이즈 없이 ZIP에서 추출했습니다.
- HTML 배치: H1 → 첫 본문 P → 랜딩 이미지 → 첫 H2
- 랜딩 이미지 **어느 부분을 클릭해도 새 탭에서 지정한 구글폼으로 열려야 합니다**: https://docs.google.com/forms/d/e/1FAIpQLSfdzNitwdwclnvlcy6wj8D73z8kBuRSHsiyCp-L3XB9agx9bQ/viewform?usp=header
- 본문 ‘중랑구 철거업체 안내 살펴보기’ 링크는 별도의 타겟링크입니다: https://store-return.netlify.app/jungnang-gu-demolition-company/
- `assets/images/thumbnail.webp` — **1254×1254px** 정사각형 썸네일, Open Graph/Twitter 미리보기 사용
- `favicon.png` — 128×128px
- SEO: 한국어 설정, title, description, canonical, OG/Twitter 메타, WebSite/WebPage JSON-LD, robots.txt, sitemap.xml
- Google/Naver 검색엔진 소유권 확인 메타 태그는 제공되지 않아 포함하지 않았습니다. 발급받으면 `<head>`에 추가하세요.

## 지원금 정보 관련 유의

2026년 희망리턴패키지 점포철거비 지원 신규 신청은 **2026년 10월 21일 18:00 마감**으로 소상공인시장진흥공단 공지가 확인되었습니다(페이지 본문 기준일: 2026-10-22). 지원제도는 변동될 수 있으므로 추후 공식 공고를 다시 확인한 뒤 갱신하세요.

공식 안내: https://www.sbiz.or.kr/nhrp/ 및 https://www.sbiz24.kr/

※ 이 ZIP 자체는 GitHub 저장소 생성이나 온라인 배포를 수행하지 않습니다.
