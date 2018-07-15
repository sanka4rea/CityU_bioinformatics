+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Brain Connectomics"

weight = 50
# Project summary to display on homepage.
summary = "Including: Connectivity Analysis, Functional Magnetic Resonance Imaging, Diffusion Magnetic Resonance Imaging Analysis, Neuron Tracing."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/pheno/brain.jpg"

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

<img src="/img/tools/pheno/brain.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}



# Connectivity Analysis

<p align="justify">The functional organization of the **brain** is characterized by segregation and integration of information being processed. A central paradigm in modern neuroscience is that anatomical and functional connections between brain regions are organized in a way such that information processing is near optimal. Functional interactions seem to be provided by synchronized activity, both locally and between distant brain regions. Brain networks thus consist of spatially distributed but functionally connected regions that process information. [Source](https://www.hindawi.com/journals/cin/2012/412512/)

## <font color=#CD5555 face="黑体">Functional Brain Connectivity</font>

<p align="justify">Functional connectivity (FC) which is defined as the temporal dependency of neuronal activation patterns of anatomically separated brain regions. It reflects statistical dependencies between distinct and distant regions of information processing neuronal populations. Hence, it is basically a statistical concept which relies on such statistical measures as correlation, covariance, spectral coherence, or phase locking. Statistical dependencies are highly time dependent and fluctuate on multiple time scales ranging form milliseconds to seconds.

---

### BCT | Brain Connectivity Toolbox

<p align="justify">A Matlab toolbox for analysis of complex brain networks. The toolbox contains network analysis functions and complex brain network datasets. These measures are increasingly used to characterize structural and functional brain connectivity datasets.

[**Official Website**](https://sites.google.com/site/bctnet/)

**Publications**:

* (2010 Neuroimage) [Complex network measures of brain connectivity: uses and interpretations.](https://www.ncbi.nlm.nih.gov/pubmed/19819337)

**Institutions(s)**:

Black Dog Institute and School of Psychiatry, University of New South Wales, Sydney, Australia;

Mental Health Research Division, Queensland Institute of Medical Research, Brisbane, Australia

---

### WholeBrain

<p align="justify">Allows users to analyze, visualize, annotate and share whole-brain data at cellular resolution. WholeBrain supplies a method to generate brain maps containing data from neuron function, neuron identity, and connectivity. It quantifies and spatially maps multidimensional data from whole-brain experiments. It also compares results across experiments in a single standardized anatomical reference atlas.

[**Official Website**](https://github.com/tractatus/wholebrain)

**Publications**:

* (2017 Nat Neurosci) [An interactive framework for whole-brain maps at cellular resolution.](https://doi.org/10.1038/s41593-017-0027-7)

**Institutions(s)**:

Department of Neuroscience, Karolinska Institutet, Stockholm, Sweden;

Department of Neuroscience, Scripps Research Institute, Jupiter, FL, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Structural Brain Connectivity</font>

<p align="justify">Anatomical connectivity (AC), also called structural connectivity, which forms the connectome through synaptic contacts between neighboring neurons or fiber tracks connecting neuron pools in spatially distant brain regions. The whole set of such fiber tracks in the brain is called white matter. On short time scales (sec, min), anatomical connections are quite persistent and stable, while for longer time spans substantial plasticity may be observed.

---

### BNRR

<p align="justify">Infers flexibly changes in a network-valued random variable with a continuous trait. BNRR is a network–response regression model, which considers the brain network as an object-type response variable having conditional expectation changing flexibly. This method can be easily adapted to incorporate directed networks via two subsets of latent coordinates—for each brain region—modeling outgoing and incoming edges, respectively.

[**Official Website**](https://github.com/wangronglu/BNRR)

**Publications**:

* (2017 Bioinformatics) [Bayesian network–response regression.](https://academic.oup.com/bioinformatics/article/33/12/1859/2971437)

**Institutions(s)**:

Department of Statistical Science, Duke University, Durham, NC, USA; 

Department of Statistical Sciences, University of Padova, Padova, Italy

---

### WholeBrain

<p align="justify">Allows users to analyze, visualize, annotate and share whole-brain data at cellular resolution. WholeBrain supplies a method to generate brain maps containing data from neuron function, neuron identity, and connectivity. It quantifies and spatially maps multidimensional data from whole-brain experiments. It also compares results across experiments in a single standardized anatomical reference atlas.

[**Official Website**](https://github.com/tractatus/wholebrain)

**Publications**:

* (2017 Nat Neurosci) [An interactive framework for whole-brain maps at cellular resolution.](https://doi.org/10.1038/s41593-017-0027-7)

**Institutions(s)**:

Department of Neuroscience, Karolinska Institutet, Stockholm, Sweden;

Department of Neuroscience, Scripps Research Institute, Jupiter, FL, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Functional Magnetic Resonance Imaging (fMRI)

<p align="justify">The relationship between **brain structure and function** has been one of the centers of research in neuroimaging for decades. In recent years, diffusion tensor imaging (DTI) and functional magnetic resonance imaging (fMRI) techniques have been widely available and popular in cognitive and clinical neurosciences for examining the brain's white matter (WM) micro-structures and gray matter (GM) functions, respectively. [Source](https://www.ncbi.nlm.nih.gov/pubmed/24103849)

Image preprocessing, processing, 3D Image Analysis could be found in [**Bioimaging:**]({{< ref "too2/new_pheno/bioimaging.md" >}})

## 3D Image Surfacing

<p align="justify">The recent advent of increasingly affordable and powerful 3D scanning devices capable of capturing high resolution range data about real-world objects and environments has fueled research into effective 3D surface reconstruction techniques for rendering the raw point cloud data produced by many of these devices into a form that would make it usable in a variety of application domains.

---

### ANTs | Advanced Normalization Tools

<p align="justify">Computes high-dimensional mappings to capture the statistics of brain structure and function. ANTs allows users to organize, visualize and statistically explore large biomedical image sets. It integrates imaging modalities and related information in space and time, and works across species or organ systems with minimal customization. ANTs depends on the Insight ToolKit (ITK), a widely used medical image processing library to which ANTs developers contribute. ANTs can be used paired with ANTsR, an emerging tool supporting standardized multimodality image analysis. ANTs is popularly considered a state-of-the-art medical image registration and segmentation toolkit.

[**Official Website**](http://stnava.github.io/ANTs/)

**Publications**:

* (2011 Neuroimage) [A reproducible evaluation of ANTs similarity metric performance in brain image registration.](https://www.ncbi.nlm.nih.gov/pubmed/20851191)

**Institutions(s)**:

Penn Image Computing and Science Laboratory, University of Pennsylvania, Philadelphia, PA, USA

---

### Surfing | 3D image surfacing 

<p align="justify">Guides voxel selection for information mapping by using a cortical surface reconstruction. Surfing uses only voxels that are classified as grey matter based on an anatomical scan. It uses a surface-based geodesic distance metric to define neighbourhoods of voxels, and does not select voxels across a sulcus. The software employs a distance metric that takes into account the folded nature of the cortical sheet.

[**Official Website**](https://github.com/nno/surfing)

**Publications**:

* (2011 Neuroimage) [A comparison of volume-based and surface-based multi-voxel pattern analysis.](https://www.ncbi.nlm.nih.gov/pubmed/20621701)

**Institutions(s)**:

School of Psychology, Bangor University, UK; Institute of Cognitive Neuroscience, University College London, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Diffusion Magnetic Resonance Imaging Analysis

<p align="justify">The relationship between brain structure and function has been one of the centers of research in neuroimaging for decades. In recent years, diffusion tensor imaging (DTI) and functional magnetic resonance imaging (fMRI) techniques have been widely available and popular in cognitive and clinical neurosciences for examining the brain's white matter (WM) micro-structures and gray matter (GM) functions, respectively.

---

## <font color=#CD5555 face="黑体">Tractography</font>

<p align="justify">Tractography (or fiber tracking) consists of three-dimensional modeling of the preferential movement of water molecules in the form of fiber tracks from the tensor field information. This technique allows a new approach for the microarchitectural analysis of anisotropic structures such as nerves, white matter, and muscles. Many disorders have been studied including cervical myelopathy, carpal tunnel syndrome, nerve root compression, and nerve tumors.

---

### SlicerDMRI 

<p align="justify">Allows diffusion of imaging research in a clinical oncology setting and provides tools for end-to-end diffusion image analysis as well as interoperation with clinical imaging systems. SlicerDMRI is a suite of open-source software tools for diffusion magnetic resonance imaging (dMRI) research. The software is built upon and integrated with 3D Slicer, an NIH-supported open-source platform for medical image computing. SlicerDMRI is used for both neuroscience research and cancer imaging research.

[**Official Website**](http://dmri.slicer.org/)

**Publications**:

* (Cancer Res) [SlicerDMRI: Open Source Diffusion MRI Software for Brain Cancer Research.](http://cancerres.aacrjournals.org/content/77/21/e101)

**Institutions(s)**:

Brigham & Women's Hospital and Harvard Medical School, Boston, MA, USA; 

Isomics, Inc., Cambridge, MA, USA

---

### Dipy | Diffusion Imaging in Python

<p align="justify">Allows to study diffusion Magnetic Resonance Imaging (MRI) data. Dipy is a program allowing users to share their code and experiments. One of its objectives is to provide transparent implementations for all the different steps of the dMRI analysis with a uniform programming interface. It implements two interfaces for probabilistic Markov fiber tracking: (1) it allows the user to provide the distribution evaluated on a discrete set of possible tracking directions, and (2) it accommodates tracking methods where the fiber orientation distribution function (fODF) cannot be easily computed.

[**Official Website**](http://nipy.org/dipy/cite.html)

**Publications**:

* (2014 Front Neuroinform) [Dipy, a library for the analysis of diffusion MRI data.](https://www.ncbi.nlm.nih.gov/pubmed/24600385)

**Institutions(s)**:

Wolfson College, University of Cambridge, Cambridge, UK; 

Medical Research Council Cognition and Brain Sciences Unit, Cambridge, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Neuron Tracing

<p align="justify">The reconstruction of neuron morphology allows to investigate how the brain works, which is one of the foremost challenges in neuroscience. This process aims at extracting the neuronal structures from microscopic imaging data. The great advances in microscopic technologies have made a huge amount of data available at the micro-, or even lower, resolution where manual inspection is time consuming, prone to error and utterly impractical. This has motivated the development of methods to automatically trace the neuronal structures, a task also known as neuron tracing.

---

## NeurphologyJ | Neuron tracing : Bioimaging analysis

<p align="justify">A quantification method capable of automatically quantifying neuronal morphologies such as soma number and size, neurite length, and neurite branching complexity (which is highly related to the numbers of attachment points and ending points). NeurphologyJ is implemented as a plugin to ImageJ, an open-source Java-based image processing and analysis platform.

[**Official Website**](http://life.nctu.edu.tw/~ehwang/neurphologyJ.html)

**Publications**:

* (2011 BMC Bioinformatics) [NeurphologyJ: an automatic neuronal morphology quantification method and its application in pharmacological discovery.](https://www.ncbi.nlm.nih.gov/pubmed/21651810)

**Institutions(s)**:

Institute of Bioinformatics and Systems Biology, National Chiao Tung University, Hsinchu, Taiwan

---

## Vaa3D | 3D Visualization-Assisted Analysis


<p align="justify">Allows users to visualize 3D/4D/5D image and to analyze system for bioimages and surface objects. Vaa3D consists of a container of modules for 3D image analysis (cell segmentation, neuron tracing, brain registration, annotation, quantitative measurement and statistics) and data management. Moreover, this platform can be used for developing 3D image analysis algorithms for high-throughput processing.

[**Official Website**](http://home.penglab.com/proj/vaa3d/home/index.html)

**Publications**:

* (2018 BioRxiv) [DeepNeuron: An Open Deep Learning Toolbox for Neuron Tracing.](https://doi.org/10.1101/254318)

* (2018 BioRxiv) [Exploring morphological motifs for a single neuron based on multiple 3D reconstructions.](https://www.biorxiv.org/content/early/2018/01/26/254425)

**Institutions(s)**:

Allen Institute for Brain Science, Seattle, WA, USA


[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/phenomics-category)

[*Image Citation1*](http://blog.myesr.org/mri-reveals-the-human-connectome/)[*2*](https://www.moshimoshi-nippon.jp/zh-hant/80554)

---