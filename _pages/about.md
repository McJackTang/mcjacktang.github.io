---
permalink: /
title: ""
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

-  I am a student researcher at Tsinghua University🎓. I am now a member of [Pervasive HCI Group](https://pi.cs.tsinghua.edu.cn/), advised by Prof. Yuanchun Shi, A/Prof. Yuntao Wang, and Prof. Yingqing Xu. I have done research in the [Department of Computer Science and Technology](https://www.cs.tsinghua.edu.cn/csen/), [Global Innovation Exchange](https://gix.uw.edu/), [Future Lab](https://thfl.tsinghua.edu.cn/en/), and [School of Vehicle and Mobility](http://www.svm.tsinghua.edu.cn/). I was a researcher at Tsinghua-Toyota AI Center and an intern at [Zhipu AI](https://www.zhipuai.cn/en/) ChatGLM Group. I enjoy working with academia and industry.

- 🔭 My research interests include `Remote Physiological Sensing`, `Pervasive Computing`, `Human-Computer Interaction(HCI)`, `Large Language Model`, and `Computer Vision`. I’m currently working on Biosensing, HCI, and LLM.  
 
- 📫 Reach me through `tjk19@mails.tsinghua.edu.cn` if interested.  

<a href='https://scholar.google.com/citations?user=SCHOLAR_ID&user=_jENFHIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
**2024.2:** 🎉🎉 Our paper [A Comprehensive Dataset and Automated Pipeline for Nailfold Capillary Analysis](https://doi.org/10.48550/arXiv.2312.05930) has been accepted by [ISBI 2024](https://biomedicalimaging.org/2024/).

**2023.12:** 🎉🎉 Awarded **Best Presentation** at Tsinghua University Initiative Scientific Research Program Forum.

**2023.11:** Attended the AI Health Summit 2023 held in Singapore and posted a [poster](https://arxiv.org/abs/2311.12524) about AnomaLous Physiological Health Assessment Using Large Language Models. 

**2023.11:** 🎉🎉 Hosting a research project on non-contact physiological indication perception based on camera technology, awarded funding by the **Beijing Natural Science Foundation**.

**2023.10:** 🎉🎉 Awarded **National Scholarship** by Ministry of Education!

**2023.10:** 🎉🎉 Our paper addressed [rPPG Toolbox](https://arxiv.org/abs/2210.00716) has been accepted by [NeurIPS 2023](https://neurips.cc/).

**2023.7:** Attended the [EMBC 2023](https://embc.embs.org/2023/)  and gave an [oral presentation](https://arxiv.org/abs/2302.03840) about new comprehensive rPPG dataset. 

**2023.3:** 🎉🎉 Our paper addressed [Privacy-Friendly Gait Date Acquisition and Emotion Recognition]([https://arxiv.org/abs/2210.00716](https://kns.cnki.net/kcms2/article/abstract?v=ebrKgZyeBkxJAkKmLRGB8ZBzoL0_JE1z5CJDrfO0vn9sAN5P7cZCI7TMzal9BZkSQQ-tNRL5sj5jZJV8Erzh5u0t4amz6h_o_KdkPSubDPVnvkfMkClSYlPa5iaNSWFktEGmXFOfGWIXzhFL20NQyw==&uniplatform=NZKPT&language=CHS)) has been accepted by [JCAD](https://www.jcad.cn/).

# 📝 Publications 
#### JOURNAL PUBLICATIONS


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NN</div><img src='../images/NN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Spiking-PhysFormer: Camera-Based Remote Photoplethysmography with Parallel Spike-driven Transformer

Mingxuan Liu\*, **Jiankai Tang\*** (\*Co-first Author), Haoxiang Li, Jiahao Qi, Siwei Li, Kegang Wang, Yuntao Wang, Hong Chen

Neural Networks, Under Review

<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2402.04798" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCAD</div><img src='../images/GaitEmotion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## A Method of Privacy-Friendly Gait Data Acquisition and Emotion Recognition

Hong Xiao, **Jiankai Tang**, Christine Qiu, Xinyi Fu

[JCAD](https://www.jcad.cn/)

<div class="extra-links">
    <a class="_blank" href="https://kns.cnki.net/kcms2/article/abstract?v=ebrKgZyeBkxJAkKmLRGB8ZBzoL0_JE1z5CJDrfO0vn9sAN5P7cZCI7TMzal9BZkSQQ-tNRL5sj5jZJV8Erzh5u0t4amz6h_o_KdkPSubDPVnvkfMkClSYlPa5iaNSWFktEGmXFOfGWIXzhFL20NQyw==&uniplatform=NZKPT&language=CHS" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
</div>

</div>
</div>

#### CONFERENCE PUBLICATIONS

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISBI 2024</div><img src='../images/Nailfold.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## A Comprehensive Dataset and Automated Pipeline for Nailfold Capillary Analysis

Linxi Zhao, **Jiankai Tang**, Dongyu Chen, Xiaohong Liu, Yong Zhou, Guangyu Wang, Yuntao Wang

[ISBI 2024]([https://healthsummit.ai/main/abstracts/](https://biomedicalimaging.org/2024/)). 

<div class="extra-links">
    <a class="_blank" href="arxiv.org/abs/2312.05930" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
      <a class="_blank" href="https://github.com/THU-CS-PI-LAB/ANFC-Automated-Nailfold-Capillary">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='../images/LongBench.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding

Yushi Bai, Xin Lv, Jiajie Zhang, Hongchang Lyu, **Jiankai Tang**, Zhidian Huang, Zhengxiao Du, Xiao Liu, Aohan Zeng, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li

ArXiv

<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2308.14508" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
      <a class="_blank" href="https://github.com/THUDM/LongBench">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AI Health Summit 2023</div><img src='../images/Alpha.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## ALPHA: AnomaLous Physiological Health Assessment Using Large Language Models

**Jiankai Tang**, Kegang Wang, Hongming Hu, Xiyuxing Zhang, Peiyu Wang, Xin Liu, Yuntao Wang

[AI Health Summit 2023](https://healthsummit.ai/main/abstracts/). 

<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2311.12524" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
      <a class="_blank" href="https://github.com/McJackTang/LLM-HealthAssistant">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMBC 2023</div><img src='../images/MMPD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## MMPD: Multi-Domain Mobile Video Physiology Dataset

**Jiankai Tang**, Kequan Chen, Yuntao Wang, Yuanchun Shi, Shwetak Patel, Daniel McDuff, Xin Liu

[IEEE EMBC 2023](https://embc.embs.org/2023/) (Oral)
<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2302.03840" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
    <a class="_blank" href="https://github.com/McJackTang/MMPD_rPPG_dataset">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='../images/Toolbox.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## rPPG-Toolbox: Deep Remote PPG Toolbox

Xin Liu, Girish Narayanswamy, Akshay Paruchuri, Xiaoyu Zhang, **Jiankai Tang**, Yuzhe Zhang, Yuntao Wang, Soumyadip Sengupta, Shwetak Patel, Daniel McDuff

[NeurIPS 2023](https://neurips.cc/)

<div class="extra-links">
    <a class="_blank" href="https://arxiv.org/abs/2210.00716" >
        <i class="fas fa-newspaper" aria-hidden="true"></i> Paper
    </a>
    <a class="_blank" href="https://github.com/ubicomplab/rPPG-Toolbox">
        <i class="ai ai-open-access ai-1x" aria-hidden="true"></i> Code
    </a>
</div>

</div>
</div>



# 🎖 Honors and Awards
- *2024* **Best Presentation Award** at Tsinghua University Initiative Scientific Research Program Forum. *Top 5*
- *2023* **National Scholarship, Ministry of Education**, P.R. China (Top 1 in department) <br /> &nbsp; &nbsp; &nbsp; *Top scholarship in China. 0.2% domestically*.
- *2023* **Scholarship for Social Work Excellence**, Tsinghua University
- *2023* **Scholarship for Science and Technology Innovation Excellence**, Tsinghua University
- *2022* **Scholarship for Social Work Excellence**, Tsinghua University
- *2022* **Scholarship for Science and Technology Innovation Excellence**, Tsinghua University
- *2021* **Scholarship for Social Work Excellence**, Tsinghua University

# 📖 Educations
- *2024.06 - 2027.06*, Research in pervasive computing, Computer Science and Technology Department, Tsinghua University
- *2019.06 - 2024.06*, Double majors in Automation and Industrial Design, Xinya College, Tsinghua University


# 💬 Invited Talks
- *2023.7*, MMPD Presentation, IEEE Engineering in Medicine and Biology Society
- *2022.12*, Creative Software, Xinya College, Tsinghua University
- *2022.05*, Patent Writing, Xinya College, Tsinghua University

# 💻 Internships
- *2024.01 - Now*, [Ant Group](https://www.antgroup.com/) Safety Lab, China.
- *2023.06 - 2023.11*, [Zhipu AI](https://www.zhipuai.cn/en/) ChatGLM Group, China.

# 👨🏻‍🎓 Service and Leadership
- 2024-Now: Academic and Innovation Tutor, Xinya College, Tsinghua University
- 2023-Now: Executive Chairman of Huxiang(湖湘） Culture Association,  Tsinghua University
- 2021-2023: Leader of Creative Design and Intelligent Engineering. CDIE9 was honored with the award of “Excellent Academic Class”.
- 2022-2023: Vice president of the Science and Innovation Association, Xinya College.
  
# 🔗 LINKS
Pervasive HCI Group: [The lab for Pervasive Computing and Human-Computer Interaction at Tsinghua](https://pi.cs.tsinghua.edu.cn/)<br>Yuntao Wang: [Associate Professor, Department of Computer Science and Technology, Tsinghua University](https://pi.cs.tsinghua.edu.cn/lab/people/YuntaoWang/)<br>Xin Liu: [Research Scientist, Google Consumer Health Research and a research affiliate, the Paul G. Allen School of Computer Science & Engineering, University of Washington](https://xliucs.github.io/)<br>Mingxuan Liu: [Department of Biomedical Engineering, Tsinghua University](https://arktis2022.github.io/)
