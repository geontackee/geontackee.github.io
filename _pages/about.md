---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /cv/
  - /resume
  - /publications/
---

{% include base_path %}

I am an M.S. student in Artificial Intelligence at the [Kim Jaechul Graduate School of AI, KAIST](https://gsai.kaist.ac.kr/), advised by Prof. [Jaegul Choo](https://sites.google.com/site/jaegulchoo/) in the DAVIAN Lab. I received my B.S. in Computer Science from [New York University Abu Dhabi (NYUAD)](https://nyuad.nyu.edu/) on a full-ride scholarship.

My research focuses on **Efficient AI**, **Model Compression**, and **Computer Vision**.

<a href="{{ base_path }}/files/Geon_Tack_Lee_CV.pdf" download><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i> Download my CV</a>

News
======
* **[Sep. 2026]** *Denoised Variance-Based Pruning with Optimal Brain Bias Compensation* was published at **ECCV 2026**.
* **[Aug. 2026]** Started my M.S. in Artificial Intelligence at KAIST.

Education
======
* **M.S. in Artificial Intelligence**, Korea Advanced Institute of Science and Technology (KAIST), Aug. 2026 – Present
  * Kim Jaechul Graduate School of AI · Advisor: Jaegul Choo
* **B.S. in Computer Science**, New York University Abu Dhabi (NYUAD), Aug. 2020 – May 2026
  * GPA: 3.87 / 4.0 · Full ride scholarship

Ongoing Research
======
I am developing **inter-layer-aware low-rank compression** frameworks for Large Language Models (LLMs) and Vision Transformers (ViTs). Specifically, I design optimization algorithms that account for cross-layer error accumulation to preserve representational fidelity under aggressive compression constraints.

Publications
======
{% for post in site.publications reversed %}
* **{% if post.paperurl %}[{{ post.title }}]({{ post.paperurl }}){% else %}{{ post.title }}{% endif %}**  
  {{ post.authors }}  
  *{{ post.venue }}*
{% endfor %}

Experience
======
* **Research Intern**, DAVIAN Lab, KAIST AI — Dec. 2025 – Aug. 2026
  * Efficient AI, Low-rank Compression for ViTs and LLMs, Structured Pruning for ViTs
  * Advisors: Jaegul Choo and Kang Eun Jeon
* **Research Assistant**, Embodied AI and Robotics Lab, NYUAD — May 2025 – Dec. 2025
  * Computer Vision, Sign Language Translation
  * Advisor: Yi Fang
* **Research Intern**, MoMA Lab, NYUAD — Jun. 2022 – Jul. 2022
  * Security and ML, Machine Learning Framework for Industrial Control Systems
  * Advisors: Michail Maniatakos and Constantine Doumanidis

Honors & Awards
======
* **2022** — 2nd Place, NYUAD International Hackathon for Social Good Focusing on Quantum Computing
