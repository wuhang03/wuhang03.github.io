---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
Hi there! My name is Hang Wu (吴杭), you can also call me by my English name Laurent.

I am currently a first-year PhD student at the University of California, Merced, conducting research under the guidance of Prof. [Yiwei Wang](https://wangywust.github.io/), with Prof. [Ming-Hsuan Yang](https://faculty.ucmerced.edu/mhyang/) as my senior advisor. Additionally, I work closely with Prof. [Yujun Cai](https://vanoracai.github.io/). My main research interests are in vision-language models and large multimodal models, with a focus on improving their performance and specific applications. I received my bachelor's degree from Tongji University, where I worked on image processing tasks in the low-level vision field.

You can find my CV here: [Hang Wu's Curriculum Vitae](https://drive.google.com/file/d/1tNOCYlOXXq9uFjwZmn2hUCbU-wdg_udY/view?usp=sharing). If you are interested in my work, please feel free to drop me an email.


# 🎓 Educations
- *2025.08 - Present*,  PhD student, University of California, Merced.
- *2021.09 - 2025.06*,  Undergraduate student, Tongji University.

# 💻 Internships
- *2025.03 - 2025.07*, Research Intern, vivo@Shenzhen, China.
- *2025.01 - 2025.07*, Research Intern, UC Merced NLP Lab@University of California-Merced, Remote.
- *2023.09 - 2025.03*, Research Intern, Ni's Group@Tongji University, Shanghai, China.

# 🔥 News
- *2026.01*: One paper submitted to ICML 2026.
- *2025.09*: Three papers submitted to ICLR 2026.
- *2025.08*: 🎉🎉 Our paper DiMo-GUI has been accepted to EMNLP 2025 Main Conference!
- *2025.08*: Officially join UC Merced NLP Lab and start my PhD journey.
- *2025.05*: Two papers submitted to EMNLP 2025.
- *2025.04*: Thrilled to accept PhD offer from UC Merced. Looking forward to working and living in CA!
- *2025.03*: Join vivo as a Research Intern!
- *2024.11*: One paper submitted to CVPR 2025.



# 📝 Selected Publications 


<!-- CamReasoner -->
<div class='paper-box'>
  <div class='paper-box-image' style="text-align: center;">
    <div>
      <img src='images/camreasoner.png' alt="sym" width="110%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

CamReasoner: Reinforcing Camera Movement Understanding via Structured Spatial Reasoning  [[Paper]()] [[Code](https://github.com/wuhang03/CamReasoner)]

**Hang Wu**, Yujun Cai$^{\dagger}$, Zehao Li, Haonan Ge, Bowen Sun, Junsong Yuan, Yiwei Wang

<strong>Arxiv 2026</strong>
* **Structured Reasoning Paradigm**: We propose the Observation-Thinking-Answer (O-T-A) paradigm, reformulating camera movement understanding from black-box classification into a structured ego-motion inference task that decouples camera trajectories from dynamic scenes.

* **Inference Trajectory Suite:** We construct a Large-scale Inference Trajectory Suite with 18k SFT and 38k RL samples, transforming static labels into dense reasoning chains to instill spatio-temporal cinematic logic into MLLMs.

* **RL-driven Logical Alignment:** We are the **first to employ Reinforcement Learning** for logical alignment in this domain, achieving state-of-the-art 78.4% and 74.5% accuracy in binary classification and visual question answering tasks.
</div>
</div>


<!-- RefineShot -->
<div class='paper-box'>
  <div class='paper-box-image' style="text-align: center;">
    <div>
      <!-- <div class="badge">Arxiv 2025</div> -->
      <img src='images/refineshot.png' alt="sym" width="110%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

RefineShot: Rethinking Cinematography Understanding with Foundational Skill Evaluation [[Paper](https://www.arxiv.org/abs/2510.02423)] [[Code](https://github.com/wuhang03/RefineShot)]

**Hang Wu**, Yujun Cai, Haonan Ge, Hongkai Chen, Ming-Hsuan Yang, Yiwei Wang$^{\dagger}$

<strong>Arxiv 2025</strong>
- Benchmark refinement: Enforces consistent option granularity, unified evaluation dimensions, and mutual exclusivity for greater dataset reliability.
- Baseline analysis: Thoroughly evaluates ShotVL, revealing weaknesses in reasoning, prompt adherence, and output consistency.
- Evaluation expansion: Adds a protocol assessing both task-specific performance and core model competencies, enabling more balanced and robust comparisons.
</div>
</div>


<!-- <div class='paper-box'>
  <div class='paper-box-image' style="text-align: center;">
    <div>
      <div class="badge">Arxiv 2025</div>
      <img src='images/framemind.png' alt="sym" width="110%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1"> -->

<!-- [FrameMind: Frame-Interleaved Video Reasoning via Reinforcement Learning](https://framemind.github.io/) -->


<!-- Haonan Ge, Yiwei Wang, Kai-Wei Chang, **Hang Wu**, Yujun Cai$^{\dagger}$ -->

<!-- <strong>Arxiv 2025</strong>
- We introduce FiCOT, a reasoning paradigm enabling dynamic visual evidence gathering during inference.
- We propose DRFS, a training methodology for learning adaptive sampling policies. We also develop DRFS-GRPO,anefficient reinforcement learning algorithm for training complex perception-reasoning policies from sparse rewards.
</div>
</div> -->


<!-- DiMo-GUI -->
<div class='paper-box'>
  <div class='paper-box-image' style="text-align: center;">
    <div>
      <!-- <div class="badge">Arxiv 2025</div> -->
      <img src='images/DiMo-GUI.jpg' alt="sym" width="60%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

DiMo-GUI: Advancing Test-time Scaling in GUI Grounding via Modality-Aware Visual Reasoning [[Paper](https://arxiv.org/abs/2507.00008)] [[Code](https://github.com/vivo/DiMo-GUI)]

**Hang Wu**, Hongkai Chen$^{\dagger}$, Yujun Cai, Chang Liu, Qingwen Ye, Ming-Hsuan Yang, Yiwei Wang

<strong>EMNLP 2025 Main Conference</strong>
- We propose DiMo-GUI, a training-free framework that can be seamlessly integrated as a plug-and-play component into any GUI agent.
- Without requiring additional training or external data, DiMo-GUI effectively enhances grounding performance across various GUI tasks.
</div>
</div>




<!-- <div class='paper-box'>
  <div class='paper-box-image' style="text-align: center;">
    <div>
      <div class="badge">Arxiv 2025</div>
      <img src='images/structure.png' alt="sym" width="60%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">


[Structured Attention Matters to Multimodal LLMs in Document Understanding](https://www.techrxiv.org/doi/full/10.36227/techrxiv.175086178.86227111/v1)

Chang Liu，Hongkai Chen$^{\dagger}$, Yujun Cai, **Hang Wu**, Qingwen Ye, Ming-Hsuan Yang, Yiwei Wang

<strong>Arxiv 2025</strong>
- Our work investigates a fundamental yet overlooked aspect: how input format influences document comprehension performance.
- We propose a novel structurepreserving approach that encodes document elements using the LATEX paradigm, maintaining the hierarchical organization and spatial relationships critical for comprehension.
</div>
</div> -->


<!-- 
# 🎖 Honors and Awards
- *2022.09* Scholarship for Outstanding Students, Tongji University. -->


<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->


# 📚 Projects 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='../images/project1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Research on Perception-oriented High Dynamic Range Imaging Systems]()

<strong>National-level Innovation Project</strong>
-  We treat artifacts in HDR images as detectable entities, explicitly detect and suppress them to enhance HDR quality.
-  National-level innovation project at Tongji University, with a funding of 10,000 RMB.
</div>
</div>


# 📖 Services
<strong>Conference Reviewer</strong>
- The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2026
- The IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2026


<strong>Teaching</strong>
- CSE 188: Natural Language Processing, Teaching Assistant (Spring 2026, UC Merced).
- CSE-022: Introduction to Programming, Teaching Assistant (Fall 2025, UC Merced).

# 🎨 About Me

- I'm ESFJ. 
- I come from Maanshan, Anhui Province, China.
- I'm a huge sports fan and enjoy doing many kinds of sports in my spare time, including tennis🎾, basketball🏀, soccer⚽️, waterpolo🤽‍♂️, swimming🏊, badminton🏸...
- I love pop music and R&B, with Ed Sheeran and The Weeknd as my favorite English artists, David Tao and Khalil Fong as my favorite Chinese artists.