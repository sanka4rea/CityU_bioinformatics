+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Non-Coding RNA"

weight = 60
# Project summary to display on homepage.
summary = "Including: Non-Coding RNA Analysis, sRNA-seq analysis, miRNA Array analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/trans/non.jpg"

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

<img src="/img/tools/trans/non.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Non-Coding RNA Analysis

<p align="justify">**Noncoding RNAs** (ncRNAs) accomplish a remarkable variety of biological functions. They regulate gene expression at the levels of transcription, RNA processing, and translation. They protect genomes from foreign nucleic acids. They can guide DNA synthesis or genome rearrangement. For ribozymes and riboswitches, the RNA structure itself provides the biological function, but most ncRNAs operate as RNA-protein complexes, including ribosomes, snRNPs, snoRNPs, telomerase, microRNAs, and long ncRNAs. [Source](http://dx.doi.org/10.1016/j.cell.2014.03.008)

---

## <font color=#CD5555 face="黑体">miRNA Target Prediction</font>

### TargetScan

<p align="justify">Allows prediction of biological targets of miRNAs. With TargetScan user has to enter a specie, a human gene symbol, and select either a broadly conserved microRNA family, a conserved microRNA family or a poorly conserved but confidently annotated microRNA family.

[**Official Website**](http://www.targetscan.org/vert_72/)

**Publications**:

* (Lewis et al., 2005) [Conserved seed pairing, often flanked by adenosines, indicates that thousands of human genes are microRNA targets](https://www.ncbi.nlm.nih.gov/pubmed/15652477).  Cell. 
* (Wei et al., 2017) [miRNA-223 suppresses FOXO1 and functions as a potential tumor marker in breast cancer](https://www.ncbi.nlm.nih.gov/pubmed/28719355).  Cell Mol Biol.  

**Institutions(s)**: 

Department of Breast Surgery , Cancer Hospital of China Medical University, Liaoning Cancer Hospital and Institute, Shenyang, China

---

### PicTar 

<p align="justify">Detects microRNA target genes for single microRNA and for combinations of microRNA. PicTar is based on the Ahab algorithm for the identification of combinations of transcription factor binding sites. This software can recover published microRNA targets that are likely to be regulated by microRNAs that are co-expressed or act in a common pathway.

[**Official Website**](https://pictar.mdc-berlin.de/)

**Publications**:

* (Krek et al., 2005) [Combinatorial microRNA target predictions](https://www.ncbi.nlm.nih.gov/pubmed/15806104).  Nat Genet.   

**Institutions(s)**: 

Center for Comparative Functional Genomics, Department of Biology, New York University, New York, NY, USA

---

### psRNATarget

<p align="justify">A plant small RNA target analysis server, which features two important analysis functions: (i) reverse complementary matching between small RNA and target transcript using a proven scoring schema, and (ii) target-site accessibility evaluation by calculating unpaired energy (UPE) required to 'open' secondary structure around small RNA's target site on mRNA. The psRNATarget incorporates recent discoveries in plant miRNA target recognition, e.g. it distinguishes translational and post-transcriptional inhibition, and it reports the number of small RNA/target site pairs that may affect small RNA binding activity to target transcript.

[**Official Website**](http://plantgrn.noble.org/psRNATarget/)

**Publications**:

* (Dai and Zhao, 2011) [psRNATarget: a plant small RNA target analysis server](https://www.ncbi.nlm.nih.gov/pubmed/21622958).  Nucleic Acids Res.  
* (Dai et al., 2018) [psRNATarget: a plant small RNA target analysis server (2017 release)](https://www.ncbi.nlm.nih.gov/pubmed/29718424).  Nucleic Acids Res. 

**Institutions(s)**: 

Plant Biology Division, The Samuel Roberts Noble Foundation, Ardmore, OK, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">miRNA Enrichment</font>

### DIANA-miRPath

<p align="justify">A miRNA pathway analysis web-server, providing accurate statistics, while being able to accommodate advanced pipelines. mirPath can utilize predicted miRNA targets (in CDS or 3’-UTR regions) provided by the DIANA-microT-CDS algorithm or even experimentally validated miRNA interactions derived from DIANA-TarBase. These interactions (predicted and/or validated) can be subsequently combined with sophisticated merging and meta-analysis algorithms.

[**Official Website**](http://snf-515788.vm.okeanos.grnet.gr/)

**Publications**:

* (Vlachos et al., 2015) [DIANA-miRPath v3.0: deciphering microRNA function with experimental support](https://www.ncbi.nlm.nih.gov/pubmed/25977294).  Nucleic Acids Res

**Institutions(s)**:

DIANA-Lab, Department of Electrical & Computer Engineering, University of Thessaly, Volos, Greece

---

### FAME | Functional Assignment of MicroRNAs via Enrichment

<p align="justify">Uses computational target predictions to automatically infer the processes affected by human miRNAs. FAME addresses specific characteristics of miRNA regulation and is based on a compendium of experimentally verified miRNA-pathway and miRNA-process associations. It predicts novel miRNA-regulated pathways, refines the annotation of miRNAs for which only crude functions are known, and assigns differential functions to miRNAs with closely related sequences.

[**Official Website**](http://acgt.cs.tau.ac.il/fame/)

[**Documentation**](http://acgt.cs.tau.ac.il/expander/help/ver7.1Help/html/)

**Publications**:

* (Ulitsky et al., 2010) [Towards computational prediction of microRNA function and activity](https://www.ncbi.nlm.nih.gov/pubmed/20576699).  Nucleic Acids Res. 

**Institutions(s)**:

Blavatnik School of Computer Science, Tel Aviv University, Tel Aviv, Israel; Center for Regenerative Medicine, The Scripps Research Institute, La Jolla, CA, USA

---

### miTEA

<p align="justify">A framework for miRNA target enrichment analysis. miTEA takes as input a ranked list of genes and then finds miRNAs of which targets are enriched in the top of the input list. miTEA uses a novel statistical analysis that takes into account the rich information available from high-throughput experiments as well as from the different miTPAs. We show how miTEA can be applied to detect miRNA activity in different experiments and shed light into miRNA activity map in healthy and cancer samples. miTEA is a web-based tool allowing the community an easy and efficient free access.

[**Official Website**](http://cbl-gorilla.cs.technion.ac.il/miTEA/)

**Publications**:

* (Steinfeld et al., 2013) [miRNA target enrichment analysis reveals directly active miRNAs in health and disease](https://www.ncbi.nlm.nih.gov/pubmed/23209027).  Nucleic Acids Res. 

**Institutions(s)**:

Computer Science Department, Technion—Israel Institute of Technology, Haifa, Israel; Agilent Laboratories, Agilent Technologies, Tel Aviv, Israel

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">miRNA-disease Association Prediction</font>

### miRPD

<p align="justify">An approach in which miRNAs are linked to diseases via proteins, thereby directly providing biological hypotheses. Specifically, we infer miRNA–disease associations by network analysis of known or predicted miRNA–protein associations and text-mined protein–disease associations. To account for the variable reliability of both types of associations, we provide a scoring scheme that allows for ranking of the inferences by confidence.

[**Official Website**](http://mirpd.jensenlab.org/HTML/miRPD?page=home)

**Publications**:

* (Mørk et al., 2014) [Protein-driven inference of miRNA-disease associations](https://www.ncbi.nlm.nih.gov/pubmed/24273243).  Bioinformatics.  

**Institutions(s)**:

Center for non-coding RNA in Technology and Health, Novo Nordisk Foundation Center for Protein Research, University of Copenhagen, Denmark

---

### MCMG

<p align="justify">Allows users to deduce microRNA– gene interactions with paired expression profiles. MCMG is a standalone software that is able to detect interactions relative to a specific cancer type or common to multiple cancers. It can be used for (i) determining common interactions, (ii) identifying specific miRNA regulations for each cancer; (iii) exploring the possible hidden links among cancers thanks to a quantitative estimate.

[**Official Website**](http://zhaocenter.org/software/)

**Publications**:

* (Chen et al., 2013) [Joint analysis of expression profiles from multiple cancers improves the identification of microRNA-gene interactions](https://www.ncbi.nlm.nih.gov/pubmed/23772050).  Bioinformatics. 

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">RNAi Reagent Design</font>

### RNAxs

<p align="justify">Helps you to design potent siRNAs to knock down your gene(s) of interest. RNAxs is based on the RNAplfold program to assess the mRNA target site accessibility. RNAxs was trained on two different datasets, one targeting 3'UTRs and the other one designed to repress coding sequences only.

[**Official Website**](http://rna.tbi.univie.ac.at/cgi-bin/RNAxs/RNAxs.cgi)

**Publications**:

* (Tafer et al., 2008) The impact of target site accessibility on the design of effective siRNAs.  Nat Biotechnol.   

**Institutions(s)**:

Institute of Theoretical Biochemistry (TBI), University of Vienna, Austria

---

### WMD | Web MicroRNA Designer

<p align="justify">Automates artificial microRNAs (amiRNAs) design. WMD3 uses the favorite gene(s), which the user want to silence, and designs 21mer amiRNA sequences. User will retrieve oligo sequences to express the small RNA from endogenous miRNA precursors. WMD3 was initially implemented for Arabidopsis thaliana, but has now been extended to more than 30 additional species for which genome or extensive EST (expressed sequence tag) information is available. WMD3 is designed to optimize both intrinsic small RNA properties as well as specificity within the given transcriptome.

[**Official Website**](http://wmd3.weigelworld.org/cgi-bin/webapp.cgi)

[**Documentation**](http://wmd3.weigelworld.org/cgi-bin/webapp.cgi?page=Help;project=stdwmd)

**Publications**:

* (Ossowski et al., 2008) [Gene silencing in plants using artificial microRNAs and other small RNAs](https://www.ncbi.nlm.nih.gov/pubmed/18269576).  Plant J. 
* (Schwab et al., 2006) [Highly specific gene silencing by artificial microRNAs in Arabidopsis](https://www.ncbi.nlm.nih.gov/pubmed/16531494).  Plant Cell. 

**Institutions(s)**:

Department of Molecular Biology, Max Planck Institute for Developmental Biology, Tübingen, Germany

---

### E-RNAi 

<p align="justify">Offers a platform dedicated to reagents management. E-RNAi contains two mains functions: (i) allowing users to select target sequences for creating reagents and; (ii) assessing existing RNAi reagents. The application can deal with long dsRNAs, siRNAs and includes twelve implemented genomes such as Acyrthosiphon pisum, Apis mellifera or Aedes aegypti. Nevertheless, these organisms can be extended by user request.

[**Official Website**](http://www.dkfz.de/signaling/e-rnai3/)

**Publications**:

* (Horn and Boutros, 2010) [E-RNAi: a web application for the multi-species design of RNAi reagents--2010 update](https://www.ncbi.nlm.nih.gov/pubmed/20444868).  Nucleic Acids Res
* (Arziman et al., 2005) [E-RNAi: a web application to design optimized RNAi constructs](https://www.ncbi.nlm.nih.gov/pubmed/15980541).  Nucleic Acids Res. 

**Institutions(s)**:

German Cancer Research Center, Division Signaling and Functional Genomics, Heidelberg, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">High-throughput RNAi Screening</font>

### cellHTS

<p align="justify">A software package implemented in Bioconductor/R to analyze cell-based high-throughput RNAi screens. The cellHTS2 package is the new version of the cellHTS package, offering improved functionality for the analysis and integration of multi-channel screens and multiple screens. We advise users starting new projects to use cellHTS2. For your existing projects, you may keep using cellHTS, which is still supported.

[**Official Website**](https://www.bioconductor.org/packages/release/bioc/html/cellHTS2.html)

**Publications**:

* (Boutros et al., 2006) [Analysis of cell-based RNAi screens](https://www.ncbi.nlm.nih.gov/pubmed/16869968).  Genome Biol.  

**Institutions(s)**:

Signaling and Functional Genomics, German Cancer Research Center, Heidelberg, Germany; EMBL - European Bioinformatics Institute, Cambridge, UK

---

### CARD

<p align="justify">Integrates analysis and visualization of RNAi screen data. CARD allows the user to seamlessly carry out sequential steps in a rigorous data analysis workflow, including normalization, off-target analysis, integration of gene expression data, optimal thresholds for hit selection and network/pathway analysis. CARD also uses cutting-edge data visualization techniques that allow users to interact dynamically with the figures and tables displayed on the web-browser to facilitate the hit selection process.

[**Official Website**](https://card.niaid.nih.gov/)

**Publications**:

* (Dutta et al., 2016) [An interactive web-based application for Comprehensive Analysis of RNAi-screen Data](https://www.ncbi.nlm.nih.gov/pubmed/26902267).  Nat Commun.   

**Institutions(s)**:

Laboratory of Systems Biology, National Institute of Allergy and Infectious Diseases, National Institutes of Health, Bethesda, MA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Small RNA sequencing Data analysis (sRNA-seq Analysis)

<p align="justify">Qualitative and quantitative analysis of **small non-coding RNAs** by next generation sequencing (smallRNA-Seq) represents a novel technology increasingly used to investigate with high sensitivity and specificity RNA population comprising microRNAs and other regulatory small transcripts. [Source](https://www.ncbi.nlm.nih.gov/pubmed/24330401)

## <font color=#CD5555 face="黑体">tRNA-derived RNA Annotation</font>

### tRF2Cancer

<p align="justify">Facilitates the identification of tRNA-derived small RNA fragments (tRFs) to study their expression in cancers from deep-sequencing data with user-friendly interfaces and time-efficient algorithms. tRF2Cancer provides three useful tools for researchers to investigate tRFs. ‘tRFfinder’ is developed to identify genuine tRF signals from random degradation RNA fragments. One statistical method, the binomial test, is introduced to evaluate the significance of the abundance of sequenced sRNAs distributed on each tRNA. A classification method is subsequently used to annotate the types of tRFs based on their position of origin in pre-tRNA or mature tRNA; the four types of tRFs are tRF-5, tRF-3, tRF-1 and tRF-novel. ‘tRFinCancer’ enables users to inspect the expression of any tRFs in different types of cancers. ‘tRFBrowser’ presents both the sites of origin and the distribution of modification sites of tRFs, including m5C, 2′-O-Me, Ψ and m6A., on their corresponding source tRNA. In addition to cancer samples, tRFfinder can be applied to many samples from different kind of tissue/disease context.

[**Official Website**](http://rna.sysu.edu.cn/tRFfinder/)

[**Documentation**](http://rna.sysu.edu.cn/tRFfinder/manual.php)

**Publications**:

* (Zheng et al., 2016) [tRF2Cancer: A web server to detect tRNA-derived small RNA fragments (tRFs) and their expression in multiple cancers](https://www.ncbi.nlm.nih.gov/pubmed/27179031).  Nucleic Acids Res.   

**Institutions(s)**:

Key Laboratory of Gene Engineering of the Ministry of Education, State Key Laboratory of Biocontrol, School of Life Sciences, Sun Yat-sen University, Guangzhou, China

---

### HAMR

<p align="justify">A web application that allows you to detect and classify modified nucleotides in RNA-seq data. HAMR scans RNA-sequencing data for sites showing potential signatures of nucleotide modification. Simply point it to your RNA-seq data it will scan the entire transcriptome. You can also limit the analysis to particular genomic regions of interest, either by entering one or providing a BED file containing the intervals.

[**Official Website**](http://tesla.pcbi.upenn.edu/hamr/)

**Publications**:

* (Ryvkin et al., 2013) [HAMR: high-throughput annotation of modified ribonucleotides](https://www.ncbi.nlm.nih.gov/pubmed/24149843).  RNA.    

**Institutions(s)**:

Genomics and Computational Biology Graduate Group, University of Pennsylvania, Philadelphia, PA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">ncRNA Identification</font>

### miRDeep

<p align="justify">Serves for the prediction of micro-RNA (miRNA) from small RNAseq data. miRDeep is a software for determining miRNAs, displaying RNAseq reads and the number of reads relative to the predicted pre-miRNA. It can provide the target prediction for both known and novel miRNAs expression levels, and display them in an interface showing each RNAseq read relative to the pre-miRNA hairpin.

[**Official Website**](https://github.com/rajewsky-lab/mirdeep2)

[**Galaxy**](https://toolshed.g2.bx.psu.edu/repository?repository_id=f94169f4643e4cdc)

**Publications**:

* (Friedländer et al., 2008) [Discovering microRNAs from deep sequencing data using miRDeep](https://www.ncbi.nlm.nih.gov/pubmed/18392026).  Nat Biotechnol.
* (Friedländer et al., 2012) [miRDeep2 accurately identifies known and hundreds of novel microRNA genes in seven animal clades](https://www.ncbi.nlm.nih.gov/pubmed/21911355). Nucleic Acids Res. 

**Institutions(s)**:

Laboratory for Systems Biology of Gene Regulatory Elements, Berlin Institute for Medical Systems Biology at the Max-Delbruck-Center for Molecular Medicine, Berlin-Buch, Germany

---

### omiRas

<p align="justify">A Web service for the analysis of ncRNA datasets derived from Illumina sRNA-Seq experiments. Starting with raw sequencing data, omiRas offers an efficient way to analyze differential expression of ncRNAs between two groups and to assign functions to differentially expressed miRNAs. MiRNA–mRNA interaction databases allow the user to construct networks of interesting miRNAs and mRNAs to identify miRNAs with implications in the development of differential gene signatures.

[**Official Website**](http://tools.genxpro.net/omiras/)

**Publications**:

* (Müller et al., 2013) [omiRas: a Web server for differential expression analysis of miRNAs derived from small RNA-Seq data](https://www.ncbi.nlm.nih.gov/pubmed/23946503). Bioinformatics. 

**Institutions(s)**:

Plant Molecular Biology, Institute of Molecular BioSciences, University of Frankfurt am Main, Frankfurt am Main, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">IsomiR detection</font>

### DeAnnIso

<p align="justify">An online tool for detection and annotation of isomiRs from small RNA sequencing data. DeAnnIso can detect all the isomiRs in an uploaded sample, and can extract the differentially expressing isomiRs from paired or multiple samples. Once the isomiRs detection is accomplished, detailed annotation information, including isomiRs expression, isomiRs classification, SNPs in miRNAs and tissue specific isomiR expression are provided to users. Furthermore, DeAnnIso provides a comprehensive module of target analysis and enrichment analysis for the selected isomiRs. Taken together, DeAnnIso is convenient for users to screen for isomiRs of their interest and useful for further functional studies. DeAnnIso is able to handle the data from single, paired and group samples, and can complete the assigned job within 1 h, depending on data size, species and selected parameters for analysis.

[**Official Website**](http://mcg.ustc.edu.cn/bsc/deanniso/)

**Publications**:

* (Zhang et al., 2016) [DeAnnIso: a tool for online detection and annotation of isomiRs from small RNA sequencing data](https://www.ncbi.nlm.nih.gov/pubmed/27179030).  Nucleic Acids Res. 

**Institutions(s)**:

Molecular and Cell Genetics Laboratory, The CAS Key Laboratory of Innate Immunity and Chronic Disease, Hefei National Laboratory for Physical Sciences at Microscale and School of Life Sciences, University of Science and Technology of China, Hefei

---

### isomiR-SEA

<p align="justify">Produces accurate miRNAs expression level quantification and both isomiRs and miRNA-mRNA interaction sites precise classification. isomiR-SEA exploits a miRNA specific alignment algorithm that is able to correlate the encountered mismatches with their positions on the miRNA sequence. It can be useful for analyses of large datasets. This tool allows users to design wide miRNAs studies.

[**Official Website**](http://eda.polito.it/isomir-sea/)

**Publications**:

* (Urgese et al., 2016) [isomiR-SEA: an RNA-Seq analysis tool for miRNAs/isomiRs expression level profiling and miRNA-mRNA interaction sites evaluation](https://www.ncbi.nlm.nih.gov/pubmed/27036505). BMC Bioinformatics. 

**Institutions(s)**:

Department of Control and Computer Engineering DAUIN, Politecnico di Torino, Turin, Italy

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

#  miRNA Array analysis

### InCroMAP

<p align="justify">A tool for the analysis and visualization of high-level microarray data from individual or multiple different platforms. Currently, InCroMAP supports mRNA, microRNA, DNA methylation and protein modification datasets. Several methods are offered that allow for an integrated analysis of data from those platforms. The available features of InCroMAP range from visualization of DNA methylation data over annotation of microRNA targets and integrated gene set enrichment analysis to a joint visualization of data from all platforms in the context of metabolic or signalling pathways.

[**Official Website**](http://www.ra.cs.uni-tuebingen.de/software/InCroMAP/)

**Publications**:

* (Eichner et al., 2014) [Integrated enrichment analysis and pathway-centered visualization of metabolomics, proteomics, transcriptomics, and genomics data by using the InCroMAP software](https://www.ncbi.nlm.nih.gov/pubmed/24811976). J Chromatogr.  
* (Wrzodek et al., 2013) [InCroMAP: integrated analysis of cross-platform microarray and pathway data](https://www.ncbi.nlm.nih.gov/pubmed/23257199).  Bioinformatics. 

**Institutions(s)**:

Center for Bioinformatics Tuebingen (ZBIT), University of Tuebingen, Tübingen, Germany

---

### AgiMicroRna

<p align="justify">A package for the pre-processing and differential expression analysis of Agilent microRNA array data. For the pre-processing of the microRNA signal, AgiMicroRNA incorporates the robust multiarray average algorithm, a method that produces a summary measure of the microRNA expression using a linear model that takes into account the probe affinity effect. To obtain a normalized microRNA signal useful for the statistical analysis, AgiMicroRna offers the possibility of employing either the processed signal estimated by the robust multiarray average algorithm or the processed signal produced by the Agilent image analysis software. It also incorporates different graphical utilities to assess the quality of the data. AgiMicroRna uses the linear model features implemented in the limma package to assess the differential expression between different experimental conditions and provides links to the miRBase for those microRNAs that have been declared as significant in the statistical analysis.

[**Official Website**](http://www.bioconductor.org/packages/release/bioc/html/AgiMicroRna.html)

[**Documentation**](http://www.bioconductor.org/packages/release/bioc/manuals/AgiMicroRna/man/AgiMicroRna.pdf)

**Publications**:

* (López-Romero, 2011) [Pre-processing and differential expression analysis of Agilent microRNA arrays using the AgiMicroRna Bioconductor library](https://www.ncbi.nlm.nih.gov/pubmed/21269452).  BMC Genomics. 

**Institutions(s)**:

Epidemiology, Atherothrombosis and Imaging Department Centro Nacional de Investigaciones Cardiovasculares Carlos III (CNIC), Melchor Fernández Almagro, Madrid, Spain

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/transcriptomics-category)

[*Image Citation*](https://en.wikipedia.org/wiki/Transcription_(biology))

---