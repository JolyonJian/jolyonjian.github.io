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

Aloha threr! I am a 3rd year Ph.D. candidate at College of Computer Science of Nankai University, advised by Prof. Tao Li. I am affliated with Nankai Intelligent Computing System (ICS) Lab and Haihe Lab of ITAI. 

I will be a visiting scholar at Nanyang Technological University (NTU) supervised by [Prof. Weichen Liu](https://personal.ntu.edu.sg/liu/) with the sponsorship of China Scholarship Council (CSC) for 12 months, from 16th March 2025 to 15 March 2026. 

My research interest includes intelligent computing system, system security, and trusted execution environment. I have published 12 papers at the top international journals and conferences with total <a href='https://scholar.google.com/citations?user=LCsCUrMAAAAJ'>google scholar citations <strong><span id='total_cit'>50+</span></strong></a> <a href='https://scholar.google.com/citations?user=LCsCUrMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

Here is my resume: [\[CV-en\]](http://www.jolyonjian.fun/files/cv-en.pdf) [\[CV-cn\]](http://www.jolyonjian.fun/files/cv-cn.pdf)

# 📖 Educations
- *2022.09 - now*, College of Computer Science, Nankai University. 
Successive master-doctor program (Ph.D. student phase) in Computer Science.
Research fields: Trusted execution environment, Confidential computing.
- *2020.09 - 2022.06*, College of Computer Science, Nankai University. 
Successive master-doctor program (Master student phase) in Computer Science.
Research fields: Trusted execution environment, Smart contract virtual machine.
- *2016.09 - 2020.06*, College of Cyber Science, Nankai University.
B.Eng. in Internet of Things Engineering.
Bachelor’s degree program.

# 🔥 News
- *2024.08*: We accepted media interviews on behalf of the 8 participating teams in the Phytium track at the 19th China Graduate Electronics Design Contest. [\[Video\]](http://www.jolyonjian.fun/files/interview.mp4)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPDS 2023</div><img src='images/tscvee.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TSC-VEE: A TrustZone-Based Smart Contract Virtual Execution Environment](http://www.jolyonjian.fun/files/tscvee.pdf)

**Zhaolong Jian**, Ye Lu*, Youyang Qiao, Yaozheng Fang, Xueshuo Xie, Dayi Yang, Zhiyuan Zhou, and Tao Li

[**Project**](https://github.com/nkicsl/TSC-VEE) ![Static Badge](https://img.shields.io/github/stars/nkicsl/TSC-VEE?style=social) <strong><span class='show_paper_citations' data='LCsCUrMAAAAJ:WF5omc3nYNoC'></span></strong>
- TSC-VEE is the first virtual execution environment for Solidity smart contract on ARM TrustZone.
- TSC-VEE contributed the first evm implemented in pure C language in the community.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SPE 2023</div><img src='images/drs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DRS: A deep reinforcement learning enhanced Kubernetes scheduler for microservice-based system](http://www.jolyonjian.fun/files/drs.pdf)

**Zhaolong Jian**, Xueshuo Xie, Yaozheng Fang, Yibing Jiang, Ye Lu, Ankan Dash, Tao Li*, and Guiling Wang

[**Project**](https://github.com/JolyonJian/DRS) ![Static Badge](https://img.shields.io/github/stars/JolyonJian/DRS?style=social) <strong><span class='show_paper_citations' data='LCsCUrMAAAAJ:YsMSGLbcyi4C'></span></strong>
- DRS uses the DQN algorithm to enhance the native scheduler of Kubernetes.
- DRS provides a good implementation reference for Kubernetes scheduling optimization.
</div>
</div>

**Publications List: 12 papers totally**

### 2024

- [Memory-Efficient and Secure DNN Inference on TrustZone-enabled Consumer IoT Devices](http://www.jolyonjian.fun/files/tinylib.pdf), Xueshuo Xie, Haoxu Wang, **Zhaolong Jian**, Tao Li\*, Wei Wang, Zhiwei Xu, and Guiling Wang, **INFOCOM 2024** ![Static Badge](https://img.shields.io/badge/CCF_A-red)

### 2023

- [DRS: A deep reinforcement learning enhanced Kubernetes scheduler for microservice-based system](http://www.jolyonjian.fun/files/drs.pdf), **Zhaolong Jian**, Xueshuo Xie, Yaozheng Fang, Yibing Jiang, Ye Lu, Ankan Dash, Tao Li\*, and Guiling Wang, **SPE 2023** ![Static Badge](https://img.shields.io/badge/CCF_B-blue)
- [TSC-VEE: A TrustZone-Based Smart Contract Virtual Execution Environment](http://www.jolyonjian.fun/files/tscvee.pdf), **Zhaolong Jian**, Ye Lu\*, Youyang Qiao, Yaozheng Fang, Xueshuo Xie, Dayi Yang, Zhiyuan Zhou, and Tao Li, **TPDS 2023** ![Static Badge](https://img.shields.io/badge/CCF_A-red)
- [Block-gram: mining knowledgeable features for efficiently smart contract vulnerability detection](http://www.jolyonjian.fun/files/dcn.pdf), Xueshuo Xie, Haolong Wang, **Zhaolong Jian**, Yaozheng Fang, Zichun Wang, and Tao Li\*, **DCN 2023** ![Static Badge](https://img.shields.io/badge/SCI_II-blue)
- [Block-gram: Mining Knowledgeable Features for Smart Contract Vulnerability Detection](http://www.jolyonjian.fun/files/smartcom.pdf), Tao Li, Haolong Wang, Yaozheng Fang, **Zhaolong Jian**, Zichun Wang, and Xueshuo Xie\*, **SmartCom 2022** ![Static Badge](https://img.shields.io/badge/EI-green)

### 2022

- [SmartVM: A Smart Contract Virtual Machine for Fast On-Chain DNN Computations](http://www.jolyonjian.fun/files/smartvm.pdf), Tao Li, Yaozheng Fang, Ye Lu\*, Jinni Yang, **Zhaolong Jian**, Zhiguo Wan, Yusen Li, **TPDS 2022** ![Static Badge](https://img.shields.io/badge/CCF_A-red)

### 2021

- [Sysnif: A log-based workflow construction method and performance measurement in intelligent IoT system](http://www.jolyonjian.fun/files/sysnif.pdf), **Zhaolong Jian**, Zongming Jin, XueShuo Xie, Ye Lu\*, Guangying Li\*, Xinwei Chen, Thar Baker, **Measurement 2021** ![Static Badge](https://img.shields.io/badge/SCI_II-blue)
- [ATOM: Architectural Support and Optimization Mechanism for Smart Contract Fast Update and Execution in Blockchain-Based IoT](http://www.jolyonjian.fun/files/atom.pdf), Tao Li; Yaozheng Fang; **Zhaolong Jian**, Xueshuo Xie, Ye Lu\* and Guiling Wang, **IOTJ 2021** ![Static Badge](https://img.shields.io/badge/SCI_I-red)
- [Trusted-DNN: A TrustZone-based Adaptive Isolation Strategy for Deep Neural Networks](http://www.jolyonjian.fun/files/trusteddnn.pdf), Zhuang Liu, Ye Lu\*, Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Tao Li, **ACM TURC 2021** ![Static Badge](https://img.shields.io/badge/Best_Paper_Award-red)
- [WIP: Sysnif: Constructing Workflow from Interleaved Logs in Intelligent IoT System](http://www.jolyonjian.fun/files/wip.pdf), Zongming Jin, Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Ye Lu\*, Guangying Li\*, **WoWMoM 2021** ![Static Badge](https://img.shields.io/badge/CCF_C-green)
- [Fast Policy Interpretation and Dynamic Conflict Resolution for Blockchain-Based IoT System](http://www.jolyonjian.fun/files/fpicr.pdf), Yaozheng Fang, **Zhaolong Jian**, Zongming Jin, Xueshuo Xie\*, Ye Lu, Tao Li, **WCMC 2021** ![Static Badge](https://img.shields.io/badge/CCF_C-green)

### 2020

- [Blockchain-driven anomaly detection framework on edge intelligence](http://www.jolyonjian.fun/files/ton.pdf), Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Ye Lu\*, Tao Li\*, Guiling Wang, **CCF ToN 2020**


# 🎖 Honors and Awards
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
- *2023.03 - now*, Haihe Lab of ITAI, Digital Health Center. Distributed medical privacy computing system.
- *2022.07 - 2022.09*, Blockchain Platform Division, Ant Group. Smart contract programming language design for asset security.
