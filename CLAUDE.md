# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요

개인 개발자 포트폴리오 및 이력서를 웹으로 표현하는 반응형 웹사이트 프로젝트입니다.

## 기술 스택

- **마크업**: HTML5
- **스타일**: CSS3, TailwindCSS (CDN)
- **인터랙션**: Vanilla JavaScript

## 개발 환경

빌드 도구 없이 정적 파일로 구성된 프로젝트입니다. 로컬 개발 시 Live Server 또는 간단한 HTTP 서버를 사용합니다.

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve
```

## 아키텍처

단일 페이지 웹사이트 구조:
- `index.html`: 메인 페이지 (모든 섹션 포함)
- `css/style.css`: 커스텀 스타일 (TailwindCSS 보완)
- `js/main.js`: 인터랙션 로직 (다크모드, 스크롤 등)
- `assets/images/`: 이미지 리소스

## 주요 섹션

Header → About → Skills → Experience → Projects → Education → Footer

## 코딩 컨벤션

- TailwindCSS 유틸리티 클래스 우선 사용
- 커스텀 CSS는 TailwindCSS로 해결 불가능한 경우에만 작성
- JavaScript는 ES6+ 문법 사용, 모듈화 없이 단일 파일 유지
