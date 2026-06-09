---
permalink: /
title: "Yihui Wang's Homepage"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## 👋 About

I am an undergraduate student in Software Engineering at [Hefei University of Technology](http://www.hfut.edu.cn), and a remote research intern at **NExT++ Research Centre, National University of Singapore**, supervised by [Dr. Yonghui Yang](https://yonghui-yang.github.io) and [Prof. Tat-Seng Chua](https://www.chuatatseng.com) (NUS Chair Professor, Singapore National Academy of Sciences). My research focuses on **LLM Safety & Alignment**, **Interpretable Robust Learning**, and **Multimodal Deepfake Detection**. I also hold multiple **ICPC/CCPC/CCSP** medals, including a **CCPC National Gold**, which sharpen my algorithmic and engineering skills.

## 📰 News

- **[May. 2026]** Led **HFUT Team 101** to win a **Gold Medal** at the **CCPC National Invitational (Nanchang)**.
- **[Jun. 2026]** Won a **Silver Medal** at the **CCPC National Invitational (Guiyang)** as a member of **Exercise Everyday**.
- **[May. 2026]** Our work **NeVA** (Neuron-level Value Alignment) was submitted to **ACL Rolling Review (ARR)** (CCF-A, co-first author).
- **[Apr. 2026]** Our work **S³** (Suppressing Method-Specific Shortcuts) was submitted to **ACM MM 2026** (CCF-A, first author).
- **[Feb. 2026]** Our work **CLEAR** (Cross-modal De-redundancy) has been transferred to **AAAI** (CCF-A).
- **[2025]** Ongoing research on **LLM Deep Safety Alignment (BEACON)**, targeting **ICLR 2027** (first author).

## 🎓 Education

- **B.Eng. in Software Engineering**, Hefei University of Technology, 2023 – 2027  
  *GPA: 90.78/100 (Top 1.75%)*
- **Remote Research Intern**, NExT++ Research Centre, National University of Singapore, 2025 – Present  
  *Supervised by Dr. Yonghui Yang and Prof. Tat-Seng Chua*

## 🔬 Research

*All work conducted at NUS NExT++ Research Centre.*

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- PROJECT 1: BEACON                                                      -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<p style="text-align: center; margin: 20px 0;">
  <img src="images/beacon.png" alt="BEACON Framework Overview" style="width: 100%; max-width: 800px;">
</p>

### LLM Deep Safety Alignment: Auditing Shallow Alignment via Representation-Level Diagnosis (BEACON)

**First Author** · Targeting **ICLR 2027** (CCF-A) · 2025 – Present

- **Quantified a belief-behavior gap**: internal probes detect harmful intent with >95% accuracy at *any* prefix length, yet model compliance surges from <2% to >50% as prefix grows — proving alignment failure is a *generation-side* problem, not a *representation-side* problem.
- **Proposed BEACON**: token-wise consistency losses anchor the model's generation behavior to its own internal harmfulness judgment, maintaining refusal robustness regardless of prefix length. Cuts adversarial attack success rate from >50% to ≤5% across four models and up to 3,000-token prefixes.

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- PROJECT 2: S³                                                          -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<p style="text-align: center; margin: 20px 0;">
  <img src="images/s3.png" alt="S³ Method Overview" style="width: 100%; max-width: 800px;">
</p>

### S³: Suppressing Method-Specific Shortcuts for Generalizable Deepfake Detection

**First Author** · **ACM MM 2026** (CCF-A, Under Review) · 2025 – 2026

- **Identified the root cause** of cross-domain failure in deepfake detection: trained detectors learn to classify forgery *method* rather than forgery *presence* — a shortcut that makes out-of-distribution collapse structurally inevitable, regardless of backbone or data scale.
- **Designed two independent remedies**: gradient projection (**NSP**) steers training away from method-discriminative feature directions; a plug-in inference module (**NAE**) achieves the same effect without backbone retraining. Cross-domain AUC gains exceed 10× the in-domain cost, validated across four backbones and a fully held-out open-world benchmark.

---

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- PROJECT 3: NeVA                                                        -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<p style="text-align: center; margin: 20px 0;">
  <img src="images/neva.png" alt="NeVA Method Overview" style="width: 100%; max-width: 800px;">
</p>

### NeVA: Controllable Value Alignment in LLMs via Neuron-Level Editing

**Co-first Author** · **ACL ARR** (CCF-A, Under Review) · 2026

- Locates and edits the sparse subset of neurons governing specific value outputs in LLMs and LVLMs, enabling **fine-grained value alignment without parameter updates**.

---

### CLEAR: Null-Space Projection for Cross-Modal De-Redundancy in Multimodal Recommendation

**Co-first Author** · **AAAI** (CCF-A, Submitting) · 2025 – 2026

- We remove coarse-grained cross-modal redundancy by projecting embeddings onto the null-space of the dominant covariance subspace — plug-and-play, no auxiliary loss.

## 🏆 Awards & Honors

- **National Scholarship**, Top 1% — Ministry of Education of China (2024)
- **Gold Medal** — CCPC National Invitational, Nanchang (2026)
- **Silver Medal** — CCPC National Invitational, Guiyang (2026)
- **Bronze Medal** — ICPC Asia Regional, Chengdu (2025)
- **Bronze Medal**, 2× — CCPC Regional, Jinan & Zhengzhou (2025)
- **Bronze Medal** — CCF CCSP; CSP 360/500, Top 1% (2025)
- **First Prize**, 2× — Anhui Province Robot Competition, Programming Track (2024, 2025)
- **Gold Prize** — Anhui Province Innovation Competition (2024)

## 👥 Leadership & Service

- **ACM Team Leader**, HFUT XCPC Team (Binary Algorithm Studio), 2024 – Present  
  *CCPC National Gold Medalist; lead daily training & solution-sharing for 20+ members; problem setter and organizer for HFUT ACM School Contest and Anhui Province Programming Competition (100+ teams).*
- **Video Team Lead**, HFUT University Media Center — Visual Imaging Studio, 2023 – 2025  
  *Produced 10+ official university videos, several adopted by Xinhua News Agency; organized cross-college photography and film editing courses reaching 300+ students.*

## 💻 Technical Strengths

- **Research Focus**: LLM Safety & Alignment · Robust Deepfake Detection · Interpretability
- **Engineering**: CCPC National Gold Medalist; production-grade full-stack developer in Python, C/C++, Java, Qt, and modern web frameworks; ship complex systems from prototype to deployment; 2 software copyrights
- **Tools & Languages**: PyTorch · MATLAB · LaTeX · Git · English CET-6: 553
- **Open Source & Community**: Maintainer of ManimVE rendering engine; educational math/CS animation creator on [Bilibili](https://space.bilibili.com/1900464093); active open-source contributor

## 📫 Contact

- **Email**: [wangyihui@mail.hfut.edu.cn](mailto:wangyihui@mail.hfut.edu.cn)
- **Secondary**: [mistrynihilityn@gmail.com](mailto:mistrynihilityn@gmail.com)
- **GitHub**: [Mistry-Nihilityn](https://github.com/Mistry-Nihilityn)
- **Location**: Hangzhou, Zhejiang, China
