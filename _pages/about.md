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

I graduated from School of Mechanical and Electrical Engineering, [Central South University (CSU)](https://en.csu.edu.cn/) <img src='images/logo_CSU.jpg' style='width: 1.1em;'> with a bachelor’s degree. I am currently a second-year M.Sc. student at [University of Chinese Academy of Sciences (UCAS)](https://english.ucas.ac.cn/) <img src='images/logo_UCAS.png' style='width: 1.1em;'> ([learn more about UCAS](https://en.wikipedia.org/wiki/University_of_the_Chinese_Academy_of_Sciences)), and doing my research at [Shenzhen Institute of Advanced Technology (SIAT)](https://english.siat.ac.cn/) <img src='images/logo_SIAT.webp' style='width: 1.1em;'>, [Chinese Academy of Sciences (CAS)](https://english.cas.cn/) under the supervision of [Prof. Zhengkun Yi](https://people.ucas.ac.cn/~zhengkunyi?language=en) and [Prof. Xinyu Wu](https://people.ucas.ac.cn/~wuxinyu?language=en).

My research interest mainly includes Robotics, Machine Learning, and Reinforcement Learning. Currently, my main focus is on investigating the Peg-in-Hole task using tactile-RL techniques and exploring its applications in various fields. The goal of my work is to improve the performance of robots in real-world situations by harnessing the potential of reinforcement learning and integrating visual and tactile sensory information.

> 📢📢📢 <font color=red>I am looking for a Ph.D. position (2024 Fall).</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to [contact me](mailto:liuchengliang21@mails.ucas.edu.cn). 😊


# 🔥 News

- *2023.05*: One first-author paper is accepted by IEEE TIM (JCR Q1, IF-5.332)! 🎉
- *2023.04*: One first-author paper is accepted by IEEE RCAR 2023! 🎉
- *2022.07*: I am honored with the title of Outstanding Student Leader of [UCAS](https://english.ucas.ac.cn/)! 🏅
- *2022.07*: I am honored with the title of Three Good Student of [UCAS](https://english.ucas.ac.cn/)! 🏅
- *2021.05*: I am honored with the title of Outstanding Graduate of [CSU](https://en.csu.edu.cn/)! 🏅
- *2021.05*: I am honored with the title of Outstanding Graduate of Hunan Province! 🏅
- *2021.03*: I have joined [SIAT, CAS](https://english.siat.ac.cn/) as a research assistant and will spend my final undergraduate year here! 🔬
- *2020.12*: I am awarded a Shanhe Elite First-class Education Scholarship (10, 000 CNY)! 🏆
- *2020.11*: I am awarded a [CSU](https://en.csu.edu.cn/) Second-Class Excellent Student Scholarship (Top 15%)! 🏆
- *2020.09*: I acquire a qualification of postgraduate recommendation, and decide to pursue my master’s degree in [UCAS](https://english.ucas.ac.cn/)! 👨‍🎓
- *2019.12*: I am awarded a Weiqiao Aluminum Electricity Scholarship (5, 000 CNY)! 🏆
- *2019.11*: I am awarded a [CSU](https://en.csu.edu.cn/) First-Class Excellent Student Scholarship (Top 5%)! 🏆
- *2018.11*: I am awarded a [CSU](https://en.csu.edu.cn/) Second-Class Excellent Student Scholarship (Top 15%)! 🏆


# 📝 Publications
## 📌 Pinned
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM</div><img src='images/Triplet-SA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Deep Learning Method Based on Triplet Network Using Self-Attention for Tactile Grasp Outcomes Prediction](https://ieeexplore.ieee.org/document/10152475)(First-author, JCR Q1, IF-5.332)

**Chengliang Liu**, Zhengkun Yi, Binhua Huang, Zhenning Zhou, Senlin Fang, Xiaoyu Li, Yupo Zhang, Xinyu Wu.

**<font color=red>IEEE Transactions on Instrumentation and Measurement</font>** 

- This work focuses on grasp outcome prediction using a limited Gelsight-based tactile dataset.
- We employ an interaction attention mechanism to utilize the context information from different Gelsight sensors, improving embedding quality and enhancing grasp outcome prediction performance.
- We explore the incorporation of a self-attention module as a non-linear projection head, which contributes to improvements in accuracy, precision, and F-score metrics for grasp outcome prediction.
- Extensive experimental results validate the effectiveness of our proposed network, and ablation studies confirm the efficacy of the aforementioned improvements.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE RCAR 2023</div><img src='images/MoCo-Gelsight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Self-supervised Contrastive Learning Method for Grasp Outcomes Prediction]()(First-author)

**Chengliang Liu**, Binhua Huang, Yiwen Liu, Yuanzhe Su, Ke Mai, Yupo Zhang, Zhengkun Yi, Xinyu Wu

**<font color=red>2023 IEEE International Conference on Real-time Computing and Robotics</font>** 

- This work focuses on the grasp outcome prediction task by employing self-supervised contrastive learning methods, utilizing Gelsight-based tactile datasets.
- Inspired by simCLR, we explore the transferability of its data augmentation techniques to a Gelsight-based tactile dataset, and propose a contrastive learning network framework based on MoCo for grasp outcome prediction. Moreover, we compare the performance of various self-supervised learning methods within this context.
- The experimental results demonstrate the effectiveness of simCLR's data augmentation techniques on Gelsight-based tactile datasets, and reveal that our proposed framework outperforms other self-supervised learning methods in this domain.

</div>
</div>

## 🔎 Other

- [Methods to Recognize Depth of Hard Inclusions in Soft Tissue Using Ordinal Classification for Robotic Palpation](https://ieeexplore.ieee.org/document/9856694), Zhenning Zhou, Binhua Huang, Runzhi Zhang, Meng Yin, **Chengliang Liu**, Yiwen Liu, Zhengkun Yi, Xinyu Wu, IEEE Transactions on Instrumentation and Measurement (TIM, JCR Q1, IF-5.332), 2022
- [TactCapsNet: Tactile Capsule Network for Object Hardness Recognition](https://ieeexplore.ieee.org/document/9517551), Senlin Fang, Tingting Mi, Zhenning Zhou, Chaoxiang Ye, **Chengliang Liu**, Hancheng Wu, Zhengkun Yi, Xinyu Wu, 2021 IEEE International Conference on Real-time Computing and Robotics (RCAR)
- [Tactile Grasp Stability Classification Based on Graph Convolutional Networks](https://ieeexplore.ieee.org/document/9517085), Tingting Mi, Dashun Que, Senlin Fang, Zhenning Zhou, Chaoxiang Ye, **Chengliang Liu**, Zhengkun Yi, Xinyu Wu, 2021 IEEE International Conference on Real-time Computing and Robotics (RCAR)
- [TGCN-P: A TCN-GCN Network With Weighted Graph Constructed by Pearson Correlation Coefficient for Human Motion Tracking](), Xiaoyu Li, Jingnan Wang, Binhua Huang, **ChengLiang Liu**, Yiwen Liu, Yupo Zhang, Zhengkun Yi, Xinyu Wu, 2023 IEEE International Conference on Real-time Computing and Robotics (RCAR, ACCEPTED)
- [Evaluation of Continual Learning Methods for Object Hardness Recognition](), Yiwen Liu, Senlin Fang, **ChengLiang Liu**, Jingnan Wang, Ke Mai, Yupo Zhang, Zhengkun Yi, Xin yu Wu, 2023 IEEE International Conference on Real-time Computing and Robotics (RCAR, ACCEPTED)
- [Attention-enhanced BLSTM Network for Liquid Volume Estimation based on Tactile Sensing](), Yuanzhe Su, Jingnan Wang, Binhua Huang, Xiaoyu Li, Yiwen Liu, **ChengLiang Liu**, Zhenning Zhou, Zhengkun Yi, Xinyu Wu, 2023 IEEE International Conference on Real-time Computing and Robotics (RCAR, ACCEPTED)


# 👨‍💻 Experience
<!-- - *2023.04 - now* &ensp; Research Intern, [Tencent YouTu Lab](https://open.youtu.qq.com/), Shenzhen, China
- *2022.07 - 2023.01* &ensp; Research Intern, [Zhejiang Lab](https://en.zhejianglab.com/), Hangzhou, China
- *2021.03 - 2021.08* &ensp; Research Assistant, [SIAT](https://english.siat.ac.cn/), Shenzhen, China
- *2019.08 - 2020.01* &ensp; Entrepreneurial Intern, [XbotPark](http://www.xbotpark.com/?lang=en), Dongguan, China -->

---

<div class='exp-box'><div class='exp-box-image'><div><img src='images/logo_SIAT_CAS.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

[SIAT, CAS](https://english.siat.ac.cn/), Shenzhen, China

**Research Assistant** @ Intelligent Systems and Robot Learning Lab (ISRL)

*2021.03 - 2021.08*

**Teaching Assistant** @ Introduction to Robotics

*2023.02 - 2023.06*

</div>
</div>

# 🏆 Selected Awards
- *2021 - 2023* &ensp; UCAS Postgraduate Fellowship (Full Tuition Waiver & 8,000 CNY p.a.)
- *2020.12* &ensp; [Shanhe Elite First-class Education Scholarship (10,000 CNY)](./honors/Shanhe_Elite-Scholarship-2020.12.06.jpg)
- *2020.11* &ensp; [Second-Class Excellent Student Scholarship (Top 15%)](./honors/CSU-Second_Class_Scholarship-2020.11.jpg)
- *2019.12* &ensp; [Weiqiao Aluminum Electricity Scholarship (5, 000 CNY)](./honors/Weiqiao-Scholarship-2019.12.jpg)
- *2019.11* &ensp; [First-Class Excellent Student Scholarship (Top 5%)](./honors/CSU-First_Class_Scholarship-2019.11.jpg)
- *2018.11* &ensp; [Second-Class Excellent Student Scholarship (Top 15%)](./honors/CSU-Second_Class_Scholarship-2018.11.jpg)

# 🏅 Selected Honors
- *2022.07* &ensp; [Outstanding Student Leader of University of Chinese Academy of Sciences (Top 5%)](./honors/UCAS-Outstanding_student_leader-2022.07.jpg)
- *2022.07* &ensp; [Three Good Student of University of Chinese Academy of Sciences (Top 15%)](./honors/UCAS-Three_Good-2022.07.jpg)
- *2021.05* &ensp; [Outstanding Graduate of Central South University (Top 4%)](./honors/CSU-Outstanding_Graduate-2021.05.jpg)
- *2021.05* &ensp; [Outstanding Graduate of Hunan Province (Top 3.5%)](./honors/Hunan_Province-Outstanding_Graduate-2021.05.jpg)
- *2018-2020* &ensp; Merit Student of Central South University (Top 15%, Three Times, Academic Year: [2017-2018](./honors/CSU-Merit_Student-2019.01.jpg)), [2018-2019](./honors/CSU-Merit_Student-2019.12.jpg), [2019-2020](./honors/CSU-Merit_Student-2020.12.jpg)