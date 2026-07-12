# Sovereign SWAT — what is this?
 
A solo project, built in about two to three weeks. Three AI pipelines that run entirely on my own machine — no cloud APIs, no external calls.
 
**Core Components:**
* **Pipeline A (Fresh):** Single-pass reasoning matrix for immediate problem decomposition.
* **Pipeline B (Context-Aware):** Memory-injected reasoning, maintaining logical continuity across sessions.
* **Pipeline C (Maintenance):** Autonomous background memory curation, deduplication, and logical grouping.
**The Engine:** Every inference flow passes through a deterministic 5-Stage Cognitive Matrix (PreValidator → Structural Analyst → Adversarial Critic → PostValidator → Synthesis). Answers are gated by a deterministic Python algorithm, not soft LLM logic — a structural analyst and an adversarial critic check each other before any response gets synthesized.
 
**Why I built it:** to show my own skill and thinking — how efficiently I can get a local, self-hosted model to reason well and stay efficient, without relying on a cloud provider's compute or API.
 
---
 
Full technical writeup — architecture, design decisions, and real execution logs:
* **[ARCHITECTURE.md](ARCHITECTURE.md)** (system design and design decisions)
* **[LOGS.md](LOGS.md)** (real, unedited operational execution traces)
 
