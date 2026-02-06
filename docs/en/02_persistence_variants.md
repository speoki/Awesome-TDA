# Persistence Methods & Variants

This page introduces various variants and extensions of persistent homology.

## Extended Persistence

### Extended Persistent Homology (EPH)
- **Tutorial**: https://github.com/GUDHI/TDA-tutorial/blob/master/Tuto-GUDHI-extended-persistence.ipynb
- **Description**: Extended persistent homology captures topological information beyond standard persistent homology
- **Applications**: Function topology analysis, terrain analysis

### Extended Persistence Diagrams (EPD)
- **Features**: Contains ordinary persistence and relative persistence information
- **Usage**: More complete topological feature description

### DC-Filtrations
- **Link**: https://github.com/aidos-lab/diffusion-condensation-filtrations
- **Full Name**: Diffusion Condensation Filtrations
- **Description**: Filtration method based on diffusion condensation
- **Application**: Topological analysis of graphs and point clouds

## Zigzag Persistence

### zzgril - Quasi Zigzag Persistence
- **Link**: https://github.com/TDA-Jyamiti/zzgril
- **Paper**: Quasi Zigzag Persistence: A Topological Framework for Analyzing Time-Varying Data
- **Description**: Topological framework for analyzing time-varying data
- **Applications**: Dynamic data analysis

### FastZigzag
- **Link**: https://github.com/taohou01/fzz
- **Paper**: Fast Computation of Zigzag Persistence
- **Description**: Fast computation of zigzag persistence

### Vineyard
- **Link**: https://bitbucket.org/ahickok/vineyard/src/main/
- **Alternative**: https://github.com/oliverchubet/persistence
- **Description**: Time series analysis for persistent homology
- **Applications**: Functional MRI (fMRI), dynamic data

### Wayne State TDA
- **Link**: https://github.com/regalski/Wayne-State-TDA
- **Description**: Vineyard generation code for time series analysis of persistent homology
- **Focus**: Identifying persistent homology features that remain stable over time
- **Applications**: fMRI data analysis

## Multi-parameter Persistence

### RIVET
- **Link**: https://github.com/aj-alonso/rivet
- **Description**: Program for visualizing and analyzing bi-parameter persistent homology
- **Features**: Interactive visualization tool

### GRIL - Bi-parameter Persistent Layers
- **Link**: https://github.com/TDA-Jyamiti/GRIL
- **Description**: Learning-based bi-parameter persistent layers

### D-GRIL
- **Link**: https://github.com/TDA-Jyamiti/d-gril
- **Paper**: D-Gril: End-to-End Topological Learning with 2-parameter Persistence
- **Description**: End-to-end topological learning with bi-parameter persistence

### pyrivet
- **Link**: https://github.com/rivetTDA/rivet-python
- **Description**: Python API for RIVET
- **Features**: Bi-parameter persistent homology computation via Python

### multipers  
- **Link**: https://github.com/conda-forge/multipers-feedstock
- **Description**: Multi-parameter persistence computation

### Delaunay Bifiltrations
- **Link**: https://github.com/ond Raganov/multipers
- **Description**: Delaunay bifiltrations in multipers library
- **Features**: Multi-parameter persistent homology with Delaunay complexes

### Algorithms for Complexes of Persistence Modules
- **Link**: https://github.com/TDA-Jyamiti/Algos-cplxs-pers-modules
- **Paper**: Efficient Algorithms for Complexes of Persistence Modules with Applications
- **Description**: Efficient algorithms for complexes of persistence modules

## Persistent Path Homology (Directed Networks)

### Path Homology Toolkit
- **Link**: https://github.com/max-nekrashevich/path-homology-toolkit
- **Description**: Toolkit for computing path homology and basic path operations
- **Applications**: Directed graph analysis

### pypph
- **Link**: https://github.com/samirchowdhury/pypph
- **Paper**: Persistent Path Homology of Directed Networks (Samir Chowdhury, Facundo Mémoli)
- **Languages**: Matlab, Python, C++
- **Description**: Computes persistent path homology on networks
- **Applications**: Asymmetric directed graph analysis

### persistent_path_homology-python3
- **Link**: https://github.com/rafaelpcarneiro/persistent_path_homology-python3
- **Based on**: Persistent Path Homology of Directed Networks paper
- **Description**: Python implementation of persistent path homology algorithm

### sheaves/path_homology
- **Link**: https://github.com/sheaves/path_homology/tree/main
- **Description**: Path homology of directed graphs

### PathHom
- **Link**: https://github.com/WeilabMSU/PathHom
- **Description**: Path homology computation tool

### PersNet
- **Link**: https://github.com/fmemoli/PersNet
- **Description**: Software package for persistence computation on networks
- **Language**: Matlab
- **Documentation**: Includes PDF tutorial, requires javaPlex

## Persistent Laplacians

### Persistent Laplacian
- **Link**: https://github.com/ndag/Persistent-Laplacian
- **Description**: Matlab implementation of q-th persistent Laplacian
- **Method**: Via Schur complement formulation

### HERMES
- **Link**: https://github.com/wangru25/HERMES
- **Description**: Simultaneous topological data analysis (persistent Betti numbers) and geometric data analysis (persistent eigenvalues)
- **Implementation**: Through persistent spectral graph theory
- **Support**: Alpha complex and Vietoris-Rips complex

### Persistent Sheaf Laplacians
- **Link**: https://github.com/weixiaoqimath/persistent_sheaf_Laplacians
- **Description**: Persistent sheaf Laplacians

### PersistentSheafLaplacian_PPI_Analysis
- **Link**: https://github.com/seanfcottrell/PersistentSheafLaplacian_PPI_Analysis
- **Description**: Protein-protein interaction analysis using persistent sheaf Laplacians
- **Applications**: Biomarker discovery, drug repurposing

### Persistent Directed Flag Laplacian
- **Link**: https://github.com/yangzhonghuan/Persistent-Laplacian
- **Description**: Persistent directed flag Laplacian

### PDFL-Score
- **Link**: https://github.com/mzia-s/PDFL-Score
- **Paper**: Persistent Directed Flag Laplacian (PDFL)-Based Machine Learning for Protein-Ligand Binding Affinity Prediction
- **Description**: PDFL-based machine learning for protein-ligand binding affinity prediction
- **Dependencies**: flagser package
- **Dataset**: PDBbind dataset

### Persistence-Mayer-Homology-and-Laplacian
- **Link**: https://github.com/WeilabMSU/Persistence-Mayer-Homology-and-Laplacian
- **Description**: Persistence Mayer homology and Laplacian

### persistentlaplaciandatascience
- **Link**: https://github.com/tomogwen/persistentlaplaciandatascience
- **Paper**: The Persistent Laplacian for Data Science: Evaluating Higher-Order Persistent Spectral Representations of Data
- **Conference**: ICML 2023

### Survey Paper
- **Link**: https://arxiv.org/pdf/2312.07563
- **Title**: Persistent Topological Laplacians – a Survey
- **Description**: Survey of persistent topological Laplacians

## Spatiotemporal Persistence

### Spatiotemporal Persistent Homology
- **Paper**: Spatiotemporal Persistent Homology for Dynamic Metric Spaces
- **Journal**: Discrete & Computational Geometry 2020
- **Description**: Spatiotemporal persistent homology for dynamic metric spaces (DMS)
- **Method**: Three-parameter "spatiotemporal" filtration
- **Applications**: Swarm/flock behavior, social networks

## Other Persistence Variants

### Chromatic TDA
- **Link**: https://github.com/OnDraganov/chromatic-tda
- **Description**: Sixpack of persistence diagrams for colored point clouds
- **Contents**: Kernel, domain, image, codomain, cokernel, and relative persistence diagrams
- **Applications**: Cell classification on tissue slices, 3D structures of materials
- **New Features**: Experimental feature extraction (extracting loops from barcodes)

### Local Persistent Homology
- **Paper**: Persistent Local Homology in Graph Learning
- **Link**: https://openreview.net/notes/edits/attachment?id=jK9bRzKRCU&name=pdf
- **Description**: Persistent local homology in graph learning

### Dowker Persistence
- **Link**: https://tgda.osu.edu/DowkerPH
- **Paper**: Persistent Homology of Asymmetric Networks
- **Description**: Persistent homology of asymmetric networks

### Hypergraph-based Persistent Cohomology
- **Link**: https://github.com/LiuXiangMath/Hypergraph-based-Persistent-Cohomology
- **Description**: Hypergraph-based persistent cohomology

---

[Back to Home](README.md)
