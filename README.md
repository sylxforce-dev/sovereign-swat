# Sovereign SWAT — what is this?
 
A solo project, built in about two to three weeks.
 
Three AI pipelines that run entirely on my own machine — no cloud APIs, no external calls.
 
- **Pipeline A** writes fresh answers.
- **Pipeline B** reads and builds on past context.
- **Pipeline C** runs in the background, cleaning up and organizing memory over time.
Every answer passes through a small internal debate first — a structural analyst and an adversarial critic checking each other — before a final response gets synthesized. That final gate is a deterministic check, not another LLM call.
 
**Why I built it:** to show my own skill and thinking — how efficiently I can get a local, self-hosted model to reason well and stay efficient, without relying on a cloud provider's compute or API.
 
---
 
Full technical writeup — architecture, design decisions, and real execution logs — see **[ARCHITECTURE.md](ARCHITECTURE.md)** and **[LOGS.md](LOGS.md)**.
 
