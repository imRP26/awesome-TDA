# awesome-TDA

A curated list of [topological data analysis (TDA)](https://en.wikipedia.org/wiki/Topological_data_analysis) resources and links.

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms)
    - [Morse-Smale complex](#Morse-Smale-complex)
    - [Persistent homology computation](#Persistent-homology-computation)
    - [Persistent cohomology computation](#Persistent-cohomology-computation)
    - [Reeb graph](#Reeb-graph)
    - [Vineyards](#Vineyards)
    - [Zigzag persistent homology ](#Zigzag-persistent-homology )
  - [Articles](#articles)
  - [Books](#books)
  - [Courses](#courses)
  - [Other lists](#other-lists)
- [Tools](#tools)
- [Frameworks and Libs](#frameworks-and-libs)
  - [C++](#c++)
  - [Java](#java)
  - [Python](#python)
  - [R](#r)
  - [Spark](#spark)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Mailing lists](#mailing-lists)
  - [Web-tools](#web-tools)
  - [Web-sites](#web-sites)
- [Contributing](#contributing)
- [License](#license)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms
#### Morse-Smale complex
#### Persistent homology computation
#### Persistent cohomology computation
#### Reeb graph
#### Vineyards
#### Zigzag persistent homology

### Articles

### Books
- [Topological and Statistical Methods for Complex Data]() Tackling Large-Scale, High-Dimensional, and Multivariate Data Spaces -  Editors: Bennett, Janine, Vivodtzev, Fabien, Pascucci, Valerio (Eds.) 
  - [About this book] This book contains papers presented at the Workshop on the Analysis of Large-scale, High-Dimensional, and Multi-Variate Data Using Topology and Statistics, held in Le Barp, France, June 2013. It features the work of some of the most prominent and recognized leaders in the field who examine challenges as well as detail solutions to the analysis of extreme scale data.

    The book presents new methods that leverage the mutual strengths of both topological and statistical techniques to support the management, analysis, and visualization of complex data. It covers both theory and application and provides readers with an overview of important key concepts and the latest research trends.

    Coverage in the book includes multi-variate and/or high-dimensional analysis techniques, feature-based statistical methods, combinatorial algorithms, scalable statistics algorithms, scalar and vector field topology, and multi-scale representations. In addition, the book details algorithms that are broadly applicable and can be used by application scientists to glean insight from a wide range of complex data sets.

- [Topological Data Analysis for Scientific Visualization](https://www.springer.com/gp/book/9783319715063)  Authors: Tierny, Julien 
  - [About this book] Combining theoretical and practical aspects of topology, this book provides a comprehensive and self-contained introduction to topological methods for the analysis and visualization of scientific data.

    Theoretical concepts are presented in a painstaking but intuitive manner, with numerous high-quality color illustrations. Key algorithms for the computation and simplification of topological data representations are described in detail, and their application is carefully demonstrated in a chapter dedicated to concrete use cases.

    With its fine balance between theory and practice, "Topological Data Analysis for Scientific Visualization" constitutes an appealing introduction to the increasingly important topic of topological data analysis for lecturers, students and researchers.


- [Topological Methods in Data Analysis and Visualization](https://www.springer.com/gp/book/9783642150135) Theory, Algorithms, and Applications - Editors: Pascucci, V., Tricoche, X., Hagen, H., Tierny, J. (Eds.) 
  - [About this book] Topology-based methods are of increasing importance in the analysis and visualization of datasets from a wide variety of scientific domains such as biology, physics, engineering, and medicine. Current challenges of topology-based techniques include the management of time-dependent data, the representation large and complex datasets, the characterization of noise and uncertainty, the effective integration of numerical methods with robust combinatorial algorithms, etc. While there is an increasing number of high-quality publications in this field, many fundamental questions remain unsolved. New focused efforts are needed in a variety of techniques ranging from the theoretical foundations of topological models, algorithmic issues related to the representation power of computer-based implementations as well as their computational efficiency, user interfaces for presentation of quantitative topological information, and the development of new techniques for systematic mapping of science problems in topological constructs that can be solved computationally. The editors have brought together the most prominent and best recognized researchers in the field of topology-based data analysis and visualization for a joint discussion and scientific exchange of the latest results in the field. The 2009 "TopoInVis" workshop in Snowbird, Utah, follows the two successful workshops in 2005 (Budmerice, Slovakia) and 2007 (Leipzig, Germany).

- [Topological Methods in Data Analysis and Visualization II](https://www.springer.com/gp/book/9783642231742)  Theory, Algorithms, and Applications - Editors: Peikert, R., Hauser, H., Carr, H., Fuchs, R. (Eds.) 
  - [About this book] When scientists analyze datasets in a search for underlying phenomena, patterns or causal factors, their first step is often an automatic or semi-automatic search for structures in the data. Of these feature-extraction methods, topological ones stand out due to their solid mathematical foundation. Topologically defined structures—as found in scalar, vector and tensor fields—have proven their merit in a wide range of scientific domains, and scientists have found them to be revealing in subjects such as physics, engineering, and medicine.

    Full of state-of-the-art research and contemporary hot topics in the subject, this volume is a selection of peer-reviewed papers originally presented at the fourth Workshop on Topology-Based Methods in Data Analysis and Visualization, TopoInVis 2011, held in Zurich, Switzerland. The workshop brought together many of the leading lights in the field for a mixture of formal presentations and discussion. One topic currently generating a great deal of interest, and explored in several chapters here, is the search for topological structures in time-dependent flows, and their relationship with Lagrangian coherent structures. Contributors also focus on discrete topologies of scalar and vector fields, and on persistence-based simplification, among other issues of note. The new research results included in this volume relate to all three key areas in data analysis—theory, algorithms and applications.

- [Topological Methods in Data Analysis and Visualization III](https://www.springer.com/gp/book/9783319040981)  Theory, Algorithms, and Applications - Editors: Bremer, P.-T., Hotz, I., Pascucci, V., Peikert, R. (Eds.) 
 - [About this book] his collection of peer-reviewed conference papers provides comprehensive coverage of cutting-edge research in topological approaches to data analysis and visualization. It encompasses the full range of new algorithms and insights, including fast homology computation, comparative analysis of simplification techniques, and key applications in materials and medical science. The volume also features material on core research challenges such as the representation of large and complex datasets and integrating numerical methods with robust combinatorial algorithms.

    Reflecting the focus of the TopoInVis 2013 conference, the contributions evince the progress currently being made on finding experimental solutions to open problems in the sector. They provide an inclusive snapshot of state-of-the-art research that enables researchers to keep abreast of the latest developments and provides a foundation for future progress. With papers by some of the world’s leading experts in topological techniques, this volume is a major contribution to the literature in a field of growing importance with applications in disciplines that range from engineering to medicine.
 
- [Topological Methods in Data Analysis and Visualization IV](https://www.springer.com/gp/book/9783319446820)  Theory, Algorithms, and Applications -  Editors: Carr, Hamish, Garth, Christoph, Weinkauf, Tino (Eds.) 
 - [About this book] This book presents contributions on topics ranging from novel applications of topological analysis for particular problems, through studies of the effectiveness of modern topological methods, algorithmic improvements on existing methods, and parallel computation of topological structures, all the way to mathematical topologies not previously applied to data analysis.

    Topological methods are broadly recognized as valuable tools for analyzing the ever-increasing flood of data generated by simulation or acquisition. This is particularly the case in scientific visualization, where the data sets have long since surpassed the ability of the human mind to absorb every single byte of data.

    The biannual TopoInVis workshop has supported researchers in this area for a decade, and continues to serve as a vital forum for the presentation and discussion of novel results in applications in the area, creating a platform to disseminate knowledge about such implementations throughout and beyond the community.

    The present volume, resulting from the 2015 TopoInVis workshop held in Annweiler, Germany, will appeal to researchers in the fields of scientific visualization and mathematics, domain scientists with an interest in advanced visualization methods, and developers of visualization software systems.

- [Topology-based Methods in Visualization](https://www.springer.com/gp/book/9783540708223)  Editors: Hauser, Helwig, Hagen, Hans, Theisel, Holger (Eds.) 
  - [About this book] Enabling insight into large and complex datasets is a prevalent theme in visualization research for which different approaches are pursued.

    Topology-based methods are built on the idea of abstracting characteristic structures such as the topological skeleton from the data and to construct the visualizations accordingly. There are currently new demands for and renewed interest in topology-based visualization solutions. This book presents 13 peer-reviewed papers as written results from the 2005 workshop “Topology-Based Methods in Visualization” that was initiated to enable additional stimulation in this field. It contains a longer chapter dedicated to a survey of the state-of-the-art, as well as a great deal of original work by leading experts that has not been published before, spanning both theory and applications. It captures key concepts and novel ideas and serves as an overview of current trends in topology-based visualization research.

### Courses
- [Computational Topology and Data Analysis](http://web.cse.ohio-state.edu/~dey.8/course/CTDA/CTDA.html)

### Other lists

## Tools
- [TdaToolbox](https://github.com/Coricos/TdaToolbox)
  - [3DShape] - This notebook gives a simple example of how to handle three-dimensional shapes. The whole example is based on the height as filtration function, so not invariant in space. However, it gives a pretty good idea of what the output of a topological analysis may give.
  - [ToMaTo Clustering] - This notebook rather focus on a specific strength of TDA: its robustness to detect centroids in dataset, along with its ability to record the relationships between each point, enabling us to retrace the whole structure of the centroids. Examples are provided in the notebook.


- [TTk](https://topology-tool-kit.github.io/index.html) - The Topology ToolKit is an open-source library and software collection for topological data analysis in scientific visualization. TTK can handle scalar data defined either on regular grids or triangulations, either in 2D or in 3D. It provides a substantial collection of generic, efficient and robust implementations of key algorithms in topological data analysis.

## Frameworks and Libs

### C++
- [Ctl](https://github.com/appliedtopology/ctl) - This C++11 library provides a set of generic tools for:
  - Building Neighborhood Graphs
  - Building Cellular Complexes
  - Computing [persistent] homology over finite fields
  - Parallel algorithm(s) for homology

- [Dionysus](http://mrzv.org/software/dionysus/) - Dionysus is a C++ library for computing persistent homology. It provides implementations of the following algorithms:
  - Persistent homology computation 
  - Vineyards (C++ only)
  - Persistent cohomology computation 
  - Zigzag persistent homology 

- [GUDHI](http://gudhi.gforge.inria.fr/) - The GUDHI library is a generic open source C++ library, with a Python interface, for Topological Data Analysis (TDA) and Higher Dimensional Geometry Understanding. The library offers state-of-the-art data structures and algorithms to construct simplicial complexes and compute persistent homology.

- [TDA](https://cran.r-project.org/web/packages/TDA/) - tools for the statistical analysis of persistent homology and for density clustering. For that, this package provides an R interface for the efficient algorithms of the C++ libraries [GUDHI](http://gudhi.gforge.inria.fr/), [Dionysus](http://www.mrzv.org/software/dionysus/), and [PHAT](https://bitbucket.org/phat-code/phat/). This package also implements the methods in Fasy et al. [(2014)](doi:10.1214/14-AOS1252) and Chazal et al. [(2014)](doi:10.1145/2582112.2582128) for analyzing the statistical significance of persistent homology features.

### Java
- [JavaPlex](https://github.com/appliedtopology/javaplex) - Persistent Homology and Topological Data Analysis Library - The JavaPlex library implements persistent homology and related techniques from computational and applied topology, in a library designed for ease of use, ease of access from Matlab and java-based systems, and ease of extensions for further research projects and approaches. JavaPlex is mainly developed by the Computational Topology workgroup at Stanford University, and is based on previous similar packages from the same group.

### Python
- [KeplerMapper](https://github.com/MLWave/kepler-mapper) - This is a Python implementation of the TDA Mapper algorithm for visualization of high-dimensional data. For complete documentation, see https://kepler-mapper.scikit-tda.org.
KeplerMapper employs approaches based on the Mapper algorithm (Singh et al.) as first described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition".
KeplerMapper can make use of Scikit-Learn API compatible cluster and scaling algorithms.

- [kohonen](https://github.com/lmjohns3/kohonen) - This module contains some basic implementations of Kohonen-style vector quantizers: Self-Organizing Map (SOM), Neural Gas, and Growing Neural Gas. Kohonen-style vector quantizers use some sort of explicitly specified topology to encourage good separation among prototype "neurons".

- [mogutda](https://github.com/stephenhky/MoguTDA) - mogutda contains Python codes that demonstrate the numerical calculation of algebraic topology in an application to topological data analysis (TDA). Its core code is the numerical methods concerning implicial complex, and the estimation of homology and Betti numbers. mogutda runs in Python 2.7, 3.5, and 3.6.

- [openTDA](https://github.com/outlace/OpenTDA) - Open source Python library for topological data analysis (TDA)

- [Python Mapper](http://danifold.net/mapper/introduction.html)Python Mapper is a realization of this toolchain, written by Daniel Müllner and Aravindakshan Babu. It is open source software and is released under the GNU GPLv3 license. 
There is also a company, Ayasdi, which was founded by Gurjeet Singh, Gunnar Carlsson and Harlan Sexton and whose main product, the [Ayasdi Iris software](https://www.ayasdi.com/solutions/clinical-variation-management/), has the Mapper algorithm at its core. Ayasdi also issues academic trial licenses.

- [Scikit-TDA](https://scikit-tda.org/) - Scikit-TDA is a home for compatible TDA Python libraries intended for non-topologists. This project aims to provide a curated library of TDA Python tools that are widely usable and easily approachable.
It is structured so that each package can stand alone or be used as part of the scikit-tda bundle.
Current packages available:
  - [Ripser] - Data to diagrams in one line
  - [Persim] - Easy Persistence Images
  - [UMAP] - Mathematically justified dimensionality reduction
  - [Kepler Mapper] - Mapper framework integrated into sklearn
  - [TaDAsets] - Constructors for common data sets for demonstrating TDa.

- [scTDA](https://github.com/CamaraLab/scTDA) - scTDA is an object oriented python library for topological data analysis of high-throughput single-cell RNA-seq data. It includes tools for the preprocessing, analysis, and exploration of single-cell RNA-seq data based on topological representations.

### R
- [TDAmapper](https://github.com/paultpearson/TDAmapper/) - Topological Data Analysis using Mapper - An R package for using discrete Morse theory to analyze a data set using the Mapper algorithm described in G. Singh, F. Memoli, G. Carlsson (2007)

### Spark

- [Spark Mapper](https://github.com/log0ymxm/spark-mapper) - Mapper is a topological data anlysis technique for estimating a lower dimensional simplicial complex from a dataset. It was initially described in the paper "Topological Methods for the Analysis of High Dimensional Data Sets and 3D Object Recognition."

- [spark-tda](https://github.com/ognis1205/spark-tda) - The scalable topological data analysis package for Apache Spark. This project aims to implement the following features:
  - [ Scalable Mapper Implemented as Reeb Diagrams, i.e., Reeb Cosheaves]
  - [Scalable Mapper Implementation]
  - [Scalable Multiscale Mapper Implementation]
  - [Scalable Tower Computation for Multiscale Mapper]
  - [Scalable Persistent Homology Computation on Top of Apache Spark]
  
  
  
## License

`awesome-TDA by [@FatemehTarashi](https://github.com/FatemehTarashi)
