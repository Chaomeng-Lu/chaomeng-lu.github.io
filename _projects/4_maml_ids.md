---
layout: page
title: Few-shot IoT Intrusion Detection
description: Model-agnostic meta-learning for detecting new IoT attack types from a few labeled samples.
img: assets/img/projects/maml_ids.png
importance: 4
category: research
github: https://github.com/Chaomeng-Lu/MAML-CNN-FSIDS-IoT
related_publications: true
---

A few-shot intrusion detection approach for IoT networks based on **model-agnostic meta-learning (MAML)** with a CNN backbone. The model is meta-trained so it can adapt quickly to new attack types when only a handful of labeled samples are available.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/maml_ids.png" title="Few-shot IoT Intrusion Detection" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Structure of the few-shot MAML intrusion detection model, with inner and outer training loops.
</div>

Published in the _IEEE Internet of Things Journal_, vol. 10, no. 24, 2023.

[Code on GitHub](https://github.com/Chaomeng-Lu/MAML-CNN-FSIDS-IoT) · [Paper (DOI)](https://doi.org/10.1109/JIOT.2023.3283408)

{% cite lu2023fewshot %}
