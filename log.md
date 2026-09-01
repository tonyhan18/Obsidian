# Knowledge Graph Log

> 모든 위키 액션의 기록. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`
> Actions: ingest, update, query, lint, create, archive

## [2026-08-23] create | Knowledge Graph 초기화
- 도메인: 투자 · 커리어 · 자산관리
- 구조: SCHEMA.md, index.md, log.md + entities/, concepts/, comparisons/, queries/, raw/
- 기존 Obsidian repo (tonyhan18/Obsidian) 위에 지식 그래프 레이어 추가

## [2026-08-23] ingest | 멘토링 세션 + 매매 일지 + 달러/금 인사이트 + 시황 분석
- Raw 소스 4건 인제스트:
  - raw/transcripts/mentoring-session.md (후배 멘토링 8섹션)
  - raw/transcripts/trading-journal.md (매매 일지 4월)
  - raw/articles/dollar-gold-btc-chart.md (달러 vs 금/비트코인)
  - raw/articles/market-analysis-202608-week2.md (8월 2주차 시황)
- Entity 페이지 6건 생성:
  - entities/samsung-electronics.md, entities/sk-hynix.md
  - entities/semiconductor-industry.md, entities/dollar.md
  - entities/gold.md, entities/bitcoin.md
- Concept 페이지 6건 생성:
  - concepts/top-down-selection.md, concepts/core-satellite.md
  - concepts/dollar-hedge.md, concepts/bu-by-bu.md
  - concepts/reverse-roadmap.md, concepts/producer-focus.md
- Comparison 페이지 1건: comparisons/gold-vs-bitcoin.md
- Query 페이지 1건: queries/market-analysis-202608-week2.md
- 총 15페이지, 모든 페이지 wikilinks로 연결됨

## [2026-08-31] ingest | 안목(taste) 글 + 인프런 디자인 시스템 구축기
- Raw 소스 2건:
  - raw/articles/taste-and-judgment.md (GeekNews — 그렇다면 안목은 어디에서 오는가?)
  - raw/articles/inflab-design-system.md (인프랩 — 디자인 시스템 구축기)
- Concept 페이지 2건:
  - concepts/taste-and-ai.md — AI 시대의 안목, 직접 만드는 과정, 후각 마비
  - concepts/design-system.md — 외부 라이브러리 활용, 점진적 적용, 전사 싱크업
- 총 17페이지
- 총 15페이지, 모든 페이지 wikilinks로 연결됨