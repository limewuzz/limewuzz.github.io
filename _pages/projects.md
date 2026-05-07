---
permalink: /projects/
title: "Projects"
author_profile: true
---

## VLM Decision Control Engine | Skyris
**2025.09 – Present** | VLM Algorithm Engineer  
*Project completed Series A funding of ¥10M (Xiaohongshu investment)*

Participated in building VLM from 0 to 1, responsible for transforming video description tools into decision-control engines (a core component of the decision system).

### Key Contributions

**1. Action Space Alignment**
- Fully disassembled Qwen2-VL inference pipeline, identifying the vocabulary layer as the critical modification point
- Replaced `vocab.json` with customized version, constraining output space from general text tokens to robot atomic instruction sets (N action classes)
- Solved the uncontrollable output format problem of general VLMs in execution scenarios

**2. Streaming Inference Data Construction**
- Referenced LiveCC real-time captioning paradigm to build timestamped video-action alignment datasets
- Each sample contains a complete chain: "video frame → reasoning chain → target action"
- Enabled the model with "reason first, then decide" capability

---

## Metro Intelligent Q&A System | Jiatu Technology
**2025.06 – 2025.09** | LLM Algorithm Intern  
*Rail Transit Unicorn Company*

### Metro Intelligent Q&A (Qwen2.5-32B)
- Improved accuracy from **73% → 95%**
- Designed error-sample scoring and filtering mechanism to construct Function Call data, solving incorrect invocation patterns caused by annotation noise
- SFT single-round alignment + PPO multi-round capability (Acc=90%), solving multi-round query intent drift issues

### Agent (Zhipu Qingyan Collaboration)
- Built Q&A + Text2SQL dual-link architecture, solving the pain point of non-technical users unable to query databases
- Text2SQL based on Qwen2.5-7B-Coder-Instruct with preference alignment without SFT
- Used Qwen-0.5B to sample 150K reject SQLs, filtered 10K preference pairs
- Adopted GRPO (execution correctness + format compliance dual rewards) to replace DPO, solving loss oscillation and output instability, **Acc +12%**

---

## Generative Recommender System | Tencent Advertising Algorithm Competition
**2025.08 – 2025.09** | Top 15%

**Core Results:**
- Ad click prediction HitRate@10: **0.120475**
- NDCG@10: **0.063665**
- **20% improvement** over baseline

**Technical Innovation:**
- Combined InfoNCE Loss and Triplet Loss to learn differences
- Used independent module to train user preference for clicking exposed samples

---

## SynDoc-R: Synthetic Document OCR Data Pipeline
**2025.05 – 2025.08** | Tsinghua University Collaboration (Co-first Author)

Designed a leakage-free document OCR data synthesis pipeline:
1. **Data Generation**: Expanded Wikipedia seeds via LLM, fused LaTeX tables to generate Markdown documents
2. **Rendering**: TeX Live + PyMuPDF rendering engine
3. **Degradation**: Augraphy for realistic noise (illumination, creases, ink blots)
4. **Correction**: LLM error-correction paradigm for post-hoc OCR rectification

**Solved:** Public corpus data leakage, synthetic data lacking realistic noise, long-tail OCR errors
