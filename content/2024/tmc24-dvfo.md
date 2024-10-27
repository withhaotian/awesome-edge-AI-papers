# [DVFO: Learning-Based DVFS for Energy-Efficient Edge-Cloud Collaborative Inference](https://ieeexplore.ieee.org/abstract/document/10412103)

\[[返回主页](../../README.md#2024)\]

## 作者信息
*Ziyang Zhang, YangZhao, Changyao Lin, HuanLi, JieLiu(Harbin Institute of Technology)*

## 研究背景
文章试图解决在边缘设备上优化DNN推理能耗和延迟面临的挑战。具体包括包括：1）如何在多计算资源（CPU、GPU和内存）的边缘设备上优化推理能耗与延迟之间的平衡；2）如何在边缘-云协作推理过程中自适应调整特征图传输比例，以减少传输瓶颈对实时性能的影响；3）如何加速深度强化学习策略的学习过程，以应对动态的实时环境。

## 主要贡献
本文提出了一个支持DVFS的边云协同推理框架，通过深度强化学习共同优化DVFS和卸载参数，具体包括：1）多计算资源频率优化-通过策略学习选择合适的CPU、GPU和内存频率组合；2）特征图传输优化-引入空间-通道注意力机制，筛选重要特征留在边缘设备执行，剩余部分压缩至云端完成；3）并行控制机制-采用DQN算法结合并行机制，允许代理在观察环境的同时执行策略推理。

![](../../figs/arxiv24-automated.png)
