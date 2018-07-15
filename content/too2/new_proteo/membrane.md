+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Membrane Protein"

weight = 50
# Project summary to display on homepage.
summary = "Including: Membrane Protein Analysis, FRAP."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/protein/membrane.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["proteomics"]

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

<img src="/img/tools/protein/membrane.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Membrane Protein Analysis

<p align="justify">**Membrane and transmembrane proteins** are key component of cell signaling. Their configuration, folding, or activity depend on several biochemical factors that can be predicted by specific software.

---

## <font color=#CD5555 face="黑体">Membrane Simulation</font>

<p align="justify">Molecular dynamics (MD) simulations have had a profound impact on studies of membrane proteins during past two decades, but the accuracy of MD simulations of membranes is limited by the quality of membrane models and the applied force fields. Membrane models used in MD simulations mostly contain one kind of lipid molecule. This is far from reality, for biological membranes always contain more than one kind of lipid molecule. Moreover, the lipid composition and their distribution are functionally important. As a result, there is a necessity to prepare more realistic lipid membranes containing different types of lipids at physiological concentrations.

---

### CHARMM-GUI Membrane Builder | Membrane simulation : Membrane protein analysis

<p align="justify">Helps user to generate a series of CHARMM inputs necessary to build a protein/membrane complex for molecular dynamics simulations. CHARMM-GUI Membrane Builder helps a wide range of scientists who simulate complex lipid membranes, both with and without peptides and proteins. It assists user in production of ligand force field (FF) parameter, structure, and other necessary files for various ligand-containing biomolecular simulations.

[**Official Website**](http://www.charmm-gui.org/?doc=input/membrane)

**Publications**:

* (2017 J Comput Chem) [CHARMM-GUI ligand reader and modeler for CHARMM force field generation of small molecules.](https://www.ncbi.nlm.nih.gov/pubmed/28497616)

**Institutions(s)**:

<p align="justify">Department of Biological Sciences and Bioengineering Program, Lehigh University, Bethlehem, PA, USA; Leadership Computing Facility, Argonne National Laboratory, Argonne, IL, USA

---

## <font color=#CD5555 face="黑体">Transmembrane Beta-barrel Prediction</font>

<p align="justify">β-Barrel membrane proteins are found in the outer membrane of gram-negative bacteria, mitochondria, and chloroplasts. They are important for pore formation, membrane anchoring, and enzyme activity. These proteins are also often responsible for bacterial virulence.

---

### PROFtmb | Transmembrane beta-barrel prediction : Membrane protein analysis

<p align="justify">Predicts transmembrane beta-barrel (TMB) proteins in Gram-negative bacteria. PROFtmb was tested on a representative set of known TMB and non-TMB proteins. It detects 50% of TMBs at 80% accuracy (z-score>=10) and 70% of TMBs at 35% accuracy (z-score >= 6). The tool uses a Hidden Markov Model (HMM) whose parameters are trained on a set of labelled sequence profiles, and which accepts sequence profiles as input for prediction.

[**Official Website**](https://open.predictprotein.org/)

**Publications**:

* (2006 Nucleic Acids Res) [PROFtmb: a web server for predicting bacterial transmembrane beta barrel proteins.](https://www.ncbi.nlm.nih.gov/pubmed/16844988)

**Institutions(s)**:

<p align="justify">This work was supported by grant R01-LM07329-01 from the National Library of Medicine.

---

### PRED-TMBB | Transmembrane beta-barrel prediction : Membrane protein analysis

<p align="justify">A web server which is capable of predicting the transmembrane strands and the topology of beta-barrel outer membrane proteins of Gram-negative bacteria. The method is based on a Hidden Markov Model, trained according to the Conditional Maximum Likelihood criterion.

[**Official Website**](http://bioinformatics.biol.uoa.gr/PRED-TMBB/)

**Publications**:

* (2004 Nucleic Acids Res) [PRED-TMBB: a web server for predicting the topology of beta-barrel outer membrane proteins.](https://www.ncbi.nlm.nih.gov/pubmed/15215419)

**Institutions(s)**:

<p align="justify">Department of Cell Biology and Biophysics, Faculty of Biology, University of Athens, Panepistimiopolis, Athens, Greece

---

## <font color=#CD5555 face="黑体">Transmembrane Helix Prediction</font>

<p align="justify">In eukaryotes, all known membrane proteins in the plasma membrane consist of alpha helical transmembrane (TM) bundles connected by loops. Accurate computational prediction of transmembrane helical segments is important for modeling membrane protein 3D structure and function.

---

### CCTOP | Consensus Constrained TOPology prediction

<p align="justify">A web-based application providing transmembrane topology prediction. In addition to utilizing 10 different state-of-the-art topology prediction methods, the CCTOP server incorporates topology information from existing experimental and computational sources available in the PDBTM, TOPDB and TOPDOM databases using the probabilistic framework of hidden Markov model. The server provides the option to precede the topology prediction with signal peptide prediction and transmembrane-globular protein discrimination. Given the amino acid sequence of a putative α-helical transmembrane protein, CCTOP predicts its topology i.e. localization of membrane spanning regions and orientation of segments between them. The prediction results and the collected experimental information are visualized on the CCTOP home page and can be downloaded in XML format.

[**Official Website**](http://cctop.enzim.ttk.mta.hu/)

**Publications**:

* (2015 Nucleic Acids Res) [CCTOP: a Consensus Constrained TOPology prediction web server.](https://www.ncbi.nlm.nih.gov/pubmed/25943549)

**Institutions(s)**:

<p align="justify">‘Momentum’ Membrane Protein Bioinformatics Research Group, Institute of Enzymology, RCNS, HAS, Budapest, Hungary

---

### SignalP

<p align="justify">Predicts the presence and location of signal peptide cleavage sites in amino acid sequences from different organisms: Gram-positive prokaryotes, Gram-negative prokaryotes, and eukaryotes. SignalP is a neural network–based method which can discriminate signal peptides from transmembrane regions. The software incorporates a prediction of cleavage sites and a signal peptide/non-signal peptide prediction based on a combination of several artificial neural networks.

[**Official Website**](http://www.cbs.dtu.dk/services/SignalP/)

**Publications**:

* (2011 Nat Methods) [SignalP 4.0: discriminating signal peptides from transmembrane regions.](https://www.ncbi.nlm.nih.gov/pubmed/21959131)

**Institutions(s)**:

<p align="justify">Center for Biological Sequence Analysis, Department of Systems Biology, Technical University of Denmark, Lyngby, Denmark

---

# FRAP

<p align="justify">Fluorescence recovery after photobleaching (FRAP) is now widely used to investigate binding interactions in live cells. Although various idealized solutions have been identified for the reaction-diffusion equations that govern FRAP, there has been no comprehensive analysisor systematic approach to serve as a guide for extracting binding information from an arbitrary FRAP curve.

---

## easy-FRAP | FRAP : Laser scanning microscopy

<p align="justify">Provides assistance for the qualitative and quantitative analysis of fluorescence recovery after photobleaching (FRAP) data. easy-FRAP allows data visualization, normalization of the raw recovery curves and curve fitting. This software can also exploit large data sets of raw data under different experimental conditions, exclude low quality data and perform batch analysis. All of this tasks can be run simultaneously.

[**Official Website**](http://ccl.med.upatras.gr/index.php?id=easyfrap/)

**Publications**:

* (2018 Nucleic Acids Res) [EasyFRAP-web: a web-based tool for the analysis of fluorescence recovery after photobleaching data.](https://www.ncbi.nlm.nih.gov/pubmed/29901776)

**Institutions(s)**:

Laboratory of Biology School of Medicine, University of Patras, Patras, Greece; Laboratory of Physiology, School of Medicine, University of Patras, Patras, Greece

---

## PyFRAP | Python Fluorescence Recovery After Photobleaching

<p align="justify">Fits numerical simulations of three-dimensional models to fluorescence recovery after photobleaching (FRAP)/inverse FRAP (iFRAP) data and accounts for bleaching/photoconversion inhomogeneities. PyFRAP is able to apply post-bleach image as initial condition, and numerically simulates the FRAP experiment in realistic two-dimensional or three-dimensional experiment geometries. Moreover, it can determine the diffusion coefficients of fluorescent molecules ranging from 3 to 500 kDa in both artificial and biological contexts.

[**Official Website**](https://mueller-lab.github.io/PyFRAP/)

**Publications**:

* (2018 Nat Commun) [Quantitative diffusion measurements using the open-source software PyFRAP.](https://www.ncbi.nlm.nih.gov/pubmed/29679054)

**Institutions(s)**:

Friedrich Miescher Laboratory of the Max Planck Society, Tübingen, Germany; Department of Organismic and Evolutionary Biology, Harvard University, Cambridge, MA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/proteomics-category)

[*Image Citation*](https://www.slideshare.net/RESTY29/membrane-proteins-65960356)

---