# JINWOO KIM Portfolio v2

취업용 GitHub Pages 정적 포트폴리오입니다.

## 구성
- `index.html`: 소개 전용 Home
- `about/index.html`: 학력, 자기소개, 관심 분야
- `experience/index.html`: 경험 타임라인
- `education/index.html`: 기존 주소 호환용 페이지 (상단 메뉴에는 표시하지 않음)
- `projects/index.html`: 채용 우선순위에 맞춘 5개 Selected Works 목록
- `projects/*.html`: 프로젝트별 상세 사례 페이지
- `activities/index.html`: 프로그램 및 연구 활동
- `contact/index.html`: 연락처
- `style.css`: 반응형 디자인
- `script.js`: 모바일 메뉴 동작
- `assets/favicon.svg`: 사이트 아이콘

## 연락처
Email, GitHub, LinkedIn 링크는 `index.html`과 `contact/index.html`에서 수정할 수 있습니다.

## Navigation URL
상단 메뉴는 `about/`, `experience/`, `contact/`, `projects/`, `activities/`로 연결됩니다. 학력 내용은 About Me에 통합했고, 기존 `education/` 주소는 유지합니다. 프로젝트 상세 페이지는 `projects/` 아래의 개별 HTML 파일입니다.

Home 링크는 GitHub Pages 사용자 사이트 `https://kjw0105.github.io/` 기준으로 `/`를 사용합니다. `/index.html` 직접 접속 시 Home의 인라인 스크립트가 새로고침 없이 주소를 `/`로 정리합니다.

## 프로젝트 상세 구조
핵심 프로젝트 상세 페이지는 `Overview / Background / Problem / My Role / Approach / Result / What I Learned / Verification Scope`를 프로젝트 특성에 맞게 구성합니다. 메인에는 자율비행 AI 검증, RO 공정 최적화, 제조 진동 분류, 방산 전략 연구, Mood of Music을 우선 노출합니다.

## GitHub Pages 배포
1. GitHub 새 repository 생성
2. 압축을 풀고 내용 전체를 repository 최상위에 업로드
3. Settings → Pages
4. Source: Deploy from a branch
5. Branch: main / root
6. Save

사용자 메인 주소(`username.github.io`)로 쓰고 싶으면 저장소 이름을 `username.github.io`로 만드세요.

## 다음 업그레이드 추천
- 실제 프로필 사진
- 실제 GitHub / 논문 / PDF 링크
