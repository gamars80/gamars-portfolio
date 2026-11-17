# Skills 페이지 스펙

## 목적
채용·면접 상대가 30초 안에 기술 범위를 훑도록, MIMI/Resta 기준 스킬만 도메인별로 모은 원페이지.

## 범위
- 포함: Resta MIMI (backend / admin / app 경계 / infra)
- 제외: 타쿠마·으랏가챠 등 다른 제품 스택 (요청 시 별도 섹션)

## IA
- 홈 `index.html`에 **Skills 카드 1개**
- `skills.html` 본문은 **도메인 섹션**으로 분리
- 숙련도는 별점 대신 **역할 깊이**만: 설계·운영 / API 소유 / 연동

## 도메인 목록
1. Backend
2. Data
3. Realtime · Media
4. Search · AI
5. Payments · Notifications
6. Admin Frontend
7. Patient App (경계)
8. Infra · CI/CD
9. Observability
10. Engineering Practice

## 톤·UI
- 기존 Notion-like HTML 톤 유지 (태그 칩, domain 카드)
- 상세 서사는 기존 이력서 링크로 위임 (중복 서술 최소화)

## 비목표
- 연차/별점 등급
- 모든 라이브러리 전수 나열
- 타 제품 스킬 혼입
