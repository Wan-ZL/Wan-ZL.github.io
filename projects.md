---
layout: page
title: Selected Work
subtitle: "Post-training, evaluation, production ML, and RL research"
---

## LLM post-training and evaluation (Postman)

As a Senior AI Software Engineer at Postman and the DRI for model training and evaluation, I own the full loop of training a model and measuring it.

- **Post-training pipeline.** Built a multi-phase fine-tuning pipeline on large-scale GPU infrastructure covering SFT, DPO, RLVR with GRPO, and reinforcement fine-tuning (RFT), with data-quality filtering and benchmark-driven checkpoint evaluation. Diagnosed and fixed a training collapse caused by catastrophic forgetting, and added safeguards against recurrence.
- **Evaluation benchmark.** Designed an industry-grade evaluation benchmark and environment for frontier LLMs, covering multiple evaluation axes with deterministic validators, bootstrap-CI scoring, anti-contamination controls, and multi-trial averaging. When frontier models saturated the initial tasks, I rebuilt a harder suite that restored a wide discriminative spread for meaningful cross-model comparison.
- **Capability vs refusal.** Found that safety-training-driven abstention was systematically understating true model capability, and introduced an abstention-adjusted metric that separates capability from refusal.
- **Agentic systems.** Designed and deployed a next-generation agentic AI system and dynamic LLM routing strategies for a production enterprise platform.
- **Partnerships.** Primary technical point of contact for AI partnerships and external model-evaluation collaborations.

## Production ML (Bobyard)

- Built and shipped a production VQA and RAG system (FastAPI, PaddleOCR, LightRAG, AWS) over a two-layer knowledge graph with per-project data isolation, serving semantic and relationship search across customer drawing sets.
- Architected a representation-learning and embedding pipeline for 100-megapixel and larger engineering drawings (custom compression and detection models) and the distributed GPU/CPU infrastructure behind it, handling multi-gigabyte batches.
- Earlier, as a computer vision intern, built zero-shot symbol detection and a Segment Anything Model (SAM) based method for detecting long thin lines in construction drawings.

## Reinforcement learning research (Virginia Tech, PhD)

- **Decision-theory-guided deep RL for fast learning.** Built a framework combining decision theory with PPO to mitigate the cold-start problem, achieving up to 184% higher initial reward and 53% more accumulated reward than standard deep RL. Code: <a href="https://github.com/Wan-ZL/DT-DRL" target="_blank">github.com/Wan-ZL/DT-DRL</a>.
- **Honey drones for drone surveillance.** Modeled attacker and defender as A3C deep RL agents competing over signal strength, with parallel training for faster convergence. Code: <a href="https://github.com/Wan-ZL/gym-drones" target="_blank">github.com/Wan-ZL/gym-drones</a>.
- **Defensive deception against advanced persistent threats.** Used hypergame theory and deep RL for defensive deception against APTs (Foureye). The latest work in this line, on cyber deception for mission surveillance via hypergame-theoretic deep RL, was accepted to IEEE TDSC in 2026. Code: <a href="https://github.com/Wan-ZL/ARO-Foureye" target="_blank">github.com/Wan-ZL/ARO-Foureye</a>.
- **Uncertainty-aware human-AI teaming.** Built a Vision Transformer pipeline with Evidential Deep Learning so the model can express uncertainty, across four U.S. Army-funded projects.
