# AI와 함께 일하기: 귀찮은 일부터 시작하는 AX

2026 오션스탭 알럼나이 · AI 특강 발표 슬라이드 (Cofoundary × 오션스탭).

단일 HTML 파일로 동작하는 55페이지 프레젠테이션입니다.

## 실행

```bash
python3 -m http.server 8080
```

브라우저에서 `http://127.0.0.1:8080/` 접속.

## 조작

- **← / →**, 스페이스, PageUp/PageDown — 이전/다음
- **숫자 입력 후 Enter** (또는 `G`) — 해당 페이지로 바로가기
- 우측 하단 페이지 번호 **클릭** — 이동할 페이지 입력
- 주소 끝 **`#42`** — 특정 페이지로 열기 (북마크·공유 가능)
- **Home / End** — 처음 / 마지막
- **F** — 전체화면

## 도구 (서브페이지)

특강에서 쓴 도구들. GitHub Pages에서 바로 접근됩니다.

- **도구 모음**: [`/tools/`](https://cofoundary.github.io/ocean-ai-talk-slides/tools/)
- **업무툴 프롬프트 빌더**: [`/tools/prompt-builder.html`](https://cofoundary.github.io/ocean-ai-talk-slides/tools/prompt-builder.html)
- **견적서 작성 프로그램**: [`/tools/quote-builder.html`](https://cofoundary.github.io/ocean-ai-talk-slides/tools/quote-builder.html)

## 구성

- `오션스탭_발표슬라이드.html` — 슬라이드 본문 (결과물 슬라이드에서 `tools/quote-builder.html` 을 임베드)
- `three.min.js` — Three.js r128 (오프닝·소개 슬라이드의 파티클 링 3D 효과, 오프라인 대응용 로컬 번들)
- `tools/` — 특강 도구 모음 (`index.html` 허브 + 각 도구 HTML)
- `index.html` — 슬라이드로의 리다이렉트 (GitHub Pages 루트용)
