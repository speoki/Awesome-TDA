# Awesome TDA 中文文档

> 拓扑数据分析（Topological Data Analysis, TDA）资源精选列表

拓扑数据分析是一种利用拓扑学和几何学方法从数据中提取有意义信息的数学框架。TDA提供了一种强大的工具来理解数据的形状、结构和模式。

## 📚 文档导航

### 核心资源

- [软件包与库](01_软件包.md) - TDA软件包、库和工具
- [持久性方法](02_持久性变体.md) - 各种持久同调变体和方法
- [可视化工具](03_可视化.md) - TDA可视化工具和技术

### 应用领域

- [图与网络分析](04_图网络分析.md) - 图和网络的TDA方法
- [数据集与应用](05_数据集应用.md) - TDA数据集和应用案例
- [数学工具](06_数学工具.md) - TDA的数学基础和工具

### 学习资源

- [教程与论文](07_教程论文.md) - 学习资源、教程和关键论文

## 🚀 快速开始

### 什么是TDA？

拓扑数据分析（TDA）使用代数拓扑（特别是持久同调）的方法来分析数据。主要优势包括：

- **形状分析**: 揭示数据的几何和拓扑结构
- **多尺度**: 在不同尺度上捕捉特征
- **坐标无关**: 对坐标变换保持不变
- **噪声鲁棒**: 对数据中的噪声具有鲁棒性

### 主要概念

- **持久同调 (Persistent Homology)**: 追踪数据在不同尺度上的拓扑特征（连通分量、环、空腔等）
- **持久图 (Persistence Diagram)**: 可视化持久同调结果的主要工具
- **过滤 (Filtration)**: 构建多尺度简单复形序列
- **Mapper算法**: 用于数据可视化和探索性分析

### 常用软件包

| 软件包 | 语言 | 特点 |
|--------|------|------|
| [giotto-tda](https://github.com/giotto-ai/giotto-tda) | Python | 机器学习集成 |
| [GUDHI](https://gudhi.inria.fr/) | C++/Python | 综合性TDA库 |
| [Ripser](https://github.com/Ripser/ripser) | C++ | 高效持久同调计算 |
| [scikit-tda](https://scikit-tda.org/) | Python | Python生态系统 |

## 🌟 特色项目

### 持久拉普拉斯算子
将持久同调与谱方法结合，提供更丰富的拓扑-几何信息
- [Persistent Laplacian](https://github.com/ndag/Persistent-Laplacian)
- [HERMES](https://github.com/wangru25/HERMES)

### 有向图持久性
专门用于有向网络和图的TDA方法
- [pyflagser](https://github.com/giotto-ai/pyflagser)
- [Path Homology](https://github.com/max-nekrashevich/path-homology-toolkit)

### 多参数持久性
处理具有多个过滤参数的复杂数据
- [RIVET](https://github.com/aj-alonso/rivet)
- [multipers](https://github.com/conda-forge/multipers-feedstock)

## 📖 学习路径

### 初学者
1. 阅读基础教程和介绍性论文
2. 安装和试用scikit-tda或giotto-tda
3. 在简单数据集上实验持久同调
4. 学习如何解释持久图

### 中级
1. 探索不同的过滤方法（Rips, Čech, Alpha）
2. 学习Mapper算法
3. 将TDA应用于实际数据集
4. 理解统计方法和机器学习集成

### 高级
1. 研究多参数持久性
2. 探索持久拉普拉斯算子和谱方法
3. 开发新的TDA应用
4. 贡献开源TDA项目

## 🤝 贡献

欢迎贡献！如果您知道优秀的TDA资源，请：
1. Fork本仓库
2. 添加您的资源（附上描述）
3. 提交Pull Request

## 📄 许可

本项目采用MIT许可证。

## 🔗 相关资源

- [Awesome TDA (FatemehTarashi)](https://github.com/FatemehTarashi/awesome-tda)
- [TDAverse](https://github.com/tdaverse/tdaverse)
- [DONUT Database](https://donut.topology.rocks/)
