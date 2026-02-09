# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 소개

개인 개발자 웹 이력서를 정적 웹사이트로 제작하는 프로젝트이다.
빌드 도구 없이 HTML, CSS, JavaScript, TailwindCSS(CDN)로 구성된 단일 페이지 사이트이다.

## 기술 스택

- HTML (시맨틱 마크업)
- CSS + TailwindCSS (유틸리티 기반 스타일링)
- JavaScript (바닐라, 모듈 없음)

## 개발 명령어

별도의 빌드/테스트 도구가 없는 정적 프로젝트이다. 로컬 개발 서버로 확인한다:

```bash
# 로컬 개발 서버 실행 (Python)
python3 -m http.server 8080 --directory resume

# 또는 npx를 사용
npx serve resume
```

## 아키텍처

단일 페이지(`index.html`)에 7개 섹션(Hero, About Me, Skills, Experience, Projects, Education, Contact)과 Navigation 바로 구성된다. 상세 섹션 정의와 개발 단계는 `ROADMAP.md`를 참고한다.

### 파일 구조

```
resume/                 # 이력서 웹사이트 소스
  index.html            # 메인 페이지 (모든 섹션 포함)
  css/style.css         # 커스텀 스타일 (TailwindCSS 보완)
  js/main.js            # 인터랙션 (스크롤 애니메이션, 네비게이션 등)
  assets/images/        # 이미지 리소스
```

## 언어 및 커뮤니케이션 규칙

- **기본 응답 언어**: 한국어
- **코드 주석**: 한국어로 작성
- **커밋 메시지**: 한국어로 작성
- **문서화**: 한국어로 작성
- **변수명/함수명**: 영어 (코드 표준 준수)
