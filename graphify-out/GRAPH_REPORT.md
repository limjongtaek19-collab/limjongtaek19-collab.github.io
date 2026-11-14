# Graph Report - limjongtaek19-collab.github.io  (2026-11-14)

## Corpus Check
- Corpus is ~1,252 words - fits in a single context window. You may not need a graph.

## Summary
- 30 nodes · 46 edges · 4 communities
- Extraction: 91% EXTRACTED · 9% INFERRED · 0% AMBIGUOUS · INFERRED: 4 edges (avg confidence: 0.72)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- 징검다리 채널 허브
- 생활 경제 · 연금
- 전자책 《집 한 채로 평생 월급 받기》
- 백세길잡이 · 건강과 마음공부

## God Nodes (most connected - your core abstractions)
1. `징검다리 · 백세길잡이 (홈페이지)` - 15 edges
2. `전자책: 집 한 채로 평생 월급 받기` - 11 edges
3. `연재: 주택연금과 연금 4총사` - 8 edges
4. `징검다리 (생활 경제 브랜드)` - 6 edges
5. `네이버 블로그: 바람이 전하는 말 (moonlighting2025)` - 5 edges
6. `백세길잡이 (건강 브랜드)` - 4 edges
7. `생활 경제` - 3 edges
8. `노후 설계` - 3 edges
9. `건강 상식` - 3 edges
10. `연재: 연말정산 완전정복 (20편)` - 3 edges

## Surprising Connections (you probably didn't know these)
- `전자책 표지 이미지` --references--> `전자책: 집 한 채로 평생 월급 받기`  [EXTRACTED]
  images/ebook-cover.jpg → index.html

## Hyperedges (group relationships)
- **연금으로 노후 생활비 마련** — index_주택연금, index_주택연금과_연금_4총사, index_집_한_채로_평생_월급_받기, index_노후_설계 [INFERRED 0.85]

## Communities (4 total, 0 thin omitted)

### Community 0 - "징검다리 채널 허브"
Cohesion: 0.33
Nodes (9): 연재: 반야심경 강해, 네이버 블로그: 바람이 전하는 말 (moonlighting2025), 인스타그램: 징검다리, 징검다리 (생활 경제 브랜드), 징검다리 · 백세길잡이 (홈페이지), 티스토리: snowball-2026, 티스토리: write0584, 틱톡: sunrise (+1 more)

### Community 1 - "생활 경제 · 연금"
Cohesion: 0.25
Nodes (8): 개인연금, 국민연금, 노후 설계, 생활 경제, 연재: 연말정산 완전정복 (20편), 주택연금, 연재: 주택연금과 연금 4총사, 퇴직연금

### Community 2 - "전자책 《집 한 채로 평생 월급 받기》"
Cohesion: 0.29
Nodes (7): 전자책 표지 이미지, 2026년에 바뀐 6가지 제도와 손익 계산, 가입 전 체크리스트 30문항 · 상담 질문지, 가입 전 꼭 알아야 할 결정 7가지, 나이·집값별 월지급금 표 (2026.6.1 기준), 전자책: 집 한 채로 평생 월급 받기, 크몽 (출간 예정 플랫폼)

### Community 3 - "백세길잡이 · 건강과 마음공부"
Cohesion: 0.40
Nodes (6): 건강 상식, 마음공부, 백세길잡이 (건강 브랜드), 네이버 블로그: 건강쉼터 (time_rich_life), 연재: 아침 7시의 혈당 (건강 추리 단편), 인스타그램: 백세길잡이

## Knowledge Gaps
- **12 isolated node(s):** `국민연금`, `퇴직연금`, `개인연금`, `티스토리: snowball-2026`, `티스토리: write0584` (+7 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 12 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `징검다리 · 백세길잡이 (홈페이지)` connect `징검다리 채널 허브` to `생활 경제 · 연금`, `전자책 《집 한 채로 평생 월급 받기》`, `백세길잡이 · 건강과 마음공부`?**
  _High betweenness centrality (0.602) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `전자책: 집 한 채로 평생 월급 받기` (e.g. with `연재: 주택연금과 연금 4총사` and `징검다리 (생활 경제 브랜드)`) actually correct?**
  _`전자책: 집 한 채로 평생 월급 받기` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `국민연금`, `퇴직연금`, `개인연금` to the rest of the system?**
  _12 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Why does `전자책: 집 한 채로 평생 월급 받기` connect `전자책 《집 한 채로 평생 월급 받기》` to `징검다리 채널 허브`, `생활 경제 · 연금`?**
  _High betweenness centrality (0.419) - this node is a cross-community bridge._
- **Why does `연재: 주택연금과 연금 4총사` connect `생활 경제 · 연금` to `징검다리 채널 허브`, `전자책 《집 한 채로 평생 월급 받기》`?**
  _High betweenness centrality (0.245) - this node is a cross-community bridge._