## Graph Data

1. Strengths into Weaknesses: A Certified Robustness Inspired Attack Framework against Graph Neural Networks

   https://arxiv.org/abs/2303.06199

   基于随机平滑分别得出节点针对图规避和中毒攻击的认证扰动大小，提高现有基础攻击的性能

2. REVISITING ROBUSTNESS IN GRAPH MACHINE LEARNING

   https://arxiv.org/abs/2305.00851

   节点分类，对抗小幅结构扰动时的鲁棒性问题，引入CSBMs，得出当前扰动模型包含大量违反语义不变假设的扰动图，即表现出超出语义变化点的鲁棒性，将训练图的标签结构纳入GNN的推理过程中，减少这种“超鲁棒性”

3. GNNCERT_ DETERMINISTIC CERTIFICATION OF GRAPH NEURAL NETWORKS AGAINST ADVERSARIAL PERTURBATIONS

   https://openreview.net/pdf?id=IGzaH538fz

   图分类，使用哈希函数分割子图，投票，建立集成图分类器，理论证明方法在节点扰动的有效性，实验证明方法在结构扰动的有效性。展望：将节点的自我网络视为一张图，将方法扩展至节点分类

4. Graph Contrastive Backdoor Attacks

   https://proceedings.mlr.press/v202/zhang23e/zhang23e.pdf

   针对GCL的后门攻击，针对图对比学习的不同阶段设计poisoning,crafting,natural backdoor，提出一种基于凸松弛的离散优化方法

5. Self-Guided Robust Graph Structure Refinement

   https://arxiv.org/pdf/2402.11837v2.pdf

   节点分类，通过新的图精炼方法识别可能增加或删除的边以减轻对抗攻击。对提取的干净子图提出了新的图增强策略和分组训练策略。

6. ROBUST ANGULAR SYNCHRONIZATION VIA DIRECTED GRAPH NEURAL NETWORKS

   https://arxiv.org/pdf/2402.13769.pdf

   解决angular synchronization（角度同步问题），提高鲁棒性。展望：有向图的节点分类

7. Local-Global Defense against Unsupervised Adversarial Attacks on Graphs

   https://dl.acm.org/doi/abs/10.1609/aaai.v37i7.25979

   无监督，提出一种扰动边缘危害性区分受攻击的边是否敏感，量化受攻击的边是否有害，从局部和整体提高表示的鲁棒性

8. REVISITING GRAPH ADVERSARIAL ATTACK AND DEFENSE FROM A DATA DISTRIBUTION PERSPECTIVE

   https://openreview.net/pdf?id=dSYoPjM5J_W

   节点分类，量化训练数据和测试数据之间的不一致性，提出有效的对抗攻击在于增加数据的分布偏移，回答了为何基于梯度的攻击方法倾向于增加而非删除边，基于梯度的方法由于基于同质性的方法

9. Transferable Structure-based Adversarial Attack of Heterogeneous Graph Neural Network

   https://dl.acm.org/doi/pdf/10.1145/3583780.3615095

   节点分类，基于结构针对异构图的攻击方法，利用边缘注意力分布的相似性来指导对抗扰动，优先扰动在不同模型中被关注的边，主要探讨图对抗样本的可转移性

10. Guard: Graph Universal Adversarial Defense

    https://arxiv.org/pdf/2204.09803.pdf

    为每个节点生成一个通用的二进制向量，提高GCN鲁棒性

11. Adversarial Training for Graph Neural Networks: Pitfalls, Solutions, and New Directions

    https://arxiv.org/pdf/2306.15427.pdf

    节点分类，对抗训练，在训练图中排除测试和验证节点，基于扩散系数的消息传递方案以选择最鲁棒的滤波器达到竞争性的训练损失

12. Adversarial Robustness in Graph Neural Networks: AHamiltonian Approach

    https://arxiv.org/pdf/2310.06396.pdf

    汉密尔顿系统，根据能量守恒，每个节点的特征由位置和动量组成，可学习的能量函数，模型在节点特征的演化过程中保持能量不变

13. Provable Adversarial Robustness for Group Equivariant Tasks: Graphs, Point Clouds, Molecules, and More

    https://arxiv.org/pdf/2312.02708.pdf

    提出一种考虑任务等变性的对抗鲁棒性定义，针对图同构等变任务的图编辑距离证书，提供理论鲁棒性保证

14. Similarity Preserving Adversarial Graph Contrastive Learning

    https://arxiv.org/pdf/2306.13854v1.pdf

    引入一个相似性保持视图和一个对抗视图，分别保证节点特征之间的相似性和学习在对抗性扰动情况下仍保持稳定的节点表示

15. Temporal Dynamics-Aware Adversarial Attacks on Discrete-Time Dynamic Graph Models

    https://dl.acm.org/doi/pdf/10.1145/3580305.3599517

    动态图的节点分类和动态链接预测，一种针对时间动态图模型的时间动态感知约束，在每个时间步引入扰动；一种基于投影梯度下降的方法，在约束下找到有效的扰动

16. Enhancing Node-Level Adversarial Defenses by Lipschitz Regularization of Graph Neural Networks

    https://dl.acm.org/doi/pdf/10.1145/3580305.3599335

    鲁棒性，定义一个莱布希思矩阵，估计每层的莱布希思界作为正则参数优化模型，减少对扰动输入的敏感性

17. Towards Inductive Robustness: Distilling and Fostering Wave-induced Resonance in Transductive GCNs Against Graph Adversarial Attacks

    https://arxiv.org/pdf/2312.08651.pdf

    将GCN增加到三层可赋予模型一种可提炼的鲁棒性，利用GCN消息传递中的自然振动与边的拉普拉斯波动方程等价，提出一种图共振增强网络

    

​       

