# [Inference Optimization of Foundation Models on AI Accelerators](https://doi.org/10.1145/3637528.3671465)

## 作者信息
*Youngsuk Park, Kailash Budhathoki, Liangfu Chen, Jonas Kübler, Jiaji Huang, Matthäus Kleindessner, Jun Huan, Volkan Cevher, Yida Wang, George Karypis (AWS AI)*

## 研究背景
强大的基础模型，包括具有Transformer架构的大型语言模型（LLMs），在各个行业引领了生成式人工智能的新纪元。基础模型的出现催生了大量新应用，这些应用涵盖了问答系统、客户服务、图像和视频生成以及代码补全等多个领域。然而，当模型参数数量达到数千亿时，在现实场景中的部署会带来高昂的推理成本和高延迟。因此，业界对使用AI加速器进行成本效益高且快速推理的需求越来越高。该论文深入探讨了关于如何使用AI加速器进行推理优化。

## 主要贡献
首先，该论文概述了基本的Transformer架构和深度学习系统框架，深入探讨用于快速和内存高效的注意力计算的系统优化技术，并讨论这些技术如何在AI加速器上高效实现。进而，描述了快速Transformer推理的关键架构元素。最后，综述了当前各种模型压缩和快速解码策略。

