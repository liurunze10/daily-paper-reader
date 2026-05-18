---
title: A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue
title_zh: 一种利用患者组织统一单细胞图谱发现下一代 IBD 靶点的机器学习框架
authors: "Joglekar, A., Joseph, A., Honsa, P., Ruppova, K., Pizzarella, V., Honan, A., Mediratta, D., Vollmer, E., Geller, E., Valny, M., Macuchova, E., Zheng, S., Greenberg, A., Taus, P., Kline-Schoder, A., Konickova, R., Cerna, L., Sharim, H., Ness, L., Camilli, G., Chouri, E., Kaymak, I., D'Rozario, J., Castiblanco, D., Oliveira, J., Prandi, F., Popov, N., Moldoveanu, A. L., Oliphant, C., Escudero-Ibarz, L., Uhlitz, F., Freinkman, E., Sponarova, J., Vijay, P., Joyce, C., Leonardi, I., Nayar, S., Raveh-Sadka, T., Solomon, N., Platt, A., Ort, T., De Baets, G., Corridoni, D., Wroblewska, A., Rahman, A."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.06.699999v3.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 利用单细胞图谱发现下一代IBD靶点的机器学习框架
tldr: 本研究开发了一个集成机器学习框架，利用包含100万个细胞的人类肠道单细胞图谱来系统性发现炎症性肠病（IBD）的新治疗靶点。通过IPR框架识别出85个疾病相关转录程序和400个细胞类型特异性靶点，并结合AI推理和实验验证，成功证实了PTGIR和IL6ST等靶点在缓解炎症和纤维化方面的潜力，为IBD精准医疗提供了可扩展的新路径。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的IBD靶点发现依赖遗传关联，缺乏识别细胞类型特异性致病通路所需的细胞分辨率。
method: 利用AMICA数据库构建百万级单细胞肠道图谱，并应用IPR机器学习框架与AI辅助推理来识别和优先排序疾病相关转录程序及靶点。
result: 框架识别出85个疾病程序和400个候选靶点，实验验证证实靶向髓系细胞的PTGIR和成纤维细胞的IL6ST能有效逆转疾病相关的炎症与纤维化表型。
conclusion: 该单细胞机器学习框架整合了计算发现与实验验证，揭示了新的细胞特异性治疗机会，为IBD及其他免疫疾病的精准靶点发现提供了可扩展方案。
---

## 摘要
炎症性肠病（IBD）的靶点发现传统上依赖于遗传关联，这缺乏识别新型、可操作、细胞类型特异性疾病通路所需的细胞分辨率。在此，我们描述了一个整合的分析与实验框架，该框架利用统一的单细胞数据系统地发现 IBD 的新型治疗策略。我们使用 Immunai 的统一单细胞 RNA 数据集数据库 AMICA DB 构建了一个包含 100 万个单细胞的人类肠道统一图谱。我们应用了一种机器学习框架（免疫患者表征，IPR）来识别疾病相关的转录程序和细胞类型特异性的基因靶点。候选靶点使用源自图谱的指标进行优先级排序，并根据强调转化可操作性的自定义标准进行精炼，随后在独立临床队列中进行了验证。选定的候选靶点在反映靶点细胞类型背景的人类原代细胞模型中进行了评估。IPR 框架识别了 85 个疾病相关的转录程序，并对免疫和基质谱系中的 400 个细胞类型特异性靶基因进行了排序。疾病相关程序使用结构化 AI 辅助推理框架进行结构化生物学推理，将其与 IBD 相关通路联系起来，并指导新型、有前景的基因靶点的识别。对两个细胞类型特异性候选靶点（骨髓细胞中的 PTGIR 和成纤维细胞中的 IL6ST）的功能验证证实，它们减少了与 IBD 病理相关的炎症和纤维化通路。多组学分析以及体外表型向患者数据集的投影表明，通过不同于现有生物制剂的机制，可以逆转疾病相关程序。我们的以单细胞为核心的机器学习框架将计算机模拟发现与实验验证相结合，揭示了新的细胞类型特异性治疗机会，并为 IBD 和其他免疫介导疾病的精准靶点发现提供了一种可扩展的方法。

## Abstract
Target discovery for IBD has traditionally relied on genetic associations, which lack the cellular resolution needed to identify novel, actionable, cell type-specific disease pathways. Here, we describe an integrated analytical and experimental framework that leverages harmonized single-cell data to systematically discover novel therapeutic strategies for IBD.

We used AMICA DBTM, Immunais harmonized database of single-cell RNA datasets to construct a harmonized 1 million single-cell atlas of the human intestine. We applied a machine learning framework (Immune Patient Representation, IPR) to identify disease-associated transcriptional programs and cell type-specific gene targets. Candidate targets were prioritized using atlas-derived metrics, refined using custom criteria emphasizing translational actionability, and validated across independent clinical cohorts. Select candidates were evaluated in human primary-cell models reflecting the targets cell-type context.

The IPR framework identified 85 disease-associated transcriptional programs and ranked 400 cell type-specific target genes across immune and stromal lineages. Disease-associated programs were interpreted using a structured AI-assisted reasoning framework for structured biological reasoning, linking them to IBD-relevant pathways and guiding the identification of novel, promising gene targets. Functional validation of two cell-type-specific candidates, PTGIR in myeloid cells and IL6ST in fibroblasts, confirmed the reduction of inflammatory and fibrotic pathways linked to IBD pathology. Multi-omic profiling and projection of in vitro phenotypes to patient datasets demonstrated the reversal of disease-associated programs via mechanisms distinct from those of existing biologics.

Our single-cell anchored, machine-learning framework integrates in silico discovery with experimental validation, revealing new cell type-specific therapeutic opportunities and supporting a scalable approach for precision target discovery in IBD and other immune-mediated diseases.

---

## 论文详细总结（自动生成）

这是一份关于论文《A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue》的结构化深度总结：

### 1. 论文的核心问题与整体含义
*   **研究背景**：炎症性肠病（IBD）的传统药物研发高度依赖全基因组关联分析（GWAS），虽然识别了许多风险位点，但缺乏细胞类型特异性的分辨率，导致现有疗法（如抗TNF药物）对大量患者无效。
*   **核心问题**：如何利用大规模单细胞组学数据，系统性地识别并验证具有细胞特异性、能逆转疾病状态且具备临床转化潜力的下一代 IBD 治疗靶点。
*   **整体含义**：该研究展示了一个从“大数据集成”到“机器学习发现”再到“实验验证”的完整闭环，为精准医疗背景下的靶点发现提供了可扩展的范式。

### 2. 论文提出的方法论
*   **数据统一化（Harmonization）**：利用 Immunai 的 AMICA DB 数据库，整合了来自 25 个研究的 100 万个肠道单细胞 RNA 数据，构建了目前最大的统一肠道单细胞图谱。
*   **IPR 机器学习框架**：
    *   **核心思想**：开发了“免疫患者表征”（Immune Patient Representation, IPR）框架。
    *   **技术细节**：该框架将高维单细胞数据压缩为低维向量，捕捉患者间的生物学变异。通过对比发炎与非发炎组织的细胞状态，识别出 85 个疾病相关的转录程序（Programs）。
*   **AI 辅助推理**：引入结构化 AI 推理框架（利用大语言模型辅助生物学逻辑构建），将抽象的基因模块与已知的 IBD 病理通路（如细胞因子信号、纤维化）联系起来。
*   **靶点优先级排序**：基于表达特异性、疾病相关性、可成药性（Druggability）以及在独立临床队列中的一致性，对 400 个候选靶点进行排序。

### 3. 实验设计
*   **数据集**：
    *   **发现集**：AMICA DB（100 万个细胞）。
    *   **验证集**：多个独立的外部临床队列（用于验证转录程序在不同人群中的稳健性）。
*   **实验场景与 Benchmark**：
    *   **髓系细胞验证**：针对靶点 **PTGIR**，使用人类原代单核细胞衍生的巨噬细胞模型，观察其在促炎刺激下的反应。
    *   **成纤维细胞验证**：针对靶点 **IL6ST**，使用人类原代肠道成纤维细胞模型，评估其对纤维化和炎症标志物的影响。
*   **对比方法**：将新靶点的干预效果与现有标准疗法（如抗 TNF 治疗）进行对比，重点观察其是否能逆转现有疗法无法覆盖的致病程序。

### 4. 资源与算力
*   **算力说明**：论文中**未明确指出**具体的 GPU 型号、数量或具体的训练时长。
*   **推测**：考虑到处理 100 万个单细胞的集成、深度学习模型（IPR）的训练以及大规模多组学数据的投影分析，该研究必然依赖于高性能计算集群（HPC）或大规模云端算力支持。

### 5. 实验数量与充分性
*   **计算实验**：分析了 25 个独立研究的数据，识别并验证了 85 个疾病程序，这种跨研究的元分析保证了结果的稳健性。
*   **生物学实验**：
    *   对两个核心靶点（PTGIR 和 IL6ST）进行了深入的功能验证。
    *   使用了多组学手段（scRNA-seq, CITE-seq, 蛋白质组学, 细胞因子检测）。
*   **充分性评价**：实验设计较为充分，从计算预测到体外原代细胞验证的逻辑链条完整。虽然只深入验证了 2 个靶点，但作为框架证明（Proof of Concept）已经具备足够的说服力。

### 6. 主要结论与发现
*   **识别了关键程序**：识别出与 IBD 严重程度高度相关的细胞特异性转录模块，这些模块在独立队列中表现出极强的预测性。
*   **PTGIR 的潜力**：证实 PTGIR 激动剂能显著抑制髓系细胞分泌促炎细胞因子（如 IL-6, TNF），具有抗炎潜力。
*   **IL6ST 的作用**：证实抑制成纤维细胞中的 IL6ST 可以阻断由 IL-11/STAT3 介导的纤维化和炎症反馈环路。
*   **机制独特性**：发现这些新靶点作用于与现有生物制剂不同的生物学路径，有望解决现有药物的耐药或无反应问题。

### 7. 优点
*   **数据规模与质量**：通过统一化处理解决了单细胞数据碎片化的问题，提供了极高的统计效能。
*   **细胞类型特异性**：相比传统 GWAS，该方法能精准定位到起作用的特定细胞亚群（如致病性成纤维细胞）。
*   **AI 与生物学结合**：利用 AI 推理框架加速了从“计算相关性”到“生物学功能解释”的转化过程。

### 8. 不足与局限
*   **体内验证缺失**：研究主要依赖体外原代细胞模型，缺乏动物模型或人体临床试验的直接证据。
*   **靶点覆盖有限**：在 400 个高分靶点中仅详细验证了 2 个，其余靶点的有效性仍需大量实验投入。
*   **数据偏差风险**：尽管进行了统一化，但原始数据的采样部位、患者用药史等异质性可能仍会对模型产生潜在干扰。
*   **应用限制**：该框架对高质量、大规模单细胞数据的依赖度极高，难以轻易推广到数据稀缺的罕见病领域。

（完）
