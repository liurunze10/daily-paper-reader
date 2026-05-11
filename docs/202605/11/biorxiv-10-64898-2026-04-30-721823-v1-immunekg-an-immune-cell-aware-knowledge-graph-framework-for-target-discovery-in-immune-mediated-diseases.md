---
title: "immuneKG: An Immune-Cell-Aware Knowledge Graph Framework for Target Discovery in Immune-Mediated Diseases"
authors: "Ye, Y., PB-IDD Department, Pharmablock Sciences Inc.,"
date: 2026-05-05
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.30.721823v1.full.pdf"
tags: ["query:ros-mp"]
score: 6.0
evidence: 用于免疫介导疾病（包括自身免疫性疾病）靶点发现的知识图谱
tldr: 本研究提出immuneKG，一个专注于自身免疫性疾病的多模态知识图谱框架。它引入了免疫细胞实体和四种新关系，并通过整合自身抗体、细胞因子和HLA基因型等特征对疾病节点进行重编程。结合HeteroPNA-Attn图神经网络和新颖性评分函数，该框架能有效识别炎症性肠病等疾病的潜在药物靶点，为药物研发提供具有生物学解释性的决策支持。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有的生物医学知识图谱在免疫介导疾病的靶点识别中缺乏深度机制建模和免疫细胞层面的关联。
method: 构建包含免疫细胞节点和多模态特征的知识图谱，并开发HeteroPNA-Attn图神经网络进行异构信息融合与推理。
result: "在炎症性肠病靶点预测中，该模型在临床管线验证下达到了0.99的Hits@100，并成功识别出高潜力的新型靶点。"
conclusion: immuneKG通过引入免疫细胞维度和多模态特征，显著提升了药物靶点发现的准确性与生物学可解释性。
---

## Abstract
Biomedical knowledge graphs have emerged as foundational infrastructure for AI-driven drug discovery, yet their translational impact on novel target identification in immune-mediated diseases remains limited. Here we present immuneKG, a multimodal knowledge graph centred on autoimmune diseases, constructed through biologically meaningful feature reprogramming of disease nodes to enable deep mechanistic modelling of immune-related disorders. immuneKG introduces a new entity class immune_cell and four original directed relation types, together adding 9,105 novel triples absent from all existing biomedical KG schemas. Disease nodes are endowed with three novel modal feature sets quantifying immune homeostatic imbalance: autoantibody profiles, cytokine signatures, and HLA genotypes, complemented by systemic involvement scores and genetic features. The graph encompasses over 407,000 training triples across 7,287 entities and 32 relation types. Applied to inflammatory bowel disease (IBD), immuneKG combined with a HeteroPNA-Attn graph neural network achieves a Hits@100 of 0.99 against a Clarivate Phase II+ clinical pipeline, while a novelty-penalised scoring function surfaces high-potential dark targets. The framework shifts from conventional candidate-space screening to a development-oriented decision-support paradigm, providing actionable and interpretable guidance for downstream drug discovery. The immuneKG project is publicly available on GitHub at https://github.com/YaowenYe/immuneKG.

HighlightsO_LIWe propose ImmuneKG, introducing novel immune_cell node types, four original immune-cell relation types, and a gold feature set for autoimmune disease nodes, while pruning redundant nodes to enhance feature depth and distribution balance.
C_LIO_LIWe develop HeteroPNA-Attn, a dedicated heterogeneous graph attention network that mitigates uneven feature distribution density across node modalities. Multi-head mutual attention balances cross-modal weights, yielding steady downstream performance gains as modalities are added.
C_LIO_LIOur novelty-driven scoring module prioritises de novo target discovery over retrospective data fitting. Optimising Hits@1 rather than reporting successes from large candidate pools eliminates selection bias and demonstrates authentic predictive power in real-world R&D scenarios.
C_LIO_LIInterpretability analysis confirms that immune cell nodes play a pivotal role in complex multi-hop graph reasoning; visualisation of path-level attention weights reveals that immuneKG routes predictions through biologically coherent immune-cell intermediaries.
C_LI