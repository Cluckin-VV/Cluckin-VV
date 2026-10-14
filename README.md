# Hi, I'm Shaokai Cheng (程少楷)

Undergraduate in Intelligent Transportation at North China University of Technology, building auditable AI applications and data products.

求职方向：**AI 应用开发 / AI 技术产品 / 数据智能**  
GitHub: [Cluckin-VV](https://github.com/Cluckin-VV) · Kaggle: [cluckinvv](https://www.kaggle.com/cluckinvv)

## Featured work

### [EqualOcean Internship Portfolio — Operations Agent, ChinaList and AI Weekly Workflow](https://github.com/Cluckin-VV/EqualOcean)

Sanitized case studies from an AI Agent and data-product internship. The featured project is an evidence-linked operations-agent POC with explicit states, customer isolation, selective memory, quality gates and human approval.

- current local Operations Agent core POC verified with **62 automated regression tests**
- ChinaList authenticated subscription experience: **14 unit tests + typecheck + lint + production build**
- AI weekly-report refactor: task identity, node retries, input hashes, audit gates and evaluation archives
- employer code, credentials, customer data, internal endpoints and production screenshots are not redistributed

### [TransitLab — Guardrailed AI Traffic World Builder](https://github.com/Cluckin-VV/AI-builderkack-traffic-lab)

A controllable 3D traffic-world builder with preview, confirmation, execution, undo, schema validation, semantic validation and an event log.

- Python + JavaScript + Three.js
- 4 weather modes and 3 vehicle types
- **311 Python tests + 48 JavaScript tests**
- [Public demo](https://ai-builderkack-traffic-lab.onrender.com)

### Kaggle agent and model evaluation

- [Pokémon TCG AI Battle](https://github.com/Cluckin-VV/kaggle-pokemon-agent): replay-driven policy iteration; best observed public score **919.9**, explicitly treated as volatile rather than a stable estimate
- [AI Agent Security: Multi-Step Tool Attacks](https://github.com/Cluckin-VV/kaggle-agent-security-case-study): 13 local mechanism tests, 18 replay candidates; best observed public score **88.785**; exploit payloads withheld
- [Biohub Cell Tracking case study](case-studies/biohub-cell-tracking.md): public-source reproduction, fusion and model-member comparisons, and trajectory auditing; [Kaggle results](https://www.kaggle.com/cluckinvv)

### [Backend Reliability Labs](https://github.com/Cluckin-VV/backend-reliability-labs)

Three FastAPI/PostgreSQL experiments covering request idempotency, transaction rollback, retryable relay, stable event identity and consumer deduplication.

- in-memory idempotency: **17 tests**
- PostgreSQL idempotency: **19 tests**
- transactional outbox: **21 tests**

### [Da Youhui — Student Discount Discovery and Review](https://github.com/Cluckin-VV/da-youhui)

A sanitized, mobile-first Next.js/PostgreSQL project for collecting, reviewing, publishing and maintaining student discounts.

- evidence and expiry-aware review workflow
- web application + WeChat Mini Program client
- **17 automated tests**; production build verified locally

### [Metro Card Ridership Forecast](https://github.com/Cluckin-VV/metro-card-ridership-forecast)

A reproducible transport-data project covering chronological forecasting, high-demand classification, day-type clustering and failure-case analysis.

- regression: MAPE **7.9564%**, R² **0.8944**
- classification: F1 **0.9149**, ROC-AUC **0.9650**
- **18 automated tests**

### [Python LRU Cache](https://github.com/Cluckin-VV/python-lru-cache)

An exact LRU cache implemented with a hash map and doubly linked list.

- O(1) average-time core get/put operations
- **18 tests** covering eviction, recency, sentinels and structural invariants

## Skills

- **AI applications:** Python, structured outputs, context/memory, source validation, quality gates, human review
- **Data/backend:** SQL, SQLite, PostgreSQL, REST APIs, JSON/JSONL
- **Frontend:** JavaScript, TypeScript, React/Next.js, Three.js
- **Engineering:** Git/GitHub, automated tests, technical documentation, reproducible evaluation
- **Domain:** intelligent transportation, GIS, traffic simulation and IoT scenarios

## Working principles

I prefer systems that are testable, reversible and auditable. I separate model suggestions from business decisions, keep evidence for important claims and state verification boundaries explicitly.

