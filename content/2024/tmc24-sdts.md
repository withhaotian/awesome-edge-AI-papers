# Startup-aware Dependent Task Scheduling with Bandwidth Constraints in Edge Computing

\[[返回主页](../../README.md)\]

## 作者信息
*Jiong Lou (Shanghai Jiao Tong University), Zhiqing Tang, Weijia Jia (Beijing Normal University), Wei Zhao (CAS Shenzhen Institute of Advanced Technology), Jie Li (Shanghai Jiao Tong University)*

## 研究背景
随着容器化技术的发展，越来越多的轻量化服务部署至网络边缘侧供用户使用。然而，目前针对边缘服务的计算任务间往往具有执行顺序依赖，且任务执行时的冷启动问题带来的高昂时间和带宽开销不可忽视。因此，本文旨在解决依赖任务执行时的冷启动、数据传输与任务调度联合优化问题。

## 主要贡献
本文提出了一种基于表查询的依赖任务调度算法——SDTS。首先，考虑任务加载时延、调度时延与执行时间对最终任务完成时间的影响。进而，设计了一种基于表查询的调度算法，并引入云辅助的依赖配置备份技术，提升带宽与通信资源利用率。