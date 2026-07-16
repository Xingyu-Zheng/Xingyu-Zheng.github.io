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

<span class="anchor" id="about-me"></span>

<section class="hero-card">
  <div class="hero-card__eyebrow">Efficient ML / LLM Quantization / Diffusion Acceleration</div>
  <h1>Xingyu Zheng</h1>
  <p class="hero-card__lead">
    PhD student at Beihang University, supervised by Prof.
    <a href="https://xlliu-beihang.github.io/">Xianglong Liu</a>. My research focuses on making large AIGC models practical, especially through inference acceleration and model quantization for LLMs and diffusion models.
  </p>
  <div class="hero-card__actions">
    <a class="btn btn--primary" href="mailto:zhengxingyu@buaa.edu.cn">Email</a>
    <a class="btn btn--light-outline" href="https://scholar.google.com/citations?user=ISXNTf8AAAAJ">Google Scholar</a>
    <a class="btn btn--light-outline" href="https://github.com/Xingyu-Zheng">GitHub</a>
  </div>
</section>

<section class="overview-grid">
  <div class="overview-card">
    <span class="overview-card__label">Current</span>
    <strong>PhD student</strong>
    <p>Beihang University, 2024 - now.</p>
  </div>
  <div class="overview-card">
    <span class="overview-card__label">Focus</span>
    <strong>Efficient AIGC systems</strong>
    <p>Low-bit LLMs, post-training quantization, and fast diffusion sampling.</p>
  </div>
  <div class="overview-card">
    <span class="overview-card__label">Recent</span>
    <strong>MrFlow &amp; FOEM</strong>
    <p>Training-free diffusion acceleration and accurate LLM quantization compensation.</p>
  </div>
</section>

<section class="content-section" id="publications">
  <div class="section-heading">
    <span>Selected work</span>
    <h2>Publications</h2>
  </div>

  <h3 class="year-heading">2026</h3>

  <article class="paper-box featured-paper">
    <div class="paper-box-image">
      <div><div class="badge">arXiv</div><img src="images/mrflow.png" alt="MrFlow overview"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://arxiv.org/abs/2607.01642">Multi-Resolution Flow Matching: Training-Free Diffusion Acceleration via Staged Sampling</a></h4>
      <p><strong>Xingyu Zheng</strong>, Xianglong Liu<sup>&dagger;</sup>, Yifu Ding, Weilun Feng, Junqing Lin, Jinyang Guo, Haotong Qin</p>
      <p class="paper-links"><a href="https://github.com/Xingyu-Zheng/MrFlow"><strong>Github</strong></a> / <a href="https://huggingface.co/papers/2607.01642"><strong>Hugging Face</strong></a></p>
      <p>This paper proposes a training-free multi-resolution strategy, <strong>MrFlow</strong>, for accelerating image generation, achieving faithful generation with up to 10x end-to-end speedup.</p>
    </div>
  </article>

  <article class="paper-box">
    <div class="paper-box-image">
      <div><div class="badge">Visual Intelligence</div><img src="images/qwen3.png" alt="Qwen3 quantization"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://link.springer.com/article/10.1007/s44267-026-00114-4">An Empirical Study of Qwen3 Quantization</a></h4>
      <p><strong>Xingyu Zheng</strong>, Yuye Li, Haoran Chu, Yue Feng, Xudong Ma, Jie Luo, Jinyang Guo, Haotong Qin<sup>&dagger;</sup>, Michele Magno, Xianglong Liu</p>
      <p class="paper-links"><a href="https://github.com/Efficient-ML/Qwen3-Quantization"><strong>Github</strong></a> / <a href="https://huggingface.co/collections/Efficient-ML/qwen3-quantization-68164450decb1c868788cb2b"><strong>Hugging Face</strong></a></p>
      <p>This paper explores <strong>Qwen3's capabilities when quantized</strong> to low bit-width, demonstrating its value in advancing future models.</p>
    </div>
  </article>

  <article class="paper-box featured-paper">
    <div class="paper-box-image">
      <div><div class="badge">AAAI 2026</div><img src="images/FOEM.png" alt="FOEM overview"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://arxiv.org/abs/2507.11017">First-Order Error Matters: Accurate Compensation for Quantized Large Language Models</a></h4>
      <p><strong>Xingyu Zheng*</strong>, Haotong Qin*, Yuye Li, Haoran Chu, Jiakai Wang, Jinyang Guo, Michele Magno, Xianglong Liu<sup>&dagger;</sup></p>
      <p class="paper-links"><a href="https://github.com/ModelCloud/GPTQModel"><strong>GPTQModel</strong></a> / <a href="https://github.com/Xingyu-Zheng/FOEM"><strong>Github</strong></a> / <a href="https://huggingface.co/Xingyu-Zheng/models?sort=downloads"><strong>Hugging Face</strong></a> / <a href="https://github.com/PaddlePaddle/PaddleNLP/pull/10958/commits/b84d22ff499f72434d1c7cb095207d562b2693c8"><strong>PaddlePaddle</strong></a></p>
      <p>This paper proposes <strong>FOEM</strong>, a novel PTQ method for LLM that explicitly incorporates first-order gradient terms to improve quantization error compensation.</p>
    </div>
  </article>

  <h3 class="year-heading">2025</h3>

  <article class="paper-box">
    <div class="paper-box-image">
      <div><div class="badge">Neural Networks</div><img src="images/LLM_Quant_Survey.png" alt="LLM quantization survey"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://arxiv.org/abs/2409.16694">A Survey of Low-bit Large Language Models: Basics, Systems, and Algorithms</a></h4>
      <p>Ruihao Gong, Yifu Ding, Zining Wang, Chengtao Lv, <strong>Xingyu Zheng</strong>, Jinyang Du, Haotong Qin, Jinyang Guo, Michele Magno, Xianglong Liu<sup>&dagger;</sup></p>
      <p>This paper presents a comprehensive <strong>survey of low-bit quantization methods tailored for LLMs</strong>, covering the fundamental principles, system implementations, and algorithmic strategies.</p>
    </div>
  </article>

  <article class="paper-box featured-paper">
    <div class="paper-box-image">
      <div><div class="badge">ICLR 2025</div><img src="images/BinaryDM.png" alt="BinaryDM overview"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://arxiv.org/abs/2404.05662">BinaryDM: Accurate Weight Binarization for Efficient Diffusion Models</a></h4>
      <p><strong>Xingyu Zheng</strong>, Xianglong Liu<sup>&dagger;</sup>, Haotong Qin, Xudong Ma, Mingyuan Zhang, Haojie Hao, Jiakai Wang, Zixiang Zhao, Jinyang Guo, Michele Magno</p>
      <p class="paper-links"><a href="https://github.com/Xingyu-Zheng/BinaryDM"><strong>Github</strong></a> / <a href="https://github.com/PaddlePaddle/PaddleSlim/tree/develop/example/BinaryDM"><strong>PaddlePaddle</strong></a></p>
      <p>This paper proposes <strong>BinaryDM</strong>, a novel accurate quantization-aware training approach to push the weights of diffusion models towards the limit of 1-bit.</p>
    </div>
  </article>

  <h3 class="year-heading">2024</h3>

  <article class="paper-box featured-paper">
    <div class="paper-box-image">
      <div><div class="badge">NeurIPS 2024</div><img src="images/BiDM.png" alt="BiDM overview"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://arxiv.org/abs/2412.05926">BiDM: Pushing the Limit of Quantization for Diffusion Models</a></h4>
      <p><strong>Xingyu Zheng</strong>, Xianglong Liu<sup>&dagger;</sup>, Yichen Bian, Xudong Ma, Yulun Zhang, Jiakai Wang, Jinyang Guo, Haotong Qin</p>
      <p class="paper-links"><a href="https://github.com/Xingyu-Zheng/BiDM"><strong>Github</strong></a></p>
      <p>This paper proposes a novel method, namely <strong>BiDM</strong>, for fully binarizing weights and activations of DMs, pushing quantization to the 1-bit limit.</p>
    </div>
  </article>

  <article class="paper-box">
    <div class="paper-box-image">
      <div><div class="badge">Visual Intelligence</div><img src="images/LLaMA3-Quant.png" alt="LLaMA3 quantization"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://link.springer.com/article/10.1007/s44267-024-00070-x">An Empirical Study of LLaMA3 Quantization: From LLMs to MLLMs</a></h4>
      <p>Wei Huang*, <strong>Xingyu Zheng*</strong>, Xudong Ma*, Haotong Qin<sup>&dagger;</sup>, Chengtao Lv, Hong Chen, Jie Luo, Xiaojuan Qi, Xianglong Liu, Michele Magno</p>
      <p class="paper-links"><a href="https://github.com/Macaronlin/LLaMA3-Quantization"><strong>Github</strong></a> / <a href="https://huggingface.co/LLMQ"><strong>Hugging Face</strong></a></p>
      <p>This paper explores LLaMA3's capabilities when quantized to low bit-width, demonstrating its value in advancing future models.</p>
    </div>
  </article>

  <article class="paper-box">
    <div class="paper-box-image">
      <div><div class="badge">ICML 2024 Oral</div><img src="images/IR-QLoRA.jpg" alt="IR-QLoRA overview"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://arxiv.org/abs/2402.05445">Accurate LoRA-Finetuning Quantization of LLMs via Information Retention</a></h4>
      <p>Haotong Qin*, Xudong Ma*, <strong>Xingyu Zheng</strong>, Xiaoyang Li, Yang Zhang, Shouda Liu, Jie Luo, Xianglong Liu<sup>&dagger;</sup>, Michele Magno</p>
      <p class="paper-links"><a href="https://github.com/htqin/ir-qlora"><strong>Github</strong></a> / <a href="https://github.com/PaddlePaddle/PaddleNLP/pull/10958/commits/32ac577526940ba5532a1ddd771094fe49cec50f"><strong>PaddlePaddle</strong></a></p>
      <p>This paper proposes a novel <strong>IR-QLoRA</strong> for pushing quantized LLMs with LoRA to be highly accurate through information retention.</p>
    </div>
  </article>

  <h3 class="year-heading">2023</h3>

  <article class="paper-box">
    <div class="paper-box-image">
      <div><div class="badge">ACM MM 2023</div><img src="images/InI.jpg" alt="InI overview"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://dl.acm.org/doi/abs/10.1145/3581783.3612092">Disolation and Induction: Training Robust Deep Neural Networks against Model Stealing Attacks</a></h4>
      <p>Jun Guo, <strong>Xingyu Zheng</strong>, Aishan Liu<sup>&dagger;</sup>, Siyuan Liang, Yisong Xiao, Yichao Wu, Xianglong Liu</p>
      <p class="paper-links"><a href="https://github.com/DIG-Beihang/InI-Model-Stealing-Defense"><strong>Github</strong></a></p>
      <p>This paper proposes Isolation and Induction (<strong>InI</strong>), a novel and effective training framework for model stealing defenses.</p>
    </div>
  </article>

  <h3 class="year-heading">Book</h3>

  <article class="paper-box">
    <div class="paper-box-image">
      <div><div class="badge">CCIS</div><img src="images/GLOW_2024.png" alt="GLOW 2024 book"></div>
    </div>
    <div class="paper-box-text">
      <h4><a href="https://link.springer.com/book/9789819606328">Generalizing from Limited Resources in the Open World</a></h4>
      <p>Jinyang Guo, Yuqing Ma, Yifu Ding, Ruihao Gong, <strong>Xingyu Zheng</strong>, Changyi He, Yantao Lu, Xianglong Liu</p>
      <p>This book presents the proceedings from the Second International Workshop <strong>GLOW 2024</strong>, held in conjunction with IJCAI 2024 in Jeju Island, South Korea.</p>
    </div>
  </article>
</section>

<section class="timeline-grid">
  <div class="timeline-card" id="honors">
    <div class="section-heading compact">
      <span>Honors</span>
      <h2>Awards</h2>
    </div>
    <ul>
      <li><strong>2026</strong>, ByteDance Global Frontier Tech Recruitment Program (字节跳动前沿技术领域人才计划; formerly ByteDance Soaring Star Talent Program, 筋斗云人才计划).</li>
      <li><strong>2025</strong>, Tencent Rhino-Bird Elite Training Program (腾讯犀牛鸟精英人才计划).</li>
      <li><strong>2024</strong>, Honor Student of Beihang University.</li>
      <li><strong>2024</strong>, Excellent Undergraduate Graduation Thesis.</li>
      <li><strong>2024</strong>, Excellent Graduate of Beihang University.</li>
      <li><strong>2022</strong>, Lanqiao Cup, National First Prize.</li>
    </ul>
  </div>

  <div class="timeline-card" id="educations">
    <div class="section-heading compact">
      <span>Education</span>
      <h2>Background</h2>
    </div>
    <ul>
      <li><strong>2024 - now</strong>, PhD student, Beihang University.</li>
      <li><strong>2020 - 2024</strong>, Undergraduate student, Beihang University.</li>
    </ul>
  </div>

  <div class="timeline-card" id="activities">
    <div class="section-heading compact">
      <span>Service</span>
      <h2>Activities</h2>
    </div>
    <ul>
      <li><strong>2025.08</strong>, Organizer, <a href="https://practical-dl.github.io/">Practical-DL 2025</a>.</li>
      <li><strong>2024.08</strong>, Publicity Chair, <a href="https://glow-ijcai.github.io/">GLOW 2024</a>.</li>
    </ul>
  </div>

  <div class="timeline-card" id="internships">
    <div class="section-heading compact">
      <span>Experience</span>
      <h2>Internships</h2>
    </div>
    <ul>
      <li><strong>2026.07 - now</strong>, ByteDance, Beijing.</li>
      <li><strong>2025.08 - 2026.07</strong>, Tencent, Shanghai.</li>
    </ul>
  </div>
</section>
