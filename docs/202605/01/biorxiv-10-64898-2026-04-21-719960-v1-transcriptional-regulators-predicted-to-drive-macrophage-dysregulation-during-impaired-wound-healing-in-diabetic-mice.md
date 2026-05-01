---
title: Transcriptional regulators predicted to drive macrophage dysregulation during impaired wound healing in diabetic mice
title_zh: 预测在糖尿病小鼠伤口愈合受损过程中驱动巨噬细胞失调的转录调节因子
authors: "Lukas, B. E., Pang, J., Dai, Y., Koh, T. J."
date: 2026-04-24
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.21.719960v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 驱动巨噬细胞状态转变和极化的转录调节因子
tldr: 鉴定了在伤口愈合过程中驱动巨噬细胞表型转变的转录调节因子。
source: biorxiv
selection_source: fresh_fetch
motivation: 驱动巨噬细胞状态转变和极化的转录调节因子。
method: 方法与实现细节请参考摘要与正文。
result: 结果与对比结论请参考摘要与正文。
conclusion: 总体而言，该工作在所述任务上展示了有效性，并提供了可复用的思路或工具。
---

## 摘要
单核细胞/巨噬细胞（Mo/Mφ）活性的失调已知会导致糖尿病伤口愈合受损；然而，这种失调背后的机制尚不完全清楚。在本研究中，我们利用多种生物信息学方法，结合非糖尿病和糖尿病小鼠伤口 Mo/Mφ 的时间序列单细胞 RNA 测序（scRNA-seq）数据，鉴定了在正常和受损愈合过程中驱动 Mo/Mφ 状态转换的转录调节因子（TRs）。首先，我们利用 Lamian 框架和新开发的伪时间图扩散（Pseudotime Graph Diffusion）方法，证明了在糖尿病小鼠愈合受损期间，从早期表型向正常愈合伤口特征性的后期修复和抗原呈递表型的状态转换受阻，而向炎症、泡沫细胞样和 Lyve-1+ Mφ 表型的转换则有所增强。利用我们的 BITFAM 模型，我们鉴定了一系列预测在每种细胞状态中优先活跃的 TRs；并利用 CellOracle 进行了计算机模拟扰动，以鉴定预测驱动细胞状态沿多条轨迹转换的 TRs 组（如 CEBPA、IRF8），而其他 TRs 则被预测驱动细胞状态向修复表型（如 NR1H3、NR3C1）或抗原呈递表型（如 IRF4、OGT）转换。部分发现通过现有实验数据得到了验证，证实了该方法的有效性。总之，我们鉴定了可能驱动 Mo/Mφ 状态向有利于或不利于伤口愈合的表型转换的 TRs。这些发现为通过改变 Mo/Mφ 表型以促进糖尿病伤口愈合的新靶点提供了见解。

## Abstract
Dysregulation of Mo/M{varphi} activity is known to contribute to impaired healing in diabetes; however, the mechanisms underlying this dysregulation are not well understood. In this study, we used a variety of bioinformatics approaches along with our time series scRNA-seq data on wound Mo/M{varphi} from non-diabetic and diabetic mice to identify transcriptional regulators (TRs) that drive Mo/M{varphi} state transitions during normal and impaired healing. First, we used the Lamian framework and our newly developed Pseudotime Graph Diffusion method to show that state transitions from early stage phenotypes to later stage reparative and antigen presenting phenotypes characteristic of normally healing wounds are impaired and that transitions to inflammatory, foam cell-like, and Lyve-1+ M{varphi} phenotypes are enhanced during impaired healing of diabetic mice. Using our BITFAM model, we identified a broad range of TRs predicted to be preferentially active in each cell state and using CellOracle, we performed in silico perturbation to identify groups of TRs predicted to drive cell state transitions along multiple trajectories (e.g. CEBPA, IRF8), whereas other TRs were predicted to drive cell state transition towards reparative phenotypes (e.g. NR1H3, NR3C1) or towards an antigen-presenting phenotype (e.g. IRF4, OGT). Selected findings were validated using existing experimental data, confirming the usefulness of this approach. In conclusion, we identified TRs that likely drive Mo/M{varphi} state transitions towards desirable and undesirable phenotypes for wound healing. These findings provide insight into novel targets for altering Mo/M{varphi} phenotypes to promote healing of diabetic wounds.