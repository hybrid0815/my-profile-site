# 개발자/TA(테크니컬 아티스트) 웹 이력서 프로젝트 ROADMAP

## 프로젝트 개요

개인 개발자(테크니컬 아티스트) 웹 이력서를 정적 웹사이트로 제작하는 프로젝트이다.

### 기술 스택

- **HTML** - 시맨틱 마크업
- **CSS** - 스타일링
- **JavaScript** - 인터랙션 및 동적 기능
- **TailwindCSS** - 유틸리티 기반 CSS 프레임워크

---

## 이력서 섹션 구성

| 섹션           | 설명                                                    |
| -------------- | ------------------------------------------------------- |
| **Hero**       | 이름, 직함, 한 줄 소개 등 첫인상을 전달하는 인트로 영역 |
| **About Me**   | 간단한 자기소개 및 개발자로서의 철학/방향성             |
| **Skills**     | 보유 기술 스택을 카테고리별로 시각적으로 표현           |
| **Experience** | 경력사항 (회사명, 직책, 기간, 주요 업무)                |
| **Projects**   | 주요 프로젝트 소개 (프로젝트명, 설명, 사용 기술, 링크)  |
| **Portfolio**  | TA 포트폴리오 영상 (YouTube 임베드)                     |
| **Education**  | 학력사항 (학교명, 전공, 기간)                           |
| **Contact**    | 이메일, GitHub, LinkedIn 등 연락처 및 소셜 링크         |

---

## 개발 단계

### Phase 1: 프로젝트 초기 설정

- [ ] Git 저장소 초기화 및 `.gitignore` 설정
- [ ] TailwindCSS CDN 또는 빌드 환경 세팅
- [ ] 기본 HTML 구조 작성 (`index.html`)
- [ ] 공통 스타일 및 레이아웃 정의
- [ ] 파비콘 및 메타태그 설정

### Phase 2: 각 섹션 UI 개발

- [ ] Hero 섹션 구현
- [ ] About Me 섹션 구현
- [ ] Skills 섹션 구현
- [ ] Experience 섹션 구현
- [ ] Projects 섹션 구현
- [ ] Portfolio 섹션 구현 (YouTube 동영상 임베드)
- [ ] Education 섹션 구현
- [ ] Contact 섹션 구현
- [ ] Navigation 바 구현

### Phase 3: 반응형 디자인 및 애니메이션

- [ ] 모바일/태블릿/데스크톱 반응형 레이아웃 적용
- [ ] 스크롤 애니메이션 추가 (Intersection Observer)
- [ ] 부드러운 스크롤 네비게이션 구현
- [ ] 다크모드 지원 (선택)

### Phase 4: 최종 점검 및 배포

- [ ] 크로스 브라우저 테스트
- [ ] 성능 최적화 (이미지, 폰트 등)
- [ ] SEO 메타태그 점검
- [ ] GitHub Pages 또는 Vercel로 배포

---

## 파일 구조

```
claude-init/
├── resume/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── assets/
│       └── images/
├── .gitignore
├── CLAUDE.md
├── README.md
└── ROADMAP.md
```
