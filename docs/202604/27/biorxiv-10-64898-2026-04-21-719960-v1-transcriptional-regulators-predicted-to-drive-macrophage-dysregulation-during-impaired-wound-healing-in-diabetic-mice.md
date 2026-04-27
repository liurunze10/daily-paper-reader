---
title: Transcriptional regulators predicted to drive macrophage dysregulation during impaired wound healing in diabetic mice
title_zh: 预测驱动糖尿病小鼠伤口愈合受损过程中巨噬细胞失调的转录调节因子
authors: "Lukas, B. E., Pang, J., Dai, Y., Koh, T. J."
date: 2026-04-24
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.21.719960v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 驱动巨噬细胞状态转换的转录调节因子
tldr: 本研究旨在揭示糖尿病小鼠伤口愈合障碍中巨噬细胞失调的机制。通过对非糖尿病和糖尿病小鼠伤口巨噬细胞的单细胞转录组测序数据进行生物信息学分析，研究者发现糖尿病环境下巨噬细胞向修复型表型的转化受阻，而向炎症和泡沫细胞样表型的转化增强。利用BITFAM和CellOracle等工具，研究识别并验证了驱动这些状态转换的关键转录调节因子（如CEBPA、NR1H3等），为促进糖尿病伤口愈合提供了潜在的治疗靶点。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究糖尿病环境下巨噬细胞活动失调导致伤口愈合受损的具体分子机制。
method: 利用单细胞转录组测序数据，结合Lamian框架、伪时间图扩散法、BITFAM模型及CellOracle模拟扰动等多种生物信息学手段进行分析。
result: 识别出驱动巨噬细胞向修复型或炎症型表型转换的关键转录调节因子，并证实糖尿病会阻碍向修复型表型的正常转化。
conclusion: 该研究确定了影响巨噬细胞状态转换的转录调节因子，为通过调节巨噬细胞表型来改善糖尿病伤口愈合提供了新思路。
---

## 摘要
单核细胞/巨噬细胞（Mo/Mφ）活性的失调已知会导致糖尿病伤口愈合受损；然而，这种失调背后的机制尚不完全清楚。在本研究中，我们利用多种生物信息学方法，结合非糖尿病和糖尿病小鼠伤口 Mo/Mφ 的时间序列单细胞 RNA 测序（scRNA-seq）数据，鉴定了在正常和受损愈合过程中驱动 Mo/Mφ 状态转换的转录调节因子（TRs）。首先，我们利用 Lamian 框架和新开发的伪时间图扩散（Pseudotime Graph Diffusion）方法，证明了从早期表型向正常愈合伤口特征性的后期修复和抗原呈递表型的状态转换受损，而在糖尿病小鼠愈合受损期间，向炎症、泡沫细胞样和 Lyve-1 Mφ 表型的转换则有所增强。利用我们的 BITFAM 模型，我们鉴定了预测在每种细胞状态中优先激活的广泛 TRs；并利用 CellOracle 进行了计算机模拟扰动（in silico perturbation），以鉴定预测驱动沿多条轨迹进行细胞状态转换的 TRs 组（如 CEBPA、IRF8），而其他 TRs 则被预测驱动细胞状态向修复表型（如 NR1H3、NR3C1）或抗原呈递表型（如 IRF4、OGT）转换。部分发现通过现有实验数据得到了验证，证实了该方法的有效性。总之，我们鉴定了可能驱动 Mo/Mφ 状态向伤口愈合有利或不利表型转换的 TRs。这些发现为通过改变 Mo/Mφ 表型以促进糖尿病伤口愈合的新靶点提供了见解。

## Abstract
Dysregulation of Mo/M{varphi} activity is known to contribute to impaired healing in diabetes; however, the mechanisms underlying this dysregulation are not well understood. In this study, we used a variety of bioinformatics approaches along with our time series scRNA-seq data on wound Mo/M{varphi} from non-diabetic and diabetic mice to identify transcriptional regulators (TRs) that drive Mo/M{varphi} state transitions during normal and impaired healing. First, we used the Lamian framework and our newly developed Pseudotime Graph Diffusion method to show that state transitions from early stage phenotypes to later stage reparative and antigen presenting phenotypes characteristic of normally healing wounds are impaired and that transitions to inflammatory, foam cell-like, and Lyve-1 M{varphi} phenotypes are enhanced during impaired healing of diabetic mice. Using our BITFAM model, we identified a broad range of TRs predicted to be preferentially active in each cell state and using CellOracle, we performed in silico perturbation to identify groups of TRs predicted to drive cell state transitions along multiple trajectories (e.g. CEBPA, IRF8), whereas other TRs were predicted to drive cell state transition towards reparative phenotypes (e.g. NR1H3, NR3C1) or towards an antigen-presenting phenotype (e.g. IRF4, OGT). Selected findings were validated using existing experimental data, confirming the usefulness of this approach. In conclusion, we identified TRs that likely drive Mo/M{varphi} state transitions towards desirable and undesirable phenotypes for wound healing. These findings provide insight into novel targets for altering Mo/M{varphi} phenotypes to promote healing of diabetic wounds.