# Hi, I'm Chenhao

Aspiring computer scientist. I build across **quant finance, AI safety, full-stack,
backend/security, and cloud infrastructure**. Below are 14 projects grouped by theme —
each is its own repo with a README, tests, and run instructions.

---

## 📈 Quantitative finance

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Options Pricing Visualizer**](https://github.com/ChenhaoZhang01/options-pricing-visualizer) | Black-Scholes pricing with live, interactive **Greeks** curves and an implied-vol solver | React · D3 · Python · FastAPI |
| [**Order Book Simulator**](https://github.com/ChenhaoZhang01/order-book-simulator) | Live limit order book with a **price-time-priority matching engine**, streamed over WebSockets | Python · FastAPI · WebSockets |
| [**Rental Cash Flow Analyzer**](https://github.com/ChenhaoZhang01/rental-cashflow-analyzer) | Underwrite rentals: cap rate, cash-on-cash, DSCR, amortization, 30-yr projection | Next.js · Chart.js · Prisma |

## AI ethics & safety

| Project | What it does | Stack |
|---------|--------------|-------|
| [**AI Sycophancy Detector**](https://github.com/ChenhaoZhang01/ai-sycophancy-detector) | Scores how **sycophantic** an AI reply is via interpretable NLP signals (+ optional LLM judge) | Python · FastAPI · NLP |
| [**Bias Audit Dashboard**](https://github.com/ChenhaoZhang01/bias-audit-dashboard) | Probe an LLM across demographics; visualize **disparate impact / 80% rule** | Streamlit · Pandas |
| [**Prompt Classifier**](https://github.com/ChenhaoZhang01/prompt-classifier) | Convergent vs. divergent prompts + an **overreliance warning** for high-stakes questions | FastAPI · React |

## Full-stack

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Content Analytics Pipeline**](https://github.com/ChenhaoZhang01/content-analytics-pipeline) | Track content performance and **predict what to post next** with a learned recommender | Next.js · Chart.js · Apify |
| [**Scholarship Matching Engine**](https://github.com/ChenhaoZhang01/scholarship-matching-engine) | Match students to scholarships via eligibility filters + **weighted fit scoring** | Next.js · Supabase · OpenAI |

## Backend & security

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Rate Limiter**](https://github.com/ChenhaoZhang01/rate-limiter) | Fixed-window, sliding-window, and **token-bucket** limiters with in-memory + **Redis (Lua)** backends | Node.js · Redis |
| [**Encrypted File Vault**](https://github.com/ChenhaoZhang01/encrypted-file-vault) | **Zero-knowledge** client-side file encryption (AES-256-GCM + PBKDF2) | Next.js · Web Crypto · S3 |
| [**build-your-own-chatgpt**](https://github.com/ChenhaoZhang01/build-your-own-chatgpt) | Streaming chat UI with a pluggable **OpenAI/Anthropic/mock** provider abstraction | Next.js · Streaming |

## Cloud infrastructure & ML

| Project | What it does | Stack |
|---------|--------------|-------|
| [**K8s GitOps CI/CD**](https://github.com/ChenhaoZhang01/k8s-argocd-cicd) | CI builds images, **Argo CD** syncs the cluster — app-of-apps, dev auto-sync, gated prod | Kubernetes · Argo CD · Kustomize |
| [**Website Operator**](https://github.com/ChenhaoZhang01/website-operator) | A **Kubernetes controller** with a custom `Website` CRD reconciling Deployments + Services | Go · controller-runtime · CRD |
| [**Game RL Agent**](https://github.com/ChenhaoZhang01/game-rl-agent) | Self-play **Q-learning** that learns Tic-Tac-Toe and never loses to random (88% win) | Python · Reinforcement Learning |

---

<sub>Every project has tests and a runnable README. Most run with zero config; where an API key or cloud account adds capability, there's an <code>.env.example</code> and a working offline fallback.</sub>
