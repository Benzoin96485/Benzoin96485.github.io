---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% assign url = '/google-scholar-stats/gs_data_shieldsio.json' | absolute_url %}

<span class='anchor' id='about-me'></span>

Nice to meet you! I'm Weiliang Luo (罗伟梁) from Dalian, Liaoning, China. I'm a Ph. D. candidate at [MIT Chemistry](https://chemistry.mit.edu/), advised by [Prof. Heather J. Kulik](http://hjkgrp.mit.edu/author/heather-j.-kulik/).

<a href="https://scholar.google.com/citations?user=kkqvEcYAAAAJ">Google Scholar citations: <strong><span id="total_cit">135</span></strong></a>

My research interest is molecular modeling/simulation, rational molecular design, and AI for chemistry. I'm working on the multiscale modeling across electronic and atomistic structures, including:

- Neural network potentials, enhanced sampling, and generative modeling for reactions in condensed phases. ([Enerzyme](https://github.com/Benzoin96485/Enerzyme))
- Mechanistic studies, design and control of enzymatic and prebiotic reactions. ([Enerzymette](https://github.com/Benzoin96485/Enerzymette))
- Agentic systems for GPU acceleration and method development in quantum chemistry. ([Electrolites](https://github.com/Benzoin96485/Electrolites))

My undergraduate studies were finished at [CCME, PKU](https://www.chem.pku.edu.cn/). I conducted my undergraduate research on graph neural networks (GNN) for ADME/T property prediction at [Molecular Design Lab](http://mdl.ipc.pku.edu.cn/mdlweb/home.php), supervised by Prof. Luhua Lai and Dr. Jianfeng Pei.

When I was a research intern at [DP Technology](https://www.dp.tech/), I focused on cutting-edge algorithms for the free energy evaluation of small drug molecules. I contributed to the molecular dynamics (MD) simulation, chemoinformatics, and software engineering in the free energy perturbation (FEP) module of the next-generation drug design platform [Hermite](https://hermite.dp.tech/). My undergraduate thesis project, supported by DP, developed a p*K* <sub>a</sub> prediction model for drug-like molecules with complex acid-base equilibrium, and accurate FEP calculation augmented by the thermodynamic correction from this p*K* <sub>a</sub> model and charge-changing alchemical transformation algorithm.

I believe that scientific computation and machine learning will replace serendipity with certainty in traditional, labor-intensive chemical discovery. However, I'm always wary of data-driven methods when it comes to real, risk-sensitive scenarios with limited quality and quantity of available data. Therefore, I'm on my way to integrating physics and statistics, understanding the relationship between data and models, and decoding the structure of the chemical space. Hope to find ones who are also excited about this vision.

Thank you for your visiting!

---

If you like the template of this homepage, you can refer to Yi Ren's GitHub Repository [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io).

# 🔥 News

- *2026.10*: The first paper with my Enerzyme open-source initiative was accepted by JCTC!

# 📝 Publications

## Main contributions

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCTC</div><img src='images/Enerzyme.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enerzyme: An Efficient Reactive Neural Network Potential Training Framework for Enzyme Cluster Models with Application to Methyltransferases.](https://doi.org/10.1021/acs.jctc.6c01330)

**Weiliang Luo**\*, and Heather J. Kulik

[**Preprint at Arxiv**](https://arxiv.org/abs/2607.01362) | [**Code for Enerzyme**](https://github.com/Benzoin96485/Enerzyme) | [**Code for Enerzymette**](https://github.com/Benzoin96485/Enerzymette) <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:4DMP91E08xMC'>| Citations: 0</span></strong>
- The first release of Enerzyme, a reactive neural network potential design and training framework for enzyme cluster models.
- The first release of Enerzymette, a reactive neural network potential harness and evaluation framework for enzyme mechanistic studies.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCIM</div><img src='images/QuantumPDB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[QuantumPDB: A Workflow for High-Throughput Quantum Cluster Model Generation from Protein Structures](https://pubs.acs.org/doi/10.1021/acs.jcim.5c03064)

David W. Kastner, **Weiliang Luo**, Wilson Ho, Clorice R. Reinhardt, Allison Keys, and Heather J. Kulik

[**Preprint at Chemrxiv**](https://chemrxiv.org/doi/10.26434/chemrxiv-2026-w5x1d) | [**Code**](https://github.com/hjkgrp/quantumPDB) <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:ULOm3_A8WrAC'>| Citations: 4</span></strong>
- Automatic quantum chemistry cluster construction for diverse enzyme systems.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nat. Comput. Sci.</div><img src='images/CrysVCD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Materials Discovery with Valence Constrained Design in Generative Modeling](https://arxiv.org/abs/2507.19799)

Mouyang Cheng\*, **Weiliang Luo**\*, Hao Tang\*, Bowen Yu\*, Yongqiang Cheng, Weiwei Xie, Ju Li, Heather J. Kulik, Mingda Li\*

[**Preprint at arXiv**](https://arxiv.org/abs/2507.19799) | 
[**Code**](https://github.com/vipandyc/CrysVCD) <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:MXK_kJrjxJIC'>| Citations: 6</span></strong>
- A solution to the ubiquitous valency imbalance in generative modeling of materials.
- Efficient stability screening with foundational MLIP.
- High-performance thermal-conductive and optical materials discovery with conditional generation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICMC 2025</div><img src='images/music102.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Music102: An *D*<sub>12</sub>-equivariant transformer for chord progression accompaniment](https://arxiv.org/abs/2410.18151)

**Weiliang Luo**\*

[**Code**](https://github.com/Benzoin96485/music102) | [**Conference Panel**](https://icmc2025.sites.northeastern.edu/papers/#paper2a) <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:0EnyYjriUFMC'>| Citations: 2</span></strong>
- A trial of a combination of symmetry and group representations in music theory and deep learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JACS Au</div><img src='images/Uni-pKa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[(Cover Article) Bridging Machine Learning and Thermodynamics for Accurate pKa Prediction](https://doi.org/10.1021/jacsau.4c00271)

**Weiliang Luo**\*, **Gengmo Zhou**\*, Zhengdan Zhu, Guolin Ke, Zhewei Wei, Zhifeng Gao, Hang Zheng

[**Preprint at Chemrxiv**](https://doi.org/10.26434/chemrxiv-2023-lw5k0) | 
[**Code**](https://github.com/dptech-corp/Uni-pKa) | 
[**Datasets**](https://www.aissquare.com/datasets/detail?pageType=datasets&name=Uni-pKa-Dataset) | 
[**Application: Ligand Protonation with Uni-pKa Free Energy Ranking**](https://bohrium.dp.tech/apps/uni-pka) | 
[**Notebook Demo**](https://bohrium.dp.tech/notebooks/38543442597) <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:qjMakFHDy7sC'>| Citations: 59</span></strong> 
- Rigorous interpretation and modeling of pKa data with thermodynamic consistency.
- State-of-the-art performance among ML-based pKa prediction models.
- Fast enumeration and ranking for the protonation states of molecules under various pH conditions.
</div>
</div>

## Other collaborations

- [Doubly Metastable Synthesis for Accelerated Quantum Materials Discovery](https://arxiv.org/abs/2610.13859), Kyuho Lee, Berit H Goodge, Soonhyun Kwon, Yash Anand, Theo Manev, Maximilien F Debbas, **Weiliang Luo**, Takehito Suzuki, Heather J Kulik, Joseph G. Checkelsky. arXiv: 2610.13859. <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:aqlVkmm33-oC'>| Citations: 0</span></strong>
- [Mammalian-like steroidogenesis in plants gives rise to endocrine-mimetic cardenolides](https://www.science.org/doi/10.1126/sciadv.aeb5460), Menglong Xu; David W. Kastner; **Weiliang Luo**; Fu-Shuang Li; Peter Müller; Yulin Sun; Wentao Huang; Christopher M. Glinkerman; Morgan Guempel; Heather J. Kulik; Jing-Ke Weng. Sci. Adv. 2026, 12 (16), eaeb5460. <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:_kc_bZDykSQC'>| Citations: 8</span></strong>
- [Robust generative transition-state models for unseen chemistry](https://www.nature.com/articles/s43588-026-01034-5), Samir Darouich; Jacob W. Toney; **Weiliang Luo**; Johannes Kästner; Mathias Niepert; Heather J. Kulik. Nat. Comput. Sci. 2026, 6, 1147–1157. <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:M3ejUd6NZC8C'>| Citations: 10</span></strong>
- [Evaluating Large Language Models in Scientific Discovery](https://doi.org/10.48550/arXiv.2512.15567), Zhangde Song, Jieyu Lu, Yuanqi Du, Botao Yu, Thomas M. Pruyn, Yue Huang, Kehan Guo, Xiuzhe Luo, Yuanhao Qu, Yi Qu, Yinkai Wang, Haorui Wang, Jeff Guo, Jingru Gan, Parshin Shojaee, Di Luo, Andres M. Bran, Gen Li, Qiyuan Zhao, Shao-Xiong Lennon Luo, Yuxuan Zhang, Xiang Zou, Wanru Zhao, Yifan F. Zhang, Wucheng Zhang, Shunan Zheng, Saiyang Zhang, Sartaaj Takrim Khan, Mahyar Rajabi-Kochi, Samantha Paradi-Maropakis, Tony Baltoiu, Fengyu Xie, Tianyang Chen, Kexin Huang, **Weiliang Luo**, Meijing Fang, Xin Yang, Lixue Cheng, Jiajun He, Soha Hassoun, Xiangliang Zhang, Wei Wang, Chandan K. Reddy, Chao Zhang, Zhiling Zheng, Mengdi Wang, Le Cong, Carla P. Gomes, Chang-Yu Hsieh, Aditya Nandy, Philippe Schwaller, Heather J. Kulik, Haojun Jia, Huan Sun, Seyed Mohamad Moosavi, Chenru Duan. arXiv: 2512.15567. <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:Zph67rFs4hoC'>| Citations: 27</span></strong>
- [Exploring beyond Experiment: Generating High-Quality Datasets of Transition Metal Complexes with Quantum Chemistry and Machine Learning](https://doi.org/10.1016/j.coche.2025.101189), Jacob W. Toney, Aaron G. Garrison, **Weiliang Luo**, Roland G. St. Michel, Sukrit Mukhopadhyay, Heather J. Kulik, Curr. Opin. Chem. Eng. 2025, 50, 101189. <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:3fE2CSJIrl8C'>| Citations: 9</span></strong>
- [Regularized Second-Order Møller-Plesset Theory: Linear Scaling Implementation and Assessment on Large-Molecule Problems](https://pubs.acs.org/doi/10.1021/acs.jctc.5c00534), Zhenling Wang, Tianyi Shi, **Weiliang Luo**, Heather J. Kulik, Yang Liu, Xiaoye S. Li, Martin Head-Gordon, J. Chem. Theory Comput. 2025, 21, 14, 6887–6904. <strong><span class='show_paper_citations' data='kkqvEcYAAAAJ:8k81kl-MbHgC'>| Citations: 10</span></strong>

# 🎖 Honors and Awards

- *2025.10*, ChemPhysChem Post Award at SMLQC 2025
- *2025.07*, Sigma Xi
- *2025.05*, [MolSSI's Software Fellow](https://molssi.org/weiliang-luo-building-better-tools-for-molecular-discovery/)
- *2024.08*, Department of Chemistry Award for Outstanding Teaching
- *2023.06*, "Chemistry Star" Academic Award (Undergraduate) (Top 2%)
- *2023.03*, Excellent Undergraduate Research Project at Peking University
- *2022.12*, National Scholarship (Undergraduate) (Top 3%)

# 📖 Educations

- *2023.09 - 2028.06 (Expectation)*, Ph. D. student, Department of Chemistry, Massachusetts Institute of Technology.
- *2019.09 - 2023.07*, Peking University.
  - B. Sc. in Chemistry, College of Chemistry and Molecular Engineering.
  - B. Sc. (double degree) in Intelligence Science and Technology, School of Electrical Engineering and Computer Science.
- *2016.09 - 2019.06*, Dalian No.24 High School.

# 🏫 Teaching and Mentorship
- *2026.07 - Now*, MIT UROP supervisor of Amelia England, Georgia Tech Chemistry, expected ’27, on adaptive QM/MM embedding for enzyme catalysis modeling
- *2025.02 - 2025.05*, MIT UROP supervisor of Michelle Luo, MIT SB AI and Chemistry, expected ’28, on atomistic property prediction for transition metal complex using 3D Graph Neural Network
- *2024.02 - 2024.05*, Teaching Assistant for MITx, Massachusetts Institute of Technology.
- *2023.09 - 2023.12*, Teaching Assistant for *Thermodynamics I* (5.601) and *Thermodynamics II and Kinetics* (5.602), Massachusetts Institute of Technology.
- *2021.03 - 2022.01*, Teaching Assistant for *Instrumental Analysis (Honor Class)* (01034390) and *Comprehensive Analytical Chemistry (Honor Class)* (01034610), Peking University.

# 📣 Leadership and Service
- *2026.12*, Organizer of [Winter AI for Materials & Chemistry Workshop](https://ai4mc26.github.io/) at Microsoft Research New England.
- *2026.08*, Organizer of [PKU-Bionet Symposium](https://pkubio.org/).
- *2026.05 - Now*, President of MIT Chinese Student and Scholar Association
- *2025.11 - 2026.03*, Chief Director of MITCSSA-PKUAANE Year-of-the-horse Spring Festival Gala

# 💻 Internships

- *2022.03 - 2023.08*, research intern in small-molecule drug discovery algorithms, [DP Technology](https://www.dp.tech/).
