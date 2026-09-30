# 추정민 · 개발자 포트폴리오

첨부한 경력기술서를 바탕으로 만든 한국어·영어 정적 포트폴리오입니다. 빌드 도구나 외부 패키지 없이 GitHub Pages에서 바로 동작합니다.

## 로컬 확인

```sh
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000/`(한국어) 또는 `http://localhost:8000/en/`(영어)을 엽니다.

## GitHub Pages 배포

1. `cipher75/cipher75.github.io` 공개 저장소의 `main` 브랜치에 푸시합니다. 원본 경력기술서 PPTX는 `.gitignore`로 제외됩니다.
2. 저장소 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**를 선택합니다.
3. 게시 브랜치(예: `main`)와 **`/(root)`** 폴더를 선택하고 저장합니다.

게시 주소는 `https://cipher75.github.io/`입니다. 사이트 내부 파일 경로는 상대 경로로 작성했습니다. 공개 연락처는 요청에 따라 이메일만 표시합니다.

## 콘텐츠 수정

- 한국어: `index.html`
- 영어: `en/index.html`
- 공통 디자인: `styles.css`

프로젝트와 경력 문구를 수정할 때 두 언어 페이지를 함께 갱신하세요. 공개 연락처를 바꾸는 경우 두 페이지의 `mailto:` 링크도 함께 수정하세요.
