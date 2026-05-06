---
title: Membrane contact site resident PTP1B limits superoxide production by suppressing a Syk-Shc1-Phagocyte Oxidase relay.
authors: "Lee, M., Zein, H. S., Ghavami, M., Wei, K., Lokhandwala, M., Wybenga-Groot, L., Moran, M. F., Fairn, G. D."
date: 2026-04-30
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.17.711902v2.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: PTP1B 在吞噬过程中限制巨噬细胞产生超氧化物
tldr: 本研究揭示了内质网驻留磷酸酶PTP1B在吞噬作用中的关键调节机制。研究发现，在Fcγ受体介导的吞噬过程中，肌动蛋白清除促使内质网-质膜接触位点形成，PTP1B借此通过去磷酸化Syk蛋白，抑制SFK-Syk-Shc1-NOX2信号轴，从而限制超氧化物的过度产生，为理解免疫细胞的抗菌反应提供了新视角。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究内质网-质膜接触位点在吞噬过程中如何通过磷酸酶PTP1B调节信号转导及抗菌活性。
method: 利用全内反射荧光显微镜、蛋白质组学和邻位连接技术，观察PTP1B在吞噬杯中的定位及其与Syk、Shc1的相互作用。
result: 缺失PTP1B会导致Syk持续高磷酸化，并通过Shc1接头蛋白使NOX2介导的超氧化物产量增加约3倍。
conclusion: PTP1B在膜接触位点负向调节SFK-Syk-Shc1-NOX2轴，是控制吞噬过程中活性氧产生的关键开关。
---

## Abstract
Phagocytosis is a specialized endocytic process used by macrophages and dendritic cells to engulf particles, which requires coordinated signaling cascades, cytoskeletal remodeling, and assembly of antimicrobial machinery to eliminate pathogens. During Fc {gamma} receptor (Fc{gamma}R)-mediated phagocytosis, dynamic actin depolymerization at the base of the phagocytic cup creates permissive conditions for endoplasmic reticulum-plasma membrane (ER-PM) membrane contact sites (MCS) to form. We demonstrate that the ER-resident protein tyrosine phosphatase PTP1B localizes to newly formed or expanded ER-PM MCS during phagocytosis and dephosphorylates Syk. Using TIRF microscopy with MCS residents, including MAPPER, STIM1, and E-Syts, we show that actin clearance allows ER proteins to approach the plasma membrane. PTP1B colocalizes with Fc{gamma}Rs in actin-cleared zones and physically interacts with Syk, a critical mediator of phagocytic signaling. Loss of PTP1B led to sustained Syk hyperphosphorylation without affecting phagocytosis. However, the PTP1B-deficient cells showed a {asymp}3-fold increase in NADPH oxidase 2 (NOX2)-mediated superoxide production. Using unbiased proteomics, we identified the adapter protein Shc1 as a critical intermediate linking Syk phosphorylation to NOX2 activation. Shc1 phosphorylation during phagocytosis is dependent on Src family kinases and Syk, while genetic ablation of SHC1 reduced superoxide production by {asymp}40%. Proximity ligation assays reveal enhanced Shc1-p47phox interactions in PTP1B-deficient cells during phagocytosis. These findings establish an SFK-Syk-Shc1-NOX2 signaling axis that PTP1B negatively regulates at MCS between the ER and the forming phagosome, providing new mechanistic insights into antimicrobial responses during phagocytosis.

---

## 论文详细总结（自动生成）

这篇论文深入探讨了内质网（ER）驻留蛋白酪氨酸磷酸酶 PTP1B 在巨噬细胞吞噬过程中的空间定位及其对抗菌反应（超氧化物产生）的调节机制。以下是对该论文的结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：在 Fcγ 受体（FcγR）介导的吞噬过程中，内质网-质膜接触位点（ER-PM MCS）如何形成，以及驻留在这些位点的磷酸酶 PTP1B 如何调节下游信号转导。
*   **背景**：吞噬作用不仅涉及颗粒的摄取，还涉及活性氧（ROS）如超氧化物的产生以杀灭病原体。已知吞噬杯底部的肌动蛋白（actin）会发生清除，但这如何影响 ER 与质膜的相互作用，以及这种空间重组如何调控信号级联（如 Syk 激酶通路），此前尚不完全清楚。

### 2. 论文提出的方法论
*   **核心思想**：通过肌动蛋白动态重塑促使 ER-PM MCS 形成，使 ER 上的 PTP1B 能够物理接近并去磷酸化质膜相关的 Syk 激酶，从而负向调节 NOX2 氧化酶的激活。
*   **关键技术细节**：
    *   **成像技术**：利用全内反射荧光显微镜（TIRF）和受挫吞噬（Frustrated Phagocytosis）模型观察细胞腹侧表面。使用 SPLICS 传感器（基于拆分 YFP）检测 10-40nm 范围内的膜接触。
    *   **遗传干预**：利用 CRISPR-Cas9 技术在 RAW264.7 巨噬细胞中敲除 *Ptpn1* (PTP1B) 和 *Shc1* 基因。
    *   **蛋白质组学**：采用“超级结合器”（Superbinder）SH2 结构域富集磷酸化酪氨酸（pY）肽段，结合质谱（LC-MS/MS）进行无偏见磷酸化蛋白筛选。
    *   **生化分析**：通过免疫共沉淀（Co-IP）和邻位连接实验（PLA）验证蛋白间的物理接近性和相互作用。

### 3. 实验设计
*   **场景与模型**：主要使用 RAW264.7 巨噬细胞系；对比野生型（WT）与 PTP1B 敲除（KO）及 Shc1 KO 细胞。
*   **刺激物（Benchmark）**：IgG 调理的酵母聚糖（Zymosan）、调理的羊红细胞（sRBC）和热聚合 IgG（AgIgG）。
*   **对比方法**：
    *   观察不同 MCS 标记物（MAPPER, STIM1, E-Syts）在肌动蛋白清除区的聚集。
    *   测量 PTP1B 缺失对 Syk 磷酸化动力学的影响。
    *   定量分析超氧化物产量（NBT 还原实验及分光光度法）。
    *   评估吞噬效率（乳胶颗粒摄取实验）。

### 4. 资源与算力
*   **说明**：论文未明确提及具体的 GPU 算力或大规模计算资源。实验核心依赖于高分辨率显微镜成像系统（Quorum 旋转磁盘显微镜）和高精度质谱仪（Orbitrap Fusion Lumos）。数据分析主要使用 MetaMorph、ImageJ/FIJI 和 GraphPad Prism。

### 5. 实验数量与充分性
*   **实验规模**：研究包含了多组独立的生物学重复（通常 n=3 或 n=4）。
*   **充分性**：
    *   针对 PTP1B 和 Shc1 均使用了 3 个不同的敲除克隆，有效排除了克隆变异带来的偏差。
    *   结合了药理学抑制（SFK 和 Syk 抑制剂）与遗传学手段，互为印证。
    *   蛋白质组学数据提供了全局视角，随后通过生化实验进行了针对性验证。
    *   实验设计客观，对照组设置严谨，逻辑链条从空间定位到分子相互作用再到生物学功能非常完整。

### 6. 主要结论与发现
*   **MCS 形成机制**：吞噬杯底部的皮层肌动蛋白解聚是 ER-PM MCS 扩展的先决条件。
*   **PTP1B 的作用**：PTP1B 在 MCS 处通过其催化结构域与 Syk 结合并对其去磷酸化。
*   **表型发现**：缺失 PTP1B 不影响颗粒的物理摄取，但会导致 Syk 持续高磷酸化，使超氧化物产量显著增加（约 3 倍）。
*   **信号轴确立**：通过蛋白质组学鉴定出接头蛋白 Shc1 是关键中间体。确立了 **SFK-Syk-Shc1-NOX2** 信号轴，PTP1B 通过在该轴的 Syk 环节“刹车”来限制 ROS 产生。

### 7. 优点
*   **空间生物学视角**：将膜接触位点（MCS）这一细胞生物学热点与经典的免疫信号转导相结合，解释了信号调控的空间特异性。
*   **发现新机制**：首次证明了 Shc1 在巨噬细胞 FcγR 信号中连接激酶与氧化酶的作用。
*   **技术综合性强**：结合了活细胞动态成像、无偏见组学筛选和精准遗传编辑。

### 8. 不足与局限
*   **细胞模型单一**：大部分实验在 RAW264.7 细胞系中完成，虽然该细胞系是经典模型，但在原代巨噬细胞或人类细胞中的普适性仍需进一步验证。
*   **物种/受体特异性**：作者提到 PTP1B 在不同研究中对吞噬效率的影响存在差异，暗示其功能可能取决于具体的受体类型或细胞微环境。
*   **分子细节**：虽然证明了 Shc1 与 p47phox 的接近性，但 Shc1 如何具体诱导 NOX2 组分装配的生化细节（如构象改变）仍有待深入研究。

（完）
