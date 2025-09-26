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

# 👋 About Me

Hi! I am a second year PhD student studying at [Tsinghua University](https://www.tsinghua.edu.cn/) starting from Fall 2024, majoring in Computer Science and Technology. I am a member of [THUNLP](http://nlp.csai.tsinghua.edu.cn/), advised by [Prof. Zhiyuan Liu](http://nlp.csai.tsinghua.edu.cn/~lzy/). I received my bachelor's degree with honors from [Tsinghua University](https://www.tsinghua.edu.cn/) in June 2024. My research interests primarily lie in the field of natural language processing, with a particular focus on alignment of LLMs.
<!-- <a href='https://scholar.google.com/citations?user=mb36VikAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fscholar.google.com%2Fcitations%3Fuser%3Dmb36VikAAAAJ&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='news'></span>

# 🌟 News
- *2025.09*: &nbsp;🎉 [MiniCPM-V 4.5](https://arxiv.org/abs/2509.18154) released at arXiv [[GitHub]](https://github.com/OpenBMB/MiniCPM-V)
- *2025.09*: &nbsp;🔥 [Survey of RL for LRM](https://arxiv.org/abs/2509.08827) released at arXiv [[GitHub]](https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs)
- *2025.07*: &nbsp;🎉 [AIR](https://arxiv.org/abs/2504.03612) accepted by COLM 2025
- *2025.06*: &nbsp;🎉 [MiniCPM4](https://arxiv.org/abs/2506.07900) released at arXiv [[GitHub]](https://github.com/openbmb/minicpm)
- *2025.05*: &nbsp;🎉 [EscapeBench](https://arxiv.org/abs/2412.13549) accepted by ACL 2025 Main [[GitHub]](https://github.com/qiancheng0/EscapeBench)
- *2025.05*: &nbsp;🎉 One [paper](https://arxiv.org/abs/2406.11721) accepted by ACL 2025 Findings [[GitHub]](https://github.com/thunlp/Dynamics-of-Zero-Shot-Generalization)
- *2025.02*: &nbsp;🔥 [PRIME](https://arxiv.org/abs/2502.01456) released at arXiv [[GitHub]](https://github.com/PRIME-RL/PRIME)
- *2024.05*: &nbsp;🎉 One [paper](https://arxiv.org/abs/2402.09205) accepted by ACL 2024 Main [[GitHub]](https://github.com/OpenBMB/Tell_Me_More)
- *2024.05*: &nbsp;🔥 [UltraFeedback](https://arxiv.org/abs/2310.01377) accepted by ICML 2024 Poster [[GitHub]](https://github.com/OpenBMB/UltraFeedback)
- *2023.10*: &nbsp;🎉 One [paper](https://aclanthology.org/2023.emnlp-main.463) accepted by EMNLP 2023 Main [[GitHub]](https://github.com/thunlp/LLM-generated-text-detection)
- *2022.09*: &nbsp;🎉 [OpenBackdoor](https://arxiv.org/abs/2206.08514) accepted by NeurIPS Datasets & Benchmarks 2022 **(Spotlight)** [[GitHub]](https://github.com/thunlp/OpenBackdoor)

<span class='anchor' id='publications'></span>

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

(* denotes equal/core contribution, † denotes project lead)

- [MiniCPM-V 4.5: Cooking Efficient MLLMs via Architecture, Data, and Training Recipe](https://arxiv.org/abs/2509.18154)<br>
  MiniCPM-V Team [[GitHub 22k+ Stars]](https://github.com/OpenBMB/MiniCPM-V)
- [A Survey of Reinforcement Learning for Large Reasoning Models](https://arxiv.org/abs/2509.08827)<br>
  Kaiyan Zhang\*†, Yuxin Zuo\*†, **Bingxiang He**\*, Youbang Sun\*, Runze Liu\*, Che Jiang\*, Yuchen Fan\*, Kai Tian\*, Guoli Jia\*, Pengfei Li\*, Yu Fu\*, Xingtai Lv\*, Yuchen Zhang\*, Sihang Zeng\*, Shang Qu\*, Haozhan Li\*, Shijie Wang\*, Yuru Wang\*, Xinwei Long, Fangfu Liu, Xiang Xu, Jiaze Ma, Xuekai Zhu, Ermo Hua, Yihao Liu, Zonglin Li, Huayu Chen, Xiaoye Qu, Yafu Li, Weize Chen, Zhenzhao Yuan, Junqi Gao, Dong Li, Zhiyuan Ma, Ganqu Cui, Zhiyuan Liu, Biqing Qi, Ning Ding, Bowen Zhou<br>
  [[GitHub 1.4k+ Stars]](https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs)
- [AIR: A Systematic Analysis of Annotations, Instructions, and Response Pairs in Preference Dataset](https://arxiv.org/abs/2504.03612)<br>
  **Bingxiang He***, Wenbin Zhang*, Jiaxi Song, Cheng Qian, Zixuan Fu, Bowen Sun, Ning Ding, Haiwen Hong, Longtao Huang, Hui Xue, Ganqu Cui, Wanxiang Che, Zhiyuan Liu, Maosong Sun
- [MiniCPM4: Ultra-Efficient LLMs on End Devices](https://arxiv.org/abs/2506.07900)<br>
  MiniCPM Team [[GitHub 8.4k+ Stars](https://github.com/openbmb/minicpm)]
- [Process Reinforcement through Implicit Rewards](https://arxiv.org/abs/2502.01456)<br>
  Ganqu Cui\*, Lifan Yuan\*, Zefan Wang\*, Hanbin Wang\*, Wendi Li\*, **Bingxiang He\***, Yuchen Fan\*, Tianyu Yu\*, Qixin Xu\*, Weize Chen, Jiarui Yuan, Huayu Chen, Kaiyan Zhang, Xingtai Lv, Shuo Wang, Yuan Yao, Xu Han, Hao Peng, Yu Cheng, Zhiyuan Liu, Maosong Sun, Bowen Zhou, Ning Ding<br>
  *ICLR 2026 Submission* [[GitHub 1.7k+ Stars](https://github.com/PRIME-RL/PRIME)]
- [EscapeBench: Pushing Language Models to Think Outside the Box](https://arxiv.org/abs/2412.13549)<br>
  Cheng Qian, Peixuan Han, Qinyu Luo, **Bingxiang He**, Xiusi Chen, Yuji Zhang, Hongyi Du, Jiarui Yao, Xiaocheng Yang, Denghui Zhang, Yunzhu Li, Heng Ji<br>
  *ACL 2025 Main* [[GitHub](https://github.com/qiancheng0/EscapeBench)]
- [The Right Time Matters: Data Arrangement Affects Zero-Shot Generalization in Instruction Tuning](https://arxiv.org/abs/2406.11721)<br>
  **Bingxiang He\***, Ning Ding\*, Cheng Qian\*, Jia Deng, Ganqu Cui, Lifan Yuan, Haiwen Hong, Huan-ang Gao, Longtao Huang, Hui Xue, Huimin Chen, Zhiyuan Liu, Maosong Sun<br>
  *ACL 2025 Findings* [[GitHub](https://github.com/thunlp/Dynamics-of-Zero-Shot-Generalization)]
- [Tell Me More! Towards Implicit User Intention Understanding of Language Model Driven Agents](https://arxiv.org/abs/2402.09205)<br>
  Cheng Qian\*, **Bingxiang He\***, Zhong Zhuang, Jia Deng, Yujia Qin, Xin Cong, Zhong Zhang, Jie Zhou, Yankai Lin, Zhiyuan Liu, Maosong Sun<br>
  *ACL 2024 Main* [[GitHub](https://github.com/HBX-hbx/Mistral-Interact)]
- [UltraFeedback: Boosting Language Models with High-quality Feedback](https://arxiv.org/abs/2310.01377)<br>
  Ganqu Cui\*, Lifan Yuan\*, Ning Ding, Guanming Yao, **Bingxiang He**, Wei Zhu, Yuan Ni, Guotong Xie, Ruobing Xie, Yankai Lin, Zhiyuan Liu, Maosong Sun<br>
  *ICML 2024 Poster* [[GitHub](https://github.com/OpenBMB/UltraFeedback)]
- [Beat LLMs at Their Own Game: Zero-Shot LLM-Generated Text Detection via Querying ChatGPT](https://aclanthology.org/2023.emnlp-main.463)<br>
  Biru Zhu, Lifan Yuan, Ganqu Cui, Yangyi Chen, Chong Fu, **Bingxiang He**, Yangdong Deng, Zhiyuan Liu, Maosong Sun, Ming Gu<br>
  *EMNLP 2023 Main* [[GitHub](https://github.com/thunlp/LLM-generated-text-detection)]
- [A Unified Evaluation of Textual Backdoor Learning: Frameworks and Benchmarks](https://arxiv.org/abs/2206.08514)<br>
  Ganqu Cui\*, Lifan Yuan\*, **Bingxiang He**, Yangyi Chen, Zhiyuan Liu, Maosong Sun<br>
  *NeurIPS Datasets & Benchmarks 2022* **(Spotlight)** [[GitHub]](https://github.com/thunlp/OpenBackdoor)

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2024.09 - 2029.06 (now)*, [Tsinghua University](https://www.tsinghua.edu.cn/)
  Ph.D. in Computer Science and Technology ([THUNLP](http://nlp.csai.tsinghua.edu.cn/))
- *2020.09 - 2024.06*, [Tsinghua University](https://www.tsinghua.edu.cn/)
  B.S. in Computer Science and Technology with honors

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
* Outstanding Graduate Award, Beijing Municipal Education Commission. *2024.06*
* Outstanding Paper Award for Diploma Project, Tsinghua University. *2024.06*
* Five Star ZiJing Volunteer Award, Tsinghua University Communist Youth League Committee. *2024.05*
* Comprehensive Merit Scholarship of Tsinghua for the 2022-2023 school year, Dept. of CST. *2023.10*
* Comprehensive Merit Scholarship of Tsinghua for the 2021-2022 school year, Dept. of CST (Top 1). *2022.10*
* Third Prize in THU Challenge Cup Academic Competition, Tsinghua University. *2022.04*
* Comprehensive Merit Scholarship of Tsinghua for the 2020-2021 school year, Dept. of CST. *2021.10*
* Second Prize in National Undergraduate Physics Competition, Beijing Physics Society. *2021.04*
* Second Prize in Freshmen Scholarship, Tsinghua University. *2020.09*

<span class='anchor' id='invited-talks'></span>

# 💬 Invited Talks
- The Right Time Matters: Data Arrangement Affects Zero-Shot Generalization in Instruction Tuning. Alibaba Security. [Link](https://mp.weixin.qq.com/s/Ig_1I_3_U0L8P1PWJsIA2A). *2025.05*
- Tell me more! towards implicit user intention understanding of language model driven agents. Wiztalk. *2024.08*
- Tell me more! towards implicit user intention understanding of language model driven agents. ModelBest. *2024.04*

<span class='anchor' id='services'></span>

# 🛠️ Services

- **Conference Reviewer**: NeurIPS (2024 - 2025), ICLR (2025 - 2026), ICML (2025), ACL ARR (2024 - 2025), COLM (2025), COLM SCALR Workshop (2025), AAAI (2026), AISTATS (2025 - 2026), ICCV (2025)


<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->