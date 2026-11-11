---
layout: about
title: about
permalink: /
subtitle: PhD Researcher in Computer Science at <a href='https://distrinet.cs.kuleuven.be/'>DistriNet</a>, <a href='https://www.kuleuven.be/'>KU Leuven</a>

profile:
  align: right
  image: prof_pic_color.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>DistriNet, Department of Computer Science</p>
    <p>KU Leuven</p>
    <p>Leuven, Belgium</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

I am a PhD researcher in Computer Science at **KU Leuven** ([DistriNet](https://distrinet.cs.kuleuven.be/)). My research focuses on **AI-driven software security**, in particular **automated vulnerability detection in C/C++ source code** using pre-trained code models, contrastive learning, and large language models (LLMs).

My work spans the full research pipeline:

- **Vulnerability data.** I build well-labeled vulnerability datasets from real-world CVEs and fix commits across 800+ GitHub repositories, including SZZ-traced vulnerability-contributing commits ([ICVul](https://github.com/Chaomeng-Lu/ICVul), MSR 2025).
- **Models.** I design detection models that capture the subtle differences between vulnerable and patched code, such as [PatchCon](https://github.com/Chaomeng-Lu/PatchCon), a patch-aware supervised contrastive learning approach.
- **Realistic evaluation.** I study how deep learning models and open-weight LLMs perform outside the lab, on newly disclosed Linux kernel and Chromium vulnerabilities (JSS 2026).

I have published as first author in the _Journal of Systems and Software_, IEEE/ACM _MSR_, and the _IEEE Internet of Things Journal_, and I serve on the program committee of the MSR Data and Tool Showcase Track. Before my PhD, I received an M.Sc. in Cyberspace Security, where I worked on meta-learning for few-shot network intrusion detection.

**I am open to research and engineering roles** in AI, software engineering, and cybersecurity, especially where research methods need to become reliable, production-ready solutions. Feel free to [get in touch](mailto:chaomeng.lu@outlook.com) or take a look at my [CV](/cv/).

<div class="values" markdown="1">
<p class="values-label">What I value</p>

I am a humanist at heart. I believe every person is many things at once, and that no single metric, ranking, or comparison can measure what someone is worth. I value freedom, openness, and inclusion, and I would rather a community make room for different people and paths than optimize everyone toward the same narrow idea of usefulness.

I also believe in starting from within: understanding yourself is what makes it possible to see the world, and other people, clearly. In research, this is part of why I care about open work: I release my datasets and code so that others can build on them.

<p class="values-sign"><img class="seal" src="{{ '/assets/img/seal.svg' | relative_url }}" alt="" aria-hidden="true"></p>

</div>
