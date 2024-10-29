# [Dependent function embedding for distributed serverless edge computing](https://doi.org/10.1109/TPDS.2021.3137380)

\[[返回主页](../../README.md)\]

## 作者信息
*Shuiguang Deng, Hailiang Zhao (Zhejiang University), Zhengzhe Xiang (Zhejiang University City College), Cheng Zhang  (Zhejiang University), Rong Jiang (Yunnan University of Finance and Economics), Ying Li, Jianwei Yin  (Zhejiang University), Schahram Dustdar (Technische Universitat Wien), Albert Y. Zomaya (University of Sydney)*

## 研究背景
容器化技术的蓬勃发展为无服务器计算（Serverless Computing）提供了一种高效的服务范式。将基础设施和代码分离来简化开发过程，函数即服务（Function-as-a-Service，FaaS）实现了云/边缘服务的快速部署与低成本管理。一般而言，应用通常可以建模为有向无环图（DAG），其中每一个图节点可视为一个函数或任务。因此，如何考虑具有依赖关系的函数执行，实现高效的DAG计算调度，最终降低服务响应延迟，是目前边缘无服务器计算（Edge Serverless Computing）亟待解决的一个关键问题。

## 主要贡献
该文章首先将DAG调度问题定义为一种具有依赖性的函数嵌入问题，并构建混合优化问题。该问题被证明是NP-Hard，为了求解该问题：1）首先，作者将原问题拆分为两个子问题，即函数放置问题与数据切分映射问题；2）通过求解无穷范数最小化问题，得到最优数据路由与切分方案；3）设计一种基于动态规划的依赖函数嵌入算法（DPE），并通过数学证明算法的理论上界。