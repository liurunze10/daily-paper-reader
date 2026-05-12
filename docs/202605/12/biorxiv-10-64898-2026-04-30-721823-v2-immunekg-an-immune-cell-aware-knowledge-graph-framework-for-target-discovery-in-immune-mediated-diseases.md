---
title: "immuneKG: An Immune-Cell-Aware Knowledge Graph Framework for Target Discovery in Immune-Mediated Diseases"
title_zh: immuneKG：一种用于免疫介导疾病靶点发现的免疫细胞感知知识图谱框架
authors: "Ye, Y., PB-IDD Department, Pharmablock Sciences Inc.,"
date: 2026-05-07
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.30.721823v2.full.pdf"
tags: ["query:ros-mp"]
score: 6.5
evidence: 用于免疫介导疾病（包括免疫细胞状态）靶点发现的知识图谱
tldr: 本研究提出immuneKG，一个专注于自身免疫性疾病的多模态知识图谱框架。它引入了免疫细胞实体和四种新关系，并通过整合自身抗体、细胞因子和HLA基因型等特征对疾病节点进行重编程。结合HeteroPNA-Attn图神经网络和新颖性评分函数，该框架能有效识别炎症性肠病等疾病的潜在药物靶点，为药物研发提供具有生物学解释性的决策支持。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有的生物医学知识图谱在免疫介导疾病的靶点识别中缺乏深度机制建模和免疫细胞层面的关联。
method: 构建包含免疫细胞节点和多模态特征的知识图谱，并开发HeteroPNA-Attn图神经网络进行异构信息融合与推理。
result: "在炎症性肠病靶点预测中，该模型在临床管线验证下达到了0.99的Hits@100，并成功识别出高潜力的新型靶点。"
conclusion: immuneKG通过引入免疫细胞维度和多模态特征，显著提升了药物靶点发现的准确性与生物学可解释性。
---

## 摘要
生物医学知识图谱已成为人工智能驱动药物研发的基础设施，但其在免疫介导疾病新靶点识别方面的转化影响仍然有限。在此，我们提出了 immuneKG，这是一个以自身免疫性疾病为中心的多模态知识图谱，通过对疾病节点进行具有生物学意义的特征重编程，实现了对免疫相关疾病的深度机制建模。immuneKG 引入了新的实体类别 immune_cell 和四种原创的有向关系类型，共增加了 9,105 个现有生物医学知识图谱模式中缺失的新三元组。疾病节点被赋予了三组量化免疫稳态失衡的新型模态特征：自身抗体谱、细胞因子特征和 HLA 基因型，并辅以系统受累评分和遗传特征。该图谱包含跨越 7,287 个实体和 32 种关系类型的超过 407,000 个训练三元组。应用于炎症性肠病（IBD）时，immuneKG 结合 HeteroPNA-Attn 图神经网络，在针对 Clarivate II 期及以上临床管线的测试中实现了 0.99 的 Hits@100，同时新颖性惩罚评分函数挖掘出了具有高潜力的“暗靶点”。该框架从传统的候选空间筛选转向以开发为导向的决策支持范式，为下游药物研发提供可操作且可解释的指导。immuneKG 项目已在 GitHub 公开发布。亮点：1. 我们提出 ImmuneKG，引入了新型 immune_cell 节点类型、四种原创免疫细胞关系类型以及自身免疫性疾病节点的黄金特征集，同时剪枝冗余节点以增强特征深度和分布平衡。2. 我们开发了 HeteroPNA-Attn，这是一种专门的异构图注意力网络，可缓解跨节点模态的特征分布密度不均。多头互注意力平衡了跨模态权重，随着模态的增加产生稳定的下游性能提升。3. 我们的新颖性驱动评分模块优先考虑从头靶点发现而非回顾性数据拟合。通过优化 Hits@1 而非报告大型候选池的成功，消除了选择偏差，并展示了在真实研发场景中的真实预测能力。4. 可解释性分析证实，免疫细胞节点在复杂的多跳图推理中起着关键作用；路径级注意力权重的可视化揭示了 immuneKG 通过生物学一致的免疫细胞中间体引导预测。

## Abstract
Biomedical knowledge graphs have emerged as foundational infrastructure for AI-driven drug discovery, yet their translational impact on novel target identification in immune-mediated diseases remains limited. Here we present immuneKG, a multimodal knowledge graph centred on autoimmune diseases, constructed through biologically meaningful feature reprogramming of disease nodes to enable deep mechanistic modelling of immune-related disorders. immuneKG introduces a new entity class immune_cell and four original directed relation types, together adding 9,105 novel triples absent from all existing biomedical KG schemas. Disease nodes are endowed with three novel modal feature sets quantifying immune homeostatic imbalance: autoantibody profiles, cytokine signatures, and HLA genotypes, complemented by systemic involvement scores and genetic features. The graph encompasses over 407,000 training triples across 7,287 entities and 32 relation types. Applied to inflammatory bowel disease (IBD), immuneKG combined with a HeteroPNA-Attn graph neural network achieves a Hits@100 of 0.99 against a Clarivate Phase II+ clinical pipeline, while a novelty-penalised scoring function surfaces high-potential dark targets. The framework shifts from conventional candidate-space screening to a development-oriented decision-support paradigm, providing actionable and interpretable guidance for downstream drug discovery. The immuneKG project is publicly available on GitHub at https://github.com/YaowenYe/immuneKG.

HighlightsO_LIWe propose ImmuneKG, introducing novel immune_cell node types, four original immune-cell relation types, and a gold feature set for autoimmune disease nodes, while pruning redundant nodes to enhance feature depth and distribution balance.
C_LIO_LIWe develop HeteroPNA-Attn, a dedicated heterogeneous graph attention network that mitigates uneven feature distribution density across node modalities. Multi-head mutual attention balances cross-modal weights, yielding steady downstream performance gains as modalities are added.
C_LIO_LIOur novelty-driven scoring module prioritises de novo target discovery over retrospective data fitting. Optimising Hits@1 rather than reporting successes from large candidate pools eliminates selection bias and demonstrates authentic predictive power in real-world R&D scenarios.
C_LIO_LIInterpretability analysis confirms that immune cell nodes play a pivotal role in complex multi-hop graph reasoning; visualisation of path-level attention weights reveals that immuneKG routes predictions through biologically coherent immune-cell intermediaries.
C_LI