# The evolution of distributed systems for graph neural networks and their origin in graph processing and deep learning: A survey

\[[返回主页](../../README.md)\]

## 作者信息
*Jana Vatter (Technical University of Munich), Ruben Mayer (University of Bayreuth), Hans-Arno Jacobsen (University of Toronto)*

## 研究背景
图神经网络是一种深度神经网络架构，适用于处理图结构数据，并将图处理技术与深度学习桥接起来。随着现实世界图数据的规模迅速增长，对于高效和可扩展的GNN训练解决方案的需求日益增加。GNN可以应用于多个领域，包括推荐系统、计算机视觉、自然语言处理、生物学和化学等。然而，目前关于如何设计和优化用于训练大规模GNN的系统的研究仍然不足。尽管已有许多研究提出了GNN系统的设计，但缺乏对这些系统的全面概述、分类和比较。

## 主要贡献
该文献旨在通过总结和分类大规模GNN解决方案中的重要方法和技术，来填补这一空白。首先对大规模GNN训练系统进行了全面的综述和分类。通过分析现有文献，总结了不同的GNN训练方法和技术，特别关注于如何将图处理和深度学习的理念结合起来，以支持大规模图数据的有效处理。此外，试图建立GNN系统、图处理系统和深度学习系统之间的联系，主要集中在如何设计一个能够有效处理大规模图数据的GNN系统，以及如何将图处理和深度学习的方法结合起来以优化这些系统的性能。研究还涉及到分布式计算、内存管理、进程间通信等技术挑战，旨在提高系统的计算效率和扩展能力。