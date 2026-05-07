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

Nice to meet you! I'm Weiliang Luo (罗伟梁) from Dalian, Liaoning, China. I'm a Ph. D. candidate at [MIT Chemistry](https://chemistry.mit.edu/), advised by [Prof. Heather J. Kulik](http://hjkgrp.mit.edu/author/heather-j.-kulik/).

My research interest is molecular modeling/simulation, rational molecular design, and AI for chemistry. I'm working on the multiscale modeling of enzymatic catalysis across electronic and atomistic structures, including:

- Next-generation machine learning potential for biochemical reactive systems.
- Automatic cluster model and QM/MM simulation workflow.
- Mechanism study of novel enzymatic reactions.
- Application of density functional theory and correlated wave function methods on biochemistry.

See my [MolSSI Fellow flyer](https://molssi.org/weiliang-luo-building-better-tools-for-molecular-discovery/)!

My undergraduate studies were finished at [CCME, PKU](https://www.chem.pku.edu.cn/). I conducted my undergraduate research on graph neural networks (GNN) for ADME/T property prediction at [Molecular Design Lab](http://mdl.ipc.pku.edu.cn/mdlweb/home.php), supervised by Prof. Luhua Lai and Dr. Jianfeng Pei.

When I was a research intern at [DP Technology](https://www.dp.tech/), I focused on cutting-edge algorithms for the free energy evaluation of small drug molecules. I contributed to the molecular dynamics (MD) simulation, chemoinformatics, and software engineering in the free energy perturbation (FEP) module of the next-generation drug design platform [Hermite](https://hermite.dp.tech/). My undergraduate thesis project, supported by DP, developed a p*K* <sub>a</sub> prediction model for drug-like molecules with complex acid-base equilibrium, and accurate FEP calculation augmented by the thermodynamic correction from this p*K* <sub>a</sub> model and charge-changing alchemical transformation algorithm.

I believe that scientific computation and machine learning will replace serendipity with certainty in traditional, labor-intensive chemical discovery. However, I'm always wary of data-driven methods when it comes to real, risk-sensitive scenarios with limited quality and quantity of available data. Therefore, I'm on my way to integrating physics and statistics, understanding the relationship between data and models, and decoding the structure of the chemical space. Hope to find ones who are also excited about this vision.

Thank you for your visiting!

---

If you like the template of this homepage, you can refer to Yi Ren's GitHub Repository [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io).

# 🔥 News

- *2026.05*: QuantumPDB, of which I am a main developer, was published on JCIM!
- *2026.04*: My collaboration with Weng Lab at NEU was published on Science Advances!

# 📝 Publications

## Main contributions

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCIM</div><img src='images/QuantumPDB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[QuantumPDB: A Workflow for High-Throughput Quantum Cluster Model Generation from Protein Structures](https://pubs.acs.org/doi/10.1021/acs.jcim.5c03064)

**David W. Kastner**, _Weiliang Luo_, Wilson Ho, Clorice R. Reinhardt, Allison Keys, and Heather J. Kulik\*

[**Code**](https://github.com/davidkastner/quantumPDB)
- Automatic quantum chemistry cluster construction for diverse enzyme systems.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/CrysVCD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Materials Discovery with Valence Constrained Design in Generative Modeling](https://arxiv.org/abs/2507.19799)

**Mouyang Cheng**, **Weiliang Luo**, **Hao Tang**, Bowen Yu, Yongqiang Cheng, Weiwei Xie, Ju Li\*, Heather J. Kulik\*, Mingda Li\*

[**Code**](https://github.com/vipandyc/CrysVCD)
- Aiming to overcome valency imbalance in material generation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICMC 2025</div><img src='images/music102.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Music102: An *D*<sub>12</sub>-equivariant transformer for chord progression accompaniment](https://arxiv.org/abs/2410.18151)

**Weiliang Luo**\*

[**Code**](https://github.com/Benzoin96485/music102) | [**Conference Panel**](https://icmc2025.sites.northeastern.edu/papers/#paper2a)
- A trial of a combination of symmetry in music theory and deep learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JACS Au</div><img src='images/Uni-pKa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[(Cover Article) Bridging Machine Learning and Thermodynamics for Accurate pKa Prediction](https://doi.org/10.1021/jacsau.4c00271)

**Weiliang Luo**, **Gengmo Zhou**, Zhengdan Zhu, Guolin Ke, Zhewei Wei, Zhifeng Gao\*, Hang Zheng\*

[**Preprint at Chemrxiv**](https://doi.org/10.26434/chemrxiv-2023-lw5k0) | 
[**Code**](https://github.com/dptech-corp/Uni-pKa) | 
[**Datasets**](https://www.aissquare.com/datasets/detail?pageType=datasets&name=Uni-pKa-Dataset) | 
[**Application: Ligand Protonation with Uni-pKa Free Energy Ranking**](https://bohrium.dp.tech/apps/uni-pka) | 
[**Notebook Demo**](https://bohrium.dp.tech/notebooks/38543442597) 
- Rigorous interpretation and modeling of pKa data with thermodynamic consistency.
- State-of-the-art performance among ML-based pKa prediction models.
- Fast enumeration and ranking for the protonation states of molecules under various pH conditions.
</div>
</div>

## Other collaborations

- [Mammalian-like steroidogenesis in plants gives rise to endocrine-mimetic cardenolides](https://www.science.org/doi/10.1126/sciadv.aeb5460), Menglong Xu; David W. Kastner; _Weiliang Luo_; Fu-Shuang Li; Peter Müller; Yulin Sun; Wentao Huang; Christopher M. Glinkerman; Morgan Guempel; Heather J. Kulik; Jing-Ke Weng. Science Advances 2026, 12 (16), eaeb5460. 
- [Beyond the Training Domain: Robust Generative Transition State Models for Unseen Chemistry](https://doi.org/10.48550/arXiv.2601.16469.), Samir Darouich; Jacob W. Toney; Weiliang Luo; Johannes Kästner; Mathias Niepert; Heather J. Kulik. arXiv: 2601.16469. 
- [Evaluating Large Language Models in Scientific Discovery](https://doi.org/10.48550/arXiv.2512.15567), Zhangde Song, Jieyu Lu, Yuanqi Du, Botao Yu, Thomas M. Pruyn, Yue Huang, Kehan Guo, Xiuzhe Luo, Yuanhao Qu, Yi Qu, Yinkai Wang, Haorui Wang, Jeff Guo, Jingru Gan, Parshin Shojaee, Di Luo, Andres M. Bran, Gen Li, Qiyuan Zhao, Shao-Xiong Lennon Luo, Yuxuan Zhang, Xiang Zou, Wanru Zhao, Yifan F. Zhang, Wucheng Zhang, Shunan Zheng, Saiyang Zhang, Sartaaj Takrim Khan, Mahyar Rajabi-Kochi, Samantha Paradi-Maropakis, Tony Baltoiu, Fengyu Xie, Tianyang Chen, Kexin Huang, _Weiliang Luo_, Meijing Fang, Xin Yang, Lixue Cheng, Jiajun He, Soha Hassoun, Xiangliang Zhang, Wei Wang, Chandan K. Reddy, Chao Zhang, Zhiling Zheng, Mengdi Wang, Le Cong, Carla P. Gomes, Chang-Yu Hsieh, Aditya Nandy, Philippe Schwaller, Heather J. Kulik, Haojun Jia, Huan Sun, Seyed Mohamad Moosavi, Chenru Duan. arXiv: 2512.15567.
- [Exploring beyond Experiment: Generating High-Quality Datasets of Transition Metal Complexes with Quantum Chemistry and Machine Learning](https://doi.org/10.1016/j.coche.2025.101189), Jacob W. Toney, Aaron G. Garrison, _Weiliang Luo_, Roland G. St. Michel, Sukrit Mukhopadhyay, Heather J. Kulik, Curr. Opin. Chem. Eng. 2025, 50, 101189.
- [Regularized Second-Order Møller-Plesset Theory: Linear Scaling Implementation and Assessment on Large-Molecule Problems](https://pubs.acs.org/doi/10.1021/acs.jctc.5c00534), Zhenling Wang, Tianyi Shi, _Weiliang Luo_, Heather J. Kulik, Yang Liu, Xiaoye S. Li, Martin Head-Gordon\*, J. Chem. Theory Comput. 2025, 21, 14, 6887–6904.

# 🎖 Honors and Awards

- *2025.10*, ChemPhysChem Post Award at SMLQC 2025
- *2025.07*, MolSSI's Software Fellow
- *2024.08*, Department of Chemistry Award for Outstanding Teaching
- *2023.06*, "Chemistry Star" Academic Award (Undergraduate) (Top 2%)
- *2023.03*, Excellent Undergraduate Research Project at Peking University
- *2022.12*, National Scholarship (Undergraduate) (Top 3%)

# 📖 Educations

- *2023.09 - 2028.06 (Expectation)*, Ph. D. student, Department of Chemistry, Massachusetts Institute of Technology.
  - Advisor: Prof. Heather J. Kulik.
- *2019.09 - 2023.07*, Peking University.
  - B. Sc. in Chemistry, College of Chemistry and Molecular Engineering.
  - B. Sc. (double degree) in Intelligence Science and Technology, School of Electrical Engineering and Computer Science.
- *2016.09 - 2019.06*, Dalian No.24 High School.

# 🏫 Teaching and Service
- *2025.02 - 2025.05*, MIT UROP supervisor of Michelle Luo, MIT SB AI and Chemistry, expected ’28, on atomistic property prediction for transition metal complex using 3D Graph Neural Network
- *2024.02 - 2024.05*, Teaching Assistant for MITx, Massachusetts Institute of Technology.
- *2023.09 - 2023.12*, Teaching Assistant for *Thermodynamics I* (5.601) and *Thermodynamics II and Kinetics* (5.602), Massachusetts Institute of Technology.
- *2021.03 - 2022.01*, Teaching Assistant for *Instrumental Analysis (Honor Class)* (01034390) and *Comprehensive Analytical Chemistry (Honor Class)* (01034610), Peking University.

# 💻 Internships

- *2022.03 - 2023.08*, research intern in small-molecule algorithms, [DP Technology](https://www.dp.tech/).
