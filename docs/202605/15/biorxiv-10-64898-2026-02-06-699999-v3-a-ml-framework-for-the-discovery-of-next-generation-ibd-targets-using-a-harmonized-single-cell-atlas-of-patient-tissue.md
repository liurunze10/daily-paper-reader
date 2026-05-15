---
title: A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue
title_zh: 基于患者组织统一单细胞图谱的下一代 IBD 靶点发现机器学习框架
authors: "Joglekar, A., Joseph, A., Honsa, P., Ruppova, K., Pizzarella, V., Honan, A., Mediratta, D., Vollmer, E., Geller, E., Valny, M., Macuchova, E., Zheng, S., Greenberg, A., Taus, P., Kline-Schoder, A., Konickova, R., Cerna, L., Sharim, H., Ness, L., Camilli, G., Chouri, E., Kaymak, I., D'Rozario, J., Castiblanco, D., Oliveira, J., Prandi, F., Popov, N., Moldoveanu, A. L., Oliphant, C., Escudero-Ibarz, L., Uhlitz, F., Freinkman, E., Sponarova, J., Vijay, P., Joyce, C., Leonardi, I., Nayar, S., Raveh-Sadka, T., Solomon, N., Platt, A., Ort, T., De Baets, G., Corridoni, D., Wroblewska, A., Rahman, A."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.06.699999v3.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 利用单细胞图谱发现IBD靶点的机器学习框架
tldr: 本研究针对炎症性肠病（IBD）靶点发现缺乏细胞分辨率的问题，构建了包含100万个细胞的人类肠道单细胞图谱。通过机器学习框架（IPR）识别出85个疾病相关转录程序和400个细胞类型特异性靶点，并成功验证了PTGIR和IL6ST等候选靶点在减轻炎症和纤维化方面的潜力，为IBD及其他免疫疾病提供了可扩展的精准靶点发现新范式。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的IBD靶点发现依赖遗传关联，缺乏识别新型、可操作且具有细胞类型特异性疾病通路所需的细胞分辨率。
method: 利用AMICA数据库构建百万级肠道单细胞图谱，并应用机器学习框架IPR识别疾病相关转录程序及细胞特异性基因靶点。
result: 框架识别出85个疾病程序和400个候选靶点，实验验证了PTGIR和IL6ST在特定细胞中逆转疾病相关表型的有效性。
conclusion: 该单细胞机器学习框架整合了计算发现与实验验证，为IBD及其他免疫介导疾病提供了精准且可扩展的治疗靶点发现方法。
---

## 摘要
炎症性肠病（IBD）的靶点发现传统上依赖于遗传关联，这缺乏识别新型、可成药、细胞类型特异性疾病通路所需的细胞分辨率。在此，我们描述了一个整合的分析与实验框架，利用统一的单细胞数据系统地发现 IBD 的新型治疗策略。我们利用 Immunai 的统一单细胞 RNA 数据集数据库 AMICA DB™，构建了一个包含 100 万个细胞的人类肠道统一单细胞图谱。我们应用机器学习框架（免疫患者表征，IPR）来识别疾病相关的转录程序和细胞类型特异性基因靶点。候选靶点通过图谱衍生指标进行优先级排序，并根据强调转化可成药性的定制标准进行精炼，随后在独立临床队列中进行了验证。选定的候选靶点在反映靶点细胞类型背景的人类原代细胞模型中进行了评估。IPR 框架识别了 85 个疾病相关的转录程序，并对免疫和基质谱系中的 400 个细胞类型特异性靶点基因进行了排名。利用结构化 AI 辅助推理框架对疾病相关程序进行了解释，将其与 IBD 相关通路联系起来，并指导了新型、具有前景的基因靶点的识别。对两个细胞类型特异性候选靶点（骨髓细胞中的 PTGIR 和成纤维细胞中的 IL6ST）的功能验证证实，它们能减少与 IBD 病理相关的炎症和纤维化通路。多组学分析以及体外表型向患者数据集的投影表明，通过与现有生物制剂不同的机制，可以逆转疾病相关程序。我们的以单细胞为核心的机器学习框架将计算机模拟发现与实验验证相结合，揭示了新的细胞类型特异性治疗机会，并为 IBD 及其他免疫介导疾病的精准靶点发现提供了一种可扩展的方法。

## Abstract
Target discovery for IBD has traditionally relied on genetic associations, which lack the cellular resolution needed to identify novel, actionable, cell type-specific disease pathways. Here, we describe an integrated analytical and experimental framework that leverages harmonized single-cell data to systematically discover novel therapeutic strategies for IBD.

We used AMICA DBTM, Immunais harmonized database of single-cell RNA datasets to construct a harmonized 1 million single-cell atlas of the human intestine. We applied a machine learning framework (Immune Patient Representation, IPR) to identify disease-associated transcriptional programs and cell type-specific gene targets. Candidate targets were prioritized using atlas-derived metrics, refined using custom criteria emphasizing translational actionability, and validated across independent clinical cohorts. Select candidates were evaluated in human primary-cell models reflecting the targets cell-type context.

The IPR framework identified 85 disease-associated transcriptional programs and ranked 400 cell type-specific target genes across immune and stromal lineages. Disease-associated programs were interpreted using a structured AI-assisted reasoning framework for structured biological reasoning, linking them to IBD-relevant pathways and guiding the identification of novel, promising gene targets. Functional validation of two cell-type-specific candidates, PTGIR in myeloid cells and IL6ST in fibroblasts, confirmed the reduction of inflammatory and fibrotic pathways linked to IBD pathology. Multi-omic profiling and projection of in vitro phenotypes to patient datasets demonstrated the reversal of disease-associated programs via mechanisms distinct from those of existing biologics.

Our single-cell anchored, machine-learning framework integrates in silico discovery with experimental validation, revealing new cell type-specific therapeutic opportunities and supporting a scalable approach for precision target discovery in IBD and other immune-mediated diseases.

---

## 论文详细总结（自动生成）

这是一份关于论文《A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue》的结构化深入总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：传统的炎症性肠病（IBD）药物靶点发现主要依赖全基因组关联分析（GWAS），虽然识别了大量遗传位点，但缺乏**细胞分辨率**，导致开发的药物往往作用于多效性通路（如类固醇、JAK抑制剂），产生全身性免疫抑制等副作用。
*   **研究动机**：利用单细胞转录组学（scRNA-seq）的高分辨率特性，识别特定细胞类型（如特定巨噬细胞或成纤维细胞）中的致病通路，从而发现更精准、副作用更小的新一代治疗靶点。
*   **整体含义**：该研究构建了一个整合机器学习（ML）与实验验证的闭环框架，旨在将海量单细胞数据转化为可临床转化的治疗策略。

### 2. 方法论：核心思想与关键技术
该框架主要包含四个核心环节：
*   **统一单细胞图谱构建**：利用 Immunai 的 AMICA DB™ 平台，整合了 20 个公共数据集，通过标准化的管道（10x Cell Ranger、质量过滤、批次校正、细胞本体注释）构建了包含近 100 万个细胞的肠道图谱。
*   **免疫患者表征（IPR）框架**：
    *   **伪批量构建**：按细胞类型聚合样本内的基因表达。
    *   **线性降维**：提取捕捉生物学变异的潜在分量（Latent Components）。
    *   **特征提取**：识别与疾病状态（如发炎 vs 非发炎）、治疗反应（如抗-TNF 响应者 vs 无响应者）显著相关的细胞特异性基因程序（IPR Features）。
*   **AI 辅助推理（AMICA-Reason™）**：利用大语言模型（LLM）驱动的代理框架，结合 GSEA 富集分析和生物医学文献，对复杂的 ML 输出进行结构化生物学解释，将统计信号转化为机械性假设。
*   **靶点优先级排序**：整合 IPR 衍生指标（效应量、炎症关联度）与正交指标（遗传证据、药物可及性、安全性/脱靶风险），对候选基因进行加权评分。

### 3. 实验设计：数据集、场景与对比
*   **数据集**：
    *   **发现集**：来自 20 个研究的 530 个肠道样本（994,206 个细胞）。
    *   **独立验证集**：包含 4 个新近研究的 163 个样本（520,969 个细胞）。
*   **实验场景**：
    *   **计算机模拟（In silico）**：识别了 85 个疾病相关程序和 400 个排名靠前的靶点。
    *   **体外验证（In vitro）**：在原代人类单核吞噬细胞（MNP）和肠道成纤维细胞中进行基因敲除（CRISPR/Cas9）。
*   **Benchmark 与对比**：
    *   **靶点召回率**：对比了已上市及临床 II/III 期在研的 IBD 药物靶点（如 TNF, ITGA4, JAK3 等），验证框架的有效性。
    *   **机制对比**：将新靶点（如 PTGIR）的效应与标准疗法（如 Infliximab/抗-TNF）进行多组学对比，证明其机制的独特性。

### 4. 资源与算力
*   论文中**未明确说明**具体的硬件型号（如 GPU 数量）或训练时长。
*   考虑到处理百万级单细胞数据的规模，通常需要高性能计算集群（HPC）或云端大规模并行计算资源，且使用了复杂的 LLM 代理框架（AMICA-Reason™），涉及大量的 API 调用或本地模型推理。

### 5. 实验数量与充分性
*   **实验规模**：
    *   分析了超过 100 万个细胞，涵盖 129 种细胞亚型。
    *   对 19 个候选靶点进行了功能验证筛选，重点展示了 PTGIR 和 IL6ST。
    *   体外实验涵盖了 6 个健康供体的原代细胞，并进行了 30 多种极化条件的筛选。
*   **充分性与客观性**：实验设计较为充分，引入了独立验证集进行交叉验证，并使用了“临床投影”（Clinical Projection）技术将体外结果映射回患者数据，增强了结论的客观性。

### 6. 主要结论与发现
*   **PTGIR（前列腺素 I2 受体）**：在发炎组织的脂质相关巨噬细胞（LAM）中高表达。敲除 PTGIR 可逆转促炎代谢状态，减少 VEGF-A 和 CCL7 分泌，其机制与抗-TNF 疗法互补。
*   **IL6ST（gp130）**：在成纤维细胞中具有促纤维化作用，但在巨噬细胞中敲除反而会诱发炎症。这强调了**细胞类型特异性给药**的重要性。
*   **框架效能**：该框架成功识别了 50% 的已上市 IBD 药物靶点，并预测了如 IL7R 等处于临床后期的新兴靶点。

### 7. 优点：亮点与创新
*   **高分辨率**：克服了传统遗传学研究缺乏细胞上下文的局限。
*   **数据标准化**：构建了目前规模最大的统一肠道单细胞图谱，消除了不同研究间的批次效应。
*   **AI 增强解释**：引入 LLM 辅助推理，解决了机器学习模型“黑盒”化、难以转化为生物学意义的痛点。
*   **转化导向**：不仅停留在计算预测，还通过原代细胞模型和临床投影验证了靶点的可转化性。

### 8. 不足与局限
*   **体外模型局限性**：尽管进行了计算优化，但单层原代细胞培养仍无法完全模拟复杂的肠道微环境（如微生物群、空间结构）。
*   **样本偏差**：虽然整合了多项研究，但数据仍受限于公共数据集的质量和临床元数据的完整性。
*   **安全性验证**：虽然通过其他组织图谱评估了脱靶风险，但长期的系统性毒性仍需动物实验和临床前研究验证。
*   **给药挑战**：如 IL6ST 的研究显示，同一靶点在不同细胞中作用相反，这对精准靶向递送技术提出了极高要求。

（完）
