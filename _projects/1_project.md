---
layout: page
title: Clinical Inconsistency Detection
description: Weakly supervised NLP for cross-note inconsistency detection in MIMIC-IV EHR
importance: 1
category: research
---

**Jan 2026 – Present**

Formulated cross-note inconsistency detection in MIMIC-IV as a weakly supervised bag-level evidence learning task, enabling admission-level supervision over latent contradictory evidence across candidate sentence pairs.

- Built an end-to-end clinical NLP pipeline generating a 110K 3-way silver corpus from discharge summaries and radiology reports
- Trained a Transformer-based bag model with temporal, assertion-aware, and structured EHR features
- Achieved **0.936 macro-F1** and **0.949 contradiction F1** on in-distribution test set; **0.945 macro-F1** on temporal OOD split
- Downstream validation showed positive AUROC gain for ICU-stay prediction over structured baseline

**Tools:** Python, PyTorch, Transformers, MIMIC-IV
