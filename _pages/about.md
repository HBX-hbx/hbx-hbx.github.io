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

Hi! I am a third-year PhD student at [Tsinghua University](https://www.tsinghua.edu.cn/), majoring in Computer Science and Technology. I am a member of [THUNLP](http://nlp.csai.tsinghua.edu.cn/), advised by [Prof. Zhiyuan Liu](http://nlp.csai.tsinghua.edu.cn/~lzy/). I received my bachelor's degree with honors from [Tsinghua University](https://www.tsinghua.edu.cn/) in June 2024. My research interests lie in natural language processing, with a focus on alignment, reinforcement learning, and self-evolving language models.
<!-- <a href='https://scholar.google.com/citations?user=mb36VikAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fscholar.google.com%2Fcitations%3Fuser%3Dmb36VikAAAAJ&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='news'></span>

# 🌟 News

<style>
  .news-list {
    max-height: 300px;
    overflow-y: auto;
    list-style-type: disc;
    padding: 0 1rem 0 20px;
    margin: 0 0 2rem;
    font-size: 0.9rem;
    line-height: 1.5;
    scrollbar-width: thin;
  }
  .news-list li { padding: 0.12rem 0; }
</style>
<ul class="news-list" aria-label="Recent news">
  <li><em>2026.09</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2609.04172">Rethinking OPD II: One-Shot OPD</a> released at arXiv <a href="https://github.com/Thinking-Space/One-Shot-OPD">GitHub</a></li>
  <li><em>2026.09</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2609.00787">StudyBench</a> released at arXiv and accepted by EMNLP 2026 <a href="https://github.com/thunlp/StudyBench">GitHub</a></li>
  <li><em>2026.08</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2608.14441">PACE-Bench</a> released at arXiv and accepted by EMNLP 2026 <a href="https://github.com/thunlp/PACE-Bench">GitHub</a></li>
  <li><em>2026.07</em>: &nbsp;🎉 Selected for the <a href="https://www.cie.org.cn/list_43/16649.html">CIE-Tencent Doctoral Research Incentive Project</a> (44 recipients nationwide)!</li>
  <li><em>2026.06</em>: &nbsp;🎉 Honored to be one of <a href="https://mp.weixin.qq.com/s/VwzvuyToY79B2DtWmenjVQ">Qingyuan InnoVibe 2026's Most Promising Rising Academic Stars</a> (25 Winners Nationwide)!</li>
  <li><em>2026.06</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2606.24530">NatureBench</a> released at arXiv <a href="https://github.com/FrontisAI/NatureBench">GitHub</a> <a href="https://frontisai.github.io/NatureBench">Leaderboard</a></li>
  <li><em>2026.05</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2604.13016">Rethinking OPD I</a> accepted by ICML 2026 FoGen Workshop, see you in Seoul! BTW metrics are merged into <a href="https://github.com/verl-project/verl/pull/6469">veRL</a>.</li>
  <li><em>2026.05</em>: &nbsp;🎉 Honored to be recognized as a Gold Reviewer of ICML 2026 (Top 25%)!</li>
  <li><em>2026.05</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2602.02979">CPMobius</a> accepted by ICML 2026 <a href="https://github.com/thunlp/CPMobius">GitHub</a></li>
  <li><em>2026.04</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2604.13016">Rethinking OPD I</a> released at arXiv <a href="https://github.com/thunlp/OPD">GitHub</a></li>
  <li><em>2026.02</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2603.08660">Unsupervised RLVR</a> accepted by ICLR 2026 <a href="https://github.com/PRIME-RL/TTRL/tree/urlvr-dev">GitHub</a></li>
  <li><em>2025.12</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2512.16649">JustRL</a> accepted by ICLR 2026 Blog Track <a href="https://github.com/thunlp/JustRL">GitHub</a></li>
  <li><em>2025.10</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2510.01932">Veri-R1</a> released at arXiv <a href="https://github.com/H0key-22/Veri-R1">GitHub</a></li>
  <li><em>2025.09</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2509.18154">MiniCPM-V 4.5</a> accepted by CVPR 2026 <a href="https://github.com/OpenBMB/MiniCPM-V">GitHub</a></li>
  <li><em>2025.09</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2509.08827">Survey of RL for LRM</a> released at arXiv <a href="https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs">GitHub</a></li>
  <li><em>2025.07</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2504.03612">AIR</a> accepted by COLM 2025</li>
  <li><em>2025.06</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2506.07900">MiniCPM4</a> released at arXiv <a href="https://github.com/openbmb/minicpm">GitHub</a></li>
  <li><em>2025.05</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2412.13549">EscapeBench</a> accepted by ACL 2025 <a href="https://github.com/qiancheng0/EscapeBench">GitHub</a></li>
  <li><em>2025.05</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2406.11721">Dynamics of Zero-Shot Generalization</a> accepted by ACL 2025 <a href="https://github.com/thunlp/Dynamics-of-Zero-Shot-Generalization">GitHub</a></li>
  <li><em>2025.02</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2502.01456">PRIME</a> released at arXiv <a href="https://github.com/PRIME-RL/PRIME">GitHub</a></li>
  <li><em>2024.05</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2402.09205">Tell Me More</a> accepted by ACL 2024 <a href="https://github.com/OpenBMB/Tell_Me_More">GitHub</a></li>
  <li><em>2024.05</em>: &nbsp;🔥 <a href="https://arxiv.org/pdf/2310.01377">UltraFeedback</a> accepted by ICML 2024 <a href="https://github.com/OpenBMB/UltraFeedback">GitHub</a></li>
  <li><em>2023.10</em>: &nbsp;🎉 Our work on <a href="https://aclanthology.org/2023.emnlp-main.463">LLM-generated Text Detection</a> is accepted by EMNLP 2023 <a href="https://github.com/thunlp/LLM-generated-text-detection">GitHub</a></li>
  <li><em>2022.09</em>: &nbsp;🎉 <a href="https://arxiv.org/pdf/2206.08514">OpenBackdoor</a> accepted by NeurIPS Datasets &amp; Benchmarks 2022 <strong>(Spotlight)</strong> <a href="https://github.com/thunlp/OpenBackdoor">GitHub</a></li>
</ul>



<span class='anchor' id='publications'></span>

# 📝 Publications 

(* denotes equal/core contribution, <sup>†</sup> denotes project lead, <sup>‡</sup> indicates corresponding author.)

[Google Scholar](https://scholar.google.com/citations?user=mb36VikAAAAJ) · **2700+ citations**

- [Rethinking On-Policy Distillation of Large Language Models II: One Training Example](https://arxiv.org/pdf/2609.04172)<br>
  Zixuan Fu\*, **Bingxiang He**\*<sup>†‡</sup>, Yuxin Zuo\*<sup>†</sup>, Haohuan Huang\*, Jinqian Zhang, Ruhang Xiao, Cheng Qian, Qinyu Luo, Huan-ang Gao, Yudong Wang, Zhiyuan Liu, Ning Ding<sup>‡</sup>, Chaojun Xiao<sup>‡</sup><br>
  *Preprint* [[GitHub]](https://github.com/Thinking-Space/One-Shot-OPD)

  <small>▸[[HF Daily Paper]](https://huggingface.co/papers/2609.04172) · [[12k+ views on X]](https://x.com/HBX_hbx/status/2095716853196747175)</small>

- [PACE-Bench: Benchmarking Physics Adaptation via Code Evolution in Dynamic Environments](https://arxiv.org/pdf/2608.14441)<br>
  Yuhao Zhan\*, **Bingxiang He**\*, Zecong Tang, Chaojun Xiao<sup>‡</sup><br>
  *EMNLP 2026 Findings* [[Project Page]](https://thunlp.github.io/PACE-Bench) [[GitHub]](https://github.com/thunlp/PACE-Bench) [[HF Benchmark]](https://huggingface.co/datasets/YuhaoZhan/PACE-Bench)

  <small>▸[[HF Daily Paper]](https://huggingface.co/papers/2608.14441) · [[2k+ views on X]](https://x.com/YuhaoZhan6/status/2089717175955407057) · Featured by [[TsinghuaNLP]](https://mp.weixin.qq.com/s/NB7xRUCEdFmlkvysVuAVrA), [[OpenBMB]](https://mp.weixin.qq.com/s/uG1nxUFzQhVo5CTrlSsE6g) </small>

- [StudyBench: Can Self-Evolution Squeeze Textbooks for Olympiad Capability?](https://arxiv.org/pdf/2609.00787)<br>
  Yinghao Chen\*, Zixi Chen\*, **Bingxiang He**\*<sup>‡</sup>, Ziqing Qiao, Huan-ang Gao, Yinuo Xu, Yuxin Zuo, Zeyuan Liu, Yuhao Zhan, Chaojun Xiao<sup>‡</sup><br>
  *EMNLP 2026 Findings* [[GitHub]](https://github.com/thunlp/StudyBench)

  <small>▸[[HF Paper]](https://huggingface.co/papers/2609.00787)</small>

- [CPMobius: Iterative Coach-Player Reasoning for Data-Free Reinforcement Learning](https://arxiv.org/pdf/2602.02979)<br>
  Ran Li\*, Zeyuan Liu\*, Yinghao Chen, **Bingxiang He**, Jiarui Yuan, Zixuan Fu, Weize Chen, Jinyi Hu, Zhiyuan Liu<sup>‡</sup>, Maosong Sun<br>
  *ICML 2026* [[GitHub]](https://github.com/thunlp/CPMobius)<br>
  <small>▸ Featured by [OpenBMB](https://mp.weixin.qq.com/s/hlfHG8nfteAVdfpO3ocXtQ)</small>

- [Rethinking On-Policy Distillation of Large Language Models: Phenomenology, Mechanism, and Recipe](https://arxiv.org/pdf/2604.13016)<br>
  Yaxuan Li\*, Yuxin Zuo\*<sup>†</sup>, **Bingxiang He**\*<sup>†</sup>, Jinqian Zhang, Chaojun Xiao<sup>‡</sup>, Cheng Qian, Tianyu Yu, Huan-ang Gao, Wenkai Yang, Zhiyuan Liu<sup>‡</sup>, Ning Ding<sup>‡</sup><br>
  *ICML 2026 FoGen Workshop* [[GitHub 900+ Stars](https://github.com/Thinking-Space/Rethinking-OPD)]<br>
  <small>▸ Adopted by [ModelBest (MiniCPM5)](https://github.com/OpenBMB/MiniCPM/tree/minicpm5#what-does-rl--opd-bring) and [ByteDance Seed's veRL](https://github.com/verl-project/verl/pull/6469) · [#1 on HF Daily Papers](https://huggingface.co/papers/2604.13016) · [19k+ views on X](https://x.com/HBX_hbx/status/2044464414829777354) · Featured by [AK](https://x.com/_akhaliq/status/2044444138582466652), [TuringPost](https://x.com/TheTuringPost/status/2046710304999104954), [QingKeAI](https://mp.weixin.qq.com/s/kBPunQnTnp2GEU3DbZRYGQ), [Synced](https://mp.weixin.qq.com/s/uUGZc2sireEyCJg8Q200aw), [OpenBMB](https://mp.weixin.qq.com/s/x32CJozGUhl9RKm0BiaciA), [TsinghuaNLP](https://mp.weixin.qq.com/s/vbt3JkS782byAzYPhC7NRw)</small>

- [How Far Can Unsupervised RLVR Scale LLM Training?](https://arxiv.org/pdf/2603.08660)<br>
  **Bingxiang He**\*, Yuxin Zuo\*<sup>†</sup>, Zeyuan Liu\*, Shangziqi Zhao\*, Zixuan Fu, Junlin Yang, Cheng Qian, Kaiyan Zhang, Yuchen Fan, Ganqu Cui, Xiusi Chen, Youbang Sun, Xingtai Lv, Xuekai Zhu, Li Sheng, Ran Li, Huan-ang Gao, Yuchen Zhang, Bowen Zhou<sup>‡</sup>, Zhiyuan Liu<sup>‡</sup>, Ning Ding<sup>‡</sup><br>
  *ICLR 2026* [[GitHub 1k+ Stars]](https://github.com/PRIME-RL/TTRL/tree/urlvr-dev)<br>
  <small>▸ [#3 on HF Daily Papers](https://huggingface.co/papers/2603.08660) · [10k+ views on X](https://x.com/HBX_hbx/status/2031406636930338828) · Featured by [AK](https://x.com/_akhaliq/status/2031390379388350507), [TuringPost](https://x.com/TheTuringPost/status/2033856658615767496), [HuggingPapers](https://x.com/HuggingPapers/status/2031406570366525729), [sheriyuo](https://x.com/sheriyuo/status/2061382777623519284), [Synced](https://mp.weixin.qq.com/s/W6v7E-Rm3vybbjn265Ev4w), [OpenBMB](https://mp.weixin.qq.com/s/oR73dIBt2bPhO8dQcjmBCQ), [TsinghuaNLP](https://mp.weixin.qq.com/s/ovfQfgvbwS42RMemx6kyLQ)</small>

- [JustRL: Scaling a 1.5B LLM with a Simple RL Recipe](https://arxiv.org/pdf/2512.16649)<br>
  **Bingxiang He**, Zekai Qu, Zeyuan Liu, Yinghao Chen, Yuxin Zuo, Cheng Qian, Kaiyan Zhang, Weize Chen, Chaojun Xiao, Ganqu Cui, Ning Ding<sup>‡</sup>, Zhiyuan Liu<sup>‡</sup><br>
  *ICLR 2026 Blog* [[Blog]](https://www.notion.so/JustRL-Scaling-a-1-5B-LLM-with-a-Simple-RL-Recipe-24f6198b0b6b80e48e74f519bfdaf0a8) [[GitHub 290+ Stars]](https://github.com/thunlp/JustRL)<br>
  <small>▸ [25k+ HF downloads](https://huggingface.co/collections/hbx/justrl) · Adopted by [ModelBest (MiniCPM5)](https://github.com/OpenBMB/MiniCPM/tree/minicpm5#what-does-rl--opd-bring) · [42k+ views on X](https://x.com/HBX_hbx/status/1988474153436090776) · [100k+ views on Zhihu](https://www.zhihu.com/question/1987478921730613767) · Featured by [alphaXiv](https://x.com/askalphaxiv/status/2003196659426316294), [DAIR.AI](https://x.com/dair_ai/status/2004235730613371251), [Synced](https://mp.weixin.qq.com/s/F4zvQfWusb-QetDi-ReErg), [TsinghuaNLP](https://mp.weixin.qq.com/s/J-_vndAFQwiWgnyS0AW4xQ), [QingKeAI](https://mp.weixin.qq.com/s/Ya6QHWQ5HKo-8XngAg3a7g)</small>

- [MiniCPM-V 4.5: Cooking Efficient MLLMs via Architecture, Data, and Training Recipe](https://arxiv.org/pdf/2509.18154)<br>
  MiniCPM-V Team <br>
  *CVPR 2026* [[GitHub 25k+ Stars]](https://github.com/OpenBMB/MiniCPM-V)<br>
  <small>▸ [280k+ HF downloads/mo](https://huggingface.co/openbmb/MiniCPM-V-4_5) · Integrated into [llama.cpp](https://github.com/ggml-org/llama.cpp/pull/15575), [vLLM](https://github.com/vllm-project/vllm/pull/23586), [Ollama](https://github.com/ollama/ollama/pull/12078), [SGLang](https://github.com/sgl-project/sglang/pull/9610), [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory/pull/9022) · Featured by [OpenBMB](https://x.com/OpenBMB/status/1960407534784942247)</small>

- [A Survey of Reinforcement Learning for Large Reasoning Models](https://arxiv.org/pdf/2509.08827)<br>
  Kaiyan Zhang\*<sup>†</sup>, Yuxin Zuo\*<sup>†</sup>, **Bingxiang He**\*, Youbang Sun\*, Runze Liu\*, Che Jiang\*, Yuchen Fan\*, Kai Tian\*, Guoli Jia\*, Pengfei Li\*, Yu Fu\*, Xingtai Lv\*, Yuchen Zhang\*, Sihang Zeng\*, Shang Qu\*, Haozhan Li\*, Shijie Wang\*, Yuru Wang\*, Xinwei Long, Fangfu Liu, Xiang Xu, Jiaze Ma, Xuekai Zhu, Ermo Hua, Yihao Liu, Zonglin Li, Huayu Chen, Xiaoye Qu, Yafu Li, Weize Chen, Zhenzhao Yuan, Junqi Gao, Dong Li, Zhiyuan Ma, Ganqu Cui, Zhiyuan Liu, Biqing Qi<sup>‡</sup>, Ning Ding<sup>‡</sup>, Bowen Zhou<sup>‡</sup><br>
  *Preprint* [[GitHub 2.5k+ Stars]](https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs)<br>
  <small>▸ [#1 on HF Daily Papers](https://huggingface.co/papers/2509.08827) · [150k+ views on X](https://x.com/omarsar0/status/1966147234954940705) · Featured by [elvis (DAIR.AI)](https://x.com/omarsar0/status/1966147234954940705), [TuringPost](https://x.com/TheTuringPost/status/1966619126186795489), [Synced](https://mp.weixin.qq.com/s/CkKlHplf-kO30L6B_ucv1g), [TsinghuaNLP](https://mp.weixin.qq.com/s/hudQhUp9j95Se35-rGxY2Q)</small>

- [NatureBench: Can Coding Agents Match the Published SOTA of Nature-Family Papers?](https://arxiv.org/pdf/2606.24530)<br>
  Yuru Wang\*, Lejun Cheng\*, Yuxin Zuo\*, Sihang Zeng, **Bingxiang He**, Che Jiang, Junlin Yang, Yuchong Wang, Kaikai Zhao, Weifeng Huang, Kai Tian, Zhenzhao Yuan, Jincheng Zhong, Weizhi Wang, Ning Ding, Bowen Zhou<sup>‡</sup>, Kaiyan Zhang<sup>‡</sup><br>
  *Preprint* [[GitHub 50+ Stars]](https://github.com/FrontisAI/NatureBench) [[Data]](https://huggingface.co/datasets/FrontisAI/NatureBench) [[Leaderboard]](https://frontisai.github.io/NatureBench)<br>
  <small>▸ [#2 on HF Daily Papers](https://huggingface.co/papers/2606.24530) · Featured by [TsinghuaC3I](https://mp.weixin.qq.com/s/k1yXiOGwznFmbvugjBvLOw)</small>

- [AIR: A Systematic Analysis of Annotations, Instructions, and Response Pairs in Preference Dataset](https://arxiv.org/pdf/2504.03612)<br>
  **Bingxiang He**\*, Wenbin Zhang\*, Jiaxi Song, Cheng Qian, Zixuan Fu, Bowen Sun, Ning Ding, Haiwen Hong, Longtao Huang, Hui Xue, Ganqu Cui<sup>‡</sup>, Wanxiang Che<sup>‡</sup>, Zhiyuan Liu, Maosong Sun <br>
  *COLM 2025*<br>
  <small>▸ [8k+ views on X](https://x.com/OpenBMB/status/2012179938388926679) · Featured by [Synced](https://mp.weixin.qq.com/s/sIpYVxFlrW76D2151p5Nbg), [TsinghuaNLP](https://mp.weixin.qq.com/s/jMFyZaIsdaodGMpIVQOo2w)</small>

- [MiniCPM4: Ultra-Efficient LLMs on End Devices](https://arxiv.org/pdf/2506.07900)<br>
  MiniCPM Team<br>
  *Preprint* [[GitHub 9k+ Stars](https://github.com/openbmb/minicpm)] [[HF Collection]](https://huggingface.co/collections/openbmb/minicpm-4-6841ab29d180257e940baa9b)<br>
  <small>▸ Featured by [OpenBMB](https://x.com/OpenBMB/status/1930983161577754747) (18k+ views), [TsinghuaNLP](https://mp.weixin.qq.com/s/bgKUJRKKt72GB5xU_3QyAQ)</small>

- [Process Reinforcement through Implicit Rewards](https://arxiv.org/pdf/2502.01456)<br>
  Ganqu Cui\*, Lifan Yuan\*, Zefan Wang\*, Hanbin Wang\*, Yuchen Zhang\*, Jiacheng Chen\*, Wendi Li\*, **Bingxiang He\***, Yuchen Fan\*, Tianyu Yu\*, Qixin Xu\*, Weize Chen, Jiarui Yuan, Huayu Chen, Kaiyan Zhang, Xingtai Lv, Shuo Wang, Yuan Yao, Xu Han, Hao Peng, Yu Cheng, Zhiyuan Liu, Maosong Sun, Bowen Zhou, Ning Ding<br>
  *Preprint* [[Blog]](https://curvy-check-498.notion.site/Process-Reinforcement-through-Implicit-Rewards-15f4fcb9c42180f1b498cc9b2eaf896f) [[GitHub 1.9k+ Stars](https://github.com/PRIME-RL/PRIME)]<br>
  <small>▸ [240k+ views on X](https://x.com/lifan__yuan/status/1874867809983033649) · Liked by John Schulman and reposted by Nathan Lambert · Featured by [QbitAI](https://mp.weixin.qq.com/s/s-DeQCAX1gth82YkABxLLA)</small>

- [EscapeBench: Pushing Language Models to Think Outside the Box](https://arxiv.org/pdf/2412.13549)<br>
  Cheng Qian, Peixuan Han, Qinyu Luo, **Bingxiang He**, Xiusi Chen, Yuji Zhang, Hongyi Du, Jiarui Yao, Xiaocheng Yang, Denghui Zhang, Yunzhu Li, Heng Ji<br>
  *ACL 2025 Main* [[GitHub](https://github.com/qiancheng0/EscapeBench)]

- [The Right Time Matters: Data Arrangement Affects Zero-Shot Generalization in Instruction Tuning](https://arxiv.org/pdf/2406.11721)<br>
  **Bingxiang He\***, Ning Ding\*, Cheng Qian\*, Jia Deng, Ganqu Cui, Lifan Yuan, Haiwen Hong, Huan-ang Gao, Longtao Huang, Hui Xue, Huimin Chen, Zhiyuan Liu<sup>‡</sup>, Maosong Sun<sup>‡</sup><br>
  *ACL 2025 Findings* [[GitHub](https://github.com/thunlp/Dynamics-of-Zero-Shot-Generalization)]

- [Tell Me More! Towards Implicit User Intention Understanding of Language Model Driven Agents](https://arxiv.org/pdf/2402.09205)<br>
  Cheng Qian\*, **Bingxiang He\***, Zhong Zhuang, Jia Deng, Yujia Qin, Xin Cong, Zhong Zhang, Jie Zhou, Yankai Lin, Zhiyuan Liu, Maosong Sun<br>
  *ACL 2024 Main* [[GitHub](https://github.com/HBX-hbx/Mistral-Interact)]<br>
  <small>▸ Featured by [AK](https://x.com/arankomatsuzaki/status/1758315401782407584) (10k+ views)</small>

- [UltraFeedback: Boosting Language Models with High-quality Feedback](https://arxiv.org/pdf/2310.01377)<br>
  Ganqu Cui\*, Lifan Yuan\*, Ning Ding, Guanming Yao, **Bingxiang He**, Wei Zhu, Yuan Ni, Guotong Xie, Ruobing Xie, Yankai Lin, Zhiyuan Liu, Maosong Sun<br>
  *ICML 2024* [[GitHub 350+ Stars](https://github.com/OpenBMB/UltraFeedback)] [[Data]](https://huggingface.co/datasets/openbmb/UltraFeedback)<br>
  <small>▸ Featured by [Thomas Wolf](https://x.com/Thom_Wolf/status/1720503998518640703) (170k+ views)</small>

- [Beat LLMs at Their Own Game: Zero-Shot LLM-Generated Text Detection via Querying ChatGPT](https://aclanthology.org/2023.emnlp-main.463)<br>
  Biru Zhu, Lifan Yuan, Ganqu Cui, Yangyi Chen, Chong Fu, **Bingxiang He**, Yangdong Deng, Zhiyuan Liu, Maosong Sun, Ming Gu<br>
  *EMNLP 2023 Main* [[GitHub](https://github.com/thunlp/LLM-generated-text-detection)]

- [A Unified Evaluation of Textual Backdoor Learning: Frameworks and Benchmarks](https://arxiv.org/pdf/2206.08514)<br>
  Ganqu Cui\*, Lifan Yuan\*, **Bingxiang He**, Yangyi Chen, Zhiyuan Liu, Maosong Sun<br>
  *NeurIPS Datasets & Benchmarks 2022* **(Spotlight)** [[GitHub 200+ Stars]](https://github.com/thunlp/OpenBackdoor)

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2024.09 - present*, [Tsinghua University](https://www.tsinghua.edu.cn/)
  Ph.D. in Computer Science and Technology ([THUNLP](http://nlp.csai.tsinghua.edu.cn/))
- *2020.09 - 2024.06*, [Tsinghua University](https://www.tsinghua.edu.cn/)
  B.S. in Computer Science and Technology with honors

<span class='anchor' id='experience'></span>

# 💼 Experience

- *2026.03 - present*, [ModelBest (面壁智能)](https://www.modelbest.cn/), Beijing. Research Intern, Forward-Four Program (前进四计划). Working with [Postdoc Chaojun Xiao](https://xcjthu.github.io/). 
  - Post-training of the MiniCPM4 & MiniCPM5 series: SFT, RL, and on-policy distillation (OPD).
  - **AutoSFT**: a coding-agent that autonomously searches SFT data recipes; the SFT data engine of the pipeline.
  - **RL**: a minimal, stable RL recipe landed as MiniCPM5's math & reasoning RL; diagnosing and fixing training collapse.
  - **OPD**: co-developed the OPD recipe, integrated into MiniCPM5 as the cross-domain model-merging mechanism.

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
* CIE-Tencent Doctoral Research Incentive Project ([CIE](https://www.cie.org.cn/list_43/16649.html); [THUNLP](https://mp.weixin.qq.com/s/dy9IjlakI7vpFltGhu6llg); 中国电子学会-腾讯大模型博士生科研激励计划, 44 Recipients Nationwide, ¥100,000 Grant). *2026.07*
* Qingyuan InnoVibe 2026 (青源最受瞩目学术新星, 25 Winners Nationwide), [BAAI](https://mp.weixin.qq.com/s/VwzvuyToY79B2DtWmenjVQ), [THUNLP](https://mp.weixin.qq.com/s/mhkVUCZw8eGlc6glxuIudQ). *2026.06*
* ICML 2026 Gold Reviewer (Top 25%). *2026.05*
* Comprehensive Scholarship of Tsinghua University for 2024-2025, Dept. of CST (Top 10). *2025.12*
* Outstanding Graduate Award, Beijing Municipal Education Commission (Top 5%). *2024.06*
* Outstanding Paper Award for Diploma Project, Tsinghua University (Top 5%). *2024.06*
* Comprehensive Scholarship of Tsinghua University for 2022-2023, Dept. of CST (Top 10). *2023.10*
* 12·9 Scholarship of Tsinghua University for 2021-2022, Dept. of CST (Top 1). *2022.10*
* Third Prize in THU Challenge Cup Academic Competition, Tsinghua University. *2022.04*
* Comprehensive Scholarship of Tsinghua University for 2020-2021, Dept. of CST (Top 10). *2021.10*
* Second Prize in Freshmen Scholarship, Tsinghua University (Top 10 in Guangdong Province, Gaokao). *2020.09*

<span class='anchor' id='invited-talks'></span>

# 💬 Invited Talks

- [Rethinking OPD II: One-Shot OPD](https://arxiv.org/pdf/2609.04172). Paper walk-through on [YouTube](https://www.youtube.com/watch?v=gR-wGiTBd58). Featured by [Kian Kyars](https://x.com/neuralkian/status/2096467880909111300). *2026.08*
- [Rethinking OPD I](https://arxiv.org/pdf/2604.13016). Paper walk-through on [YouTube](https://www.youtube.com/watch?v=i7TqHMHlKQ0). Featured by [Kian Kyars](https://x.com/neuralkian/status/2091238980184392135). *2026.08*
- Three Boundaries for Scalable Reinforcement Learning. [Qingyuan InnoVibe 2026 in BAAI](https://event.baai.ac.cn/activities/1030). *2026.06*
- AMA (Ask Me Anything) for [Rethinking OPD I](https://arxiv.org/pdf/2604.13016). [QingKeAI](https://mp.weixin.qq.com/s/dgZ9Iy2ercIrynrdsXFOMA). *2026.05*
- Towards Scalable Reinforcement Learning for LLMs. [BAAI](https://event.baai.ac.cn/activities/1054). [NICE](https://weixin.qq.com/sph/A8w25KHX4r). *2026.05*
- How Far Can Unsupervised RLVR Scale LLM Training? [AI TIME](https://live.bilibili.com/21813994). [Synced](https://channels.weixin.qq.com/finder-preview/pages/sph?id=A9nMDqasTh). [QingKeAI](https://qingkeai.online/archives/urlvr-talk). *2026.04*
- JustRL: Scaling a 1.5B LLM with a Simple RL Recipe. [QingKeAI](https://qingkeai.online/archives/JustRL). *2026.02*
- The Right Time Matters: Data Arrangement Affects Zero-Shot Generalization in Instruction Tuning. [Alibaba Security](https://mp.weixin.qq.com/s/Ig_1I_3_U0L8P1PWJsIA2A). *2025.05*
- Tell me more! towards implicit user intention understanding of language model driven agents. Wiztalk. *2024.08*
<!-- - Tell me more! towards implicit user intention understanding of language model driven agents. ModelBest. *2024.04* -->

<span class='anchor' id='services'></span>

# 🛠️ Services

- **Conference Reviewer**: NeurIPS (2024 - 2025), ICLR (2025 - 2027), ICML (2025 - 2026), ACL ARR (2024 - 2026), COLM (2025 - 2026), COLM SCALR Workshop (2025), AAAI (2026), AISTATS (2025 - 2026), ICCV (2025)


<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

<div style="width:300px;margin:0 auto;text-align:center;">
<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=a1a0a3&w=a&t=tt&d=1TDvEahPmV3VuWyZ7W9mP_u5oVF0eoyT5LaJP0C-Oc4&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>
<!-- <script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?cl=aaaaaa&w=300&t=tt&d=REPLACE_WITH_YOUR_WIDGET_ID&co=ffffff&ct=666666&cmo=3acc3a&cmn=ff5353"></script> -->
</div>