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

Aloha there! I am a 3rd year Ph.D. candidate at College of Computer Science of Nankai University, advised by Prof. Tao Li and Ye Lu. I am affliated with [Nankai Intelligent Computing System Lab](https://ics.nankai.edu.cn/) and [Haihe Lab of ITAI](https://www.hl-it.cn/). 

I will be a visiting scholar at Nanyang Technological University (NTU) supervised by [Prof. Weichen Liu](https://personal.ntu.edu.sg/liu/) with the sponsorship of China Scholarship Council (CSC) for 12 months, from March 2025 to March 2026. 

My research interest includes intelligent computing system, system security, and trusted execution environment. I have published 14 papers at the top international journals and conferences with total <a href='https://scholar.google.com/citations?user=LCsCUrMAAAAJ'>google scholar citations <strong><span id='total_cit'>90+</span></strong></a> <a href='https://scholar.google.com/citations?user=LCsCUrMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

Here is my resume: [\[CV-en\]](http://www.jolyonjian.fun/files/cv-en.pdf) [\[CV-cn\]](http://www.jolyonjian.fun/files/cv-cn.pdf)

# 📖 Educations
- *2022.09 - 2026.06*, College of Computer Science, Nankai University. 
Successive master-doctor program (Ph.D. student phase) in Computer Science.
Research fields: Trusted execution environment, Confidential computing.
- *2025.03 - 2026.03*, College of Computing and Data Science, Nanyang Technological University. 
Visting Ph.D. student (CSC) in Computer Archtecture.
Research fields: TEE-based heterogeneous computing.
- *2020.09 - 2022.06*, College of Computer Science, Nankai University. 
Successive master-doctor program (Master student phase) in Computer Science.
Research fields: Trusted execution environment, Smart contract virtual machine.
- *2016.09 - 2020.06*, College of Cyber Science, Nankai University.
B.Eng. in Internet of Things Engineering.
Bachelor’s degree program.


# 🔥 News
- *2025.03*: Our paper titled "DRS: A Deep Reinforcement Learning Enhanced Kubernetes Scheduler for Microservice-based System" has been listed as the [most cited paper of SPE](https://onlinelibrary.wiley.com/journal/1097024x?tabActivePane=undefined) in the past two years!
- *2024.08*: We accepted media interviews on behalf of the 8 participating teams in the Phytium track at the 19th China Graduate Electronics Design Contest. [\[Video\]](http://www.jolyonjian.fun/files/interview.mp4)
 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TC 2025</div><img src='images/smartzone.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SmartZone: Runtime Support for Secure and Efficient On-device Inference on ARM TrustZone](https://ieeexplore.ieee.org/abstract/document/10949698)

**Zhaolong Jian**, Xu Liu, Qiankun Dong, Longkai Cheng, Xueshuo Xie*, and Tao Li*

[**Project**](https://github.com/nkicsl/SmartZone) ![Static Badge](https://img.shields.io/github/stars/nkicsl/SmartZone?style=social) <strong><span class='show_paper_citations' data='LCsCUrMAAAAJ:UebtZRa9Y70C'></span></strong>
- SmartZone provides entire protection for on-device DNN and LLM inference while keeping efficiency.
- SmartZone is a good paradigm for TrustZone-based high performance confidential computing.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPDS 2023</div><img src='images/tscvee.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TSC-VEE: A TrustZone-Based Smart Contract Virtual Execution Environment](https://ieeexplore.ieee.org/document/10094016)

**Zhaolong Jian**, Ye Lu*, Youyang Qiao, Yaozheng Fang, Xueshuo Xie, Dayi Yang, Zhiyuan Zhou, and Tao Li

[**Project**](https://github.com/nkicsl/TSC-VEE) ![Static Badge](https://img.shields.io/github/stars/nkicsl/TSC-VEE?style=social) <strong><span class='show_paper_citations' data='LCsCUrMAAAAJ:WF5omc3nYNoC'></span></strong>
- TSC-VEE is the first virtual execution environment for Solidity smart contract on ARM TrustZone.
- TSC-VEE contributed the first evm implemented in pure C language in the community.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SPE 2023</div><img src='images/drs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DRS: A deep reinforcement learning enhanced Kubernetes scheduler for microservice-based system](https://onlinelibrary.wiley.com/doi/10.1002/spe.3284)

**Zhaolong Jian**, Xueshuo Xie, Yaozheng Fang, Yibing Jiang, Ye Lu, Ankan Dash, Tao Li*, and Guiling Wang

[**Project**](https://github.com/JolyonJian/DRS) ![Static Badge](https://img.shields.io/github/stars/JolyonJian/DRS?style=social) <strong><span class='show_paper_citations' data='LCsCUrMAAAAJ:YsMSGLbcyi4C'></span></strong>
- DRS uses the DQN algorithm to enhance the native scheduler of Kubernetes.
- DRS provides a good implementation reference for Kubernetes scheduling optimization.
</div>
</div>

**Publications List: 14 papers totally**

### 2025

- [SmartZone: Runtime Support for Secure and Efficient On-device Inference on ARM TrustZone](https://ieeexplore.ieee.org/abstract/document/10949698), **Zhaolong Jian**, Xu Liu, Qiankun Dong, Longkai Cheng, Xueshuo Xie\*, and Tao Li\*, **TC 2025** ![Static Badge](https://img.shields.io/badge/CCF_A-red)

- [Hybrid-Granularity Parallelism Support for Fast Transaction Processing in Blockchain-based Federated Learning](https://www.ipdps.org/ipdps2025/2025-advance-program.html), Mulin Li, **Zhaolong Jian**, Kaixuan Yang, Xueshuo Xie\*, Wajdy, Tao Li\*, **IPDPS 2025** ![Static Badge](https://img.shields.io/badge/CCF_B-blue)

### 2024

- [Memory-Efficient and Secure DNN Inference on TrustZone-enabled Consumer IoT Devices](https://ieeexplore.ieee.org/document/10621088), Xueshuo Xie, Haoxu Wang, **Zhaolong Jian**, Tao Li\*, Wei Wang, Zhiwei Xu, and Guiling Wang, **INFOCOM 2024** ![Static Badge](https://img.shields.io/badge/CCF_A-red)

### 2023

- [DRS: A Deep Reinforcement Learning Enhanced Kubernetes Scheduler for Microservice-based System](https://onlinelibrary.wiley.com/doi/10.1002/spe.3284), **Zhaolong Jian**, Xueshuo Xie, Yaozheng Fang, Yibing Jiang, Ye Lu, Ankan Dash, Tao Li\*, and Guiling Wang, **SPE 2023** ![Static Badge](https://img.shields.io/badge/CCF_B-blue)
- [TSC-VEE: A TrustZone-Based Smart Contract Virtual Execution Environment](https://ieeexplore.ieee.org/document/10094016), **Zhaolong Jian**, Ye Lu\*, Youyang Qiao, Yaozheng Fang, Xueshuo Xie, Dayi Yang, Zhiyuan Zhou, and Tao Li, **TPDS 2023** ![Static Badge](https://img.shields.io/badge/CCF_A-red)
- [Block-gram: Mining Knowledgeable Features for Efficiently Smart Contract Vulnerability Detection](https://www.sciencedirect.com/science/article/pii/S2352864823001347), Xueshuo Xie, Haolong Wang, **Zhaolong Jian**, Yaozheng Fang, Zichun Wang, and Tao Li\*, **DCN 2023** ![Static Badge](https://img.shields.io/badge/SCI_II-blue)
- [Block-gram: Mining Knowledgeable Features for Smart Contract Vulnerability Detection](https://dl.acm.org/doi/10.1007/978-3-031-28124-2_52), Tao Li, Haolong Wang, Yaozheng Fang, **Zhaolong Jian**, Zichun Wang, and Xueshuo Xie\*, **SmartCom 2022** ![Static Badge](https://img.shields.io/badge/EI-green)

### 2022

- [SmartVM: A Smart Contract Virtual Machine for Fast On-Chain DNN Computations](https://ieeexplore.ieee.org/document/9780577), Tao Li, Yaozheng Fang, Ye Lu\*, Jinni Yang, **Zhaolong Jian**, Zhiguo Wan, Yusen Li, **TPDS 2022** ![Static Badge](https://img.shields.io/badge/CCF_A-red)

### 2021

- [Sysnif: A log-based workflow construction method and performance measurement in intelligent IoT system](https://www.sciencedirect.com/science/article/pii/S0263224121010897), **Zhaolong Jian**, Zongming Jin, XueShuo Xie, Ye Lu\*, Guangying Li\*, Xinwei Chen, Thar Baker, **Measurement 2021** ![Static Badge](https://img.shields.io/badge/SCI_II-blue)
- [ATOM: Architectural Support and Optimization Mechanism for Smart Contract Fast Update and Execution in Blockchain-Based IoT](https://ieeexplore.ieee.org/document/9520821), Tao Li; Yaozheng Fang; **Zhaolong Jian**, Xueshuo Xie, Ye Lu\* and Guiling Wang, **IOTJ 2021** ![Static Badge](https://img.shields.io/badge/SCI_I-red)
- [Trusted-DNN: A TrustZone-based Adaptive Isolation Strategy for Deep Neural Networks](https://dl.acm.org/doi/10.1145/3472634.3472652), Zhuang Liu, Ye Lu\*, Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Tao Li, **ACM TURC 2021** ![Static Badge](https://img.shields.io/badge/Best_Paper_Award-red)
- [WIP: Sysnif: Constructing Workflow from Interleaved Logs in Intelligent IoT System](https://ieeexplore.ieee.org/document/9469470), Zongming Jin, Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Ye Lu\*, Guangying Li\*, **WoWMoM 2021** ![Static Badge](https://img.shields.io/badge/CCF_C-green)
- [Fast Policy Interpretation and Dynamic Conflict Resolution for Blockchain-Based IoT System](https://onlinelibrary.wiley.com/doi/10.1155/2021/9968743), Yaozheng Fang, **Zhaolong Jian**, Zongming Jin, Xueshuo Xie\*, Ye Lu, Tao Li, **WCMC 2021** ![Static Badge](https://img.shields.io/badge/CCF_C-green)

### 2020

- [Blockchain-driven Anomaly Detection Framework on Edge Intelligence](https://link.springer.com/article/10.1007/s42045-020-00044-9), Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Ye Lu\*, Tao Li\*, Guiling Wang, **CCF ToN 2020**

# 🥏 Interesting Repositories
- [CCF4DBLP: Retrieve papers from DBLP based on CCF ranting](https://github.com/JolyonJian/CCF4DBLP) ![Static Badge](https://img.shields.io/github/stars/JolyonJian/CCF4DBLP?style=social)
- [BC4SM: Blockchain-based secure messaging mechanism](https://github.com/JolyonJian/BC4SM) ![Static Badge](https://img.shields.io/github/stars/JolyonJian/BC4SM?style=social)
- [TxAnalysis: Analysis of popular Ethereum smart contracts](https://github.com/JolyonJian/tx-analysis) ![Static Badge](https://img.shields.io/github/stars/JolyonJian/tx-analysis?style=social)

# 🎖 Honors and Awards
- *2024.12* Second Prize in the 3th CCF Blockchain Competition.
- *2023.10* Nankai University Academic Competition Special Scholarship.
- *2023.10* Nankai University Gongneng Schoarship (the 2nd class).
- *2024.08* Second Prize in the 8th China College IC Competition.
- *2024.08* Third Prize in the 19th China Graduate Electronics Design Contest.
- *2024.07* Scholarship from China Scholarship Council (CSC).
- *2023.11* CIE Outstanding Paper Award (for TSC-VEE). 
- *2023.10* Nankai University Gongneng Schoarship (the 1st class). 
- *2023.09* Outstanding post-graduate of Nankai University (6/122).
- *2022.10* Nankai University Gongneng Schoarship. 
- *2021.10* Outstanding post-graduate of Nankai University (6/122).
- *2021.10* Nankai University Gongneng Schoarship (the 2nd class).
- *2020.10* Nankai University Gongneng Schoarship.

# 💬 Invited Talks
- *2022.11*, The work TSC-VEE is reported at the annual academic conference of Tianjin Key Laboratory of Network and Data Security Technology. 

# 💻 Internships
- *2023.03 - now*, Digital Health Center, Haihe Lab of ITAI. Distributed medical privacy computing system.
- *2022.07 - 2022.09*, Blockchain Platform Division, Ant Group. Smart contract programming language design for asset security.
