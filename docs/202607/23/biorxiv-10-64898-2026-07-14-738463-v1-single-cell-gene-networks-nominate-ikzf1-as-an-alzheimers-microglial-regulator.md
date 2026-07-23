---
title: "Single-cell gene networks nominate IKZF1 as an Alzheimer's microglial regulator"
title_zh: 单细胞基因网络提名 IKZF1 为阿尔茨海默病小胶质细胞调节因子
authors: "Ozkurt, C."
date: 2026-07-15
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.14.738463v1.full.pdf"
tags: ["query:ros-mp"]
score: 6.0
evidence: 小胶质细胞状态转变与神经炎症
tldr: 本研究针对阿尔茨海默病中由小胶质细胞驱动的神经炎症，利用SEA-AD图谱的单细胞核转录组数据，通过轨迹推断和基因调控网络分析，识别出调控小胶质细胞状态转换的关键转录因子IKZF1。研究还预测了神经元与小胶质细胞间的SLIT2-ROBO2通讯路径，并筛选出氯苯唑酸等潜在重定位药物，为AD精准治疗提供了新靶点。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-14-738463-v1/fig-001.webp\", \"caption\": \"\", \"page\": 10, \"index\": 1, \"width\": 1247, \"height\": 989}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-14-738463-v1/fig-002.webp\", \"caption\": \"\", \"page\": 16, \"index\": 2, \"width\": 1247, \"height\": 747}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-14-738463-v1/fig-003.webp\", \"caption\": \"\", \"page\": 17, \"index\": 3, \"width\": 1247, \"height\": 947}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-14-738463-v1/fig-004.webp\", \"caption\": \"\", \"page\": 19, \"index\": 4, \"width\": 1247, \"height\": 680}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-14-738463-v1/fig-005.webp\", \"caption\": \"\", \"page\": 26, \"index\": 5, \"width\": 1247, \"height\": 900}]"
motivation: 旨在识别控制阿尔茨海默病中小胶质细胞状态转换的转录因子，并寻找可用于药物重定位的结构化候选化合物。
method: 对84名供体的23.6万个小胶质细胞核数据应用轨迹推断、基因调控网络分析、细胞通讯分析及1962种批准药物的虚拟筛选。
result: 确定IKZF1为晚期疾病相关小胶质细胞的关键调控因子，并发现SLIT2-ROBO2是神经元向小胶质细胞传递信号的主要路径。
conclusion: IKZF1被确认为阿尔茨海默病晚期小胶质细胞的候选转录因子，而筛选出的重定位药物仍需进一步实验验证。
---

## 摘要
背景：小胶质细胞驱动阿尔茨海默病（AD）中的神经炎症，但目前尚无针对该领域的获批疗法。人类全基因组关联研究（GWAS）一致表明先天免疫位点与 AD 风险相关，这使得小胶质细胞转录程序成为具有治疗相关性但尚未被充分开发的药理学靶点。目的：我们旨在通过计算方法识别控制小胶质细胞状态转换的转录因子（TFs），并提名结构上易于处理的药物重利用候选药物。方法：我们对来自 84 名捐赠者的 236,002 个小胶质细胞核（SEA-AD 图谱）应用了轨迹推断（PAGA）、伪批量（pseudobulk）DESeq2、pySCENIC 基因调控网络（GRN）推断、CellChat 以及对 1,962 种已获批化合物的虚拟筛选。结果：IKZF1 是在 cisTarget v10 基序约束下保留的唯一目标转录因子，其调节子活性在晚期 AD 疾病相关小胶质细胞（LateAD-DAM）中达到峰值（伪时间 rho = +0.309），并在独立的大宗（bulk）队列中得到验证（GSE95587；校正后 P 值 = .004）。CellChat 识别出源自多种神经元亚型（主要是抑制性中间神经元）的 SLIT2->ROBO2 是预测的通往小胶质细胞的首选通路。氯苯唑酸（针对 IRF8）和二氟尼柳（针对 PPARG）是虚拟筛选中的领先候选药物；所有评估的化合物均未达到预设的选择性阈值。结论：IKZF1 被优先列为候选的疾病晚期小胶质细胞转录因子，并得到了包括独立大宗验证在内的六个收敛证据维度的支持。氯苯唑酸和二氟尼柳是低置信度的药物重利用假设，需要进一步的实验验证。

## Abstract
BackgroundMicroglia drive neuroinflammation in Alzheimers disease (AD), yet no approved therapy targets this compartment. Human genome-wide association studies consistently implicate innate immune loci in AD risk, establishing microglial transcriptional programs as therapeutically relevant but pharmacologically underexploited targets.

ObjectiveWe sought to identify transcription factors (TFs) governing microglial state transitions computationally and to nominate structurally tractable drug repurposing candidates.

MethodsWe applied trajectory inference (PAGA), pseudobulk DESeq2, pySCENIC gene regulatory network (GRN) inference, CellChat, and virtual screening of 1,962 approved compounds to 236,002 microglial nuclei from 84 donors (SEA-AD atlas).

ResultsIKZF1 was the sole target TF retained under cisTarget v10 motif constraints, with peak regulon activity in LateAD-DAM (pseudotime {rho} = +0.309) and replication in an independent bulk cohort (GSE95587; adjusted P value =.004). CellChat identified SLIT2[-&gt;]ROBO2 from multiple neuron subtypes (predominantly inhibitory interneurons) as the top predicted pathway to microglia. Tafamidis ([-&gt;]IRF8) and diflunisal ([-&gt;]PPARG) were top virtual screening hits; all evaluated compounds failed the pre-specified selectivity threshold.

ConclusionsIKZF1 is prioritised as a candidate late-disease microglial TF, supported by six convergent evidence dimensions including independent bulk replication. Tafamidis and diflunisal are low-confidence repurposing hypotheses requiring experimental validation.