<div align="center">

# boostus

부스트캠프의 소중한 학습 경험들을 아카이빙 하는 서비스

2025.12 - 2026.02 · 5인 팀 · 백엔드/인프라

</div>

<p align="center">
  <a href="https://www.notion.so/Pole-Position-2c3d4705e03f80f7bba0c5264dc7be36?source=copy_link"><b>📑 팀 노션</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://github.com/boostcampwm2025/web01-pole-position/wiki"><b>📖 위키</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://www.figma.com/board/AZlRmfD1liRtDK41pwLJeK/%ED%8F%B4-%ED%8F%AC%EC%A7%80%EC%85%98-%ED%8C%80-BoostUs-%F0%9F%9A%80?node-id=0-1&t=VDqpRXD7pJhBLJk6-1"><b>🎨 피그잼</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://github.com/boostcampwm2025/web01-BoostUs"><b>⭐️ 원본 리포지토리</b></a>
</p>

> 현재 서비스는 재정 문제로 인해 운영 종료 상태입니다.

---

## 🟩 담당 역할

### ✔︎ 백엔드

- 프로젝트, 캠퍼들의 이야기, Q&A 도메인 DB 모델링 및 Prisma 시드 데이터 구성 ([#112](https://github.com/boostcampwm2025/web01-BoostUs/pull/112))
- 공통 API 응답 포맷과 전역 예외 처리 구조 표준화 ([#116](https://github.com/boostcampwm2025/web01-BoostUs/pull/116), [#135](https://github.com/boostcampwm2025/web01-BoostUs/pull/135))
- RSS 크롤러 서비스 설계 및 구현 ([#167](https://github.com/boostcampwm2025/web01-BoostUs/pull/167))
- JWT 기반 인증 도입 및 전역 AuthGuard, `@Public`, `@CurrentMember` 인증 흐름 구현 ([#221](https://github.com/boostcampwm2025/web01-BoostUs/pull/221))
- 캠퍼들의 이야기 조회 API 구현 및 커서 기반 페이지네이션/정렬 안정화 ([#117](https://github.com/boostcampwm2025/web01-BoostUs/pull/117), [#128](https://github.com/boostcampwm2025/web01-BoostUs/pull/128), [#192](https://github.com/boostcampwm2025/web01-BoostUs/pull/192), [#314](https://github.com/boostcampwm2025/web01-BoostUs/pull/314))
- 캠퍼들의 이야기 좋아요, 조회수 증가, 관리자 삭제 권한 등 사용자 상호작용 API 구현 ([#265](https://github.com/boostcampwm2025/web01-BoostUs/pull/265), [#280](https://github.com/boostcampwm2025/web01-BoostUs/pull/280), [#326](https://github.com/boostcampwm2025/web01-BoostUs/pull/326), [#350](https://github.com/boostcampwm2025/web01-BoostUs/pull/350))
- RSS 피드 CRUD 및 Velog/Tistory RSS URL 유효성 검증/예외 처리 구현 ([#226](https://github.com/boostcampwm2025/web01-BoostUs/pull/226))
- 조회수 처리 로직 개선 (동기 UPDATE → Redis 카운터 누적 + Batch Flush) ([#386](https://github.com/boostcampwm2025/web01-BoostUs/pull/386))

### ✔︎ 인프라

- RSS 크롤러 Dockerfile 작성 및 CI/CD 파이프라인 구성 ([#211](https://github.com/boostcampwm2025/web01-BoostUs/pull/211))
- 백엔드 Dockerfile 개선 및 컨테이너 빌드 최적화 ([#157](https://github.com/boostcampwm2025/web01-BoostUs/pull/157))

### ✔︎ 프론트엔드

- JWT 인증 전역 상태 관리(AuthProvider/useAuth) 및 로그인 상태 기반 Header/Login UI 구현 ([#221](https://github.com/boostcampwm2025/web01-BoostUs/pull/221))
- 캠퍼들의 이야기 RSS 피드 등록 UI 구현 및 블로그 URL → RSS URL 자동 변환 UX 개선 ([#261](https://github.com/boostcampwm2025/web01-BoostUs/pull/261))
- 캠퍼들의 이야기 상세 페이지 좋아요/공유 사이드바 및 좋아요 상태 연동 구현 ([#265](https://github.com/boostcampwm2025/web01-BoostUs/pull/265))
- 관리자용 프로젝트/Q&A 삭제 UI 및 삭제 확인 모달 구현 ([#350](https://github.com/boostcampwm2025/web01-BoostUs/pull/350))

---

## 🟩 기술 스택

| Category           | Stack                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Language**       | ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)                                                                                                                                                                                                          |
| **Frontend**       | ![Next.js](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)                                                                                                                                                                                                                             |
| **Backend**        | ![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)                                                                                                                                                                                                                                          |
| **Database & ORM** | ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)                                                                                                                                                                                                                                                   |
| **Infra & DevOps** | ![NCP](https://img.shields.io/badge/Naver%20Cloud-03C75A?style=for-the-badge&logo=naver&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |

---

## 🟩 서비스 아키텍처

<img width="640" height="715" alt="스크린샷 2026-01-30 오전 10 28 45" src="https://github.com/user-attachments/assets/3b8165b7-6462-4ec2-8879-53fb855e8c4e" />

---

## 🟩 데이터 모델

**공통 설계 원칙**

- 조회수, 좋아요 수, 추천 수는 매번 집계하지 않고 카운터 컬럼으로 관리해 조회 성능을 높였습니다.
- 콘텐츠는 물리적으로 삭제 대신 상태값으로 관리해 복구가 가능하도록 했습니다.

**1. 프로젝트**

- `Project`를 중심으로 등록자, 참여자, 기술 스택을 분리해 프로젝트 정보를 구조화했습니다.
- 참여자는 서비스 회원이 아닐 수 있어 `Member`와 연결하지 않고 `ProjectParticipant`에 GitHub 정보만 저장했습니다.
- 기술 스택은 여러 프로젝트에서 재사용되므로 `TechStack`과 매핑 테이블로 N:M 관계를 구성했습니다.

**2. 캠퍼들의 이야기 (RSS)**

- RSS 수집 구조를 `Feed`(수집 대상)와 `Story`(수집 결과)로 분리해, 하나의 피드에서 여러 글이 생성되는 흐름을 표현했습니다.
- `(feedId, guid)` Unique 제약으로 크롤러가 같은 글을 반복 수집해도 중복 저장되지 않도록 했습니다.
- `publishedAt`과 `id`를 함께 복합 인덱스로 두어 최신순/인기순 커서 기반 페이지네이션 안정성을 확보했습니다.

**3. 질문 & 답변**

- `Question`과 `Answer`를 1:N으로 분리해 답변별 작성자, 채택 여부, 추천/비추천 수를 독립적으로 관리했습니다.
- 질문의 해결 상태(`isResolved`)와 답변의 채택 상태(`isAccepted`)를 분리해 Q&A 흐름을 명확히 표현했습니다.
- 질문/답변 투표는 각각 별도 테이블로 두어 투표 이력과 중복 방지를 명확하게 관리했습니다.

**4. 사용자 / 인증**

- GitHub OAuth 기반 서비스이므로 `githubId`를 사용자 식별 기준으로 사용했습니다.
- 관리자 권한은 별도 테이블이 아닌 `Role`로 표현했습니다.

---

## 🟩 주요 기능

### ☘️ 프로젝트 모아보기

> **한 곳에 모아 프로젝트를 더 가치 있게**

- 부스트캠프의 모든 프로젝트를 한 눈에 모아 볼 수 있는 공간입니다.
- 예비 지원자들에게는 부스트캠프의 실제 성장 과정을 보여주는 창이 되고,
- 캠퍼들에게는 서로의 경험을 연결하는 포트폴리오 공간이 됩니다.

<img width="2048" height="1137" alt="image" src="https://github.com/user-attachments/assets/3c40fa00-3fab-4ce6-b21b-9e500b0c7494" />

### ☘️ 캠퍼들의 이야기

> **이야기를 연결하다**

- 캠퍼들의 성장 경험과 다양한 이야기를 한 눈에 모아볼 수 있는 공간입니다.
- 예비 지원자에게는 부스트캠프의 길잡이가 되고, 수료생의 글은 성장의 발자국이 됩니다.

<img width="2000" height="1022" alt="image" src="https://github.com/user-attachments/assets/a762e183-e37f-466a-aff2-d8cdd2ad20eb" />

### ☘️ 질문 & 답변

> **집단지성의 힘으로 더 빠르게 성장하기**

- 혼자 답을 찾기보다 함께 사고 과정을 나누고, 질문과 토론을 통해 문제 해결력을 키웁니다.
- 예비 지원자에게는 부스트캠프의 학습 문화를 미리 경험하는 창이 되고, 캠퍼들에게는 서로의 성장을 가속하는 배움터가 됩니다.

<img width="2048" height="925" alt="image" src="https://github.com/user-attachments/assets/aaa22260-69fa-4f78-bcb7-24f7ddb35bbd" />
