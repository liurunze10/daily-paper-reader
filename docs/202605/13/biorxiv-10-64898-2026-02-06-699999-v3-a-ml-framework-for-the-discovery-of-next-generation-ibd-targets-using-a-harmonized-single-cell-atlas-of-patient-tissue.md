---
title: A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue
title_zh: 一种利用患者组织统一单细胞图谱发现下一代 IBD 靶点的机器学习框架
authors: "Joglekar, A., Joseph, A., Honsa, P., Ruppova, K., Pizzarella, V., Honan, A., Mediratta, D., Vollmer, E., Geller, E., Valny, M., Macuchova, E., Zheng, S., Greenberg, A., Taus, P., Kline-Schoder, A., Konickova, R., Cerna, L., Sharim, H., Ness, L., Camilli, G., Chouri, E., Kaymak, I., D'Rozario, J., Castiblanco, D., Oliveira, J., Prandi, F., Popov, N., Moldoveanu, A. L., Oliphant, C., Escudero-Ibarz, L., Uhlitz, F., Freinkman, E., Sponarova, J., Vijay, P., Joyce, C., Leonardi, I., Nayar, S., Raveh-Sadka, T., Solomon, N., Platt, A., Ort, T., De Baets, G., Corridoni, D., Wroblewska, A., Rahman, A."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.06.699999v3.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 利用单细胞图谱发现IBD靶点的机器学习框架
tldr: 本研究针对炎症性肠病（IBD）传统靶点发现缺乏细胞分辨率的问题，构建了一个包含百万级单细胞的肠道图谱。通过机器学习框架（IPR）识别出85个疾病相关转录程序和400个细胞类型特异性靶点。实验验证了PTGIR和IL6ST等候选靶点在缓解炎症和纤维化方面的潜力，展示了与现有生物制剂不同的作用机制，为IBD及其他免疫疾病提供了精准的靶点发现新范式。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的IBD靶点发现依赖遗传关联，缺乏识别新型、可操作且具有细胞类型特异性疾病通路所需的细胞分辨率。
method: 利用AMICA数据库构建百万级肠道单细胞图谱，并应用IPR机器学习框架识别疾病相关转录程序，结合AI辅助推理和原代细胞模型进行验证。
result: 框架识别出85个疾病程序和400个特异性靶点，并证实PTGIR和IL6ST能有效逆转与IBD相关的炎症和纤维化表型。
conclusion: 该单细胞机器学习框架实现了从计算发现到实验验证的闭环，为IBD及免疫介导疾病提供了可扩展的精准治疗靶点发现方法。
---

## 摘要
炎症性肠病（IBD）的靶点发现传统上依赖于遗传关联，这缺乏识别新型、可操作、细胞类型特异性疾病通路所需的细胞分辨率。在此，我们描述了一个整合的分析与实验框架，该框架利用统一的单细胞数据系统地发现 IBD 的新型治疗策略。我们使用 Immunai 的统一单细胞 RNA 数据集数据库 AMICA DBTM，构建了一个包含 100 万个单细胞的人类肠道统一图谱。我们应用了一种机器学习框架（免疫患者表征，IPR）来识别疾病相关的转录程序和细胞类型特异性的基因靶点。候选靶点使用源自图谱的指标进行优先级排序，并根据强调转化可操作性的自定义标准进行精炼，随后在独立临床队列中进行了验证。选定的候选靶点在反映靶点细胞类型背景的人类原代细胞模型中进行了评估。IPR 框架识别了 85 个疾病相关的转录程序，并对免疫和基质谱系中的 400 个细胞类型特异性靶基因进行了排序。疾病相关程序使用结构化 AI 辅助推理框架进行结构化生物学推理，将其与 IBD 相关通路联系起来，并指导新型、有前景的基因靶点的识别。对两个细胞类型特异性候选靶点（骨髓细胞中的 PTGIR 和成纤维细胞中的 IL6ST）的功能验证证实，它们减少了与 IBD 病理相关的炎症和纤维化通路。多组学分析以及体外表型向患者数据集的投影表明，通过不同于现有生物制剂的机制，可以逆转疾病相关程序。我们的以单细胞为核心的机器学习框架将计算机模拟发现与实验验证相结合，揭示了新的细胞类型特异性治疗机会，并为 IBD 和其他免疫介导疾病的精准靶点发现提供了一种可扩展的方法。

## Abstract
Target discovery for IBD has traditionally relied on genetic associations, which lack the cellular resolution needed to identify novel, actionable, cell type-specific disease pathways. Here, we describe an integrated analytical and experimental framework that leverages harmonized single-cell data to systematically discover novel therapeutic strategies for IBD.

We used AMICA DBTM, Immunais harmonized database of single-cell RNA datasets to construct a harmonized 1 million single-cell atlas of the human intestine. We applied a machine learning framework (Immune Patient Representation, IPR) to identify disease-associated transcriptional programs and cell type-specific gene targets. Candidate targets were prioritized using atlas-derived metrics, refined using custom criteria emphasizing translational actionability, and validated across independent clinical cohorts. Select candidates were evaluated in human primary-cell models reflecting the targets cell-type context.

The IPR framework identified 85 disease-associated transcriptional programs and ranked 400 cell type-specific target genes across immune and stromal lineages. Disease-associated programs were interpreted using a structured AI-assisted reasoning framework for structured biological reasoning, linking them to IBD-relevant pathways and guiding the identification of novel, promising gene targets. Functional validation of two cell-type-specific candidates, PTGIR in myeloid cells and IL6ST in fibroblasts, confirmed the reduction of inflammatory and fibrotic pathways linked to IBD pathology. Multi-omic profiling and projection of in vitro phenotypes to patient datasets demonstrated the reversal of disease-associated programs via mechanisms distinct from those of existing biologics.

Our single-cell anchored, machine-learning framework integrates in silico discovery with experimental validation, revealing new cell type-specific therapeutic opportunities and supporting a scalable approach for precision target discovery in IBD and other immune-mediated diseases.

---

## 论文详细总结（自动生成）

这篇论文介绍了一个结合机器学习与单细胞组学的整合框架，旨在发现炎症性肠病（IBD）的下一代治疗靶点。以下是对该论文的结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：传统的 IBD 靶点发现主要依赖全基因组关联分析（GWAS），虽然识别了大量遗传位点，但缺乏细胞分辨率，导致现有疗法（如类固醇、JAK 抑制剂）多为广谱免疫抑制，副作用大且部分患者不响应。
*   **研究动机**：利用单细胞 RNA 测序（scRNA-seq）的高分辨率特性，识别特定细胞类型（如特定巨噬细胞或成纤维细胞）中的致病通路，从而开发更精准、更安全的疗法。

### 2. 方法论：核心思想与技术细节
该框架包含四个关键环节：
*   **AMICA DB™ 统一图谱构建**：整合了 20 个公开研究的原始数据，通过标准化流水线进行质量控制、批次校正和细胞注释，构建了包含约 100 万个细胞的肠道单细胞图谱。
*   **免疫患者表征（IPR）框架**：
    *   **伪批量处理（Pseudobulk）**：按样本和细胞类型聚合基因表达。
    *   **线性降维**：提取捕捉生物学变异的潜在分量（IPR 特征）。
    *   **特征提取**：识别与疾病状态（如发炎 vs 非发炎）、治疗响应相关的细胞类型特异性转录程序。
*   **AMICA-Reason™ 推理引擎**：利用大型语言模型（LLM）驱动的智能体框架，结合统计富集分析和生物医学文献，对机器学习提取的抽象特征进行生物学解释。
*   **SystemMatch 与临床投影**：
    *   **SystemMatch**：通过计算匹配，选择与患者体内细胞状态最接近的体外原代细胞模型。
    *   **临床投影**：将体外基因敲除（KO）产生的转录特征映射回临床图谱，验证其是否能逆转疾病特征。

### 3. 实验设计：数据集、场景与对比
*   **数据集**：
    *   **发现集**：20 个公开研究，530 个肠道样本，994,206 个细胞。
    *   **验证集**：独立整合了 4 个新研究，163 个样本，约 52 万个细胞。
*   **验证场景**：重点验证了两个靶点：**PTGIR**（在脂质相关巨噬细胞中）和 **IL6ST**（在成纤维细胞中）。
*   **对比方法（Benchmark）**：
    *   **靶点排序对比**：检查框架是否能重新识别出已上市或临床在研的 IBD 药物靶点（如 TNF, ITGA4, JAK3 等）。
    *   **机制对比**：将候选靶点与现有生物制剂（Infliximab/抗 TNF、Tofacitinib/JAKi、Vedolizumab/抗整合素）的作用机制进行横向对比。

### 4. 资源与算力
*   **算力说明**：论文中**未明确说明**具体的 GPU 型号、数量或训练时长。
*   **软件工具**：提到了使用 10x Genomics Cell Ranger (v5.0.1) 处理原始数据，以及使用 R 语言环境下的 limma-voom 等标准生物信息学工具。

### 5. 实验数量与充分性
*   **实验规模**：
    *   **计算层面**：分析了 85 个显著的疾病相关特征，对 400 个靶基因进行了排序。
    *   **实验层面**：对 19 个候选靶点进行了初步筛选，并对 PTGIR 和 IL6ST 进行了深入的功能验证。
    *   **样本量**：体外实验使用了来自 6 名健康供体的原代单核细胞衍生巨噬细胞，以及来自 4 名供体（小肠和结肠）的原代成纤维细胞。
*   **充分性评价**：实验设计较为充分且客观。通过独立队列验证、多组学（RNA-seq + 流式 + 蛋白质组）交叉验证以及临床投影技术，确保了从计算预测到生物学功能的闭环验证。

### 6. 主要结论与发现
*   **靶点识别**：框架成功识别并排序了 400 个细胞类型特异性靶点，其中约 50% 的已上市 IBD 药物靶点排在前列，证明了框架的有效性。
*   **PTGIR 发现**：在巨噬细胞中敲除 PTGIR 可逆转促炎代谢状态，减少 VEGF-A 和 CCL7 分泌，且其机制与抗 TNF 疗法正交（互补）。
*   **IL6ST 发现**：在成纤维细胞中敲除 IL6ST 具有抗纤维化作用，但在巨噬细胞中敲除却会诱发炎症，强调了**细胞类型特异性给药**的重要性。
*   **临床相关性**：临床投影证实，候选靶点的干预效果能显著向“健康/非发炎”状态偏移。

### 7. 优点：亮点与创新
*   **数据统一化**：克服了单细胞数据碎片化和批次效应的难题，构建了大规模统一图谱。
*   **AI 辅助解释**：引入 AMICA-Reason™ 解决了机器学习特征“黑盒”问题，使统计信号转化为可理解的生物学假设。
*   **转化导向**：不仅停留在计算发现，还通过 SystemMatch 优化了实验模型，并通过临床投影增强了结果的转化可信度。

### 8. 不足与局限
*   **模型局限性**：尽管进行了计算优化，但体外原代细胞模型仍无法完全模拟肠道复杂的微环境（如微生物群、空间结构）。
*   **给药挑战**：IL6ST 的实验结果显示其在不同细胞中作用相反，这对药物递送技术（如何精准靶向成纤维细胞而非巨噬细胞）提出了极高要求。
*   **数据偏差**：虽然整合了大量数据，但主要来源于公开数据集，可能存在临床元数据不完整或采样偏差。

（完）
