# Graph & Network Analysis

This page collects TDA methods and tools for graphs and networks.

## Directed Graph Persistence

### pyflagser
- **Link**: https://github.com/giotto-ai/pyflagser
- **Description**: Computes persistent homology of directed flag complexes
- **Paper**: Persistent Homology Over Directed Acyclic Graphs
- **arXiv**: https://arxiv.org/abs/1407.2523

### Persistent Homology on Graphs
- **Link**: https://github.com/USFDataVisualization/PersistentHomologyOnGraphs
- **Description**: Visualization tool for interactive work with undirected graphs using persistent homology

### TDA-on-graphs
- **Link**: https://github.com/OliviaMcGough/TDA-on-graphs
- **Description**: Applying Topological Data Analysis to graph data
- **Supported Complexes**:
  - Flag complexes
  - Directed flag complexes
  - Flag tournaplexes
  - Dowker sink complexes

## Path Homology (Directed Networks)

### pypph
- **Link**: https://github.com/samirchowdhury/pypph
- **Paper**: Persistent Path Homology of Directed Networks
- **Languages**: Matlab, Python, C++
- **Applications**: Directed graphs with asymmetric weights

### Path Homology Toolkit
- **Link**: https://github.com/max-nekrashevich/path-homology-toolkit
- **Description**: Computing path homology and basic path operations

### sheaves/path_homology
- **Link**: https://github.com/sheaves/path_homology/tree/main
- **Description**: Path homology of directed graphs

### persistent_path_homology-python3
- **Link**: https://github.com/rafaelpcarneiro/persistent_path_homology-python3
- **Description**: Python implementation of persistent path homology algorithm

### PersNet
- **Link**: https://github.com/fmemoli/PersNet
- **Description**: Software package for persistence computation on networks (Matlab)
- **PMC Paper**: https://pmc.ncbi.nlm.nih.gov/articles/PMC10575407/

### PathHom
- **Link**: https://github.com/WeilabMSU/PathHom
- **Description**: Path homology computation tool

## Dynamic Graphs & Networks

### TMetaNet
- **Link**: https://github.com/Lihaogx/TMetaNet
- **Paper**: TMetaNet: Topological Meta-Learning Framework for Dynamic Link Prediction
- **Description**: 
  - Meta-learning framework based on dynamic topological features
  - Uses Dowker Zigzag Persistence (DZP)
  - Captures higher-order features of dynamic graphs
- **Applications**: Dynamic link prediction

### tergm
- **Link**: https://github.com/statnet/tergm
- **Description**: Network evolution models based on exponential-family random graph models
- **Features**: Fit, simulate, and diagnose

### TDAdynamicdata
- **Link**: https://github.com/frabertoglio/TDAdynamicdata
- **Description**: TDA methods for dynamic data

### tpot
- **Link**: https://github.com/zsteve/tpot.git
- **Description**: Topological tools for dynamic data

### Vineyard
- **Link**: https://bitbucket.org/ahickok/vineyard/src/main/
- **Description**: Time series analysis of persistent homology
- **Applications**: Identifying persistent features that remain stable over time

## Stability & Distances

### Stable Distance for Persistent Homology in Dynamic Graph Comparison
- **Link**: https://www.x-mol.com/paper/1685527121194770432/t?adv
- **Description**: Stable distance for dynamic graph representation learning

### Dynamic Network Embedding Survey
- **Link**: https://junshan-wang.github.io/essays/dynamic_network_embedding/
- **Content**: 
  - Graph representation learning
  - SkipGram models
  - GNN models
  - Capturing graph evolution patterns

## Network Datasets

### Dowker PH - Persistent Homology of Asymmetric Networks
- **Link**: https://tgda.osu.edu/DowkerPH
- **Description**: Persistent homology of asymmetric networks
- **Datasets**: 
  - Simulated hippocampal networks
  - U.S. economy input-output accounts
  - U.S. migration data
  - Global migration data
  - Grapevine Network demo

### Network Evolution Data
- **Description**: 3D MDS plots of hippocampal network classification

## Graph Classification

### TDA for Graph Classification
- **Paper**: https://arxiv.org/pdf/2512.24917
- **Description**: Using TDA for graph classification

### SCOTT
- **Link**: https://github.com/aidos-lab/curvature-filtrations
- **Full Name**: Synthesizing Curvature Operations and Topological Tools
- **Paper**: [Curvature Filtrations for Graph Generative Model Evaluation](https://arxiv.org/abs/2301.12906)
- **Conference**: NeurIPS 2023
- **Description**: Curvature filtration computation for graphs and graph distributions
- **Core Idea**: Combining discrete curvature with persistent homology
- **Core Components**:
  - **KILT**: Curvature filtration for single graphs
  - **Comparator**: Compare graphs or graph distributions
- **Curvature Methods**: Forman curvature and other discrete curvatures
- **Features**:
  - Robust
  - Stable
  - Expressive
  - Compatible with statistical testing
- **Applications**:
  - Graph generative model evaluation
  - Graph distribution comparison
  - Avoiding MMD (Maximum Mean Discrepancy) limitations

### Orchid 🌸
- **Link**: https://github.com/aidos-lab/orchid
- **Full Name**: Ollivier-Ricci Curvature for Hypergraphs in Data
- **Paper**: Ollivier-Ricci Curvature for Hypergraphs: A Unified Framework
- **Conference**: ICLR 2023
- **Language**: Julia
- **Description**: Unified framework for Ollivier-Ricci curvature of hypergraphs
- **Features**:
  - Julia library and CLI
  - Hypergraph curvature computation
  - Full reproducibility package (Zenodo)
- **Application**: Hypergraph data analysis, higher-order network structure research
- **Complement**: Works with SCOTT (SCOTT for graphs, Orchid for hypergraphs)

### Neural k-Forms
- **Link**: https://github.com/aidos-lab/neural-k-forms
- **Paper**: [Simplicial Representation Learning with Neural k-Forms](https://openreview.net/forum?id=Djw0XhjHZb)
- **Conference**: ICLR 2024
- **Description**: Simplicial representation learning using neural k-forms
- **Core Idea**:
  - Use differential k-forms to create simplicial representations
  - Leverage geometric information (node coordinates) instead of message passing
- **Advantages**:
  - Strong interpretability
  - Geometric consistency
  - No message passing needed
  - Avoids over-smoothing
  - Supports differential geometry tools
  - Achieves universal approximation
- **Applicable Structures**:
  - Graphs
  - Simplicial Complexes
  - Cell Complexes
- **Application**: Geometric graph representation learning, outperforms traditional message passing neural networks

### TARDIS
- **Link**: https://github.com/aidos-lab/TARDIS
- **Full Name**: Topological Algorithm for Revealing Directions of Irregularity in Spectra
- **Paper**: [TARDIS: Topological Algorithms for Robust Discovery of Singularities](https://arxiv.org/abs/2308.07846)
- **Conference**: ICML 2023  
- **Description**: Robust singularity detection
- **Core**: Detect instabilities and singularities in spectral data
- **Features**: Topology-based robustness
- **Application**: Spectral analysis, quantum system singularity detection

### Graph Learning Papers
- **Link**: https://github.com/doujiang-zheng/Awesome-Graph-Learning-Papers-List
- **Description**: Curated list of graph learning papers

## Anomaly Detection

### Graph Edge Anomaly Detection
- **Link**: https://github.com/MKasaei00/graph-edge-anomaly-detection/tree/master/AnoEdge
- **Description**: Graph edge anomaly detection algorithms

### Graph Anomaly Detection Datasets
- **Link**: https://github.com/lizhong2613/GraphAnomalyDetectionDatasets
- **Description**: Collection of graph anomaly detection datasets

## Dowker Complexes

### Dowker PH
- **Link**: https://tgda.osu.edu/DowkerPH
- **Paper**: Persistent Homology of Asymmetric Networks
- **Description**: Persistent homology of asymmetric networks

## Reeb Graphs

### ceREEBerus
- **Link**: https://munchlab.github.io/ceREEBerus/index.html
- **Description**: Reeb graph computations in Python
- **EUSIPCO Paper**: https://eurasip.org/Proceedings/Eusipco/Eusipco2023/pdfs/0002033.pdf

### pyper
- **Link**: https://github.com/Pseudomanifold/pyper
- **Description**: Python-based persistent homology algorithms
- **Usage**: Manifold learning

---

[Back to Home](README.md)
