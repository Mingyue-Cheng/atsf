# Agentic Time Series Forecasting

**Position: Beyond Model-Centric Prediction — Agentic Time Series Forecasting**

[![arXiv](https://img.shields.io/badge/arXiv-2602.01776-b31b1b.svg)](https://arxiv.org/abs/2602.01776)
[![Project Page](https://img.shields.io/badge/Project-Page-blue)](https://mingyue-cheng.github.io/atsf/)

## Overview

Conventional time series forecasting frames prediction as a **model-centric, static, single-pass problem** — fit a model, run inference, report metrics. This framing is fundamentally inadequate for the complexity and adaptivity demanded by real-world deployments.

This position paper argues for a paradigm shift toward **Agentic Time Series Forecasting (ATSF)**: organizing forecasting as an iterative agentic workflow where systems *perceive* context, *plan* strategies, *act* through tools, *reflect* on outcomes, and *remember* experience — evolving continuously rather than remaining frozen after training.

## Framework

ATSF is built around five interconnected cognitive components:

| Component | Role |
|-----------|------|
| **Perception** | Adaptive extraction of task-relevant signals from raw, noisy inputs |
| **Planning** | Dynamic decomposition of forecasting objectives; revised as new information arrives |
| **Action** | Autonomous tool interaction; forecasting is one action among a broader action space |
| **Reflection** | Iterative self-evaluation and prediction revision without external supervision |
| **Memory** | Hierarchical accumulation of patterns, strategies, and failure cases across instances |

## Implementation Paradigms

We propose three concrete paradigms spanning the interpretability–adaptability spectrum:

- **Workflow-Based Design** — Structured cognitive pipelines (DAGs / SOPs); high interpretability and stability
- **Agentic Reinforcement Learning (AgenticRL)** — RL applied to the decisions *surrounding* forecasting; enables autonomous strategy discovery
- **Hybrid Agentic Workflow (AgentFlow)** — Workflow structure with localized RL at decision points; balances stability with adaptability

## Authors

[Mingyue Cheng](https://mingyue-cheng.github.io/), Xiaoyu Tao, Qi Liu, Ze Guo, Enhong Chen

University of Science and Technology of China

## Related Work

A curated list of papers on agentic time series forecasting, maintained alongside this position paper.

| Paper | Authors | Venue | Links |
|-------|---------|-------|-------|
| **Cast-R1**: Learning Tool-Augmented Sequential Decision Policies for Time Series Forecasting | Xiaoyu Tao, **Mingyue Cheng**, et al. | arXiv Feb 2026 | [arXiv](https://arxiv.org/abs/2602.13802) · [Code](https://github.com/Xiaoyu-Tao/Cast-R1-TS) |
| **CastMind**: An Interaction-Driven Agentic Reasoning Framework for Cognition-Inspired Time Series Forecasting | Xiaohan Zhang, **Mingyue Cheng**, et al. | arXiv Nov 2025 | [arXiv](https://arxiv.org/abs/2511.08947) |

## Citation

```bibtex
@article{cheng2026atsf,
  title   = {Position: Beyond Model-Centric Prediction -- Agentic Time Series Forecasting},
  author  = {Cheng, Mingyue and Tao, Xiaoyu and Liu, Qi and Guo, Ze and Chen, Enhong},
  journal = {arXiv preprint arXiv:2602.01776},
  year    = {2026}
}
```
