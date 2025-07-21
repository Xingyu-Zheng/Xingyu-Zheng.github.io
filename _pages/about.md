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

## 2025


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/FOEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[First-Order Error Matters: Accurate Compensation for Quantized Large Language Models](https://arxiv.org/abs/2507.11017)

**Xingyu Zheng\***, Haotong Qin\*, Yuye Li, Jiakai Wang, Jinyang Guo, Michele Magno, Xianglong Liu$^{\dagger}$

[**Github**](https://github.com/Xingyu-Zheng/FOEM)
- This paper proposes FOEM, a novel PTQ method for LLM that explicitly incorporates first-order gradient terms to improve quantization error compensation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/LLM_Quant_Survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A Survey of Low-bit Large Language Models: Basics, Systems, and Algorithms](https://arxiv.org/abs/2409.16694)

Ruihao Gong, Yifu Ding, Zining Wang, Chengtao Lv, **Xingyu Zheng**, Jinyang Du, Haotong Qin, Jinyang Guo, Michele Magno, Xianglong Liu$^{\dagger}$

- This paper presents a comprehensive **survey of low-bit quantization methods tailored for LLMs**, covering the fundamental principles, system implementations, and algorithmic strategies.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/qwen3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[An Empirical Study of Qwen3 Quantization](https://arxiv.org/abs/2505.02214)

**Xingyu Zheng\***, Yuye Li\*, Haoran Chu\*, Yue Feng\*, Xudong Ma, Jie Luo, Jinyang Guo, Haotong Qin$^{\dagger}$, Michele Magno, Xianglong Liu

[**Github**](https://github.com/Efficient-ML/Qwen3-Quantization)   [**Hugging Face**](https://huggingface.co/collections/Efficient-ML/qwen3-quantization-68164450decb1c868788cb2b) 
- This paper explores Qwen3's capabilities when quantized to low bit-width, demonstrating its value in advancing future models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/BinaryDM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[BinaryDM: Accurate Weight Binarization for Efficient Diffusion Models](https://arxiv.org/abs/2404.05662)

**Xingyu Zheng**, Xianglong Liu$^{\dagger}$, Haotong Qin, Xudong Ma, Mingyuan Zhang, Haojie Hao, Jiakai Wang, Zixiang Zhao, Jinyang Guo, Michele Magno

[**Github**](https://github.com/Xingyu-Zheng/BinaryDM) [**PaddlePaddle**](https://github.com/PaddlePaddle/PaddleSlim/tree/develop/example/BinaryDM)
- This paper proposes **BinaryDM**, a novel accurate quantization-aware training approach to push the weights of diffusion models towards the limit of 1-bit.
</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/BiDM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[BiDM: Pushing the Limit of Quantization for Diffusion Models](https://arxiv.org/abs/2412.05926)

**Xingyu Zheng**, Xianglong Liu$^{\dagger}$, Yichen Bian, Xudong Ma, Yulun Zhang, Jiakai Wang, Jinyang Guo, Haotong Qin

[**Github**](https://github.com/Xingyu-Zheng/BiDM)

- This paper proposes a novel method, namely **BiDM**, for fully binarizing weights and activations of DMs, pushing quantization to the 1-bit limit.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Visual Intelligence</div><img src='images/LLaMA3-Quant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Empirical Study of LLaMA3 Quantization: From LLMs to MLLMs](https://link.springer.com/article/10.1007/s44267-024-00070-x)

Wei Huang\*, **Xingyu Zheng\***, Xudong Ma\*, Haotong Qin$^{\dagger}$, Chengtao Lv, Hong Chen, Jie Luo, Xiaojuan Qi, Xianglong Liu, Michele Magno

[**Github**](https://github.com/Macaronlin/LLaMA3-Quantization)   [**Hugging Face**](https://huggingface.co/LLMQ) 

- This paper explores LLaMA3's capabilities when quantized to low bit-width, demonstrating its value in advancing future models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024 (Oral)</div><img src='images/IR-QLoRA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Accurate LoRA-Finetuning Quantization of LLMs via Information Retention](https://arxiv.org/abs/2402.05445)

Haotong Qin\*, Xudong Ma\*, **Xingyu Zheng**, Xiaoyang Li, Yang Zhang, Shouda Liu, Jie Luo, Xianglong Liu$^{\dagger}$, Michele Magno

[**Github**](https://github.com/htqin/ir-qlora)
- This paper proposes a novel **IR-QLoRA** for pushing quantized LLMs with LoRA to be highly accurate through information retention.
</div>
</div>

## 2023

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/InI.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DIsolation and Induction: Training Robust Deep Neural Networks against Model Stealing Attacks](https://dl.acm.org/doi/abs/10.1145/3581783.3612092)

Jun Guo, **Xingyu Zheng**, Aishan Liu$^{\dagger}$, Siyuan Liang, Yisong Xiao, Yichao Wu, Xianglong Liu

[**Github**](https://github.com/DIG-Beihang/InI-Model-Stealing-Defense)
- This paper proposes Isolation and Induction (**InI**), a novel and effective training framework for model stealing defenses.
</div>
</div>

## Book

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCIS</div><img src='images/GLOW_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalizing from Limited Resources in the Open World](https://dl.acm.org/doi/abs/10.1145/3581783.3612092)

Jinyang Guo, Yuqing Ma, Yifu Ding, Ruihao Gong, **Xingyu Zheng**, Changyi He, Yantao Lu, Xianglong Liu

- This book presents the Proceedings from the Second International Workshop **GLOW 2024** held in conjunction with the International Joint Conference on Artificial Intelligence, IJCAI 2024, in Jeju Island, South Korea, in August 2024.
</div>
</div>


# 🎖 Honors
- *2025*, Tencent Rhino-Bird Elite Training Program.
- *2024*, Honor Student of Beihang University.
- *2024*, Excellent Undergraduate Graduation Thesis.
- *2024*, Excellent Graduate of Beihang University.
- *2022*, Lanqiao Cup, National First prize.

# 📖 Educations
- *2024 -  now*, PhD student, Zhongguancun Academy.
- *2024 -  now*, PhD student, Beihang University.
- *2020 - 2024*, Undergrad student, Beihang University.
