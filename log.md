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

## [2026-09-08] ingest | 한국경제 RSS 5건 수집 — 코스피 EPS 둔화/환율/국채/기관투자자
- RSS 피드: 한국경제-증권
- 수집된 글 5건, 키워드 필터(투자, 증권, 코스피, 반도체, 환율, 기관) 통과
- Raw 소스 2건 생성 (그룹화):
  - raw/articles/kospi-eps-warning-20260908.md — EPS 둔화 경고, 환율 하락, 코스피 7100선, SK하이닉스 5%↑ (3건)
  - raw/articles/pension-bond-krx-acga-20260908.md — NH투자증권 DC·IRP 국채 청약, KRX-ACGA 라운드테이블 (2건)
- Concept 페이지 2건 생성:
  - concepts/kospi-eps-slowdown-20260908.md — EPS 증가율 97%→50% 반토막, 이익 둔화 경고, ROE 중심 투자, 고금리 고착화
  - concepts/pension-bond-institutional-20260908.md — 연금계좌 국채 투자, KRX-ACGA 기관투자자 라운드테이블, 밸류업 공시 756개사
- 기존 페이지 업데이트:
  - concepts/kospi-7000-202609.md — 오후 장 7,100선 돌파, SK하이닉스 5%↑, EPS 둔화 경고 추가
  - entities/sk-hynix.md — 2026-09-08 시황 wikilinks 추가
  - entities/dollar.md — 환율 하락, 일본 국채 3%, 연금계좌 국채 청약 추가
- 총 39페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제 RSS 3건 수집 — 의료 AI/국방 AI/AI칩 양산
- RSS 피드: 한국경제-IT, 한국경제-경제
- 수집된 글 3건, 키워드 필터(AI, 조직, 삼성) 통과
- Raw 소스 1건 생성:
  - raw/articles/medical-ai-defense-ai-20260908.md — 네이버 의료 AI 조직 신설, 한화 GPU 팜, 세미파이브 4나노 양산 (3건)
- Entity 페이지 1건 생성:
  - entities/hanwha-aerospace.md — 한화에어로스페이스, 국방 AI GPU 팜 구축
- Concept 페이지 1건 생성:
  - concepts/ai-sector-expansion-20260908.md — AI 도메인 확장: 의료·국방·파운드리
- 기존 페이지 업데이트:
  - entities/samsung-electronics.md — 파운드리 4나노 AI칩 양산 수혜 섹션 추가
  - entities/semiconductor-industry.md — AI칩 양산 시대 진입 섹션 추가
- 총 42페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제 RSS 9건 수집 — AI 칩 지정학/미 채권/코스피/증권사/GPT-6/소상공인/중국 수출
- RSS 피드: 한국경제-증권, 한국경제-IT, 한국경제-경제
- 수집된 글 9건, 키워드 필터(AI, 주식, 코스피, 삼성, 증권, 투자, 반도체) 통과
- Raw 소스 9건 생성:
  - raw/articles/huawei-ai-chip-malaysia-20260908.md — 말레이시아 화웨이 어센드 910C 도입 검토
  - raw/articles/us-treasury-yield-20260908.md — 미 10년물 4.8%, 장기채 ETF 마이너스
  - raw/articles/kospi-dip-20260908.md — 코스피 0.58% 하락 마감
  - raw/articles/kb-securities-commercial-paper-20260908.md — KB증권 발행어음 AA+ 신용
  - raw/articles/samsung-securities-support-20260908.md — 삼성증권 주식·금현물 지원금
  - raw/articles/shinhan-light-products-20260908.md — 신한투자증권 Light 수수료 제로
  - raw/articles/gpt6-astra-token-cost-20260908.md — GPT-6 Astra 토큰 비용, 에이전트 1000배 소비
  - raw/articles/traditional-store-ai-cctv-20260908.md — 백년가게 AI CCTV 도입
  - raw/articles/china-ai-export-20260908.md — 중국 수출 +25%, 반도체 가격 700% 상승
- Concept 페이지 7건 생성:
  - concepts/huawei-ai-chip-geopolitics-20260908.md — 화웨이 AI 칩 지정학
  - concepts/us-treasury-yield-20260908.md — 미 장기채 금리 상승과 안전자산 논쟁
  - concepts/securities-firm-cash-strategy-20260908.md — 증권사 현금 관리 전략 (3사 통합)
  - concepts/kospi-afternoon-dip-20260908.md — 코스피 오후 하락 반전
  - concepts/gpt6-astra-token-economics-20260908.md — GPT-6 Astra 토큰 경제학
  - concepts/traditional-store-ai-adoption-20260908.md — 전통 소상공인 AI 도입
  - concepts/china-ai-export-20260908.md — 중국 AI 수출 호조와 반도체 가격 폭등
- 기존 페이지 업데이트:
  - entities/gpt-6-astra.md — 토큰 비용 현실 섹션 추가, 토큰 경제학 링크
  - entities/semiconductor-industry.md — 반도체 가격 폭등·중국 수출 섹션 추가
  - concepts/kospi-7000-202609.md — 오후 하락 반전 링크 추가
  - concepts/ai-sector-expansion-20260908.md — 화웨이·소상공인·중국 수출 링크 추가
- 총 49페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | RSS 2차 수집 — 14건 인제스트
- Raw 소스 14건 인제스트:
  - raw/articles/mistral-3b-funding-20260908.md — Mistral 30억 유로 투자, 삼성 주도
  - raw/articles/us-investment-162t-20260908.md — 대미 투자 162조원, JP모건 톱픽
  - raw/articles/nuclear-power-us-investment-20260908.md — 원전 8기 수혜 종목 30% 급등
  - raw/articles/pension-bond-8pct-20260908.md — 퇴직연금 국채 연 8%대
  - raw/articles/mirae-asset-ai-pension-20260908.md — 미래에셋 AI 연금 자산배분
  - raw/articles/nh-private-equity-fund-20260908.md — NH 사모펀드 분산투자 공모펀드
  - raw/articles/asia-memory-etf-20260908.md — 아시아 메모리 초집중 ETF
  - raw/articles/robotics-gpt-moment-20260908.md — 로봇 GPT 모멘트, 비용 붕괴 임박
  - raw/articles/dividend-stock-season-20260908.md — 배당주 시즌, 분리과세
  - raw/articles/high-dividend-etf-semi-20260908.md — 고배당 ETF 반도체 편차
  - raw/articles/valueup-shareholder-return-20260908.md — 밸류업지수 vs 진짜 주주환원주
  - raw/articles/samsung-tsmc-niche-20260908.md — 삼성·TSMC 틈새 파운드리 기업
  - raw/articles/samsung-employee-housing-20260908.md — 삼성 주거지원금 축소 우려
  - raw/articles/samsung-asml-euv-20260908.md — 삼성 ASML 12인치 포토마스크, 2028 EUV
- Concept 페이지 8건 생성:
  - concepts/mistral-funding-20260908.md — Mistral 30억 유로 투자 유치
  - concepts/us-investment-beneficiaries-20260908.md — 대미 투자 162조원 수혜주와 원전 수출
  - concepts/pension-ai-bond-20260908.md — 퇴직연금 국채 8%대·AI 자산배분
  - concepts/asia-memory-etf-20260908.md — 아시아 메모리 초집중 ETF
  - concepts/robotics-gpt-moment-20260908.md — 로봇 GPT 모멘트
  - concepts/dividend-shareholder-season-20260908.md — 배당주·주주환원 시즌
  - concepts/samsung-tsmc-niche-20260908.md — 삼성·TSMC 틈새 파운드리 기업
  - concepts/samsung-asml-euv-20260908.md — 삼성 ASML 12인치 포토마스크·차세대 EUV
- 기존 페이지 업데이트:
  - entities/samsung-electronics.md — Mistral 투자 주도, ASML EUV 도입, 복지 리스크 섹션 추가
- 총 57페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | RSS 3차 수집 — 12건 인제스트, 반도체/AI 인프라/증권/암호학
- RSS 피드: GeekNews, 한국경제(증권/IT/경제)
- 수집된 글 12건, 키워드 필터(기관, 증권, 투자, 반도체, AI, 코스피, 연기금, 다크팩토리) 통과
- 1건 제외: 하나은행 캠페인 포토 기사 (위키 도메인 범위 외)
- Raw 소스 11건 생성:
  - raw/articles/rsa-key-factorization-20260908.md — 512비트 RSA 키 인수분해, CADO-NFS (1건)
  - raw/articles/securities-polarization-20260908.md — 빅5 순익 62%, 증권업 양극화 (1건)
  - raw/articles/nuclear-rally-20260908.md — 한전기술 30% 급등, 두산에너빌 4조 수주 (1건)
  - raw/articles/sk-innovation-pension-20260908.md — SK이노 연매출 100조, 연기금 1000억 매수 (1건)
  - raw/articles/semiconductor-rebalancing-20260908.md — 반도체 지수 리밸런싱, 소부장 재분배 (1건)
  - raw/articles/retail-exit-20260908.md — 개미 본전 심리, 코스피 7000 탈환 실패 (1건)
  - raw/articles/photonics-ai-20260908.md — 터틀캐피탈 포토닉스 집중, AI 차세대 수혜 (1건)
  - raw/articles/naver-medical-ai-20260908.md — 네이버 CEO 직속 헬스케어 조직 신설 (1건)
  - raw/articles/kt-dark-factory-20260908.md — KT+다임리서치 다크팩토리 플랫폼 (1건)
  - raw/articles/semiconductor-gni-40k-20260908.md — 명목 GDP 26.4% 증가, GNI 4만弗 (1건)
  - raw/articles/sgc-ai-datacenter-20260908.md — SGC에너지+버티브 AI센터 인프라 (1건)
- Concept 페이지 7건 생성:
  - concepts/rsa-key-factorization-20260908.md — 512비트 RSA 인수분해, 암호학적 안전성의 시간 의존성
  - concepts/securities-polarization-20260908.md — 증권업 빅5 순익 62%, 자기자본 규모가 사업 자격 결정
  - concepts/sk-innovation-pension-20260908.md — SK이노 연기금 베팅, 배터리 호실적
  - concepts/semiconductor-rebalancing-20260908.md — 반도체 지수 리밸런싱, 삼전닉스→소부장
  - concepts/photonics-ai-20260908.md — 포토닉스 AI 다음 수혜, AI 인프라 계층도
  - concepts/dark-factory-platform-20260908.md — KT 다크팩토리, 로봇 비용 붕괴 구체화
  - concepts/sgc-ai-datacenter-20260908.md — AI 데이터센터 에너지 인프라, SGC+버티브
- 기존 페이지 업데이트:
  - concepts/us-investment-beneficiaries-20260908.md — 원전주 동반 랠리 업데이트 (한전기술 30%, 두산에너빌 4조)
  - concepts/kospi-afternoon-dip-20260908.md — 개미 본전 심리 손절 매물, 7000 탈환 실패 추가
  - concepts/ai-sector-expansion-20260908.md — 네이버 의료AI 조직 신설, KT 다크팩토리, SGC AI센터 추가
  - concepts/korea-gni-40k-202609.md — 명목 GDP 26.4% 증가, 반도체 견인 GNI 4만弗 업데이트
- 총 65페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제·GeekNews RSS 7건 추가 수집 — 삼성SDS/국가AI/미스트랄/ASML/원전/AI가격
- RSS 피드: 한국경제(IT/경제), GeekNews
- 수집된 글 7건, 키워드 필터 통과
- Raw 소스 7건 생성:
  - raw/articles/stage-gen-2d-game-assets-20260908.md — stage-gen 2D 게임 에셋 AI 생성 (1건)
  - raw/articles/samsung-sds-robot-platform-20260908.md — 삼성SDS 로봇 오케스트레이션, AX/RX (1건)
  - raw/articles/national-ai-strategy-1yr-20260908.md — 국가AI전략위 1주년, 실용화 전환 (1건)
  - raw/articles/samsung-asml-euv-details-20260908.md — 12인치 포토마스크 상세, High-NA EUV (1건)
  - raw/articles/nuclear-wec-stake-20260908.md — WEC 지분 인수, 원전 8기 APR1400 (1건)
  - raw/articles/samsung-mistral-investment-20260908.md — 삼성 미스트랄 투자 상세, 소버린 AI (1건)
  - raw/articles/ai-price-competition-shift-20260908.md — 토큰 단가→총비용 경쟁 기준 전환 (1건)
- Concept 페이지 3건 생성:
  - concepts/ai-game-asset-generation-20260908.md — AI 게임 에셋 생성, 안목과 AI 시대 연결
  - concepts/samsung-sds-robot-orchestration-20260908.md — 로봇 오케스트레이션, 로봇 GPT 모멘트 연결
  - concepts/national-ai-strategy-1yr-20260908.md — 국가 AI 전략 실용화, AI 조직 전환 연결
- 기존 페이지 업데이트 4건:
  - concepts/samsung-asml-euv-20260908.md — 12인치 포토마스크 상세, 경쟁사 로드맵 추가
  - concepts/mistral-funding-20260908.md — 삼성 협력 심화, 소버린 AI, HBM 수요 추가
  - concepts/gpt6-astra-token-economics-20260908.md — 가격 경쟁 기준 전환, 총비용 개념 추가
  - concepts/us-investment-beneficiaries-20260908.md — WEC 지분 인수, APR1400 관철 추가
- 총 68페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제 RSS 1건 수집 — 비트코인 블록체인 해킹 4300억 증발
- RSS 피드: 한국경제-경제
- 수집된 글 1건, 키워드 필터(비트코인) 통과
- Raw 소스 1건 생성:
  - raw/articles/bitcoin-blockchain-hack-20260908.md — 비트코인 블록체인 해킹, 4300억원 증발 (1건)
- Concept 페이지 1건 생성:
  - concepts/bitcoin-blockchain-exploit-20260908.md — 블록체인 보안 리스크, 디지털 금 서사의 한계, 코인 비중 재평가
- 기존 페이지 업데이트:
  - entities/bitcoin.md — 보안 리스크 섹션 추가, tags에 리스크관리 추가, sources에 해킹 기사 추가
- 총 69페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제 RSS 1건 수집 — 엔캐리 트레이드 청산과 엔화 강세
- RSS 피드: 한국경제-경제
- 수집된 글 1건, 키워드 필터(금리) 통과
- Raw 소스 1건 생성:
  - raw/articles/yen-carry-trade-20260908.md — BOJ 금리 인상 가시화, 엔화 152.89엔 급등, 엔캐리 자금 3조 달러, 2024년과 다른 점진적 청산 (1건)
- Concept 페이지 1건 생성:
  - concepts/yen-carry-trade-20260908.md — 엔캐리 트레이드 청산과 엔화 강세, BOJ 9월 인상 97% 확률, 숏커버링 연쇄 리스크
- 기존 페이지 업데이트:
  - entities/dollar.md — 엔화 강세·엔캐리 청산 섹션 추가, 달러 약세+엔화 강세 동시 진행
  - concepts/us-treasury-yield-20260908.md — 엔캐리 트레이드 링크 추가, 미·일 금리 격차 맥락 연결
- 총 70페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-08] ingest | 한국경제 RSS 2건 수집 — AI 학업능력 저하 & 중국 노광장비 자립화
- RSS 피드: 한국경제-경제
- 수집된 글 2건, 키워드 필터(AI, 반도체) 통과
- Raw 소스 2건 생성:
  - raw/articles/ai-homework-academic-decline-20260908.md — 한국 학생 동아시아 최저 학업능력, AI 숙제 의촉 1.5년 뒤처짐 (1건)
  - raw/articles/china-lithography-equipment-20260908.md — 화웨이·SMIC·위량성 DUV 노광장비 개발, ASML 독점 위협 (1건)
- Concept 페이지 2건 생성:
  - concepts/ai-homework-academic-decline-20260908.md — AI 숙제 의존과 학업능력 저하, 인지 바이러스의 교육적 실증, LLM 인지 영향·AI 정렬·안목과 AI 연결
  - concepts/china-lithography-equipment-20260908.md — 중국 노광장비 자립화와 반도체 밸류체인 재편, 화웨이 AI 칩 지정학·삼성 ASML EUV·중국 AI 수출 연결
- 기존 페이지 업데이트 2건:
  - entities/semiconductor-industry.md — 중국 노광장비 자립화 링크 추가
  - concepts/huawei-ai-chip-geopolitics-20260908.md — 칩 설계 자립화 → 장비 자립화 확장 링크 추가
- 총 72페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | GeekNews·한국경제 RSS 2건 수집 — Arm 피지컬 AI 생태계 & 유가급등 속 반도체 반등
- RSS 피드: GeekNews, 한국경제-경제
- 수집된 글 2건, 키워드 필터(AI, 반도체) 통과
- Raw 소스 2건 생성:
  - raw/articles/arm-physical-ai-ecosystem-20260909.md — Arm Total Design for Physical AI, 80개 기업 참여, 전 스택 협업 (1건)
  - raw/articles/oil-surge-ny-market-dip-20260909.md — 유가급등·무역긴장으로 뉴욕증시 하락, 반도체주 반등 (1건)
- Concept 페이지 2건 생성:
  - concepts/arm-physical-ai-ecosystem-20260909.md — 피지컬 AI 생태계 협업, 로봇 비용 붕괴 가속, AI 인프라 확장·로봇 GPT 모멘트·삼성SDS 로봇 오케스트레이션 연결
  - concepts/oil-surge-semiconductor-rebound-20260909.md — 매크로 헤드윈드 속 반도체 반등, AI 수요가 펀더멘털 회복력 근거, 중국 AI 수출·코스피 시황 연결
- 기존 페이지 업데이트 1건:
  - entities/semiconductor-industry.md — 피지컬 AI 생태계 협업 섹션 + 매크로 헤드윈드 속 반도체 반등 섹션 추가
- 총 74페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | GeekNews·한국경제 RSS 2건 수집 — LibreOffice AI 비탑재 & 삼성-미스트랄 투자 재확인
- RSS 피드: GeekNews, 한국경제-경제
- 수집된 글 2건, 키워드 필터(AI, 투자, 삼성) 통과
- Raw 소스 2건 생성:
  - raw/articles/libreoffice-ai-free-20260909.md — LibreOffice 26.8 AI 비탑재, 100만 다운로드, 프라이버시 차별점 (1건)
  - raw/articles/samsung-mistral-investment-20260909.md — 삼성전자 미스트랄 수천억원 투자 규모 재확인 (1건)
- Concept 페이지 1건 생성:
  - concepts/libreoffice-ai-free-20260909.md — AI 비탑재를 차별점으로 100만 다운로드, AI 의존 거부·데이터 주권·인지 자율성 흐름, 셀프 호스팅·AI 인지 관리·Build vs Buy·안목과 AI·AI 구독 선택 연결
- 기존 페이지 업데이트 2건:
  - concepts/mistral-funding-20260908.md — 삼성전자 투자 규모 "수천억원" 재확인 섹션 추가 (3차 업데이트)
  - entities/samsung-electronics.md — 미스트랄 수천억원 투자 재확인 섹션 추가
- 총 75페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | GeekNews RSS 1건 수집 — AI 시대의 사무실 복귀 강요 (RTO) 풍자
- RSS 피드: GeekNews
- 수집된 글 1건, 키워드 필터(AI) 통과
- Raw 소스 1건 생성:
  - raw/articles/ai-rto-satire-20260909.md — AI 버튼 클릭 노동 vs 사무실 복귀 강요, Mondo Mayo 풍자 (1건)
- Concept 페이지 1건 생성:
  - concepts/ai-rto-satire-20260909.md — AI 시대의 RTO 강요 역설, 조직 권위와 AI 결합, 버튼 클릭 노동, AI 조직 전환·부바부·안목과 AI·생산자 몰입·LLM 인지 영향·LibreOffice AI 비탑재 연결
- 기존 페이지 업데이트: 없음
- 총 77페이지, 모든 신규 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | Navier–Stokes 밀레니엄 문제와 OpenAI AI 증명
- 수집된 글 1건, 키워드 필터(AI) 통과
- Raw 소스 1건 생성:
  - raw/articles/navier-stokes-openai-proof-20260909.md — OpenAI의 3D Navier–Stokes 특이점 증명, Lean 형식화, 밀레니엄 상금 문제 C·D 입증 주장 (1건)
- Concept 페이지 1건 생성:
  - concepts/navier-stokes-millennium-openai-20260909.md — AI의 순수 수학 증명 능력, Lean 형식적 검증, AI 능력 범위 확장, 과학 vs 엔지니어링·RSA 인수분해·GPT-6 Astra·AI 정렬과 안전성 연결
- 기존 페이지 업데이트: 없음
- 총 77페이지, 신규 페이지 4개 아웃바운드 wikilinks로 기존 페이지와 연결됨

## [2026-09-09] ingest | 한국경제 RSS 2건 — 중동 유가 충돌 & 삼성 vs LG 로봇청소기
- RSS 피드: 한국경제 (증권/경제)
- 수집된 글 2건
- Raw 소스 2건 생성:
  - raw/articles/middle-east-oil-100-20260909.md — 중동 충돌(후티 아람코 공격, 이란 유조선 미군 공격), 유가 100달러 육박, 3대 지수 하락, 반도체 반등, CPI/FOMC 리스크
  - raw/articles/samsung-lg-robot-vacuum-20260909.md — 귀곰 리뷰 삼성 vs LG 로봇청소기 9항목 비교, 회피력 차이 결정적, 국내 브랜드 중국 반격
- Concept 페이지 1건 생성:
  - concepts/samsung-lg-robot-vacuum-20260909.md — 삼성 vs LG 로봇청소기 경쟁, 회피력 핵심 차별화, 중국 브랜드 반격, 피지컬 AI 응용 (6개 아웃바운드 링크)
- 기존 페이지 업데이트 2건:
  - concepts/oil-surge-semiconductor-rebound-20260909.md — 중동 충돌 상세(후티, 이란), 유가 수치, 구리 강세, CPI/FOMC 리스크 추가, 출처 확장
  - entities/samsung-electronics.md — 로봇청소기 시장 1위 달성 & LG 경쟁 섹션 추가, 소스 확장
- 총 78페이지, 모든 신규/업데이트 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | RSS 9건 수집 — AI 에이전트/이미지/증권/환율 (스크립트 오류 수동 실행)
- ⚠️ 크론 스크립트 오류: `Script not found: /Users/mac/.hermes/scripts/python3 ~/.hermes/scripts/wiki-collector.py` — 크론 명령어 파싱 오류로 `python3`가 경로의 일부로 해석됨. 수동 실행으로 복구.
- RSS 피드: GeekNews, 한국경제(증권/경제)
- 수집된 글 9건, 키워드 필터 통과 9건, 도메인 부적합 스킵 1건(떡지순례 — 투자/커리어/자산관리 무관)
- Raw 소스 8건 생성:
  - raw/articles/navier-stokes-buckmaster-20260909.md — Buckmaster의 OpenAI 협의 과정 공개, LLM 활용 개인 공동연구
  - raw/articles/chatgpt-images-2-5-20260909.md — ChatGPT Images 2.5, 주 30억 장, 참조 재현도 향상, 지연 50% 단축
  - raw/articles/davinci-resolve-21-1-20260909.md — DaVinci Resolve 21.1, Claude·Codex 연동, 자연어 영상 편집
  - raw/articles/meta-muse-agent-20260909.md — Meta Muse 개인 AI 에이전트, Secure VM, WhatsApp 연동
  - raw/articles/ai-model-competition-samsung-20260909.md — AI 모델 경쟁 격화, 삼성전자 최대 수혜
  - raw/articles/ms-semiconductor-momentum-20260909.md — 유가 100달러 속 반도체 급등, MS "마지막 불꽃" 경고
  - raw/articles/securities-consensus-top5-20260909.md — 증권사 컨센서스 상향 톱5, 유의점
  - raw/articles/currency-war-japan-india-20260909.md — 일본 15조엔·인도 150억달러 환율 개입
- Concept 페이지 6건 생성:
  - concepts/chatgpt-images-2-5-20260909.md — 이미지 생성 품질·속도 동시 개선, AI 도구 경쟁 확장 (4개 아웃바운드 링크)
  - concepts/davinci-resolve-21-1-20260909.md — AI 어시스턴트 영상 편집 통합, 자연어 인터페이스 확장 (4개 아웃바운드 링크)
  - concepts/meta-muse-agent-20260909.md — 개인 AI 에이전트, Secure VM 아키텍처, 에이전트 투명성·안전성 (4개 아웃바운드 링크)
  - concepts/ai-model-competition-samsung-20260909.md — AI 경쟁→반도체 수요 파이프라인, 삼성 포지션 (7개 아웃바운드 링크)
  - concepts/securities-consensus-top5-20260909.md — 컨센서스 상향 의미, 밸류에이션 함정 (4개 아웃바운드 링크)
  - concepts/currency-war-japan-india-20260909.md — 환율 전쟁 전파 경로, 일본·인도 개입 맥락 (6개 아웃바운드 링크)
- 기존 페이지 업데이트 3건:
  - concepts/navier-stokes-millennium-openai-20260909.md — Buckmaster 협의 과정 공개 섹션 추가, 소스 확장
  - concepts/oil-surge-semiconductor-rebound-20260909.md — MS "마지막 불꽃" 경고 섹션 추가, 소스 확장
  - entities/samsung-electronics.md — AI 모델 경쟁 최대 수혜주 섹션 추가, 소스 확장
- 총 84페이지, 모든 신규/업데이트 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | 한국경제 RSS 6건 수집 — 코스피 시황/삼성 계열사/고유가 수혜/위안화/노바티스/AI 회사채
- ⚠️ 크론 스크립트 오류: `Script not found: /Users/mac/.hermes/scripts/python3 ~/.hermes/scripts/wiki-collector.py` — 크론 명령어 파싱 오류. 수동 실행으로 복구.
- RSS 피드: 한국경제(증권/경제)
- 수집된 글 6건, 키워드 필터 통과 6건
- Raw 소스 5건 생성:
  - raw/articles/kospi-kosdaq-morning-20260909.md — 코스피 강보합·코스닥 1%대 상승 & 초고수 삼성 계열사 회전 매매 (2건)
  - raw/articles/high-oil-beneficiaries-20260909.md — 고유가 수혜주·피해주 양극화 (1건)
  - raw/articles/china-yuan-borrowing-20260909.md — 중국 저금리, 위안화 채권 1500억달러 육박 (1건)
  - raw/articles/novartis-drug-failure-20260909.md — 노바티스 120억달러 근육질환 신약 임상 실패 (1건)
  - raw/articles/ai-ipo-corporate-bond-20260909.md — 오픈AI·앤스로픽 상장 후 회사채 시장 진입 (1건)
- Concept 페이지 3건 생성:
  - concepts/kospi-kosdaq-session-20260909.md — 코스피 시황 & 삼성 계열사 초고수 회전 매매 (6개 아웃바운드 링크)
  - concepts/china-yuan-borrowing-20260909.md — 중국 위안화 차입 급증과 글로벌 자본 흐름 (4개 아웃바운드 링크)
  - concepts/novartis-drug-failure-20260909.md — 노바티스 신약 좌초, 바이오 투자 리스크 (3개 아웃바운드 링크)
  - concepts/ai-ipo-corporate-bond-20260909.md — AI 유니콘 자본 구조 성숙, 에쿼티+뎁트 결합 (6개 아웃바운드 링크)
- 기존 페이지 업데이트 1건:
  - concepts/oil-surge-semiconductor-rebound-20260909.md — 수혜주·피해주 양극화 섹션 추가, 소스 확장
- 총 88페이지, 모든 신규/업데이트 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | RSS 2차 수집 — GeekNews 7건 + 한국경제 5건 = 12건
- ⚠️ 크론 스크립트 오류 재발: `Script not found` — 경로 파싱 문제. 수동 실행으로 복구.
- RSS 피드: GeekNews, 한국경제(증권/IT/경제)
- 수집된 글 12건, 키워드 필터 통과 12건
- Raw 소스 12건 생성:
  - raw/articles/routar-typed-http-20260909.md — routar 타입세이프 HTTP 클라이언트 (GeekNews)
  - raw/articles/extreme-ssr-20260909.md — 극단적 SSR 실험 (GeekNews)
  - raw/articles/europe-cloud-providers-20260909.md — 유럽 클라우드 제공업체 비교 (GeekNews)
  - raw/articles/qwen-drive-autonomous-20260909.md — Qwen-Drive 자율주행 AI (GeekNews)
  - raw/articles/caltech-mathathon-20260909.md — Caltech AI 수학 해커톤 (GeekNews)
  - raw/articles/dhs-predictive-policing-20260909.md — DHS 예측 치안 금융 데이터 (GeekNews)
  - raw/articles/paramount-grassroots-merger-20260909.md — Paramount 위장 풀뿌리 (GeekNews)
  - raw/articles/doosan-fuelcell-datacenter-20260909.md — 두산퓨얼셀 미 데이터센터 (한국경제)
  - raw/articles/sangsan-securities-listing-20260909.md — 상상인증권 액면병합 급락 (한국경제)
  - raw/articles/samsung-oil-burden-20260909.md — 삼전닉스 유가 부담 (한국경제)
  - raw/articles/hem-pharma-ai-health-20260909.md — HEM파마 AI 헬스케어 (한국경제)
  - raw/articles/hanwha-gpu-farm-20260909.md — 한화에어로 GPU 팜 (한국경제)
- Concept 페이지 11건 생성:
  - concepts/routar-typed-http-client-20260909.md — 프론트엔드 API 스키마 관리 (2개 아웃바운드 링크)
  - concepts/extreme-ssr-20260909.md — 극단적 SSR (2개 아웃바운드 링크)
  - concepts/europe-cloud-providers-20260909.md — 유럽 클라우드 비교 (2개 아웃바운드 링크)
  - concepts/qwen-drive-autonomous-20260909.md — 자율주행 AI (2개 아웃바운드 링크)
  - concepts/caltech-mathathon-20260909.md — AI 수학 해커톤 (2개 아웃바운드 링크)
  - concepts/doosan-fuelcell-datacenter-20260909.md — 두산퓨얼셀 데이터센터 (2개 아웃바운드 링크)
  - concepts/samsung-oil-burden-20260909.md — 삼전닉스 유가 부담 (2개 아웃바운드 링크)
  - concepts/dhs-predictive-policing-20260909.md — 예측 치안과 금융 데이터 (2개 아웃바운드 링크)
  - concepts/paramount-grassroots-merger-20260909.md — Paramount 합병 위장 캠페인 (2개 아웃바운드 링크)
  - concepts/sangsan-securities-listing-20260909.md — 상상인증권 급락 (2개 아웃바운드 링크)
  - concepts/hem-pharma-ai-health-20260909.md — HEM파마 AI 헬스케어 (2개 아웃바운드 링크)
- 기존 엔티티 페이지 업데이트 1건:
  - entities/hanwha-aerospace.md — GPU 팜 소스 추가, wikilink 개선, 업데이트 이력 추가
- 총 100페이지, 모든 신규/업데이트 페이지 기존 페이지와 wikilinks로 연결됨
## [2026-09-09] ingest | RSS 수집 — 5건 신규
- RSS 피드: GeekNews, 한국경제(증권)
- 수집된 글 5건, 키워드 필터 통과 5건
- Raw 소스 5건 생성:
  - raw/articles/copperhead-pcb-ai-20260909.md — Copperhead 회로 기판 AI (GeekNews)
  - raw/articles/ai-infra-rally-cpu-optical-power-20260909.md — AI 인프라 랠리 CPU·광통신·전력 (한국경제)
  - raw/articles/pension-etf-guide-20260909.md — 퇴직연금 ETF 매수 가이드 (한국경제)
  - raw/articles/samsung-plan-overhaul-fx-20260909.md — 삼성 내년 계획 전면 재검토 환율 비상 (한국경제)
  - raw/articles/daishin-creon-customer-20260909.md — 대신증권 크레온 비대면 고객 유치 (한국경제)
- Concept 페이지 5건 생성:
  - concepts/copperhead-pcb-ai-20260909.md — 회로 기판 AI 코파일럿 (3개 아웃바운드 링크)
  - concepts/ai-infra-rally-expansion-20260909.md — AI 인프라 랠리 키워드 확장 (4개 아웃바운드 링크)
  - concepts/pension-etf-guide-20260909.md — 퇴직연금 ETF 매수 가이드 (3개 아웃바운드 링크)
  - concepts/samsung-plan-overhaul-fx-20260909.md — 삼성 환율 널뛰기 비상 (4개 아웃바운드 링크)
  - concepts/daishin-creon-customer-20260909.md — 대신증권 비대면 고객 유치 (4개 아웃바운드 링크)
- 기존 엔티티 페이지 업데이트 2건:
  - entities/samsung-electronics.md — 환율 널뛰기 리스크 소스 추가, 내년 계획 재검토 섹션 추가
  - entities/dollar.md — 2026-09-09 환율 11% 급락 업데이트 추가, 삼성 계획 재검토 연결
- 총 105페이지, 모든 신규/업데이트 페이지 기존 페이지와 wikilinks로 연결됨

## [2026-09-09] ingest | RSS 16건 수집 — AI 안전성/코딩 철학/메모리/IPO/정밀가공
- RSS 피드: GeekNews (5건), 한국경제-증권 (3건), 한국경제-경제 (5건), 한국경제-IT (0건), 인프랩 (0건)
- 수집된 글 16건, 키워드 필터(AI, GPT, 삼성, 메모리, 투자, 달러, 경제 등) 통과
- Raw 소스 16건 생성:
  - raw/articles/anthropic-resignation-ai-safety-20260909.md — Anthropic 연구자 사직, AI 안전성 비판
  - raw/articles/ai-wrong-build-well-20260909.md — AI 개발의 진짜 위험: 잘못된 생각을 잘 구현
  - raw/articles/quiz-gate-code-review-20260909.md — Quiz Gate: git diff 기반 코드 리뷰 퀴즈 앱
  - raw/articles/tao-math-mining-20260909.md — Tao: AI가 수학 문제를 재생불가능 자원처럼 채굴
  - raw/articles/gpt6-astra-skills-prompts-20260909.md — GPT-6 Astra 스킬과 프롬프트 재설계
  - raw/articles/programming-as-art-20260909.md — 프로그래밍은 예술이다: AI 시대의 코딩 동기
  - raw/articles/belgium-transit-webgl-20260909.md — 벨기에 대중교통 WebGL 이슈
  - raw/articles/kimi-k3-macbook-streaming-20260909.md — Kimi K3 2.8T SSD 스트리밍 로컬 실행
  - raw/articles/ge-aerospace-cpp-acquisition-20260909.md — GE에어로스페이스 CPP 117억달러 인수
  - raw/articles/target-date-fund-fss-20260909.md — 목표전환형 펀드, 금감원 C클래스 가이드
  - raw/articles/openai-ipo-retail-nervous-20260909.md — IPO 러시 속 개인 투자자 긴장
  - raw/articles/samsung-foldable-precision-20260909.md — 삼성 0.001g 정밀가공, 여권폰 경쟁력
  - raw/articles/samsung-health-tech-20260909.md — 삼성 기술 심장 살린 사례
  - raw/articles/sk-hynix-fullstack-ai-memory-20260909.md — SK하이닉스 풀스택 AI 메모리 승부수
  - raw/articles/economy-leap-committee-20260909.md — 경제대도약위원회 출범
  - raw/articles/hyundai-flood-relief-20260909.md — 현대차 네팔 홍수 성금 50만 달러
- Concept 페이지 11건 생성:
  - concepts/anthropic-resignation-safety-20260909.md — Anthropic 연구자 사직과 AI 안전성 내부 비판 (3개 아웃바운드 링크)
  - concepts/ai-wrong-build-well-20260909.md — AI 개발의 진짜 위험: 잘못된 생각을 너무 잘 구현 (5개 아웃바운드 링크)
  - concepts/tao-math-mining-20260909.md — Tao 경고: AI가 수학 문제를 재생불가능 자원처럼 채굴 (3개 아웃바운드 링크)
  - concepts/gpt6-astra-skills-prompts-20260909.md — GPT-6 Astra 스킬과 프롬프트 재설계 (3개 아웃바운드 링크)
  - concepts/programming-as-art-20260909.md — 프로그래밍은 예술이다: AI 시대의 코딩 동기 (3개 아웃바운드 링크)
  - concepts/kimi-k3-local-streaming-20260909.md — Kimi K3 2.8T 로컬 실행: SSD 스트리밍 (3개 아웃바운드 링크)
  - concepts/ge-aerospace-acquisition-20260909.md — GE에어로스페이스 CPP 117억달러 인수 (2개 아웃바운드 링크)
  - concepts/target-date-fund-fss-20260909.md — 목표전환형 펀드와 C클래스 수수료 가이드 (2개 아웃바운드 링크)
  - concepts/ipo-rush-retail-dilemma-20260909.md — IPO 러시 속 개인 투자자의 선택 딜레마 (3개 아웃바운드 링크)
  - concepts/samsung-precision-health-20260909.md — 삼성 0.001g 정밀가공: 여권폰 경쟁력의 원천 (3개 아웃바운드 링크)
  - concepts/sk-hynix-fullstack-ai-memory-20260909.md — SK하이닉스 풀스택 AI 메모리 전략 (4개 아웃바운드 링크)
- 기존 엔티티 페이지 업데이트 2건:
  - entities/samsung-electronics.md — 정밀 가공 + 건강 기기 소스 추가, 새 섹션 추가
  - entities/sk-hynix.md — 풀스택 AI 메모리 섹션 추가, wikilinks 개선
- 기존 컨셉 페이지 업데이트 1건:
  - concepts/ai-safety-alignment.md — Anthropic 사직 소스 추가, confidence medium→high, 새 링크 2개 추가
- 총 116페이지, 모든 신규/업데이트 페이지 기존 페이지와 wikilinks로 연결됨
