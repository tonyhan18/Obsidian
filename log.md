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

## [2026-09-08] ingest | GeekNews 6건 + 한국경제 1건 수집 — Build vs Buy, 브랜드 디자인, Theranos, 폴더블폰, 수리권, Claude Code+GPT-6
- RSS 피드: GeekNews, 한국경제
- 수집된 글 8건, 키워드 필터 통과 7건 (Xteink X3 전자책 리더는 위키 도메인 범위에서 제외)
- Raw 소스 5건 생성:
  - raw/articles/build-vs-buy-ai.md — Build vs Buy 인증 사례 + Claude Code GPT-6 Astra 혼합 사용 (2건)
  - raw/articles/lovable-brand-design.md — Lovable 브랜드 구축, clock speed, 정성과 디자인 (1건)
  - raw/articles/science-vs-engineering-theranos.md — Theranos 다큐, 과학 vs 엔지니어링, AI CEO 유사성 (1건)
  - raw/articles/foldable-phone-202609.md — 삼성 vs 샤오미 vs 애플 폴더블폰 경쟁 (1건)
  - raw/articles/right-to-repair-eu.md — EU 수리 정보 공개 규제, 준수율 18% (1건)
- Concept 페이지 5건 생성:
  - concepts/build-vs-buy-ai.md — AI 시대 자체 개발 의사결정, "3년 차에는 누가 패치하는가"
  - concepts/startup-brand-clock-speed.md — 스타트업 브랜드 구축과 clock speed, 정성은 결과물에 드러남
  - concepts/science-vs-engineering-hype.md — 과학 vs 엔지니어링, 기술 과장과 검증, Theranos→AI CEO
  - concepts/foldable-phone-competition-202609.md — 폴더블폰 경쟁 본격화, 삼성 하드웨어 차별화 재평가
  - concepts/right-to-repair-autonomy.md — 수리권과 소비자 하드웨어 자립, 규제 집행의 과제
- 기존 페이지 업데이트:
  - entities/gpt-6-astra.md — Claude Code 혼합 사용 사례, 과학 vs 엔지니어링 링크 추가
  - entities/samsung-electronics.md — 2026-09-08 폴더블폰 경쟁 본격화 섹션 추가
- 총 32페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제 RSS 2건 수집 — AI 테마주/초고수 동향, 카카오뱅크 플랫폼 확장
- RSS 피드: 한국경제(증권/경제)
- 수집된 글 2건, 키워드 필터(AI, 주식) 통과
- Raw 소스 2건 생성:
  - raw/articles/openai-product-stocks-202609.md — 오픈AI 신제품 출시, 초고수 투자자 동향 (1건)
  - raw/articles/kakaobank-platform-expansion-202609.md — 카카오뱅크 자동차 대출 비교 + 주식 투자 기능 (1건)
- Concept 페이지 1건 생성:
  - concepts/ai-theme-investor-flow-202609.md — AI 테마주 투자 동향, 오픈AI 신제품 → 초고수 매수 종목
- Entity 페이지 1건 생성:
  - entities/kakaobank.md — 인터넷 전문은행, 종합 금융 플랫폼 확장 (자동차 대출 비교, 주식 투자)
- 총 34페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | GeekNews 1건 + 한국경제 2건 수집 — AI 구독 선택, 건설주 수혜, 인버스 베팅
- RSS 피드: GeekNews, 한국경제(증권)
- 수집된 글 3건, 키워드 필터(GPT, 기관, 코스피) 통과
- Raw 소스 3건 생성:
  - raw/articles/ai-subscription-choice-202609.md — Ask GN: Claude vs GPT 단일 구독 선택 질문 (1건)
  - raw/articles/construction-public-relocation-202609.md — 공공기관 이도향촌, 건자재·건설주 강세 (1건)
  - raw/articles/inverse-retail-202609.md — 코스피 상승장에서 개미 2,000억 인버스 매수 (1건)
- Concept 페이지 3건 생성:
  - concepts/ai-subscription-choice-202609.md — AI 구독 단일 선택 딜레마, Claude vs GPT, 사이드프로젝트용 AI 비교
  - concepts/construction-sector-202609.md — 공공기관 이도향촌 → 건설주 수혜, 정책 드라이브 섹터 분석
  - concepts/inverse-retail-betting-202609.md — 인버스 베팅과 개인 투자자 행태, 조정 대비 vs 헤지 전략
- 기존 페이지 업데이트: 없음
- 총 37페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨