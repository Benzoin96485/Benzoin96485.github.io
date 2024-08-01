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

Nice to meet you! I'm Weiliang Luo (罗伟梁) from Dalian, Liaoning, China. I'm a Ph. D. student at [MIT Chemistry](https://chemistry.mit.edu/), advised by [Prof. Heather J. Kulik](http://hjkgrp.mit.edu/author/heather-j.-kulik/).

My research interest is molecular modeling/simulation, rational molecular design, and AI for chemistry. I'm working on the multiscale modeling of enzymatic catalysis across electronic and atomistic structures, including:

- Next-generation machine learning potential for biochemical reactive systems.
- Automatic cluster model and QM/MM simulation workflow.
- Mechanism study of novel enzymatic reactions.
- Application of density functional theory and correlated wave function methods on biochemistry.

My undergraduate study is at [CCME, PKU](https://www.chem.pku.edu.cn/). I conducted my undergraduate research on graph neural networks (GNN) for ADME/T property prediction at [Molecular Design Lab](http://mdl.ipc.pku.edu.cn/mdlweb/home.php), supervised by Prof. Luhua Lai and Dr. Jianfeng Pei.

When I was a research intern at [DP Technology](https://www.dp.tech/), I focused on cutting-edge algorithms for the free energy evaluation of small drug molecules. I contributed to the molecular dynamics (MD) simulation, chemoinformatics, and software engineering in the free energy perturbation (FEP) module of the next-generation drug design platform [Hermite](https://hermite.dp.tech/). My undergraduate thesis completed here was about accurate FEP calculation and p*K* <sub>a</sub> prediction for drug-like molecules with complex acid-base equilibrium.

I believe that scientific computation and machine learning will replace serendipity with certainty in traditional, labor-intensive chemical discovery. However, I'm always wary of data-driven methods when it comes to real, risk-sensitive scenarios with limited quality and quantity of available data. Therefore, I'm on my way combining physics and statistics, understanding the relationship between data and models, and decoding the structure of the chemical space. Hope to find ones who are also excited about this vision.

Thank you for your visiting!

---

If you like the template of this homepage, you can refer to Yi Ren's Github Repository [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io).

# 🔥 News

- *2024.07*: Uni-pKa has been accepted by *JACS Au* and selected as the cover article!
- *2023.11*: I joined [Kulik's research group](http://hjkgrp.mit.edu/)!

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JACS Au</div><img src='images/Uni-pKa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bridging Machine Learning and Thermodynamics for Accurate pKa Prediction](https://doi.org/10.1021/jacsau.4c00271)

**Weiliang Luo**, **Gengmo Zhou**, Zhengdan Zhu, Guolin Ke, Zhewei Wei, Zhifeng Gao\*, Hang Zheng\*

[**Preprint at Chemrxiv**](https://doi.org/10.26434/chemrxiv-2023-lw5k0) | 
[**Code**](https://github.com/dptech-corp/Uni-pKa) | 
[**Datasets**](https://www.aissquare.com/datasets/detail?pageType=datasets&name=Uni-pKa-Dataset) | 
[**Application: Ligand Protonation with Uni-pKa Free Energy Ranking**](https://bohrium.dp.tech/apps/uni-pka) 
- Rigorous interpretation and modeling of pKa data with thermodynamic consistency.
- State-of-the-art performance among ML-based pKa prediction models.
- Fast enumeration and ranking for the protonation states of molecules under various pH conditions.
</div>
</div>

# 🎖 Honors and Awards

- *2023.6*, "Chemistry Star" Academic Award (Undergraduate) (Top 2%)
- *2023.3*, Excellent Undergraduate Research
- *2022.12*, National Scholarship (Undergraduate) (Top 3%)

# 📖 Educations

- *2023.09 - 2028.06 (Expectation)*, Ph. D. student, Department of Chemistry, Massachusetts Institute of Technology.
  - Advisor: Prof. Heather J. Kulik.
- *2019.09 - 2023.07*, Peking University.
  - B. Sc. in Chemistry, College of Chemistry and Molecular Engineering.
  - B. Sc. (double degree) in Intelligence Science and Technology, School of Electrical Engineering and Computer Science.
- *2016.09 - 2019.06*, Dalian No.24 High School.

# 🏫 Teaching and Service
- *2023.02 - 2023.05*, Teaching Assistant for MITx, Massachusetts Institute of Technology.
- *2023.09 - 2023.12*, Teaching Assistant for *Thermodynamics I* (5.601) and *Thermodynamics II and Kinetics* (5.602), Massachusetts Institute of Technology.
- *2021.03 - 2022.01*, Teaching Assistant for *Instrumental Analysis (Honor Class)* (01034390) and *Comprehensive Analytical Chemistry (Honor Class)* (01034610), Peking University.

# 💻 Internships

- *2022.03 - 2023.08*, research intern in small-molecule algorithms, [DP Technology](https://www.dp.tech/).
