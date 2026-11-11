---
layout: about
title: About
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

<section class="hero">
  <p class="hero-kicker">// Hi, I'm Chaomeng</p>
  <p class="hero-title">AI for Finding Vulnerabilities in Real&#8209;World Code<span class="cursor" aria-hidden="true">_</span></p>
  <div class="hero-pills">
    <a class="pill" href="{{ '/cv/' | relative_url }}"><i class="ai ai-cv"></i> CV</a>
    <a class="pill" href="{{ '/publications/' | relative_url }}"><i class="fa-solid fa-book-open"></i> Publications</a>
    <a class="pill" href="https://scholar.google.com/citations?user={{ site.data.socials.scholar_userid }}"><i class="ai ai-google-scholar"></i> Google Scholar</a>
    <a class="pill" href="https://github.com/{{ site.data.socials.github_username }}"><i class="fa-brands fa-github"></i> GitHub</a>
    <a class="pill pill-outline" href="mailto:{{ site.data.socials.email }}"><i class="fa-solid fa-envelope"></i> Get in touch</a>
  </div>
</section>

I am a PhD researcher in Computer Science at **KU Leuven** ([DistriNet](https://distrinet.cs.kuleuven.be/)). My research focuses on **AI-driven software security**, in particular **automated vulnerability detection in C/C++ source code** using pre-trained code models, contrastive learning, and large language models (LLMs). My work spans the full research pipeline:

<section class="features">
  <div class="feature">
    <i class="fa-solid fa-database feature-icon" aria-hidden="true"></i>
    <h3><span class="accent">Build</span> Vulnerability Data</h3>
    <ul>
      <li>Real-world CVEs and fix commits from 800+ GitHub repositories</li>
      <li>SZZ-traced vulnerability-contributing commits</li>
      <li><a href="https://github.com/Chaomeng-Lu/ICVul">ICVul</a>, MSR 2025</li>
    </ul>
  </div>
  <div class="feature">
    <i class="fa-solid fa-microchip feature-icon" aria-hidden="true"></i>
    <h3><span class="accent">Design</span> Detection Models</h3>
    <ul>
      <li>Capture the subtle differences between vulnerable and patched code</li>
      <li>Supervised contrastive learning on pre-trained code models</li>
      <li><a href="https://github.com/Chaomeng-Lu/PatchCon">PatchCon</a>, preprint 2026</li>
    </ul>
  </div>
  <div class="feature">
    <i class="fa-solid fa-flask feature-icon" aria-hidden="true"></i>
    <h3><span class="accent">Evaluate</span> in the Real World</h3>
    <ul>
      <li>Deep learning models and open-weight LLMs</li>
      <li>Newly disclosed Linux kernel and Chromium vulnerabilities</li>
      <li><a href="{{ '/projects/3_lab_to_reality/' | relative_url }}">From Lab to Reality</a>, JSS 2026</li>
    </ul>
  </div>
</section>

I have published as first author in the _Journal of Systems and Software_, IEEE/ACM _MSR_, and the _IEEE Internet of Things Journal_, and I serve on the program committee of the MSR Data and Tool Showcase Track. Before my PhD, I received an M.Sc. in Cyberspace Security, where I worked on meta-learning for few-shot network intrusion detection.

**I am open to research and engineering roles** in AI, software engineering, and cybersecurity, especially where research methods need to become reliable, production-ready solutions. Feel free to [get in touch](mailto:chaomeng.lu@outlook.com) or take a look at my [CV](/cv/).

<div class="values" markdown="1">
<p class="values-label">What I Value</p>

I am a humanist at heart. I believe every person is many things at once, and that no single metric, ranking, or comparison can measure what someone is worth. I value freedom, openness, and inclusion, and I would rather a community make room for different people and paths than optimize everyone toward the same narrow idea of usefulness.

</div>
