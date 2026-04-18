---
permalink: /
title: "Chenzhuo Zhao"
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% comment %}
If you use a Google Scholar badge/stats plugin, replace the `user=` id below with your Scholar ID.
https://scholar.google.com/citations?user=XXXXXXXXXXX
{% endcomment %}

<span class='anchor' id='about-me'></span>

# 👋 About Me

I am **Chenzhuo Zhao**, currently an **M.E. student in Software Engineering** at **Peking University, School of Software & Microelectronics** (*Sep 2024 – Jul 2027*). I received my B.E. in **Software Engineering** from **Northwestern Polytechnical University (NPU), School of Software** (*Sep 2020 – Jul 2024*), ranking **1/313** with a **GPA of 3.80/4.10**.

My research focuses on **LLM post-training**, including **RFT / RLVR / GRPO-style methods**, **prompt optimization**, **agentic systems**, and **evaluation**.

- Email: `cyczzhao@gmail.com`
- Phone: `177-8297-1779`

---

# 💼 Career Interests

I am currently interested in the following directions:

🤖 **Large Language Model Applications**: Developing and deploying practical, production-ready LLM systems across diverse domains, with a focus on solving real-world problems.

⚖️ **Large Language Model Alignment**: Aligning LLM behavior with human values and intentions to build safer and more reliable systems, covering robustness, controllability, reward modeling, and evaluation.

🧩 **Agentic Systems for Real-World Problem Solving**: Building LLM-powered agents that can plan, use tools, and execute multi-step workflows to solve complex user problems end to end, with strong attention to verification, safety, and measurable impact.

---

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/PMPO.png' alt="PMPO paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PMPO: Probabilistic Metric Prompt Optimization for Small and Large Language Models**

**Chenzhuo Zhao**, Ziqian Liu, Xinda Wang, Junting Lu, Chaoyi Ruan

[**Paper**](#) <strong><span class='show_paper_citations' data=''></span></strong>

- Proposes **PMPO**, a lightweight prompt optimization framework driven by token-level scoring and reward-model-guided rewriting.
- Unifies *prompt diagnosis → sample generation → policy rewrite* for both small and large language models.
- Achieves strong gains on BBH-style tasks and improves win rate on AlpacaEval 2.0.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/tase.png' alt="TASE paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TASE: Token Awareness and Structured Evaluation for Multilingual Language Models**

**Chenzhuo Zhao**, Xinda Wang, Yue Huang, Junting Lu, Ziqian Liu

[**Paper**](#) | [**Code**](#) <strong><span class='show_paper_citations' data=''></span></strong>

- Introduces a structured benchmark for multilingual language models, explicitly addressing tokenization-induced bias.
- Builds a scalable data-generation pipeline and a **36k** test set spanning multiple task types.
- Analyzes multilingual capability gaps with GRPO-trained Qwen2.5-14B models.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 (Under Review)</div><img src='images/ARPO.png' alt="ARPO paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ARPO: Answer-Refined Policy Optimization for Learning from Hard Instances in Group-Relative RLVR**

**Chenzhuo Zhao**, Pu Zhao, Fangkai Yang, Lu Wang, Qibin Wang, Liqun Li, Xinda Wang, Ran Jia, Xu Chen, Junting Lu, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang

[**Paper**](#) <strong><span class='show_paper_citations' data=''></span></strong>

- Proposes **ARPO** to improve learning on hard instances under group-relative rewards in RLVR.
- Combines answer-refined prompting with controlled off-policy shaping to mitigate training stalls such as all-zero groups.
- Improves pass@1 on Qwen2.5-Math-7B from **37.61** to **40.38**.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 (Under Review)</div><img src='images/gmpo.png' alt="GMPO paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Gradient-Guided Multi-Judge Prompt Optimization**

**Chenzhuo Zhao**, Xinda Wang, Pu Zhao, Yue Huang, Junting Lu, Ziqian Liu, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang

[**Paper**](#) | [**Code**](#) <strong><span class='show_paper_citations' data=''></span></strong>

- Uses multi-judge feedback to reduce overfitting to a single evaluator and improve transferability.
- Introduces gradient-guided refinement for more stable and efficient prompt updates.
- Delivers consistent gains on math reasoning, language understanding, and instruction-following benchmarks.

</div>
</div>

## Full Publication List

- **PMPO: Probabilistic Metric Prompt Optimization for Small and Large Language Models**, **Chenzhuo Zhao**, Ziqian Liu, Xinda Wang, Junting Lu, Chaoyi Ruan. **EMNLP 2025**
- **TASE: Token Awareness and Structured Evaluation for Multilingual Language Models**, **Chenzhuo Zhao**, Xinda Wang, Yue Huang, Junting Lu, Ziqian Liu. **AAAI 2025**
- **ARPO: Answer-Refined Policy Optimization for Learning from Hard Instances in Group-Relative RLVR**, **Chenzhuo Zhao**, Pu Zhao, Fangkai Yang, Lu Wang, Qibin Wang, Liqun Li, Xinda Wang, Ran Jia, Xu Chen, Junting Lu, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang. **ACL 2026 (Under Review)**
- **Gradient-Guided Multi-Judge Prompt Optimization**, **Chenzhuo Zhao**, Xinda Wang, Pu Zhao, Yue Huang, Junting Lu, Ziqian Liu, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang. **ACL 2026 (Under Review)**
- **Process Rewarding via Solution-Space Alignment**, **Chenzhuo Zhao**. **EMNLP 2026 (Under Review)**
- **SciFigDetect: A Benchmark for AI-Generated Scientific Figure Detection**, **Chenzhuo Zhao** (co-first author). **ACM Multimedia 2026 (Under Review)**
- **PEARL: Perturbation Efficient Alignment Group-Relative Reinforcement Learning**, **Chenzhuo Zhao** (co-first author). **EMNLP 2026 (Under Review)**
- **EvolvR: Self-Evolving Pairwise Reasoning for Story Evaluation to Enhance Generation**, Xinda Wang, Zhengxu Hou, Yangshijie Zhang, Yanbingren, Jialin Liu, **Chenzhuo Zhao**, Zhibo Yang, Bin-Bin Yang, Feng Xiao. **ACL 2026 (Under Review)**
- **Triviality Corrected Endogenous Reward**, Xinda Wang, Zhengxu Hou, Yangshijie Zhang, Yanbingren, Jialin Liu, **Chenzhuo Zhao**, Zhibo Yang, Bin-Bin Yang, Feng Xiao. **ACL 2026 (Under Review)**
- **MedReflect: Teaching Medical LLMs to Self-Improve via Reflective Correction**, Yue Huang, Yanyuan Chen, Dexuan Xu, **Chenzhuo Zhao**, Weihua Yue, Yu Huang. **ACL 2026 (Under Review)**
- **DisRec: Intra-Visit Disease Diagnosis as Recommendation**, Xinda Wang, Hongzhi Liu, **Chenzhuo Zhao**, Wenhao Zhang. **IJCAI 2026 (Under Review)**

Additional manuscripts are in progress, with planned submissions to **ICML**, **EMNLP**, and **ACM Multimedia**.

---

# 🎖 Honors and Awards

- **National Scholarship** (twice)
- **Xiaomi Special Scholarship**
- **Outstanding Student Role Model (Nominee)**, NPU
- **First-Class Scholarship** (three consecutive years)
- **Outstanding Student**
- **Outstanding Communist Youth League Cadre**
- **National Undergraduate Innovation and Entrepreneurship Project** (excellent completion, twice)
- Tencent **Supernova Program** — **Excellent Completion**

---

# 📖 Education

- **Peking University** — M.E. in Software Engineering, School of Software & Microelectronics  
  *Sep 2024 – Jul 2027*  
  Research focus: LLM post-training

- **Northwestern Polytechnical University (NPU)** — B.E. in Software Engineering, School of Software  
  *Sep 2020 – Jul 2024*  
  GPA: **3.80/4.10** | Rank: **1/313**

---

# 💻 Experience

<div class='paper-box'><div class='paper-box-image'><div style="display:flex;align-items:center;justify-content:center;background:#fff;padding:12px;min-height:110px;"><img src='https://upload.wikimedia.org/wikipedia/commons/0/07/ByteDance_logo_English.svg' alt='ByteDance logo' style='max-width:90%;max-height:56px;object-fit:contain;'></div></div>
<div class='paper-box-text' markdown="1">

### ByteDance Seed — LLM Research Intern
*Mar 2026 – Present*

- Work on **Doubao Expert Mode** optimization, spanning **reward model design**, **data and training pipeline construction**, **tool-use chain optimization**, **evaluation**, and **release support**.
- **Reward modeling and training pipeline**: design and iterate the reward model for the expert-mode system, building an end-to-end pipeline from data construction and sample processing to training, evaluation, and analysis to improve signal quality and alignment performance.
- **Expert-model optimization**: continuously refine training strategies, data policies, and evaluation loops for complex real-world tasks, while contributing to **Seed Pro** release integration, validation, and issue diagnosis.
- **Agent tool-use optimization**: improve tool selection, call decisions, result utilization, and end-to-end task completion quality to increase execution stability and usability in multi-step real-world scenarios.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="display:flex;align-items:center;justify-content:center;background:#fff;padding:12px;min-height:110px;"><img src='https://upload.wikimedia.org/wikipedia/commons/9/96/Microsoft_logo_%282012%29.svg' alt='Microsoft logo' style='max-width:90%;max-height:54px;object-fit:contain;'></div></div>
<div class='paper-box-text' markdown="1">

### Microsoft — Research Intern, DKI
*Sep 2025 – Mar 2026*

- Focused on **RLVR post-training optimization** under verifiable feedback, targeting **sparse learning signals**, **training instability**, and **performance ceilings**.
- Responsible for training strategy design, experiment and ablation pipelines, training diagnostics, and reusable recipe development.
- **Learning-signal enhancement**: explored ARPO-style strategies to make better use of supervision and reference information under strict verifiable rewards, improving stability and upper-bound performance without expanding data.
- **Process-signal optimization**: investigated finer-grained **credit assignment** based on structured intermediate reasoning states to improve reward allocation and learning control.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="display:flex;align-items:center;justify-content:center;background:#fff;padding:12px;min-height:110px;"><img src='https://upload.wikimedia.org/wikipedia/commons/a/a4/Xiaohongshu_logo%26slogan.png' alt='Xiaohongshu logo' style='max-width:90%;max-height:64px;object-fit:contain;'></div></div>
<div class='paper-box-text' markdown="1">

### Xiaohongshu — LLM Algorithm Intern, AI Platform
*Feb 2025 – Jul 2025*

- Worked on large-model optimization for **search query understanding**, **recall improvement**, and **ecosystem review/risk identification**, covering the full loop from data construction and model training to online deployment.
- **Query understanding and recall**: iterated the QueryNER pipeline for long-tail and emerging entities, supported online incremental learning and hot updates, and led relevance modeling improvements for hard boundary and paraphrase cases.
- Built a personalized **query rewriting** loop with multi-constraint prompting and user-behavior-driven sample generation; introduced **LLM-as-Judge** for data quality control and used **SFT + GRPO** on **Qwen2.5-14B**, reaching about **82.1%** recognition accuracy and improving online/nearline F1 by more than **10%**.
- **Review and routing**: designed an 8-step structured reasoning template for mixed image-text traffic-diversion detection; fine-tuned **Gemma3-27B** with **SFT + GRPO**, improving task F1 from **0.56** to **0.71** with stronger stability.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="display:flex;align-items:center;justify-content:center;background:#fff;padding:12px;min-height:110px;"><img src='https://upload.wikimedia.org/wikipedia/commons/6/6a/Tencent_logo_2017.svg' alt='Tencent logo' style='max-width:90%;max-height:56px;object-fit:contain;'></div></div>
<div class='paper-box-text' markdown="1">

### Tencent YouTu Lab — Computer Vision Intern
*Apr 2024 – Jan 2025*

- Built and deployed **rPPG-based liveness detection** for palm-payment and face anti-spoofing scenarios, covering method design, cross-scenario transfer, edge deployment, and evaluation.
- Proposed **EST-rPPG**, a dual-level liveness method that improves robustness under short temporal windows and 3D mask attacks, enabling reliable detection with an approximately **0.13s** window.
- Extended face-liveness capability to **palm-liveness recognition**, completed end-to-end pipeline refactoring and on-device acceleration, and achieved **99.99%** accuracy on an in-house palm dataset.
- Contributed to research writing, scenario validation, and engineering deployment for real payment-security applications.

</div>
</div>

---

# 🚀 Open-Source Contribution

### EditDeck: From Requirements to Fully Editable Slide Decks
*GitHub 500+ Stars | Owner*

- Designed and built an **LLM-agent-driven** slide generation and editable reconstruction system.
- Unified page planning, style generation, outline generation, slide-by-slide rendering, and document packaging into a closed-loop workflow.
- Combined placeholder capture, MinerU-based asset parsing, geometric matching, and code generation to automatically produce editable **`.pptx`** files.
- Further improved robustness through runtime-feedback-driven self-repair across multiple generation rounds.

---

{% comment %}
Optional: keep Scholar stats here if you want:
- Google Scholar: https://scholar.google.com/citations?user=XXXXXXXXXXX
{% endcomment %}
