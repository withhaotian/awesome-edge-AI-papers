# Multi-agent deep reinforcement learning based uav trajectory optimization for differentiated services

\[[返回主页](../../README.md)\]

## 作者信息
*Zhaolong Ning (Chongqing University of Posts and Telecommunications), Yuxuan Yang (The University of Sydney), Xiaojie Wang, Qingyang Song, Lei Guo (Chongqing University of Posts and Telecommunications), Abbas Jamalipour (The University of Sydney)*

## 研究背景
无人机辅助移动边缘计算，可以为地面终端用户提供更高吞吐量的低延迟服务。本文探讨了多无人机辅助的移动边缘计算场景，解决如何优化用户与无人机计算开销的同时，实现地理位置分散下无人机的分布式路径控制。

## 主要贡献
本文提出了一种基于多智能体强化学习的多无人机轨迹优化算法。该算法通过优化无人机的飞行轨迹，同时考虑用户的计算成本和服务偏好，实现了最小化用户计算成本和无人机长期计算成本。通过分析服务供应商之间的相互作用，证明了算法达到纳什均衡的条件和唯一性，从而同时解决用户与无人机两个子优化问题。