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

I am currently pursuing a combined B.S./M.S./Ph.D. program in Computer Science at [Northeastern University](https://neu.edu.cn/), presently in the master's stage. My research focuses on reasoning and retrieval for large language models in legal scenarios, with broader interests spanning NLP, Information Retrieval, and LLM applications. 
I am studying at NEUIR Lab under the guidance of Associate Professor [Zhenghao Liu](https://edwardzh.github.io/), as well as at [Tsinghua University](https://www.tsinghua.edu.cn/), supervised by [Chaojun Xiao](https://xcjthu.github.io/).


# 🔥 News
- *2025.10*: Our paper has been awarded the Best Paper Award at the 2025 International Conference on Advanced Data Mining and Applications (ADMA 2025)! 🏆 


# 📝 Publications

> \* indicates **equal contribution**, and † indicates **corresponding author**.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL2026</div><img src='images/merged-image.png' alt="paper teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### Revealing the Attention Floating Mechanism in Masked Diffusion Models

**Xin Dai**, Pengcheng Huang, Zhenghao Liu†, Shuo Wang, Yukun Yan, Chaojun Xiao, Yu Gu, Ge Yu, Maosong Sun

[**📃Paper**](https://arxiv.org/abs/2601.07894) | [**💻Code**](https://github.com/NEUIR/Attention-Floating) | <span class="paper-tag paper-tag-ccf-a">CCF-A</span>

- This work uncovers the attention floating mechanism in masked diffusion models, showing how attention anchors move dynamically across denoising steps and layers. The analysis provides a mechanistic explanation for their strong in-context learning behavior and strong performance on knowledge-intensive tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL2026</div><img src='images/SAFEQAQ.png' alt="paper teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### SAFE-QAQ: End-to-End Slow-Thinking Audio-Text Fraud Detection via Reinforcement Learning

Peidong Wang\*, Zhiming Ma\*, **Xin Dai**\*, Yongkang Liu, Shi Feng, Xiaocui Yang, Wenxing Hu, Zhihao Wang, Mingjun Pan, Li Yuan, Daling Wang

[**📃Paper**](https://arxiv.org/abs/2601.01392) | [**💻Code**](https://github.com/Control-derek/SAFE-QAQ) | <span class="paper-tag paper-tag-ccf-a">CCF-A</span>

- This work presents an end-to-end audio-text fraud detection framework that directly models both speech signals and textual content with slow-thinking reinforcement learning. It captures fine-grained acoustic cues missed by text-only methods and supports more robust and real-time fraud detection.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP2026</div><img src='images/LegalDelta.png' alt="paper teaser" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

### LegalΔ: Enhancing Legal Reasoning in LLMs via Reinforcement Learning with Chain-of-Thought Guided Information Gain

**Xin Dai\***, Buqiang Xu\*, Zhenghao Liu†, Yukun Yan, Huiyuan Xie, Xiaoyuan Yi, Shuo Wang, Ge Yu

[**📃Paper**](https://arxiv.org/abs/2508.12281) | [**💻Code**](https://github.com/NEUIR/LegalDelta) | <span class="paper-tag paper-tag-ccf-b">CCF-B</span>

- This work introduces a reinforcement learning framework for legal LLMs that explicitly encourages high-quality chain-of-thought reasoning through information gain. It improves both prediction accuracy and interpretability, making legal judgments more reliable and better grounded in multi-step reasoning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ADMA2025</div><img src='images/LegalDuet.png' alt="paper teaser" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

### LegalDuet: Learning Fine-Grained Representations for Legal Judgment Prediction via a Dual-View Contrastive Learning

Buqiang Xu\*, **Xin Dai\***, Zhenghao Liu†, Huiyuan Xie, Xiaoyuan Yi, Shuo Wang, Yukun Yan, Liner Yang, Yu Gu, Ge Yu

[**📃Paper**](https://link.springer.com/chapter/10.1007/978-981-95-3453-1_23) | [**💻Code**](https://github.com/NEUIR/LegalDuet) | <span class="paper-tag paper-tag-ccf-c">CCF-C</span>

- This work proposes a dual-view contrastive learning framework to learn fine-grained representations for legal cases and judgments. By jointly modeling case similarity and decision-level distinctions, it improves legal judgment prediction on challenging and easily confusable cases.

</div>
</div>

# 🎖 Honors and Awards
- *2025.11* President Scholarship, First-Class Excellent Student Scholarship.
- *2024.11* National Scholarship, First-Class Excellent Student Scholarship, and Outstanding Student Award.
- *2023.11* National Scholarship, First-Class Excellent Student Scholarship, Outstanding Student Role Model.
- *2022.11* Second-Class Excellent Student Scholarship and Outstanding Student Award.

# 📖 Educations
- *2025.09 - now*, M.S. School of Computer Science and Engineering, Northeastern University.
- *2021.09 - 2025.06*, B.S. School of Computer Science and Engineering, Northeastern University.


# 💻 Internships
- *2025.10 - now*, [ModelBest](https://www.modelbest.cn/), China.