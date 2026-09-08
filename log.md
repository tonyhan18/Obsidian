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

## [2026-09-08] ingest | GeekNews RSS 21건 수집 — AI/LLM/조직/셀프호스팅
- RSS 피드: GeekNews (https://news.hada.io/rss/news)
- 수집된 글 21건, 키워드 필터(AI, LLM, GPT, 조직, 클라우드, 백엔드 등) 통과
- Raw 소스 6건 생성 (그룹화):
  - raw/articles/llm-cognitive-impact.md — 인지 바이러스, 지적 바지 지퍼, 독자의 반란 (3건)
  - raw/articles/ai-org-transformation.md — 브라운필드, 도구 vs 기업, 특화 AI, 코드 품질 (4건)
  - raw/articles/gpt-6-astra-capabilities.md — 수능 만점, 하네스, 로봇 제어, AAII v4.2 (4건)
  - raw/articles/ai-safety-alignment.md — Alien Mind, Terence Tao 경고 (2건)
  - raw/articles/self-hosting-digital-autonomy.md — Cloud in a Bottle, EU Git, NAS, A/I, Nitter (5건)
  - raw/articles/brain-rot-and-ai-waiting.md — 브레인롯, VIBE-GAME, Anubis (3건)
- Entity 페이지 1건 생성:
  - entities/gpt-6-astra.md — 수능 만점, 하네스 격차, 로봇 제어, AAII v4.2
- Concept 페이지 5건 생성:
  - concepts/llm-cognitive-impact.md — LLM의 인지·신뢰 영향 (인지 바이러스, 신뢰 훼손)
  - concepts/ai-org-transformation.md — AI 조직 전환 (브라운필드, 도구 vs 기업, 특화 AI, 코드 품질)
  - concepts/ai-safety-alignment.md — AI 정렬과 안전성 (Alien Mind, Terence Tao)
  - concepts/self-hosting-digital-autonomy.md — 셀프 호스팅과 디지털 자립
  - concepts/ai-cognitive-management.md — AI 시대의 인지 관리 (브레인롯, AI 대기 시간, 스크래핑 방어)
- 기존 페이지 업데이트:
  - concepts/taste-and-ai.md — 3개 신규 wikilinks 추가 (llm-cognitive-impact, ai-cognitive-management, ai-safety-alignment)
- 총 23페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제 RSS 10건 + GeekNews 1건 수집 — 반도체/매크로/달러/AI 에이전트
- RSS 피드: 한국경제(증권/IT/경제), GeekNews
- 수집된 글 11건, 키워드 필터(반도체, 코스피, 달러, 투자, AI, 파운드리, S&P) 통과
- Raw 소스 4건 생성 (그룹화):
  - raw/articles/semiconductor-rally-202609.md — 코스피 7천피 재탈환, 삼전하닉 급등, 9월 CPI, DB하이텍 파운드리 (5건)
  - raw/articles/macro-dollar-202609.md — 미국 1200억달러 원전 투자, 미 대학기금 S&P500 능가, GNI 4만달러, 릴리 1조달러 (4건)
  - raw/articles/apache-maka-agent-workspace.md — Apache Maka 로컬 우선 에이전트 워크스페이스 (1건)
  - raw/articles/auto-krw-202609.md — 자동차주 이중고: 판매 둔화 + 원화 강세 (1건)
- Concept 페이지 4건 생성:
  - concepts/kospi-7000-202609.md — 코스피 7천피 재탈환, 반도체 훈풍, 9월 CPI가 결정할 방향
  - concepts/korea-gni-40k-202609.md — 한국 GNI 4만달러 시대, 달러 약세 견인, 원전 투자, 릴리 전략
  - concepts/agent-execution-logging.md — 에이전트 실행 기록과 로컬 우선 워크스페이스 (Apache Maka)
  - concepts/auto-sector-dual-risk.md — 자동차주 이중고, 판매 둔화 + 원화 강세, 반도체와 대조
- 기존 페이지 업데이트:
  - entities/semiconductor-industry.md — 2026-09-08 시장 흐름 추가 (코스피 7천피, DB하이텍, 9월 CPI)
  - entities/dollar.md — 2026-09-08 업데이트 (원전 1200억달러, GNI 4만달러, 원화 강세 영향)
- 총 27페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨