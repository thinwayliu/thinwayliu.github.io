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

# 👤 About Me

I'm **Xinwei Liu**, a Ph.D. candidate at the [Institute of Information Engineering, Chinese Academy of Sciences](http://www.iie.ac.cn/) (IIE, CAS), where I focus on advancing the frontiers of AI security and privacy protection. I am fortunate to be supervised by [**Prof. Xiaochun Cao**](https://scst.sysu.edu.cn/members/caoxiaochun.htm) (Dean of the School of Cyber Science and Technology at Sun Yat-sen University) and [**Prof. Hua Zhang**](https://visionhzhang.github.io/zh-cn/).

I received my Bachelor's degree from the School of Mathematics and Computer Science, Nanchang University in 2020, advised by [**Prof. Yuchao Tang**](https://maths.gzhu.edu.cn/info/1263/5252.htm). During my research journey, I also gained valuable industry experience as a research intern at Ant Group (2022-2023).

**Research Focus**: My work centers on developing **trustworthy AI systems** through multimodal data protection and proactive defense mechanisms. I specialize in:

- 🛡️ **AI Security**: Adversarial attacks, backdoor defenses, and poisoning strategies
- 🔒 **Privacy Protection**: Machine unlearning and data privacy for multimodal systems  
- 🚨 **Large Model Safety**: Jailbreak attacks and defenses for LLM/VLM models

> 🚀 **I will complete my Ph.D. in June 2026 and am actively seeking postdoctoral opportunities worldwide. Please feel free to reach out!**

---

# 🔥 News

- **🎉 Oct 2025:** One paper on Security of VLM is accepted in **T-IFS 2025**!
- **🎉 Sep 2024:** One paper on Privacy of Multi-modal Data accepted by **ACM MM 2024**!
- **🎉 Feb 2024:** One paper on Backdoor Attack is accepted by **T-IFS 2024**!

---

# 📝 Publications

## 🏆 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2025</div><img src='images/paper/cleaner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CleanerCLIP: Fine-grained Counterfactual Semantic Augmentation for Backdoor Defense in Contrastive Learning](https://arxiv.org/pdf/2409.17601?)

Yuan Xun, Siyuan Liang, Xiaojun Jia, **Xinwei Liu**, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2409.17601?) IEEE Transactions on Information Forensics and Security (TIFS)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/paper/unlearnable.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multimodal unlearnable examples: Protecting data against multimodal contrastive learning](https://arxiv.org/pdf/2407.16307)

**Xinwei Liu**, Xiaojun Jia, Yuan Xun, Siyuan Liang, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2407.16307) [**Code**](https://github.com/thinwayliu/Multimodal-Unlearnable-Examples)
Proceedings of the 32nd ACM International Conference on Multimedia 2024 (ACM MM, 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/paper/few-shot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Does few-shot learning suffer from backdoor attacks?](https://ojs.aaai.org/index.php/AAAI/article/view/29965/31689)

**Xinwei Liu**, Xiaojun Jia, Jindong Gu, Yuan Xun, Siyuan Liang, Xiaochun Cao

[**PDF**](https://ojs.aaai.org/index.php/AAAI/article/view/29965/31689) [**Code**](https://github.com/thinwayliu/FLBA-Backdoor)
Thirty-Eighth AAAI Conference on Artificial Intelligence (AAAI 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/paper/watermark.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Watermark vaccine: Adversarial attacks to prevent watermark removal](https://arxiv.org/pdf/2207.08178)

**Xinwei Liu**, Jian Liu, Yang Bai, Jindong Gu, Tao Chen, Xiaojun Jia, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2207.08178) [**Code**](https://github.com/thinwayliu/Watermark-Vaccine)
European Conference on Computer Vision 2022 (ECCV 2022) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2024</div><img src='images/paper/minimalism.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Minimalism is king! high-frequency energy-based screening for data-efficient backdoor attacks](https://ieeexplore.ieee.org/abstract/document/10478135/)

Yuan Xun, Xiaojun Jia, Jindong Gu, **Xinwei Liu**, Qing Guo, Xiaochun Cao 

[**PDF**](https://ieeexplore.ieee.org/abstract/document/10478135/)
IEEE Transactions on Information Forensics and Security (TIFS 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2024</div><img src='images/paper/transfer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey on Transferability of Adversarial Examples Across Deep Neural Networks](https://arxiv.org/pdf/2310.17626)

Jindong Gu, Xiaojun Jia, Pau de Jorge, Wenqain Yu, **Xinwei Liu**, Avery Ma, Yuan Xun, Anjun Hu, Ashkan Khakzar, Zhijiang Li, Xiaochun Cao, Philip Torr

[**PDF**](https://arxiv.org/pdf/2310.17626)
Transactions on Machine Learning Research 2024 (TMLR 2024) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR Workshop</div><img src='images/paper/universal-watermark.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Universal watermark vaccine: Universal adversarial perturbations for watermark protection](https://openaccess.thecvf.com/content/CVPR2023W/AML/papers/Chen_Universal_Watermark_Vaccine_Universal_Adversarial_Perturbations_for_Watermark_Protection_CVPRW_2023_paper.pdf)

Jianbo Chen, **Xinwei Liu**, Siyuan Liang, Xiaojun Jia, Yuan Xun

[**PDF**](https://openaccess.thecvf.com/content/CVPR2023W/AML/papers/Chen_Universal_Watermark_Vaccine_Universal_Adversarial_Perturbations_for_Watermark_Protection_CVPRW_2023_paper.pdf)
Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshop (CVPR Workshop 2023)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JEI</div><img src='images/paper/jei.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Primal-dual algorithm to solve the constrained second-order total generalized variational model for image denoising](https://www.spiedigitallibrary.org/journals/Journal-of-Electronic-Imaging/volume-28/issue-4/043017/Primal-dual-algorithm-to-solve-the-constrained-second-order-total/10.1117/1.JEI.28.4.043017.short)

**Xinwei Liu**, Yuchao Tang, Yixuan Yang

[**PDF**](https://www.spiedigitallibrary.org/journals/Journal-of-Electronic-Imaging/volume-28/issue-4/043017/Primal-dual-algorithm-to-solve-the-constrained-second-order-total/10.1117/1.JEI.28.4.043017.short)
Journal of Electronic Imaging

</div>
</div>

## 📖 Preprints 

See full list on [Google Scholar](https://scholar.google.com/citations?user=dVn3LgwAAAAJ&hl=en)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper/geoshield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GeoShield: Safeguarding Geolocation Privacy from Vision-Language Models via Adversarial Perturbations](https://arxiv.org/abs/2508.03209)

**Xinwei Liu**, Xiaojun Jia, Yuan Xun, Simeng Qin, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2508.03209) arXiv 2024

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper/persguard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PersGuard: Preventing Malicious Personalization via Backdoor Attacks on Pre-trained Text-to-Image Diffusion Models](https://arxiv.org/pdf/2502.16167)

**Xinwei Liu**, Xiaojun Jia, Yuan Xun, Hua Zhang, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2502.16167) arXiv 2025

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper/babyemo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Emotional Baby Is Truly Deadly: Does your Multimodal Large Reasoning Model Have Emotional Flattery towards Humans?](https://arxiv.org/abs/2508.03986)

Yuan Xun, Xiaojun Jia, **Xinwei Liu**, Hua Zhang

[**PDF**](https://arxiv.org/pdf/2508.03986) arXiv 2024

</div>
</div>

# 🎖 Honors and Awards

- **National Scholarship (Doctoral Level)**, Ministry of Education of China, 2024 
- **National Scholarship (Undergraduate Level)**, Ministry of Education of China, 2019
- **Third Prize (Ranked 1st)** in the 2025 Qiyuan Large Model Adversarial Challenge  

# 🚩 Service

- **Conference Reviewer**: CVPR, NeurIPS, ICLR, ICCV, ECCV, ACM MM, AAAI 
- **Journal Reviewer**: IEEE T-PAMI, IEEE TIFS, IEEE TIP, IEEE TDSC, Pattern Recognition

# 💻 Internships

- **2022.03 - 2023.06**, Research Intern, Ant Group, China




<!-- Visitor Map with controlled size -->
<div style="text-align: center; margin: 2em 0;">
  <h3>🌍 Visitor Map</h3>
  <div style="display: inline-block; max-width: 500px; overflow: hidden;">
    <script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=02YgsFpbUruEfoxHNXywiwvBEYLKAjEJgbU97tyvVfQ&cl=ffffff&w=400"></script>
  </div>
  <p style="margin-top: 1em; font-size: 0.9em; color: #666;">
    📍 <em>Thank you for visiting my homepage!</em>
  </p>
</div>

---

<div style="text-align: center; margin-top: 2em; padding: 1em; background: #f8f9fa; border-radius: 8px;">
  <p><strong>🤝 Let's Connect!</strong></p>
  <p>I'm always open to collaborations, discussions, and new opportunities in AI security and privacy protection.</p>
</div>