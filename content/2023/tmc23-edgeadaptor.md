# EdgeAdaptor: Online configuration adaption, model selection and resource provisioning for edge DNN inference serving at scale

\[[返回主页](../../README.md)\]

## 作者信息
*Kongyange Zhao, Zhi Zhou, Xu Chen (Sun Yat-sen University), Ruiting Zhou (Wuhan University), Xiaoxi Zhang, Shuai Yu, Di Wu (Sun Yat-sen University)*

## 研究背景
在边缘计算环境中，由于不同应用的请求可以由多个DNN模型提供服务，因此，如何选择最佳模型以及动态提供每个DNN模型的模型实例数量是一个具有挑战性的问题。此外，启动新的模型实例会产生实例切换成本，而销毁空闲的模型实例不一定能提高成本效益。因此，亟需针对在线配置适应、模型选择和资源分配问题进行联合优化。

## 主要贡献
本文提出了一种在线优化框架EdgeAdaptor，实现联合进行配置适应、模型选择和资源分配，以实现成本高效的边缘DNN推理服务。具体而言，通过将该问题建模为混合整数线性规划，并通过正则化方法，松弛整数约束并对长期问题中的时间耦合项进行正则化。进而，将问题分解为一系列单时间隙独立子问题，设计随机化依赖舍入方案求得可行的整数解。