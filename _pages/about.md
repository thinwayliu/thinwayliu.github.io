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
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | app# 🎖 Honors and Awards
<div class="honor-item">
  <strong>🏅 National Scholarship (Doctoral Level)</strong> - Ministry of Education of China, 2024
</div>
<div class="honor-item">
  <strong>🏅 National Scholarship (Undergraduate Level)</strong> - Ministry of Education of China, 2019  
</div>
<div class="honor-item">
  <strong>🥉 Third Prize (Ranked 1st)</strong> - 2025 Qiyuan Large Model Adversarial Challenge
</div>

# 🚩 Academic Service
<div class="service-item">
  <strong>📋 Conference Reviewer:</strong> CVPR, NeurIPS, ICLR, ICCV, ECCV, ACM MM, AAAI
</div>
<div class="service-item">
  <strong>📖 Journal Reviewer:</strong> IEEE T-PAMI, IEEE TIFS, IEEE TIP, IEEE TDSC, Pattern Recognition
</div>e.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# � About Me

I'm **Xinwei Liu**, a Ph.D. candidate at the [Institute of Information Engineering, Chinese Academy of Sciences](http://www.iie.ac.cn/) (IIE, CAS), where I focus on advancing the frontiers of AI security and privacy protection. I am fortunate to be supervised by [**Prof. Xiaochun Cao**](https://scst.sysu.edu.cn/members/caoxiaochun.htm) (Dean of the School of Cyber Science and Technology at Sun Yat-sen University) and [**Prof. Hua Zhang**](https://visionhzhang.github.io/zh-cn/).

I received my Bachelor's degree from the School of Mathematics and Computer Science, Nanchang University in 2020, advised by [**Prof. Yuchao Tang**](https://maths.gzhu.edu.cn/info/1263/5252.htm). During my research journey, I also gained valuable industry experience as a research intern at Ant Group (2022-2023).

**Research Focus**: My work centers on developing **trustworthy AI systems** through multimodal data protection and proactive defense mechanisms. I specialize in:

<div class="research-focus">
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1em; margin-top: 1em;">
    <div>
      🛡️ <strong>AI Security</strong><br>
      <em>Adversarial attacks, backdoor defenses, and poisoning strategies</em>
    </div>
    <div>
      🔒 <strong>Privacy Protection</strong><br>
      <em>Machine unlearning and data privacy for multimodal systems</em>
    </div>
    <div>
      🚨 <strong>Large Model Safety</strong><br>
      <em>Jailbreak attacks and defenses for LLM/VLM models</em>
    </div>
    <div>
  </div>
</div>

🚀 **I will complete my Ph.D. in June 2026 and am actively seeking postdoctoral opportunities worldwide. Please feel free to reach out!**



# 🔥 News
<div class="news-item">
  <strong>🎉 2025.10:</strong> One paper on Security of VLM is accepted in <strong>T-IFS 2025</strong>!
</div>
<div class="news-item">
  <strong>🎉 2024.09:</strong> One paper on Privacy of Multi-modal Data accepted by <strong>ACM MM 2024</strong>!
</div>
<div class="news-item">
  <strong>🎉 2024.02:</strong> One paper on Backdoor Attack is accepted by <strong>T-IFS</strong>!
</div> 


# 📝 Publications 
<!-- 
<div style="background: linear-gradient(45deg, #f8f9ff, #e8f0fe); padding: 1.5em; border-radius: 10px; margin-bottom: 2em; text-align: center;">
  <h3 style="margin-top: 0; color: #4285f4;">🎯 Research Impact</h3>
  <p>I have published <strong>9+ papers</strong> in top-tier venues including <strong>TIFS, ECCV, AAAI, ACM MM</strong>, focusing on AI security and privacy protection.</p>
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1em; margin: 1em 0; text-align: center;">
    <div style="background: white; padding: 1em; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
      <strong>🎯 Main Focus</strong><br>
      <span style="color: #4285f4;">AI Security & Privacy</span>
    </div>
    <div style="background: white; padding: 1em; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
      <strong>📊 Impact Areas</strong><br>
      <span style="color: #4285f4;">Multimodal Learning</span>
    </div>
    <div style="background: white; padding: 1em; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
      <strong>🔬 Methods</strong><br>
      <span style="color: #4285f4;">Adversarial & Defense</span>
    </div>
  </div>
  <p><em>Click on any paper below to learn more about the research!</em></p>
</div> -->

## 🏆 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2025</div><img src='images/paper/cleaner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CleanerCLIP: Fine-grained Counterfactual Semantic Augmentation for Backdoor Defense in Contrastive Learning](https://arxiv.org/pdf/2409.17601?)

Yuan Xun, Siyuan Liang, Xiaojun Jia, **Xinwei Liu**, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2409.17601?)  <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> IEEE Transactions on Information Forensics and Security (TIFS)




</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/paper/unlearnable.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multimodal unlearnable examples: Protecting data against multimodal contrastive learning](https://arxiv.org/pdf/2407.16307)

 **Xinwei Liu**, Xiaojun Jia, Yuan Xun, Siyuan Liang, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2407.16307) 
[**Code**](https://github.com/thinwayliu/Multimodal-Unlearnable-Examples) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Proceedings of the 32nd ACM International Conference on Multimedia 2024 (ACM MM, 2024)
<!-- - This is a landmark paper in deep learning that introduced residual connections to enable training of very deep neural networks. -->
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/paper/few-shot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Does few-shot learning suffer from backdoor attacks?](https://ojs.aaai.org/index.php/AAAI/article/view/29965/31689)

 **Xinwei Liu**, Xiaojun Jia, Jindong Gu, Yuan Xun, Siyuan Liang, Xiaochun Cao

[**PDF**](https://ojs.aaai.org/index.php/AAAI/article/view/29965/31689) 
[**Code**](https://github.com/thinwayliu/FLBA-Backdoor) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Thirty-Eighth AAAI Conference on Artificial Intelligence (AAAI 2024)
<!-- - This is a landmark paper in deep learning that introduced residual connections to enable training of very deep neural networks. -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/paper/watermark.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Watermark vaccine: Adversarial attacks to prevent watermark removal](https://arxiv.org/pdf/2207.08178)

 **Xinwei Liu**, Jian Liu, Yang Bai, Jindong Gu, Tao Chen, Xiaojun Jia, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2207.08178) 
[**Code**](https://github.com/thinwayliu/Watermark-Vaccine) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
European Conference on Computer Vision 2022 (ECCV 2022) 
<!-- - This is a landmark paper in deep learning that introduced residual connections to enable training of very deep neural networks. -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2024</div><img src='images/paper/minimalism.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Minimalism is king! high-frequency energy-based screening for data-efficient backdoor attacks](https://ieeexplore.ieee.org/abstract/document/10478135/)

Yuan Xun, Xiaojun Jia, Jindong Gu, **Xinwei Liu**, Qing Guo, Xiaochun Cao 

[**PDF**](https://ieeexplore.ieee.org/abstract/document/10478135/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
IEEE Transactions on Information Forensics and Security (TIFS 2024)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2024</div><img src='images/paper/transfer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey on Transferability of Adversarial Examples Across Deep Neural Networks](https://arxiv.org/pdf/2310.17626)

Jindong Gu, Xiaojun Jia, Pau de Jorge, Wenqain Yu, **Xinwei Liu**, Avery Ma, Yuan Xun, Anjun Hu, Ashkan Khakzar, Zhijiang Li, Xiaochun Cao, Philip Torr

[**PDF**](https://arxiv.org/pdf/2310.17626) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Transactions on Machine Learning Research 2024 (TMLR 2024) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR Workshop</div><img src='images/paper/universal-watermark.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Universal watermark vaccine: Universal adversarial perturbations for watermark protection](https://openaccess.thecvf.com/content/CVPR2023W/AML/papers/Chen_Universal_Watermark_Vaccine_Universal_Adversarial_Perturbations_for_Watermark_Protection_CVPRW_2023_paper.pdf)

Jianbo Chen, **Xinwei Liu**, Siyuan Liang, Xiaojun Jia, Yuan Xun

[**PDF**](https://openaccess.thecvf.com/content/CVPR2023W/AML/papers/Chen_Universal_Watermark_Vaccine_Universal_Adversarial_Perturbations_for_Watermark_Protection_CVPRW_2023_paper.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshop (CVPR Workshop 2023)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JEI</div><img src='images/paper/jei.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Primal-dual algorithm to solve the constrained second-order total generalized variational model for image denoising](https://www.spiedigitallibrary.org/journals/Journal-of-Electronic-Imaging/volume-28/issue-4/043017/Primal-dual-algorithm-to-solve-the-constrained-second-order-total/10.1117/1.JEI.28.4.043017.short)

 **Xinwei Liu**, Yuchao Tang, Yixuan Yang

[**PDF**](https://www.spiedigitallibrary.org/journals/Journal-of-Electronic-Imaging/volume-28/issue-4/043017/Primal-dual-algorithm-to-solve-the-constrained-second-order-total/10.1117/1.JEI.28.4.043017.short) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Journal of Electronic Imaging
</div>
</div>

<!-- Add your publications here with proper titles and descriptions
<!-- 

 Preprints (see full list on Google Scholar) -->

# 📖 Preprints (see full list on [Google Scholar]("https://scholar.google.com/citations?user=dVn3LgwAAAAJ&hl=en"))


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/paper/geoshield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GeoShield: Safeguarding Geolocation Privacy from Vision-Language Models via Adversarial Perturbations](https://arxiv.org/abs/2508.03209)

 **Xinwei Liu**, Xiaojun Jia, Yuan Xun, Simeng Qin, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2508.03209) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Arxiv 2025
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/paper/persguard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PersGuard: Preventing Malicious Personalization via Backdoor Attacks on Pre-trained Text-to-Image Diffusion Models](https://arxiv.org/pdf/2502.16167)

 **Xinwei Liu**, Xiaojun Jia, Yuan Xun, Hua Zhang, Xiaochun Cao

[**PDF**](https://arxiv.org/pdf/2508.03209) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Arxiv 2025
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/paper/babyemo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Emotional Baby Is Truly Deadly: Does your Multimodal Large Reasoning Model Have Emotional Flattery towards Humans?](https://arxiv.org/abs/2508.03986)

 Yuan Xun, Xiaojun Jia, **Xinwei Liu**, Hua Zhang

[**PDF**](https://arxiv.org/pdf/2508.03986) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Arxiv 2025

</div>
</div>


# 🎖 Honors and Awards
- National Scholarship (Undergraduate Level), Ministry of Education of China 2024 
- National Scholarship (Doctoral Level), Ministry of Education of China 2019
- Third Prize (Ranked 1st) in the 2025 Qiyuan Large Model Adversarial Challenge  

# 🚩 Service
- **Conference Reviewer**: CVPR, NeurIPS, ICLR, ICCV, ECCV, ACM MM, AAAI 
- **Journal Reviewer**: IEEE T-PAMI, IEEE TIFS, IEEE TIP, IEEE TDSC, Pattern Recognition

<!-- # 💬 Invited Talks
Add your invited talks here -->

# 💻 Internships
- 2022.03 - 2023.06, Research Intern, Ant Group, China.

# 🌍 Visitor Map

<div class="visitor-map">
  <h3>🗺️ Visitors from Around the World</h3>
  <p>Thank you for visiting my homepage! Here's where my visitors are from:</p>
  
  <!-- To get your clustrmaps code:
       1. Visit https://clustrmaps.com/
       2. Click "Get Free Map"
       3. Enter your website URL: https://thinwayliu.github.io
       4. Choose your map style
       5. Copy the generated script code and replace the line below
  -->
  <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=YOUR_MAP_ID&cl=ffffff&w=a"></script>
  
  <p style="margin-top: 1em; font-size: 0.9em; color: #666;">
    📍 <em>This map shows the geographical distribution of visitors to my website.</em>
  </p>
</div>

---

<div style="text-align: center; margin-top: 2em; padding: 1em; background: linear-gradient(45deg, #f8f9ff, #e8f0fe); border-radius: 10px;">
  <p><strong>🤝 Let's Connect!</strong></p>
  <p>I'm always open to collaborations, discussions, and new opportunities.</p>
  <p>Feel free to reach out if you're interested in AI security, privacy protection, or academic collaboration.</p>
</div>