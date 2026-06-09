---
layout: page
title: About
subtitle: "Building the model and the instrument that measures it"
---

I am an ML / Research Engineer working on LLM post-training, evaluation, and reinforcement learning. What ties my work together is a single question I have been chasing since my PhD: how do you get a learning system to improve in a way you can actually measure and trust?

## Training and evaluation as one loop

At Postman I own both halves of that loop. I build multi-phase post-training pipelines (SFT, DPO, RLVR with GRPO, and RFT) on large-scale GPU infrastructure, and I design the agent evaluation benchmarks that decide whether a change actually helped. I treat a benchmark as an instrument: deterministic validators, anti-contamination, bootstrap-CI scoring, and multi-trial averaging, rebuilt into harder task suites when frontier models saturate them. I also work on separating real capability from safety-driven refusal, so a model is not judged weaker than it is just because it abstains.

## Reinforcement learning, from games to LLMs

Reinforcement learning is the throughline. My CS PhD at Virginia Tech (Outstanding PhD Research Award, 2025) used game-theoretic and deep RL methods for cyber-defense, including defensive deception against advanced persistent threats and a decision-theory-guided framework that cut the cold-start cost of deep RL. Reward design, environment design, and the careful study of what a policy is really learning are the same problems whether the agent is defending a network or solving an API task.

## Knowing what you do not know

A second thread is uncertainty. I built uncertainty-aware human-AI teaming systems using Vision Transformers and Evidential Deep Learning, and co-authored a survey bridging Dempster-Shafer theory, subjective logic, and neural-network uncertainty quantification (Information Fusion). Calibrated uncertainty is exactly what you need when you separate a model's real capability from its safety-driven refusals.

## Now

I am a Senior AI Software Engineer at Postman, where I am the DRI for model training and evaluation. Earlier I shipped production ML systems at Bobyard. The throughline is the same: build the thing that learns, and build the instrument that tells you the truth about it.
