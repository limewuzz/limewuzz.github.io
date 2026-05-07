---
title: "Generative Recommender System"
collection: projects
category: competition
permalink: /project/generative-recommender
excerpt: 'Tencent Advertising Algorithm Competition Top 15% with InfoNCE + Triplet Loss for ad click prediction.'
date: 2025-08-01
venue: "Tencent Advertising Algorithm Competition"
authors: "limewuzz"
---

## Results

| Metric | Score | Improvement |
|--------|-------|-------------|
| HitRate@10 | **0.120475** | +20% vs Baseline |
| NDCG@10 | **0.063665** | +20% vs Baseline |

- **Rank: Top 15%** in Tencent Advertising Algorithm Competition

## Technical Innovation

- Combined **InfoNCE Loss** and **Triplet Loss** to learn differences
- Used independent module to train user preference for clicking exposed samples
- Generative approach for advertising click prediction
