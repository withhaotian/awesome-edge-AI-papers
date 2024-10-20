# [Accelerating the Decentralized Federated Learning via Manipulating Edges](https://doi.org/10.1145/3589334.3645509)

\[[返回主页](https://github.com/withhaotian/awesome-edge-AI-papers.git)\]

## 作者信息
*Mingyang Zhou, Gang Liu, KeZhong Lu, Rui Mao, Hao Liao (Shenzhen University)*

## 研究背景
随着数据隐私和安全性的重要性日益增加，分布式联邦学习（DFL）允许多个参与者在不共享原始数据的情况下共同训练模型。然而，DFL在实际应用中常常面临收敛速度慢的问题，这在大型图网络中，尤其是社交网络和移动电话网络等尤为明显。该论文主要解决了如何通过优化通信图的拓扑结构来加速DFL的收敛速度。

## 主要贡献
该论文通过优化DFL中的通信图结构，以加速其收敛速度。具体而言，引入有限数量的边来增强点对点图的连接性。首先，通过增加新的边和去除冗余的边来优化通信图。边操作旨在提高图的第二小特征值，从而加速收敛过程。具体而言，量化新边的添加对特征值的影响，进而有效地选择最优的边集，优化DFL的训练性能。
