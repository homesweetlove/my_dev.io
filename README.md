# my_dev.io

개인 포트폴리오 / 홈페이지 (GitHub Pages)

## 미리보기

`index.html`을 브라우저로 열거나, GitHub Pages로 배포하면 바로 확인할 수 있습니다.

## GitHub Pages 배포 방법

1. 이 저장소의 **Settings → Pages**로 이동합니다.
2. **Source**를 `main` 브랜치(혹은 사용 중인 기본 브랜치), 폴더는 `/ (root)`로 설정합니다.
3. 저장하면 `https://homesweetlove.github.io/my_dev.io/` 주소로 사이트가 배포됩니다.

## 내용 수정하기

아래 파일에서 이름, 소개, 프로젝트, 기술 스택, 연락처 등을 본인 정보로 교체하세요.

- `index.html` — 페이지 구조 및 텍스트 콘텐츠
- `assets/style.css` — 색상, 폰트, 레이아웃 등 디자인
- `assets/script.js` — 타이핑 효과 문구, 인터랙션

주요 수정 포인트:

- `<title>`, 자기소개 문구, 소셜 링크(`github.com/yourhandle`, `mailto:you@example.com` 등)
- `#projects` 섹션의 프로젝트 카드 4개
- `#skills` 섹션의 기술 스택 목록
- `#blog` 섹션의 글 목록

## GitHub 프로필 README

`PROFILE_README.md` 파일은 GitHub 프로필 페이지(예: `github.com/homesweetlove`)에 표시되는
소개 카드용 템플릿입니다. 적용하려면:

1. `homesweetlove/homesweetlove`라는 이름의 새 저장소를 만듭니다 (본인의 GitHub 아이디와 동일한 이름, public).
2. `PROFILE_README.md`의 내용을 그 저장소의 `README.md`로 붙여넣습니다.
3. 커밋하면 프로필 페이지 상단에 자동으로 표시됩니다.

원하시면 이 저장소도 대신 만들어 드릴 수 있습니다.

## 디자인

- 다크/라이트 모드 자동 감지 + 수동 토글
- 보라~시안 그라디언트 포인트 컬러의 미니멀 개발자 스타일
- Inter / JetBrains Mono 폰트
- 빌드 도구 없이 순수 HTML/CSS/JS로 작성 (별도 설치 불필요)
