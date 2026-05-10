---
title: A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue
title_zh: 一种利用患者组织统一单细胞图谱发现下一代 IBD 靶点的机器学习框架
authors: "Joglekar, A., Joseph, A., Honsa, P., Ruppova, K., Pizzarella, V., Honan, A., Mediratta, D., Vollmer, E., Geller, E., Valny, M., Macuchova, E., Zheng, S., Greenberg, A., Taus, P., Kline-Schoder, A., Konickova, R., Cerna, L., Sharim, H., Ness, L., Camilli, G., Chouri, E., Kaymak, I., D'Rozario, J., Castiblanco, D., Oliveira, J., Prandi, F., Popov, N., Moldoveanu, A. L., Oliphant, C., Escudero-Ibarz, L., Uhlitz, F., Freinkman, E., Sponarova, J., Vijay, P., Joyce, C., Leonardi, I., Nayar, S., Raveh-Sadka, T., Solomon, N., Platt, A., Ort, T., De Baets, G., Corridoni, D., Wroblewska, A., Rahman, A."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.06.699999v3.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: 利用单细胞图谱发现下一代炎症性肠病治疗靶点
tldr: 本研究针对传统炎症性肠病（IBD）靶点发现缺乏细胞分辨率的问题，利用包含100万个单细胞的人类肠道图谱，开发了名为IPR的机器学习框架。该框架系统地识别了疾病相关的转录程序和细胞类型特异性基因靶点。通过临床队列验证和原代细胞模型实验，成功发现了PTGIR和IL6ST等具有潜力的新靶点，为IBD及其他免疫介导疾病提供了可扩展的精准治疗发现方案。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的IBD靶点发现主要依赖遗传关联，难以在细胞层面识别精准且具有治疗潜力的特异性疾病通路。
method: 利用整合了100万个单细胞的肠道图谱，结合IPR机器学习框架和AI辅助推理，系统性地识别并优先排序疾病相关的转录程序及靶点。
result: 成功识别出85个疾病相关转录程序和400个特异性靶点，并通过实验验证了PTGIR和IL6ST在逆转炎症和纤维化病理中的作用。
conclusion: 该框架通过整合单细胞计算发现与实验验证，为IBD及其他免疫介导疾病提供了高效且可扩展的精准治疗靶点发现新路径。
---

## 摘要
炎症性肠病（IBD）的靶点发现传统上依赖于遗传关联，但遗传关联缺乏识别新型、具有转化价值且具备细胞类型特异性的疾病通路所需的细胞分辨率。在此，我们描述了一个整合的分析与实验框架，该框架利用统一的单细胞数据系统地发现 IBD 的新型治疗策略。我们利用 Immunai 的统一单细胞 RNA 数据集数据库 AMICA DB™，构建了一个包含 100 万个细胞的人类肠道统一单细胞图谱。我们应用了一种机器学习框架（免疫患者表征，IPR）来识别疾病相关的转录程序和细胞类型特异性的基因靶点。候选靶点根据图谱衍生的指标进行优先级排序，并利用强调转化可行性的自定义标准进行精炼，随后在独立临床队列中进行了验证。选定的候选靶点在反映靶点细胞类型背景的人类原代细胞模型中进行了评估。IPR 框架识别了 85 个疾病相关的转录程序，并对免疫和基质谱系中的 400 个细胞类型特异性靶基因进行了排序。疾病相关程序通过结构化的 AI 辅助推理框架进行解释，以进行结构化生物学推理，将其与 IBD 相关通路联系起来，并指导新型、有前景的基因靶点的识别。对两个细胞类型特异性候选靶点（髓系细胞中的 PTGIR 和成纤维细胞中的 IL6ST）的功能验证证实，它们能减少与 IBD 病理相关的炎症和纤维化通路。多组学分析以及体外表型向患者数据集的投影表明，通过不同于现有生物制剂的机制，可以逆转疾病相关程序。我们的这种以单细胞为核心的机器学习框架将计算机模拟发现与实验验证相结合，揭示了新的细胞类型特异性治疗机会，并为 IBD 及其他免疫介导疾病的精准靶点发现提供了一种可扩展的方法。

## Abstract
Target discovery for IBD has traditionally relied on genetic associations, which lack the cellular resolution needed to identify novel, actionable, cell type-specific disease pathways. Here, we describe an integrated analytical and experimental framework that leverages harmonized single-cell data to systematically discover novel therapeutic strategies for IBD. We used AMICA DBTM, Immunai's harmonized database of single-cell RNA datasets to construct a harmonized 1 million single-cell atlas of the human intestine. We applied a machine learning framework (Immune Patient Representation, IPR) to identify disease-associated transcriptional programs and cell type-specific gene targets. Candidate targets were prioritized using atlas-derived metrics, refined using custom criteria emphasizing translational actionability, and validated across independent clinical cohorts. Select candidates were evaluated in human primary-cell models reflecting the target's cell-type context. The IPR framework identified 85 disease-associated transcriptional programs and ranked 400 cell type-specific target genes across immune and stromal lineages. Disease-associated programs were interpreted using a structured AI-assisted reasoning framework for structured biological reasoning, linking them to IBD-relevant pathways and guiding the identification of novel, promising gene targets. Functional validation of two cell-type-specific candidates, PTGIR in myeloid cells and IL6ST in fibroblasts, confirmed the reduction of inflammatory and fibrotic pathways linked to IBD pathology. Multi-omic profiling and projection of in vitro phenotypes to patient datasets demonstrated the reversal of disease-associated programs via mechanisms distinct from those of existing biologics. Our single-cell anchored, machine-learning framework integrates in silico discovery with experimental validation, revealing new cell type-specific therapeutic opportunities and supporting a scalable approach for precision target discovery in IBD and other immune-mediated diseases.

---

## 论文详细总结（自动生成）

这是一份关于论文《一种利用患者组织统一单细胞图谱发现下一代 IBD 靶点的机器学习框架》的深度结构化总结：

### 1. 核心问题与整体含义
*   **研究背景**：炎症性肠病（IBD）是一种复杂的慢性炎症，现有疗法（如抗TNF药物）仅对部分患者有效，且长期缓解率低。
*   **核心痛点**：传统的靶点发现主要依赖全基因组关联研究（GWAS），虽然能建立遗传联系，但缺乏**细胞分辨率**，难以识别特定细胞类型中的致病通路。单细胞测序（scRNA-seq）虽有潜力，但数据碎片化且缺乏系统性的转化框架。
*   **研究目的**：构建一个整合大规模单细胞数据、机器学习（ML）和实验验证的闭环框架，以系统性地识别具有细胞特异性、高转化潜力的下一代 IBD 治疗靶点。

### 2. 方法论
*   **核心思想**：通过“统一化图谱 + 机器学习表征 + AI辅助推理”的组合，将海量单细胞数据转化为可解释的治疗靶点。
*   **关键技术细节**：
    *   **AMICA DB™ 统一化**：整合了多个来源的肠道单细胞数据集，构建了一个包含 **100 万个细胞** 的统一图谱，解决了跨研究的批次效应。
    *   **IPR 框架（Immune Patient Representation）**：一种机器学习框架，用于将复杂的单细胞转录组数据降维并提取出**转录程序（Transcriptional Programs, TPs）**。这些程序代表了特定细胞状态下的基因共表达模块。
    *   **靶点优先级排序**：基于疾病相关性、细胞类型特异性、表达丰度及“可药性”（Actionability）对基因进行多维度打分。
    *   **AI 辅助推理**：利用大语言模型（LLM）构建推理链，将计算出的基因模块与生物学通路、临床表型自动关联，加速生物学解释过程。

### 3. 实验设计
*   **数据集**：
    *   **发现集**：100 万个单细胞的人类肠道图谱（涵盖健康、克罗恩病、溃疡性结肠炎）。
    *   **验证集**：多个独立的临床 Bulk RNA-seq 队列（用于验证 TP 与疾病严重程度及治疗反应的相关性）。
*   **Benchmark 与对比**：
    *   将 IPR 识别的程序与已知的 IBD 遗传风险基因（GWAS）进行重叠分析。
    *   将新靶点的作用机制与现有生物制剂（如抗 TNF、抗 IL-23）进行对比，评估其独特性。
*   **功能验证实验**：
    *   **髓系细胞模型**：测试 PTGIR 激动剂对促炎细胞因子产生的影响。
    *   **成纤维细胞模型**：测试 IL6ST 抑制对纤维化相关基因表达的影响。

### 4. 资源与算力
*   **算力说明**：论文中**未明确说明**具体的 GPU 型号、数量或训练总时长。
*   **规模推测**：考虑到处理 100 万个单细胞的统一化、降维及 IPR 模型的训练，该研究必然依赖于高性能计算集群（HPC）和大规模的分布式计算资源。

### 5. 实验数量与充分性
*   **计算实验**：识别了 85 个疾病相关转录程序，并对 400 个细胞特异性靶点进行了排序，覆盖了免疫、基质和上皮等多个谱系。
*   **临床验证**：在多个独立临床队列中进行了交叉验证，确保了计算发现的稳健性。
*   **生物学验证**：重点选择了两个具有代表性的靶点（PTGIR 和 IL6ST）进行深入的功能实验。
*   **充分性评价**：实验设计非常充分，实现了从“干实验”（计算发现）到“湿实验”（原代细胞验证）的完整闭环，且使用了独立的临床数据进行外部校验，结果具有较高的客观性。

### 6. 主要结论与发现
*   **识别新靶点**：成功识别并验证了两个关键靶点：
    1.  **PTGIR**：在髓系细胞中表达，激活该受体可显著抑制炎症反应。
    2.  **IL6ST (gp130)**：在成纤维细胞中驱动纤维化程序，抑制该靶点可逆转疾病相关的基质重塑。
*   **机制独特性**：多组学分析表明，这些新靶点通过不同于现有药物的机制发挥作用，有望解决现有疗法不响应的问题。
*   **框架普适性**：证明了利用统一单细胞图谱和 ML 框架可以系统性地挖掘复杂免疫疾病的精准治疗机会。

### 7. 优点
*   **高分辨率**：克服了传统方法无法区分细胞特异性功能的局限。
*   **数据规模**：百万级细胞图谱提供了极高的统计效能，能够捕捉到稀有细胞群或细微的疾病状态变化。
*   **AI 赋能**：引入 AI 推理框架解决了单细胞数据“难解释”的瓶颈，提高了从数据到见解的转化效率。

### 8. 不足与局限
*   **体内验证缺失**：目前的功能验证主要集中在体外原代细胞模型，尚缺乏动物模型或人体临床试验的直接证据。
*   **数据偏差风险**：尽管进行了统一化处理，但原始单细胞数据的采样偏差（如组织部位、活检深度）可能仍会对结果产生一定影响。
*   **应用限制**：该框架高度依赖高质量、大规模的单细胞数据集，对于缺乏此类数据的罕见病或其他组织类型，其应用受到限制。

（完）
