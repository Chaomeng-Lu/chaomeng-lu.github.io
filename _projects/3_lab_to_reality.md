---
layout: page
title: From Lab to Reality
description: A practical evaluation of deep learning models and LLMs for vulnerability detection.
img: assets/img/projects/lab_to_reality.png
importance: 3
category: research
github: https://github.com/Chaomeng-Lu/A-Practical-Evaluation-of-Deep-Learning-Models-and-LLMs-for-Vulnerability-Detection
related_publications: true
---

How well do vulnerability detectors that score highly on benchmarks work in practice? This project is a deployment-oriented evaluation of deep learning models and open-weight LLMs for source-code vulnerability detection.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/lab_to_reality.png" title="From Lab to Reality" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Evaluation design: representation analysis, benchmark evaluation, and deployment evaluation on VentiVul.
</div>

- Compares models across multiple benchmark datasets under a common, reproducible setup.
- Tests real-world effectiveness on **recently disclosed Linux kernel and Chromium vulnerabilities**.

Accepted in the _Journal of Systems and Software_ (JSS), 2026.

[Code on GitHub](https://github.com/Chaomeng-Lu/A-Practical-Evaluation-of-Deep-Learning-Models-and-LLMs-for-Vulnerability-Detection) · [Paper (arXiv)](https://arxiv.org/abs/2512.10485)

{% cite lu2026labtoreality %}
