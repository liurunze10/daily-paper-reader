---
title: Single-cell analysis of an adult IBD INCEPTION cohort reveals Galectin-linked disease mechanisms
authors: "Leipner, M., Rimmer, P., Tull, S., Paun, A., Sandrin, V., Begum, J., Mansour, A. A., Saviano, A., Sharma, N., Cheesbrough, J., Maione, F., Trenkle, P., Klein, A., Danilin, S., Iqbal, T. H., Iqbal, A. J., Regan-Komito, D."
date: 2026-07-03
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.30.735473v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: IBD队列单细胞分析及巨噬细胞刺激模型
tldr: 本研究通过对137名初治炎症性肠病（IBD）患者的100万个肠道细胞进行单细胞转录组测序，构建了高分辨率免疫图谱。研究发现炎症单核细胞的扩张是克罗恩病和溃疡性结肠炎的共同特征，并识别出Galectin-9是驱动黏膜炎症的关键信号分子。该研究揭示了Galectin-单核细胞轴在IBD早期发病中的核心作用，为疾病诊断和治疗提供了新的生物标志物和潜在靶点。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在通过分析初治IBD患者的单细胞免疫图谱，揭示疾病发作的早期致病机制和核心驱动因素。
method: 整合了137名受试者的单细胞转录组数据，利用共变邻域分析和细胞通讯张量分解技术，并结合体外实验和血清学验证。
result: 发现炎症单核细胞显著扩张，并识别出以Galectin-9为核心的疾病特异性信号模块，其水平与炎症程度及治疗反应密切相关。
conclusion: Galectin-单核细胞信号轴是早期IBD的统一炎症特征，Galectin-9可作为驱动炎症的功能因子和监测病情的动态生物标志物。
---

## Abstract
Background and Aims: The molecular pathogenesis of Inflammatory Bowel Disease (IBD) remains unclear. We aimed to establish a high-resolution immune landscape of treatment-naive IBD to identify central drivers of disease onset and early pathogenic signalling. Methods: We generated a single-cell atlas using intestinal biopsies from a large adult inception cohort of 137 individuals, including treatment-naive Crohn's disease (CD), ulcerative colitis (UC), and symptomatic non-IBD controls. We integrated scRNA-seq (1 million cells) with co-varying neighbourhood analysis (CNA) and unbiased tensor decomposition of cell-cell communication (CCC) networks. Findings were validated in vitro macrophage stimulation model and using serum from patients. Results: The inception cohort exhibited significantly more homogenous compartmental diversity compared to benchmark reference studies (p < 0.001). Inflammation in both CD and UC was characterized by a marked expansion of inflammatory monocytes. Unbiased CCC analysis identified a dominant disease-specific signalling module centred on the Galectin family (LGALS1 and LGALS9). Galectin-9 expression was specifically enriched in inflammatory monocytes, which exhibited distinct. transcriptional programs linked to antigen presentation and microbial sensing. In vitro, Galectin-9 acted as a potent stimulus, driving macrophages toward a pro-inflammatory phenotype. Clinically, serum Galectin-9 levels were significantly elevated in IBD patients and correlated with systemic inflammatory markers and treatment response. Conclusions: Our data identify a galectin-monocyte signalling axis as a unifying inflammatory hallmark of early IBD. Galectin-9 serves as both a functional driver of mucosal inflammation and a dynamic biomarker, offering new opportunities for therapeutic targeting and disease monitoring from diagnosis. Keywords: Inflammatory Bowel Disease; Crohn's Disease; Ulcerative Colitis; Single-cell RNA sequencing; Galectin-9; Inflammatory monocytes.

---

## 论文详细总结（自动生成）

这是一份关于论文《Single-cell analysis of an adult IBD INCEPTION cohort reveals Galectin-linked disease mechanisms》的结构化深入总结：

### 1. 论文的核心问题与整体含义（研究动机和背景）
*   **核心问题**：炎症性肠病（IBD，包括克罗恩病 CD 和溃疡性结肠炎 UC）的早期致病机制尚不明确。现有的单细胞研究大多针对已接受治疗的患者，药物干预会掩盖疾病初期的原始免疫特征。
*   **整体含义**：本研究通过建立一个大规模的**初治（Treatment-naive）**成人 IBD 队列（INCEPTION 队列），旨在排除药物干扰，识别驱动肠道炎症发生的早期核心细胞群和分子信号通路，为精准诊断和新药研发提供靶点。

### 2. 论文提出的方法论
*   **核心思想**：结合大规模单细胞转录组测序（scRNA-seq）与先进的计算生物学方法，从细胞组成、基因表达和细胞间通讯三个维度解析 IBD 早期病理。
*   **关键技术细节**：
    *   **scRNA-seq 整合**：对 137 名受试者的肠道活检组织进行单细胞测序，捕获约 100 万个细胞。
    *   **共变邻域分析（CNA）**：用于识别在疾病状态下显著扩张或缩减的特定细胞亚群。
    *   **张量分解（Tensor Decomposition）**：对细胞间通讯（CCC）网络进行无监督分析，从复杂的通讯数据中提取出具有生物学意义的“信号模块”。
    *   **功能验证**：通过体外巨噬细胞刺激模型验证候选分子（Galectin-9）的促炎功能。

### 3. 实验设计
*   **数据集/场景**：
    *   **INCEPTION 队列**：包含 137 名成年人，分为初治 CD、初治 UC 和有症状但非 IBD 的对照组。
*   **Benchmark（基准对比）**：
    *   将该队列与已发表的多个 IBD 单细胞参考数据集（如 Smillie et al. 2019）进行对比，评估细胞组成的异质性和同质性。
*   **对比方法**：
    *   跨疾病对比（CD vs UC）。
    *   炎症状态对比（发炎组织 vs 未发炎组织）。
    *   治疗反应对比（对治疗有反应者 vs 无反应者）。

### 4. 资源与算力
*   **算力说明**：论文中**未明确指出**具体的 GPU 型号、数量或训练时长。但考虑到 100 万个细胞的单细胞整合、降维及张量分解运算，该研究通常需要高性能计算集群（HPC）以及大容量内存（通常为 256GB RAM 以上）支持。

### 5. 实验数量与充分性
*   **实验规模**：
    *   **样本量**：137 人，100 万个细胞，是目前最大的初治 IBD 单细胞研究之一。
    *   **计算实验**：进行了 CNA 分析、细胞通讯张量分解、差异基因表达分析等。
    *   **验证实验**：包括体外单核细胞衍生巨噬细胞（MDM）的 Galectin-9 刺激实验，以及对患者血清样本的 ELISA 检测。
*   **充分性**：实验设计非常充分。研究不仅停留在“描述性”的测序层面，还通过计算模型预测了核心因子，并进一步通过体外功能实验和临床血清学数据实现了“计算-实验-临床”的闭环验证。

### 6. 论文的主要结论与发现
*   **炎症单核细胞的扩张**：发现炎症单核细胞（Inflammatory Monocytes）的显著扩张是 CD 和 UC 共同的早期免疫特征。
*   **Galectin 信号轴**：识别出以 Galectin 家族（尤其是 **Galectin-9**）为核心的疾病特异性信号模块。Galectin-9 在炎症单核细胞中高度表达。
*   **功能驱动作用**：体外实验证明 Galectin-9 能直接诱导巨噬细胞向促炎表型转化，分泌大量促炎细胞因子。
*   **临床生物标志物**：血清 Galectin-9 水平与 IBD 患者的系统性炎症指标（如 CRP）高度相关，且能反映患者对治疗的反应情况。

### 7. 优点
*   **队列纯净**：专注于初治患者，最大限度地减少了免疫抑制剂或生物制剂对免疫图谱的干扰。
*   **分析深入**：采用了张量分解等前沿算法，能够从复杂的细胞互动中精准锁定关键的通讯模块，而非仅仅关注单个基因。
*   **临床转化价值高**：发现的 Galectin-9 不仅是病理驱动者，还具有作为无创生物标志物的潜力。

### 8. 不足与局限
*   **空间信息缺失**：虽然进行了单细胞测序，但缺乏空间转录组数据来证实这些细胞在肠道组织中的精确物理位置关系。
*   **上游机制不明**：虽然确定了 Galectin-9 的促炎作用，但究竟是什么因素在疾病初期诱导了 Galectin-9 的异常升高尚需进一步研究。
*   **人群局限性**：研究主要集中在成人队列，其结论是否完全适用于儿童 IBD 患者仍待验证。

（完）
