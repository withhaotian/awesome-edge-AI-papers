# [Enabling age-aware big data analytics in serverless edge clouds](https://doi.org/10.1109/INFOCOM53939.2023.10228905)

## 作者信息
*Zichuan Xu, Yuexin Fu, Qiufen Xia (Dalian University of Technology), Hao Li (China Coal Research Institute)
*
## 研究背景
为了实现在网络边缘进行大数据的实时分析，揭示有价值的信息。大数据分析开发人员通常面临管理底层云资源的负担，这极大地拖慢了分析开发的速度。目前，服务器无感知计算作为一种新的服务范式，能够释放开发人员管理负担，并实现边缘侧敏捷大数据分析。然而，数据的时效性往往取决于延迟表现，包括等待调度、传输延迟、处理延迟等，如何权衡不同性能指标以实现灵活高效大数据分析是具有挑战性的。

## 主要贡献
该文献提出了一种基于单个查询的数据年龄（Age of Data）感知大数据查询评估的近似算法。首先，该算法考虑了具有容量约束且无预算约束的情况，将问题转化为最小化处理数据分割的最大完成时间调度问题。进而，通过将每个位置划分为一组虚拟地址，以确保满足内存资源容量，并提出了一个近似算法。具体而言，通过将内存容量划分为虚拟地址，使得每个虚拟地址具有内存容量，以实例化一个服务器无感知函数，处理单个数据分割任务。