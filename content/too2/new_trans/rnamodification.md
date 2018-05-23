+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "RNA Modifications"

weight = 30
# Project summary to display on homepage.
summary = "Including: RNA Modifications Analysis, MeRIP-seq Analysis, Degradome-seq Analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/trans/modification.png"

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

<img src="/img/tools/trans/modification.png"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# RNA Modifications Analysis

<p align="justify">From a biosynthetic point of view, the roughly 100 known different RNA nucleotide modifications can be easily divided according to their complexity. There are simple chemical transformations, such as addition of a methyl group or bond isomerization of uridine to yield pseudouridine, and there are more complex multistep transformations involving the action of several enzymes in a defined order. [source](https://doi.org/10.1093/nar/gkj471)

## <font color=#CD5555 face="黑体">Protein-binding Region Prediction</font>

### RNAcompete

<p align="justify">Allows the study of RNA-protein interactions. RNAcompete provides an estimate of relative preference for a large number of individual sequences using a single binding reaction. It also permits to design arrays that focus on variants of a specific type of sequence and structure. Finally, this method can be used to reliably identify preferred binding sequences for RNA-binding proteins (RBPs), whether these are in structured or unstructured RNA contexts.

[**Official Website**](http://hugheslab.ccbr.utoronto.ca/supplementary-data/RNAcompete/)

**Publications**:

* (Ray et al., 2009) [Rapid and systematic analysis of the RNA recognition specificities of RNA-binding proteins](https://www.ncbi.nlm.nih.gov/pubmed/19561594).  Nat Biotechnol. 

**Institutions(s)**: 

Banting and Best Department of Medical Research, University of Toronto, Toronto, ON, Canada; Department of Computer Science, University of Toronto, Toronto, ON, Canada

---

### catRAPID omics 

<p align="justify">A server for large-scale calculations of protein-RNA interactions. catRAPID omics allows (i) predictions at proteomic and transcriptomic level; (ii) use of protein and RNA sequences without size restriction; (iii) analysis of nucleic acid binding regions in proteins; and (iv) detection of RNA motifs involved in protein recognition.

[**Official Website**](http://s.tartaglialab.com/page/catrapid_omics_group)

**Publications**:

* (Agostini et al., 2013) [catRAPID omics: a web server for large-scale prediction of protein-RNA interactions](https://www.ncbi.nlm.nih.gov/pubmed/23975767).  Bioinformatics. 
* (Bellucci et al., 2011) [Predicting protein associations with long noncoding RNAs](https://www.ncbi.nlm.nih.gov/pubmed/21623348).  Nat Methods. 

**Institutions(s)**: 

Gene Function and Evolution, Bioinformatics and Genomics, Centre for Genomic Regulation (CRG) and Universitat Pompeu Fabra (UPF), Barcelona, Spain

---

### RBPmap

<p align="justify">A web server for accurate prediction and mapping of RBP binding sites. RBPmap has been developed specifically for mapping RBPs in human, mouse and Drosophila melanogaster genomes, though it supports other organisms too. RBPmap enables the users to select motifs from a large database of experimentally defined motifs. In addition, users can provide any motif of interest, given as either a consensus or a PSSM.

[**Official Website**](http://rbpmap.technion.ac.il/)

**Publications**:

* (Paz et al., 2014) [RBPmap: a web server for mapping binding sites of RNA-binding proteins](https://www.ncbi.nlm.nih.gov/pubmed/24829458).  Nucleic Acids Res. 

**Institutions(s)**: 

Department of Biology, Technion - Israel Institute of Technology, Technion City, Haifa, Israel

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Alternative Splicing Annotation</font>

### APPRIS

<p align="justify">The main goal of developing the APPRIS WebServer and WebServices is to allow users to annotate splice isoforms and select a principal isoform for vertebrate genome species beyond those that are annotated in the APPRIS Database, to annotate genes and variants that are missing from the APPRIS Database, and to annotate their experimental results with existing annotations. The APPRIS WebServer has been designed to be used for the comparison of splice isoform annotations for individual genes, while the APPRIS WebServices have been created to allow access to the APPRIS Database and to run an automatic version of the APPRIS server, using REST architecture to be portable, modular and flexible in the automation of programmatic scripts.

[**Official Website**](http://appris.bioinfo.cnio.es/)

**Publications**:

* (Rodriguez et al., 2015) [APPRIS WebServer and WebServices](https://www.ncbi.nlm.nih.gov/pubmed/25990727).  Nucleic Acids Res. 
* (Rodriguez et al., 2013) [APPRIS: annotation of principal and alternative splice isoforms](https://www.ncbi.nlm.nih.gov/pubmed/23161672).  Nucleic Acids Res. 

**Institutions(s)**: 

Spanish National Bioinformatics Institute (INB) and Structural Biology and Biocomputing Programme, Spanish National Cancer Research Centre (CNIO), Madrid, Spain

---

### rPGA

<p align="justify">Allows users to discover hidden splice junctions by mapping personal RNA-seq data to the matching personal genome sequence. rPGA personalizes the reference genome according to an individual’s single nucleotide polymorphisms (SNPs) and then maps the individual’s transcriptome to the corresponding personal genome, and discovers novel splice variants specific to the individual. This software was applied to analyze RNA-seq data from individuals with whole-genome genotype data in the 1000 Genomes project.

[**Official Website**](https://github.com/Xinglab/rPGA)

[**Documentation**] (https://github.com/Xinglab/rPGA/wiki)

**Publications**:

* (Stein et al., 2015) [Discover hidden splicing variations by mapping personal transcriptomes to personal genomes](https://www.ncbi.nlm.nih.gov/pubmed/26578562).  Nucleic Acids Res 
* (Stein et al., 2017) [Using RNA-Seq to Discover Genetic Polymorphisms That Produce Hidden Splice Variants](https://www.ncbi.nlm.nih.gov/pubmed/28766294).  Methods Mol Biol. 

**Institutions(s)**:

Department of Microbiology, Immunology, and Molecular Genetics, University of California, Los Angeles, Los Angeles, CA, USA

---

### Exogean

<p align="justify">Predicts transcripts human mRNA and mouse protein sequence alignments. Exogean enables prediction of several alternative transcripts per gene. It can be useful for annotation of eukaryote protein coding genes based on alignments with proteins from a different species and/or mRNAs from the same species. This tool produces information on each predicted gene and transcript that summarizes their structure, the evidence used, the problems and conflicts encountered and the solutions applied.

[**Official Website**](https://github.com/DyogenIBENS/Exogean)

**Publications**:

* (Djebali et al., 2006) [Exogean: a framework for annotating protein-coding genes in eukaryotic genomic DNA](https://www.ncbi.nlm.nih.gov/pubmed/16925841).  Genome Biol. 

**Institutions(s)**:

Dyogen Lab, CNRS UMR8541, Ecole Normale Superieure, Paris, France; IBISC Lab, CNRS FRE2873, Universite d’Evry Val d’Essonne, Genopole, Evry, France

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">RNA Methylation Prediction</font>

### SRAMP

<p align="justify">A mammalian m6A sites predictor. SRAMP achieves promising performance both in cross-validation tests on its training dataset, and in the rigorous independent tests. Another highlighting trait of this predictor is that only RNA sequences are required when running a prediction and no external -omics data are loaded. With either kind of input sequence, SRAMP achieves competitive performance in both cross-validation tests and rigorous independent benchmarking tests. SRAMP serves as a useful tool to predict m6A modification sites on the RNA sequences of interests.

[**Official Website**](http://www.cuilab.cn/sramp)

**Publications**:

* (Zhou et al., 2016) [SRAMP: prediction of mammalian N6-methyladenosine (m6A) sites based on sequence-derived features](https://www.ncbi.nlm.nih.gov/pubmed/26896799).  Nucleic Acids Res.  

**Institutions(s)**:

Department of Biomedical Informatics, School of Basic Medical Sciences, Peking University, Beijing, China

---

### iRNAm5C-PseDNC

<p align="justify">Predicts the identifying RNA 5-methylcytosine modification sites. iRNAm5C-PseDNC is a web-server and a predictor developed by incorporating ten types of physical-chemical properties into pseudo dinucleotide composition. To obtain the predicted result with the anticipated success rate, the user have to employ the entire sequence of the query RNA rather than its fragment as an input.

[**Official Website**](http://www.jci-bioinfo.cn/iRNAm5C-PseDNC)

**Publications**:

* (Qiu et al., 2017) [iRNAm5C-PseDNC: identifying RNA 5-methylcytosine sites by incorporating physical-chemical properties into pseudo dinucleotide composition](https://www.ncbi.nlm.nih.gov/pubmed/28476023). Oncotarget. 

**Institutions(s)**:

Department of Computer Science and Bond Life Science Center, University of Missouri, Columbia, MO, USA

---

### m6Apred

<p align="justify">A support vector machine based-method is proposed to identify m(6)A sites in Saccharomyces cerevisiae genome. In this model, RNA sequences are encoded by their nucleotide chemical property and accumulated nucleotide frequency information. It is observed in the jackknife test that the accuracy achieved by the proposed model in identifying the m(6)A site was 78.15%.

[**Official Website**](http://lin-group.cn/server/m6Apred.php)

**Publications**:

* (Chen et al., 2015) [Identification and analysis of the N(6)-methyladenosine in the Saccharomyces cerevisiae transcriptome](https://www.ncbi.nlm.nih.gov/pubmed/26343792).  Sci Rep.  

**Institutions(s)**:

Department of Physics, School of Sciences, and Center for Genomics and Computational Biology, Hebei United University, Tangshan, China

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Methylated RNA Immunoprecipitation Sequencing Data Analysis (MeRIP-seq Analysis)

RNA modifications, especially methylation of the N6 position of adenosine (m6A), represent an emerging research frontier in RNA biology. Along with the development of MeRIP-Seq ([Meyer et al., 2012](https://www.cell.com/abstract/S0092-8674(12)00536-3)) also called m6A-seq ([Dominissini et al., 2012](https://www.ncbi.nlm.nih.gov/pubmed/22575960)), researchers are knowable to carry out in-depth studies on m6A distribution and function of related genes.

## <font color=#CD5555 face="黑体">Spliced Read Alignment</font>

### TopHat

<p align="justify">Aligns RNA-Seq reads to mammalian-sized genomes using the ultra high-throughput short read aligner Bowtie. TopHat also analyzes the mapping results to identify splice junctions between exons. It can align reads of various lengths produced by the latest sequencing technologies, while allowing for variable-length indels with respect to the reference genome. The tool combines the ability to identify novel splice sites with direct mapping to known transcripts, producing sensitive and accurate alignments, even for highly repetitive genomes or in the presence of pseudogenes.

[**Official Website**](http://ccb.jhu.edu/software/tophat/index.shtml)

[**Galaxy**](https://toolshed.g2.bx.psu.edu/repository?repository_id=3bece861a6a3608c)

[**Documentation**](Documentation:  http://ccb.jhu.edu/software/tophat/manual.shtml)

**Publications**:

* (Kim et al., 2013) [TopHat2: accurate alignment of transcriptomes in the presence of insertions, deletions and gene fusions](https://www.ncbi.nlm.nih.gov/pubmed/23618408).  Genome Biol.   
* (Trapnell et al., 2009) [TopHat: discovering splice junctions with RNA-Seq](https://www.ncbi.nlm.nih.gov/pubmed/19289445).  Bioinformatics. 

**Institutions(s)**:

Center for Bioinformatics and Computational Biology, University of Maryland, College Park, MD, USA; Department of Computer Science, University of Maryland, College Park, MD, USA

---

### HISAT | Hierarchical Indexing for Spliced Alignment of Transcripts

<p align="justify">A fast and sensitive spliced alignment program for mapping RNA-seq reads. In addition to one global FM index that represents a whole genome, HISAT uses a large set of small FM indexes that collectively cover the whole genome (each index represents a genomic region of ~64,000 bp and ~48,000 indexes are needed to cover the human genome). These small indexes (called local indexes) combined with several alignment strategies enable effective alignment of RNA-seq reads, in particular, reads spanning multiple exons. The memory footprint of HISAT is relatively low (~4.3GB for the human genome).

[**Official Website**](http://www.ccb.jhu.edu/software/hisat/index.shtml)

**Publications**:

* (Kim et al., 2015) [HISAT: a fast spliced aligner with low memory requirements](https://www.ncbi.nlm.nih.gov/pubmed/25751142).  Nat Methods. 

**Institutions(s)**:

Center for Computational Biology, McKusick-Nathans Institute of Genetic Medicine, Johns Hopkins University School of Medicine, Baltimore, MD, USA

---

### Subread

<p align="justify">Assists users in mapping reads to a reference genome. Subread consists of a seed-and-vote step, that achieves local alignment simultaneously in multiple parts of the read. This strategy uses a large number of short equi-spaced seeds from each read, called subreads. It allows all the subreads to vote on the optimal location for the read.

[**Official Website**](http://subread.sourceforge.net/)

[**Documentation**](https://toolshed.g2.bx.psu.edu/repository?repository_id=a6153f28cd8d7a19)

**Publications**:

* (Liao et al., 2014) [featureCounts: an efficient general purpose program for assigning sequence reads to genomic features](https://www.ncbi.nlm.nih.gov/pubmed/24227677). Bioinformatics.  
* (Liao et al., 2013) [The Subread aligner: fast, accurate and scalable read mapping by seed-and-vote](https://www.ncbi.nlm.nih.gov/pubmed/23558742).  Nucleic Acids Res. 

**Institutions(s)**:

Division of Bioinformatics, The Walter and Eliza Hall Institute of Medical Research, Parkville, VIC, Australia

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Peak Calling</font>

### ExomePeak | Peak calling : MeRIP-seq analysis

<p align="justify">The package is developed for the analysis of affinity-based epitranscriptome shortgun sequencing data from MeRIP-seq (maA-seq).

[**Official Website**](http://compgenomics.utsa.edu/exomePeak/)

**Publications**:

* (Meng et al., 2013) [Exome-based analysis for RNA epigenome sequencing data](https://www.ncbi.nlm.nih.gov/pubmed/23589649).  Bioinformatics. 

**Institutions(s)**:

Picower Institute for Learning and Memory, Department of Brain and Cognitive Sciences, Massachusetts Institute of Technology, Stanley Center for Psychiatric Research, Broad Institute of MIT and Harvard, MA, USA

---

### MeTPeak

<p align="justify">A graphical model-based peak calling method for transcriptome-wide detection of m6A sites from MeRIP-seq data. MeTPeak models read count of m6A site and introduces a hierarchical layer of Beta variables to capture the variances and a Hidden Markov model (HMM) to characterize the reads dependency across a site. MetPeak prediction on real MeRIPseq datasets have suggested that it precisely recapitulates the motif and distribution of m6A sites, as well as correctly predicting the methylation differences among these methyltransferases.

[**Official Website**](https://github.com/compgenomics/MeTPeak)

**Publications**:

* (Cui et al., 2016) [A novel algorithm for calling mRNA m6A peaks by modeling biological variances in MeRIP-seq data](https://www.ncbi.nlm.nih.gov/pubmed/27307641).  Bioinformatics.

**Institutions(s)**:

Department of Electrical and Computer Engineering, University of Texas at San Antonio, TX, USA; Department of Biological Science, XI'an Jiaotong-Liverpool University, Suzhou, China

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">De novo motif discovery</font>

### Weeder

<p align="justify">Falls into the motif enumeration family of motif discovery tools in which the occurrence of motifs in the query sequences are counted and, in this case, compared to a pre-calculated set of genome specific background motifs. This has the benefit of not having to construct a background set of sequences (no easy task). Weeder was initially used to identify common motifs in defined promoter regions, but evolved to consider first ChIP-chip and then ChIP-seq data.

[**Official Website**](http://159.149.160.51/modtools/)

[**Galaxy**](https://toolshed.g2.bx.psu.edu/repository?repository_id=45d66a9eacc4ddaf)

**Publications**:

* (Pavesi and Pesole, 2006) [Using Weeder for the discovery of conserved transcription factor binding sites](https://www.ncbi.nlm.nih.gov/pubmed/18428764).  Curr Protoc Bioinformatics. 
* (Zambelli et al., 2014) [Using Weeder, Pscan, and PscanChIP for the Discovery of Enriched Transcription Factor Binding Site Motifs in Nucleotide Sequences](https://www.ncbi.nlm.nih.gov/pubmed/25199791). Curr Protoc Bioinformatics. 

**Institutions(s)**:

University of Milan, Italy

---

### HOMER | Hypergeometric Optimization of Motif EnRichment

<p align="justify">Performs peak finding and downstream data analysis for next-generation sequencing analysis. HOMER affords several tools and methods to make use of ChIP-Seq, GRO-Seq, RNA-Seq, DNase-Seq, Hi-C and other types of functional genomics sequencing data sets. This software offers support to UCSC visualization, peaks annotation, quantification of transcripts and repeats or differential features, enrichment and expression.

[**Official Website**](http://homer.ucsd.edu/homer/ngs/index.html)

[**Galaxy**](https://toolshed.g2.bx.psu.edu/repository?repository_id=aaa8f7315ce6dac2)

**Publications**:

* (Heinz et al., 2010) [Simple combinations of lineage-determining transcription factors prime cis-regulatory elements required for macrophage and B cell identities](https://www.ncbi.nlm.nih.gov/pubmed/20513432). Mol Cell. 

**Institutions(s)**:

Department of Cellular and Molecular Medicine, University of California, San Diego, La Jolla, CA, USA; Department of Medicine, University of California, San Diego, La Jolla, CA, USA

---

### MEME Suite

<p align="justify">Provides a unified portal for online discovery and analysis of sequence motifs representing features such as DNA binding sites and protein interaction domains. The popular MEME motif discovery algorithm is now complemented by the GLAM2 algorithm which allows discovery of motifs containing gaps. Three sequence scanning algorithms--MAST, FIMO and GLAM2SCAN--allow scanning numerous DNA and protein sequence databases for motifs discovered by MEME and GLAM2. Transcription factor motifs (including those discovered using MEME) can be compared with motifs in many popular motif databases using the motif database scanning algorithm TOMTOM. Transcription factor motifs can be further analyzed for putative function by association with Gene Ontology (GO) terms using the motif-GO term association tool GOMO. MEME output now contains sequence LOGOS for each discovered motif, as well as buttons to allow motifs to be conveniently submitted to the sequence and motif database scanning algorithms (MAST, FIMO and TOMTOM), or to GOMO, for further analysis. GLAM2 output similarly contains buttons for further analysis using GLAM2SCAN and for rerunning GLAM2 with different parameters.

[**Official Website**](http://meme-suite.org/)

**Publications**:

* (Bailey et al., 2009) [MEME SUITE: tools for motif discovery and searching](https://www.ncbi.nlm.nih.gov/pubmed/19458158).  Nucleic Acids Res. 

**Institutions(s)**:

Institute for Molecular Bioscience, University of Queensland, Brisbane, Queensland, Australia

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Degradome-seq Analysis

### sPARTA package 

<p align="justify">A powerful tool for plant miRNA target prediction and PARE validation. It can search for targets in unannotated genomic regions, which is useful to discover novel regulatory modules, independent of genome annotations that may be incomplete.

[**Official Website**](http://mpss.danforthcenter.org/tools/mirna_apps/download.php)

**Publications**:

* (Kakrana et al., 2014) [sPARTA: a parallelized pipeline for integrated analysis of plant miRNA and cleaved mRNA data sets, including new miRNA target-identification software](https://www.ncbi.nlm.nih.gov/pubmed/25120269). Nucleic Acids Res.  

**Institutions(s)**:

Center for Bioinformatics and Computational Biology, University of Delaware, Newark, DE, USA; Delaware Biotechnology Institute, University of Delaware, Newark, DE, USA; Department of Plant and Soil Sciences, University of Delaware, Newark, DE, USA

---

### CleaveLand 

<p align="justify">A generalizable computational pipeline for the detection of cleaved miRNA targets from degradome data.

[**Official Website**](https://github.com/MikeAxtell/CleaveLand4)

**Publications**:

* (Addo-Quaye et al., 2009) [CleaveLand: a pipeline for using degradome data to find cleaved small RNA targets](https://www.ncbi.nlm.nih.gov/pubmed/19017659).  Bioinformatics.   

**Institutions(s)**:

Department of Computer Science and Engineering and Department of Biology, Pennsylvania State University, University Park, PA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMICTOOLS**](https://omictools.com/transcriptomics-category)

[*Image Citation*](http://modomics.genesilico.pl/))

---