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

Welcome to my homepage! I am **Qiyu Chen**, a direct Ph.D. student in Pattern Recognition and Intelligent Systems at the **Institute of Automation, Chinese Academy of Sciences (CASIA)**, supervised by Prof. [Zhengtao Zhang](https://scholar.google.com/citations?user=k1IruYkAAAAJ).

My research focuses on **industrial visual anomaly detection**, especially anomaly data synthesis, zero-shot anomaly detection, semantic segmentation, multimodal large models, and robust computer vision systems for industrial inspection.

Please feel free to contact me if you are interested in research collaboration or academic discussion.

# Resume

[![Download my CV (PDF)](https://img.shields.io/badge/Resume-PDF-blue?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white)](/docs/CV_Qiyu_Chen_jake.pdf)

# News
- *2026.03*: 🎉🎉 Our paper [**CoPS: Conditional Prompt Synthesis for Zero-Shot Anomaly Detection**](https://arxiv.org/abs/2508.03447) was accepted by **CVPR Findings**; the [code](https://github.com/cqylunlun/CoPS) has been open-sourced.
- *2026.01*: 🎉🎉 Our paper [**MRAD: Zero-Shot Anomaly Detection With Memory-Driven Retrieval**](https://openreview.net/forum?id=TQkFiW3AEX) was accepted by **ICLR**; the [code](https://github.com/CROVO1026/MRAD) has been open-sourced.
- *2025.11*: 🎉🎉 Our paper [**TDSS: Task Dynamic-Synergistic Skill Adaptation for Efficient and Scalable Multi-Task Learning**](https://doi.org/10.1609/aaai.v40i14.38172) was accepted by **AAAI**.
- *2025.11*: 🎉🎉 Our paper [**Parameter-, Memory-, Time-Efficient Multi-Task Dense Vision Adaptation**](https://doi.org/10.1609/aaai.v40i14.38171) was accepted by **AAAI**.
- *2025.11*: 🎉🎉 Our paper [**Anomagic: Crossmodal Prompt-driven Zero-shot Anomaly Generation**](https://doi.org/10.1609/aaai.v40i7.37466) was accepted by **AAAI**; the [code](https://github.com/yuxin-jiang/Anomagic) has been open-sourced.
- *2025.05*: 🎉🎉 Our paper [**Center-aware Residual Anomaly Synthesis for Multiclass Industrial Anomaly Detection**](https://doi.org/10.1109/TII.2025.3575122) was published in **IEEE Transactions on Industrial Informatics**; the [code](https://github.com/cqylunlun/CRAS) has been open-sourced.
- *2025.03*: 🎉🎉 Our paper [**Bayesian Prompt Flow Learning for Zero-Shot Anomaly Detection**](https://openaccess.thecvf.com/content/CVPR2025/html/Qu_Bayesian_Prompt_Flow_Learning_for_Zero-Shot_Anomaly_Detection_CVPR_2025_paper.html) was accepted by **CVPR**; the [code](https://github.com/xiaozhen228/Bayes-PFL) has been open-sourced.
- *2024.10*: 🎉🎉 Our paper [**Progressive Boundary Guided Anomaly Synthesis for Industrial Anomaly Detection**](https://doi.org/10.1109/TCSVT.2024.3479887) was published in **IEEE Transactions on Circuits and Systems for Video Technology**; the [code](https://github.com/cqylunlun/PBAS) has been open-sourced.
- *2024.07*: 🎉🎉 Our paper [**A Unified Anomaly Synthesis Strategy with Gradient Ascent for Industrial AD and Localization**](https://doi.org/10.1007/978-3-031-72855-6_3) was accepted by **ECCV**; the [code](https://github.com/cqylunlun/GLASS) has been open-sourced.

# Publications

<ol reversed>
  <li id="pub-cops">
    CoPS: Conditional Prompt Synthesis for Zero-Shot Anomaly Detection
    <a href="https://arxiv.org/abs/2508.03447">[Paper]</a>
    <a href="https://github.com/cqylunlun/CoPS">[Code]</a><br>
    <strong>Qiyu Chen</strong>, Zhen Qu, Wei Luo, Haiming Yao, Yunkang Cao, et al.<br>
    <i>IEEE/CVF Conference on Computer Vision and Pattern Recognition Findings <strong>(CVPR-F)</strong></i>.
  </li>
  <li id="pub-cras">
    Center-aware Residual Anomaly Synthesis for Multiclass Industrial Anomaly Detection
    <a href="https://doi.org/10.1109/TII.2025.3575122">[Paper]</a>
    <a href="https://github.com/cqylunlun/CRAS">[Code]</a><br>
    <strong>Qiyu Chen</strong>, Huiyuan Luo, Haiming Yao, Wei Luo, Zhen Qu, et al.<br>
    <i>IEEE Transactions on Industrial Informatics <strong>(TII)</strong></i>.
  </li>
  <li id="pub-pbas">
    Progressive Boundary Guided Anomaly Synthesis for Industrial Anomaly Detection
    <a href="https://doi.org/10.1109/TCSVT.2024.3479887">[Paper]</a>
    <a href="https://github.com/cqylunlun/PBAS">[Code]</a><br>
    <strong>Qiyu Chen</strong>, Huiyuan Luo, Han Gao, Chengkan Lv, Zhengtao Zhang<br>
    <i>IEEE Transactions on Circuits and Systems for Video Technology <strong>(TCSVT)</strong></i>.
  </li>
  <li id="pub-glass">
    A Unified Anomaly Synthesis Strategy with Gradient Ascent for Industrial AD and Localization
    <a href="https://doi.org/10.1007/978-3-031-72855-6_3">[Paper]</a>
    <a href="https://github.com/cqylunlun/GLASS">[Code]</a><br>
    <strong>Qiyu Chen</strong>, Huiyuan Luo, Chengkan Lv, Zhengtao Zhang<br>
    <i>European Conference on Computer Vision <strong>(ECCV)</strong></i>.
  </li>
  <li id="pub-tdss">
    TDSS: Task Dynamic-Synergistic Skill Adaptation for Efficient and Scalable Multi-Task Learning
    <a href="https://doi.org/10.1609/aaai.v40i14.38172">[Paper]</a><br>
    Haiming Yao, <strong>Qiyu Chen</strong>, Wei Luo, Zheng Zhang, Jianxing Liao, et al.<br>
    <i>AAAI Conference on Artificial Intelligence <strong>(AAAI)</strong></i>.
  </li>
  <li id="pub-mrad">
    MRAD: Zero-Shot Anomaly Detection With Memory-Driven Retrieval
    <a href="https://openreview.net/forum?id=TQkFiW3AEX">[Paper]</a>
    <a href="https://github.com/CROVO1026/MRAD">[Code]</a><br>
    Chaoran Xu, Chengkan Lv, <strong>Qiyu Chen</strong>, Feng Zhang, Zhengtao Zhang<br>
    <i>International Conference on Learning Representations <strong>(ICLR)</strong></i>.
  </li>
  <li id="pub-pmt">
    Parameter-, Memory-, Time-Efficient Multi-Task Dense Vision Adaptation
    <a href="https://doi.org/10.1609/aaai.v40i14.38171">[Paper]</a><br>
    Haiming Yao, Wei Luo, <strong>Qiyu Chen</strong>, Jianxing Liao, Wei You<br>
    <i>AAAI Conference on Artificial Intelligence <strong>(AAAI)</strong></i>.
  </li>
  <li id="pub-anomagic">
    Anomagic: Crossmodal Prompt-driven Zero-shot Anomaly Generation
    <a href="https://doi.org/10.1609/aaai.v40i7.37466">[Paper]</a>
    <a href="https://github.com/yuxin-jiang/Anomagic">[Code]</a><br>
    Yuxin Jiang, Wei Luo, Hui Zhang, <strong>Qiyu Chen</strong>, Haiming Yao, et al.<br>
    <i>AAAI Conference on Artificial Intelligence <strong>(AAAI)</strong></i>.
  </li>
  <li id="pub-bayes-pfl">
    Bayesian Prompt Flow Learning for Zero-Shot Anomaly Detection
    <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Qu_Bayesian_Prompt_Flow_Learning_for_Zero-Shot_Anomaly_Detection_CVPR_2025_paper.html">[Paper]</a>
    <a href="https://github.com/xiaozhen228/Bayes-PFL">[Code]</a><br>
    Zhen Qu, Xian Tao, Xinyi Gong, Shichen Qu, <strong>Qiyu Chen</strong>, et al.<br>
    <i>IEEE/CVF Conference on Computer Vision and Pattern Recognition <strong>(CVPR)</strong></i>.
  </li>
  <li id="pub-flower-pot">
    Distributed Integrated Intelligent Pot Using Remote Monitor and Control System
    <a href="https://doi.org/10.12677/CSA.2020.102023">[Paper]</a><br>
    <strong>Qiyu Chen</strong>, Tianming Li, Shengyue Wang, Mingzhong Huang<br>
    <i>Computer Science and Application <strong>(CSA)</strong></i>.
  </li>
  <li id="pub-vr-flower">
    The Remote Intelligent Virtual Reality Monitoring and Control System for Flower Maintenance
    <a href="https://doi.org/10.12677/CSA.2016.63015">[Paper]</a><br>
    <strong>Qiyu Chen</strong>, Peng Gong, Renchun Guo, Gaojian Zhang<br>
    <i>Computer Science and Application <strong>(CSA)</strong></i>.
  </li>
</ol>

# Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV & TII</div><img src='images/project.png' alt="Low-contrast fabric anomaly segmentation" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Unsupervised Image Segmentation for Low-Contrast Anomalies**

- Developed fabric defect detection and data acquisition equipment for a university–industry collaboration project with Weiqiao Textile.
- Achieved 99.9% domain-level SOTA performance for subtle fabric defects.
- Resulted in first-author ECCV and TII papers and two first-author invention patents.
</div>
</div>

<!-- # Experience

- ### *May 2025 - May 2026, Huawei, 2012 Laboratories, Central Research Institute*
  **AI Algorithm Engineer Intern**, Terminal Computing, Beijing, China  
  Built an edge-side hardware-software co-designed gesture interaction vision system based on event cameras, constructed a 12-class gesture dataset, and explored efficient fine-tuning for lightweight dense visual prediction on terminal devices.

- ### *Oct. 2023 - Oct. 2024, CASIVision Technology Co., Ltd., Industrial Vision Laboratory*
  **Computer Vision Algorithm Engineer Intern**, Defect Detection, Beijing, China  
  Developed defect-detection algorithms for mobile-phone middle-frame inspection and explored defect image generation for back-panel inspection under scarce real-defect data. -->

# Patents

- **Remote Intelligent Flower-Watering System Based on Virtual Reality Technology**, CN105532390B.
- **Multi-Point Sampling Device and UAV Carrying the Multi-Point Sampling Device**, CN111551401B.
- **Intelligent Flowerpot Control System, Flowerpot, and Control Method**, CN111657003B.
- **Defect Detection Method, System, Device, and Computer-Readable Storage Medium**, CN118279280B.
- **Fabric Surface Defect Detection Method and Related Apparatus**, CN119810058B.

# Awards

- **First Prize**, China Intelligent Robot Fighting Competition, National.
- **Second Prize**, Chinese Collegiate Computing Design Competition, National.
- **Third Prize**, National University Intelligent Car Race, National.
- **First Prize**, CAS Industrial Vision Achievement Scholarship.
- **Second Prize**, CASIA Climbing Scholarship.
- **Merit Student**, University of Chinese Academy of Sciences.
- **Outstanding Graduate**, Tongji University.
- **Vice President**, College of Electronics and Information Engineering, Tongji University.

# Education

- ### *Sep. 2021 - Jul. 2026, Institute of Automation, Chinese Academy of Sciences*
  **Direct Ph.D. Student** in Pattern Recognition and Intelligent Systems, Beijing, China  
  **Advisor**: Prof. [Zhengtao Zhang](https://scholar.google.com/citations?user=k1IruYkAAAAJ)

- ### *Sep. 2017 - Jul. 2021, Tongji University*
  **B.Eng.** in Communication Engineering, College of Electronics and Information Engineering, Shanghai, China
