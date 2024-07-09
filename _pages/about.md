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

I am a PhD student at Beihang University, supervised by Prof. [Xianglong Liu](https://xlliu-beihang.github.io/). I am currently focused on the practical application of large AIGC models such as LLM and Diffusion, including inference acceleration and model quantization. I hope that advanced technological methods can truly bring convenience to people's lives.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/LLaMA3-Quant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[How Good Are Low-bit Quantized LLaMA3 Models? An Empirical Study](https://arxiv.org/abs/2404.14047)

Wei Huang\*, Xudong Ma\*, Haotong Qin, **Xingyu Zheng**, Chengtao Lv, Hong Chen, Jie Luo, Xiaojuan Qi, Xianglong Liu, Michele Magno

[**Github**](https://github.com/Macaronlin/LLaMA3-Quantization)   [**Hugging Face**](https://huggingface.co/LLMQ) 
- This paper explores LLaMA3's capabilities when quantized to low bit-width, demonstrating its value in advancing future models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/BinaryDM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Accurate Binarization of Diffusion Model](https://arxiv.org/abs/2404.05662)

**Xingyu Zheng\***, Haotong Qin\*, Xudong Ma, Mingyuan Zhang, Haojie Hao, Jiakai Wang, Zixiang Zhao, Jinyang Guo, Xianglong Liu

[**Github**](https://github.com/Xingyu-Zheng/BinaryDM)
- This paper proposes **BinaryDM**, a novel accurate quantization-aware training approach to push the weights of diffusion models towards the limit of 1-bit.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/IR-QLoRA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accurate LoRA-Finetuning Quantization of LLMs via Information Retention](https://arxiv.org/abs/2402.05445)

Haotong Qin\*, Xudong Ma\*, **Xingyu Zheng**, Xiaoyang Li, Yang Zhang, Shouda Liu, Jie Luo, Xianglong Liu, Michele Magno

[**Github**](https://github.com/htqin/ir-qlora)
- This paper proposes a novel **IR-QLoRA** for pushing quantized LLMs with LoRA to be highly accurate through information retention.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/InI.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DIsolation and Induction: Training Robust Deep Neural Networks against Model Stealing Attacks](https://dl.acm.org/doi/abs/10.1145/3581783.3612092)

Jun Guo, **Xingyu Zheng**, Aishan Liu, Siyuan Liang, Yisong Xiao, Yichao Wu, Xianglong Liu

[**Github**](https://github.com/DIG-Beihang/InI-Model-Stealing-Defense)
- This paper proposes Isolation and Induction (**InI**), a novel and effective training framework for model stealing defenses.
</div>
</div>

# 🎖 Honors
- *2024*, Excellent Undergraduate Graduation Thesis.
- *2024*, Excellent Graduate of Beihang University.
- *2022*, Lanqiao Cup, National First prize.

# 📖 Educations
- *2024 -  now*, PhD student, Beihang University. 
- *2020 - 2024*, Undergrad student, Beihang University. 
