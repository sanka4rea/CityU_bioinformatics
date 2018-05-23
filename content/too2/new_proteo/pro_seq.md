+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Protein Sequence/Expression"

weight = 10
# Project summary to display on homepage.
summary = "Including: Protein Sequence Analysis, MS-based untargeted Proteomics, MS-based Metaproteomics, Antibody Array Analysis, Proteogenomics Analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/protein/pro_seq.png"

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

<img src="/img/tools/protein/pro_seq.png"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Protein Sequence Analysis

<p align="justify">Protein sequence analysis tools are used to predict specific functions, activities, origin, or localization of proteins based on their amino-acid sequence. Software tools are also used to analysis high-throughput proteomics data sequences obtained by mass-spectrometry.

## <font color=#CD5555 face="黑体">Amino Acid Repeat Prediction</font>

### RADAR

<p align="justify">A tool to identify short composition biased and gapped approximate repeats, as well as complex repeat architectures involving many different types of repeats in a query sequence. RADAR is useful because many large proteins have evolved by internal duplication and many internal sequence repeats correspond to functional and structural units.

[**Official Website**](https://www.ebi.ac.uk/Tools/pfa/radar/)

[**Documentation**](http://www.ebi.ac.uk/Tools/pfa/radar/help/)

**Publications**:

* (Li et al., 2015) [The EMBL-EBI bioinformatics web and programmatic tools framework](https://www.ncbi.nlm.nih.gov/pubmed/25845596).  Nucleic Acids Res. 
* (Heger and Holm, 2000) [Rapid automatic detection and alignment of repeats in protein sequences](https://www.ncbi.nlm.nih.gov/pubmed/10966575).  Proteins. 

**Institutions(s)**: 

European Bioinformatics Institute, Wellcome Trust Genome Campus, Hinxton, Cambridge, UK

---

### REPRO

<p align="justify">The program is able to recognize distant repeats in a single query sequence. The technique relies on a variation of the Smith-Waterman local alignment strategy to find non-overlapping top-scoring local alignments, followed by a graph-based iterative clustering procedure to delineate the repeat set(s) based on consistency of the pairwise top-alignments.

[**Official Website**](http://www.ibi.vu.nl/programs/reprowww/)

[**Documentation**](http://www.ibi.vu.nl/programs/reprowww/info.php)

**Publications**:

* (George and Heringa, 2000) [The REPRO server: finding protein internal sequence repeats through the Web](https://www.ncbi.nlm.nih.gov/pubmed/11203383).  Trends Biochem Sci. 
* (Heringa and Argos, 1993) [A method to recognize distant repeats in protein sequences](https://www.ncbi.nlm.nih.gov/pubmed/8108381).  Proteins. 

**Institutions(s)**: 

European Molecular Biology Laboratory, Heidelberg, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Subcellular Localizaton Prediction</font>

### TargetP

<p align="justify">Allows users to predict eukaryotic proteins location. TargetP is a web application that scores N-terminal pre-sequences in a submitted protein. The software indicates chloroplast transit peptide (cTP), mitochondrial targeting peptide (mTP) and secretory pathway signal peptide (SP) predicted localization. The application includes parameters which allow choosing between in Plants and Non-Plants version, personalized cutoffs and the possibility to determine cleavage sites.

[**Official Website**](http://www.cbs.dtu.dk/services/TargetP/)

[**Documentation**](http://www.ibi.vu.nl/programs/reprowww/info.php)

**Publications**:

* (Emanuelsson et al., 2007) [Locating proteins in the cell using TargetP, SignalP and related tools](https://www.ncbi.nlm.nih.gov/pubmed/17446895).  Nat Protoc. 

**Institutions(s)**: 

Stockholm Bioinformatics Center, Albanova, Stockholm University, Stockholm, Sweden; Center for Biological Sequence Analysis, Technical University of Denmark, Lyngby, Denmark

---

### pRoloc

<p align="justify">Provides machine learning and visualization methods for interrogating and analyzing on quantitative mass spectrometry (MS) data to infer protein sub-cellular localization. PRoloc is suited for spatial proteomics data analysis provided as an R package that performs sub-cellular localization prediction from experimental and condition-specific MS-based quantitative proteomics data. The software allows classification of proteins to tens of sub-cellular compartments.

[**Official Website**](http://bioconductor.org/packages/release/bioc/html/pRoloc.html)

[**Documentation**](http://bioconductor.org/packages/release/bioc/manuals/pRoloc/man/pRoloc.pdf)

**Publications**:

* (Breckels et al., 2016) [Learning from Heterogeneous Data Sources: An Application in Spatial Proteomics](https://www.ncbi.nlm.nih.gov/pubmed/27175778).  PLoS Comput Biol. 
* (Crook et al., 2018) [A Bayesian Mixture Modelling Approach For Spatial Proteomics](https://www.biorxiv.org/content/early/2018/05/22/282269).  BioRxiv. 

**Institutions(s)**: 

Computational Proteomics Unit, Department of Biochemistry, University of Cambridge, Cambridge, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Protein Clustering</font>

### CD-HIT

<p align="justify">A widely used program for clustering biological sequences to reduce sequence redundancy and improve the performance of other sequence analyses. In response to the rapid increase in the amount of sequencing data produced by the next-generation sequencing technologies, a new CD-HIT program accelerated with a novel parallelization strategy and some other techniques has been developed to allow efficient clustering of such datasets.

[**Official Website**](http://weizhong-lab.ucsd.edu/cd-hit/)

**Publications**:

* (Fu et al., 2012) [CD-HIT: accelerated for clustering the next-generation sequencing data](https://www.ncbi.nlm.nih.gov/pubmed/23060610).  Bioinformatics.
* (Li and Godzik, 2006) [Cd-hit: a fast program for clustering and comparing large sets of protein or nucleotide sequences](https://www.ncbi.nlm.nih.gov/pubmed/16731699). Bioinformatics. 

**Institutions(s)**: 

Center for Research in Biological Systems, University of California San Diego, La Jolla, CA, USA

---

### USEARCH

<p align="justify">Searches and clusters algorithms that can be orders of magnitude. USEARCH is a sequence analysis software which combines different algorithms into a single package. This software searches in database for top global hits and provides several NGS read processing features such as dereplication, paired read overlapping, quality filtering, FASTQ file statistics or chimeric sequence filtering.

[**Official Website**](http://www.drive5.com/usearch/)

[**Galaxy**](https://toolshed.g2.bx.psu.edu/repository?repository_id=13df57e58dc7e075)

**Publications**:

* (Edgar, 2010) [Search and clustering orders of magnitude faster than BLAST](https://www.ncbi.nlm.nih.gov/pubmed/20709691).  Bioinformatics. 
* (Edgar and Flyvbjerg, 2015) [Error filtering, pair assembly and error correction for next-generation sequencing reads](https://www.ncbi.nlm.nih.gov/pubmed/26139637).  Bioinformatics. 

**Institutions(s)**: 

Department of Micro- and Nanotechnology, Technical University of Denmark, Lyngby, Denmark

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# MS-based (Mass Spectrometry) untargeted Proteomics

A number of technologies can be used to study proteomes, but arguably none is more powerful than mass spectrometry. There are two fundamentally different MS-based strategies for analyzing proteomes: discovery-based identification and targeted quantification ([Doerr, 2013](https://www.ncbi.nlm.nih.gov/pubmed/23547294); [Picotti and Aebersold, 2012](https://www.ncbi.nlm.nih.gov/pubmed/22669653)). With a discovery-based strategy, the goal is usually to identify as many proteins as possible. The goal of a targeted proteomics experiment is to monitor a select few proteins of interest with high sensitivity, reproducibility and quantitative accuracy. [Wikipedia](https://en.wikipedia.org/wiki/List_of_mass_spectrometry_software)

## <font color=#CD5555 face="黑体">2D gel Image Analysis</font>

### digeR

<p align="justify">Provides a graphical user interface (GUI) for the visualization of protein post-translational modification (PTM) changes between different biological states. digeR is an R package for analyzing potential protein PTM changes in 2D-DIGE (2D gel) study using spots correlation. It can also be used to support other ‘omic’ data analysis in a similar manner and to assist biologist to look for panels of biomarkers which would improve the diagnosis and prognosis of the disease.

[**Official Website**](https://cran.r-project.org/src/contrib/Archive/digeR/)

**Publications**:

* (Fan et al., 2009) [digeR: a graphical user interface R package for analyzing 2D-DIGE data](https://www.ncbi.nlm.nih.gov/pubmed/19706743).  Bioinformatics. 

**Institutions(s)**:

UCD School of Medicine and Medical Science, University College Dublin, Dublin, Ireland; UCD Conway Institute of Biomolecular and Biomolecular Research, University College Dublin, Dublin, Ireland

---

### Plasmo2D

<p align="justify">Performs gel alignment and protein identification computationally. Plasmo2D assists in the identification of proteins in the P. falciparum 3D7 proteome from the 2-DE gel image. It allows users to overlap the markers of the gel image on the marker provided by the software using the image resizes buttons in the software. This too can display a list of potential candidate proteins corresponding to a spot of interest.

[**Official Website**](http://utlab3.biochem.iisc.ernet.in/Plasmo2D/index.html)

**Publications**:

* (Khachane et al., 2005) ["Plasmo2D": an ancillary proteomic tool to aid identification of proteins from Plasmodium falciparum](https://www.ncbi.nlm.nih.gov/pubmed/16335988).  J Proteome Res.  

**Institutions(s)**:

Department of Biochemistry, Indian Institute of Science, Bangalore, India

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">In Silico Analysis</font>

### OpenMS

<p align="justify">Allows to manage and analyse Liquid chromatography coupled to mass spectrometry (LC-MS) data. OpenMS is a programming library and tool collection integrated into full-featured workflow systems, such as KNIME, Galaxy and WS-PGRADE, to facilitate bioinformatics research in the field of MS on all levels. The software provides pre-built and ready-to-use tools for analysis of both proteomics and non-targeted metabolomics data.

[**Official Website**](https://www.openms.de/)

[**Github**](https://github.com/OpenMS/OpenMS)

**Publications**:

* (Lange et al., 2007) [A geometric approach for the alignment of liquid chromatography-mass spectrometry data](https://www.ncbi.nlm.nih.gov/pubmed/17646306).  Bioinformatics. 
* (Pfeuffer et al., 2017) [OpenMS - A platform for reproducible analysis of mass spectrometry data](https://www.ncbi.nlm.nih.gov/pubmed/28559010).  J Biotechnol. 

**Institutions(s)**:

Applied Bioinformatics, Department for Computer Science, University of Tuebingen, Tuebingen, Germany; Center for Bioinformatics, University of Tuebingen, Tuebingen, Germany

---

### multiplierz

<p align="justify">Manages proteomic mass spectrometry workflows and data analysis. Multiplierz provides a toolset of multiple methods for peptide identification, quantitation, reporting, as well as tools for easily manipulating standard data formats. This software is a Python library compatible with new reporting formats and high-level tools to achieve post-perform proteomic analyses. The architecture of the software environment has seamless integration with native data files via mzAPI.

[**Official Website**](https://github.com/BlaisProteomics/multiplierz)

[**Documentation**](https://github.com/MaxAlex/multiplierz/wiki)

**Publications**:

* (Parikh et al., 2009) [multiplierz: an extensible API based desktop environment for proteomics data analysis](https://www.ncbi.nlm.nih.gov/pubmed/19874609).  BMC Bioinformatics. 
* (Alexander et al., 2017) [multiplierz v2.0: A Python-based ecosystem for shared access and analysis of native mass spectrometry data](https://www.ncbi.nlm.nih.gov/pubmed/28686798).  Proteomics. 

**Institutions(s)**:

Department of Cancer Biology and Blais Proteomics Center, Dana- Farber Cancer Institute, Boston, MA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Phosphorylation Site Assignment</font>

### Ascore

<p align="justify">Processes localization-specific probability for every phosphorylation site within a data set. Ascore allows users to detect peptides, shows the degree of certainty and the non-localized peptides. This software can determine the proper phosphorylation site alignment by calculating the differences in site placement at the level of the site-determining ions. It avoids the potential inconsistencies that may happen from manual validation.

[**Official Website**](http://ascore.med.harvard.edu/)

**Publications**:

* (Beausoleil et al., 2006) [A probability-based approach for high-throughput protein phosphorylation analysis and site localization](https://www.ncbi.nlm.nih.gov/pubmed/16964243).  Nat Biotechnol. 

**Institutions(s)**:

Department of Cell Biology, Harvard Medical School, Boston, MA, USA; Department of Genetics and Norris Cotton Cancer Center, Lebanon, New Hampshire, NH, USA

---

### Phosphonormalizer

<p align="justify">Provides pairwise normalization of phosphoproteomics data. Phosphonormalizer allows analysis of large-scale experiments in various treatment conditions. It incorporates non-enriched data as a reference for normalizing the enriched data. This tool can be applied to studies of other post-translational modifications (PTMs) than phosphorylation that are commonly studied using enrichment and that can also be detected in non-enriched samples with sensitive methods.

[**Official Website**](https://bioconductor.org/packages/release/bioc/html/phosphonormalizer.html)

**Publications**:

* (Saraei et al., 2017) [Phosphonormalizer: an R package for normalization of MS-based label-free phosphoproteomics](https://doi.org/10.1093/bioinformatics/btx573).  Bioinformatics. 

**Institutions(s)**:

Turku Centre for Biotechnology, University of Turku and Åbo Akademi, Turku, Finland; Department of Future Technologies, University of Turku, Turku, Finland

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">PTM Identification</font>

### PIQED

<p align="justify">Provides a complete, automated workflow for post translational modification (PTM) identification, quantification, and statistical testing from exclusively data-independent acquisition-mass spectrometry (DIA-MS) data. PIQED is a workflow and open-source software that enables a two-fold reduction of acquisition time because both identification and quantification are achieved with a single DIA analysis. PTM-specific capabilities of this package include site localization scoring and filtering, peptide consolidation to modification site-level, and optional local or global total-ion chromatogram (TIC) normalization.

[**Official Website**](https://github.com/jgmeyerucsd/PIQEDia/tree/v0.1.2)

[**Documentation**](https://github.com/jgmeyerucsd/PIQEDia/raw/master/Tutorial_and_manual.pdf)

**Publications**:

* (Meyer et al., 2017) [DIA-Pipe: Identification and Quantification of Post-Translational Modifications using exclusively Data-Independent Acquisition](https://doi.org/10.1101/141382). BioRxiv. 
* (Meyer et al., 2017) [PIQED: automated identification and quantification of protein modifications from DIA-MS data](https://www.nature.com/articles/nmeth.4334).  Nat Methods. 

**Institutions(s)**:

Buck Institute for Research on Aging, Novato, CA, USA; Department of Pathology, Boston Children’s Hospital and Harvard Medical School, Boston, MA, USA

---

### SUMmOn

<p align="justify">An automated pattern recognition tool that detects diagnostic PTM fragment ion series within complex MS/MS spectra, to identify modified peptides and modification sites within these peptides. The results of the SUMmOn analysis are stored in an XML instance document. A dynamically generated XSLT style sheet is then used to create an HTML file that is formatted via CSS (cascading style sheet), and viewed in a web-browser.

[**Official Website**](http://summon.sourceforge.net/)

**Publications**:

* (Pedrioli et al., 2006) [Automated identification of SUMOylation sites using mass spectrometry and SUMmOn pattern recognition software](https://www.ncbi.nlm.nih.gov/pubmed/16791211).  Nat Methods. 

**Institutions(s)**:

Institute for Systems Biology, Seattle, WA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Glycosylation Identification</font>

### SugarQb

<p align="justify">Enables genome-wide insights into protein glycosylation and glycan modifications in complex biological systems. SugarQb identifies intact glycopeptides, and maps and quantifies changes in protein glycosylation at a proteome scale. This method can assist user in investigation of the glycoproteome of mouse embryonic stem cells.

[**Official Website**](http://ms.imp.ac.at/?action=sugarqb)

[**Documentation**](http://ms.imp.ac.at/data/sugarqb/SugarQb_HowTo_2017-09-20.pdf)

**Publications**:

* (Stadlmann et al., 2017) [Comparative glycoproteomics of stem cells identifies new players in ricin toxicity](https://www.nature.com/articles/nature24015).  Nature.  

**Institutions(s)**:

IMBA, Institute of Molecular Biotechnology of the Austrian Academy of Sciences, Vienna, Austria; Institute of Molecular Pathology (IMP), Vienna, Austria

---

### MAGIC

<p align="justify">Identifies intact N-glycosylated peptides from a public protein database without requiring any prior information of proteins or glycans. MAGIC aims to support untargeted glycopeptide analysis while the newly implemented MAGIC+ is designed to perform targeted glycopeptide analysis that allows users to upload their own protein sequence file to find glycopeptides in their data. The search results from Mascot can be integrated with the results from MAGIC-web via Reports Integrator to generate a complete protein/peptide-glycan summary report. Independent of the above three modules, the fourth module, Glycan Search, allows users to find various glycans from a large glycan database stored in the web server, regardless the types of glycosylation. MAGIC-web has a user-friendly visualization interface for easy data uploading and processing, and result interpretation. MAGIC-web is free and open to all users and there is no log in requirement.

[**Official Website**](http://magic.iis.sinica.edu.tw/index.html)

**Publications**:

* (Lih et al., 2016) [MAGIC-web: a platform for untargeted and targeted N-linked glycoprotein identification.](https://www.ncbi.nlm.nih.gov/pubmed/27084943)  Nucleic Acids Res. 
* (Lynn et al., 2015) [MAGIC: an automated N-linked glycoprotein identification tool using a Y1-ion pattern matching algorithm and in silico MS² approach](https://www.ncbi.nlm.nih.gov/pubmed/25629585). Anal Chem. 

**Institutions(s)**:

Bioinformatics Program, Taiwan International Graduate Program, Academia Sinica, Taipei, Taiwan; Institute of Information Science, Academia Sinica, Taipei, Taiwan

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# MS-based Metaproteomics

### Unipept

<p align="justify">An open source web application that is designed for metaproteomics analysis with a focus on interactive data-visualization. Unipept is underpinned by a fast index built from UniProtKB and the NCBI taxonomy that enables quick retrieval of all UniProt entries in which a given tryptic peptide occurs. Unipept provides programmatic access to the metaproteomics analysis features. This enables integration of Unipept functionality in custom applications and data processing pipelines.

[**Official Website**](http://magic.iis.sinica.edu.tw/index.html)

**Publications**:

* (Mesuere et al., 2015) [The Unipept metaproteomics analysis pipeline](https://www.ncbi.nlm.nih.gov/pubmed/25477242).  Proteomics. 
* (Mesuere et al., 2016) [Unipept web services for metaproteomics analysis](https://www.ncbi.nlm.nih.gov/pubmed/26819472).  Bioinformatics. 

**Institutions(s)**:

Department of Applied Mathematics, Computer Science and Statistics, Faculty of Sciences, Ghent University, Ghent, Belgium

---

### MPA

<p align="justify">An intuitive open-source tool for metaproteomics data analysis and interpretation, which includes multiple search engines and the feature to decrease data redundancy by grouping protein hits to so-called meta-proteins. The functionality of the MetaProteomeAnalyzer is demonstrated using a sample of a microbial community taken from a biogas plant.

[**Official Website**](https://github.com/compomics/meta-proteome-analyzer)

[**Documentation**](https://github.com/compomics/meta-proteome-analyzer/wiki)

**Publications**:

* (Muth et al., 2015) [The MetaProteomeAnalyzer: a powerful open-source software suite for metaproteomics data analysis and interpretation](https://www.ncbi.nlm.nih.gov/pubmed/25660940).  J Proteome Res.  
* (Muth et al., 2017) [MPA Portable: a Stand-alone Software Package for Analyzing Metaproteome Samples on the Go](https://www.ncbi.nlm.nih.gov/pubmed/29215871).  Anal Chem. 

**Institutions(s)**:

Max Planck Institute for Dynamics of Complex Technical Systems, Magdeburg, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---
# Antibody Array Analysis

### PANDA

<p align="justify">A web-based software program developed at Emory University for analyzing phosphorylation antibody arrays.

[**Official Website**](http://www.mathcs.emory.edu/panda/)

**Publications**:

* (Zhong et al., 2008) [LKB1 is necessary for Akt-mediated phosphorylation of proapoptotic proteins](https://www.ncbi.nlm.nih.gov/pubmed/18794113).  Cancer Res. 

**Institutions(s)**:

The Winship Cancer Institute, Emory University School of Medicine, Atlanta, Georgia, USA


[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMICTOOLS**](https://omictools.com/proteomics-category)

[*Image Citation*](https://www.ebi.ac.uk/training/online/course/introduction-protein-classification-ebi/protein-classification)

---