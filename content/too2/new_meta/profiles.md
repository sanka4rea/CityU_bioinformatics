+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Metabolic Profiles"

weight = 10
# Project summary to display on homepage.
summary = "Including: Metabolic profiles analysis, MS-based untargeted Metabolomics, NMR-based Metabolomics, MS-based targeted metabolomics."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/meta/profile.gif"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["metabolomics"]

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

<img src="/img/tools/meta/profile.gif"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Metabolic profiles analysis

<p align="justify">The further development of spectroscopic and spectrometric tools for high throughput analyses of selected biochemical pathways is crucial to the acquisition of metabolome data sets of sufficient quality for metabonomics and metabolomics. Whilst metabolic fingerprinting or metabonomics assumes it is not necessary to determine levels of all individual metabolites for classification or response readouts, metabolic profiling or metabolomics absolutely requires the identification and quantification of as broad a class of metabolites as possible. 

---

## <font color=#CD5555 face="黑体">Metabolic Network analysis</font>

### BLASTX

<p align="justify">[**The Basic Local Alignment Search Tool** (BLAST)](https://blast.ncbi.nlm.nih.gov/Blast.cgi) finds regions of	local similarity between sequences. The program compares nucleotide or protein sequences to sequence databases and calculates the statistical significance of matches. BLAST can be used to infer functional and evolutionary relationships between sequences as well as help identify members of gene families.A BLAST search enables a researcher to compare a query sequence with a library or database of sequences, and identify library sequences that resemble the query sequence above a certain threshold.

<p align="justify">Different types of BLASTs are available according to the query sequences. For example, following the discovery of a previously unknown gene in the mouse, a scientist will typically perform a BLAST search of the human genome to see if humans carry a similar gene; BLAST will identify sequences in the human genome that resemble the mouse gene based on similarity of sequence. The BLAST algorithm and program were designed by `Stephen Altschul`, `Warren Gish`, `Webb Miller`, `Eugene Myers`, and `David J. Lipman` at the [National Institutes of Health](https://en.wikipedia.org/wiki/National_Institutes_of_Health) and was published in the [Journal of Molecular Biology](https://en.wikipedia.org/wiki/Journal_of_Molecular_Biology) in 1990 and cited over 50,000 times.

<img src="/img/tools/Blast.png" width= 800 height= 500 alt="blast" align="center">
**Input**: Input sequences (in [FASTA](https://en.wikipedia.org/wiki/FASTA_format) or Genbank format) and weight matrix. 

**Output**: BLAST output can be delivered in a variety of formats. These formats include HTML, plain text, and XML formatting.

<p align="justify">The details about **process** and **algorithm** coule be found [here](https://en.wikipedia.org/wiki/BLAST) and [official website](https://blast.ncbi.nlm.nih.gov/Blast.cgi)

---

### PiMP | Polyomics integrated Metabolomics Pipeline

<p align="justify">Allows users to analyze and visualize liquid chromatography – mass spectrometry (LC-MS) data. PiMP is a comprehensive and integrated web enabled pipeline that consists of five tasks: (1) project administration, (2) data upload, (3) quality control, (4) analysis parameters and (5) data interpretation. Users can define the experimental design, specify metadata and share the project with collaborators with a chosen level of permission. It aims at automatization and standardization of metabolomics analysis.

[**Official Website**](http://polyomics.mvls.gla.ac.uk/)

**Publications**:

* (2017 Bioinformatics) [PiMP my metabolome: An integrated, web-based tool for LC-MS metabolomics data.](https://www.ncbi.nlm.nih.gov/pubmed/28961954)

**Institutions(s)**:

Glasgow Polyomics, University of Glasgow, Glasgow, Scotland; 

School of Computing Science, University of Glasgow, Glasgow, Scotland

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Metabolite enrichment analysis</font>

While many tools exist for performing enrichment analysis of transcriptomic and proteomic data in order to interpret them in biological terms, almost no equivalent tools exist for metabolomic data.

---

### MetScape | Data integration : Mass spectrometry analysis

<p align="justify">Provides a bioinformatics framework for the visualization and interpretation of metabolomic and expression profiling data in the context of human metabolism. MetScape allows users to build and analyze networks of genes and compounds, identify enriched pathways from expression profiling data, and visualize changes in metabolite data. MetScape uses an internal relational database that integrates data from KEGG and EHMN.

[**Official Website**](http://metscape.ncibi.org/)

**Publications**:

* (2012 Bioinformatics) [Metscape 2 bioinformatics tool for the analysis and visualization of metabolomics and gene expression data.](https://www.ncbi.nlm.nih.gov/pubmed/22135418)

* (2010 Bioinformatics) [Metscape: a Cytoscape plug-in for visualizing and interpreting metabolomic data in the context of human metabolic networks.](https://www.ncbi.nlm.nih.gov/pubmed/20139469)

**Institutions(s)**:

National Center for Integrative Biomedical Informatics, University of Michigan, Ann Arbor, MI, USA

---

### FELLA | Metabolite enrichment analysis

<p align="justify">Enables enrichment of metabolomics data using KEGG reactions, enzymes, modules and pathways. FELLA is a metabolomics data enrichment tool that combines pathway enrichment with the flexibility of sub-network analysis. The method builds sub-pathway representations of the biology at several molecular levels, derived through a null diffusive process on a curated graph object built from the KEGG database.

[**Official Website**](https://bioconductor.org/packages/devel/bioc/html/FELLA.html)

**Publications**:

* (2017 PLoS One) [Null diffusion-based enrichment for metabolomics data.](https://www.ncbi.nlm.nih.gov/pubmed/29211807)

**Institutions(s)**:

Departament d'Enginyeria de Sistemes, Automàtica i Informàtica Industrial, Universitat Politècnica de Catalunya, Barcelona, Spain

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# MS-based untargeted Metabolomics

<p align="justify">Metabolomics is an emerging field of study in post-genomics, which aims at comprehensive analysis of small organic molecules in biological systems (Patti et al., 2012). Techniques of mass spectrometry coupled to liquid chromatography (LC–MS) stand out as dominant methods in metabolomic experiments (Dettmer et al., 2007).

---

## <font color=#CD5555 face="黑体">mGWAS</font>

Genome-wide association scans with high-throughput metabolic profiling provide unprecedented insights into how genetic variation influences metabolism and complex disease.

### MWASTools | mGWAS

<p align="justify">Allows users to visualize the results from metabolome-wide association studies (MWAS) analysis. MWASTools performs essential quality control (QC) analyses via Principal Component Analysis (PCA) and by computing the coefficients of variation (CV) of individual metabolic features. It is composed of four functional parts: (1) QC analysis; (2) MWAS analysis; (3) visualization of MWAS results; and (4) metabolite assignment using correlation analysis.

[**Official Website**](https://bioconductor.org/packages/release/bioc/html/MWASTools.html)

**Publications**:

* (2017 Bioinformatics) [MWASTools: an R/Bioconductor package for metabolome-wide association studies.](https://doi.org/10.1093/bioinformatics/btx477)

**Institutions(s)**:

Computational and Systems Medicine, Department of Surgery and Cancer, Imperial College London, UK; 

Division of Myocardial Function, National Heart and Lung Institute, Imperial College London, UK

---

### RegScan

<p align="justify">A command line tool for performing fast association analysis between allele frequencies and continuous traits. RegScan uses linear regression to estimate marker effects on continuous traits.

[**Official Website**](https://www.geenivaramu.ee/en/tools/regscan)

**Publications**:

* (2015 Brief Bioinform) [RegScan: a GWAS tool for quick estimation of allele effects on continuous traits and their combinations.](https://www.ncbi.nlm.nih.gov/pubmed/24008273)

**MAINTAINER**:

Toomas Haller <toomas.haller@ut.ee>

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# NMR-based Metabolomics/MS-based targeted metabolomics

<p align="justify">Elucidation of the chemical composition of biological samples is a main focus of systems biology and metabolomics. Because nuclear magnetic resonance (NMR) spectroscopy is a rich source of molecular information, it has a unique potential for this task.

<p align="justify">Targeted metabolomics assay platforms are extremely useful for hypothesis testing. These experiments require extensive planning to define the key metabolites in biochemical pathways of interest. Rate-limiting precursors, end-product pools, critical intermediates, and potential alternate precursors or products need to be incorporated into an assay platform.

## <font color=#CD5555 face="黑体">Spectral corrections</font>

The spectra processing step is crucial in metabolomics approaches, especially for proton NMR metabolomics profiling. During this step, noise reduction, baseline correction, peak alignment and reduction of the 1D (1)H-NMR spectral data are required in order to allow biological information to be highlighted through further statistical analyses. Above all, data reduction (binning or bucketing) strongly impacts subsequent statistical data analysis and potential biomarker discovery.

---

### NMRPipe

<p align="justify">An extensive software system for processing, analyzing, and exploiting NMR spectroscopic data.

[**Official Website**](https://spin.niddk.nih.gov/NMRPipe/)

**Publications**:

* (1995 J Biomol NMR) [NMRPipe: a multidimensional spectral processing system based on UNIX pipes.](https://www.ncbi.nlm.nih.gov/pubmed/8520220)

**Institutions(s)**:

Laboratory of Chemical Physics, National Institute of Diabetes and Digestive and Kidney Diseases, National Institutes of Health, Bethesda, MD, USA

---

### NMRPro

<p align="justify">An extensible web component that can be easily integrated in current web applications and databases, providing NMR processing and visualization functionalities. NMRPro is highly extensible to include new functionalities according to the needs of each application. It integrates server-side processing with client-side interactive visualization through three parts: a python package to efficiently process large NMR datasets on the server-side, a Django App managing server-client interaction, and SpecdrawJS for client-side interactive visualization.

[**Official Website**](https://github.com/phnmnl/container-nmrpro)

**Publications**:

* (2016 Bioinformatics) [NMRPro: an integrated web component for interactive processing and visualization of NMR spectra.](https://www.ncbi.nlm.nih.gov/pubmed/27153725)

**Institutions(s)**:

Bioinformatics Center, Institute for Chemical Research, Kyoto University, Kyoto, Japan

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Spectral deconvolution</font>

NMR spectroscopy has been an important tool for metabolomics although severe overlap of signals has limited the number of compounds, which can be unambiguously identified and quantified. Therefore, deconvolution of NMR spectra is one of the greatest challenges for NMR-based metabolomics.

---

### NMRPipe

<p align="justify">An extensive software system for processing, analyzing, and exploiting NMR spectroscopic data.

[**Official Website**](https://spin.niddk.nih.gov/NMRPipe/)

**Publications**:

* (1995 J Biomol NMR) [NMRPipe: a multidimensional spectral processing system based on UNIX pipes.](https://www.ncbi.nlm.nih.gov/pubmed/8520220)

**Institutions(s)**:

Laboratory of Chemical Physics, National Institute of Diabetes and Digestive and Kidney Diseases, National Institutes of Health, Bethesda, MD, USA

---

### BATMAN | Bayesian AuTomated Metabolite Analyser for NMR data

<p align="justify">An R package for estimating metabolite concentrations from Nuclear Magnetic Resonance spectral data using a specialised MCMC algorithm. BATMAN deconvolutes peaks from 1-dimensional NMR spectra, automatically assigns them to specific metabolites from a target list and obtains concentration estimates. The Bayesian model incorporates information on characteristic peak patterns of metabolites and is able to account for shifts in the position of peaks commonly seen in NMR spectra of biological samples. It applies a Markov Chain Monte Carlo (MCMC) algorithm to sample from a joint posterior distribution of the model parameters and obtains concentration estimates with reduced error compared with conventional numerical integration and comparable to manual deconvolution by experienced spectroscopists.

[**Official Website**](http://batman.r-forge.r-project.org/)

**Publications**:

* (2014 Nat Protoc) [Bayesian deconvolution and quantification of metabolites in complex 1D NMR spectra using BATMAN.](https://www.ncbi.nlm.nih.gov/pubmed/24853927)

* (2012 Bioinformatics) [BATMAN--an R package for the automated quantification of metabolites from nuclear magnetic resonance spectra using a Bayesian model.](https://www.ncbi.nlm.nih.gov/pubmed/22635605)

**Institutions(s)**:

Computational and Systems Medicine, Department of Surgery and Cancer, Imperial College London, London, UK; 

Department of Statistical Science, University College London, London, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Chemometric analysis</font>

Chemometric analysis programs for MS-based metabolomic analysis.

### MetaboAnalyst 

<p align="justify">Provides a user-friendly, web-based analytical pipeline for high-throughput metabolomics studies. In particular, MetaboAnalyst aims to offer a variety of commonly used procedures for metabolomic data processing, normalization, multivariate statistical analysis, as well as data annotation. The current implementation focuses on exploratory statistical analysis, functional interpretation, and advanced statistics for translational metabolomics studies.

[**Official Website**](http://www.metaboanalyst.ca/)

**Publications**:

* (2018 Nucleic Acids Res) [MetaboAnalyst 4.0: towards more transparent and integrative metabolomics analysis.](https://www.ncbi.nlm.nih.gov/pubmed/29762782)

* (2011 Bioinformatics) [MetATT: a web-based metabolomics tool for analyzing time-series and two-factor datasets.](https://www.ncbi.nlm.nih.gov/pubmed/21712247)

**Institutions(s)**:

Institute of Parasitology, and Department of Animal Science, McGill University, Ste Ann de Bellevue, Canada; 

Department of Microbiology and Immunology, McGill University, Montreal, Canada

---

### speaq | spectrum alignment and quantitation

<p align="justify">Allows Nuclear Magnetic Resonance (NMR) spectroscopy data analysis. Speaq enables raw spectra alignment and quantitation but also an analysis based on features whereby the spectra are converted to peaks which are then grouped and turned into features. The underlying core paradigm is to efficiently summarize spectra with little user interaction, high speed and most importantly little loss of information whilst greatly reducing the dimensions of the data. The package can be combined with existing tools to improve performance.

[**Official Website**](https://cran.r-project.org/web/packages/speaq/index.html)

**Publications**:

* (2018 PLoS Comput Biol) [speaq 2.0: A complete workflow for high-throughput 1D NMR spectra processing and quantification.](https://www.ncbi.nlm.nih.gov/pubmed/29494588)

* (2011 Bioinformatics) [An integrated workflow for robust alignment and simplified quantitative analysis of NMR spectrometry data.](https://www.ncbi.nlm.nih.gov/pubmed/22014236)

**Institutions(s)**:

Advanced Database Research and Modelling (ADReM), Department of Mathematics and Computer Science, University of Antwerp, Antwerp, Belgium

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Metabolite identification</font>

Identification and quantification programs for NMR-based metabolomic analysis.

### W4M | Workflow4Metabolomics

<p align="justify">Permits comprehensive metabolomics data pre-processing, statistical analysis and interpretation. W4M includes computational modules for data normalization, multivariate analysis and annotation. It can create interactive web-based documents showing the results of the analyses, and users can share them with collaborators directly on the platform. This tool enables multi-omics analyses in a global systems-biology approach.

[**Official Website**](http://workflow4metabolomics.org/)

**Publications**:

* (2017 Int J Biochem Cell Biol) [Create, run, share, publish, and reference your LC-MS, FIA-MS, GC-MS, and NMR data analysis workflows with the Workflow4Metabolomics 3.0 Galaxy online infrastructure for metabolomics.](https://www.ncbi.nlm.nih.gov/pubmed/28710041)

**Institutions(s)**:

INRA, UMR 1019, PFEM, Saint Genes Champanelle, France;

CNRS, UPMC, FR2424, ABiMS, Station Biologique, Roscoff, France; INRA, UMR 1331, PF MetaToul-AXIOM, Toxalim, Toulouse, France

---

### MetaboAnalyst 

<p align="justify">Provides a user-friendly, web-based analytical pipeline for high-throughput metabolomics studies. In particular, MetaboAnalyst aims to offer a variety of commonly used procedures for metabolomic data processing, normalization, multivariate statistical analysis, as well as data annotation. The current implementation focuses on exploratory statistical analysis, functional interpretation, and advanced statistics for translational metabolomics studies.

[**Official Website**](http://www.metaboanalyst.ca/)

**Publications**:

* (2018 Nucleic Acids Res) [MetaboAnalyst 4.0: towards more transparent and integrative metabolomics analysis.](https://www.ncbi.nlm.nih.gov/pubmed/29762782)

* (2011 Bioinformatics) [MetATT: a web-based metabolomics tool for analyzing time-series and two-factor datasets.](https://www.ncbi.nlm.nih.gov/pubmed/21712247)

**Institutions(s)**:

Institute of Parasitology, and Department of Animal Science, McGill University, Ste Ann de Bellevue, Canada; 

Department of Microbiology and Immunology, McGill University, Montreal, Canada

---

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/metabolomics-category)

[*Image Citation*](https://www.aau.at/en/social-ecology/research/long-term-socio-ecological-research-and-environmental-history/)

---