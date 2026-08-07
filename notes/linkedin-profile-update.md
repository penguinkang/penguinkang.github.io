# LinkedIn Profile Update — Draft

Chrome connector isn't reachable yet (extension install/sign-in still settling), so here's the full draft to paste in now. Once Chrome connects, tell me to retry and I'll apply this live instead.

Sourced from your 2026-07-31/08-01 resume pass (`career-history-intuit.md`) — de-jargoned for an external audience the same way you had the resume itself retargeted (no VEP/AIEP/ASTAR/MXS internal acronyms), targeting Principal AI Scientist / MLE-level exposure.

---

## Headline (220 char limit)

```
Principal AI Scientist @ Intuit | LLM Fine-Tuning, Speech & Multimodal Models | Production ML Infra | 16 Patents Filed
```

Alternate, more outcome-led version:

```
AI Scientist building production LLM/speech systems at Intuit — model fine-tuning, agentic infra, 16 patents filed
```

---

## About

```
AI scientist and architect with 8+ years building production machine learning systems, most recently focused on efficient fine-tuning, speech/multimodal models, and the infrastructure that gets them into real products.

Recent highlights:
• Designed a lightweight speech-intent classifier that fuses frozen audio and text encoders through a compact 4.5M-parameter model, reaching production-grade accuracy (macro F1 0.746) at roughly 1,000x fewer parameters than a comparable large multimodal LLM pipeline, with sub-100ms latency.
• Fine-tuned a small language model to replace an upstream large-model API call for a memory/topic-extraction pipeline, hitting 97% output-format compliance and cutting p95 latency 8x through model merging and constrained decoding.
• Built a real-time coaching-turn generation model (fine-tuned Llama-3.2-3B, LoRA) deployed to production with strict latency and quality gates.
• Led the production ML infrastructure (container recipes, distributed training/eval orchestration, secure credential management across cloud ML platforms) underpinning multiple fine-tuning and inference workloads.
• Shipped a chat knowledge-base recommender that ran in production for 5+ quarters with a measurable handle-time and satisfaction impact.
• 16 US patent applications filed, 5 granted, spanning conversational AI and real-time guidance systems.

Earlier in my career I built NLP/QA and abandonment-prediction models still in production use, and I hold a PhD focused on human-computer interaction and applied AI.

Always happy to connect with people working on efficient model fine-tuning, speech/multimodal systems, or applied ML infrastructure.
```

(~1,750 characters — LinkedIn's About limit is 2,600, so there's room if you want to add anything personal.)

---

## Experience — Intuit entry (bullets to replace/merge into your current one)

```
• Design and ship efficient fine-tuned models (speech-intent, memory/topic-extraction, coaching-turn generation) that replace large general-purpose model calls with small, fast, production-grade alternatives — cutting latency 4–8x and parameter count by up to 1,000x while holding or improving quality.
• Own the production ML infrastructure for model training and evaluation: container recipe management, distributed orchestration across cloud ML platforms, and secure credential handling — supporting a portfolio of concurrent fine-tuning and inference workloads.
• Built and shipped a real-time chat knowledge-base recommendation feature to production, sustained over 5+ quarters with a quantified handle-time and satisfaction business case.
• Developed a model self-confidence scorer (linear probe) that automates production quality-gating in place of manual LLM-judge review, reaching 0.80 Pearson / 0.88 AUROC agreement.
• Filed 16 US patent applications (5 granted) covering conversational AI and real-time guidance/deduplication systems.
• Earlier: built query-understanding and customer-abandonment prediction models (improving token coverage 87%→94% over baseline) that shipped into production support tooling.
```

---

## Skills (add/reorder to top of Skills section)

```
LLM Fine-Tuning
Speech & Multimodal Models
Model Distillation
Production ML Infrastructure
Applied Research
Conversational AI
Natural Language Processing
PyTorch
Machine Learning Operations (MLOps)
Distributed Training
Applied AI Research
```

---

## Notes / things to double check before posting

- The itemized patent list still has a few grant statuses unreconciled to the 16-filed/5-granted aggregate per your 2026-08-01 note — the About/Experience text above uses the aggregate figure only, which is safe to post as-is.
- I intentionally left out internal codenames (VEP, AIEP, ECMS, VEPAGE, MSLM, etc.) and Jira/doc IDs — none of that belongs on a public profile.
- If you have distinct role titles/dates already on LinkedIn (e.g., separate entries for promotions), let me know how you want the bullets split across them — right now this is written as one continuous block.
