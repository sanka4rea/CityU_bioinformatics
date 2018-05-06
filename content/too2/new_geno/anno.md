+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Genome Annotation"

weight = 10
# Project summary to display on homepage.
summary = "Including: Gene Ontology Annotation, GO Semantic Similarity Analysis, Promoter Predication, Annotation Workflows."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/geno/anno.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["genomics"]

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

<img src="/img/tools/geno/anno.jpg" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Genome Annotation

<p align="justify">**Genome annotation** is a key process for identifying the coding and non-coding regions of a genome, gene locations and functions. Analysis of DNA sequence with genome annotation software tools allow finding and mapping genes, exons-introns, regulatory elements, repeats and mutations. Genome databases are essential to retrieve information on gene name, protein product and DNA sequence functions.

## <font color=#CD5555 face="黑体">Gene Ontology Annotation</font>

### BLASTX

<p align="justify">[**The Basic Local Alignment Search Tool** (BLAST)](https://blast.ncbi.nlm.nih.gov/Blast.cgi) finds regions of	local similarity between sequences. The program compares nucleotide or protein sequences to sequence databases and calculates the statistical significance of matches. BLAST can be used to infer functional and evolutionary relationships between sequences as well as help identify members of gene families.A BLAST search enables a researcher to compare a query sequence with a library or database of sequences, and identify library sequences that resemble the query sequence above a certain threshold.

<p align="justify">Different types of BLASTs are available according to the query sequences. For example, following the discovery of a previously unknown gene in the mouse, a scientist will typically perform a BLAST search of the human genome to see if humans carry a similar gene; BLAST will identify sequences in the human genome that resemble the mouse gene based on similarity of sequence. The BLAST algorithm and program were designed by `Stephen Altschul`, `Warren Gish`, `Webb Miller`, `Eugene Myers`, and `David J. Lipman` at the [National Institutes of Health](https://en.wikipedia.org/wiki/National_Institutes_of_Health) and was published in the [Journal of Molecular Biology](https://en.wikipedia.org/wiki/Journal_of_Molecular_Biology) in 1990 and cited over 50,000 times.

<img src="/img/tools/Blast.png" width= 800 height= 500 alt="blast" align="center">
**Input**: Input sequences (in [FASTA](https://en.wikipedia.org/wiki/FASTA_format) or Genbank format) and weight matrix. 

**Output**: BLAST output can be delivered in a variety of formats. These formats include HTML, plain text, and XML formatting.

<p align="justify">The details about **process** and **algorithm** coule be found [here](https://en.wikipedia.org/wiki/BLAST) and [official website](https://blast.ncbi.nlm.nih.gov/Blast.cgi)

**NCBI BLAST**:

<p align="justify">BLAST stands for Basic Local Alignment Search Tool.The emphasis of this tool is to find regions of sequence similarity, which will yield functional and evolutionary clues about the structure and function of your sequence.

This tool can be used in the following contexts:Protein, Nucleotide, Vectors. 

**PSI-BLAST**:

<p align="justify">Position specific iterative BLAST (PSI-BLAST) refers to a feature of BLAST 2.0 in which a profile is automatically constructed from the first set of BLAST alignments. PSI-BLAST is similar to NCBI BLAST2 except that it uses position-specific scoring matrices derived during the search, this tool is used to detect distant evolutionary relationships. PHI-BLAST functionality is available to use patterns to restrict search results. 

[How to use](https://www.ebi.ac.uk/seqdb/confluence/display/THD/PSI-BLAST)

**Publications**

* (Altschul et al., 1997) [Gapped BLAST and PSI-BLAST: a new generation of protein database search programs](https://www.ncbi.nlm.nih.gov/pubmed/9254694).  Nucleic Acids Res. PMID: 9254694
* (Altschul et al., 1990) [Basic local alignment search tool](https://www.ncbi.nlm.nih.gov/pubmed/2231712).  J Mol Biol. PMID: 2231712

**Institution(s)**

National Center for Biotechnology Information, National Library of Medicine, National Institutes of Health, Bethesda, MD, USA

*citation:* [Sequence Similarity Searching](https://www.ebi.ac.uk/Tools/sss/)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

### Blast2GO

<p align="justify">Permits functional annotation, management, and data mining of novel sequence data. **Blast2GO** is based on the utilization of common controlled vocabulary schemas, the gene ontology (GO). It takes in consideration similarity, the extension of the homology, the database of choice, the GO hierarchy, and the quality of the original annotations. This tool is suitable for plant genomics research. It generates functional annotation and assesses the functional meaning of their experimental results.

<img src="/img/tools/geno/blast2go.png" width= 800 height= 500 alt="blast" align="center">

[**Official Website**](https://www.blast2go.com/)

[**Documentation**](https://www.blast2go.com/images/b2g_pdfs/b2g_user_manual.pdf)

**Publications**:

* (Conesa et al., 2005) Blast2GO: a universal tool for annotation, visualization and analysis in functional genomics research.<br> PMID: 16081474 DOI: 10.1093/bioinformatics/bti610
* (Conesa and Götz, 2008) Blast2GO: A comprehensive suite for functional analysis in plant genomics.  Int J Plant Genomics. <br>PMID: 18483572 DOI: 10.1155/2008/619832
* (Götz et al., 2008) High-throughput functional annotation and data mining with the Blast2GO suite.  Nucleic Acids Res. <br>PMID: 18445632 DOI: 10.1093/nar/gkn176
* (Aparicio et al., 2006) Blast2GO goes grid: developing a grid-enabled prototype for functional genomics analysis.  Stud Health Technol Inform. <br>PMID: 16823138

**Institutions(s)**: Bioinformatics Department, Centro de Investigación Príncipe Felipe, Valencia, Spain

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## <font color=#CD5555 face="黑体">GO Semantic Similarity Analysis</font>

### G-SESAME | Gene Semantic Similarity Analysis and Measurement Tools

<p align="justify">A set of online tools for measuring the **semantic similarities** of Gene Ontology (GO) terms and the functional similarities of gene products, and for further discovering biomedical knowledge from the GO database. Visualization techniques are provided in these tools to allow users to inspect the locations of the GO terms within the GO graph and to visually determine the semantic similarity. A batch command interface is also provided for users to execute the tools to measure the semantic similarity of a group of GO terms or functional similarities of a group of genes. Web based APIs are also provided for advanced users.

[**Official Website**](http://bioinformatics.clemson.edu/G-SESAME/)


**Publications**:

* (Song, 2014) [Measure the Semantic Similarity of GO Terms Using Aggregate Information Content](https://www.ncbi.nlm.nih.gov/pubmed/26356015).  IEEE Trans Comput Biol Bioinform.<br>PMID: 26356015 DOI: 10.1109/TCBB.2013.176
* (Du et al., 2009) [G-SESAME: web tools for GO-term-based gene similarity analysis and knowledge discovery](https://www.ncbi.nlm.nih.gov/pubmed/19491312).  Nucleic Acids Res. <br>PMID: 19491312 DOI: 10.1093/nar/gkp463
* (Wang et al., 2007) [A new method to measure the semantic similarity of GO terms](https://www.ncbi.nlm.nih.gov/pubmed/17344234). Bioinformatics. <br>PMID: 17344234

**Institutions(s)**: School of Computing, Clemson University, Clemson, SC, USA

### clusterProfiler | GO semantic similarity analysis : Genome annotation

<p align="justify">Automates the process of biological-term classification and the enrichment analysis of gene clusters. ClusterProfiler supports three species, including humans, mice, and yeast. It offers a gene classification method, namely groupGO, to sort genes based on their projection at a specific level of the gene ontology (GO) corpus. This tool is able to calculate enrichment test for GO terms and KEGG pathways based on hypergeometric distribution.

[**Official Website**](http://bioconductor.org/packages/release/bioc/html/clusterProfiler.html)

[**Github**](https://github.com/GuangchuangYu/clusterProfiler)

[**Documentation**](http://bioconductor.org/packages/release/bioc/manuals/clusterProfiler/man/clusterProfiler.pdf)

**Publications**:

* (Yu et al., 2012) [clusterProfiler: an R package for comparing biological themes among gene clusters](https://www.ncbi.nlm.nih.gov/pubmed/22455463).  OMICS. 
* (Yu, 2018) [clusterProfiler: An universal enrichment tool for functional and comparative study](https://www.biorxiv.org/content/early/2018/02/01/256784).  BioRxiv. 

**Institutions(s)**: State Key Laboratory of Emerging Infectious Diseases and Centre of Influenza Research, School of Public Health, The University of Hong Kong, Hong Kong, China

### GOToolBox | GO semantic similarity analysis : DNA sequence analysis

<p align="justify">Provides a series of programs allowing the functional investigation of groups of genes, based on the Gene Ontology resource. GOToolBox allows 1) the identification of statistically relevant over- or under-represented terms in a gene dataset, 2) the clustering of functionally related genes within a set and 3) the retrieval of genes sharing annotations with a query gene. The user can also constrain the GO annotations to a slim hierarchy or to a given level of the ontology, in order to facilitate the interpretation of the results.

[**Official Website**](http://genome.crg.es/GOToolBox/)

**Publications**:

* (Martin et al., 2004) [GOToolBox: functional analysis of gene datasets based on Gene Ontology](https://www.ncbi.nlm.nih.gov/pubmed/15575967).  Genome Biol. 

**Institutions(s)**: Laboratoire de Génétique et Physiologie du Développement, IBDM, CNRS/INSERM/Université de la Méditerranée, Parc Scientifique de Luminy, Marseille, France

### SML-Toolkit | Semantic Measures Library Toolkit

<p align="justify">A Java Toolkit dedicated to semantic measures computation and analysis. SML-Toolkit is composed of various tools related to semantic measures computation and analysis. Those tools are provided through a common command-line interface.

[**Official Website**](http://www.semantic-measures-library.org/sml/index.php?q=toolkit)

[**Github**](https://github.com/sharispe/slib/)

**Publications**:

* (Harispe et al., 2014) [A framework for unifying ontology-based semantic similarity measures: a study in the biomedical domain](https://www.ncbi.nlm.nih.gov/pubmed/24269894).  J Biomed Inform. 
* (Harispe et al., 2014) [The semantic measures library and toolkit: fast computation of semantic similarity and relatedness using biomedical ontologies](https://www.ncbi.nlm.nih.gov/pubmed/24108186). Bioinformatics. 

**Institutions(s)**: LGI2P/EMA Research Centre, Site EERIE, Parc Scientifique G Besse, Nîmes, France

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## <font color=#CD5555 face="黑体">Promoter Predication</font>

### FirstEF | First Exon Finder

<p align="justify">A **5' terminal exon and promoter** prediction program. FirstEF consists of different discriminant functions structured as a decision tree. The probabilistic models are optimized to find potential first donor sites and CpG-related and non-CpG-related promoter regions based on discriminant analysis. For every potential first donor site (GT) and an upstream promoter region, FirstEF decides whether or not the intermediate region can be a potential first exon, based on a set of quadratic discriminant functions.

[**Official Website**](http://rulai.cshl.org/tools/FirstEF/)

[**Documentation**](http://rulai.cshl.org/tools/FirstEF/Readme/README.html)

**Publications**:

* (Davuluri et al., 2001) [Computational identification of promoters and first exons in the human genome](https://www.ncbi.nlm.nih.gov/pubmed/11726928).  Nat Genet. 


**Institutions(s)**: Cold Spring Harbor Laboratory, Cold Spring Harbor, New York, NY, USA

### CpGpromoter

<p align="justify">A program for a large-scale human promoter mapping using CpG islands. CpGpromoter is based on results of discriminant analysis between the promoter-associated CpG islands and non-associated ones. It enables an efficient mapping of human promoters with 2Kb resolution, if there is a CpG island inside an interval (-500...+1,500) around a transcription start site.

[**Official Website**](http://rulai.cshl.org/tools/CpG_promoter/)

**Publications**:

* (Ioshikhes and Zhang, 2000) [Large-scale human promoter mapping using CpG islands](https://www.ncbi.nlm.nih.gov/pubmed/10973249).  Nat Genet.  


**Institutions(s)**: Cold Spring Harbor Laboratory, Cold Spring Harbor, NY, USA

### PROmiRNA

<p align="justify">A program for annotating **miRNA promoters in human**, as well as other species. PROmiRNA uses deepCAGE data from the FANTOM4 Consortium and integrated cage tag counts and other promoter features, such as CpG content, conservation and TATA box affinity, to score the potential of a candidate region to be a promoter. Given a list of genomic regions of interest, in the form of a gff file, PROmiRNA returns the most probable promoter locations, together with the posterior probabilities calculated by the model.

[**Official Website**](http://promirna.molgen.mpg.de/)

**Publications**:

* (Marsico et al., 2013) [PROmiRNA: a new miRNA promoter recognition method uncovers the complex regulation of intronic miRNAs](https://www.ncbi.nlm.nih.gov/pubmed/23958307). Genome Biol. 


**Institutions(s)**: Max Planck Institute for Molecular Genetics, Berlin, Germany; Partner Institute for Computational Biology, Shanghai Institutes for Biological Sciences, Chinese Academy of Sciences, Shanghai, China

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## <font color=#CD5555 face="黑体">Annotation Workflows</font>

### RAST | Rapid Annotation using Subsystem Technology

<p align="justify">Assists in annotating complete or nearly complete bacterial and archaeal genomes. RAST is a fully-automated application provides high quality genome annotations for these genomes across the whole phylogenetic tree. It includes a user interface that allows registered users to make manual changes to their genomes before retrieving them. It was designed to extend annotations to as many protein-encoding genes in as many genomes as possible.

[**Official Website**](http://rast.nmpdr.org/)

**Publications**:

* (Overbeek et al., 2014) [The SEED and the Rapid Annotation of microbial genomes using Subsystems Technology (RAST)](https://www.ncbi.nlm.nih.gov/pubmed/24293654).  Nucleic Acids Res. 
* (Aziz et al., 2008) [The RAST Server: rapid annotations using subsystems technology](https://www.ncbi.nlm.nih.gov/pubmed/18261238).  BMC Genomics. 

### Prokka | Annotation workflows

<p align="justify">A command line software tool to fully annotate a draft bacterial genome in about 10 min on a typical desktop computer. It produces standards-compliant output files for further analysis or viewing in genome browsers. Prokka uses parallel processing to decrease running time on multicore computers. The most time-consuming steps are BLAST+ and hmmscan, which both support multiple CPUs natively. However, Prokka is more efficient if it runs multiple single CPU threads on subsets of the data, which it achieves using GNU parallel.

[**Official Website**](http://www.vicbioinformatics.com/software.prokka.shtml)

**Publications**:

* (Seemann, 2014) [Prokka: rapid prokaryotic genome annotation](https://www.ncbi.nlm.nih.gov/pubmed/24642063).  Bioinformatics.  


**Institutions(s)**: Victorian Bioinformatics Consortium, Monash University, Clayton; Life Sciences Computation Centre, Victorian Life Sciences Computation Initiative, Carlton, Australia

### BlastKOALA

<p align="justify">Assigns K numbers to the user's sequence data by BLAST searches, respectively, against a nonredundant set of KEGG GENES. KOALA (KEGG Orthology And Links Annotation) is KEGG's internal annotation tool for K number assignment of KEGG GENES using SSEARCH computation. Annotate Sequence in KEGG Mapper and Pathogen Checker in KEGG Pathogen are special interfaces to this server and can be executed in an interactive mode. BlastKOALA is suitable for annotating fully sequenced genomes.

[**Official Website**](http://www.kegg.jp/blastkoala/)

**Publications**:

* (Kanehisa et al., 2016) [BlastKOALA and GhostKOALA: KEGG Tools for Functional Characterization of Genome and Metagenome Sequences](https://www.ncbi.nlm.nih.gov/pubmed/26585406).  J Mol Biol.  


**Institutions(s)**: Institute for Chemical Research, Kyoto University, Uji, Kyoto, Japan; Healthcare Solutions Department, Fujitsu Kyushu Systems Ltd, Hakata-ku, Fukuoka, Japan; Institute for Chemical Research, Kyoto University, Uji, Kyoto, Japan

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## Find more tools: [**OMIVTOOLS**](https://omictools.com/genomics2-category)

---