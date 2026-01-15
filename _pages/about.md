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

I am **Chenzhuo Zhao**, currently an **M.E. student in Electronic Information** at **Peking University, School of Software & Microelectronics** (2024.09–2027.07). I received my B.E. in **Software Engineering** from **Northwestern Polytechnical University (NPU), School of Software** (2020.09–2024.07), ranked **1/313** with **GPA 3.80/4.10**.

My research focuses on **LLM post-training**, including **RFT / RLVR / GRPO-style methods**, **prompt optimization**, and **evaluation** (multi-judge frameworks, benchmarking), with interests spanning **multilingual** and **multimodal** settings.

- Email: `cyczzhao@gmail.com`
- Phone: `177-8297-1779`
- Party membership: CPC

---

# 🔥 News
- *2026*: Focusing on LLM post-training: stability of RLVR/GRPO, learning signal & reward design, prompt optimization, and evaluation.
- *2025*: Papers submitted/published at top venues (AAAI / IJCAI / EMNLP / ACL, etc.).

---

# 📝 Publications / Preprints

> Note: The list below is organized from the CV image you provided. I can help fill in authors, links, BibTeX, and code repos if you share them.

### Prompt Optimization
- **PMPO: Probabilistic Metric Prompt Optimization for Small and Large Language Models** *(EMNLP 2025)*  
  - Proposes **PMPO**, a token-level scoring and reward-model-driven framework that unifies *low-quality prompt diagnosis → sample generation → policy rewrite*.  
  - Improves accuracy on BBH-style tasks and increases win-rate on AlpacaEval 2.0, demonstrating scalability across small and large models.

- **Gradient-Guided Multi-Judge Prompt Optimization** *(ACL 2026, under review)*  
  - Addresses overfitting to a single judge and poor transferability via multi-judge feedback with gradient-guided refinement.  
  - Achieves stable gains on math reasoning, language understanding, and instruction following under a ~0.11M token optimization budget.

### Evaluation / Benchmarking
- **TASE: Token Awareness and Structured Evaluation for Multilingual Language Models** *(AAAI 2025)*  
  - Targets tokenization-induced bias and systematic evaluation gaps in multilingual settings with a structured benchmark and scalable data-generation pipeline.  
  - Builds a 36k test set and analyzes mechanisms using GRPO-trained Qwen2.5-14B.

### RLVR / Post-training
- **ARPO: Answer-Refined Policy Optimization for Learning from Hard Instances in Group-Relative RLVR** *(ACL 2026, under review)*  
  - Proposes **ARPO** for hard instances under group-relative rewards, combining answer-refined prompts with off-policy shaping to improve learning signals.  
  - Mitigates training stalls caused by all-zero groups; improves pass@1 on Qwen2.5-Math-7B (e.g., 37.61→40.38) and boosts small-model performance.

---

# 🎖 Honors and Awards
- **National Scholarship** (two consecutive years)
- **Xiaomi Special Scholarship**
- **Outstanding Student Role Model (Nominee)**, NPU
- **First-class Scholarship** (three consecutive years)
- **Outstanding Student**, **Outstanding Communist Youth League Cadre**
- **National Undergraduate Innovation & Entrepreneurship Project** (excellent completion, two consecutive years)
- Tencent “**Supernova**” Program — **Excellent Completion**

---

# 📖 Education
- **Peking University** — M.E., Electronic Information (School of Software & Microelectronics)  
  *Sep 2024 – Jul 2027*  
  Research: LLM post-training

- **Northwestern Polytechnical University (NPU)** — B.E., Software Engineering (School of Software)  
  *Sep 2020 – Jul 2024*  
  GPA: 3.80/4.10 | Rank: 1/313

---

# 💻 Experience

### Microsoft — LLM Research Intern, Search & Distribution Group
*Sep 2025 – Present*  
- Work on post-training with verifiable feedback, tackling **sparse learning signals**, **training instability**, and **upper-bound bottlenecks**. Responsible for training design, experiments/ablations, evaluation, and diagnostics.  
- **Learning-signal enhancement**: explore ARPO-style strategies to better exploit supervision/reference information under strict verification rewards without changing the main framework.  
- **Process-signal / credit assignment**: propose finer-grained credit assignment using structured intermediate reasoning states to better control advantage/reward allocation.

### Xiaohongshu (RED) — LLM Algorithm Intern, AI Platform
*Feb 2025 – Jul 2025*  
- Improve search Query understanding under sparse/noisy user intent signals; focus on an interpretable, end-to-end pipeline from **Query understanding → recall enhancement → review/risk identification**, and ship optimizations online.  
- **Query understanding & recall**: iterate QueryNER with online incremental learning and hot updates; low-resource multi-domain hard-example mining and data augmentation; adopt LLM-as-Judge for data quality; SFT+GRPO on Qwen2.5-14B, reaching ~82.1% recognition accuracy and >10% gains in online/offline F1.  
- **Ecosystem review & routing**: design an 8-step structured reasoning template and multi-metric agreement checks; SFT+GRPO based on Gemma3-27B, boosting routing task F1 from 0.56→0.71 with improved stability.  
- **Training platform & experimentation**: support engine iterations and large-scale experiments; run DeepSeek 671B LoRA on 64×H20; completed 22,400 experiment groups to support performance/stability optimization and business metric tracking.

### Tencent — Computer Vision Intern, YouTu Lab
*Apr 2024 – Jan 2025*  
- Built and deployed rPPG-based face anti-spoofing for payment scenarios: method design, scenario validation, on-device deployment, and evaluation.  
- **Paper**: propose **EST-rPPG** to address unstable short-window rPPG signals and 3D mask robustness; reliable detection with ~0.13s window (first-author submission).  
- **Transfer & deployment**: extend rPPG liveness to palm liveness recognition; refactor and deploy the full pipeline; achieved 99.99% accuracy on self-collected data.  
- **Competition & patents**: 6th place in IJCAI RCPSS unsupervised challenge; filed 3 invention patents covering core method and engineering components.

---

{% comment %}
Optional: keep Scholar stats here if you want:
- Google Scholar: https://scholar.google.com/citations?user=XXXXXXXXXXX
{% endcomment %}
