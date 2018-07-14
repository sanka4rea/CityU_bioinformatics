+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Immune System"

weight = 30
# Project summary to display on homepage.
summary = "Including: Immune System Analysis, Flow Cytometry, Mass Cytometry, Peptide Array Analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/protein/immune.jpg"

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

<img src="/img/tools/protein/immune.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Immune System Analysis

<p align="justify">**Immunoinformatics** involves the application of computational methods to immunological problems. Prediction of B- and T-cell epitopes has long been the focus of immunoinformatics, given the potential translational implications, and many tools have been developed. With the advent of next-generation sequencing (NGS) methods, an unprecedented wealth of information has become available that requires more-advanced immunoinformatics tools. Based on information from whole-genome sequencing, exome sequencing and RNA sequencing, it is possible to characterize with high accuracy an individual’s human leukocyte antigen (HLA) allotype (i.e., the individual set of HLA alleles of the patient), as well as changes arising in the HLA ligandome (the collection of peptides presented by the HLA) owing to genomic variation. This has allowed new opportunities for translational applications of epitope prediction, such as epitope-based design of prophylactic and therapeutic vaccines, and personalized cancer immunotherapies. [Source](https://www.ncbi.nlm.nih.gov/pubmed/26589500)

## <font color=#CD5555 face="黑体">Sequence-based B-cell Epitope Prediction</font>

<p align="justify">For over 30 years, computational methods have been developed for facilitating epitope recognition (El-Manzalawy and Honavar, 2010). In the past, the majority of the in silico methods were focused on linear epitopes. Most of these approaches are sequence-based and use amino acid-based propensity scales, such as hydrophilicity, solvent accessibility, secondary structure and flexibility; a score derived from the propensity scales is assigned to each residue, and the whole sequence is examined for high-scoring window fragments, which are then predicted as epitopes (Hopp and Woods, 1981; Parker et al., 1986; Pellequer et al., 1991; Emini et al., 1985; Karplus and Schulz, 1985; Kolaskar and Tongaonkar, 1990; Welling et al., 1985).

---

### ABCpred 

<p align="justify">Predicts B cell epitope(s) in an antigen sequence, using artificial neural network. ABCpred is able to predict epitopes with 65.93% accuracy using recurrent neural network.

[**Official Website**](http://crdd.osdd.net/raghava/abcpred/)

**Publications**:

* (2006 Proteins) [Prediction of continuous B-cell epitopes in an antigen using recurrent neural network](https://www.ncbi.nlm.nih.gov/pubmed/16894596)

**Institutions(s)**:

Institute of Microbial Technology, Chandigarh, India

---

### BepiPred 

<p align="justify">Predicts the location of linear B-cell epitopes using a combination of a hidden Markov model (HMM) and a propensity scale method. BepiPred is a web server constructed from a large set of structurally defined B cell epitopes. The interface can aid researchers with limited computational knowledge to use and understand the results to their full extent. Additionally, the advanced option allows more experienced researchers to further interpret the output based on additionally predicted structural features.

[**Official Website**](http://www.cbs.dtu.dk/services/BepiPred/)

**Publications**:

* (2017 Nucleic Acids Res) [BepiPred-2.0: improving sequence-based B-cell epitope prediction using conformational epitopes.](https://www.ncbi.nlm.nih.gov/pubmed/28472356)

**Institutions(s)**:

Department of Bio and Health Informatics, Technical University of Denmark, Kgs, Lyngby, Denmark; La Jolla, Institute for Allergy and Immunology, La Jolla, CA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Structure-based B-cell Epitope Prediction</font>

<p align="justify">In recent years, computational identification of immunogenic regions/segments in a given protein antigen has provided increasing assistance in guiding the experimental validation. Since the majority of the epitope area was dominated by discontinuous amino acids in the surface of protein antigens (Haste Andersen et al., 2006), a lot of efforts have been devoted into computing spatial/conformational epitopes based on protein structures. These methods can be roughly divided into two tracks, one of which proposing useful parameters to discriminate epitope residues from common surface ones, while the other focusing on various classification algorithm to improve the performance.

---

### LYRA 

<p align="justify">Implements a complete and automated method for building of B- and T-cell receptor structural models starting from their amino acid sequence alone. LYRA is based on the canonical structure method and can produce, easily and within minutes, extremely reliable models of lymphocyte receptors. It is freely available and easy to use for non-specialists. Upon submission, LYRA automatically generates alignments using ad hoc profiles, predicts the structural class of each hypervariable loop, selects the best templates in an automatic fashion, and provides within minutes a complete 3D model that can be downloaded or inspected online. Experienced users can manually select or exclude template structures according to case specific information.

[**Official Website**](http://www.cbs.dtu.dk/services/LYRA/)

**Publications**:

* (2015 Nucleic Acids Res) [LYRA, a webserver for lymphocyte receptor structural modeling.](https://www.ncbi.nlm.nih.gov/pubmed/26007650)

**Institutions(s)**:

Center for Biological Sequence Analysis, Technical University of Denmark, Kgs Lyngby, Denmark

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">MHC Class I Epitope Prediction</font>

<p align="justify">A key role in cell-mediated immunity is dedicated to the major histocompatibility complex (MHC) molecules that bind peptides for presentation on the cell surface. Several in silico methods capable of predicting peptide binding to MHC class I have been developed. The accuracy of these methods depends on the data available characterizing the binding specificity of the MHC molecules.

---

### ProPred1 

<p align="justify">An on-line service for identifying the MHC Class-I binding regions in antigens. It implements matrices for 47 MHC Class-I alleles, proteasomal and immunoproteasomal models. The main aim of ProPred1 is to help users in identifying the promiscuous regions.

[**Official Website**](http://crdd.osdd.net/raghava/propred1/)

**Publications**:

* (2003 Bioinformatics) [ProPred1: prediction of promiscuous MHC Class-I binding sites.](https://www.ncbi.nlm.nih.gov/pubmed/12761064)

**Institutions(s)**:

Institute of Microbial Technology, Chandigarh, India

---

### GradDock 

<p align="justify">Decouples global and local conformational searches and generates diverse native-like peptide conformations for peptide binding to major histocompatibility complex class I (pMHC-I). GradDock uses a ranking function specific for pMHC-I which was reconstructed from the Rosetta scoring terms. It provides three steps: (1) the generation of peptide candidates from the sequence; (2) the insertion of peptides into the MHC-I molecule; and (3) the ranking of the peptides. It can create native-like peptides with a certain degree of diversity, which is sufficient for describing the pMHC-I space.

[**Official Website**](http://crdd.osdd.net/raghava/propred1/)

**Publications**:

* (2017 Bioinformatics) [GradDock: Rapid Simulation and Tailored Ranking Functions for Peptide-MHC Class I Docking.](https://academic.oup.com/bioinformatics/article-abstract/34/3/469/4160677?redirectedFrom=fulltext)

**Institutions(s)**:

Department of Biological Sciences, Korea Advanced Institute of Science and Technology (KAIST), Daejeon, Republic of Korea

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">MHC Class II Epitope Prediction</font>

<p align="justify">CD4+ T-cell epitopes play a crucial role in eliciting vigorous protective immune responses during peptide (epitope)-based vaccination. The prediction of these epitopes focuses on the peptide binding process by MHC class II proteins. The ability to account for MHC class II polymorphism is critical for epitope-based vaccine design tools, as different allelic variants can have different peptide repertoires. In addition, the specificity of CD4+ T-cells is often directed to a very limited set of immunodominant peptides in pathogen proteins. The ability to predict what epitopes are most likely to dominate an immune response remains a challenge.

---

### HLAMatchmaker 

<p align="justify">Determines human leukocyte antigen (HLA) matching at epitope level in alloantibody responses. HLAMatchmaker utilizes an algorithm where each HLA antigen is considered as a string of amino acid configurations in antibody-accessible positions. This program can be used as a quantitative tool to define the degree of a mismatch such as mismatched eplets of triplets.

[**Official Website**](http://www.epitopes.net/)

**Publications**:

* (2011 Tissue Antigens) [Antibody-reactive epitope determination with HLAMatchmaker and its clinical applications.](https://www.ncbi.nlm.nih.gov/pubmed/21410655)

**Institutions(s)**:

Division of Transplantation Pathology, Thomas E. Starzl Transplantation Institute, University of Pittsburgh Medical Center, Pittsburgh, PA, USA

---

### ProPred 

<p align="justify">Analyses sequence data to predict MHC class II binding regions in antigenic protein sequences. Propred (generates text or graphic outputs, presents the binding score calculated from matrix in tabular format, selects an appropriate threshold for locating promiscuous binders using a threshold profile and performs analysis on any sub-sequence including the computation of the binding strength of all peptide frames.

[**Official Website**](http://osddlinux.osdd.net/raghava/propred/)

**Publications**:

* (2001 Bioinformatics) [ProPred: prediction of HLA-DR binding sites.](https://www.ncbi.nlm.nih.gov/pubmed/11751237)

**Institutions(s)**:

Bioinformatics Centre, Institute of Microbial Technology, Sector 39A, Chandigarth, India

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Flow Cytometry

<p align="justify">**Flow cytometry** is a technology widely used in clinical practice and in research, particularly in the field of immunology. It is capable of interrogating a wide variety of markers on many different cell types on a single-cell basis, using fluorophore-conjugated antibodies. Although molecular as well as genomic studies have advanced the understanding of immunological processes and autoimmune diseases, the components of the human immune system and their functions have yet to be comprehensively described. Without such a reference “catalog” of the immune system, it is ultimately difficult to interpret the pathogenic significance of genetic, molecular, or phenotypic variants observed in diseases.

---

## <font color=#CD5555 face="黑体">Cell Population Identification</font>

<p align="justify">Traditionally, the majority of flow cytometry experiments have been analyzed visually, either by serial manual inspection of one or two dimensions at a time (a process termed “gating”, with boundaries or “gates” defining cell populations of interest). However, these visual approaches are labor intensive and highly subjective, and they neglect information present in the data that are not visible to the human eye, thus representing a major obstacle to the automation and reproducibility of research.

---

### FCS Express

<p align="justify">Enables flow and image cytometry data analysis. FCS Express is able to analyze flow cytometry data, with flow cytometry tools, plots, and gates. The software allows export to Powerpoint, pdf, Excel, Word, and Microsoft office.

[**Official Website**](https://www.denovosoftware.com/)

**Forum**:

[Forum](https://www.denovosoftware.com/site/forums.shtml)

---

### FlowJo 

<p align="justify">A flow cytometry data analysis software.. FlowJo contains a list of loaded samples (experimental data), statistics, gates, and other analyses, as well as tabular and graphical layouts. FlowJo provides features and tools for the creation of histogram and other plot overlays, cell cycle analysis, calcium flux analysis, proliferation analysis, quantitation, cluster identification and backgating display.

[**Official Website**](https://www.flowjo.com/solutions/flowjo)

**CITATIONS**:

* (2017) [Circulating Mycobacterium tuberculosis DosR latency antigen-specific, polyfunctional, regulatory IL10+ Th17 CD4 T-cells differentiate latent from active tuberculosis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5607261/)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Mass Cytometry

<p align="justify">Mass cytometry addresses the analytical challenges of polychromatic flow cytometry by using metal atoms as tags rather than fluorophores and atomic mass spectrometry as the detector rather than photon optics.

---

## SPADE (Spanning tree Progression of Density normalized Events
)

<p align="justify">Facilitates the analysis of cellular heterogeneity, the identification of cell types, and comparison of functional markers in response to perturbations, based on a versatile method. SPADE helps to organize high-dimensional cytometry data in an unsupervised manner, and to investigate natural and pathogenic cellular heterogeneity for biological insight. The SPADE algorithm consists of four components: (i) density-dependent downsampling, (ii) clustering, (iii) linking clusters with a minimum spanning tree, and (iv) upsampling to restore all cells in the final result. This modularized process allows more efficient sub-algorithms to replace the current components. In this sense, SPADE can be viewed as a framework for cytometric data analysis and visualization that has the capacity to be evolved and adapted.

[**Official Website**](https://github.com/nolanlab/spade)

**Publications**:

* (2011 Nat Biotechnol) [Extracting a cellular hierarchy from high-dimensional cytometry data with SPADE.](https://www.ncbi.nlm.nih.gov/pubmed/21964415)

* (2011 Science) [Single-cell mass cytometry of differential immune and drug responses across a human hematopoietic continuum.](https://www.ncbi.nlm.nih.gov/pubmed/21551058)

**Institutions(s)**:

Department of Radiology, Stanford University, Stanford, CA, USA

---

## viSNE | Data visualization : Flow cytometry

<p align="justify">A tool that allows one to map high-dimensional cytometry data onto two dimensions, yet conserve the high-dimensional structure of the data.

[**Official Website**](https://www.denovosoftware.com/site/manual/visne.htm)

**Publications**:

* (2013 Nat Biotechnol) [viSNE enables visualization of high dimensional single-cell data and reveals phenotypic heterogeneity of leukemia.](https://www.ncbi.nlm.nih.gov/pubmed/23685480)

**Institutions(s)**:

Department of Biological Sciences, Columbia Initiative for Systems Biology, Columbia University, New York, NY, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/proteomics-category)

[*Image Citation*](https://www.proprofs.com/quiz-school/story.php?title=quiz-lecture-2-components--innate-immune-system)

---