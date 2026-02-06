# Software Packages & Libraries

This page collects major TDA software packages, libraries, and tools.

## Comprehensive TDA Libraries

### giotto-tda
- **Link**: https://github.com/giotto-ai/giotto-tda
- **Language**: Python
- **Features**: TDA library designed for machine learning, seamless integration with scikit-learn
- **Capabilities**: Persistent homology, Mapper, time series analysis, graph analysis

### giotto-ph
- **Link**: https://github.com/giotto-ai/giotto-ph
- **Language**: Python/C++
- **Description**: High-performance CPU implementation of Vietoris-Rips persistence under GNU AGPLv3 license
- **Features**: 
  - Improved "lock-free Ripser" implementation
  - Parallelized apparent pairs optimization
  - Improved GUDHI Edge Collapse (EC) algorithm
  - Support for weighted VR filtrations

### GUDHI
- **Link**: https://gudhi.inria.fr/
- **Language**: C++/Python
- **Description**: Comprehensive geometry understanding library developed by INRIA
- **Capabilities**: 
  - Multiple simplicial complex constructions
  - Persistent homology computation
  - Rips, Alpha, Čech complexes
  - Extended persistent homology
- **Tutorials**: https://github.com/GUDHI/TDA-tutorial

### scikit-tda
- **Link**: https://scikit-tda.org/
- **Description**: Python TDA ecosystem
- **Components**:
  - **ripser.py**: Fast persistent homology computation
  - **persim**: Persistence diagram distances and visualization
  - **kepler-mapper**: Mapper algorithm implementation
  - **cechmate**: Custom filtration constructors
  - **tadasets**: TDA benchmark datasets

#### ripser.py
- **Description**: Lean persistent homology library for Python based on Ripser
- **Features**: Simple and efficient API

#### persim
- **Description**: Distances and representations of persistence diagrams
- **Features**: Bottleneck distance, Wasserstein distance, diagram visualization

#### kepler-mapper
- **Description**: Flexible Python implementation of Mapper algorithm
- **Features**: Topological data visualization and exploration

#### cechmate
- **Description**: Custom filtration constructors for Python
- **Features**: Easy construction of Čech, Alpha, and custom filtrations

#### tadasets
- **Description**: Synthetic datasets for TDA
- **Purpose**: Benchmarking and exploration

## Efficient Persistent Homology Computation

### Ripser
- **Link**: https://github.com/Ripser/ripser
- **Language**: C++
- **Features**: One of the world's fastest persistent homology computation tools
- **Bindings**: ripserr (R), ripser.py (Python)

### Ripser
- **Link**: https://github.com/Ripser/ripser
- **Language**: C++
- **Features**: One of the world's fastest persistent homology computation tools
- **Bindings**: ripserr (R), ripser.py (Python)

### Dory
- **Link**: https://github.com/nihcompmed/Dory
- **Python Package**: pyDory (`pip install pydory`)
- **Description**: VR persistent homology and tight cycle representatives for large datasets
- **Output**: H0/H1/H2 persistence pairs files
- **Requirements**: gcc-10.2 with openMP
- **Application**: Large-scale point cloud topological analysis

### DIPHA
- **Link**: https://github.com/DIPHA/dipha
- **Full Name**: Distributed Persistent Homology Algorithm
- **Language**: C++
- **Description**: Distributed persistent homology computation with MPI cluster support
- **Input**: Grayscale images, distance matrices, weighted complexes
- **Features**: Parallel computation, dualization optimization, PHAT data structures
- **Application**: Large-scale distributed topological computation

### dowker_homology
- **Link**: https://sparse-dowker-nerves.readthedocs.io/
- **Documentation**: https://sparse-dowker-nerves.readthedocs.io/en/latest/
- **Description**: Sparse Dowker nerves and persistent homology computation
- **Papers**: Sparse Dowker Nerves (2018), Sparse Filtered Nerves (2018)
- **Features**: Point clouds, weighted networks, filtered covers
- **Complexes**: Čech complex, Alpha complex, subspace sparsification

### PHAT
- **Features**: Provides clean interface for persistence reduction algorithms on boundary matrices
- **Related**: GUDHI's edge collapse implementation

### Sophia
- **Link**: https://bitbucket.org/schreiberh/sophia/
- **Description**: Streaming algorithm for persistent homology of towers
- **Core**: Converts towers to equivalent filtrations using coning strategy
- **Features**: Space complexity independent of tower length, only depends on max subcomplex
- **License**: GNU LGPL

### CGAL
- **Link**: https://www.cgal.org/
- **Language**: C++
- **Description**: Open source computational geometry algorithms library
- **Features**: Triangulations, Voronoi diagrams, convex hulls, Alpha shapes, mesh generation
- **Applications**: GIS, CAD, molecular biology, medical imaging, robotics
- **License**: GPL v3+ / Commercial license

### OAT
- **Link**: https://openappliedtopology.github.io/
- **Full Name**: Open Applied Topology  
- **Languages**: Rust + Python
- **Description**: General-purpose applied topology library
- **Core**: High-performance linear algebra tools designed for topology
- **Features**:
  - Complete analysis pipelines and building blocks
  - Open linear algebra interface for customization
  - Persistent homology and visualization support
- **Documentation**: Python and Rust dual language support

## Specialized TDA Tools

### cechmate
- **Link**: https://github.com/scikit-tda/cechmate
- **Documentation**: https://cechmate.scikit-tda.org/
- **Description**: Provides easy-to-use custom filtration constructors for Phat
- **Supported filtrations**: Alpha, Rips, Čech
- **Purpose**: Bridges the gap between data matrices and boundary matrices

### kepler-mapper
- **Link**: https://github.com/scikit-tda/kepler-mapper
- **Description**: Mapper algorithm implementation in Python
- **Usage**: Topological data visualization and exploratory analysis
- **Applications**: https://kepler-mapper.scikit-tda.org/en/latest/applications.html

## Directed Graph Persistence

### pyflagser
- **Link**: https://github.com/giotto-ai/pyflagser
- **Description**: Computes persistent homology of directed flag complexes
- **Documentation**: https://giotto-ai.github.io/gtda-docs/latest/modules/generated/homology/gtda.homology.VietorisRipsPersistence.html
- **Examples**: https://github.com/giotto-ai/giotto-tda/blob/master/examples/persistent_homology_graphs.ipynb

### flagser-laplacian
- **Link**: https://github.com/bdjones13/flagser-laplacian
- **Description**: Computes persistent spectra of directed flag complexes using persistent topological Laplacian

## R Language TDA

### TDAverse
- **Link**: https://github.com/tdaverse/tdaverse
- **Description**: TDA ecosystem for R
- **Includes**:
  - ripserr: Vietoris-Rips filtrations
  - Cubical filtrations for raster data
  - TDAvec: Efficient persistence diagram vectorization

### TDA (R package)
- **Documentation**: https://github.com/tdaverse/tdarec
- **Engines**:
  - Vietoris-Rips filtrations (point clouds)
  - Cubical filtrations (raster data)
- **Vectorization**: Euler characteristic curves, etc.

## Deep Learning & TDA Integration

Integrate topological features into neural networks or design topological regularization layers.

### TopoModelX
- **Link**: https://github.com/pyt-team/TopoModelX
- **Description**: Topological deep learning library
- **Support**:
  - Simplicial Complex Neural Networks (SCNN)
  - Cell Complex Networks (CCNN)
  - Other topological domain neural networks
- **Similar to**: PyTorch Geometric (PyG)

### PersLay  
- **Link**: https://github.com/MathieuCarriere/perslay
- **Alternative**: https://github.com/rballeba/perslay-pytorch
- **Description**: Neural network layer for persistence diagrams
- **Features**: Vectorizes diagrams for ML tasks, differentiable

### pytorch-topological
- **Link**: https://github.com/aidos-lab/pytorch-topological
- **Description**: PyTorch topological layer library
- **Features**: Wasserstein distance, Alpha complex filtrations, various diagram vectorizations

### TopologyLayer
- **Link**: https://github.com/bruel-gabrielsson/TopologyLayer
- **Description**: PyTorch differentiable topological layers (classic)
- **Core Features**:
  - LevelSetLayer and RipsLayer
  - 0-dim and 1-dim homology differentiation
  - Persistent homology computation
- **Applications**:
  - Topological regularization (as loss function term)
  - Optimize topological constraints via backpropagation
  - Integrate topological features into deep learning models

### GUDHI TensorFlow/PyTorch
- **Link**: https://gudhi.inria.fr/python/latest/tensorflow_module.html
- **Description**: GUDHI differentiable support for deep learning
- **Features**: Differentiable persistence layers, Wasserstein distance
- **Stability**: Industry-grade performance

### Topological-Layers
- **Link**: https://github.com/aymericdamien/Topological-Layers
- **Description**: NeurIPS paper implementation
- **Purpose**: Topological layers for generative models

### Teardrop
- **Link**: https://github.com/aumgn/teardrop
- **Description**: PyTorch library for differentiable topological optimization
- **Features**: Complex topological feature optimization

### TorchTDA
- **Links**:
  - https://github.com/CompTop/torch-tda
  - https://zread.ai/CompTop/torch-tda
- **Description**: Lightweight TDA wrapper
- **Features**: Basic differentiable layers and topological loss functions
- **Note**: Multiple libraries with same name, verify carefully

### DECT
- **Link**: https://github.com/aidos-lab/dect-evaluation
- **Paper**: [Differentiable Euler Characteristic Transforms for Shape Classification](https://openreview.net/forum?id=MO632iPq3I)
- **Conference**: ICLR 2024
- **Full Name**: Differentiable Euler Characteristic Transform
- **Description**: End-to-end learnable Euler characteristic transform
- **Core Features**:
  - Combines geometric and topological properties
  - Fast and computationally efficient
  - Learns task-specific representations  
  - Same topological expressivity as complex topological DL layers
- **Applications**: Graph classification, point cloud classification, shape classification
- **Advantage**: Performance comparable to complex models but simpler

### Topological Uncertainty
- **Link**: https://github.com/tlacombe/topologicalUncertainty/
- **Paper**: Topological Uncertainty: Monitoring Trained Neural Networks through Persistence of Activation Graphs
- **Description**: Monitor trained neural networks via activation graph persistence
- **Core Idea**:
  - Extract topological information from weighted graphs
  - Aggregate via Fréchet mean
  - Compute topological distance to detect anomalies
- **Applications**:
  - Out-of-distribution (OOD) sample detection
  - Neural network anomaly monitoring
  - Weight distribution anomaly detection
- **Current Support**: TensorFlow 2 sequential networks, fully-connected layers
- **Future**: Integration into GUDHI, PyTorch support

## Data Analysis & Preprocessing

### tsfresh
- **Link**: https://github.com/blue-yonder/tsfresh
- **Description**: Time series feature extraction
- **Usage**: Exploratory Data Analysis (EDA) before TDA

## Other Tools

### qsv
- **Link**: https://github.com/RottenFruits/qsv
- **Description**: Fast CSV data processing tool

### gda-public
- **Link**: https://github.com/geomdata/gda-public/
- **Link2**: https://geomdata.github.io/gda-public/
- **Description**: Geometric data analysis public resources
- **Content**: Multidimensional data analysis, algebraic homology group analysis

### Oineus
- **Link**: https://github.com/anigmetov/oineus/
- **Link2**: https://github.com/aidos-lab/py-oineus
- **Description**: Efficient persistent homology computation library

### CoralTDA with PrunIt
- **Link**: https://github.com/cakcora/PersistentHomologyWithCoralPrunit
- **Description**: Persistent homology computation using CoralTDA and PrunIt

## Build Tools

### BATS
- **Link**: https://github.com/CompTop/BATS
- **Description**: Basic Algebraic Topology Subroutines

---

[Back to Home](README.md)
