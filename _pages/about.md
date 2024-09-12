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

I will soon become a visiting scholar at Nanyang Technological University (NTU) supervised by Prof. Weichen Liu with the sponsorship of China Scholarship Council (CSC). 

My research interest includes intelligent computing system, system security, and trusted execution environment. I have published more than 10 papers at the top international journals and conferences with total <a href='https://scholar.google.com/citations?user=LCsCUrMAAAAJ'>google scholar citations <strong><span id='total_cit'>67+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=LCsCUrMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

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
- *2024.08*: We accepted media interviews on behalf of the 8 participating teams in the Feiteng track at the 19th China Graduate Electronics Design Contest. [\[Video\]](http://www.jolyonjian.fun/files/interview.mp4)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPDS 2023</div><img src='images/tscvee.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TSC-VEE: A TrustZone-Based Smart Contract Virtual Execution Environment]([https://ieeexplore.ieee.org/document/10094016](https://www.jolyonjian.fun/files/tscvee.pdf))

**Zhaolong Jian**, Ye Lu*, Youyang Qiao, Yaozheng Fang, Xueshuo Xie, Dayi Yang, Zhiyuan Zhou, and Tao Li

[**Project**](https://github.com/nkicsl/TSC-VEE) <strong><span class='show_paper_citations' data='LCsCUrMAAAAJ:YsMSGLbcyi4C'></span></strong>
- TSC-VEE is the first virtual execution environment for Solidity smart contract on ARM TrustZone.
- TSC-VEE contributed the first evm implemented in pure C language in the community.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SPE 2023</div><img src='images/drs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DRS: A deep reinforcement learning enhanced Kubernetes scheduler for microservice-based system](https://www.jolyonjian.fun/files/drs.pdf)

**Zhaolong Jian**, Xueshuo Xie, Yaozheng Fang, Yibing Jiang, Ye Lu, Ankan Dash, Tao Li*, and Guiling Wang

[**Project**](https://github.com/JolyonJian/DRS) <strong><span class='show_paper_citations' data='LCsCUrMAAAAJ:WF5omc3nYNoC'></span></strong>
- DRS uses the DQN algorithm to enhance the native scheduler of Kubernetes.
- DRS provides a good implementation reference for Kubernetes scheduling optimization.
</div>
</div>

**Total List: 12**

- [Memory-Efficient and Secure DNN Inference on TrustZone-enabled Consumer IoT Devices](https://www.jolyonjian.fun/files/tinylib.pdf), Xueshuo Xie, Haoxu Wang, **Zhaolong Jian**, Tao Li\*, Wei Wang, Zhiwei Xu, and Guiling Wang, **INFOCOM 2024**
- [DRS: A deep reinforcement learning enhanced Kubernetes scheduler for microservice-based system](https://www.jolyonjian.fun/files/drs.pdf), **Zhaolong Jian**, Xueshuo Xie, Yaozheng Fang, Yibing Jiang, Ye Lu, Ankan Dash, Tao Li\*, and Guiling Wang, **SPE 2023**
- [TSC-VEE: A TrustZone-Based Smart Contract Virtual Execution Environment]([https://ieeexplore.ieee.org/abstract/document/10094016](https://www.jolyonjian.fun/files/tscvee.pdf)), **Zhaolong Jian**, Ye Lu\*, Youyang Qiao, Yaozheng Fang, Xueshuo Xie, Dayi Yang, Zhiyuan Zhou, and Tao Li, **TPDS 2023**
- [Block-gram: mining knowledgeable features for efficiently smart contract vulnerability detection](https://www.sciencedirect.com/science/article/pii/S2352864823001347), Xueshuo Xie, Haolong Wang, **Zhaolong Jian**, Yaozheng Fang, Zichun Wang, and Tao Li\*, **DCN 2023**
- [Block-gram: Mining Knowledgeable Features for Smart Contract Vulnerability Detection](https://link.springer.com/chapter/10.1007/978-3-031-28124-2_52), Tao Li, Haolong Wang, Yaozheng Fang, **Zhaolong Jian**, Zichun Wang, and Xueshuo Xie\*, **SmartCom 2022**
- [SmartVM: A Smart Contract Virtual Machine for Fast On-Chain DNN Computations](https://www.jolyonjian.fun/files/smartvm.pdf), Tao Li, Yaozheng Fang, Ye Lu\*, Jinni Yang, **Zhaolong Jian**, Zhiguo Wan, Yusen Li, **TPDS 2022**
- [Sysnif: A log-based workflow construction method and performance measurement in intelligent IoT system](https://www.jolyonjian.fun/files/sysnif.pdf), **Zhaolong Jian**, Zongming Jin, XueShuo Xie, Ye Lu\*, Guangying Li\*, Xinwei Chen, Thar Baker, **Measurement 2021**
- [ATOM: Architectural Support and Optimization Mechanism for Smart Contract Fast Update and Execution in Blockchain-Based IoT](https://www.jolyonjian.fun/files/atom.pdf), Tao Li; Yaozheng Fang; **Zhaolong Jian**, Xueshuo Xie, Ye Lu\* and Guiling Wang, **IOTJ 2021**
- [Trusted-DNN: A TrustZone-based Adaptive Isolation Strategy for Deep Neural Networks](https://www.jolyonjian.fun/files/trusteddnn.pdf), Zhuang Liu, Ye Lu\*, Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Tao Li, **ACM TURC 2021**
- [WIP: Sysnif: Constructing Workflow from Interleaved Logs in Intelligent IoT System](https://ieeexplore.ieee.org/abstract/document/9469470), Zongming Jin, Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Ye Lu\*, Guangying Li\*, **WoWMoM 2021**
- [Fast Policy Interpretation and Dynamic Conflict Resolution for Blockchain-Based IoT System](https://onlinelibrary.wiley.com/doi/full/10.1155/2021/9968743), Yaozheng Fang, **Zhaolong Jian**, Zongming Jin, Xueshuo Xie\*, Ye Lu, Tao Li, **WCMC 2021**
- [Blockchain-driven anomaly detection framework on edge intelligence](https://www.jolyonjian.fun/files/ton.pdf), Xueshuo Xie, Yaozheng Fang, **Zhaolong Jian**, Ye Lu\*, Tao Li\*, Guiling Wang, **CCF ToN 2020**


# 🎖 Honors and Awards
- *2024.08* Second Prize in the 8th China College IC Competition.
- *2024.08* Third Prize in the 19th China Graduate Electronics Design Contest.
- *2024.07* Scholarship from China Scholarship Council (CSC).
- *2023.11* CIE Outstanding Paper Award (for TSC-VEE). 
- *2023.10* Nankai University Gongneng Scoarship (the 1st class). 
- *2023.09* Outstanding post-graduate of Nankai University (6/122).
- *2022.10* Nankai University Gongneng Scoarship. 
- *2021.10* Outstanding post-graduate of Nankai University (6/122).
- *2021.10* Nankai University Gongneng Scoarship (the 2nd class).
- *2021.10* Nankai University Gongneng Scoarship.

# 💬 Invited Talks
- *2022.11*, The work TSC-VEE is reported at the annual academic conference of Tianjin Key Laboratory of Network and Data Security Technology. 

# 💻 Internships
- *2022.07 - 2022.09*, Blockchain Platform Division, Ant Group.
