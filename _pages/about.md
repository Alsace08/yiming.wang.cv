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


### **Hello, I'm Yiming Wang (王一鸣).**

I was born in Jiangsu Province, China, in August 2001. I'm now a second-year Ph.D. candidate at the Department of Computer Science and Engineering, Shanghai Jiao Tong University, supervised by <a href="https://wangruinlp.github.io/">Prof. Rui Wang</a>. Before that, I received a Bachelor's degree from the Institute of Artificial Intelligence, Beihang University.

# 🔬 Research

My research field is Natural Language Processing (NLP). Now I mainly focus on these areas oriented toward Large Language Models (LLMs) and Machine Learning (ML):

* Machine Reasoning **(Primary)**:
  - Pushing the Upper Limits of LLMs' Known Reasoning Ability
  - Exploring the Boundaries of LLM Reasoning Ability

* Discrete Generation:
  - Text Generation: Summarization
  - Molecular Generation: Retrosynthesis

* Others: Interpretable AI, Trustworthy AI



# 🔥 News

- *2024.09*: One paper about Mathematical Reasoning and Out-of-Distribution Detection is accepted by <a href="https://neurips.cc/Conferences/2024">NeurIPS 2024</a>.
- *2024.09*: Two paper about Summarization and LLM Safety are accepted by <a href="https://2024.emnlp.org/">EMNLP 2024</a>.
- *2024.05*: One paper about LLM Reasoning is accepted by <a href="https://2024.aclweb.org/">ACL 2024</a>.
- *2023.06*: I earn my B.S. in Artificial Intelligence with a 1/31 overall ranking.
- *2023.05*: One paper about LLM Summarization (SumCoT) is accepted by <a href="https://2023.aclweb.org/">ACL 2023</a>.
- *2022.08*: One paper about Low-resource Summarization is accepted by <a href="https://coling2022.org/">COLING 2022</a>.

    


# 📝 Selected Publications


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning, Trustworthy AI</div><img src='images/TVscore.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trajectory Volatility for Out-of-Distribution Detection in Mathematical Reasoning](https://arxiv.org/abs/2405.14039)

**Yiming Wang**, Pei Zhang, Baosong Yang, Derek F. Wong, Zhuosheng Zhang, Rui Wang

Annual Conference on Neural Information Processing Systems (**NeurIPS 2024**, CCF-A)

<!-- <a href='https://github.com/Alsace08/OOD-Math-Reasoning'><button type="button" class="btn btn-primary">CODE</button></a> -->
<!-- <a href='https://arxiv.org/abs/2405.14039'><button type="button" class="btn btn-danger">PDF</button></a> -->

<a href='https://github.com/Alsace08/OOD-Math-Reasoning'><button class="code-btn">CODE</button></a>

<!-- * We discover the ''pattern collapse'' phenomenon under mathematical reasoning -->
<!-- * We propose embedding trajectory volatility (TV Score) to detect OOD samples -->

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning</div><img src='images/Meta-Reasoning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Meta-Reasoning: Semantics-Symbol Deconstruction for Large Language Models](https://arxiv.org/abs/2306.17820)

**Yiming Wang**, Zhuosheng Zhang, Pei Zhang, Baosong Yang, Rui Wang

Annual Meeting of the Association for Computational Linguistics (**ACL 2024 Findings**, CCF-A)

<a href='https://github.com/Alsace08/Meta-Reasoning'><button class="code-btn">CODE</button></a>

<!-- * We establish the equivalence mapping from semantics to symbols under the purely natural language -->
<!-- * Meta-Reasoning substantially generalizes the reasoning capability of LLMs -->

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Summarization</div><img src='images/sumcot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Element-aware Summarization with Large Language Models: Expert-aligned Evaluation and Chain-of-Thought Method](https://aclanthology.org/2023.acl-long.482/)

**Yiming Wang**, Zhuosheng Zhang, Rui Wang

Annual Meeting of the Association for Computational Linguistics (**ACL 2023**, CCF-A)

<a href='https://github.com/Alsace08/SumCoT'><button class="code-btn">CODE</button></a>

<!-- * We construct expert-writing element-aware summary test sets to evaluate general summarization systems more objectively -->
<!-- * We revisit the zero-shot summarization ability of LLMs. -->
<!-- * We propose **SumCoT**, which allows the LLMs to generate more fine-grained summaries step by step. -->


</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Summarization</div><img src='images/cpsum.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Noise-injected Consistency Training and Entropy-constrained Pseudo Labeling for Semi-supervised Extractive Summarization](https://aclanthology.org/2022.coling-1.561/)

**Yiming Wang**, Qianren Mao, Junnan Liu, Weifeng Jiang, Hongdong Zhu, Jianxin Li

International Conference on Computational Linguistics (**COLING 2022**, CCF-B)

<a href='https://github.com/OpenSUM/CPSUM'><button class="code-btn">CODE</button></a>

<!-- * We introduce consistency regularization on the extractive summarization task for the first time -->
<!-- * We propose a pseudo-label selection method based on dynamic average entropy comparison and a ramp-up pseudo-label exploration strategy -->
  
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Fact Checking</div><img src='images/factchecking.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HiGIL: Hierarchical Graph Inference Learning for Fact Checking](https://ieeexplore.ieee.org/abstract/document/10027671)

Qianren Mao, **Yiming Wang**, Chenghong Yang, Linfeng Du, Hao Peng, Jia Wu, Jianxin Li, Zheng Wang

International Conference on Data Mining (**ICDM 2022**, CCF-B)

<a href='https://github.com/OpenSUM/CPSUM'><button class="code-btn">CODE</button></a>

<!-- * We propose a claim-evidence language graph model upon progressive tuple, fact, and sentence levels. -->
<!-- * We combine the semantic and topological information of the graph neural network -->
  
</div>
</div>



# 📝 Selected Preprint

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning</div><img src='images/CoT_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents](https://arxiv.org/abs/2311.11797)

Zhuosheng Zhang, Yao Yao, Aston Zhang, Xiangru Tang, Xinbei Ma, Zhiwei He, **Yiming Wang**, Mark Gerstein, Rui Wang, Gongshen Liu, Hai Zhao

<a href='https://github.com/Zoeyyao27/CoT-Igniting-Agent'><button class="code-btn">CODE</button></a>

<!-- * A comprehensive survey from Chain-of-Thought (CoT) technique to LLM agents -->

</div>
</div>


# 📖 Educations
- *2023.09 - Present*, <a href="https://www.cs.sjtu.edu.cn/">Department of Computer Science and Engineering, Shanghai Jiao Tong University (SJTU)</a>, Shanghai, China
- *2019.09 - 2023.06*, <a href="https://iai.buaa.edu.cn/">Institute of Artificial Intelligence, Beihang University (BUAA)</a>, Beijing, China


# 💻 Internships
- *2024.03 - Present*, Tongyi Laboratory, Alibaba, Hangzhou.
    - Research Intern: Multilingual LLMs; Mentor: Pei Zhang, <a href="https://baosongyang.site/">Dr. Baosong Yang</a>
- *2023.03 - 2023.09*, Institute of AI Industry Research (AIR), Tsinghua University, Beijing.
    - Research Intern: AI for Science; Mentor: <a href="https://zhouh.github.io/">Prof. Hao Zhou</a>
- *2021.11 - 2022.09*, ACT Lab, Department of Computer Science and Engineering, Beihang University, Beijing.
    - Research Intern: NLP & Graph Learning; Mentor: Qianren Mao, <a href="https://myjianxin.github.io/">Prof. Jianxin Li</a>


# 💬 Service

- Reviewer: ICLR (2025), ACL Rolling Review (2024)
- Teaching Assistant: Natural Language Processing and Large Language Model (for the John Class, CS3966, 2024)


    


# 🎖 Honors and Awards

* *2023.06:* Outstanding Graduate of Beijing (5%)
* *2023.01:* Outstanding Teaching Assistant for Algebra Courses
* *2021.12:* Ministry of Education-Huawei ``Future Star'' Joint Commendation Scholarship
* *2020.12:* The 1st prize in Beijing of the National College Student Mathematics Competition
* *2018.09:* The 1st prize in Jiangsu Province of the Mathematical Competition of Senior High School of China
