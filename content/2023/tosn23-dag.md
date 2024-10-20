# [DAG Scheduling in Mobile Edge Computing](https://doi.org/10.1145/3616374)

\[[返回主页](https://github.com/withhaotian/awesome-edge-AI-papers.git)\]

## 作者信息
*Guopeng Li, Haisheng Tan, Liuyan Liu, Hao Zhou (University of Science and Technology of China), Shaofeng H.-C. Jiang (Peking University), Zhenhua Han (Microsoft Research Asia), Xiang-Yang Li, Guoliang Chen (University of Science and Technology of China)*

## 研究背景
边缘智能应用日益复杂化。例如，视频分析应用包含了视频追踪、视频编码、帧分解、解码等任务，且上述过程存在一定的依赖关系。为了更高效地执行边缘应用，通常将应用的执行抽象为DAG模型，并将任务的计算映射为图节点的有序执行。然而，边缘服务器的有限资源能力使得在异构边缘环境下执行DAG任务，仍在存在技术挑战。

## 主要贡献
基于三种DAG任务执行方式，作者设计了三种针对性的解决方案。具体而言，1）针对传统固定服务器配置的DAG任务而言，提出了一种基于动态规划的静态DAG调度算法FixDoc；2）从边缘服务器可配置的角度，考虑了一种支持任务复用与重放置的按需调度方案GenDoc；3）面向在线动态请求任务，基于查表法构建任务优先级列表，并给出了一种在线调度算法OnDoc。