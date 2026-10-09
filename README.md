# GitHub Pages Developer Portfolio

GitHub Pages에 바로 배포할 수 있는 정적 개발자 포트폴리오입니다. 빌드 도구가 필요 없고, `index.html`, `styles.css`, `script.js`, `assets/hero-workspace.png`만으로 동작합니다.

## 수정할 곳

- `index.html`: 이름, 소개 문구, 프로젝트 설명, 이메일, GitHub, LinkedIn 링크를 본인 정보로 바꾸세요.
- `styles.css`: 색상, 간격, 카드 스타일을 바꿀 수 있습니다.
- `assets/hero-workspace.png`: 첫 화면 배경 이미지입니다. 다른 이미지를 쓰려면 같은 파일명으로 교체하거나 HTML의 이미지 경로를 바꾸세요.

## 로컬 미리보기

저장소 폴더에서 다음 명령으로 로컬 서버를 실행합니다. 별도 패키지 설치나 빌드는 필요하지 않습니다.

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

JavaScript 문법은 `node --check script.js`로 확인할 수 있습니다.

## GitHub Pages 배포

1. `luminisharu-afk/luminisharu-afk.github.io` 저장소를 사용합니다.
2. 이 폴더의 파일들을 저장소 루트에 커밋하고 푸시합니다.
3. 저장소의 `Settings` > `Pages`에서 `Source`를 `Deploy from a branch`로 선택합니다.
4. 브랜치는 `main`, 폴더는 `/(root)`를 선택하고 저장합니다.

설정 후 배포가 완료되면 사이트 주소는 https://luminisharu-afk.github.io/ 입니다.

현재 첫 프로젝트는 이 포트폴리오의 실제 소스 저장소에 연결되어 있습니다. 나머지 두 카드는 작성 예정입니다. 공개 전 이름, 소개, 기술 스택을 본인 정보로 확인하고, 프로젝트 설명과 링크를 채워 주세요. 연락 링크는 저장소 계정의 GitHub 프로필을 사용하며 이메일과 LinkedIn은 실제 주소가 준비되면 추가할 수 있습니다. 다른 계정으로 옮길 경우 `index.html`의 canonical, `og:url`, `og:image`와 GitHub 링크도 바꿔 주세요.

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
