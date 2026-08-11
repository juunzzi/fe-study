# 학습 백로그 (공부해야 할 내용)

> 이 레포는 **학습이 필요한 항목을 나열**하는 용도다. 학습 완료 추적은 하지 않는다.
> learning-coach 가 여기서 골라 추천한다. 우선순위 P1(지금 가치 큼) > P2 > P3.

<!-- 항목 형식:
- [P1] 주제 — 왜 지금 (출처: 링크, 추가일: YYYY-MM-DD)
-->

- [P1] node:sqlite 내장 모듈 — juunzzi-bot 의 내구 잡 큐가 SQLite 위에 서 있어서, 드라이버 없는 표준 API·동기 실행 모델·트랜잭션 경계를 알아야 큐 동작과 장애를 읽을 수 있음 (출처: https://nodejs.org/api/sqlite.html, 추가일: 2026-08-11)
- [P1] Next.js 16.3 Instant Navigations / Cache Components — 차기 메이저 기본값 예정 + LBOX3-917 전환 성능·FE-1145 version skew 대응과 직결 (출처: https://nextjs.org/blog/next-16-3, 추가일: 2026-08-06)
- [P2] React Compiler 동작 원리와 lbox-client 적용 현황 — 팀 코드베이스에서 이미 활성화되어 있고 setState-in-effect 같은 함정이 실제로 발생함 (출처: 팀 메모리, 추가일: 2026-08-05)
- [P2] TanStack Query v5 구조적 공유(structural sharing)와 리렌더 최적화 — 매일 쓰는 라이브러리의 내부 동작 이해 (추가일: 2026-08-05)
- [P2] Claude Code Skills 컨텍스트 설계(강제 주입 vs 선택 로딩) — D2 실측 6,900→170토큰이 juunzzi-bot skills/ 구조·lbox-client .claude/skills 경계 판단에 직결 (출처: https://d2.naver.com/helloworld/7337586, 추가일: 2026-08-11)
