---
title: Comparative single cell analysis of wound and cancer identifies the metabolic dialogues between tumor initiating stem cells and macrophages
title_zh: 伤口与癌症的比较单细胞分析揭示了肿瘤起始干细胞与巨噬细胞之间的代谢对话
authors: "Guo, W., Leon, D., Nicholson, B., Que, J., Miao, Y. P."
date: 2026-04-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.02.716187v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: 巨噬细胞程序和代谢对话的比较分析
tldr: 本研究通过单细胞转录组测序对比了皮肤伤口愈合与皮肤鳞状细胞癌中的巨噬细胞动态，旨在区分伤口相关巨噬细胞（WAMs）与肿瘤相关巨噬细胞（TAMs）的异同。研究发现脂质代谢异常是TAMs的独特特征，并鉴定出SOX2高表达的肿瘤起始干细胞是驱动TAMs代谢重塑的关键因素。这一发现揭示了肿瘤如何劫持修复程序，并为通过干预代谢对话来增强免疫治疗提供了新思路。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-02-716187-v1/fig-001.webp\", \"caption\": \"\", \"page\": 28, \"index\": 1, \"width\": 1750, \"height\": 1716}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-02-716187-v1/fig-002.webp\", \"caption\": \"\", \"page\": 29, \"index\": 2, \"width\": 1830, \"height\": 1079}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-02-716187-v1/fig-003.webp\", \"caption\": \"\", \"page\": 30, \"index\": 3, \"width\": 1912, \"height\": 2035}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-02-716187-v1/fig-004.webp\", \"caption\": \"\", \"page\": 31, \"index\": 4, \"width\": 1901, \"height\": 1996}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-02-716187-v1/fig-005.webp\", \"caption\": \"\", \"page\": 32, \"index\": 5, \"width\": 1849, \"height\": 2555}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-02-716187-v1/fig-006.webp\", \"caption\": \"\", \"page\": 33, \"index\": 6, \"width\": 1908, \"height\": 2087}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-04-02-716187-v1/fig-007.webp\", \"caption\": \"\", \"page\": 34, \"index\": 7, \"width\": 1897, \"height\": 1505}]"
motivation: 探究伤口相关巨噬细胞与肿瘤相关巨噬细胞在分子和功能上的差异，以理解癌症如何利用组织修复机制驱动肿瘤生长。
method: 采用单细胞RNA测序技术对皮肤伤口愈合过程和皮肤鳞状细胞癌进展中的巨噬细胞状态进行动态对比分析。
result: 发现脂质代谢异常是TAMs区别于WAMs的显著特征，且该代谢状态受SOX2高表达的肿瘤起始干细胞调控。
conclusion: 阻断肿瘤起始干细胞与巨噬细胞间的代谢通讯是改善髓系细胞功能并提升癌症免疫治疗效果的潜在策略。
---

## 摘要
巨噬细胞是伤口愈合的关键介导者，然而它们所采用的细胞程序可能被癌症劫持以驱动肿瘤发生。尽管类似的巨噬细胞程序同时支持生理性组织再生和病理性细胞生长，但伤口相关巨噬细胞 (WAMs) 与肿瘤相关巨噬细胞 (TAMs) 之间的分子和功能差异仍不明确。在本研究中，我们通过比较单细胞 RNA 测序，描绘了皮肤伤口愈合和皮肤鳞状细胞癌进展过程中巨噬细胞的动态细胞状态。我们的分析表明，异常调节的脂质代谢是 TAMs 的一个显著特征。关键的是，通过遗传操作，我们确定了 SOX2高表达 (SOX2High) 的肿瘤起始干细胞是调节 TAMs 脂质代谢并塑造其细胞状态的关键协调者。这些发现表明，阻断肿瘤起始干细胞与 TAMs 之间的代谢互作，是使髓系细胞功能恢复正常并增强癌症免疫治疗疗效的一种极具前景的策略。

## Abstract
Macrophages are pivotal mediators of wound healing, yet the cellular programs they employ can be hijacked by cancers to drive tumorigenesis. Although similar macrophage programs support both physiological tissue regeneration and pathological cell growth, the molecular and functional difference between wound-associated macrophages (WAMs) and tumor-associated macrophages (TAMs) remain poorly defined. Here, we perform comparative single-cell RNA sequencing to delineate the dynamic cell states of macrophages during skin wound healing and the progression of cutaneous squamous cell carcinoma. Our analyses reveal that aberrantly regulated lipid metabolism is a distinct feature of TAMs. Critically, our genetic manipulations allow us to identify SOX2High tumor-initiating stem cells as key orchestrators that modulate the lipid metabolism of TAMs and shape their cell states. These findings suggest that disrupting the metabolic crosstalk between tumor-initiating stem cells and TAMs represents a promising strategy to normalize myeloid cell function and enhance cancer immunotherapy efficacy.

---

## 论文详细总结（自动生成）

这是一份关于论文《Comparative single cell analysis of wound and cancer identifies the metabolic dialogues between tumor initiating stem cells and macrophages》的结构化深入总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：癌症常被描述为“永不愈合的伤口”，因为肿瘤会劫持正常的组织修复机制。虽然伤口相关巨噬细胞（WAMs）和肿瘤相关巨噬细胞（TAMs）在促进生长和免疫抑制方面具有相似性，但它们在分子水平上的**本质区别**以及**肿瘤如何特异性重塑巨噬细胞**的机制尚不清楚。
*   **研究背景**：巨噬细胞具有高度可塑性。在伤口中，它们从促炎状态转向促愈合状态以支持干细胞再生；在肿瘤中，它们被慢性重编程以支持肿瘤发生。研究旨在通过对比生理性（伤口）与病理性（癌症）过程，寻找癌症特异性的治疗靶点。

### 2. 方法论：核心思想与关键技术
*   **核心思想**：利用单细胞转录组测序（scRNA-seq）对比分析同一组织（皮肤）在伤口愈合不同阶段与癌症进展不同阶段的免疫微环境。
*   **关键技术细节**：
    *   **模型选择**：采用小鼠“部分厚度伤口”模型（模拟上皮再生）和DMBA/TPA诱导的自发性皮肤鳞状细胞癌（SCC）模型。
    *   **单细胞技术**：使用基于拆分-池组合条形码（Split-pool combinatorial barcoding）的 Parse Biosciences Evercode 技术，有效降低批次效应。
    *   **遗传操作**：构建了 `K14CreER; R26-LSL-Sox2-IRES-GFP`（Sox2 异位表达）和 `K14CreER; Sox2 flox/flox`（Sox2 条件敲除）模型，以验证肿瘤起始干细胞（tSCs）中 SOX2 蛋白对巨噬细胞的调控作用。
    *   **生物信息学分析**：应用 Seurat 进行聚类、SingleR 进行细胞注释、scVelo 进行 RNA 速率分析（推断细胞分化轨迹）以及伪体（Pseudo-bulk）差异表达分析。

### 3. 实验设计与 Benchmark
*   **数据集/场景**：
    *   **伤口组**：第2天（炎症期）和第4天（愈合期）的 CD45+ 免疫细胞。
    *   **癌症组**：良性乳头状瘤（Papilloma）和恶性癌（SCC）阶段。
    *   **干预组**：Sox2 过表达伤口、Sox2 敲除肿瘤、以及接受 anti-PDL1 + CD40 激动剂免疫治疗后的肿瘤。
*   **对比方法**：
    *   横向对比 WAMs 与 TAMs 的转录组特征。
    *   纵向对比癌症进展过程中巨噬细胞状态的演变。
    *   对比免疫治疗敏感与耐药状态下巨噬细胞的组成。

### 4. 资源与算力
*   **算力说明**：论文中**未明确说明**具体的 GPU 型号、数量或训练时长。
*   **数据规模**：最终筛选并分析了 18,456 个高质量免疫细胞。

### 5. 实验数量与充分性
*   **实验规模**：
    *   每个实验组均包含两个生物学重复，每个重复由多只小鼠或多个肿瘤样本混合而成。
    *   涵盖了从生理损伤到恶性肿瘤的完整生物学谱系。
    *   包含了增益性（过表达）和缺失性（敲除）功能实验。
*   **充分性评价**：实验设计非常充分且逻辑严密。通过在正常伤口中异位表达 SOX2 成功模拟了 TAM 样特征，这一“逆向验证”极大地增强了结论的说服力。实验过程考虑了批次效应控制，分析方法符合当前单细胞研究的主流标准。

### 6. 主要结论与发现
*   **脂质代谢是核心差异**：虽然 WAMs 和 TAMs 都表现出 M2 样特征，但 **“异常脂质代谢”** 是 TAMs 的独特标志（涉及 *ApoE, Cd36, Trem2, Pparg, Acss1/2* 等基因的高表达）。
*   **SOX2 的驱动作用**：SOX2 高表达的肿瘤起始干细胞（tSCs）是诱导巨噬细胞进入这种“脂质充盈”状态的关键。在伤口中激活 SOX2 会使 WAMs 转向 TAM 样状态；在肿瘤中敲除 SOX2 则会削弱这种代谢重塑。
*   **免疫治疗耐药机制**：在免疫治疗下，普通的促肿瘤巨噬细胞会被清除，但受 SOX2 调控的脂质代谢型 TAMs 能够持续存在，为 tSCs 提供保护生态位，导致肿瘤复发。

### 7. 优点与亮点
*   **模型独特性**：使用部分厚度伤口模型，使其与皮肤 SCC 的起源细胞（角质形成干细胞）高度一致，实现了真正意义上的“同源对比”。
*   **机制深入**：不仅停留在描述现象，还通过遗传模型锁定了 SOX2 这一关键转录因子作为跨细胞通讯的“指挥官”。
*   **临床相关性**：揭示了为什么某些巨噬细胞亚群在免疫治疗后依然存在，为开发针对脂质代谢路径的联合免疫疗法提供了理论依据。

### 8. 不足与局限
*   **代谢物身份未明**：虽然确定了 SOX2 调控了脂质代谢程序，但具体是哪种脂质分子或脂肪酸介导了 tSCs 与巨噬细胞之间的对话尚不清楚。
*   **空间信息缺失**：研究主要基于解离后的单细胞测序，虽然引用了前人关于空间分布的结论，但本研究本身缺乏空间转录组数据来直接观察这种“代谢对话”发生的物理位置。
*   **物种局限**：研究完全基于小鼠模型，虽然皮肤 SCC 模型具有代表性，但仍需在人类临床样本中进一步验证 SOX2-TAM 代谢轴的普遍性。

（完）
