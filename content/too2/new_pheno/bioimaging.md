+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Bioimaging"

weight = 10
# Project summary to display on homepage.
summary = "Including: Image preprocessing, Image processing, Microscopic Phenotype Analysis, Laser Scanning Microscopy, Conventional Fluorescence microscopy, Super-resolution Imaging, Cryo-EM."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/pheno/bioimage.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["phenomics"]

# Optional external URL for project (replaces project detail page).
#external_link = "https://cityu-bioinformatics.netlify.com/tools/seq_new/sequence alignment/"


# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"


+++
---

<img src="/img/tools/pheno/bioimage.jpg"  width="400" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Microscopic Phenotype Analysis

<p align="justify">**Microscopic phenotype analysis** deals with all tools usefull for describing, identifying or classifying phenotypes at microscopic scale. Microscopic sample can, for example, be cells or microscopic organisms (worms, parasites..) imaged by all kinds of microscopic devices.

## <font color=#CD5555 face="黑体">Microscopic Image Formats Management</font>

<p align="justify">Microscopy image formats management tools are used to convert image files into desired formats, add metadata, facilitate open-exchange, and more.

---

### OMERO | OME Remote Objects

<p align="justify">A software platform that enables access to and use of a wide range of biological data. OMERO uses a server-based middleware application to provide a unified interface for images, matrices and tables. OMERO's design and flexibility have enabled its use for light-microscopy, high-content-screening, electron-microscopy and even non-image-genotype data.

[**Official Website**](http://www.openmicroscopy.org/omero/)

**Publications**:

* (2012 Nat Methods) [OMERO: flexible, model-driven data management for experimental biology.](https://www.ncbi.nlm.nih.gov/pubmed/22373911)

**Institutions(s)**:

Wellcome Trust Centre for Gene Regulation and Expression, College of Life Sciences, University of Dundee, Dundee, Scotland, UK

---

### SCIFIO | SCientific Image Format Input and Output

<p align="justify">A library software to create extensible framework for the reading, writing, and translation of images. SCIFIO was designed to provide the architecture that will equally facilitate: i) the conversion of additional formats into supported open-exchange formats such as OME-TIFF and ii) the integration of additional scientific open-exchange formats. The extensible design of SCIFIO facilitates community contribution, the establishment of domain-specific metadata standards, and integration into a unified system capable of adapting to the demands of scientific imaging analysis.

[**Official Website**](http://scif.io/)

**Publications**:

* (2016 BMC Bioinformatics) [SCIFIO: an extensible framework to support scientific image formats.](https://www.ncbi.nlm.nih.gov/pubmed/27927161)

**Institutions(s)**:

Laboratory for Optical and Computational Instrumentation, University of Wisconsin at Madison, Madison, WI, USA;

Morgridge Institute for Research, Madison, WI, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">PheWAS</font>

<p align="justify">The genome-wide association study (GWAS) is a powerful approach for studying the genetic complexities of human disease. Unfortunately, GWASs often fail to identify clinically significant associations and describing function can be a challenge. GWAS is a phenotype-to-genotype approach. It is now possible to conduct a converse genotype-to-phenotype approach using extensive electronic medical records to define a phenome. This approach associates a single genetic variant with many phenotypes across the phenome and is called a phenome-wide association study (PheWAS).

---

### PheWAS | Phenome-wide association study


<p align="justify">Tests associations between a genetic variant or clinical factor of interest and a compendium of clinical outcomes or phenotypes. PheWAS finds disease-gene associations using ICD9 billing codes. It can serve to construct hypotheses around a variety of exposures. This tool implements a propensity score (PS) method for PS matching or PS adjustment. It employs a penalized maximum likelihood (PML) in logistic regression that can reduce bias in the parameter estimates.

[**Official Website**](https://github.com/PheWAS/PheWAS)

**Publications**:

* (2018 Bioinformatics) [Evaluating statistical approaches to leverage large clinical datasets for uncovering therapeutic and adverse medication effects.](https://doi.org/10.1093/bioinformatics/bty306)

* (2014 Bioinformatics) [R PheWAS: data analysis and plotting tools for phenome-wide association studies in the R environment.](https://www.ncbi.nlm.nih.gov/pubmed/24733291)

**Institutions(s)**:

Department of Biostatistics, Vanderbilt University Medical Center, Nashville, TN, USA;

Department of Biomedical Informatics, Vanderbilt University Medical Center, Nashville, TN, USA

---

### SPAtest

<p align="justify">Performs a score test for a single variant based on saddlepoint approximation single variant test in genetic associations. SPAtest is an R package implements in the fastspa package that can accurate calculate p-values even for extremely unbalanced case-control outcomes. It provides a scalable solution for this large-scale problem and contribute to finding genetic component of complex traits.

[**Official Website**](https://cran.r-project.org/web/packages/SPAtest/index.html)

**Publications**:

* (2017 Am J Hum Genet) [A Fast and Accurate Algorithm to Test for Binary Phenotypes and Its Application to PheWAS.](https://www.ncbi.nlm.nih.gov/pubmed/28602423)

**Institutions(s)**:

Department of Biostatistics, University of Michigan, Ann Arbor, MI, USA;

Center for Statistical Genetics, University of Michigan, Ann Arbor, MI, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Laser Scanning Microscopy

<p align="justify">Confocal microscopy is an established light microscopical technique for imaging fluorescently labeled specimens with significant three-dimensional structure. Applications of confocal microscopy in the biomedical sciences include the imaging of the spatial distribution of macromolecules in either fixed or living cells, the automated collection of 3D data, the imaging of multiple labeled specimens and the measurement of physiological events in living cells. The laser scanning confocal microscope continues to be chosen for most routine work although a number of instruments have been developed for more specific applications.

---

## <font color=#CD5555 face="黑体">FISH</font>

<p align="justify">Fluorescence in situ hybridization (FISH) is used to study the organization and the positioning of specific DNA sequences within the cell nucleus. Analyzing the data from FISH images is a tedious process that invokes an element of subjectivity.

---

### ImageJ

<p align="justify">Provides easy installation on arbitrary platforms and a simple user interface. ImageJ is a platform for biological image analysis and an open source Java image processing program inspired by NIH Image. The ImageJ community can communicate through an interdisciplinary forum where knowledge is disseminated and questions that might appear difficult to experts in one scientific field may be easily answered by an expert in another field.

[**Official Website**](https://imagej.net/Welcome)

**Publications**:

* (2017 BMC Bioinformatics) [ImageJ2: ImageJ for the next generation of scientific image data.](https://www.ncbi.nlm.nih.gov/pubmed/29187165)

**Institutions(s)**:

Laboratory for Optical and Computational Instrumentation, University of Wisconsin at Madison, Madison, WI, USA;

Morgridge Institute for Research, Madison, WI, USA

---

### GoIFISH 

<p align="justify">A widely applicable, user-friendly system tailored for the objective and semi-automated visualization, detection and quantification of genomic alterations and protein expression obtained from fluorescence in situ analysis. In a sample set of HER2-positive breast cancers GoIFISH is highly robust in visual analysis and its accuracy compares favorably to other leading image analysis methods.

[**Official Website**](https://sourceforge.net/projects/goifish/)

**Publications**:

* (2014 Genome Biol) [GoIFISH: a system for the quantification of single cell heterogeneity from IFISH images.](https://www.ncbi.nlm.nih.gov/pubmed/25168174)

**Institutions(s)**:

University of Cambridge, Cancer Research UK Cambridge Institute, Robinson Way, Cambridge, UK; 

Department of Genetics, Institute for Cancer Research, Oslo, Norway; 

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Colocalization Analysis</font>

<p align="justify">The measurement of colocalization requires images of two fluorophores that are aligned, with no cross talk, and that the intensities remain within the response range of the microscope. Quantitation depends upon differentiating between the presence and absence of fluorescence, and measurements should be made within biologically relevant regions of interest. Co-occurrence can be measured simply by area or with the M1 and M2 coefficients, and should be compared to random distributions.

---

### BioImageXD

<p align="justify">Analyzes, processes and visualizes multi-dimensional microscopy images. BioImageXD puts open-source computer science tools for three-dimensional visualization and analysis into the hands of all researchers, through a user-friendly graphical interface tuned to the needs of biologists. BioImageXD has no restrictive licenses or undisclosed algorithms and enables publication of precise, reproducible and modifiable workflows. It allows simple construction of processing pipelines and should enable biologists to perform challenging analyses of complex processes.

[**Official Website**](http://www.bioimagexd.net/)

**Publications**:

* (2012 Nat Methods) [BioImageXD: an open, general-purpose and high-throughput image-processing platform.](https://www.ncbi.nlm.nih.gov/pubmed/22743773)

**Institutions(s)**:

Department of Biochemistry and Food Chemistry, University of Turku, Turku, Finland

---

### ViBE-Z | Virtual Brain Explorer for Zebrafish

<p align="justify">An imaging and image analysis framework for virtual colocalization studies in larval zebrafish brains. ViBE-Z contains a database with precisely aligned gene expression patterns, an anatomical atlas, and a software. ViBE-Z software creates high-quality data sets through fusion of multiple confocal stacks, it aligns 3D gene or protein expression patterns of different zebrafish larvae of a given developmental stage to a common reference, and it stores the aligned patterns in the ViBE-Z database. Together with the anatomical segmentation (ViBE-Z atlas), this database allows users to explore the colocalization of all contained patterns in their anatomical context.

[**Official Website**](http://vibez.informatik.uni-freiburg.de/)

**Publications**:

* (2012 Nat Methods) [ViBE-Z: a framework for 3D virtual colocalization analysis in zebrafish larval brains.](https://www.ncbi.nlm.nih.gov/pubmed/22706672)

**Institutions(s)**:

Computer Science Department, Albert-Ludwigs-University Freiburg, Freiburg, Germany;

BIOSS Centre for Biological Signalling Studies, Freiburg, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">3D Image Analysis</font>

<p align="justify">Find and compare the best bioinformatics software tools for analyzing 3D laser scanning microscopy images. Tools are ranked by the biomedical research community.

---

### u-track

<p align="justify">A multiple-particle tracking Matlab software that is designed to (1) track dense particle fields, (2) close gaps in particle trajectories resulting from detection failure, and (3) capture particle merging and splitting events resulting from occlusion or genuine aggregation and dissociation events. Its core is based on formulating correspondence problems as linear assignment problems and searching for a globally optimal solution.

[**Official Website**](https://www.utsouthwestern.edu/labs/danuser/software/)

**Publications**:

* (2008 Nat Methods) [Robust single-particle tracking in live-cell time-lapse sequences.](https://www.ncbi.nlm.nih.gov/pubmed/18641657)

**Institutions(s)**:

Department of Cell Biology, The Scripps Research Institute, La Jolla, CA, USA

---

### UltraTracer

<p align="justify">Designed to extend any base neuron-tracing algorithm to be able to trace virtually unlimited data volumes. UltraTracer was applied to neuron-tracing algorithms with different design principles and tested on challenging human and mouse neuron datasets that have hundreds of billions of voxels. Results indicate that UltraTracer is scalable, accurate, and about 3 to 6 times more efficient compared to other state-of-the-art approaches.

[**Official Website**](https://github.com/Vaa3D/vaa3d_tools/tree/master/released_plugins/v3d_plugins/ultratracer)

**Publications**:

* (2017 Nat Methods) [Automatic tracing of ultra-volumes of neuronal images](https://www.ncbi.nlm.nih.gov/pubmed/28362437)

**Institutions(s)**:

Allen Institute for Brain Science, Seattle, WA, USA; 

Erasmus University Medical Center Rotterdam, Rotterdam, Netherlands; 

Janelia Research Campus, Howard Hughes Medical Institute, Ashburn, VA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Conventional Fluorescence microscopy

<p align="justify">The wide-field fluorescence microscope is a modification of the compound optical microscope, arranged to admit light of a selected wavelength to fluorescently labeled specimens and to image them through the emitted radiation. Since fluorescence emission has a lifetime in the nanosecond scale, continuous excitation is needed to collect an image having fluorescence as contrast mechanism. In a classical wide-field optical fluorescence microscope, the light source of a fluorescent microscope is a gas-vapor arc lamp, using either a discrete (Mercury) or a continuous (Xenon) light-emission spectrum.

---

## <font color=#CD5555 face="黑体">High-throughput Screening</font>

Millions of cells are present in thousands of images created in high-throughput screening (HTS). Biologists could classify each of these cells into a phenotype by visual inspection. But in the presence of millions of cells this visual classification task becomes infeasible. Biologists train classification models on a few thousand visually classified example cells and iteratively improve the training data by visual inspection of the important misclassified phenotypes.

---

### histoCAT | HIStology TOpography Cytometry Analysis Toolbox

<p align="justify">Uses a computational multiplexed image cytometry analysis toolbox to enable the interactive, quantitative, and comprehensive exploration of phenotypes of individual cells, cell-to-cell interactions, microenvironments, and morphological structures within intact tissues. miCAT will be useful in all areas of tissue-based research.

[**Official Website**](https://github.com/BodenmillerGroup/histoCAT)

**Publications**:

* (2017 Nat Methods) [histoCAT: analysis of cell phenotypes and interactions in multiplex image cytometry data.](https://www.ncbi.nlm.nih.gov/pubmed/28783155)

---

### CellProfiler

<p align="justify">A free, open-source system designed for flexible, high-throughput cell image analysis. CellProfiler can address a variety of biological questions quantitatively, including standard assays (for example, cell count, size, per-cell protein levels) and complex morphological assays (for example, cell/organelle shape or subcellular patterns of DNA or protein staining).

[**Official Website**](http://cellprofiler.org/)

**Publications**:

* (2006 Genome Biol) [CellProfiler: image analysis software for identifying and quantifying cell phenotypes.](https://www.ncbi.nlm.nih.gov/pubmed/17076895)

**Institutions(s)**:

Whitehead Institute for Biomedical Research, Cambridge, MA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Cell Phenotyping</font>

<p align="justify">Find and compare the best bioinformatics software tools for phenotying cells using conventional fluorescence microscopy images. Tools are ranked by the biomedical research community.

---

### PhenoRipper

<p align="justify">Allows user to explore high-content microscopy images. PhenoRipper assists users in comparison of images and based on similarity of image phenotypes. It uses cluster analysis to identify superblock types, representing the most common block type co-occurrence patterns. It profiles each image by the frequency of occurrence of superblock types.

[**Official Website**](http://awlab.ucsf.edu/Web_Site/PhenoRipper/default.htm)

**Publications**:

* (2012 Nat Methods) [PhenoRipper: software for rapidly profiling microscopy images.](https://www.ncbi.nlm.nih.gov/pubmed/22743764)

**Institutions(s)**:

Green Center for Systems Biology, University of Texas Southwestern Medical Center, Dallas, TX, USA; 

Department of Pharmacology, University of Texas Southwestern Medical Center, Dallas, TX, USA

---

### histoCAT | HIStology TOpography Cytometry Analysis Toolbox

<p align="justify">Uses a computational multiplexed image cytometry analysis toolbox to enable the interactive, quantitative, and comprehensive exploration of phenotypes of individual cells, cell-to-cell interactions, microenvironments, and morphological structures within intact tissues. miCAT will be useful in all areas of tissue-based research.

[**Official Website**](https://github.com/BodenmillerGroup/histoCAT)

**Publications**:

* (2017 Nat Methods) [histoCAT: analysis of cell phenotypes and interactions in multiplex image cytometry data.](https://www.ncbi.nlm.nih.gov/pubmed/28783155)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Super-resolution Imaging

<p align="justify">In recent years, **super-resolution** optical imaging techniques have been developed to overcome the diffraction limit in fluorescence microscopy. Among these techniques, methods based on stochastic switching and localization of individual molecules, such as stochastic optical reconstruction microscopy (STORM) ([Rust et al. 2006](https://www.ncbi.nlm.nih.gov/pubmed/16896339)) and (fluorescent) photoactivated localization microscopy ((F)PALM), achieve sub-diffraction-limit resolutions by sequentially imaging and localizing fluorescent emitters in the sample. [Source](https://www.ncbi.nlm.nih.gov/pubmed/25431749)

---

## <font color=#CD5555 face="黑体">Morphometric Analysis</font>

<p align="justify">Find and compare the best bioinformatics software tools for analysing sample morphology on super-resolution microscopy images. Tools are ranked by the biomedical research community.

---

### MIB | Microscopy Image Browser

<p align="justify">Serves for effective segmentation of multidimensional datasets. MIB can recognize several number of imaging formats and offers a variety of image processing tools. It also simplifies utilization and quantification of acquired data. It permits users to segment large datasets, to realize 3D visualization, and to quantify images and models. Its parameters enable users to insert plugin s to customize the program for specific needs.

[**Official Website**](http://mib.helsinki.fi/)

**Publications**:

* (2016 PLoS Biol) [Microscopy Image Browser: A Platform for Segmentation and Analysis of Multidimensional Datasets.](https://www.ncbi.nlm.nih.gov/pubmed/26727152)

**Institutions(s)**:

Electron Microscopy Unit, Institute of Biotechnology, University of Helsinki, Helsinki, Finland

---

### BioImageXD

<p align="justify">Analyzes, processes and visualizes multi-dimensional microscopy images. BioImageXD puts open-source computer science tools for three-dimensional visualization and analysis into the hands of all researchers, through a user-friendly graphical interface tuned to the needs of biologists. BioImageXD has no restrictive licenses or undisclosed algorithms and enables publication of precise, reproducible and modifiable workflows. It allows simple construction of processing pipelines and should enable biologists to perform challenging analyses of complex processes.

[**Official Website**](http://www.bioimagexd.net/)

**Publications**:

* (2012 Nat Methods) [BioImageXD: an open, general-purpose and high-throughput image-processing platform.](https://www.ncbi.nlm.nih.gov/pubmed/22743773)

**Institutions(s)**:

Department of Biochemistry and Food Chemistry, University of Turku, Turku, Finland

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Single Molecule Detection and Localization</font>

<p align="justify">The quality of super-resolution images obtained by single-molecule localization microscopy (SMLM) depends largely on the software used to detect and accurately localize point sources.

---

### rapidSTORM

<p align="justify">A localization microscopy evaluation program. rapidSTORM is designed to find and precisely localize fluorophores in super-resolvable movies such as those generated by the PALM or dSTORM techniques.

[**Official Website**](https://github.com/stevewolter/rapidSTORM)

**Publications**:

* (2012 Nat Methods) [rapidSTORM: accurate, fast open-source software for localization microscopy.](https://www.ncbi.nlm.nih.gov/pubmed/23132113)

**Issues**:

https://github.com/stevewolter/rapidSTORM/issues

---

### ViSP

<p align="justify">An interactive, freely available, cross-platform 3D localization representation tool. ViSP advances the interpretation of 3D single-particle super-resolution data (and the features are also compatible with 2D data sets). With an ever-growing number of 3D microscopy techniques and applications available, the features that ViSP offers are of critical importance in the greater microscopy research community.

[**Official Website**](https://science.institut-curie.org/research/multiscale-physics-biology-chemistry/umr168-physical-chemistry/team-dahan/softwares/visp-software-2/)

**Publications**:

* (2013 Nat Methods) [ViSP: representing single-particle localizations in three dimensions.](https://www.ncbi.nlm.nih.gov/pubmed/23900246)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Cryo-EM

<p align="justify">**Cryo-electron microscopy** of biological matter has made important advances in the past decades. It has become a research tool that further expands the scope of structural research into unique areas of cell and molecular biology, and it could augment the materials research portfolio in the study of soft and hybrid materials.

## <font color=#CD5555 face="黑体">Neuron Tracing</font>

Find and compare the best bioinformatics software tools for tracing neurons on cryo-Electron microscopy images. Tools are ranked by the biomedical research community.

---

### UltraTracer

<p align="justify">Designed to extend any base neuron-tracing algorithm to be able to trace virtually unlimited data volumes. UltraTracer was applied to neuron-tracing algorithms with different design principles and tested on challenging human and mouse neuron datasets that have hundreds of billions of voxels. Results indicate that UltraTracer is scalable, accurate, and about 3 to 6 times more efficient compared to other state-of-the-art approaches.

[**Official Website**](https://github.com/Vaa3D/vaa3d_tools/tree/master/released_plugins/v3d_plugins/ultratracer)

**Publications**:

* (2017 Nat Methods) [Automatic tracing of ultra-volumes of neuronal images](https://www.ncbi.nlm.nih.gov/pubmed/28362437)

**Institutions(s)**:

Allen Institute for Brain Science, Seattle, WA, USA; 

Erasmus University Medical Center Rotterdam, Rotterdam, Netherlands

---

### webKnossos

<p align="justify">Allows 3D image data annotation in various 3D image analysis settings in connectomics and other fields. webKnossos is an in-browser annotation tool. The software accelerates human 3D data interaction for electron microscopic (EM)-based connectomics in browser by about 4- to 13-fold, which likely saturates human interaction speed with 3D EM data of nervous tissue using flight mode.

[**Official Website**](https://webknossos.org/)

**Publications**:

* (2017 Nat Methods) [webKnossos: efficient online 3D data annotation for connectomics.](https://www.ncbi.nlm.nih.gov/pubmed/28604722)

**Institutions(s)**:

Department of Connectomics, Max Planck Institute for Brain Research, Frankfurt, Germany; 

Scalable minds UG (haftungsbeschränkt) & Co. KG, Potsdam, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Single Particle Analysis</font>

<p align="justify">Single particle electron microscopy is a versatile technique for the structural analysis of protein complexes in near-native conditions. While tremendous progress has been made during the past few decades in techniques for specimen preparation, imaging, and image analysis, the field is still in development.

---

### EMAN 

<p align="justify">Reconstructs single particle from electron cryo-microscopy (cryoEM) images. EMAN is capable of processing large data sets and focuses on processing data from transmission electron microscopes. The application is mainly dedicated to single particle rebuilding but includes more than 40 functionalities allowing users to perform helical reconstruction or single particle tomography as well as interacting with external software such as Frealign or Relion.

[**Official Website**](http://blake.bcm.tmc.edu/EMAN2/)

**Publications**:

* (2016 Methods Enzymol) [Single-Particle Refinement and Variability Analysis in EMAN2.1.](https://www.ncbi.nlm.nih.gov/pubmed/27572727)

* (1999 J Struct Biol) [EMAN: semiautomated software for high-resolution single-particle reconstructions.](https://www.ncbi.nlm.nih.gov/pubmed/10600563)

**Institutions(s)**:

National Center for Macromolecular Imaging, The Verna and Marrs McLean Department of Biochemistry and Molecular Biology, Baylor College of Medicine, One Baylor Plaza, Houston, TX, USA
---

### EMRinger

<p align="justify">A tool that assesses the precise fitting of an atomic model into the map during refinement and shows how radiation damage alters scattering from negatively charged amino acids. EMRinger is useful for monitoring progress in resolving and modeling high-resolution features in cryo-EM.

[**Official Website**](https://github.com/fraser-lab/EMRinger)

**Publications**:

* (2015 Nat Methods) [EMRinger: side chain-directed model and map validation for 3D cryo-electron microscopy.](https://www.ncbi.nlm.nih.gov/pubmed/26280328)

**Institutions(s)**:

Department of Bioengineering and Therapeutic Sciences, University of California, San Francisco, San Francisco, CA, USA;

Graduate Group in Biophysics, University of California, San Francisco, San Francisco, CA, USA


[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/phenomics-category)

[*Image Citation*](https://www.amazon.com/Microscope-OMAX-40X-2000X-Mechanical-Homeschool/dp/B006MX03Q0)

---
