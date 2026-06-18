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
[A/Prof. Bohan Zhuang](https://ziplab.co/people/) and
[A/Prof. Qi Wu](https://scholar.google.com/citations?user=aKXe1FEAAAAJ&hl=en).

My research focuses on developing **efficient and scalable AI algorithms** for multimodal understanding and image generation. Previously, I have worked on the following topics:

- **Long Context Efficiency of MLLMs** across inference, training, and post-training, including  [ZipVL](https://arxiv.org/abs/2410.08584), [OmniSparse](https://arxiv.org/abs/2511.12201), and [Sparsity Forcing](https://arxiv.org/abs/2504.18579).

- **Efficient Autoregressive Image Generation** with speculative decoding, parallel pretrain and post-training distillation, including [ZipAR](https://arxiv.org/abs/2412.04062), [NAR](https://arxiv.org/abs/2503.10696) and [FlashAR](https://lxazjk.github.io/FlashAR/).

Currently, my research focuses on **embodied learning**, with two main directions:

- **Efficient VLA/WAM**: improving *policy efficiency* by enabling VLA/WAM models to complete tasks with fewer action steps and over longer horizons, reducing redundant inference while maintaining robust task performance.

- **3D-aware Physical World Models**: building world models with a *3D Gaussian-aware tokenizer* for spatially grounded scene representation, and designing benchmarks at the level of *physical formulas* to evaluate whether models truly understand physical laws, towards [large-scale world simulation](https://arxiv.org/abs/2603.07145).

**We are looking for highly self-motivated Master, PhD students and interns. If you are interested in joining us, please feel free to contact us with your CV as the [post](https://ziplab.co/uploads/zip-lab-poster-full.html)!**


News
------
- **[2026.06]** 🎉 4 papers accepted to **ECCV 2026**.
- **[2026.06]** Our latent 3D memory for video world model is now [released](https://microsoft.github.io/LatentSpatialMemory/).
- **[2026.05]** Our **A<sup>3</sup>**, a dynamic execution horizon method for VLA, is now [released](https://inceptionwang.github.io/A3/).
- **[2026.05]** Our **FlashAR**, a post-training acceleration for AR image generationm, is now [released](https://lxazjk.github.io/FlashAR/).
- **[2026.04]** 🎉 1 paper accepted to **IEEE TAFFC**.
- **[2026.04]** 🎉 2 papers accepted to **ACL 2026**.
- **[2026.03]** 🎉 4 papers accepted to **CVPR 2026**.



Work Experience
------
- **Research Intern**, TikTok, Sydney (Oct 2024 – Apr 2025)
- **Research Intern**, Ant Group, Hangzhou (Sep 2022 – Apr 2024)


Preprint
------
<div class="publication-list__item">
  <div class="publication-list__venue">arXiv</div>
  <div class="publication-list__body">
    <strong>Latent Spatial Memory for Video World Models</strong><br>
    Weijie Wang, Haoyu Zhao, Yifan Yang, <strong>Feng Chen</strong>, Zeyu Zhang, Yefei He, Zicheng Duan, Donny Y. Chen, Yuqing Yang, Bohan Zhuang<br>
    <em>arXiv preprint, 2026</em><br>
    [<a href="https://arxiv.org/abs/2606.09828">Paper</a>] [<a href="https://aka.ms/latent-spatial-memory">Project</a>] [<a href="https://github.com/microsoft/LatentSpatialMemory">Code</a>] [<a href="https://huggingface.co/papers/2606.09828">Hugging Face</a>]
  </div>
</div>


<div class="publication-list__item">
  <div class="publication-list__venue">arXiv</div>
  <div class="publication-list__body">
    <strong>FlashAR: Efficient Post-Training Acceleration for Autoregressive Image Generation</strong><br>
    Junkang Zhou<sup>*</sup>, Yefei He<sup>*</sup>, <strong>Feng Chen</strong><sup>*</sup>, Weijie Wang, Bohan Zhuang &nbsp;<br>
    <em>arXiv preprint, 2026</em><br>
    [<a href="https://arxiv.org/pdf/2605.09430">Paper</a>] [<a href="https://lxazjk.github.io/FlashAR/">Project</a>] [<a href="https://github.com/lxazjk/LlamaGen-FlashAR">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">arXiv</div>
  <div class="publication-list__body">
    <strong>Dynamic Execution Commitment of Vision-Language-Action Models  </strong><br>
    <strong>Feng Chen</strong>, Xianghui Wang, Yuxuan Chen, Boying Li, Yefei He, Zeyu Zhang, Yicheng Wu &nbsp;<br>
    <em>arXiv preprint, 2026</em><br>
    [<a href="https://arxiv.org/pdf/2605.11567">Paper</a>] [<a href="https://inceptionwang.github.io/A3/">Project</a>] [<a href="https://github.com/INCEPTIONwang/A3">Code</a>]
  </div>
</div>

Selected Publications
------

**Efficient MLLM/VLA**

<div class="publication-list__item">
  <div class="publication-list__venue">CVPR</div>
  <div class="publication-list__body">
    <strong>Beyond Accuracy: An Empirical Study of Perception Stability in Multimodal Large Language Models</strong><br>
    <strong>Feng Chen</strong>, Chenhui Gou, Yefei He, Yang Yang, Bohan Zhuang, Qi Wu<br>
    <em>CVPR Findings, 2026</em><br>
    [<a href="https://openaccess.thecvf.com/content/CVPR2026F/papers/Chen_Beyond_Accuracy_An_Empirical_Study_of_Perception_Stability_in_Multimodal_CVPRF_2026_paper.pdf">Paper</a>] [<a href="https://github.com/Chenfeng1271/AbilityLens">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">ICLR</div>
  <div class="publication-list__body">
    <strong>Sparsity Forcing: Reinforcing Token Sparsity of MLLMs</strong><br>
    <strong>Feng Chen</strong>, Yefei He, Lequan Lin, Chenhui Gou, Jing Liu, Bohan Zhuang, Qi Wu<br>
    <em>ICLR, 2026</em><br>
    [<a href="https://arxiv.org/abs/2504.18579">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">AAAI</div>
  <div class="publication-list__body">
    <strong>OmniSparse: Training-Aware Fine-Grained Sparse Attention for Long-Video MLLMs</strong><br>
    <strong>Feng Chen</strong>, Yefei He, Shaoxuan He, Yuanyu He, Jing Liu, Lequan Lin, Akide Liu, Zhaoyang Li, Jiyuan Zhang, Zhenbang Sun, Bohan Zhuang, Qi Wu<br>
    <em>AAAI, 2026</em><br>
    [<a href="https://arxiv.org/abs/2511.12201">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">ICCV</div>
  <div class="publication-list__body">
    <strong>ZipVL: Efficient Large Vision-Language Models with Dynamic Token Sparsification</strong><br>
    Yefei He, <strong>Feng Chen</strong>, Jing Liu, Wenqi Shao, Hong Zhou, Kaipeng Zhang, Bohan Zhuang<br>
    <em>ICCV, 2025</em><br>
    [<a href="https://arxiv.org/abs/2410.08584">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">ACL</div>
  <div class="publication-list__body">
    <strong>Less is More: Improving LLM Reasoning with Minimal Test-Time Intervention</strong><br>
    Zhen Yang, Mingyang Zhang, <strong>Feng Chen</strong>, Ganggui Ding, Liang Hou, Xin Tao, Ying-Cong Chen<br>
    <em>ACL, 2026</em><br>
    [<a href="https://arxiv.org/abs/2510.13940">Paper</a>] [<a href="https://github.com/EnVision-Research/MTI">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">NeurIPS</div>
  <div class="publication-list__body">
    <strong>ACT as Human: Multimodal Large Language Model Data Annotation with Critical Thinking</strong><br>
    Lequan Lin, Dai Shi, Andi Han, <strong>Feng Chen</strong>, Qiuzheng Chen, Jiawen Li, Zhaoyang Li, Jiyuan Li, Zhenbang Sun, Junbin Gao<br>
    <em>NeurIPS, 2025</em><br>
    [<a href="https://arxiv.org/abs/2511.09833">Paper</a>]
  </div>
</div>

**Efficient and Controllable World Model**

<div class="publication-list__item">
  <div class="publication-list__venue">ECCV</div>
  <div class="publication-list__body">
    <strong>LiveWorld: Simulating Out-of-Sight Dynamics in Generative Video World Models</strong><br>
    Zicheng Duan, Jiatong Xia, Zeyu Zhang, Wenbo Zhang, Gengze Zhou, Chenhui Gou, Yefei He, <strong>Feng Chen</strong> (Project Lead), Xinyu Zhang, Lingqiao Liu<br>
    <em>ECCV, 2026</em><br>
    [<a href="https://arxiv.org/abs/2603.07145">Paper</a>] [<a href="https://zichengduan.github.io/pages/LiveWorld/index.html">Project</a>] [<a href="https://github.com/ZichengDuan/LiveWorld">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">CVPR</div>
  <div class="publication-list__body">
    <strong>Chain of Event-Centric Causal Thought for Physically Plausible Video Generation</strong><br>
    Zixuan Wang<sup>*</sup>, Yixin Hu<sup>*</sup>, Haolan Wang, <strong>Feng Chen</strong><sup>*</sup>, Yan Liu, Wen Li, Yinjie Lei &nbsp;<br>
    <em>CVPR, 2026</em><br>
    [<a href="https://arxiv.org/abs/2603.09094">Paper</a>] [<a href="https://github.com/ZixuanWang0525/CoECT">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">ICCV</div>
  <div class="publication-list__body">
    <strong>Neighboring Autoregressive Modeling for Efficient Visual Generation</strong><br>
    Yefei He<sup>*</sup>, Yuanyu He<sup>*</sup>, Shaoxuan He<sup>*</sup>, <strong>Feng Chen</strong><sup>*</sup>, Hong Zhou, Kaipeng Zhang, Bohan Zhuang &nbsp;<br>
    <em>ICCV, 2025</em><br>
    [<a href="https://arxiv.org/abs/2503.10696">Paper</a>] [<a href="https://github.com/ThisisBillhe/NAR/tree/main">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">ICML</div>
  <div class="publication-list__body">
    <strong>ZipAR: Accelerating Auto-Regressive Image Generation through Spatial Locality</strong><br>
    Yefei He, <strong>Feng Chen</strong>, Yuanyu He, Shaoxuan He, Hong Zhou, Kaipeng Zhang, Bohan Zhuang<br>
    <em>ICML, 2025</em><br>
    [<a href="https://arxiv.org/abs/2412.04062">Paper</a>] [<a href="https://github.com/thisisbillhe/zipar">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">CVPR</div>
  <div class="publication-list__body">
    <strong>Training-free Dense-Aligned Diffusion Guidance for Modular Conditional Image Synthesis</strong><br>
    Zixuan Wang, Duo Peng, <strong>Feng Chen</strong>, Yuwei Yang, Yinjie Lei<br>
    <em>CVPR, 2025</em><br>
    [<a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_Training-free_Dense-Aligned_Diffusion_Guidance_for_Modular_Conditional_Image_Synthesis_CVPR_2025_paper.pdf">Paper</a>] [<a href="https://github.com/ZixuanWang0525/DADG">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">CVPR</div>
  <div class="publication-list__body">
    <strong>Training-free Motion Factorization for Compositional Video Generation</strong><br>
    Zixuan Wang, Ziqin Zhou, <strong>Feng Chen</strong>, Duo Peng, Yixin Hu, Changsheng Li, Yinjie Lei<br>
    <em>CVPR, 2026</em><br>
    [<a href="https://arxiv.org/abs/2603.09104">Paper</a>]
  </div>
</div>

**Others**

<div class="publication-list__item">
  <div class="publication-list__venue">Information Fusion</div>
  <div class="publication-list__body">
    <strong>Balanced Cross-modal Prompt Learning and Fusion Network for Multi-modal Fake News Detection</strong><br>
    Fei Wu, Hao Jin, <strong>Feng Chen</strong>, Yimu Ji, Xiao-Yuan Jing, Guo-Ping Jiang<br>
    <em>Information Fusion, 2025</em><br>
    [<a href="https://doi.org/10.1016/j.inffus.2025.103196">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">Pattern Recognition</div>
  <div class="publication-list__body">
    <strong>Learning Multi-granularity Representation with Transformer for Visible-Infrared Person Re-identification</strong><br>
    Yujian Feng<sup>*</sup>, <strong>Feng Chen</strong><sup>*</sup>, Guozi Sun, Fei Wu, Yimu Ji, Tianliang Liu, Shangdong Liu, Xiao-Yuan Jing, Jiebo Luo<br>
    <em>Pattern Recognition, 2025</em><br>
    [<a href="https://doi.org/10.1016/j.patcog.2025.111510">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">Pattern Recognition</div>
  <div class="publication-list__body">
    <strong>Homogeneous and Heterogeneous Relational Graph for Visible-Infrared Person Re-Identification</strong><br>
    Yujian Feng<sup>*</sup>, <strong>Feng Chen</strong><sup>*</sup>, Jian Yu, Yimu Ji, Fei Wu, Shangdong Liu, Xiao-Yuan Jing<br>
    <em>Pattern Recognition, 2025</em><br>
    [<a href="https://doi.org/10.1016/j.patcog.2024.110981">Paper</a>] [<a href="https://github.com/fegnyujian/Homogeneous-and-Heterogeneous-Relational-Graph">Code</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">IEEE TMM</div>
  <div class="publication-list__body">
    <strong>Cross-Modality Spatial-Temporal Transformer for Video-Based Visible-Infrared Person Re-Identification</strong><br>
    Yujian Feng<sup>*</sup>, <strong>Feng Chen</strong><sup>*</sup>, Jian Yu, Yimu Ji, Fei Wu, Tianliang Liu, Shangdong Liu, Xiao-Yuan Jing, Jiebo Luo<br>
    <em>IEEE Transactions on Multimedia, 2024</em><br>
    [<a href="https://doi.org/10.1109/TMM.2024.3354575">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">IEEE TMM</div>
  <div class="publication-list__body">
    <strong>Visible-Infrared Person Re-Identification via Cross-Modality Interaction Transformer</strong><br>
    Yujian Feng, Jian Yu, <strong>Feng Chen</strong>, Yimu Ji, Fei Wu, Shangdong Liu, Xiao-Yuan Jing<br>
    <em>IEEE Transactions on Multimedia, 2023</em><br>
    [<a href="https://doi.org/10.1109/TMM.2022.3224663">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">SDM</div>
  <div class="publication-list__body">
    <strong>Coarse-to-Fine Open Information Extraction via Relation Oriented Reading Comprehension</strong><br>
    Tingxin Li, Rui Meng, <strong>Feng Chen</strong>, Jianming Wu<br>
    <em>SDM, 2023</em><br>
    [<a href="https://doi.org/10.1137/1.9781611977653.ch103">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">ICCV</div>
  <div class="publication-list__body">
    <strong>Uncertainty-guided Learning for Improving Image Manipulation Detection</strong><br>
    Kaixiang Ji, <strong>Feng Chen</strong>, Xin Guo, Yadong Xu, Jian Wang, Jingdong Chen<br>
    <em>ICCV, 2023</em><br>
    [<a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Ji_Uncertainty-guided_Learning_for_Improving_Image_Manipulation_Detection_ICCV_2023_paper.pdf">Paper</a>]
  </div>
</div>



<div class="publication-list__item">
  <div class="publication-list__venue">ACM MM</div>
  <div class="publication-list__body">
    <strong>Learning Implicit Entity-object Relations by Bidirectional Generative Alignment for Multimodal NER</strong><br>
    <strong>Feng Chen</strong>, Jiajia Liu, Kaixiang Ji, Wang Ren, Jian Wang, Jingdong Wang<br>
    <em>ACM MM, 2023</em><br>
    [<a href="https://arxiv.org/abs/2308.02570">Paper</a>]
  </div>
</div>

<div class="publication-list__item">
  <div class="publication-list__venue">Pattern Recognition</div>
  <div class="publication-list__body">
    <strong>JSPNet: Learning Joint Semantic & Instance Segmentation of Point Clouds via Feature Self-Similarity and Cross-Task Probability</strong><br>
    <strong>Feng Chen</strong>, Fei Wu, Guangwei Gao, Yimu Ji, Jing Xu, Guo-Ping Jiang, Xiao-Yuan Jing<br>
    <em>Pattern Recognition, 2022</em><br>
    [<a href="https://doi.org/10.1016/j.patcog.2021.108250">Paper</a>] [<a href="https://github.com/Chenfeng1271/JSPNet">Code</a>]
  </div>
</div>

Professional Activities
------
- **Reviewer**: CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, IJCV


Awards
------

- **Jiangsu Province Outstanding Graduate**, 2021
- **Jiangsu Province Outstanding Master Thesis Award**, 2021
