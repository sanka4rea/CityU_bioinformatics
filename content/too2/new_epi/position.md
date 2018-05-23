+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Nucleosome Positioning"

weight = 20
# Project summary to display on homepage.
summary = "Including: Nucleosome positioning, MNase-seq analysis, ATAC-seq analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/geno/position.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["epigenomics"]

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

<img src="/img/tools/geno/position.jpg" width="600" height="400" alt="position" align="center">

<span id="top"></span>

{{% toc %}}

# Nucleosome Positioning

## NuCMap | Nucleosome positioning : Epigenomics

<p align="justify">Maps directly nucleosome centers. NuCMap is based on chemical modification of engineered histones. It locates nucleosome positions genome-wide on a map in unprecedented detail and accuracy and shows significantly stronger dinucleotide signals in nucleosome DNAs than MNase maps. The tool reveals novel aspects of the in vivo nucleosome organization that are linked to transcription factor (TF) binding, RNA polymerase pausing, and the higher order structure of the chromatin fiber.

[**Official Website**](http://bioinfo.stats.northwestern.edu/~jzwang/NuCMap.html)

[**Documentation**](http://bioinfo.stats.northwestern.edu/~jzwang/NuCMap-manual.pdf)

**Publications**:

* (Brogaard, 2012) [A map of nucleosome positions in yeast at base-pair resolution](https://www.ncbi.nlm.nih.gov/pubmed/22722846).  Nature. 

**Institutions(s)**:

Department of Molecular Biosciences and Department of Chemistry, Northwestern University, Evanston, IL, USA; Department of Statistics, Northwestern University, Evanston, IL, USA

---

## nuMap | Nucleosome positioning : Epigenomics

<p align="justify">Implements the YR and W/S schemes to predict nucleosome positioning at high resolution. This methodology is based on the sequence-dependent anisotropic bending, which dictates how DNA is wrapped around a histone octamer. nuMap allows users to specify a number of options such as schemes and parameters for threading calculation and provides multiple layout formats.

[**Official Website**](http://numap.rit.edu/app/dna/index.xhtml)

**Publications**:

* (Cui and Zhurkin, 2014) [Rotational positioning of nucleosomes facilitates selective binding of p53 to response elements associated with cell cycle arrest](https://www.ncbi.nlm.nih.gov/pubmed/24153113). Nucleic Acids Res. 
* (Cui and Zhurkin, 2010) [Structure-based analysis of DNA sequence patterns guiding nucleosome positioning in vitro](https://www.ncbi.nlm.nih.gov/pubmed/20232936).  J Biomol Struct Dyn. 

**Institutions(s)**:

Thomas H Gosnell School of Life Sciences, Chinahester Institute of Technology, Rochester, NY, USA

---

## ICM | Interactive Chromatin Modeling

<p align="justify">Allows users to assess nucleosome stability and fold sequences of DNA into putative chromatin templates. ICM generates a nucleosome energy level diagram, coarse-grained representations of free DNA and chromatin and plots of the helical parameters (Tilt, Roll, Twist, Shift, Slide and Rise) as a function of position. It uses an elastic model to automatically place nucleosomes. The tool can be used to y assemble models of chromatin that can be employed to rationalize biophysical data, especially spatial relations.

[**Official Website**](http://dna.engr.latech.edu/icm-du/)

**Publications**:

* (Stolz and Bishop, 2010) [ICM Web: the interactive chromatin modeling web server](https://www.ncbi.nlm.nih.gov/pubmed/20542915).  Nucleic Acids Res. 

**Institutions(s)**:

Department of Biostatistics, Tulane University, New Orleans, LA, USA; Centre for Computational Science, Lindy Boggs Centre, Tulane University, New Orleans, LA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# MNase-seq analysis

<p align="justify">The technology of micrococcal nuclease (MNase) digestion combined with high-throughput sequencing (MNase-seq) is a powerful method to map the genome-wide distribution of nucleosome occupancy (Mavrich et al., 2008; Schones et al., 2008; Jiang and Pugh, 2009). Source text: Chen et al., 2014.

## PING 

<p align="justify">Serves for nucleosome positioning. PING uses MNase-Seq data or MNase - or sonicated - ChIP-Seq data combined with either single-end or paired-end sequencing. It enables nucleosome predictions even in the presence of low read counts. It contains functions for pre-processing and reading raw data. It can handle sonicated and MNase protocols combined with either single-end (SE) or paired-end (PE) sequencing.

[**Official Website**](http://bioconductor.org/packages/release/bioc/html/PING.html)

[**Documentation**](http://bioconductor.org/packages/release/bioc/manuals/PING/man/PING.pdf)

**Publications**:

* (Woo et al., 2013) [PING 2.0: an R/Bioconductor package for nucleosome positioning using next-generation sequencing data](https://www.ncbi.nlm.nih.gov/pubmed/23786769). Bioinformatics. 
* (Zhang et al., 2012) [Probabilistic inference for nucleosome positioning with MNase-based or sonicated short-read data](https://www.ncbi.nlm.nih.gov/pubmed/22393380).  PLoS One. 

**Institutions(s)**:

Vaccine and Infectious Diseases and Public Health Sciences Divisions, Fred Hutchinson Cancer Research Center, Seattle, WA, USA; Department of Biostatistics, Johns Hopkins University, Baltimore, MD, USA;

---

## nucleR 

<p align="justify">A package for non-parametric nucleosome positioning. nucleR uses a novel aproach in this field which comprises a deep profile cleaning using Fourier Transform and peak scoring for a quick and flexible nucleosome calling.

[**Official Website**](http://mmb.pcb.ub.es/nucleR/)

[**Documentation**](http://bioconductor.org/packages/release/bioc/manuals/PING/man/PING.pdf)

**Publications**:

* (Flores and Orozco, 2011) [nucleR: a package for non-parametric nucleosome positioning](https://www.ncbi.nlm.nih.gov/pubmed/21653521).  Bioinformatics. 

**Institutions(s)**:

IRB-BSC Joint Research Program on Computational Biology, Institute of Research in Biomedicine, Barcelona, Spain

---

## NOrMAL

<p align="justify">A command line tool for accurate placing of the nucleosomes. NOrMAL was designed to resolve overlapping nucleosomes and extract extra information ("fuzziness", probability, etc.) of nucleosome placement.

[**Official Website**](http://alumni.cs.ucr.edu/~polishka/)

**Publications**:

* (Polishko et al., 2012) [NORMAL: accurate nucleosome positioning using a modified Gaussian mixture model](https://www.ncbi.nlm.nih.gov/pubmed/22689767).  Bioinformatics. 

**Institutions(s)**:

Department of Computer Science and Engineering, University of California, Riverside, CA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# ATAC-seq analysis

<p align="justify">ATAC-seq allows simultaneous interrogation of factor occupancy, nucleosome positions in regulatory sites, and chromatin accessibility genome wide by considering the position of insertion and the distribution of insert lengths captured during the transposition reaction. 

## NucleoATAC | Nucleosome positionning analysis : ATAC-seq analysis

<p align="justify">A python package for nucleosome-positioning using as basis the highly structured pattern of DNA fragment lengths and positions around nucleosomes. NucleoATAC can identify the rotational and translational positions of nucleosomes with up to base-pair resolution and provide quantitative measures of nucleosome occupancy in Schizosaccharomyces cerevisiae, Schizosaccharomyces pombe and human cells. NucleoATAC can be used to analyze sequence features underlying nucleosome positioning, to promote chromatin architecture across species, to identify transient changes in nucleosome occupancy and to asses positioning during a dynamic cellular response.

[**Official Website**](http://nucleoatac.readthedocs.io/en/latest/)

[**Github**](https://github.com/GreenleafLab/NucleoATAC)

[**Documentation**](http://nucleoatac.readthedocs.io/en/latest/#nucleoatac-documentation)

**Publications**:

* (Schep et al., 2015) [Structured nucleosome fingerprints enable high-resolution mapping of chromatin architecture within regulatory regions](https://www.ncbi.nlm.nih.gov/pubmed/26314830).  Genome Res.  

**Institutions(s)**:

Department of Genetics, Stanford University School of Medicine, Stanford, CA, USA; Biophysics Program, Stanford University School of Medicine, Stanford, CA, USA; Department of Applied Physics, Stanford University, Stanford, CA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMIVTOOLS**](https://omictools.com/epigenomics-category)

[*Image Citation*](https://www.nature.com/articles/nbt.1685)

---