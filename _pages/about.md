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

I am an Assistant Professor (Research) with Department of Computing, <a href = "https://www.polyu.edu.hk/comp/people/academic-staff/dr-guo-jingcai/">The Hong Kong Polytechnic University</a>, Hong Kong SAR, where I received my Ph.D. degree in early 2021. Prior to that, I received my M.Eng. degree (2015) from <a href = "https://www.waseda.jp/top/">Waseda University</a>, Japan, and B.Eng. degree (2013) from <a href = "http://en.scu.edu.cn/">Sichuan University</a>, China, all in Computer Science. From 2021 to 2022, I was an Associate Professor with School of Computing and Artificial Intelligence, <a href ="https://e.swufe.edu.cn/">SWUFE</a>, China, and from 2019 to 2020, I was a Visiting Researcher with School of Computer Science, <a href = "https://sydney.edu.au/">The University of Sydney</a>, Australia. 

I am generally interested in **Machine Learning** and **Edge AI**, with a particular focus on **Zero/Few-shot Learning**, **Federated Learning**, **Representation Learning**, and **Model Compression**. I regularly serve as program committee member and/or reviewer for several conferences and journals such as AAAI, CVPR, NeurIPS, ACM-MM, ICML, ICCV, ICME, ECCV, TNNLS, TMM, TMC, TKDE, JSAC, IoT-J, etc. I am a member of IEEE and CCF. I am the recipient of RGC-HKPFS in 2017.


# 🔥 News
- ***<font color=red>TOP</font>***: &nbsp;🎉🎉 We have several openings for 1) **PhD Student**, 2) **Research Assistant / Associate**, and 3) **Visiting Student** to work together on multiple research projects. Drop me an email along with your updated CV if interested. 
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

# 📝 Publications 

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

## 📚 Other Selected Papers 

- ``TC 2023`` J. Zhang, S. Guo, **<u><font size=3>J. Guo*</font></u>**, D. Zeng, J. Zhou, A. Zomaya, ["Towards Data-independent Knowledge Transfer in Model-heterogeneous Federated Learning",](https://ieeexplore.ieee.org/abstract/document/10115052), *IEEE Transactions on Computers (IEEE TC, CCF-A)*, 2023.

- ``ICDCS 2023`` T. Qi, Y. Zhan, P. Li, **<u><font size=3>J. Guo</font></u>**, Y. Xia, [Hwamei: A Learning-based Aggregation Framework for Hierarchical Federated Learning System](), In *Proceedings of the Fouty-Third IEEE International Conference on Distributed Computing Systems (ICDCS, CCF-B)*, 2023.

- ``IJCNN 2023`` Y. Wang, **<u><font size=3>J. Guo</font></u>**, J. Zhang, S. Guo, W. Zhang, Q. Zheng, [Towards Fairer and More Efficient Federated Learning via Multidimensional Personalized Edge Models](), In *Proceedings of the 2023 International Joint Conference on Neural Networks (IJCNN, CCF-C)*, 2023.

- ``TMM 2023`` Z. Liu, S. Guo, **<u><font size=3>J. Guo*</font></u>**, Y. Xu, F. Huo, [Towards Unbiased Multi-label Zero-Shot Learning with Pyramid and Semantic Attention](), *IEEE Transactions on Multimedia (IEEE TMM, 中科院1区/IF=8.182)*, 2022.

- ``TNNLS 2023`` **<u><font size=3>J. Guo</font></u>**, S. Guo, S. Ma, Y. Sun, Y. Xu, [Conservative Novelty Synthesizing Network for Malware Recognition in an Open-set Scenario](), *IEEE Transactions on Neural Networks and Learning Systems (IEEE TNNLS, 中科院1区/IF=14.255)*, 2021.

- ``USENIX-ATC 2021`` Q. Zhou, S. Guo, Z. Qu, **<u><font size=3>J. Guo</font></u>**, Z. Xu, J. Zhang, T. Guo, B. Luo, J. Zhou, [INT8 Training with Loss-aware Compensation and Backward Quantization for Tiny On-device Learning](), IN *Proceedings of the 202O USENIX Annual Technical Conference (USENIX-ATC, CCF-A)*, 2021.

- ``IoT-J 2021`` Q. Zhou, Z. Qu, S. Guo, B. Luo, **<u><font size=3>J. Guo</font></u>**, Z. Xu, R. Akerkar, [On-device Learning Systems for Edge Intelligence: A Software and Hardware Synergy Perspective](), *IEEE Internet of Things Journal (IEEE IoT-J, 中科院1区/IF=10.238)*, 2021.

- ``TMM 2020`` **<u><font size=3>J. Guo</font></u>**, S. Guo, [A Novel Perspective to Zero-shot Learning: Towards an Alignment of Manifold Structures via Semantic Feature Expansion](), *IEEE Transactions on Multimedia (IEEE TMM, 中科院1区/IF=8.182)*, 2020.

- ``ICASSP 2019`` **<u><font size=3>J. Guo</font></u>**, S. Guo, [Adaptive Adjustment with Semantic Feature Space for Zero-Shot Recognition](), In *Proceedings of the Forty-Fourth IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP, CCF-B)*, 2019.

- ``ICASSP 2019`` **<u><font size=3>J. Guo</font></u>**, S. Guo, [EE-AE: An Exclusivity Enhanced Unsupervised Feature Learning Approach](), In *Proceedings of the Forty-Fourth IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP, CCF-B)*, 2019.

- ``ICME 2019`` **<u><font size=3>J. Guo</font></u>**, S. Guo, [AMS-SFE: Towards an Alignment of Manifold Structures via Semantic Feature Expansion for Zero-shot Learning](), In *Proceedings of the Twentieth IEEE International Conference on Multimedia and Expo (ICME, CCF-B)*, 2019.

## 📖 Selected Books/Chapters

- ``CRC Press`` **<u><font size=3>J. Guo</font></u>**, Z. Liu, [Application: Image-Based Visual Perception](), *Machine Learning on Commodity Tiny Devices*, edited by S. Guo&Q. Zhou, CRC Press, 2022.


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
