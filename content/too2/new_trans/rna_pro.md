+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "RNA-Protein Interactions"

weight = 40
# Project summary to display on homepage.
summary = "Including: CLIP-seq Analysis, Ribo-seq Analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/trans/rna_pro.gif"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["transcriptomics"]

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

<img src="/img/tools/trans/rna_pro.gif"  width="400" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

#  CLIP-seq Analysis

<p align="justify">Cross-Linking Immunoprecipitation associated to **high-throughput sequencing** (CLIP-seq) is a technique used to identify RNA directly bound to RNA-binding proteins across the entire transcriptome in cell or tissue samples. Recent technological and computational advances permit the analysis of many CLIP-seq samples simultaneously, allowing us to reveal the comprehensive network of RNA-protein interaction and to integrate it to other genome-wide analyses. Therefore, the design and quality management of the CLIP-seq analyses are of critical importance to extract clean and biological meaningful information from CLIP-seq experiments. The application of CLIP-seq technique to Argonaute 2 (Ago2) protein, the main component of the microRNA (miRNA)-induced silencing complex, reveals the direct binding sites of miRNAs, thus providing insightful information about the role played by miRNA(s). [Source](https://www.ncbi.nlm.nih.gov/pubmed/28605404)

---

## <font color=#CD5555 face="黑体">Peak Calling</font>

### DFilter

<p align="justify">Detects functional signals in tag profiles from different assays such as histone ChIP-seq, TF ChiP-seq, DNase-seq and FAIRE-seq. DFilter is based on a single receiver operating characteristic – area under the curve (ROC-AUC) optimizing algorithm. This software suits for genomic signals of individual cell types diluted in cellular mixture because the proportion of marginal signals can be mistaken for noise by suboptimal algorithms.

[**Official Website**](http://collaborations.gis.a-star.edu.sg/~cmb6/kumarv1/dfilter/)

**Publications**:

* (Kumar et al., 2013) [Uniform, optimal signal processing of mapped deep-sequencing data](https://www.ncbi.nlm.nih.gov/pubmed/23770639).  Nat Biotechnol. 

**Institutions(s)**: 

Computational and Systems Biology, Genome Institute of Singapore, Singapore; Gene Regulation Laboratory, Genome Institute of Singapore, Singapore

---

### CLIPper 

<p align="justify">Defines peaks in CLIP-seq dataset. CLIPper combines features from many CLIP peak-finding algorithms. To reduce false-positives, it employes a three-pass filter on our peaks. For each gene it calculates the false-discovery rate threshold (FDR), which is the "height" of reads mapped at a single genomic position that is likely to be noise, determined by randomly scattering the same number of faux reads as real reads across a faux transcript that is the same effective length as the real transcript.

[**Official Website**](https://github.com/YeoLab/clipper/wiki/CLIPper-Home)

[**Github**](https://github.com/YeoLab/clipper)

[**Documentation**](https://github.com/YeoLab/clipper/wiki)

[**Forum**](https://groups.google.com/forum/?fromgroups#!forum/clipper-discuss)

**Publications**:

* (Lovci et al., 2013) [Rbfox proteins regulate alternative mRNA splicing through evolutionarily conserved RNA bridges](https://www.ncbi.nlm.nih.gov/pubmed/24213538).  Nat Struct Mol Biol. 

**Institutions(s)**: 

Supercomputing Facility for Bioinformatics & Computational Biology, IIT Delhi, India; Department of Bioinformatics, Banasthali Vidyapith, Banasthali, India

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Motif Discovery</font>

### RNAmotifs

<p align="justify">Recognizes clusters of motifs underlying regulatory principles of alternative splicing and alternative polyadenylation. RNAmotifs computes an enrichment score (ES) on the super-imposed sequences of all the features. It finds possible short motifs, convolutes their signals with a short sliding window.

[**Official Website**](https://github.com/grexor/rnamotifs2)

**Publications**:

* (Cereda et al., 2014) [RNAmotifs: prediction of multivalent RNA motifs that control alternative splicing](https://www.ncbi.nlm.nih.gov/pubmed/24485098).  Genome Biol. 
* (Rot et al., 2017) [High-Resolution RNA Maps Suggest Common Principles of Splicing and Polyadenylation Regulation by TDP-43](https://www.ncbi.nlm.nih.gov/pubmed/28467899).  Cell Rep. 

**Institutions(s)**: 

Institute of Molecular Life Sciences and Swiss Institute of Bioinformatics, Zurich, Switzerland; MRC Laboratory of Molecular Biology, Cambridge, UK

---

### MEMERIS

<p align="justify">A computational method for searching sequence motifs in a set of RNA sequences and simultaneously integrating information about secondary structures. MEMERIS precomputes values that characterize the single-strandedness of all putative motif occurrences. These values are then used to guide the motif search towards single-stranded regions. Authors conclude that MEMERIS preferably selects single stranded motif occurrences and that it is able to identify a weaker over a stronger motif if the average single strandedness is sufficiently higher.

[**Official Website**](http://www.bioinf.uni-freiburg.de/~hiller/MEMERIS/)

**Publications**:

* (Hiller et al., 2006) [Using RNA secondary structures to guide sequence motif finding towards single-stranded regions](https://www.ncbi.nlm.nih.gov/pubmed/16987907).  Nucleic Acids Res. 

**Institutions(s)**: 

Institute of Computer Science, Chair for Bioinformatics, Albert-Ludwigs-University Freiburg, Georges-Koehler-AlleeFreiburg, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">miRNA Target Site Detection</font>

### MicroMUMMIE 

<p align="justify">A specific model, implemented within the MUMMIE framework, for predicting micro-RNA binding sites using PAR-CLIP data.

[**Official Website**](https://ohlerlab.mdc-berlin.de/software/microMUMMIE_99/)

**Publications**:

* (Majoros et al., 2013) [MicroRNA target site identification by integrating sequence and binding information](https://www.ncbi.nlm.nih.gov/pubmed/23708386).  Nat Methods. 

**Institutions(s)**: 

Institute for Genome Sciences and Policy, Duke University, Durham, NC, USA

---

### MIRZA

<p align="justify">A biophysical model of miRNA-target interaction and infer its energy parameters from Ago-CLIP data. MIRZA includes parameters associated with base pairs and loops and specific miRNA position–dependent energy parameters that reflect the constraints imposed by the Argonaute protein on miRNA-mRNA interaction. MIRZA predicts the frequencies with which RNA-induced silencing complexes (RISCs) bind to different mRNA fragments in the mRNA pool.

[**Official Website**](http://www.clipz.unibas.ch/downloads/mirza/)

**Publications**:

* (Khorshid et al., 2013) [A biophysical miRNA-mRNA interaction model infers canonical and noncanonical targets](https://www.ncbi.nlm.nih.gov/pubmed/23334102).  Nat Methods.

**Institutions(s)**: 

Biozentrum, University of Basel, Basel, Switzerland; Swiss Institute of Bioinformatics, Basel, Switzerland

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Ribo-seq Analysis

<p align="justify">Genome-wide analyses of gene expression have so far focused on the abundance of mRNA species as measured either by microarray or, more recently, by RNA sequencing. However, neither approach provides information on protein synthesis, which is the true end point of gene expression. **Ribosome profiling** is an emerging technique that uses deep sequencing to monitor in vivo translation. Studies using ribosome profiling have already provided new insights into the identity and the amount of proteins that are produced by cells, as well as detailed views into the mechanism of protein synthesis itself. [Source](https://www.ncbi.nlm.nih.gov/pubmed/24468696)

## <font color=#CD5555 face="黑体">Ribosome P-site Localization</font>

### RiboProfiling 

<p align="justify">Offers a collection of tools for Ribo-seq data analysis. RiboProfiling provides a unique, straightforward R implementation of a ribosome profiling pipeline from BAM, to P-site calibration, quantification of reads on sequence features, and codon coverage. The packages’ graphical features offer quality assessment and result representation across the analyses. Following the overview of Ribo-seq experiments with ’RiboProfiling, the output tables can then be easily integrated into more specialized dowstream analyses.

[**Official Website**](https://www.bioconductor.org/packages/release/bioc/html/RiboProfiling.html)

[**Documentation*](https://www.bioconductor.org/packages/release/bioc/manuals/RiboProfiling/man/RiboProfiling.pdf)

**Publications**:

* (Popa et al., 2016) [RiboProfiling: a Bioconductor package for standard Ribo-seq pipeline processing](https://www.ncbi.nlm.nih.gov/pubmed/27347386).  F1000Res. 

**Institutions(s)**: 

Institut de Pharmacologie Moléculaire et Cellulaire, University Nice Sophia Antipolis and CNRS, Sophia- Antipolis, Nice, France

---

### riboWaltz

<p align="justify">Computes the P-site Offset (PO) for all reads from single or multiple RiboSeq samples. riboWaltz provides the user with a variety of graphical representations, laying the foundations for further accurate RiboSeq analyses and better interpretation of positional information. It uses reads aligning across annotated translation initiation sites to identify P-site. This tool is able to assist with the detailed interrogation of RiboSeq data at single nucleotide resolution.

[**Official Website**](https://github.com/LabTranslationalArchitectomics/RiboWaltz)

**Publications**:

* (Lauria et al., 2017) [riboWaltz: optimization of ribosome P-site positioning in ribosome profiling data](https://www.biorxiv.org/content/early/2017/07/28/169862).  BioRxiv. 

**Institutions(s)**: 

Institute of Biophysics, CNR Unit at Trento, Italy; Centre for Integrative Biology, University of Trento, Italy

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Ribosome Stalling Prediction</font>

### ROSE

<p align="justify">Analyzes large-scale ribosome profiling data and study the contextual regulation of ribosome stalling and its potential functions in protein biogenesis. ROSE formalizes the modeling problem as a classification task, in which the resulting prediction score can be used to measure the probability of a ribosome stalling event. It is able to predict ribosome stalling events in several different datasets generated from other studies.

[**Official Website**](https://github.com/zhangsaithu/rose)

**Publications**:

* (Zhang et al., 2016) [ROSE: a deep learning based framework for predicting ribosome stalling](https://doi.org/10.1101/067108).  BioRxiv.  

**Institutions(s)**: 

Institute for Interdisciplinary Information Sciences, Tsinghua University, Beijing, China; School of Medicine, Tsinghua University, Beijing, China

---

## <font color=#CD5555 face="黑体">Translated ORF Prediction</font>

### ORF-RATER

<p align="justify">Allows users to identify and quantify translation from protein-coding DNA sequences (CDSs) regardless of start codon. ORF-RATER makes the assumption that translated ORFs display a pattern of ribosome occupancy that mimics that of annotated genes. This tool is based on linear regression, which naturally integrates multiple lines of evidence simultaneously. Also, it enables each open reading frame (ORF) to be evaluated in the context of nearby and overlapping ORFs.

[**Official Website**](https://github.com/alexfields/ORF-RATER)

**Publications**:

* (Fields et al., 2015) [A Regression-Based Analysis of Ribosome-Profiling Data Reveals a Conserved Complexity to Mammalian Translation](https://www.ncbi.nlm.nih.gov/pubmed/26638175).  Mol Cell. 

**Institutions(s)**: 

Howard Hughes Medical Institute, Department of Cellular and Molecular Pharmacology, University of California, San Francisco and California Institute for Quantitative Biomedical Research, San Francisco, CA, USA


[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/transcriptomics-category)

[*Image Citation*](http://www.bioc.rice.edu/~shamoo/prid.html)

---