# TesCoder — ML Systems & Generative AI Engineering

I build machine learning systems that focus on **experimentation, validation, and reliable deployment**, with a growing focus on **generative AI and visual generation pipelines**.

My work spans:
- Generative AI workflows (diffusion, ComfyUI, image/video pipelines)
- Multi-agent and LLM systems with guardrails and validation
- Backend infrastructure for deploying and evaluating ML systems at scale

Every project here is designed to:
- Run end-to-end (copy/paste quickstart)
- Make constraints explicit (validation + guardrails)
- Include deterministic checks where possible (tests/CI/scripts)
- Support reproducible experimentation and debugging

### Selected Focus Areas

- **Generative AI & Visual Systems**
  - Diffusion pipelines (ComfyUI, AnimateDiff)
  - Image-to-video generation and temporal consistency
  - Parameter tuning, prompt engineering, and output evaluation

- **ML Systems & Experimentation**
  - Reproducible pipelines and evaluation frameworks
  - Failure case analysis and validation layers
  - Multi-stage model workflows

- **Production AI Systems**
  - LLM orchestration with guardrails
  - Backend systems for reliable model deployment
  - CI-backed validation and monitoring
  
### Projects

- **AI Agent Collaboration Framework** — coordinates multi-agent workflows for structured experimentation, validation, and reliable execution of complex AI systems.  
  Repo: https://github.com/tescoder/ai-agent-collab-framework  
  Highlights: explicit authorization + verification steps (Work Packets), evidence-backed closure (append-only inbox + approval ledger), deterministic packet linter + one-command verification (`bash run.sh`), built for teams coordinating parallel AI sessions within a single initiative.  
  Live docs (GitHub Pages): https://tescoder.github.io/ai-agent-collab-framework/

- **AI-Enhanced Portfolio Optimization Platform** — FastAPI + CVXPY portfolio engine with explainable outputs and a Next.js dashboard.  
  Repo: https://github.com/tescoder/ai-enhanced-portfolio-optimization-platform  
  Highlights: Markowitz (`/optimize`) with constraints, `/efficient_frontier`, Black–Litterman views, regime-aware tilt, stress testing, deterministic explanation payload, and a local Stooq ETF dataset (12 symbols) for reproducible runs; planned: CVaR objective, stronger regime models, backtesting, caching/CI polish, bring-your-own CSV upload.  
  Live docs (GitHub Pages): https://tescoder.github.io/ai-enhanced-portfolio-optimization-platform/  
  Note: Pages will host quick references for the mathematical and research background powering this platform; an interactive optimizer would need a separate deployed API/UI “Live demo” link.

- **LLM-to-SQL Enterprise Query Assistant** — plain-English questions to SQL-backed answers, with transparency and safety controls.  
  Repo: https://github.com/tescoder/llm-to-sql-enterprise-query-assistant  
  Highlights: read-only enforcement (SELECT-only + keyword blocking), multi-statement blocking, default result cap (`LIMIT 200`), server-side validation of generated SQL, one-shot repair retry on execution errors, CI checks (`black --check`, `pytest`, Docker build).  
  Live docs (GitHub Pages): https://tescoder.github.io/llm-to-sql-enterprise-query-assistant/

- **Generative Image & Video Workflows (ComfyUI + AnimateDiff)** — node-based pipelines for controlled image and video generation (in progress)
  Highlights: diffusion-based workflows, LoRA-controlled motion (pan/zoom), temporal consistency tuning, failure analysis (artifact reduction, stability improvements)

- **Arcades** — SwiftUI iOS mini-arcade with a clean app shell, shared state, and production-style build checks.  
  Repo: https://github.com/tescoder/arcades  
  Highlights: shared application state across views with explicit lifecycle management, timer-driven gameplay states, gesture handling (tap/drag/pinch), offline-first (no backend), CI builds via `xcodebuild`; screenshots in README: https://github.com/tescoder/arcades#screenshots

- **Low-Rank Image Compression via SVD** — deterministic CLI that generates shareable error/energy curves and rank-\(k\) panels from built-in datasets.  
  Repo: https://github.com/TesCoder/Low-Rank-Image-Compression-via-SVD  
  Highlights: offline synthetic dataset option, validated CLI args, reproducible PNG artifacts, importable helpers, `pytest` tests + CI.

- **IR** — Next.js form signing + contact workflows with serverless PDF generation.  
  Repo: https://github.com/tescoder/IR  
  Highlights: Next.js UI deployed on Netlify, Google Cloud Function generates signed PDFs from submitted form content, environment-driven configuration and integrations.

### Contact

- GitHub: https://github.com/tescoder
- Resume: https://app.box.com/s/yr3bkoe1auaf75oehrutol9dnjmy612m