# Awesome TDA Documentation

> A curated list of Topological Data Analysis (TDA) resources

Topological Data Analysis is a mathematical framework that uses methods from topology and geometry to extract meaningful information from data. TDA provides powerful tools for understanding the shape, structure, and patterns in data.

## 📚 Documentation Navigation

### Core Resources

- [Software Packages & Libraries](01_software_packages.md) - TDA software packages, libraries, and tools
- [Persistence Methods](02_persistence_variants.md) - Various persistent homology variants and methods
- [Visualization Tools](03_visualization.md) - TDA visualization tools and techniques

### Application Domains

- [Graph & Network Analysis](04_graph_network_analysis.md) - TDA methods for graphs and networks
- [Datasets & Applications](05_datasets_applications.md) - TDA datasets and application cases
- [Mathematical Tools](06_mathematical_tools.md) - Mathematical foundations and tools for TDA

### Learning Resources

- [Tutorials & Papers](07_tutorials_papers.md) - Learning resources, tutorials, and key papers

## 🚀 Quick Start

### What is TDA?

Topological Data Analysis (TDA) uses methods from algebraic topology, particularly persistent homology, to analyze data. Key advantages include:

- **Shape Analysis**: Reveals geometric and topological structure of data
- **Multi-scale**: Captures features at different scales
- **Coordinate-free**: Invariant to coordinate transformations
- **Noise Robust**: Robust to noise in data

### Main Concepts

- **Persistent Homology**: Tracks topological features (connected components, loops, voids, etc.) across different scales
- **Persistence Diagram**: Main tool for visualizing persistent homology results
- **Filtration**: Construction of multi-scale simplicial complex sequences
- **Mapper Algorithm**: For data visualization and exploratory analysis

### Popular Software Packages

| Package | Language | Features |
|---------|----------|----------|
| [giotto-tda](https://github.com/giotto-ai/giotto-tda) | Python | Machine learning integration |
| [GUDHI](https://gudhi.inria.fr/) | C++/Python | Comprehensive TDA library |
| [Ripser](https://github.com/Ripser/ripser) | C++ | Efficient persistent homology |
| [scikit-tda](https://scikit-tda.org/) | Python | Python ecosystem |

## 🌟 Featured Projects

### Persistent Laplacians
Combining persistent homology with spectral methods for richer topological-geometric information
- [Persistent Laplacian](https://github.com/ndag/Persistent-Laplacian)
- [HERMES](https://github.com/wangru25/HERMES)

### Directed Graph Persistence
TDA methods specifically for directed networks and graphs
- [pyflagser](https://github.com/giotto-ai/pyflagser)
- [Path Homology](https://github.com/max-nekrashevich/path-homology-toolkit)

### Multi-parameter Persistence
Handling complex data with multiple filtration parameters
- [RIVET](https://github.com/aj-alonso/rivet)
- [multipers](https://github.com/conda-forge/multipers-feedstock)

## 📖 Learning Path

### Beginners
1. Read foundational tutorials and introductory papers
2. Install and try scikit-tda or giotto-tda
3. Experiment with persistent homology on simple datasets
4. Learn how to interpret persistence diagrams

### Intermediate
1. Explore different filtration methods (Rips, Čech, Alpha)
2. Learn the Mapper algorithm
3. Apply TDA to real-world datasets
4. Understand statistical methods and machine learning integration

### Advanced
1. Study multi-parameter persistence
2. Explore persistent Laplacians and spectral methods
3. Develop new TDA applications
4. Contribute to open-source TDA projects

## 🤝 Contributing

Contributions welcome! If you know excellent TDA resources, please:
1. Fork this repository
2. Add your resource (with description)
3. Submit a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🔗 Related Resources

- [Awesome TDA (FatemehTarashi)](https://github.com/FatemehTarashi/awesome-tda)
- [TDAverse](https://github.com/tdaverse/tdaverse)
- [DONUT Database](https://donut.topology.rocks/)
