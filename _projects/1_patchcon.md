---
layout: page
title: PatchCon
description: Patch-aware weighted supervised contrastive learning for vulnerability detection.
img: assets/img/projects/patchcon.png
importance: 1
category: research
github: https://github.com/Chaomeng-Lu/PatchCon
related_publications: true
---

PatchCon is a CodeBERT-based vulnerability detector that jointly optimizes vulnerability classification and supervised contrastive learning. It treats each vulnerable function and its patched version as a **weighted hard-negative pair**, so the model learns the small, fix-related differences that separate vulnerable code from safe code.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/patchcon.png" title="PatchCon" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Overview of the PatchCon framework: pair construction, pair input encoding, training objectives, and evaluation.
</div>

- On **PairVul-Linux**, PatchCon improves pairwise accuracy over the strongest reproduced baseline from **0.21 to 0.33 (+58%)**.
- It matches a GPT-4o-based LLM method at a substantially lower cost.
- It generalizes best to unseen CVEs and to newly disclosed Linux kernel vulnerabilities.

**Stack:** Python, PyTorch, Hugging Face Transformers, CodeBERT, HPC.

[Code on GitHub](https://github.com/Chaomeng-Lu/PatchCon) · [Paper (arXiv)](https://arxiv.org/abs/2611.06583)

{% cite lu2026patchcon %}
