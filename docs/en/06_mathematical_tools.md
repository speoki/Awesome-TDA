# Mathematical Tools & Theory

This page collects mathematical foundation tools and theoretical resources for TDA.

## Homological Algebra Analysis

### GDA-Public
- **Link**: https://geomdata.github.io/gda-public/multidimensional_data.html
- **GitHub**: https://github.com/geomdata/gda-public/
- **Description**: Geometric data analysis public resources
- **Content**: 
  - TDA algebraic homology group analysis
  - Multidimensional data processing
  - Euler characteristic computation

## Manifolds & Riemannian Geometry

### PyManopt
- **Link**: https://pymanopt.org/
- **Description**: Python toolbox for Riemannian manifold optimization with automatic differentiation
- **Applications**: 
  - SPD manifold data processing
  - Grassmann manifold analysis
  - Optimization problems on manifolds

### Riemannian Change Point Detection
- **Link**: https://github.com/xiuheng-wang/CPD_RCE_release
- **Paper**: Online Change Point Detection on Riemannian Manifolds with Karcher Mean Estimates
- **Description**: Riemannian change point detection on manifolds with robust centroid estimation
- **Applications**: Karcher mean estimation

### CPD Manifold Release
- **Link**: https://github.com/xiuheng-wang/CPD_manifold_release
- **Description**: Change point detection tools on manifolds

## Reeb Graph Theory

### ceREEBerus
- **Link**: https://munchlab.github.io/ceREEBerus/index.html
- **Description**: Reeb graph computations in Python
- **Applications**: Dimensionality reduction and visualization in TDA

### pyper
- **Link**: https://github.com/Pseudomanifold/pyper
- **Description**: Python-based persistent homology algorithms
- **Usage**: Manifold learning experiments

## Topological Invariants Theory

### Euler Characteristic
- **Description**: Topological invariant from surface area integration
- **Properties**: 
  - For spherical structures, Gaussian curvature integral = 4π
  - Provides global description of common properties of structures
  - Forms basic topological invariants with connectivity number

### Betti Numbers
- **Theory**: Describes the number of "holes" in topological spaces
- **Applications**: 
  - β₀: Number of connected components
  - β₁: Number of cycles/loops
  - β₂: Number of voids

## Distances & Metrics

### Landscape Distance
- **Paper**: Equivalence of Landscape and Erosion Distances for Persistence Diagrams
- **Link**: https://albanymath.github.io/comper25/schedule.html
- **Description**: Equivalence of landscape and erosion distances for persistence diagrams

### Erosion Distance
- **Description**: Erosion distance metric between persistence diagrams

### Gromov-Hausdorff Distance
- **Applications**: Stability analysis of dynamic metric spaces (DMS)
- **Paper**: Spatiotemporal Persistent Homology for Dynamic Metric Spaces

### Magnipy
- **Link**: https://github.com/aidos-lab/magnipy
- **Description**: Magnitude computation tool for metric spaces
- **Core Modules**:
  - **Magnipy**: In-depth computation for single metric space
  - **Diversipy**: Magnitude comparison across multiple datasets
- **Features**: Distance matrices, magnitude weights, magnitude dimension, MagArea (diversity measure)
- **Application**: Quantify intrinsic diversity and dimensionality of datasets

### Presto
- **Link**: https://github.com/aidos-lab/Presto
- **Full Name**: Projected Embedding Similarity based on Topological Overlays
- **Conference**: ICML 2024
- **Description**: Topological similarity metric tool for embedding representations
- **Core**: Efficiently measure structural differences in representations from different ML workflows
- **Application**: Latent representation multiverse analysis, embedding comparison

## Algebraic Topology Tools

### javaPlex
- **Description**: Persistent homology computation library in Java
- **Usage**: Dependency for tools like PersNet

### PHAT (Persistent Homology Algorithm Toolbox)
- **Description**: Interface for persistence reduction algorithms on boundary matrices
- **Features**: Design separating representation from implementation

## Theoretical Papers & Surveys

### Persistent Topological Laplacians Survey
- **Link**: https://arxiv.org/pdf/2312.07563
- **Title**: Persistent Topological Laplacians – a Survey
- **Content**: Survey of persistent topological Laplacians

### TDA Papers Collection
- **Link**: https://github.com/LiuXiangMath/TDA_papers
- **Description**: Collection of TDA papers

### Distance-from-flat Persistent Homology Transforms
- **Link**: https://albanymath.github.io/comper25/schedule.html
- **Description**: Distance-from-flat persistent homology transforms: an efficient tool for shape analysis

## Complex Theory

### Vietoris-Rips Complex
- **Description**: Most commonly used simplicial complex construction method
- **Features**: Based on distances between point cloud

### Čech Complex
- **Description**: Complex based on ball covering
- **Features**: Good theoretical properties but computationally complex

### Alpha Complex
- **Description**: Subcomplex of Delaunay triangulation
- **Features**: Computationally efficient, suitable for low-dimensional data

### Flag Complex
- **Description**: Maximal simplicial complex constructed from graphs
- **Applications**: Directed graphs, network analysis

### Dowker Complex
- **Applications**: Asymmetric network analysis
- **Features**: Handles asymmetric relationships

## Shape Analysis

### Vietoris-Rips Complexes of Split-Decomposable Spaces
- **Link**: https://albanymath.github.io/comper25/schedule.html
- **Description**: Vietoris-Rips complexes of split-decomposable spaces

### Knot Theory
- **Tool**: KnotPlot (https://knotplot.com/)
- **Applications**: Visualization and manipulation of mathematical knots in 3D and 4D

## Statistical Topology

### Statistical Methods for Persistence Diagrams
- **Content**: 
  - Mean persistence diagrams
  - Confidence bands
  - Hypothesis testing

### Bootstrap Methods
- **Applications**: Statistical significance assessment for persistence diagrams

---

[Back to Home](README.md)
