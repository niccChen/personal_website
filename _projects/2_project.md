---
layout: page
title: Counterfactual MLLM Benchmark
description: Evaluating multimodal LLM robustness to misleading chart encodings
importance: 2
category: research
---

**Jan 2026 – Present**

Addressed a key evaluation gap in multimodal chart understanding — prior benchmarks could show that models fail on charts, but not whether errors came from the visual encoding or the underlying data/task.

- Built a counterfactual benchmark generating 400 paired instances across 5 tasks, 5 deception types, and 3 chart families
- Designed metrics: Deception Gap, Flip Rate, Repair Consistency
- Evaluated **GPT-4o, Claude 3.5 Sonnet, Gemini 2.0 Flash**, and a chart-to-table baseline
- Found misleading encodings caused substantial conclusion instability; ground-truth table access did not fully eliminate the problem

**Tools:** Python, GPT-4o API, Claude API, Gemini API
