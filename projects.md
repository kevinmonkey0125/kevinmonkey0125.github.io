---
layout: page
title: Projects
subtitle: Selected work in manufacturing analytics, data engineering, and RAG
---

## Manufacturing Analytics (FPY / OTD)

### OTD Weekly Tracker & Risk Monitoring
- Built a tracking workflow to monitor weekly OTD risk across WOs and buffers.
- Automated reporting + escalation signals for high-risk WOs.
- Tools: BigQuery SQL, Python, Power BI

### FPY Improvement / Failure Pareto
- Failure pattern analysis by station/test_step/symptom.
- Root-cause insights to prioritize rework actions and reduce repeat fails.
- Tools: BigQuery SQL, Python

---

## RAG Repair Recommendation (Internal Tooling)

### Evidence → Actionable Repair Plan (RAG)
- Retrieved similar historical rework cases and generated verification-driven repair steps.
- Ranked actions by support count and success rate to reduce trial-and-error.
- Tools: Python, embeddings/vector search, LLM (Ollama)

### Future: Debug Log Integration
- Plan to ingest large-scale debug logs and link to symptom_label/message for finer retrieval.

---

## Data Engineering

### Automated Data Pipeline (BigQuery + Python)
- ETL scripts + scheduled queries to standardize KPIs and keep dashboards consistent.
- Focused on reliability, refresh automation, and traceability.
