# GitHub Pages Developer Portfolio

GitHub Pages에 바로 배포할 수 있는 정적 개발자 포트폴리오입니다. 빌드 도구가 필요 없고, `index.html`, `styles.css`, `script.js`, `assets/hero-workspace.png`만으로 동작합니다.

## 수정할 곳

- `index.html`: 이름, 소개 문구, 프로젝트 설명, 이메일, GitHub, LinkedIn 링크를 본인 정보로 바꾸세요.
- `styles.css`: 색상, 간격, 카드 스타일을 바꿀 수 있습니다.
- `assets/hero-workspace.png`: 첫 화면 배경 이미지입니다. 다른 이미지를 쓰려면 같은 파일명으로 교체하거나 HTML의 이미지 경로를 바꾸세요.

## 로컬 미리보기

파일 탐색기에서 `index.html`을 더블클릭하면 브라우저에서 확인할 수 있습니다.

## GitHub Pages 배포

1. GitHub에서 저장소를 만듭니다.
   - 개인 메인 사이트: `<username>.github.io`
   - 프로젝트 사이트: 원하는 저장소 이름
2. 이 폴더의 파일들을 저장소 루트에 커밋하고 푸시합니다.
3. 저장소의 `Settings` > `Pages`에서 `Source`를 `Deploy from a branch`로 선택합니다.
4. 브랜치는 `main`, 폴더는 `/(root)`를 선택하고 저장합니다.

공식 문서:

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 파일 구조

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    └── hero-workspace.png
```
