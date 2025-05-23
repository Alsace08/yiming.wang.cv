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

* Interpretable AI:
  - Behavioral Laws in the Latent Space (Chain-of-Embedding, ICLR 2025)
  - Controlled Meta-Behavioral Analysis like Physics

* Machine Reasoning:
  - Enhancing LLM Reasoning Ability and Efficiency (ST-BoN)
  - Evaluating the Boundaries of LLM Reasoning (PolyMath)




# 🔥 News

- *2025.04*: 🎉We construct <a href="https://huggingface.co/datasets/Alsace08/PolyMath">PolyMath</a>, a challenging multilingual mathematical reasoning benchmark, and used for standard evaluation by <a href="https://arxiv.org/abs/2505.09388">Qwen3</a>
- *2025.01*: Two papers about Interpretable AI and Mathematical Reasoning are accepted by <a href="https://iclr.cc/Conferences/2025">ICLR 2025</a>.
- *2024.09*: One paper about Mathematical Reasoning and Out-of-Distribution Detection is accepted by <a href="https://neurips.cc/Conferences/2024">NeurIPS 2024</a>.
- *2024.09*: Two paper about Summarization and LLM Agent are accepted by <a href="https://2024.emnlp.org/">EMNLP 2024</a>.
- *2024.05*: One paper about LLM Reasoning is accepted by <a href="https://2024.aclweb.org/">ACL 2024</a>.
- *2023.06*: I earned my B.S. in Artificial Intelligence with a 1/31 overall ranking.
- *2023.05*: One paper about LLM Summarization (SumCoT) is accepted by <a href="https://2023.aclweb.org/">ACL 2023</a>.
- *2022.08*: One paper about Low-resource Summarization is accepted by <a href="https://coling2022.org/">COLING 2022</a>.




# 📝 Selected Preprint


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning, Evaluation</div><img src='images/PolyMath.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PolyMath: Evaluating Mathematical Reasoning in Multilingual Contexts](https://arxiv.org/abs/2504.18428)

**Yiming Wang**, Pei Zhang, Jialong Tang, Haoran Wei, Baosong Yang, Rui Wang, Chenshu Sun, Feitong Sun, Jiran Zhang, Junxuan Wu, Qiqian Cang, Yichang Zhang, Fei Huang, Junyang Lin, Fei Huang, Jingren Zhou

<a href='https://github.com/QwenLM/PolyMath'><button class="code-btn">Code</button></a>
<a href='https://huggingface.co/datasets/Alsace08/PolyMath'><button class="code-btn">Dataset</button></a>
<a href='https://qwen-polymath.github.io/'><button class="code-btn">Leaderboard</button></a>

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning</div><img src='images/ST_BoN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Sampling-Efficient Test-Time Scaling: Self-Estimating the Best-of-N Sampling in Early Decoding](https://arxiv.org/abs/2503.01422)

**Yiming Wang**, Pei Zhang, Siyuan Huang, Baosong Yang, Zhuosheng Zhang, Fei Huang, Rui Wang

</div>
</div>





# 📝 Selected Publications






<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Trustworthy AI, Interpretable AI</div><img src='images/CoE-results.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Latent Space Chain-of-Embedding Enables Output-free LLM Self-Evaluation](https://arxiv.org/abs/2410.13640)

**Yiming Wang**, Pei Zhang, Baosong Yang, Derek F. Wong, Rui Wang

**[ICLR 2025]** International Conference on Learning Representations

<a href='https://github.com/Alsace08/Chain-of-Embedding'><button class="code-btn">Code</button></a>

  
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning, Trustworthy AI</div><img src='images/TVscore.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Embedding Trajectory for Out-of-Distribution Detection in Mathematical Reasoning](https://arxiv.org/abs/2405.14039)

**Yiming Wang**, Pei Zhang, Baosong Yang, Derek F. Wong, Zhuosheng Zhang, Rui Wang

**[NeurIPS 2024]** Annual Conference on Neural Information Processing Systems

<!-- <a href='https://github.com/Alsace08/OOD-Math-Reasoning'><button type="button" class="btn btn-primary">CODE</button></a> -->
<!-- <a href='https://arxiv.org/abs/2405.14039'><button type="button" class="btn btn-danger">PDF</button></a> -->

<a href='https://github.com/Alsace08/OOD-Math-Reasoning'><button class="code-btn">Code</button></a>

<!-- * We discover the ''pattern collapse'' phenomenon under mathematical reasoning -->
<!-- * We propose embedding trajectory volatility (TV Score) to detect OOD samples -->

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning</div><img src='images/CoT_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents](https://arxiv.org/abs/2311.11797)

Zhuosheng Zhang, Yao Yao, Aston Zhang, Xiangru Tang, Xinbei Ma, Zhiwei He, **Yiming Wang**, Mark Gerstein, Rui Wang, Gongshen Liu, Hai Zhao

**[ACM Computing Surveys]** (SCI Q1, IF=23.8)

<a href='https://github.com/Zoeyyao27/CoT-Igniting-Agent'><button class="code-btn">Code</button></a>

<!-- * A comprehensive survey from Chain-of-Thought (CoT) technique to LLM agents -->

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Reasoning</div><img src='images/Meta-Reasoning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Meta-Reasoning: Semantics-Symbol Deconstruction for Large Language Models](https://arxiv.org/abs/2306.17820)

**Yiming Wang**, Zhuosheng Zhang, Pei Zhang, Baosong Yang, Rui Wang

**[ACL 2024 Findings]** Annual Meeting of the Association for Computational Linguistics

<a href='https://github.com/Alsace08/Meta-Reasoning'><button class="code-btn">Code</button></a>

<!-- * We establish the equivalence mapping from semantics to symbols under the purely natural language -->
<!-- * Meta-Reasoning substantially generalizes the reasoning capability of LLMs -->

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Summarization</div><img src='images/sumcot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Element-aware Summarization with Large Language Models: Expert-aligned Evaluation and Chain-of-Thought Method](https://aclanthology.org/2023.acl-long.482/)

**Yiming Wang**, Zhuosheng Zhang, Rui Wang

[**ACL 2023**] Annual Meeting of the Association for Computational Linguistics

<a href='https://github.com/Alsace08/SumCoT'><button class="code-btn">Code</button></a>

<!-- * We construct expert-writing element-aware summary test sets to evaluate general summarization systems more objectively -->
<!-- * We revisit the zero-shot summarization ability of LLMs. -->
<!-- * We propose **SumCoT**, which allows the LLMs to generate more fine-grained summaries step by step. -->


</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Summarization</div><img src='images/cpsum.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Noise-injected Consistency Training and Entropy-constrained Pseudo Labeling for Semi-supervised Extractive Summarization](https://aclanthology.org/2022.coling-1.561/)

**Yiming Wang**, Qianren Mao, Junnan Liu, Weifeng Jiang, Hongdong Zhu, Jianxin Li

**[COLING 2022]** International Conference on Computational Linguistics


<a href='https://github.com/OpenSUM/CPSUM'><button class="code-btn">Code</button></a>

<p style="color:red;"><b>This is my first research paper, and also the last one on the eve of the LLM era.</b></p>

<!-- * We introduce consistency regularization on the extractive summarization task for the first time -->
<!-- * We propose a pseudo-label selection method based on dynamic average entropy comparison and a ramp-up pseudo-label exploration strategy -->
  
</div>
</div>







# 📖 Educations
- *2023.09 - Present*, <a href="https://www.cs.sjtu.edu.cn/">Department of Computer Science and Engineering, Shanghai Jiao Tong University (SJTU)</a>, Shanghai, China
- *2019.09 - 2023.06*, <a href="https://iai.buaa.edu.cn/">Institute of Artificial Intelligence, Beihang University (BUAA)</a>, Beijing, China


# 💻 Internships
- *2024.03 - Present*, Tongyi Laboratory, Alibaba, Hangzhou.
    - Research Intern: Multi-lingual/modal LLMs; Mentor: <a href="https://baosongyang.site/">Dr. Baosong Yang</a>
- *2023.03 - 2023.09*, Institute of AI Industry Research (AIR), Tsinghua University, Beijing.
    - Research Intern: AI for Science; Mentor: <a href="https://zhouh.github.io/">Prof. Hao Zhou</a>
- *2021.11 - 2022.09*, ACT Lab, Department of Computer Science and Engineering, Beihang University, Beijing.
    - Research Intern: Graph Learning / NLP; Mentor: Qianren Mao, <a href="https://myjianxin.github.io/">Prof. Jianxin Li</a>


# 💬 Service

- Reviewer: ICLR (2025), ACL Rolling Review (2024-), IEEE TASLP (2024-)
- Teaching Assistant:
    - Natural Language Processing and Large Language Model (for the John Class (SJTU), CS3966, 2024-)
    - Cognitive Basis (Beihang University, 2022)
    - Advanced Algebra (Beihang University, 2020-2022)


    


# 🎖 Honors and Awards

* *2023.06:* Outstanding Graduate of Beijing (5%)
* *2023.01:* Outstanding Teaching Assistant for Algebra Courses
* *2021.12:* Ministry of Education-Huawei ``Future Star'' Joint Commendation Scholarship
* *2020.12:* The 1st prize in Beijing of the National College Student Mathematics Competition
* *2018.09:* The 1st prize in Jiangsu Province of the Mathematical Competition of Senior High School of China
