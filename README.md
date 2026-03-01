# AI-Auto-Posting-Frontend

AI 기반 블로그 콘텐츠 생성과 자동 업로드를 하나의 파이프라인으로 묶은 통합 프로젝트의 프론트엔드입니다.
쇼핑몰 상품 홍보 자동화에 특화된 서비스이며, React 기반으로 관리자 대시보드 및 사용자 인터페이스를 제공합니다.

## 프로젝트 개요

- 프로젝트명: OCP (Online Commerce Promotion)
- 개발 기간: 2025.11 ~ 2025.12
- 팀 구성: 6명 (Backend 3, Frontend 2, AI 1)
- 담당 역할: Frontend

## 시연 영상

https://github.com/user-attachments/assets/002db9a0-98e8-41f5-a7a1-5d2380e73112

## 담당 업무

### 관리자 대시보드
- 데이터 트렌드 파악을 위해 관리자 대시보드 추이 그래프 필터 및 차트 개선
- 대량 데이터 처리를 위해 관리자 통계 테이블 페이징 구현
- 관리 효율성 향상을 위해 관리자 페이지 UI/UX 개선

### 관리자 통계/설정
- 관리자 블로그 통계 및 통계 재집계 기능 구현
- 설정값 관리를 위해 공통 코드 관리 페이지 구현

### 메인 페이지 및 공통
- 코드 유지보수성을 위해 메인페이지 리팩토링 및 Footer/NoticeSection 개선
- 공지사항 페이지 Header import 경로 수정

### 프로젝트 환경 설정
- 백엔드 연동 및 API 설정 추가
- Prettier 설정 및 README 업데이트
- Node.js 버전 명시 추가
- 팀원을 위한 상세한 설정 가이드 문서 작성
- GitHub Templates 추가

## 기술 스택

- Language: TypeScript
- Framework: React
- 상태관리/통신: Axios
- 빌드: Vite
- 코드 품질: Prettier, ESLint

## 실행 방법
```bash
npm install
npm run dev
```

## 관련 레포지토리

- Backend: [AI-Auto-Posting-Backend](https://github.com/WONJUN-KR/AI-Auto-Posting-Backend)
- 통합 레포: [Kernel-Final-Project/integration](https://github.com/Kernel-Final-Project/integration)
