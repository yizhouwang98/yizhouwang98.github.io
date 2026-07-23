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

I am a second-year Ph.D. student at [MMLab](http://mmlab.ie.cuhk.edu.hk/), The Chinese University of Hong Kong, supervised by Prof. [Wanli Ouyang](https://wlouyang.github.io/). 
Before that, I received Master's degree in 2023 and Bachelor's degree in 2020 from [Zhejiang University](https://www.zju.edu.cn/english/).

My research focuses on **multimodal foundation models** and **unified generation and recognition**. I have led or co-led multiple projects building generalist models that bridge perception and generation: from human-centric unified models ([Hulk](https://arxiv.org/pdf/2312.01697), [UniHCP](https://openaccess.thecvf.com/content/CVPR2023/papers/Ci_UniHCP_A_Unified_Model_for_Human-Centric_Perceptions_CVPR_2023_paper.pdf)) to multimodal LLM detection ([DetToolChain](https://arxiv.org/pdf/2403.12488)) to scientific foundation models ([SciReasoner](https://arxiv.org/pdf/2509.21320), an 8B LLM for scientific reasoning open-sourced on [HuggingFace](https://huggingface.co/SciReason/SciReasoner-8B)) spanning protein, material, and molecular domains. I have published 10+ papers at top venues including TPAMI, CVPR, ICCV, NeurIPS, and ECCV.

I am actively seeking **research internship and full-time opportunities** in multimodal large models and unified generation-recognition systems. Feel free to reach out via [email](mailto:yizhouwang@link.cuhk.edu.hk).


# 🔥 News
- *2026.07*: &nbsp; We release [Accurate, Interdisciplinary and Transparent Structure-property Understanding with Deep Native Structural Reasoning](https://arxiv.org/abs/2607.07708), a further step of SciReasoner. We propose **native structural reasoning**, making protein structures, crystal structures, and molecular topology first-class citizens in scientific LLM reasoning, achieving state-of-the-art on 67 of 86 benchmarks. [[project](https://scireasoner.github.io/)]
- *2026.05*: &nbsp; [LECTOR](https://arxiv.org/abs/2605.25964) is accepted by ICML 2026.
- *2025.09*: &nbsp; As the student project lead, I directed the development of [SciReasoner](https://arxiv.org/pdf/2509.21320), an 8B scientific reasoning foundation model that explicitly elicits scientific reasoning and supports five capability families with up to 103 tasks. The model, instruct tuning datasets and the evaluation code are open-sourced at [huggingface](https://huggingface.co/SciReason) and [github](https://github.com/open-sciencelab/SciReason).
- *2025.06*: &nbsp; [EgoAgent](https://arxiv.org/pdf/2502.05857) and [CMT](https://arxiv.org/pdf/2504.20830) are accepted by ICCV 2025.
- *2025.05*: &nbsp; We will host the [1st Workshop on Interactive Human-centric Foundation Models](https://i-hfm-2025.github.io/I-HFM-2025/) at ICCV 2025, Honolulu, HI, USA.
- *2025.03*: &nbsp; A survey about [Human-Centric Foundation Models](https://arxiv.org/pdf/2502.08556) is accepted by IJCAI 2025.
- *2025.03*: &nbsp; [Hulk](https://arxiv.org/pdf/2312.01697) is accepted by TPAMI.
- *2025.02*: &nbsp; [Instruct-ReID++](https://arxiv.org/pdf/2405.17790) is accepted by TPAMI.
- *2025.02*: &nbsp; We release a [survey paper](https://arxiv.org/pdf/2502.08556) on human-centric foundation models.
- *2024.08*: &nbsp; I join MMLab, CUHK as a Ph.D. student.

<details class="news-more" markdown="1">
<summary>Show more news</summary>

- *2024.07*: &nbsp; [Dettoolchain](https://arxiv.org/pdf/2403.12488) is accepted by ECCV 2024.
- *2024.03*: &nbsp; [Instruct-ReID](https://openaccess.thecvf.com/content/CVPR2024/papers/He_Instruct-ReID_A_Multi-purpose_Person_Re-identification_Task_with_Instructions_CVPR_2024_paper.pdf) is accepted by CVPR 2024.
- *2023.03*: &nbsp; [UniHCP](https://openaccess.thecvf.com/content/CVPR2023/papers/Ci_UniHCP_A_Unified_Model_for_Human-Centric_Perceptions_CVPR_2023_paper.pdf) and [HumanBanch](https://openaccess.thecvf.com/content/CVPR2023/papers/Tang_HumanBench_Towards_General_Human-Centric_Perception_With_Projector_Assisted_Pretraining_CVPR_2023_paper.pdf) are accepted by CVPR 2023.
- *2022.09*: &nbsp; One paper is accepted by NeurIPS 2022.
- *2022.07*: &nbsp; I am named as one of the Outstanding Reviewers of ICML 2022.
- *2022.07*: &nbsp; One paper is accepted by ECCV 2022.
- *2022.03*: &nbsp; One paper is accepted by CVPR 2022.

</details>

# 📝Selective Publications 
(* equal contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/scireasoner_partE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accurate, Interdisciplinary and Transparent Structure-property Understanding with Deep Native Structural Reasoning](https://arxiv.org/abs/2607.07708)

Chen Tang, **Yizhou Wang**, Jianyu Wu, Lintao Wang, Shixiang Tang, Pengze Li, Encheng Su, Jun Yao, Jiabei Xiao, Yuqi Shi, Jielan Li, Hongxia Hao, Zhangyang Gao, Fang Wu, Ben Fei, Xiangyu Yue, Pan Tan, Bozitao Zhong, Jinouwen Zhang, Aoran Wang, Yan Lu, Jiaheng Liu, Xinzhu Ma, Liang Hong, Mingyue Zheng, Phil Torr, Bowen Zhou, Wanli Ouyang, Lei Bai

A further step of SciReasoner. We propose **native structural reasoning**, making protein structures, crystal structures, and molecular topology first-class citizens of scientific LLM reasoning: coordinates, topologies, and periodic connectivities are discretized into a unified structure-aware vocabulary so that structural tokens become addressable evidence units. SciReasoner achieves state-of-the-art on 67 of 86 benchmarks (e.g., improving Gene Ontology Cellular Component F_max from 0.42 to 0.55 on low-homology proteins and single-step retrosynthesis accuracy from 0.63 to 0.72), and double-blind expert evaluation rates its reasoning traces preferred or comparable to a frontier LLM in 98% of cases.

[project](https://scireasoner.github.io/)/[pdf](https://arxiv.org/abs/2607.07708)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/lector.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LECTOR: Joint Optimization of Scientific Reasoning Graphs and Introduction Generation](https://arxiv.org/abs/2605.25964)

Jiabei Xiao, **Yizhou Wang**, Chen Tang, Pengze Li, Wanli Ouyang, Shixiang Tang

We reframe scientific Introduction writing as a joint reasoning-and-structuring problem. LECTOR is a Logic-Expression Co-Reinforcement Learning framework that first builds a verifiable logic-reasoning graph from the paper body, then co-optimizes graph structural fidelity and narrative quality, substantially reducing citation hallucination.

[pdf](https://arxiv.org/abs/2605.25964)/[code](https://github.com/Xiao-Youth/LECTOR)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/scireasoner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SciReasoner: Laying the Scientific Reasoning Ground Across Disciplines](https://arxiv.org/pdf/2509.21320)

**Yizhou Wang**, Chen Tang, Han Deng, Jiabei Xiao, Jiaqi Liu, Jianyu Wu, Jun Yao, Pengze Li, Encheng Su, Lintao Wang, Guohang Zhuang, Yuchen Ren, Ben Fei, Ming Hu, Xin Chen, Dongzhan Zhou, Junjun He, Xiangyu Yue, Zhenfei Yin, Jiamin Wu, Qihao Zheng, Yuhao Zhou, Huihui Xu, Chenglong Ma, Yan Lu, Wenlong Zhang, Chunfeng Song, Philip Torr, Shixiang Tang, Xinzhu Ma, Wanli Ouyang, Lei Bai

[pdf](https://arxiv.org/pdf/2509.21320)/[code](https://github.com/open-sciencelab/SciReason)/[data and model](https://huggingface.co/SciReason)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/egoagent.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EgoAgent: A Joint Predictive Agent Model in Egocentric Worlds](https://arxiv.org/pdf/2502.05857)

Lu Chen\*, **Yizhou Wang**\*, Shixiang Tang, Qianhong Ma, Tong He, Wanli Ouyang, Xiaowei Zhou, Hujun Bao, Sida Peng

[project](https://egoagent.github.io/)/[pdf](https://arxiv.org/pdf/2502.05857)/[code](https://github.com/zju3dv/EgoAgent)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/hulk.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hulk: A universal knowledge translator for human-centric tasks](https://arxiv.org/pdf/2312.01697)

**Yizhou Wang**, Yixuan Wu, Shixiang Tang, Weizhen He, Xun Guo, Feng Zhu, Lei Bai, Rui Zhao, Jian Wu, Tong He, Wanli Ouyang

[project](https://humancentricmodels.github.io/Hulk/)/[pdf](https://arxiv.org/pdf/2312.01697)/[code](https://github.com/OpenGVLab/Hulk)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/dettoolchain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dettoolchain: A new prompting paradigm to unleash detection ability of mllm](https://arxiv.org/pdf/2403.12488)

Yixuan Wu\*, **Yizhou Wang**\*, Shixiang Tang, Wenhao Wu, Tong He, Wanli Ouyang, Philip Torr, Jian Wu 

[pdf](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04682.pdf)/[code](https://github.com/yixuan730/DetToolChain)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/Unihcp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unihcp: A unified model for human-centric perceptions](https://openaccess.thecvf.com/content/CVPR2023/papers/Ci_UniHCP_A_Unified_Model_for_Human-Centric_Perceptions_CVPR_2023_paper.pdf)

Yuanzheng Ci\*, **Yizhou Wang**\*, Meilin Chen, Shixiang Tang, Lei Bai, Feng Zhu, Rui Zhao, Fengwei Yu, Donglian Qi, Wanli Ouyang

[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Ci_UniHCP_A_Unified_Model_for_Human-Centric_Perceptions_CVPR_2023_paper.pdf)/[code](https://github.com/OpenGVLab/UniHCP)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/joindet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unsupervised object detection pretraining with joint object priors generation and detector learning](https://proceedings.neurips.cc/paper_files/paper/2022/file/50ca96a1a9ebe0b5e5688a504feb6107-Paper-Conference.pdf)

**Yizhou Wang**\*, Meilin Chen\*, Shixiang Tang, Feng Zhu, Haiyang Yang, Lei Bai, Rui Zhao, Yunfeng Yan, Donglian Qi, Wanli Ouyang

[pdf](https://proceedings.neurips.cc/paper_files/paper/2022/file/50ca96a1a9ebe0b5e5688a504feb6107-Paper-Conference.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/revisit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revisiting the Transferability of Supervised Pretraining: an MLP Perspective](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Revisiting_the_Transferability_of_Supervised_Pretraining_An_MLP_Perspective_CVPR_2022_paper.pdf)

**Yizhou Wang**\*, Shixiang Tang\*, Feng Zhu, Lei Bai, Rui Zhao, Donglian Qi, Wanli Ouyang

[pdf](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Revisiting_the_Transferability_of_Supervised_Pretraining_An_MLP_Perspective_CVPR_2022_paper.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/instruct_reid++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Instruct-ReID++: Towards Universal Purpose Instruction-Guided Person Re-identification](https://arxiv.org/pdf/2405.17790)

Weizhen He, Yiheng Deng, Yunfeng Yan, Feng Zhu, **Yizhou Wang**, Lei Bai, Qingsong Xie, Rui Zhao, Donglian Qi, Wanli Ouyang, Shixiang Tang

[pdf](https://arxiv.org/pdf/2405.17790)/[code](https://github.com/hwz-zju/Instruct-ReID)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/HumanBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Humanbench: Towards general human-centric perception with projector assisted pretraining](https://openaccess.thecvf.com/content/CVPR2023/papers/Tang_HumanBench_Towards_General_Human-Centric_Perception_With_Projector_Assisted_Pretraining_CVPR_2023_paper.pdf)

Shixiang Tang, Cheng Chen, Qingsong Xie, Meilin Chen, **Yizhou Wang**, Yuanzheng Ci, Lei Bai, Feng Zhu, Haiyang Yang, Li Yi, Rui Zhao, Wanli Ouyang

[pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Tang_HumanBench_Towards_General_Human-Centric_Perception_With_Projector_Assisted_Pretraining_CVPR_2023_paper.pdf)/[code](https://github.com/OpenGVLab/HumanBench)

</div>
</div>



# 🎖 Honors and Awards
- *2023.03* Excellent Postgraduate of Zhejiang University.
- *2023.03* Youxian Sun Scholarship (Top 1 in the Master’s class of College of Electrical Engineering)
- *2022.07* **Outstanding Reviewers** of ICML 2022.

# 📖 Educations
- *2024.09 - Now*, Ph.D., The Chinese University of Hong Kong, Hong Kong SAR, China.
- *2020.09 - 2023.03*, Master, Zhejiang University, Hangzhou, China.
- *2016.09 - 2020.06*, Undergraduate, Zhejiang University, Hangzhou, China.

# 🧑‍🔬 Academic Service
- **Reviewer**: CVPR, ICCV, ECCV, NeurIPS, ICLR, AAAI, ICML, etc.
- **Organizer / Program Chair**: [1st Workshop on Interactive Human-centric Foundation Models (I-HFM)](https://i-hfm-2025.github.io/I-HFM-2025/), ICCV 2025.

[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

# 💻 Internships
- *2023.01 - Now*, Shanghai AI Laboratory, China.
- *2021.03 - 2022.12*, SenseTime, China.