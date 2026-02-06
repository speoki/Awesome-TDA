# Visualization Tools

This page collects TDA visualization tools and techniques.

## Persistence Diagram Visualization Tools

### Persistent Homology Visualizer (PHV)
- **Link**: https://github.com/Jiahuic/persistent_homology_visualizer
- **Description**: Represents persistent homology and persistent Laplacian using GUDHI, NetworkX, and Matplotlib
- **Features**: Persistence diagram visualization, barcode plots

### TopoEmbedding
- **Link**: https://github.com/DaVisLab/TopoEmbedding
- **Description**: Web-based tool that simplifies interactive visualization and analysis based on persistence descriptors
- **Features**: 
  - Interactive visualization of persistence descriptors
  - Connects topological descriptors with original data domain
  - Simple and effective visualization for non-TDA experts
- **Advantage**: Addresses the limited interactive visualization support in most TDA software libraries

## Comprehensive Visualization Platforms

### Topology ToolKit (TTK)
- **Link**: https://github.com/topology-tool-kit/ttk
- **Website**: https://topology-tool-kit.github.io/
- **Description**: Open source topological data analysis and visualization library collection
- **Platform**: Based on ParaView and VTK
- **Core Features**:
  - Persistent homology computation and visualization
  - Morse-Smale complexities
  - Reeb graphs and contour trees
  - Topological simplification
  - Interactive visualization of various topological features
- **Characteristics**:
  - Industrial-grade performance and stability
  - Seamless ParaView integration
  - Large-scale scientific data visualization support
  - Rich tutorials and documentation
- **Application Areas**: Scientific computing visualization, flow analysis, materials science

#### PersistenceCycles (TTK Module)
- **Link**: https://github.com/IuricichF/PersistenceCycles
- **Description**: TTK module for computing persistent homology and representative cycles
- **Core Modules**:
  - **BoundaryMatrix**: Sequential algorithm for persistent homology
  - **FormanGradient**: Forman gradient implementation
  - **FG_PersistentHomology**: Persistent cycle computation
- **Installation**: Requires ParaView and TTK
- **Features**: Representative cycle visualization for persistent homology

## Colored Point Cloud Visualization

### chromatic-tda
- **Link**: https://github.com/OnDraganov/chromatic-tda
- **Description**: Package for computing sixpack of persistence diagrams for colored point clouds
- **Applications**: 
  - Cells and their type information on tissue slices
  - 3D structures of materials composed of different atoms
- **Sixpack Contents**:
  - Kernel diagram
  - Domain diagram
  - Image diagram
  - Codomain diagram
  - Cokernel diagram
  - Relative persistence diagram
- **v1.1.8 New Feature**: Experimental feature extraction - extracting loops from barcodes
- **Constraints**: Suitable for hundreds to thousands of points in 2D or 3D space, 2-3 colors

## Multi-parameter Persistence Visualization

### RIVET
- **Link**: https://github.com/aj-alonso/rivet
- **Description**: Program for visualizing and analyzing bi-parameter persistent homology
- **Interface**: Interactive GUI
- **Features**: Persistence diagram computation and visualization for bi-parameter filtrations

## Mapper Algorithm Visualization

### kepler-mapper
- **Link**: https://github.com/scikit-tda/kepler-mapper
- **Documentation**: https://kepler-mapper.scikit-tda.org/en/latest/
- **Description**: Mapper algorithm implementation in Python for topological data visualization
- **Application Cases**: https://kepler-mapper.scikit-tda.org/en/latest/applications.html
- **Features**: 
  - Generates interactive HTML visualizations
  - Exploratory data analysis
  - High-dimensional data dimensionality reduction visualization

### Regional Ball Mapper
- **Link**: https://github.com/srudkin12/RegionalBallMapper
- **Paper**: https://arxiv.org/pdf/2601.00508
- **Description**: Regional ball variant of the Mapper algorithm

## Graph & Network Visualization

### Persistent Homology on Graphs Visualization Tool
- **Link**: https://github.com/USFDataVisualization/PersistentHomologyOnGraphs
- **Description**: Visualization tool for interactive work with undirected graphs using persistent homology
- **Features**: Interactive graph persistence analysis

## Knot and Topology Visualization

### KnotPlot
- **Link**: https://knotplot.com/
- **Description**: Powerful program for visualizing and manipulating mathematical knots in 3D and 4D
- **Content**: Mathematical visualization of knots and links

## Terrain Metaphor Visualization

### AYLA
- **Link**: https://tgda.osu.edu/
- **Description**: Collaborative visual analytics platform
- **Method**: Generates 2D terrain metaphor
- **Applications**: Visualize/explore high-dimensional molecular simulation data

### DENALI
- **Link**: https://tgda.osu.edu/
- **Description**: Tool for visualizing scalar functions defined on trees, graphs, and point clouds using terrain metaphor

## Graph Analysis Visualization

### TDA-on-graphs
- **Link**: https://github.com/OliviaMcGough/TDA-on-graphs
- **Description**: Applying Topological Data Analysis (TDA) to graph data
- **Features**: 
  - Computing persistent homology of flag complexes
  - Directed flag complexes
  - Flag tournaplexes
  - Dowker sink complexes
- **Feature**: Options to print all simplices in complexes

## Dynamic Data Visualization

### Vineyard Visualization
- **Link**: https://github.com/regalski/Wayne-State-TDA
- **Description**: Visualization of features discovered in fMRI data
- **Method**: Vineyard diagrams
- **Applications**: Time series analysis of persistent homology

### TMetaNet
- **Link**: https://github.com/Lihaogx/TMetaNet
- **Paper**: TMetaNet: Topological Meta-Learning Framework for Dynamic Link Prediction
- **Description**: Visualization of meta-learning parameter update model based on dynamic topological features

## Network Evolution Visualization

### tergm
- **Link**: https://github.com/statnet/tergm
- **Description**: Fit, simulate, and diagnose network evolution models based on exponential-family random graph models
- **Documentation**: https://rstudio-pubs-static.s3.amazonaws.com/383759_9d63861d14ec45e1a0f410b8e22b95ee.html

## 3D Visualization

### CoCone
- **Link**: https://tgda.osu.edu/
- **Description**: Surface reconstruction software

### HanTun
- **Link**: https://tgda.osu.edu/
- **Description**: Software for computing handle and tunnel loops in 3D models

### ShortLoop
- **Link**: https://tgda.osu.edu/
- **Description**: Computing shortest homology basis

## TDA Art & Applications

### TDArt
- **Link**: https://albanymath.github.io/comper25/schedule.html
- **Description**: Using persistent homology to recognize paintings
- **Applications**: Art analysis and identification

---

[Back to Home](README.md)
