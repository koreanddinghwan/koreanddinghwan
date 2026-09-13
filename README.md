# 강명환 · Backend Engineer

제품 요구에 맞춰 API·데이터·실시간 통신·비동기 처리의 역할을 나누어 설계하고 배포·운영까지 맡습니다.

Node.js / NestJS로 제품 백엔드를 개발한 실무 경험은 2년 2개월입니다. 현재 Java / Spring도 학습하고 있습니다.

[Portfolio](https://myunghwan-backend.myunghwan0421.chatgpt.site) · [Resume](https://myunghwan-backend.myunghwan0421.chatgpt.site/resume) · [Evidence Appendix](https://myunghwan-backend.myunghwan0421.chatgpt.site/evidence) · [Email](mailto:myunghwan0421@gmail.com)

## Experience

- **㈜플랫 / COUT** — 공동창업자·백엔드 개발 총괄, 정규직·상근 (2024.09.30–2026.01.31)
  - 개발 인력 1명으로 2025년 활성 사용자 2,590명의 인증·콘텐츠·검색 백엔드와 2,239건의 백오피스 운영 요청 흐름을 구축·운영했습니다.
  - API·Admin·Chat·Worker 4개 실행 단위와 PostgreSQL·Redis/Bull·Socket.IO·FCM의 책임 경계를 설계했습니다.
- **주식회사 하이** — 백엔드 개발자, 프리랜서에서 정규직 전환 (2023.11.20–2024.09.27)
  - JSONB 결과를 조회 시점에 점진적으로 전환하고 ML 호출을 비동기로 처리하도록 구현했습니다. Echo middleware로 locale을 정규화하고 서비스 간 결제 계약을 구현했습니다.
  - Go PDF 생성 경로의 병렬화와 Kubernetes workload 격리를 담당했습니다.

## Selected Work

- [COUT Case Study](https://myunghwan-backend.myunghwan0421.chatgpt.site/case-studies/cout) — 초기 댓글 목록의 정적 DB read 호출 경로를 limit=5에서 9–14회 → 3회로 축소하고 측정 범위를 공개
- [Leetdash](https://github.com/whoisyourbias/leetdash) — Accepted → Draft PR → Validate → AI Review Gate → Merge → Pages 자동화
- [Java / Spring Concurrency Lab](https://github.com/whoisyourbias/playground/tree/81f93eb1199f384fd77bbae1477045202302a21c) — 70개 부하 케이스에서 274,999 요청을 처리하고 정합성 위반 0을 확인한 공개 재현 실험
- [Experiment Report · 81f93eb](https://github.com/whoisyourbias/playground/blob/81f93eb1199f384fd77bbae1477045202302a21c/docs/direct-db-experiment.md) — 500 RPS에서 중앙값 HTTP p95 25.0% 차이와 핵심 DB query 10.9배 차이를 확인한 조건과 원시 결과
- [kqueue Web Server](https://github.com/koreanddinghwan/nginx-like-webserv-using-kqueue) — HTTP/1.1·CGI·partial write·I/O multiplexing 직접 구현

수치의 출처·산식·측정 범위는 [Evidence Appendix](https://myunghwan-backend.myunghwan0421.chatgpt.site/evidence)에 공개합니다. Java / Spring은 교육·공개 실험 경험으로 구분합니다.

## Open Source Contributions

외부 오픈소스 프로젝트에 제출한 문서 기여입니다. 상태는 2026-09-13 기준이며 각 PR에서 최신 상태를 확인할 수 있습니다.

| 프로젝트 | 기여 내용 | PR | 상태 |
| --- | --- | --- | --- |
| NestJS | 이벤트 리스너 옵션 설명 보강 | [#2888](https://github.com/nestjs/docs.nestjs.com/pull/2888) | **Merged** · 2023-10-23 |
| NestJS | NestJS 12의 AWS Lambda 실행에 필요한 `NODE_OPTIONS=--experimental-require-module` 설정 안내 | [#3530](https://github.com/nestjs/docs.nestjs.com/pull/3530) | **Open** · 리뷰 대기 |
| Kubernetes | kubeadm 설치 가이드 한국어 문서 업데이트 제안 | [#44920](https://github.com/kubernetes/website/pull/44920), [#44922](https://github.com/kubernetes/website/pull/44922) | **Closed** · 미병합 |

NestJS #2888과 Kubernetes PR은 `koreanddinghwan`, NestJS #3530은 `whoisyourbias` 계정으로 제출했습니다.

## Skills

**Backend**

TypeScript · Node.js · NestJS · Go · REST · OpenAPI · OAuth/JWT

**Data · Realtime · Async**

PostgreSQL · TypeORM · GIN/FTS · Redis · Bull · Socket.IO · FCM

**Cloud · Delivery**

GCP App Engine · Cloud SQL · Load Balancing · Docker · Kubernetes · GitHub Actions

**Testing · Current Learning**

Jest · Vitest · Testcontainers · k6 · Java 21 · Spring Boot 3 · C++ · kqueue

## Education

- **연세대학교 경영학과** — 2018.03–2026.08 졸업
- **SSAFY 16기** — 2026.07–현재, Java / Spring 백엔드 과정
- **42서울 6기** — 2022.03–2024.03, 2년 수료
- **SQLD** — 2021.10 취득

## GitHub Identity

- [`koreanddinghwan`](https://github.com/koreanddinghwan) — 대표 계정·시스템·백엔드 프로젝트
- [`myukang-flat`](https://github.com/myukang-flat) — COUT 창업기 비공개 제품 개발 계정
- [`whoisyourbias`](https://github.com/whoisyourbias) — SSAFY·Java/Spring·현재 자동화 프로젝트

세 계정의 기여자는 모두 강명환입니다.
