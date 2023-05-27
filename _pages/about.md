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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech: Fast, Robust and Controllable Text to Speech](https://papers.nips.cc/paper/8580-fastspeech-fast-robust-and-controllable-text-to-speech.pdf) \\
**Yi Ren**, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- FastSpeech is the first fully parallel end-to-end speech synthesis model.
- **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet). Our work are promoted by more than 20 media and forums, such as [机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu).
- **Industry Impact**: FastSpeech has been deployed in [Microsoft Azure TTS service](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911) and supports 49 more languages with state-of-the-art AI quality. It was also shown as a text-to-speech system acceleration example in [NVIDIA GTC2020](https://resources.nvidia.com/events/GTC2020s21420).
</div>
</div>



## 📚 Other Selected Papers 


















- ``AAAI 2023`` **<u>J. Guo</u>**, S. Guo, Q. Zhou, Z. Liu, X. Lu, F. Huo, "Graph knows unknowns: Reformulate zero-shot learning as sample-level graph recognition," In *Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence (AAAI, CCF-A),* 2023.

- ``CVPR 2023`` Z. Liu, S. Guo, X. Lu, **<u>J. Guo*</u>**, J. Zhang, Y. Zeng, F. Huo, "$(ML)^2$ P-Encoder: On Exploration of Channel-class Correlation for Multi-label Zero-shot Learning," In *Proceedings of Computer Vision and Pattern Recognition (CVPR, CCF-A)*, 2023.

- ``CVPR 2023`` X. Lu, S. Guo*, Z. Liu, **<u>J. Guo*</u>**, "Decomposed Soft Prompt Guided Fusion Enhancing for Compositional Zero-Shot Learning," In *Proceedings of Computer Vision and Pattern Recognition (CVPR, CCF-A)*, 2023. 

- <font style="background: #FF00BB">``AAAI 2023``</font> **<u>J. Guo</u>**, S. Guo, Q. Zhou, Z. Liu, X. Lu, F. Huo, "Graph knows unknowns: Reformulate zero-shot learning as sample-level graph recognition," In *Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence (AAAI, CCF-A),* 2023.


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
