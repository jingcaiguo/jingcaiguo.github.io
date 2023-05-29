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

I am a Research Assistant Professor with Department of Computing, <a href = "https://www.polyu.edu.hk/comp/people/academic-staff/dr-guo-jingcai/">The Hong Kong Polytechnic University (香港理工大学)</a>, Hong Kong SAR, where I received my Ph.D. degree in early 2021. Prior to that, I received my M.Eng. degree (2015) from <a href = "https://www.waseda.jp/top/">Waseda University (早稻田大学)</a>, Japan, and B.Eng. degree (2013) from <a href = "http://en.scu.edu.cn/">Sichuan University (四川大学)</a>, China, all in Computer Science. From 2021 to 2022, I was an Associate Professor with School of Computing and Artificial Intelligence, <a href ="https://e.swufe.edu.cn/">SWUFE (西南财经大学)</a>, China, and from 2019 to 2020, I was a Visiting Researcher with School of Computer Science, <a href = "https://sydney.edu.au/">The University of Sydney (悉尼大学)</a>, Australia. 

I am generally interested in **Machine Learning** and **Edge AI**, with a particular focus on **Zero/Few-shot Learning**, **Federated Learning**, **Representation Learning**, and **Model Compression**. My ultimate goal is to build a generalized intelligent paradigm that can be learnt from limited resource in terms of both data and computing capability. I regularly serve as program committee member and/or reviewer for several conferences and journals such as AAAI, CVPR, NeurIPS, ACM-MM, ICML, ICCV, ICME, ECCV, TNNLS, TMM, TMC, TKDE, JSAC, IoT-J, etc. I am a member of IEEE and CCF. I am the recipient of RGC-HKPFS in 2017.


<span class='anchor' id='news'></span>
# 🔥 News
- ***<font color=red>TOP</font>***: &nbsp;🎉🎉 <font color=red>We have several openings for 1) Research Assistant, and 2) Visiting Student to work together on multiple research projects. Drop me an email along with your updated CV if interested</font>. 
- *2023.02*: &nbsp; [Review] Serve as a Reviewer for <a href="https://iccv2023.thecvf.com/">ICCV 2023</a> and <a href="https://nips.cc/">NeurIPS 2023</a>.
- *2022.11*: &nbsp; [Review] Serve as a Program Committee Member for <a href="https://cvpr2023.thecvf.com/">CVPR 2023</a> and Reviewer for <a href="https://iclr.cc/">ICLR 2023</a>.
- *2022.08*: &nbsp;  [Review] Serve as a Program Committee Member for <a href="https://aaai.org/Conferences/AAAI-23/">AAAI 2023</a>.
- *2022.07*: &nbsp; [Organization] Serve as a Session Chair for <a href="https://2022.ieeeicme.org/">ICME 2022</a>.
- *2022.04*: &nbsp;  [Review] Serve as a Program Committee Member for <a href="https://2022.acmmm.org/">ACM-MM 2022</a>.
- *2022.03*: &nbsp;  [Review] Serve as a Program Committee Member for <a href="https://neurips.cc/">NeurIPS 2022</a> and <a href="https://eccv2022.ecva.net/">ECCV 2022</a>.
- *2022.03*: &nbsp; [Organization] Serve as a Publicity Chair for <a href="https://srds-conference.org/">SRDS 2022</a>.
- *2022.01*: &nbsp;  [Review] Serve as a Reviewer for <a href="https://icml.cc/">ICML 2022</a>.
- *2021.10*: &nbsp; [Project] One project has been funded by <a href="https://www.edu.cn/rd/gai_kuang/zheng_ce_fa_gui/202112/t20211214_2189444.shtml">Fundamental Research Funds for the Central Universities</a>.
- *2021.12*: &nbsp;  [Review] Serve as a Program Committee Member for <a href="https://cvpr2022.thecvf.com/">CVPR 2022</a>.
- *2021.10*: &nbsp; [Project] One project has been funded by <a href="https://www.nsfc.gov.cn/">National Natural Science Foundation of China (NSFC)</a> 

<span class='anchor' id='publications'></span>
# 📝 Publications 
<!--
## 🎙 Five Most Representative Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/aaai23-zsl.png' alt="sym" width=255px></div></div>
<div class='paper-box-text' markdown="1">
[**Graph knows unknowns: Reformulate zero-shot learning as sample-level graph recognition,**](https://jingcai91.github.io/_pages/aaai23-zsl.pdf)

**<u><font size=3>J. Guo</font></u>**, S. Guo, Q. Zhou, Z. Liu, X. Lu, F. Huo,

In *Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence (AAAI, CCF-A)*, 2023.

**Contribution**: We are the first to investigate sample-level graph and formulate zero-shot learning to a graph-to-semantics matching task.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/cvpr23-mlzsl.png' alt="sym" width=350px></div></div>
<div class='paper-box-text' markdown="1">
[**$(ML)^2$P-Encoder: On Exploration of Channel-class Correlation for Multi-label Zero-shot Learning,**](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_ML2P-Encoder_On_Exploration_of_Channel-Class_Correlation_for_Multi-Label_Zero-Shot_Learning_CVPR_2023_paper.pdf)

Z. Liu, S. Guo, X. Lu, **<u><font size=3>J. Guo*</font></u>**, J. Zhang, Y. Zeng, F. Huo,

In *Proceedings of the Thirty-Fourth IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR, CCF-A)*, 2023.

**Contribution**: We first suggest the concept of channel-class correlation in multi-label zero-shot learning and design a channel-sensitive attention module $(ML)^2$ P-Encoder to extract and preserve channel-wise semantics.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/cvpr23-zsl.png' alt="sym" width=350px></div></div>
<div class='paper-box-text' markdown="1">
[**Decomposed Soft Prompt Guided Fusion Enhancing for Compositional Zero-Shot Learning,**](https://openaccess.thecvf.com/content/CVPR2023/papers/Lu_Decomposed_Soft_Prompt_Guided_Fusion_Enhancing_for_Compositional_Zero-Shot_Learning_CVPR_2023_paper.pdf)

X. Lu, S. Guo, Z. Liu, **<u><font size=3>J. Guo*</font></u>**,

In *Proceedings of the Thirty-Fourth IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR, CCF-A)*, 2023.

**Contribution**: We design a learnable soft prompt to construct the joint-representation of states and objects for compositional zero-shot learning, which can be more precisely decomposed than images.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2022</div><img src='images/ijcai22-fl.png' alt="sym" width=255px></div></div>
<div class='paper-box-text' markdown="1">
[**Personalized Federated Learning with Contextualized Generalization,**](https://www.ijcai.org/proceedings/2022/0311.pdf)

X. Tang, S. Guo, **<u><font size=3>J. Guo*</font></u>**,

In *Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence (IJCAI, CCF-A)*, 2022.

**Contribution**: We introduce a novel concept called contextualized generalization to provide each client with fine-grained context knowledge that can better fit the local data distributions and facilitate faster model convergence.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM-MM 2020</div><img src='images/mm20-sr.png' alt="sym" width=255px></div></div>
<div class='paper-box-text' markdown="1">
[**Dual-view Attention Networks for Single Image Super-Resolution,**](https://dl.acm.org/doi/10.1145/3394171.3413613)

**<u><font size=3>J. Guo</font></u>**, S. Ma, J. Zhang, Q. Zhou, S. Guo,

In *Proceedings of the Twenty-Eighth ACM International Conference on Multimedia (ACM-MM, CCF-A)*, 2020.

**Contribution**: We introduce the dual-view attention networks to improve the restoration ability of high-frequency information for CNNs-based single image super-resolution models that can obtain better quantitative performance along with more visually pleasing images.
</div>
</div>
-->

## 📚 Selected Papers
(* indicates corresponding author)

- [Graph Knows Unknowns: Reformulate Zero-Shot Learning as Sample-Level Graph Recognition](),<br>
  **<u><font size=3>J. Guo</font></u>**, S. Guo, Q. Zhou, Z. Liu, X. Lu, F. Huo,<br>
  In *Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence (**<font color=Blue>AAAI</font>**, CCF-A)*, 2023.

- [(ML)$^2$P-Encoder: On Exploration of Channel-Class Correlation for Multi-Label Zero-Shot Learning](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_ML2P-Encoder_On_Exploration_of_Channel-Class_Correlation_for_Multi-Label_Zero-Shot_Learning_CVPR_2023_paper.pdf),<br>
  Z. Liu, S. Guo, X. Lu, **<u><font size=3>J. Guo*</font></u>**, J. Zhang, Y. Zeng, F. Huo,<br>
  In *Proceedings of the Thirty-Fourth IEEE/CVF Conference on Computer Vision and Pattern Recognition (**<font color=Blue>CVPR</font>**, CCF-A)*, 2023.

- [Decomposed Soft Prompt Guided Fusion Enhancing for Compositional Zero-Shot Learning](https://openaccess.thecvf.com/content/CVPR2023/papers/Lu_Decomposed_Soft_Prompt_Guided_Fusion_Enhancing_for_Compositional_Zero-Shot_Learning_CVPR_2023_paper.pdf),<br>
  X. Lu, S. Guo\*, Z. Liu, **<u><font size=3>J. Guo*</font></u>**,<br>
  In *Proceedings of the Thirty-Fourth IEEE/CVF Conference on Computer Vision and Pattern Recognition (**<font color=Blue>CVPR</font>**, CCF-A)*, 2023.

- [Towards Data-Independent Knowledge Transfer in Model-Heterogeneous Federated Learning](),<br>
  J. Zhang, S. Guo\*, **<u><font size=3>J. Guo*</font></u>**, D. Zeng, J. Zhou, A. Zomaya,<br>
  *IEEE Transactions on Computers (**<font color=Blue>TC</font>**, CCF-A)*, 2023.
  
- [Hwamei: A Learning-Based Aggregation Framework for Hierarchical Federated Learning System](),<br>
  T. Qi, Y. Zhan, P. Li, **<u><font size=3>J. Guo</font></u>**, Y. Xia,<br>
  In *Proceedings of the Fouty-Third IEEE International Conference on Distributed Computing Systems (**<font color=Blue>ICDCS</font>**, CCF-B)*, 2023.

- [Towards Fairer and More Efficient Federated Learning via Multidimensional Personalized Edge Models](),<br>
  Y. Wang, **<u><font size=3>J. Guo</font></u>**, J. Zhang, S. Guo, W. Zhang, Q. Zheng,<br>
  In *Proceedings of the 2023 International Joint Conference on Neural Networks (**<font color=Blue>IJCNN</font>**, CCF-C)*, 2023.
  
- [Personalized Federated Learning with Contextualized Generalization](https://www.ijcai.org/proceedings/2022/0311.pdf),<br>
  X. Tang, S. Guo\*, **<u><font size=3>J. Guo*</font></u>**,<br>
  In *Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence (**<font color=Blue>IJCAI</font>**, CCF-A)*, 2022.

- [Towards Unbiased Multi-Label Zero-Shot Learning with Pyramid and Semantic Attention](),<br>
  Z. Liu, S. Guo\*, **<u><font size=3>J. Guo*</font></u>**, Y. Xu, F. Huo,<br>
  *IEEE Transactions on Multimedia (**<font color=Blue>TMM</font>**, 中科院1区/IF=8.182)*, 2022.

- [Conservative Novelty Synthesizing Network for Malware Recognition in an Open-Set Scenario](),<br>
  **<u><font size=3>J. Guo</font></u>**, S. Guo, S. Ma, Y. Sun, Y. Xu,<br>
  *IEEE Transactions on Neural Networks and Learning Systems (**<font color=Blue>TNNLS</font>**, 中科院1区/IF=14.255)*, 2021.

- [INT8 Training with Loss-Aware Compensation and Backward Quantization for Tiny On-Device Learning](),<br>
  Q. Zhou, S. Guo, Z. Qu, **<u><font size=3>J. Guo</font></u>**, Z. Xu, J. Zhang, T. Guo, B. Luo, J. Zhou,<br>
  In *Proceedings of the 202O USENIX Annual Technical Conference (**<font color=Blue>USENIX-ATC</font>**, CCF-A)*, 2021.

- [On-Device Learning Systems for Edge Intelligence: A Software and Hardware Synergy Perspective](),<br>
  Q. Zhou, Z. Qu, S. Guo, B. Luo, **<u><font size=3>J. Guo</font></u>**, Z. Xu, R. Akerkar,<br>
  *IEEE Internet of Things Journal (**<font color=Blue>IoT-J</font>**, 中科院1区/IF=10.238)*, 2021.
  
- [Dual-View Attention Networks for Single Image Super-Resolution](https://dl.acm.org/doi/10.1145/3394171.3413613),<br>
  **<u><font size=3>J. Guo</font></u>**, S. Ma, J. Zhang, Q. Zhou, S. Guo,<br>
  In *Proceedings of the Twenty-Eighth ACM International Conference on Multimedia (**<font color=Blue>ACM-MM</font>**, CCF-A)*, 2020.

- [A Novel Perspective to Zero-Shot Learning: Towards an Alignment of Manifold Structures via Semantic Feature Expansion](),<br>
  **<u><font size=3>J. Guo</font></u>**, S. Guo,<br>
  *IEEE Transactions on Multimedia (**<font color=Blue>TMM</font>**, 中科院1区/IF=8.182)*, 2020.

- [Adaptive Adjustment with Semantic Feature Space for Zero-Shot Recognition](),<br>
  **<u><font size=3>J. Guo</font></u>**, S. Guo,<br>
  In *Proceedings of the Forty-Fourth IEEE International Conference on Acoustics, Speech, and Signal Processing (**<font color=Blue>ICASSP</font>**, CCF-B)*, 2019.

- [EE-AE: An Exclusivity Enhanced Unsupervised Feature Learning Approach](),<br>
  **<u><font size=3>J. Guo</font></u>**, S. Guo,<br>
  In *Proceedings of the Forty-Fourth IEEE International Conference on Acoustics, Speech, and Signal Processing (**<font color=Blue>ICASSP</font>**, CCF-B)*, 2019.

- [AMS-SFE: Towards an Alignment of Manifold Structures via Semantic Feature Expansion for Zero-Shot Learning](),<br>
  **<u><font size=3>J. Guo</font></u>**, S. Guo,<br>
  In *Proceedings of the Twentieth IEEE International Conference on Multimedia and Expo (**<font color=Blue>ICME</font>**, CCF-B)*, 2019.

## 📖 Selected Books/Chapters

- [Application: Image-Based Visual Perception](),<br>
  **<u><font size=3>J. Guo</font></u>**, Z. Liu,<br>
  *Machine Learning on Commodity Tiny Devices*, edited by S. Guo&Q. Zhou, CRC Press, 2022.

<span class='anchor' id='grants'></span>
# 📝 Grants

- **<font color=Blue>[PI]:</font>** Start-Up Fund for RAPs under the Strategic Hiring Scheme,<br>
  Funding source: PolyU (UGC)-P0043932, 2022-2024.
  
- **<font color=Blue>[PI]:</font>** Entity Anti-fraud Prediction Combining Zero-Shot Learning and Graph Neural Networks,<br>
  Funding source: Young Scientists Fund of the National Natural Science Foundation of China (NSFC)-62102327, 2022-2024.

- **<font color=Blue>[PI]:</font>** Learning-Based Anti-Fraud Prevention in Financial Industry,<br>
  Funding source: Fundamental Research Funds for the Central Universities-JBK21YJ04, 2021-2021.

- \[Participant\]: Edge Intelligence Oriented Resource Management and Deployment Optimization,<br>
  Funding source: National Natural Science Foundation of China (NSFC)-61872310, 2019-2022.

- \[Participant\]: Research on Cloud Edge Collaborative Learning Architecture and Key Optimization Theory,<br>
  Funding source: Shenzhen Science and Technology Innovation Commission, Fundamental Research Project-JCYJ20200109142008673, 2021-2023.

- \[Participant\]: Transnational Partnership for Excellent Research and Education in Big Data and Emergency Management,<br>
  Funding source: Norwegian Research Council INTPART Programme, 2017-2020.

<!--
<span class='anchor' id='invited-talks'></span>
# 💬 Invited Talks
-->

<span class='anchor' id='teachings'></span>
# 📝 Teachings

- Subject Lecturer, Data Structures and Database Systems, PolyU, Spring 2023.
- Subject Lecturer, Data Structures (Syllabus), SWUFE, Fall 2021.
- Teaching Assistant, B2B & B2C E-commerce and Management, PolyU, Spring 2019
- Teaching Assistant, Information Systems Project Management, PolyU, Fall 2018.
- Teaching Assistant, Big Data Analytics, PolyU, Spring 2018.
- Teaching Assistant, Web Advertising and Web Publishing, PolyU, Fall 2017.

<span class='anchor' id='services'></span>
# 📝 Services

## 📖 Conference Organizing Committee

- **Publicity Chair:** The 41st International Symposium on Reliable Distributed Systems (SRDS 2022)
- **Session Chair:** The 23th IEEE International Conference on Multimedia and Expo (ICME 2022)

## 📖 Conference PC Member/Reviewer

- AAAI Conference on Artificial Intelligence (**AAAI**: 2021 / 2022 / 2023)
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**: 2022 / 2023)
- Conference on Neural Information Processing Systems (**NeurIPS**: 2022 / 2023)
- International Conference on Computer Vision (**ICCV**: 2023)
- International Conference on Learning Representations (**ICLR**: 2023)
- ACM International Conference on Multimedia (**ACM-MM**: 2022)
- International Conference on Machine Learning (**ICM**L: 2022)
- European Conference on Computer Vision (**ECCV**: 2022)
- IEEE International Conference on Multimedia and Expo (**ICME**: 2019 / 2020 / 2021)
- International Joint Conference on Neural Networks (**IJCNN**: 2022)
- IEEE International Conference on Big Data Intelligence and Computing (**DataCom**: 2018)

## 📖 Journal Reviewer

- Reviewer for IEEE Transactions on Neural Networks and Learning Systems (**IEEE TNNLS**)
- Reviewer for IEEE Transactions on Multimedia (**IEEE TMM**)
- Reviewer for IEEE Transactions on Knowledge and Data Engineering (**IEEE TKDE**)
- Reviewer for IEEE Transactions on Mobile Computing (**IEEE TMC**)
- Reviewer for IEEE Journal on Selected Areas in Communications (**IEEE JSAC**)
- Reviewer for IEEE Internet of Things Journal (**IEEE IoTJ**)
- Reviewer for IEEE Transactions on Industrial Informatics (**IEEE TII**)
- Reviewer for IEEE Transactions on Emerging Topics in Computing (**IEEE TETC**)

## 📖 Editorial Board Member

- Progress in Human Computer Interaction (Jun. 2018-Jun. 2020)

<span class='anchor' id='selected-honors'></span>
# 🎖 Selected Honors
- **Hong Kong Ph.D. Fellowship (2017),**<br>
  Funding source: Hong Kong Research Grants Council (acceptance rate ~= 1.7%, 231 out of 14000).

- **Ting Hsing International Scholarship (2013),**<br>
  Funding source: Waseda University and Ting Hsin Holding Corp. (acceptance rate ~= 4.2%, 85 out of 2000).

<span class='anchor' id='sponsors'></span>
# 📝 Sponsors

I sincerely thank these sponsors for providing support for my research:<br>

<img src="./images/nsfc.jpeg" width = "250" />
<img src="./images/RGC.jpg" width = "150" />
<img src="./images/polyu.jpg" width = "130" />
<img src="./images/waseda1.jpg" width = "200" />
<img src="./images/nvidia.png" width = "150" />
<img src="./images/tinghsing.jpeg" width = "130" />  
<div style="display:inline-block;width:5px;"><script type="text/javascript" src="//rf.revolvermaps.com/0/0/7.js?i=0hdmm10vwtf&amp;m=1&amp;c=ff0000&amp;cr1=ffffff&amp;sx=0&amp;ds=35" async="async"></script></div>
