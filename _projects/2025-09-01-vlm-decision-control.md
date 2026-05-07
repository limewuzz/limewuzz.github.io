---
title: "VLM Decision Control Engine"
collection: projects
category: work
permalink: /project/vlm-decision-control
excerpt: 'Transforming video description tools into decision-control engines for robotics, with action space alignment and streaming inference data construction.'
date: 2025-09-01
venue: ""
authors: "limewuzz"
projecturl: ""
---

## Overview

Project description goes here.

## Key Contributions

### 1. Action Space Alignment
- Fully disassembled **Qwen2-VL** inference pipeline, identifying the **vocabulary layer** as the critical modification point
- Replaced `vocab.json` with customized version, constraining output space from general text tokens to **robot atomic instruction sets** (N action classes)
- Solved the uncontrollable output format problem of general VLMs in execution scenarios

### 2. Streaming Inference Data Construction
- Referenced **LiveCC** real-time captioning paradigm to build timestamped video-action alignment datasets
- Each sample contains a complete chain: "video frame → reasoning chain → target action"
- Enabled the model with **"reason first, then decide"** capability

## Impact
- Add your project impact here
