<div align="center">

<img src="https://avatars.githubusercontent.com/u/232012965?v=4" width="110" style="border-radius:50%" alt="homesweetlove avatar" />

# my_dev.io

**i_so_free (@homesweetlove)의 개인 포트폴리오 / 홈페이지**

"오타쿠가 세상을 지배한다!"

### 🌐 [홈페이지 바로가기 → homesweetlove.github.io/my_dev.io](https://homesweetlove.github.io/my_dev.io/)

[![Homepage](https://img.shields.io/badge/Homepage-Visit-6c5ce7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://homesweetlove.github.io/my_dev.io/)
[![GitHub](https://img.shields.io/badge/GitHub-homesweetlove-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/homesweetlove)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white)
![No Build](https://img.shields.io/badge/build-none-brightgreen?style=flat-square)

</div>

---

## 📑 목차

- [소개](#-소개)
- [페이지 구성](#-페이지-구성)
- [주요 기능](#-주요-기능)
- [프로젝트 구조](#-프로젝트-구조)
- [로컬에서 실행하기](#-로컬에서-실행하기)
- [GitHub Pages 배포 방법](#-github-pages-배포-방법)
- [콘텐츠 수정 가이드](#️-콘텐츠-수정-가이드)
- [GitHub 프로필 README](#-github-프로필-readme)
- [디자인](#-디자인)

---

## 👋 소개

GitHub 계정 [`@homesweetlove`](https://github.com/homesweetlove)의 공개 정보(아바타, bio, 공개 저장소 목록, 사용 언어)를 바탕으로 만든 한 페이지짜리 포트폴리오 사이트입니다.
빌드 도구나 프레임워크 없이 **순수 HTML / CSS / JavaScript**만으로 작성되어, 파일을 열기만 하면 바로 동작합니다.

> 🔗 **라이브 사이트:** https://homesweetlove.github.io/my_dev.io/

## 🧭 페이지 구성

| # | 섹션 | 내용 |
|---|------|------|
| 00 | **Home** | 아바타, 이름, 타이핑 효과로 바뀌는 소개 문구, 주요 버튼 |
| 01 | **About** | 한 줄 bio, GitHub 정보, 숫자 카운트업 통계 카드 |
| 02 | **Projects** | 공개 저장소 카드 목록 (`working_toolpage`, `joking`, `joko`, `java_endtest`, `blueprint`, `pantum`) |
| 03 | **Skills** | Languages / Web / Tools 별 기술 스택 |
| 04 | **Activity** | 최근 업데이트된 저장소 목록 |
| 05 | **Contact** | GitHub 프로필로 연결되는 연락 섹션 |

## ✨ 주요 기능

- 🌗 **다크 / 라이트 테마** — 시스템 설정 자동 감지 + 수동 토글, 선택한 테마는 `localStorage`에 저장
- ⌨️ **타이핑 애니메이션** — 히어로 영역의 역할 문구가 타이핑/삭제되며 순환
- 🔢 **카운트업 통계** — 스크롤해서 About 섹션이 보이면 숫자가 0부터 올라가는 애니메이션 (`IntersectionObserver`)
- 📱 **반응형 레이아웃** — 모바일에서는 햄버거 메뉴로 전환
- 🧷 **부드러운 섹션 이동** — 상단 네비게이션에서 각 섹션으로 앵커 이동, 스크롤 시 네비게이션 그림자
- 📅 **자동 연도 표시** — 푸터의 저작권 연도가 현재 연도로 자동 갱신

## 📁 프로젝트 구조

```
my_dev.io/
├── index.html          # 페이지 구조 및 텍스트 콘텐츠
├── assets/
│   ├── style.css       # 색상, 폰트, 레이아웃 등 디자인
│   └── script.js       # 테마 토글, 타이핑 효과, 카운트업 등 인터랙션
├── PROFILE_README.md   # GitHub 프로필(homesweetlove/homesweetlove)용 README 템플릿
└── README.md
```

## 💻 로컬에서 실행하기

별도 설치 없이 `index.html`을 브라우저로 열면 됩니다.
간단한 로컬 서버로 확인하고 싶다면:

```bash
git clone https://github.com/homesweetlove/my_dev.io.git
cd my_dev.io
npx serve .
# 또는
python -m http.server 8000
```

그다음 브라우저에서 `http://localhost:8000` (serve 사용 시 안내된 주소)으로 접속합니다.

## 🚀 GitHub Pages 배포 방법

1. 이 저장소의 **Settings → Pages**로 이동합니다.
2. **Source**를 `Deploy from a branch`, 브랜치는 `main`, 폴더는 `/ (root)`로 설정합니다.
3. 저장하면 잠시 후 **https://homesweetlove.github.io/my_dev.io/** 주소로 사이트가 배포됩니다.
4. 이후 `main` 브랜치에 push할 때마다 자동으로 다시 배포됩니다.

## 🛠️ 콘텐츠 수정 가이드

새 저장소를 만들거나 소개를 바꾸고 싶다면 아래 위치만 수정하면 됩니다.

| 바꾸고 싶은 것 | 수정할 곳 |
|----------------|-----------|
| 프로젝트 카드 추가/삭제 | `index.html`의 `#projects` 섹션 — `<article class="project-card">` 블록 복사/삭제 |
| 기술 스택 | `index.html`의 `#skills` 섹션 — `<span>` 태그 추가/삭제 |
| 최근 업데이트 목록 | `index.html`의 `#activity` 섹션 — `<a class="blog-item">` 블록 수정 |
| 통계 숫자 | `index.html`의 `.stat-num` 요소의 `data-count` 값 |
| 타이핑 효과 문구 | `assets/script.js`의 `roles` 배열 |
| 색상 / 폰트 / 레이아웃 | `assets/style.css` |

프로젝트 카드 예시:

```html
<article class="project-card">
  <div class="project-thumb" style="--c1:#7c6cff;--c2:#00d4ff;">📦</div>
  <div class="project-body">
    <h3>새_저장소_이름</h3>
    <p>저장소 한 줄 설명</p>
    <div class="tags"><span>TypeScript</span></div>
    <div class="project-links">
      <a href="https://github.com/homesweetlove/새_저장소_이름" target="_blank" rel="noopener">GitHub ↗</a>
    </div>
  </div>
</article>
```

> `--c1`, `--c2` 값을 바꾸면 카드 썸네일의 그라디언트 색상이 바뀝니다.

## 🐙 GitHub 프로필 README

`PROFILE_README.md`는 GitHub 프로필 페이지(`github.com/homesweetlove`)에 표시되는 소개 카드용 템플릿입니다.
기술 스택 배지, GitHub Stats, Streak 카드, 홈페이지 링크가 포함되어 있습니다. 적용하려면:

1. `homesweetlove/homesweetlove`라는 이름의 새 저장소를 만듭니다 (GitHub 아이디와 동일한 이름, public).
2. `PROFILE_README.md`의 내용을 그 저장소의 `README.md`로 붙여넣습니다.
3. 커밋하면 프로필 페이지 상단에 자동으로 표시됩니다.

## 🎨 디자인

- 다크/라이트 모드 자동 감지 + 수동 토글
- 보라~시안 그라디언트 포인트 컬러의 미니멀 개발자 스타일
- [Inter](https://fonts.google.com/specimen/Inter) / [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) 폰트
- 빌드 도구 없이 순수 HTML/CSS/JS로 작성 (별도 설치 불필요)

---

<div align="center">

**[🌐 홈페이지 방문하기](https://homesweetlove.github.io/my_dev.io/)** · **[🐙 GitHub 프로필](https://github.com/homesweetlove)**

<sub>© homesweetlove · Built with HTML, CSS &amp; a little JS</sub>

</div>
