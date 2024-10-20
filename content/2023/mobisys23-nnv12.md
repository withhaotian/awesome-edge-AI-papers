# [Boosting DNN Cold Inference on Edge Devices](https://doi.org/10.1145/3581791.3596842)

## 作者信息
*Rongjie Yi (State Key Laboratory of Networking and Switching Technology), Ting Cao (Microsoft Research), Ao Zhou, Xiao Ma, Shangguang Wang, Mengwei Xu (State Key Laboratory of Networking and Switching Technology)*

## 研究背景
模型推理过程中的冷推理（Cold Inference）是指在DNN模型未被预热的情况下进行读取、初始化和执行的过程，极大影响端到端的推理响应延迟与服务质量。因此，本文旨在优化边缘设备上深度神经网络（即DNN）的冷推理性能。

## 主要贡献
作者提出了一种在端侧优化冷推理的运行时引擎NNV12。具体而言，NNV12通过为每个DNN操作符选择适当的内核（即操作符实现）、将后转换的权重缓存至磁盘以绕过权重转换，并在不对称处理器上对多个内核进行流水线执行来优化冷推理。此外，设计了一种基于启发式的最优的内核调度计划，进一步优化内核调度性能。

![](../../figs/mobisys23-nnv12.png)