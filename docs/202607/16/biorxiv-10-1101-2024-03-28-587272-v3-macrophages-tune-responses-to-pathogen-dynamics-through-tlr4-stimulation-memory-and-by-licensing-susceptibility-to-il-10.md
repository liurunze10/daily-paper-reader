---
title: Macrophages tune responses to pathogen dynamics through TLR4 stimulation memory and by licensing susceptibility to IL-10
title_zh: 巨噬细胞通过 TLR4 刺激记忆和许可对 IL-10 的敏感性来调节对病原体动态的反应
authors: "Bongartz, H., Boughter, C. T., Marrero, B., Prustel, T., Bradfield, C. J., Gross, J. L., Gottschalk, R. A., Nita-Lazar, A., Fraser, I., Meier-Schellersheim, M."
date: 2026-07-09
pdf: "https://www.biorxiv.org/content/10.1101/2024.03.28.587272v3.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 巨噬细胞炎症规模调节与IL-10反应
tldr: 本研究探讨了巨噬细胞如何根据病原体载量动态调节炎症。通过对骨髓来源巨噬细胞施加不同强度的连续TLR4刺激，研究发现巨噬细胞保留了对既往刺激的定量记忆：仅当二次刺激强度达到或超过前次时，才会增强细胞因子输出。此外，IL-10的抑炎作用受TLR4历史“许可”调控，弱启动细胞能抵抗高浓度IL-10。该机制通过BCL-3招募和p65置换实现，使免疫系统能感知感染轨迹，平衡病原体清除与组织保护。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2024-03-28-587272-v3/fig-001.webp\", \"caption\": \"Table 3. Outcome with active resolution (product form, t = 240 h; time courses in main-text Fig. 5B).\", \"page\": 70, \"index\": 1, \"width\": 980, \"height\": 564}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2024-03-28-587272-v3/fig-002.webp\", \"caption\": \"Fig. 2 H, I) (A) Per-cell TNF distributions of firing cells: IL-10 slides the heavily-primed distribution (100/100, mean 2.56) downward relative to the lightly-primed one (1/100, mean 3.72), and anti-IL-10R blockade restores it (mean 3.59); naive cells (0/100, mean 3.30) are shown for reference. (B) Quantile–quantile comparison of the suppressed (100/100) and de-repressed (+anti-IL-10R) distributions lies close to a constant offset (≈ +1.05 log units; uniform gain), not peeling away at the lower quantiles as a suppressed subpopulation would. (C) The de-repression is ≈ 1 log unit at every percentile, with only a mild gradient (low expressers suppressed slightly more).\", \"page\": 72, \"index\": 2, \"width\": 977, \"height\": 750}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2024-03-28-587272-v3/fig-003.webp\", \"caption\": \"Table 1. Gene-expression clusters defined by TLR4 dose and IL-10 dependence. 180\", \"page\": 8, \"index\": 3, \"width\": 956, \"height\": 931}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-1101-2024-03-28-587272-v3/fig-004.webp\", \"caption\": \"Table 2. Outcome at the default operating point (base model, product form, t = 240 h).\", \"page\": 69, \"index\": 4, \"width\": 981, \"height\": 494}]"
motivation: 旨在揭示巨噬细胞如何根据感染轨迹调节炎症强度，并理解IL-10如何避免在错误时机抑制免疫反应。
method: 采用系统变化的连续TLR4刺激方案处理巨噬细胞，并结合分子生物学实验与数学建模进行分析。
result: 发现巨噬细胞存在刺激记忆效应，且对IL-10的敏感性由TLR4预刺激强度决定，涉及BCL-3对Tnf位点p65的置换。
conclusion: 这种“许可逻辑”确保了巨噬细胞能产生感知轨迹的反应，在有效清除病原体的同时限制过度炎症导致的组织损伤。
---

## 摘要
巨噬细胞必须根据感染轨迹调整炎症规模，随病原体载量上升而升级，随其下降而消退。细胞因子 IL-10 及其染色质水平效应因子 BCL-3 是至关重要的抗炎因子，但它们如何避免在这些新招募的细胞读取自身的病原体输入之前就将其抑制，目前尚不清楚。通过对骨髓来源的巨噬细胞施加系统变化的连续 TLR4（Kdo2-Lipid A）刺激，我们发现了两个耦合特征。首先，巨噬细胞保留了先前刺激的定量记忆：只有当二次 TLR 刺激达到或超过先前的刺激时，IκB 降解、NF-κB/MAPK 激活和细胞因子输出才会增加。其次，IL-10 的敏感性本身受 TLR4 历史的门控：即使是 100 倍过量的 IL-10 也无法抑制弱启动细胞中的 TNF-α。这两者都追溯到依赖于历史和 IL-10 的 BCL-3 招募，并伴随着 Tnf κB 位点的 p65 置换。模型显示了这种许可逻辑如何实现感知轨迹的反应，从而在清除病原体的同时限制组织损伤。

## Abstract
Macrophages must scale inflammation to the trajectories of infections, escalating as pathogen loads rise, resolving as they fall. The cytokine IL-10 and its chromatin-level effector BCL-3 are critically important anti-inflammatory agents, yet how they avoid muting newly recruited cells before those cells read their own pathogen input has been unclear. Applying systematically varied consecutive TLR4 (Kdo2-Lipid A) stimuli to bone marrow-derived macrophages, we identify two coupled features. First, macrophages retain a quantitative memory of prior stimulation: only when a secondary TLR stimulus matches or exceeds a prior one, I{kappa}B degradation, NF-{kappa}B/MAPK activation, and cytokine output increase. Second, IL-10 susceptibility is itself gated by TLR4 history: even a 100-fold IL-10 excess fails to suppress TNF- in weakly primed cells. Both trace to history- and IL-10-dependent BCL-3 recruitment with p65 displacement at the Tnf {kappa}B site. Modeling shows how this licensing logic enables trajectory-aware responses that clear pathogens while limiting tissue damage.