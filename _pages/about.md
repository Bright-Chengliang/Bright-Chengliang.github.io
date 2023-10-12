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

I graduated from School of Mechanical and Electrical Engineering, [Central South University (CSU](https://en.csu.edu.cn/), [Project 985](https://en.wikipedia.org/wiki/Project_985), [Project 211)](https://en.wikipedia.org/wiki/Project_211) <img src='images/logo_CSU.jpg' style='width: 1.1em;'> with a bachelor’s degree. I am currently a third-year M.Sc. student at [University of Chinese Academy of Sciences (UCAS)](https://english.ucas.ac.cn/) <img src='images/logo_UCAS.png' style='width: 1.1em;'> ([learn more about UCAS](https://en.wikipedia.org/wiki/University_of_the_Chinese_Academy_of_Sciences)), and doing my research at [Shenzhen Institute of Advanced Technology (SIAT)](https://english.siat.ac.cn/) <img src='images/logo_SIAT.webp' style='width: 1.1em;'>, [Chinese Academy of Sciences (CAS)](https://english.cas.cn/) under the supervision of [Prof. Zhengkun Yi](https://people.ucas.ac.cn/~zhengkunyi?language=en) and [Prof. Xinyu Wu](https://people.ucas.ac.cn/~wuxinyu?language=en).

My research interest mainly includes Robotics, Machine Learning, especially Contrastive Learning, and Reinforcement Learning. Currently, my main focus is on investigating the Dexterous Grasping and Contrastive Learning and exploring their applications in various fields. The goal of my work is to improve the performance of robots in real-world situations by harnessing the potential of deep learning, reinforcement learning and integrating visual and tactile sensory information.


> 📢📢📢 [VIEW MY CV](_pages/Bright_Resume_10.12(latest).pdf). <font color=red>I am looking for a Ph.D. position (2024 Fall).</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to [contact me](mailto:cl.liu99@foxmail.com). 😊

# 🔥 News

- *2023.10*: I am nominated as a candidate for the National Postgraduate Scholarship (Top 1.67%, 20, 000 CNY)! 🏆
- *2023.05*: One first-author paper is accepted by IEEE TIM (JCR Q1, IF-5.6)! 🎉
- *2023.04*: One first-author paper is accepted by IEEE RCAR 2023! 🎉
- *2022.07*: I am honored with the title of Outstanding Student Leader of [UCAS](https://english.ucas.ac.cn/) (Top 5%)! 🏅
- *2022.07*: I am honored with the title of Three Good Student of [UCAS](https://english.ucas.ac.cn/) (Top 15%)! 🏅
- *2021.05*: I am honored with the title of Outstanding Graduate of [CSU](https://en.csu.edu.cn/) (Top 4%)! 🏅
- *2021.05*: I am honored with the title of Outstanding Graduate of Hunan Province (Top 3.5%)! 🏅
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

[A Deep Learning Method Based on Triplet Network Using Self-Attention for Tactile Grasp Outcomes Prediction](https://ieeexplore.ieee.org/document/10152475)(First-author, JCR Q1, IF-5.6)

**Chengliang Liu**, Zhengkun Yi, Binhua Huang, Zhenning Zhou, Senlin Fang, Xiaoyu Li, Yupo Zhang, Xinyu Wu.

**<font color=red>IEEE Transactions on Instrumentation and Measurement</font>** 

- Investigate contrastive learning using triplet loss in a supervised manner for grasp outcome prediction in a small Gelsight-based tactile dataset.
- Integrate cross self-attention mechanisms with triplet net to exploit context information from different sensors.
- Found that a self-attention module can work as a non-linear projection head for contrastive learning, which performs better than a simple MLP.
- The experimental results demonstrate significant performance improvements in various metrics when using our framework, compared to the original method.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE RCAR 2023</div><img src='images/MoCo-Gelsight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Self-supervised Contrastive Learning Method for Grasp Outcomes Prediction](https://ieeexplore.ieee.org/document/10249649)(First-author)

**Chengliang Liu**, Binhua Huang, Yiwen Liu, Yuanzhe Su, Ke Mai, Yupo Zhang, Zhengkun Yi, Xinyu Wu

**<font color=red>2023 IEEE International Conference on Real-time Computing and Robotics</font>** 

- Explore and verify the transferability of widely-applied data augmentation techniques in the field of Computer Vision to Gelsight-based tactile datasets.
- A grasp outcome prediction network was proposed based on momentum contrast with the maintenance of a large dictionary, which achieves 81.83% predictive accuracy with a single tactile sensor data.
- The experimental results show that the proposed network achieved state-of-the-art performance compared to three other self-supervised methods.

</div>
</div>

## 🔎 Other

- Probabilistic Spiking Neural Network for Robotic Tactile Continual Learning, Senlin Fang, Yiwen Liu, **Chengliang Liu**, Jingnan Wang, Yuanzhe Su, Yupo Zhang, Hoiio Kong, Zhengkun Yi, Xinyu Wu, 2024 IEEE International Conference on Robotics and Automation (ICRA, under review)
- [Evaluation of Continual Learning Methods for Object Hardness Recognition](https://ieeexplore.ieee.org/document/10249594), Yiwen Liu, Senlin Fang, **Chengliang Liu**, Jingnan Wang, Ke Mai, Yupo Zhang, Zhengkun Yi, Xinyu Wu, 2023 IEEE International Conference on Real-time Computing and Robotics (RCAR)
- [Attention-enhanced BLSTM Network for Liquid Volume Estimation based on Tactile Sensing](https://ieeexplore.ieee.org/document/10250000/), Yuanzhe Su, Jingnan Wang, Binhua Huang, Xiaoyu Li, Yiwen Liu, **Chengliang Liu**, Zhenning Zhou, Zhengkun Yi, Xinyu Wu, 2023 IEEE International Conference on Real-time Computing and Robotics (RCAR)
- [TGCN-P: A TCN-GCN Network With Weighted Graph Constructed by Pearson Correlation Coefficient for Human Motion Tracking](https://ieeexplore.ieee.org/document/10249259/), Xiaoyu Li, Jingnan Wang, Binhua Huang, **Chengliang Liu**, Yiwen Liu, Yupo Zhang, Zhengkun Yi, Xinyu Wu, 2023 IEEE International Conference on Real-time Computing and Robotics (RCAR)
- [Methods to Recognize Depth of Hard Inclusions in Soft Tissue Using Ordinal Classification for Robotic Palpation](https://ieeexplore.ieee.org/document/9856694), Zhenning Zhou, Binhua Huang, Runzhi Zhang, Meng Yin, **Chengliang Liu**, Yiwen Liu, Zhengkun Yi, Xinyu Wu, IEEE Transactions on Instrumentation and Measurement (TIM, JCR Q1, IF-5.6), 2022
- [TactCapsNet: Tactile Capsule Network for Object Hardness Recognition](https://ieeexplore.ieee.org/document/9517551), Senlin Fang, Tingting Mi, Zhenning Zhou, Chaoxiang Ye, **Chengliang Liu**, Hancheng Wu, Zhengkun Yi, Xinyu Wu, 2021 IEEE International Conference on Real-time Computing and Robotics (RCAR)
- [Tactile Grasp Stability Classification Based on Graph Convolutional Networks](https://ieeexplore.ieee.org/document/9517085), Tingting Mi, Dashun Que, Senlin Fang, Zhenning Zhou, Chaoxiang Ye, **Chengliang Liu**, Zhengkun Yi, Xinyu Wu, 2021 IEEE International Conference on Real-time Computing and Robotics (RCAR)

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
- *2023.10* &ensp; National Postgraduate Scholarship (Candidate, Top 1.67%, 20, 000 CNY)
- *2021 - 2024* &ensp; UCAS Postgraduate Fellowship (Full Tuition Waiver & 8,000 CNY p.a.)
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
- *2018 - 2020* &ensp; Merit Student of Central South University (Top 15%, Three Times, Academic Year: [2017-2018](./honors/CSU-Merit_Student-2019.01.jpg), [2018-2019](./honors/CSU-Merit_Student-2019.12.jpg), [2019-2020](./honors/CSU-Merit_Student-2020.12.jpg))
