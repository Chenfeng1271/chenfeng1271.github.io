---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**I am actively looking for industry positions in MLLM pretraining, VLA, World Model, and related areas. Feel free to reach out via [email](mailto:chenfeng1271@gmail.com) if you are interested!**

Hi 👋, I am a final-year Ph.D. candidate  at the University of Adelaide, supervised by
[Prof. Bohan Zhuang](https://scholar.google.com.au/citations?user=DFuDBBwAAAAJ) and
[Prof. Qi Wu](https://scholar.google.com/citations?user=aKXe1FEAAAAJ&hl=en).

My research focuses on developing **efficient and scalable AI algorithms** for multimodal learning and image generation. Previously, I have worked on the following topics:

- **Long Context Efficiency of MLLMs** across inference, training, and post-training, including  [ZipVL](https://arxiv.org/abs/2410.08584), [OmniSparse](https://arxiv.org/abs/2511.12201), and [Sparsity Forcing](https://arxiv.org/abs/2504.18579).

- **Efficient Autoregressive Image Generation**, including [ZipAR](https://arxiv.org/abs/2412.04062) and [NAR](https://arxiv.org/abs/2503.10696).

Currently, my research focuses on **embodied learning**, with two main directions:

- **Efficient VLA**: improving *policy efficiency* by enabling VLA models to complete tasks with fewer action steps and over longer horizons, reducing redundant inference while maintaining robust task performance.

- **Physical-aware World Models**: building world models with a *3D Gaussian-aware tokenizer* for spatially grounded scene representation, and designing benchmarks at the level of *physical formulas* to evaluate whether models truly understand physical laws, towards [large-scale world simulation](https://arxiv.org/abs/2603.07145).


News
------
- **[2026.04]** 🎉 1 paper accepted to **IEEE Transactions on Affective Computing**.
- **[2026.04]** 🎉 2 papers accepted to **ACL 2026**.
- **[2026.03]** 🎉 4 papers accepted to **CVPR 2026**.



Work Experience
------
- **Research Intern**, TikTok, Sydney (Oct 2024 – Apr 2025)
- **Research Intern**, Ant Group, Hangzhou (Sep 2022 – Apr 2024)


Selected Publications
------

**Efficient MLLM**

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/beyond%20accuracy.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Beyond Accuracy: An Empirical Study of Perception Stability in Multimodal Large Language Models</strong><br>
    <strong>Feng Chen</strong>, Chenhui Gou, Yefei He, Yang Yang, Bohan Zhuang, Qi Wu<br>
    <em>CVPR Findings, 2026</em><br>
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/sparsity%20forcing.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Sparsity Forcing: Reinforcing Token Sparsity of MLLMs</strong><br>
    <strong>Feng Chen</strong>, Yefei He, Lequan Lin, Chenhui Gou, Jing Liu, Bohan Zhuang, Qi Wu<br>
    <em>ICLR, 2026</em><br>
    [<a href="https://arxiv.org/abs/2504.18579">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/omnisparse.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>OmniSparse: Training-Aware Fine-Grained Sparse Attention for Long-Video MLLMs</strong><br>
    <strong>Feng Chen</strong>, Yefei He, Shaoxuan He, Yuanyu He, Jing Liu, Lequan Lin, Akide Liu, Zhaoyang Li, Jiyuan Zhang, Zhenbang Sun, Bohan Zhuang, Qi Wu<br>
    <em>AAAI, 2026</em><br>
    [<a href="https://arxiv.org/abs/2511.12201">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/zipvl.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>ZipVL: Efficient Large Vision-Language Models with Dynamic Token Sparsification</strong><br>
    Yefei He, <strong>Feng Chen</strong>, Jing Liu, Wenqi Shao, Hong Zhou, Kaipeng Zhang, Bohan Zhuang<br>
    <em>ICCV, 2025</em><br>
    [<a href="https://arxiv.org/abs/2410.08584">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/MTI.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Less is More: Improving LLM Reasoning with Minimal Test-Time Intervention</strong><br>
    Zhen Yang, Mingyang Zhang, <strong>Feng Chen</strong>, Ganggui Ding, Liang Hou, Xin Tao, Ying-Cong Chen<br>
    <em>ACL, 2026</em><br>
    [<a href="https://arxiv.org/abs/2510.13940">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/ACT.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>ACT as Human: Multimodal Large Language Model Data Annotation with Critical Thinking</strong><br>
    Lequan Lin, Dai Shi, Andi Han, <strong>Feng Chen</strong>, Qiuzheng Chen, Jiawen Li, Zhaoyang Li, Jiyuan Li, Zhenbang Sun, Junbin Gao<br>
    <em>NeurIPS, 2025</em><br>
    [<a href="https://arxiv.org/abs/2511.09833">Paper</a>]
  </div>
</div>

**Efficient and Controllable World Model**

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/liveworld.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>LiveWorld: Simulating Out-of-Sight Dynamics in Generative Video World Models</strong><br>
    Zicheng Duan, Jiatong Xia, Zeyu Zhang, Wenbo Zhang, Gengze Zhou, Chenhui Gou, Yefei He, <strong>Feng Chen</strong> (Project Lead), Xinyu Zhang, Lingqiao Liu<br>
    <em>arXiv preprint, 2026</em><br>
    [<a href="https://arxiv.org/abs/2603.07145">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/chain_of_event.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Chain of Event-Centric Causal Thought for Physically Plausible Video Generation</strong><br>
    Zixuan Wang<sup>*</sup>, Yixin Hu<sup>*</sup>, Haolan Wang, <strong>Feng Chen</strong><sup>*</sup>, Yan Liu, Wen Li, Yinjie Lei &nbsp;<br>
    <em>CVPR, 2026</em><br>
    [<a href="https://arxiv.org/abs/2603.09094">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/NAR.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Neighboring Autoregressive Modeling for Efficient Visual Generation</strong><br>
    Yefei He<sup>*</sup>, Yuanyu He<sup>*</sup>, Shaoxuan He<sup>*</sup>, <strong>Feng Chen</strong><sup>*</sup>, Hong Zhou, Kaipeng Zhang, Bohan Zhuang &nbsp;(<sup>*</sup>Equal contribution)<br>
    <em>ICCV, 2025</em><br>
    [<a href="https://arxiv.org/abs/2503.10696">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/ZIPAR.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>ZipAR: Accelerating Auto-Regressive Image Generation through Spatial Locality</strong><br>
    Yefei He, <strong>Feng Chen</strong>, Yuanyu He, Shaoxuan He, Hong Zhou, Kaipeng Zhang, Bohan Zhuang<br>
    <em>ICML, 2025</em><br>
    [<a href="https://arxiv.org/abs/2412.04062">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/modular.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Training-free Dense-Aligned Diffusion Guidance for Modular Conditional Image Synthesis</strong><br>
    Zixuan Wang, Duo Peng, <strong>Feng Chen</strong>, Yuwei Yang, Yinjie Lei<br>
    <em>CVPR, 2025</em><br>
    [<a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_Training-free_Dense-Aligned_Diffusion_Guidance_for_Modular_Conditional_Image_Synthesis_CVPR_2025_paper.pdf">Paper</a>]
  </div>
</div>

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/motion.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Training-free Motion Factorization for Compositional Video Generation</strong><br>
    Zixuan Wang, Ziqin Zhou, <strong>Feng Chen</strong>, Duo Peng, Yixin Hu, Changsheng Li, Yinjie Lei<br>
    <em>CVPR, 2026</em><br>
    [<a href="https://arxiv.org/abs/2603.09104">Paper</a>]
  </div>
</div>

**Others**

<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/UEN.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Uncertainty-guided Learning for Improving Image Manipulation Detection</strong><br>
    Kaixiang Ji, <strong>Feng Chen</strong>, Xin Guo, Yadong Xu, Jian Wang, Jingdong Chen<br>
    <em>ICCV, 2023</em><br>
    [<a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Ji_Uncertainty-guided_Learning_for_Improving_Image_Manipulation_Detection_ICCV_2023_paper.pdf">Paper</a>]
  </div>
</div>



<div style="display:flex; align-items:flex-start; margin-bottom:24px;">
  <div style="flex-shrink:0; width:180px; margin-right:16px;">
    <img src="{{ site.baseurl }}/images/paper/BGA-MNER.png" style="width:100%; border-radius:4px;">
  </div>
  <div>
    <strong>Learning Implicit Entity-object Relations by Bidirectional Generative Alignment for Multimodal NER</strong><br>
    <strong>Feng Chen</strong>, Jiajia Liu, Kaixiang Ji, Wang Ren, Jian Wang, Jingdong Wang<br>
    <em>ACM MM, 2023</em><br>
    [<a href="https://arxiv.org/abs/2308.02570">Paper</a>]
  </div>
</div>

Professional Activities
------
- **Reviewer**: CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, IJCV


Awards
------

- **Jiangsu Province Outstanding Graduate**, 2021
- **Jiangsu Province Outstanding Master Thesis Award**, 2021
