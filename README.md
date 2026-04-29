# boostus

<div align="center">

**네이버 부스트캠프의 학습 경험을 아카이빙 하는 서비스**
2025.12 - 2026.02 · 5인 팀 · 백엔드/인프라

</div>

> 현재 서비스는 재정 문제로 인해 운영 종료 상태입니다.

<p align="center">
  <a href="https://www.notion.so/Pole-Position-2c3d4705e03f80f7bba0c5264dc7be36?source=copy_link"><b>📑 팀 노션</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://github.com/boostcampwm2025/web01-pole-position/wiki"><b>📖 위키</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://www.figma.com/board/AZlRmfD1liRtDK41pwLJeK/%ED%8F%B4-%ED%8F%AC%EC%A7%80%EC%85%98-%ED%8C%80-BoostUs-%F0%9F%9A%80?node-id=0-1&t=VDqpRXD7pJhBLJk6-1"><b>🎨 피그잼</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://github.com/boostcampwm2025/web01-BoostUs"><b>⭐️ 원본 리포지토리</b></a>
</p>

---

## 🟩 담당 역할

### ✔︎ 백엔드

- 캠퍼들의 이야기 조회 API 구현 ([#117](https://github.com/boostcampwm2025/web01-BoostUs/pull/117), [#128](https://github.com/boostcampwm2025/web01-BoostUs/pull/128))
- 캠퍼들의 이야기 좋아요 API 구현 ([#265](https://github.com/boostcampwm2025/web01-BoostUs/pull/265))
- 캠퍼들의 이야기 조회수 증가 API 구현 ([#280](https://github.com/boostcampwm2025/web01-BoostUs/pull/280))
- 캠퍼들의 이야기 페이지네이션 적용 ([#192](https://github.com/boostcampwm2025/web01-BoostUs/pull/192), [#314](https://github.com/boostcampwm2025/web01-BoostUs/pull/314))
- RSS 크롤러 서비스 설계 및 구현 ([#167](https://github.com/boostcampwm2025/web01-BoostUs/pull/167))
- Velog/Tistory RSS URL 유효성 검증/예외 처리 구현 ([#226](https://github.com/boostcampwm2025/web01-BoostUs/pull/226))
- JWT 기반 인증 도입 및 전역 인증 상태 관리 구현 ([#221](https://github.com/boostcampwm2025/web01-BoostUs/pull/221))
- 조회수 증가 로직 Batch 처리 개선 ([#386](https://github.com/boostcampwm2025/web01-BoostUs/pull/386))

### ✔︎ 인프라

- RSS 크롤러 Dockerfile 작성 및 CI/CD 파이프라인 구성 ([#211](https://github.com/boostcampwm2025/web01-BoostUs/pull/211))
- 백엔드 Dockerfile 개선 및 컨테이너 빌드 최적화 ([#157](https://github.com/boostcampwm2025/web01-BoostUs/pull/157))

### ✔︎ 프론트엔드

- JWT 인증 전역 상태 관리 및 헤더 로그인 UI 구현 ([#221](https://github.com/boostcampwm2025/web01-BoostUs/pull/221))
- 캠퍼들의 이야기 RSS 피드 등록 UI 구현 ([#261](https://github.com/boostcampwm2025/web01-BoostUs/pull/261))
- 캠퍼들의 이야기 상세 페이지 좋아요 UI 구현 ([#265](https://github.com/boostcampwm2025/web01-BoostUs/pull/265))
- 관리자용 프로젝트/Q&A 수정/삭제 UI 구현 ([#326](https://github.com/boostcampwm2025/web01-BoostUs/pull/326), [#350](https://github.com/boostcampwm2025/web01-BoostUs/pull/350))

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

---

## 설계 결정과 이유

제한된 기간과 팀 상황 안에서 **왜 그렇게 설계했는지**를 남기기 위해 작성했습니다.  
각 의사결정은 `문제 → 선택 → 근거 → 결과/트레이드오프 → 느낀 점` 순서로 정리했습니다.

### 1. 데이터 모델링

<img width="2048" height="1197" alt="image" src="https://github.com/user-attachments/assets/fac11cef-624a-4c2b-b4a0-8279ff4bde03" />

**설계 원칙**

- 목록에서 자주 노출되는 좋아요, 조회수 등은 매번 집계하지 않고 카운터 컬럼으로 관리했습니다.
- 콘텐츠 삭제는 물리 삭제보다 상태값(`PUBLISHED`, `PRIVATE`, `DELETED`)으로 표현해 데이터 복구가 가능하도록 했습니다.
- 사용자 행동 이력은 별도 테이블로 분리해 중복 좋아요/투표를 DB 제약으로 막을 수 있게 했습니다.

**프로젝트**

- 프로젝트는 등록자와 실제 참여자를 분리했습니다.
- 프로젝트 참여자는 서비스 회원이 아닐 수 있으므로 `Member`와 강하게 묶지 않고 GitHub 정보만 저장했습니다.
- 기술 스택은 여러 프로젝트에서 재사용되므로 `TechStack`과 `ProjectTechStack`으로 N:M 관계를 구성했습니다.

**캠퍼들의 이야기**

- 수집 대상(`Feed`)과 수집 결과(`Story`)를 분리해, 하나의 RSS에서 여러 글이 생성되는 구조를 명확히 표현했습니다.
- `(feedId, guid)`에 유니크 제약을 적용해 크롤러 수집 중복을 방지했습니다.
- 최신순 커서 조회를 위해 `publishedAt`, `id` 복합 인덱스를 사용해 정렬 안정성을 확보했습니다.

**질문 & 답변**

- 질문과 답변을 분리해 1:N 구조로 설계했습니다.
- 질문은 isResolved, 답변은 isAccepted 상태를 가지도록 책임을 분리했습니다.
- 투표는 별도 테이블로 관리하고 유니크 제약을 통해 중복을 방지했습니다.

### 2. Offset에서 Cursor Pagination으로 전환

**문제**

- Offset 기반 조회는 뒤 페이지로 갈수록 앞 데이터를 건너뛰기 위해 더 많은 row를 스캔해야 합니다.
- 목록을 조회하는 중간에 새 글이 추가되거나 삭제되면 같은 글이 중복 노출되거나 일부 글이 누락될 수 있습니다.

```sql
ORDER BY published_at DESC
LIMIT n
OFFSET m;
```

**설계**

- 마지막으로 조회한 글의 정렬 기준을 커서로 내려주고, 다음 요청에서는 그 기준보다 뒤에 있는 데이터만 조회하도록 바꿨습니다.
- 최신순 및 인기순 정렬 시 동일 값으로 인해 결과 순서가 달라지는 문제를 경험했고, 이를 해결하기 위해 id를 보조 정렬 기준으로 함께 사용했습니다.

```sql
WHERE published_at < ?
   OR (published_at = ? AND id < ?)
ORDER BY published_at DESC, id DESC
LIMIT ?;
```

**결과와 트레이드오프**

- Full Scan 중심의 조회를 Range Scan 형태로 전환할 수 있는 구조를 만들었습니다.
- 데이터 추가/삭제가 발생해도 이전 페이지 기준이 밀리지 않아 중복과 누락 가능성을 줄였습니다.
- Offset 기반 페이지네이션과 비교했을 때 상대적으로 구현 복잡도가 높았습니다.

**느낀 점**

- 작은 서비스에서는 데이터 규모가 크지 않아, 복잡한 커서 기반 페이지네이션보다 Offset 기반 페이지네이션이 구현과 유지보수 측면에서 더 효율적이라고 느꼈습니다.
- Offset 기반 페이지네이션의 한계만 잘 이해하고 있다면, 대부분의 ORM에서 제공하는 페이지네이션 기능을 활용하는 것이 더 이득일 수도 있겠다는 생각이 들었습니다.

### 3. 조회수 증가 병목 개선

**문제**

- 조회 요청마다 `view_count = view_count + 1` UPDATE가 발생하면서 동일 row에 대한 lock 대기가 생겼습니다.
- 로컬 부하 테스트(1,000 VU)에서 p95 응답 시간이 3.8초까지 증가했습니다.
- 사용자가 게시글 조회 API를 요청할 때마다 동기적으로 조회수를 증가(`UPDATE`)시키는 것이 병목의 원인이었습니다.

**설계**

- 동일 사용자의 중복 조회는 Redis TTL 키로 필터링해 불필요한 증가 요청을 줄였습니다.
- 조회수 증가분을 Redis에 누적하고, dirty set에 변경된 게시글 ID를 기록한 뒤, 주기적으로 DB에 batch 반영하는 구조로 개선했습니다.
- 이를 통해 조회 요청과 DB 쓰기를 분리해, 게시글 조회 API가 row lock에 직접 영향을 받지 않도록 했습니다.

**결과**

| 지표           |    Before |     After |     개선 효과 |
| -------------- | --------: | --------: | ------------: |
| 평균 응답 시간 |    2.51초 |    0.88초 |   약 65% 감소 |
| p95 응답 시간  |    3.80초 |    1.57초 |   약 58% 감소 |
| 처리량         | 251 req/s | 581 req/s | 약 2.3배 증가 |

**트레이드오프**

- 조회수가 즉시 반영되지 않고 batch 주기(5초)만큼 뒤늦게 반영이 됐습니다.
- 하지만 조회수는 꼭 즉시 반영되어야 하는 것이 아니라고 생각했기에 문제가 없다고 판단했습니다.
- Redis 장애가 발생할 경우 DB에 반영되지 않은 조회수가 일부 유실될 수 있습니다.
- Redis 메모리 사용량이 증가했기에 데이터 삭제 전략을 고민해야 했습니다.

**느낀 점**

- 모든 데이터를 실시간으로 처리하는 것이 항상 좋은 것만은 아니라는 점을 배웠습니다.
- 읽기와 쓰기 쿼리를 분리하는 구조가 중요하다는 점을 배웠습니다.
- 서로 다른 저장소 간 트랜잭션을 어떻게 관리하고 일관성을 유지할지에 대한 고민이 필요하다는 점도 느꼈습니다.

### 4. JWT 기반 인증과 Refresh Token 도입

**문제**

- Access Token만 사용하면서 만료 시간을 길게 두면 탈취 시 보안 위험이 커지고, 짧게 두면 사용자가 자주 로그인해야 하는 문제가 있었습니다.
- 서버에서 토큰을 직접 무효화하기 어려워 보안과 사용자 경험을 함께 만족시키기 어려웠습니다.

**설계**

- Access Token은 짧은 만료 시간으로 설정하고, 로그인 유지를 위해 Refresh Token을 함께 발급했습니다.
- Refresh Token은 Redis에 저장하고 TTL로 만료를 관리했습니다.
- Access Token이 만료된 경우에만 Refresh Token을 검증해 토큰을 재발급하도록 구성했습니다.
- 로그아웃 시 Redis의 Refresh Token을 삭제해 재사용을 방지했습니다.

**근거**

- Access Token 탈취 시에도 유효 시간을 짧게 유지하면 피해 가능 시간을 줄일 수 있습니다.
- Refresh Token을 서버 저장소에서 관리하면 로그아웃, 만료 처리를 서버에서 직접 제어할 수 있습니다.
- Refresh Token을 DB에 저장하면 만료 처리 로직이 별도로 필요하고, DB 부하가 증가할 수 있습니다.

**느낀 점**

- 작은 서비스에서는 Access Token만으로도 충분히 구현할 수 있지만, 보안과 확장성을 고려하면 Refresh Token 구조가 필요하다고 느꼈습니다.
- 보안성을 위해 토큰의 만료 시간, 저장 방식, 전달 방식까지 함께 고려한 설계가 중요하다는 것을 배웠습니다.

### 5. RSS 수집 파이프라인

**문제**

- Velog, Tistory 등 플랫폼마다 RSS 구조와 날짜 포맷이 달라 파싱 로직이 복잡해지는 문제가 있었습니다.
- HTML, CDATA 등 본문 표현 방식이 달라 플랫폼별 분기 코드가 계속 늘어날 수 있는 상황이었습니다.

**설계**

- 수집 과정을 `피드 조회 → RSS 다운로드 → 파싱/정규화 → API 저장` 단계로 분리했습니다.
- RSS 데이터를 공통 모델로 변환하고, 날짜는 ISO 형식으로 정규화했습니다.
- 크롤러는 DB에 직접 접근하지 않고 백엔드 API를 통해 저장하도록 구성했습니다.
- `(feedId, guid)` 기준 Upsert를 적용해 중복 수집을 방지했습니다.

**결과**

- 13명의 캠퍼들의 RSS를 등록하고 133개의 블로그 글을 수집할 수 있었습니다.
- 플랫폼이 추가되어도 파싱(parser) 계층만 확장하면 되는 구조가 되었습니다.

**느낀 점**

- 외부 데이터는 일정하지 않기 때문에, 철저한 검증과 정규화 과정이 필요하다는 것을 느꼈습니다.
- 플랫폼별로 분기하는 방식보다, 공통 모델로 변환하는 구조가 유지보수에 더 유리하다는 것을 배웠습니다.
