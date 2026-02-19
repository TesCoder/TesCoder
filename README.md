# TesCoder — AI Systems & Backend Engineering

I build AI-enabled systems that prioritize safety, validation, and operational reliability.

I focus on multi-agent orchestration, guarded LLM workflows, and backend infrastructure that translates AI capabilities into reliable, production-grade systems.

Every project here is designed to:
- Run end-to-end (copy/paste quickstart)
- Make constraints explicit (validation + guardrails)
- Include deterministic checks where possible (tests/CI/scripts)
- Stay honest about system boundaries

### Projects

- **Agent Collaboration Framework** — coordinates multi-agent workflows with scoped Work Packets, checkpoints, and CI validation to prevent silent failures.  
  Repo: https://github.com/tescoder/ai-agent-collab-framework  
  Highlights: explicit authorization + verification steps (Work Packets), evidence-backed closure (append-only inbox + approval ledger), deterministic packet linter + one-command verification (`bash run.sh`), built for teams coordinating parallel AI sessions within a single initiative.  
  Live docs (GitHub Pages): https://tescoder.github.io/ai-agent-collab-framework/

- **LLM-to-SQL Enterprise Query Assistant** — plain-English questions to SQL-backed answers, with transparency and safety controls.  
  Repo: https://github.com/tescoder/llm-to-sql-enterprise-query-assistant  
  Highlights: read-only enforcement (SELECT-only + keyword blocking), multi-statement blocking, default result cap (`LIMIT 200`), server-side validation of generated SQL, one-shot repair retry on execution errors, CI checks (`black --check`, `pytest`, Docker build).

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