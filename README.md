# 로또 번호 추천 🎱

매번 새로 뽑는 로또 6/45 번호 추천 페이지입니다.

- 구글 첫 화면처럼 화면 정중앙에 번호 6개만 보여주는 초미니멀 레이아웃입니다.
- **번호 뽑기** 버튼으로 6개 번호를 다시 뽑습니다.
- 오른쪽 복사 버튼으로 현재 번호를 `01, 12, ...` 형식으로 복사합니다.
- 동행복권 공 색상 규칙(1~10 노랑, 11~20 파랑, 21~30 빨강, 31~40 회색, 41~45 초록)을 적용했습니다.
- 빌드 없이 동작하는 단일 HTML 파일(`index.html`)이며, 모바일 우선 반응형입니다.

## SEO

- `index.html` `<head>`: title, description, canonical, Open Graph, robots(index, follow)
- `robots.txt`: 전체 허용 + sitemap 위치
- `sitemap.xml`: 사이트 루트 URL 등록

## 안내

본 사이트는 조합 참고용이며, 로또는 매 회차 독립 시행입니다. 어떤 번호도 당첨 확률을 높이지 않습니다.

## 배포

GitHub Pages(`main` 브랜치 루트)로 배포됩니다.

- URL: https://491434ss-create.github.io/Lotto-pick/
