# Awesome TDA

> 拓扑数据分析（Topological Data Analysis）资源精选列表

[![GitHub Pages](https://img.shields.io/badge/docs-GitHub%20Pages-blue)](https://speoki.github.io/Awesome-TDA/)

欢迎来到**Awesome TDA**！这是一个精心整理的拓扑数据分析资源集合，包括软件包、教程、论文和应用案例。

## 📖 在线文档

**访问完整文档**: [https://speoki.github.io/Awesome-TDA/](https://speoki.github.io/Awesome-TDA/)

在线文档提供：
- 🔍 搜索功能
- 🌐 中英文双语支持
- 📱 响应式设计
- 🎨 清晰的分类导航

## 📚 文档目录

### 核心资源
- [软件包与库](docs/01_软件包.md) - TDA软件包、库和工具
- [持久性方法](docs/02_持久性变体.md) - 各种持久同调变体和方法
- [可视化工具](docs/03_可视化.md) - TDA可视化工具和技术

### 应用领域
- [图与网络分析](docs/04_图网络分析.md) - 图和网络的TDA方法
- [数据集与应用](docs/05_数据集应用.md) - TDA数据集和应用案例
- [数学工具](docs/06_数学工具.md) - TDA的数学基础和工具

### 学习资源
- [教程与论文](docs/07_教程论文.md) - 学习资源、教程和关键论文

## 🚀 快速开始

### 推荐软件包

#### 入门/通用分析
```bash
pip install giotto-tda
```
**giotto-tda** 文档最全，安装最简单，涵盖从预处理到可视化的全流程。

#### 大规模数据处理
```bash
pip install ripser
```
底层计算使用 **Ripser** 或 **GUDHI**，并行加速可使用 **giotto-ph**。

#### 深度学习集成
```bash
pip install torch-topological
```
将拓扑特征集成到深度学习模型中。

### 技术选型建议

| 应用场景 | 推荐工具 |
|---------|---------|
| 入门学习 | giotto-tda, scikit-tda |
| 大规模计算 | Ripser, GUDHI, giotto-ph |
| 探索性分析 (EDA) | KeplerMapper, tsfresh |
| 动态系统/时间序列 | Dionysus 2, Teaspoon, FastZigzag |
| 有向网络 | Flagser, Path Homology |
| 深度学习 | TopoModelX, PersLay, pytorch-topological |
| NLP应用 | TDA4NLP |
| 生物医学 | HERMES, TopoDockQ |

## 🌟 特色项目

- **持久拉普拉斯算子**: 结合拓扑与谱方法 ([HERMES](https://github.com/wangru25/HERMES),  [Persistent Laplacian](https://github.com/ndag/Persistent-Laplacian))
- **有向图持久性**: 专用于有向网络 ([pyflagser](https://github.com/giotto-ai/pyflagser), [Path Homology](https://github.com/ndag/path-homology))
- **多参数持久性**: 处理多过滤参数 ([RIVET](https://github.com/aj-alonso/rivet), [multipers](https://github.com/conda-forge/multipers-feedstock))
- **拓扑深度学习**: TDA + 神经网络 ([TopoModelX](https://github.com/pyt-team/TopoModelX), [PersLay](https://github.com/MathieuCarriere/perslay))

## 📦 主要软件包

- **giotto-tda** - Python机器学习TDA库
- **GUDHI** - 综合性几何理解库
- **scikit-tda** - Python TDA生态系统
- **Ripser** - 高效持久同调计算
- **Dionysus 2** - 经典TDA库，Vineyard算法
- **Eirene** - Julia高维同调计算
- **TopoModelX** - 拓扑深度学习
- **Teaspoon** - 时间序列TDA

## 🎓 学习资源

- [GUDHI教程](https://github.com/GUDHI/TDA-tutorial)
- [ComPer 2025研讨会](https://albanymath.github.io/comper25/)
- [TDA论文集](https://github.com/LiuXiangMath/TDA_papers)
- [DONUT数据库](https://donut.topology.rocks/)

## 🤝 贡献

欢迎贡献！请查看[贡献指南](CONTRIBUTING.md)。

如果您知道优秀的TDA资源：
1. Fork本仓库
2. 添加资源（附上描述）  
3. 提交Pull Request

## 📄 许可

MIT License

## 🔗 相关资源

- [Awesome TDA (FatemehTarashi)](https://github.com/FatemehTarashi/awesome-tda)
- [TDAverse](https://github.com/tdaverse/tdaverse)
- [Awesome Graph Learning Papers](https://github.com/doujiang-zheng/Awesome-Graph-Learning-Papers-List)

---

**⭐ 如果觉得有用，请给个Star！**
