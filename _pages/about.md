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

I am a senior student at Beihang University, supervised by Prof. [Xianglong Liu](https://xlliu-beihang.github.io/). After participating in adversarial learning, I'm currently devoted to the quantization of pretrained large models. I hope to gain a deeper understanding of models, and in turn make them more efficient and robust.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/BinaryDM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BinaryDM: Towards Accurate Binarization of Diffusion Model](https://arxiv.org/abs/2404.05662)

**Xingyu Zheng\***, Haotong Qin\*, Xudong Ma, Mingyuan Zhang, Haojie Hao, Jiakai Wang, Zixiang Zhao, Jinyang Guo, Xianglong Liu

[**Project**](https://github.com/Xingyu-Zheng/BinaryDM)
- This paper proposes **BinaryDM**, a novel accurate quantization-aware training approach to push the weights of diffusion models towards the limit of 1-bit.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/IR-QLoRA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accurate LoRA-Finetuning Quantization of LLMs via Information Retention](https://arxiv.org/abs/2402.05445)

Haotong Qin\*, Xudong Ma\*, **Xingyu Zheng**, Xiaoyang Li, Yang Zhang, Shouda Liu, Jie Luo, Xianglong Liu, Michele Magno

[**Project**](https://github.com/htqin/ir-qlora)
- This paper proposes a novel **IR-QLoRA** for pushing quantized LLMs with LoRA to be highly accurate through information retention.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/InI.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DIsolation and Induction: Training Robust Deep Neural Networks against Model Stealing Attacks](https://dl.acm.org/doi/abs/10.1145/3581783.3612092)

Jun Guo, **Xingyu Zheng**, Aishan Liu, Siyuan Liang, Yisong Xiao, Yichao Wu, Xianglong Liu

[**Project**](https://github.com/DIG-Beihang/InI-Model-Stealing-Defense)
- This paper proposes Isolation and Induction (**InI**), a novel and effective training framework for model stealing defenses.
</div>
</div>

# 📖 Educations
- *2020.09 - 2024.06 (now)*, Beihang University, Beijing. 
