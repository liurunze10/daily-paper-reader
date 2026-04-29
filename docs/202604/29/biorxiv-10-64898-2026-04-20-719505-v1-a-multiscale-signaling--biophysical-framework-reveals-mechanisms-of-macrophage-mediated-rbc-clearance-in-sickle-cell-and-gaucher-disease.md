---
title: A Multiscale Signaling--Biophysical Framework Reveals Mechanisms of Macrophage-Mediated RBC Clearance in Sickle Cell and Gaucher Disease
title_zh: 一个多尺度信号-生物物理框架揭示了镰状细胞病和戈谢病中巨噬细胞介导的红细胞清除机制
authors: "Chai, Z., Ahmadi Daryakenari, N., Karniadakis, G. E."
date: 2026-04-22
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.20.719505v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 巨噬细胞介导的清除机制和信号动力学
tldr: 本研究针对镰状细胞病（SCD）和戈谢病（GD）中红细胞（RBC）异常清除的问题，开发了一个整合信号动力学、生物物理模拟和机器学习的多尺度混合建模框架。通过耦合耗散粒子动力学（DPD）与物理信息神经网络（PINNs），揭示了巨噬细胞与红细胞相互作用中的分子扩散与膜接触机制。研究发现CD47-SIRP-SHP1抑制轴的减弱是导致异常吞噬的关键，为理解免疫清除机制及开发针对性疗法提供了定量预测平台。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在探究镰状细胞病和戈谢病中，红细胞物理特性改变如何通过生化信号通路导致巨噬细胞异常吞噬。
method: 结合了耗散粒子动力学模拟、系统生物学信号模型以及物理信息神经网络（PINNs/PIKANs）进行多尺度建模与参数推断。
result: 模拟揭示了SCD和GD中CD47-SIRP抑制信号的减弱，并验证了抗SIRP抗体在调节吞噬结果中的治疗潜力。
conclusion: 该多尺度框架为研究免疫清除提供了强有力的计算工具，有助于指导针对红细胞-巨噬细胞相互作用的治疗策略。
---

## 摘要
巨噬细胞对红细胞（RBC）的清除维持着血液稳态，但在溶血性疾病镰状细胞病（SCD）和溶酶体贮积症戈谢病（GD）中，这一过程会发生失调，其生物物理和生化改变促进了红细胞的过早吞噬。我们开发了一个整合了信号动力学、生物物理模拟和机器学习的多尺度混合建模框架，以研究这些疾病中控制红细胞吞噬的机制。我们的方法将巨噬细胞-红细胞信号传导的系统生物学模型与分子扩散和膜相互作用的耗散粒子动力学（DPD）模拟相结合，并利用物理信息神经网络（PINNs）进行稳健的参数推断。DPD框架为巨噬细胞-红细胞接触过程中的抗体扩散、受体结合和膜级相互作用提供了机械性见解，生成了CD47-SIRP信号传导和抗体-受体结合的空间分辨轨迹，这些轨迹作为约束信号模型的中间观测值。该模型准确捕捉了健康红细胞与改变后的红细胞之间差异化的吞噬反应，揭示了SCD和GD中抑制性信号的减弱以及SHP1介导通路的改变。结合费舍尔信息矩阵诊断和剖面似然的可辨识性分析证实，控制CD47-SIRP-SHP1轴的参数是最稳健可恢复的，而抗SIRP抗体治疗干预的模拟展示了对吞噬结果的调节。我们进一步采用物理信息柯尔莫哥洛夫-阿诺德网络（PIKANs）作为标准PINNs的替代方案，证明了在噪声和采样变异性下改进的稳健性。更广泛地说，我们将生物物理模拟与系统级推断相结合的多尺度平台具有通用性，为涉及吞噬失调的疾病提供了机械性见解和治疗探索的计算工具。意义声明：红细胞通常由巨噬细胞通过严格调节的分子信号从循环中清除。在镰状细胞病和戈谢病等疾病中，这一清除过程变得异常，导致贫血和其他并发症。然而，将红细胞的物理特性与免疫信号联系起来的机制仍不清楚。在这里，我们开发了一个结合了基于粒子的生物物理模拟、系统生物学模型和物理信息机器学习的多尺度计算框架。该方法提供了一个定量框架，用于解释红细胞力学和表面信号的变化如何破坏通常防止吞噬作用的CD47-SIRP抑制通路。该框架为研究免疫清除提供了一个预测平台，并可能有助于指导针对红细胞-巨噬细胞相互作用的治疗策略。

## Abstract
Red blood cell (RBC) clearance by macrophages maintains blood homeostasis and is dysregulated in the hemolytic disorder sickle cell disease (SCD) and the lysosomal storage disorder Gaucher disease (GD), where biophysical and biochemical alterations promote premature phagocytosis. We develop a multiscale hybrid modeling framework integrating signaling dynamics, biophysical simulations, and machine learning to investigate the mechanisms governing RBC phagocytosis in these diseases. Our approach couples a systems biology model of macrophage-RBC signaling with Dissipative Particle Dynamics (DPD) simulations of molecular diffusion and membrane interactions, and leverages Physics-Informed Neural Networks (PINNs) for robust parameter inference. The DPD framework provides mechanistic insight into antibody diffusion, receptor engagement, and membrane-level interactions during macrophage-RBC contact, generating spatially resolved trajectories of CD47-SIRP signaling and antibody-receptor binding that serve as intermediate observables constraining the signaling model. The model accurately captures differential phagocytic responses between healthy and altered RBCs, revealing diminished inhibitory signaling and changes in SHP1-mediated pathways in both SCD and GD. Identifiability analysis combining Fisher Information Matrix diagnostics and profile likelihood confirms that parameters governing the CD47-SIRP-SHP1 axis are among the most robustly recoverable, and simulations of therapeutic perturbations with anti-SIRP antibodies demonstrate modulation of engulfment outcomes. We further employ Physics-Informed Kolmogorov-Arnold Networks (PIKANs) as an alternative to standard PINNs, demonstrating improved robustness under noise and sampling variability. More broadly, our multiscale platform linking biophysical simulation with systems-level inference is generalizable, offering mechanistic insights and computational tools for therapeutic exploration in diseases involving dysregulated phagocytosis.

Significance statementRed blood cells are normally removed from circulation by macrophages through tightly regulated molecular signals. In diseases such as sickle cell disease and Gaucher disease, this clearance process becomes abnormal, contributing to anemia and other complications. However, the mechanisms linking the physical properties of red blood cells to immune signaling remain poorly understood. Here we develop a multiscale computational framework that combines particle-based biophysical simulations, systems biology models, and physics-informed machine learning. This approach provides a quantitative framework to interpret how changes in red blood cell mechanics and surface signaling disrupt the CD47-SIRP inhibitory pathway that normally prevents phagocytosis. The framework provides a predictive platform for studying immune clearance and may help guide therapeutic strategies targeting red blood cell-macrophage interactions.