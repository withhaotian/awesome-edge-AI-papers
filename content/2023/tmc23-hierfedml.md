# [HierFedML: aggregator placement and UE assignment for hierarchical federated learning in mobile edge computing](https://doi.org/10.1109/TPDS.2022.3218807)

\[[返回主页](https://github.com/withhaotian/awesome-edge-AI-papers.git)\]

## 作者信息
*Zichuan Xu, Dapeng Zhao (Dalian University of Technology), Weifa Liang (City University of Hong Kong), Omer F. Rana (Cardiff University), Pan Zhou (Huazhong University of Science and Technology), Mingchu Li (Dalian University of Technology), Wenzheng Xu (Sichuan University), Hao Li (China Coal Research Institute), Qiufen Xia (Dalian University of Technology)*

## 研究背景
传统联邦学习（Federated Learning，FL）通过单个参数服务器聚合模型，面临效率与可扩展性问题。因此，本文主要针对移动边缘计算（MEC）网络中，针对混合联邦学习（即基于Master-Workers架构的联邦学习）的资源分配问题。

## 主要贡献
本文提出了一种在线资源优化框架HierFedML。具体而言，该框架包括三个模块：优化器、控制器和监视器。1）优化器实现了混合联邦学习算法，根据请求的输入返回包括用户设备数量、训练数据集、聚合数量和聚合位置等配置；2）控制器将算法生成的配置解析为训练计划；3）进而，监听器基于FedML提供的接口监控层次化训练过程，并提供当前过程所需的参数等状态。