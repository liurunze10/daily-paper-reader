---
title: A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue
title_zh: 一种利用患者组织统一单细胞图谱发现下一代 IBD 靶点的机器学习框架
authors: "Joglekar, A., Joseph, A., Honsa, P., Ruppova, K., Pizzarella, V., Honan, A., Mediratta, D., Vollmer, E., Geller, E., Valny, M., Macuchova, E., Zheng, S., Greenberg, A., Taus, P., Kline-Schoder, A., Konickova, R., Cerna, L., Sharim, H., Ness, L., Camilli, G., Chouri, E., Kaymak, I., D'Rozario, J., Castiblanco, D., Oliveira, J., Prandi, F., Popov, N., Moldoveanu, A. L., Oliphant, C., Escudero-Ibarz, L., Uhlitz, F., Freinkman, E., Sponarova, J., Vijay, P., Joyce, C., Leonardi, I., Nayar, S., Raveh-Sadka, T., Solomon, N., Platt, A., Ort, T., De Baets, G., Corridoni, D., Wroblewska, A., Rahman, A."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.06.699999v3.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 利用单细胞图谱发现下一代IBD靶点的机器学习框架
tldr: 本研究针对炎症性肠病（IBD）靶点发现缺乏细胞分辨率的问题，构建了包含100万个细胞的人类肠道单细胞图谱。通过机器学习框架（IPR）识别出85个疾病相关转录程序和400个细胞类型特异性靶点，并成功验证了PTGIR和IL6ST等候选靶点在减轻炎症和纤维化方面的潜力，为IBD及其他免疫疾病提供了可扩展的精准靶点发现新范式。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的IBD靶点发现依赖遗传关联，缺乏识别新型、可操作且具有细胞类型特异性疾病通路所需的细胞分辨率。
method: 利用AMICA数据库构建百万级肠道单细胞图谱，并应用机器学习框架IPR识别疾病相关转录程序及细胞特异性基因靶点。
result: 框架识别出85个疾病程序和400个候选靶点，实验验证了PTGIR和IL6ST在特定细胞中逆转疾病相关程序且机制不同于现有生物制剂。
conclusion: 该单细胞机器学习框架整合了计算发现与实验验证，为IBD及其他免疫介导疾病提供了精准且可扩展的治疗靶点发现方法。
---

## 摘要
IBD 的靶点发现传统上依赖于遗传关联，这缺乏识别新型、可操作且具有细胞类型特异性的疾病通路所需的细胞分辨率。在这里，我们描述了一个整合的分析与实验框架，该框架利用统一的单细胞数据系统地发现 IBD 的新型治疗策略。我们利用 Immunai 的统一单细胞 RNA 数据集数据库 AMICA DBTM，构建了一个包含 100 万个细胞的人类肠道统一单细胞图谱。我们应用了一种机器学习框架（免疫患者表征，IPR）来识别疾病相关的转录程序和细胞类型特异性的基因靶点。候选靶点根据图谱衍生的指标进行优先级排序，并使用强调转化可操作性的自定义标准进行精炼，随后在独立临床队列中进行了验证。选定的候选靶点在反映靶点细胞类型背景的人类原代细胞模型中进行了评估。IPR 框架识别了 85 个疾病相关的转录程序，并对免疫和基质谱系中的 400 个细胞类型特异性靶基因进行了排名。疾病相关程序通过结构化的 AI 辅助推理框架进行解释，以进行结构化生物学推理，将其与 IBD 相关通路联系起来，并指导新型、有前景的基因靶点的识别。对两个细胞类型特异性候选靶点（髓系细胞中的 PTGIR 和成纤维细胞中的 IL6ST）的功能验证证实，它们能减少与 IBD 病理相关的炎症和纤维化通路。多组学分析以及体外表型向患者数据集的投影表明，通过不同于现有生物制剂的机制，可以逆转疾病相关程序。我们的以单细胞为核心的机器学习框架整合了计算机模拟发现与实验验证，揭示了新的细胞类型特异性治疗机会，并为 IBD 和其他免疫介导疾病的精准靶点发现提供了一种可扩展的方法。

## Abstract
Target discovery for IBD has traditionally relied on genetic associations, which lack the cellular resolution needed to identify novel, actionable, cell type-specific disease pathways. Here, we describe an integrated analytical and experimental framework that leverages harmonized single-cell data to systematically discover novel therapeutic strategies for IBD.

We used AMICA DBTM, Immunais harmonized database of single-cell RNA datasets to construct a harmonized 1 million single-cell atlas of the human intestine. We applied a machine learning framework (Immune Patient Representation, IPR) to identify disease-associated transcriptional programs and cell type-specific gene targets. Candidate targets were prioritized using atlas-derived metrics, refined using custom criteria emphasizing translational actionability, and validated across independent clinical cohorts. Select candidates were evaluated in human primary-cell models reflecting the targets cell-type context.

The IPR framework identified 85 disease-associated transcriptional programs and ranked 400 cell type-specific target genes across immune and stromal lineages. Disease-associated programs were interpreted using a structured AI-assisted reasoning framework for structured biological reasoning, linking them to IBD-relevant pathways and guiding the identification of novel, promising gene targets. Functional validation of two cell-type-specific candidates, PTGIR in myeloid cells and IL6ST in fibroblasts, confirmed the reduction of inflammatory and fibrotic pathways linked to IBD pathology. Multi-omic profiling and projection of in vitro phenotypes to patient datasets demonstrated the reversal of disease-associated programs via mechanisms distinct from those of existing biologics.

Our single-cell anchored, machine-learning framework integrates in silico discovery with experimental validation, revealing new cell type-specific therapeutic opportunities and supporting a scalable approach for precision target discovery in IBD and other immune-mediated diseases.

---

## 论文详细总结（自动生成）

这是一份关于论文《A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue》的结构化深入分析总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：炎症性肠病（IBD）的传统靶点发现主要依赖全基因组关联分析（GWAS），虽然识别了大量遗传位点，但缺乏**细胞分辨率**。这导致现有疗法多作用于多效性通路（如类固醇、JAK抑制剂），产生全身性免疫抑制等副作用。
*   **研究动机**：利用单细胞转录组学（scRNA-seq）的高分辨率特性，识别特定细胞类型（如特定巨噬细胞或成纤维细胞）中的致病通路，从而开发更精准、副作用更小的下一代治疗方案。
*   **整体含义**：该研究构建了一个从“大数据整合”到“机器学习发现”再到“实验验证”的闭环框架，旨在解决单细胞数据异质性大、临床转化率低的问题。

### 2. 方法论：核心思想与技术细节
*   **AMICA DB™ 统一图谱构建**：整合了20个公共scRNA-seq研究，通过标准化管道（Cell Ranger处理、低质量过滤、批次校正、细胞本体论标注），构建了包含约100万个细胞的肠道组织图谱。
*   **IPR (Immune Patient Representation) 框架**：
    1.  **Pseudobulk 构建**：在样本层面按细胞类型聚合基因表达，并进行非线性批次校正。
    2.  **线性降维**：提取捕捉主要生物学变异的潜在成分（Latent Components）。
    3.  **特征提取**：将细胞类型特异性的基因载荷作为“IPR特征”，用于区分炎症、治疗反应等生物学状态。
*   **AMICA-Reason™ 推理引擎**：利用大语言模型（LLM）驱动的智能体框架，结合GSEA富集分析和生物医学文献，将统计信号转化为可理解的生物学机制。
*   **多准则优先级排序**：整合图谱转录指标（效应量、炎症关联）、遗传证据（Open Targets）、网络生物学（STRING）、成药性（DGIdb）和安全性（心/肝组织表达）进行综合评分。

### 3. 实验设计：数据集、场景与对比
*   **数据集**：
    *   **发现集**：20个公共研究，530个肠道样本（含CD、UC及健康对照）。
    *   **验证集**：4个独立研究，163个样本（约52万个细胞），用于外部验证。
*   **验证场景**：
    *   **PTGIR 验证**：在原代人单核吞噬细胞（MNP）中通过 CRISPR 敲除验证其对炎症程序的调节。
    *   **IL6ST 验证**：在原代人肠道成纤维细胞中验证其抗纤维化潜力。
*   **Benchmark 与对比方法**：
    *   **已知靶点回收率**：测试框架是否能识别出已上市或临床在研的靶点（如 TNF, ITGA4, JAK3 等）。
    *   **机制对比**：将 PTGIR 敲除的效果与英夫利昔单抗（anti-TNF）处理进行对比，评估机制的独特性。

### 4. 资源与算力
*   **算力说明**：论文未明确列出具体的 GPU 型号、数量或训练总时长。
*   **软件工具**：提及使用了 10x Genomics Cell Ranger (v5.0.1) 进行原始数据处理，以及 Immunai 自有的 AMICA™ 平台进行大规模数据集成和模型训练。考虑到百万级细胞的集成与降维，该研究依赖于高性能计算集群。

### 5. 实验数量与充分性
*   **实验规模**：
    *   识别了 **85个** 显著的疾病相关转录程序。
    *   对 **400个** 细胞特异性靶基因进行了排名。
    *   功能验证涵盖了 **19个** 候选靶点（文中重点展示了 PTGIR 和 IL6ST）。
*   **充分性与客观性**：
    *   **多供体验证**：体外实验使用了 6 个健康供体的原代细胞，通过配对设计减少个体差异。
    *   **临床投影（Clinical Projection）**：将体外敲除产生的基因签名重新投影回 100 万细胞的临床图谱中，验证体外结果与人体组织状态的一致性。
    *   **独立验证**：使用了未参与模型训练的独立数据集进行交叉验证，增强了结果的客观性。

### 6. 主要结论与发现
*   **PTGIR 是巨噬细胞新靶点**：PTGIR 在炎症巨噬细胞中高表达，敲除 PTGIR 可逆转炎症程序，且其作用机制与 anti-TNF 疗法正交（互补），有望解决 anti-TNF 不耐受问题。
*   **IL6ST 的细胞特异性双刃剑**：在成纤维细胞中敲除 IL6ST 具有显著的抗纤维化效果；但在巨噬细胞中敲除反而会诱发促炎反应。这解释了为何非选择性抑制该通路可能失败，强调了**细胞特异性给药**的重要性。
*   **框架有效性**：前 400 个候选基因中包含了约 50% 的已上市 IBD 药物靶点，证明了该机器学习框架对已知生物学的捕捉能力及对新靶点的预测潜力。

### 7. 优点与亮点
*   **端到端集成**：将大规模计算发现与精准的原代细胞实验紧密结合，减少了计算生物学的“虚假发现”。
*   **AI 辅助解释**：引入 AMICA-Reason™ 解决了机器学习模型“黑盒”问题，使复杂的转录组特征具备了临床医生可理解的生物学意义。
*   **系统匹配（SystemMatch）**：在体外实验前，先用算法筛选出与人体组织细胞状态最接近的培养条件，提高了转化成功率。

### 8. 不足与局限
*   **体外模型局限性**：尽管经过优化，原代细胞单层培养仍无法完全模拟肠道复杂的空间结构、微生物群及多细胞交互环境。
*   **数据维度限制**：主要依赖转录组数据，缺乏蛋白质组学或表观遗传组学的深度整合（虽然提及正在扩展）。
*   **验证靶点数量**：虽然筛选出 400 个靶点，但受限于实验成本，仅对极少数靶点进行了深度功能验证。
*   **偏差风险**：公共数据集的质量参差不齐，尽管进行了批次校正，仍可能存在潜在的技术偏差影响特征提取。

（完）
