---
layout: page
title: ICVul
description: A well-labeled C/C++ vulnerability dataset with comprehensive metadata and vulnerability-contributing commits.
img: assets/img/projects/icvul.png
importance: 2
category: research
github: https://github.com/Chaomeng-Lu/ICVul
related_publications: true
---

ICVul is a C/C++ vulnerability dataset built from real-world CVEs and their GitHub fix commits across **800+ repositories**.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/icvul.png" title="ICVul" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  The ICVul construction framework, from CVE extraction to the five linked dataset tables.
</div>

- Function-, file-, and commit-level metadata for each vulnerability.
- **Vulnerability-Contributing Commits (VCCs)** traced with the SZZ algorithm, linking each fix back to the change that introduced the bug.
- Designed as a clean, reproducible basis for training and evaluating deep learning and LLM-based vulnerability detectors.

Published at the IEEE/ACM 22nd International Conference on Mining Software Repositories (MSR 2025).

[Dataset and code on GitHub](https://github.com/Chaomeng-Lu/ICVul) · [Paper (arXiv)](https://arxiv.org/abs/2505.08503)

{% cite lu2025icvul %}
