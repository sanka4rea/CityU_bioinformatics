+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Genome Editing"

weight = 30
# Project summary to display on homepage.
 summary = "Including: Genome Edition, Genome Editing Databases, CRISPR/Cas9 Screen Analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/geno/edit.png"

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

<img src="/img/tools/geno/edit.png" width="500", height="300" alt="dnastr" align="center">

<span id="top"></span>

{{% toc %}}

---

# Genome Editing 

<p align="justify">Programmable nucleases - including zinc-finger nucleases (ZFNs), transcription activator-like effector nucleases (TALENs) and RNA-guided engineered nucleases (RGENs) derived from the bacterial clustered regularly interspaced short palindromic repeat (CRISPR)-Cas (CRISPR-associated) system - enable targeted genetic modifications in cultured cells, as well as in whole animals and plants. The value of these enzymes in research, medicine and biotechnology arises from their ability to induce site-specific DNA cleavage in the genome, the repair (through endogenous mechanisms) of which allows high-precision genome editing.

[Related websites](https://en.wikipedia.org/wiki/Genome_editing)

---

## <font color=#CD5555 face="黑体">CRISPR/Cas9 sgRNA Design</font>

### CRISPR design

<p align="justify">A web tool crafted to simplify the process of **CRISPR guide selection** in an input DNA sequence by (i) discovering possible offtargets genome-wide, (ii) highlighting guides with high target specificity, and (iii) flagging guides with numerous or genic offtargets in target genomes. The CRISPR design tool allows users to enter a 23-1000bp DNA sequence of interest and will find all SpCas9 target sites within the input sequence. The result will contain a rank ordered list of target sites based on predicted specificity.

[**Official Website**](http://crispr.mit.edu/)

**Publications**

* (Hsu et al., 2013) [DNA targeting specificity of RNA-guided Cas9 nucleases](https://www.ncbi.nlm.nih.gov/pubmed/23873081).  Nat Biotechnol. 

**Institution(s)**: Broad Institute of MIT and Harvard, Cambridge, MA, USA; McGovern Institute for Brain Research, Department of Brain and Cognitive Sciences, Department of Biological Engineering, Massachusetts Institute of Technology, Cambridge, MA, USA

---

### GuideScan

<p align="justify">Allows for the design of **CRISPR** guide RNA libraries that can be used to edit coding and noncoding genomic regions. GuideScan produces high-density sets of guide RNAs (gRNAs) for single- and paired-gRNA genome-wide screens. Rather than using an alignment tool, GuideScan uses a retrieval tree (trie) data structure, which efficiently and precisely enumerates all targetable sequences present in a given genome. Traversals of the trie allow for the computation of sequence mismatch neighborhoods, which are used to construct databases of gRNAs whose target sites are unique in the genome up to a user-defined number of mismatches. The GuideScan website allows users to input coordinates of genomic features in batch, to choose between designing single internal gRNAs or pairs of flanking gRNAs, and retrieve for each genomic coordinate a pre-defined number of gRNAs or gRNA pairs.

[**Official Website**](http://www.guidescan.com/)

[**Documentation**](http://www.guidescan.com/help)

**Publications**

* (Perez, 2017) [GuideScan software for improved single and paired CRISPR guide RNA design](https://www.ncbi.nlm.nih.gov/pubmed/28263296).  Nat Biotechnol.  

**Institution(s)**

Computational Biology Program, Memorial Sloan Kettering Cancer Center, New York, NY, USA; Cancer Biology and Genetics Program, Memorial Sloan Kettering Cancer Center, New York, NY, USA

---

### E-CRISP

<p align="justify">A software tool to design and evaluate target sites for use with the **Clustered Regularly Interspaced Short Palindromic Repeat** (CRISPR) system.

[**Official Website**](http://www.e-crisp.org/E-CRISP/)

**Publications**

* (Heigwer et al., 2014)[ E-CRISP: fast CRISPR target site identification](https://www.ncbi.nlm.nih.gov/pubmed/24481216).  Nat Methods. 

**Institution(s)**

Division of Signaling and Functional Genomics, German Cancer Research Center (DKFZ), Heidelberg, Germany; Department of Cell and Molecular Biology, Medical Faculty Mannheim, Heidelberg University, Heidelberg, Germany

---

### CRISPRscan

<p align="justify">A predictive **single guide RNAs** (sgRNA)-scoring algorithm that effectively captures the sequence features affecting the activity of CRISPR-Cas9 in vivo. Based on a large scale analysis of sgRNA mutagenesis activity in zebrafish, we established rules to predict sgRNA activity in vivo and build the CRISPRscan model integrating these rules. We independently validated with success our predictions using sgRNAs different from the large scale analysis.

[**Official Website**](http://www.crisprscan.org/)

**Publications**

* (Moreno-Mateos et al., 2015) [CRISPRscan: designing highly efficient sgRNAs for CRISPR-Cas9 targeting in vivo](https://www.ncbi.nlm.nih.gov/pubmed/26322839).  Nat Methods. 

**Institution(s)**

Department of Genetics, Yale University School of Medicine, New Haven, CT, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">TALEN design</font>

### TALE-NT

<p align="justify">Enables design of custom **TAL effector repeat arrays** for desired targets and prediction of TAL effector binding sites, ranked by likelihood, in a genome, promoterome or other sequence of interest.

[**Official Website**](https://tale-nt.cac.cornell.edu/)

**Publications**:

* (Doyle et al., 2012) [TAL Effector-Nucleotide Targeter (TALE-NT) 2.0: tools for TAL effector design and target prediction](https://www.ncbi.nlm.nih.gov/pubmed/22693217).  Nucleic Acids Res. 

**Institutions(s)**

Department of Plant Pathology and Microbiology, Iowa State University, Ames, IA, USA

---

### TALEN Targeter

<p align="justify">Aids researchers in adopting **TAL effector nucleases** (TALENs) as gene editing tools. TALEN Targeter is a web application that identifies paired monomer (typically heteromeric) binding sites oriented 50 –30 on opposite strands of the DNA and separated by a spacer. It also allows users to specify a range for the spacer length, and all possible combinations of repeat numbers and spacer lengths are considered.

[**Official Website**](https://tale-nt.cac.cornell.edu/node/add/talen)

**Publications**:

* (Doyle et al., 2012) [TAL Effector-Nucleotide Targeter (TALE-NT) 2.0: tools for TAL effector design and target prediction](https://www.ncbi.nlm.nih.gov/pubmed/22693217).  Nucleic Acids Res. 

**Institutions(s)**

Department of Plant Pathology and Microbiology, Iowa State University, Ames, IA, USA; Department of Entomology, Iowa State University, Ames, IA, USA; Department of Genetics, Development and Cell Biology, Iowa State University, Ames, IA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">ZFN Design</font>

### Zinc Finger Tools

<p align="justify">This site provides several tools for selecting zinc finger protein (ZFP) target sites and for designing the proteins that will target them.

[**Official Website**](http://www.scripps.edu/barbas/zfdesign/zfdesignhome.php)

**Publications**:

* (Mandell and Barbas CF 3rd, 2006) [Zinc Finger Tools: custom DNA-binding domains for transcription factors and nucleases](https://www.ncbi.nlm.nih.gov/pubmed/16845061).  Nucleic Acids Res.  

**Institutions(s)**

Department of Molecular Biology and The Skaggs Institute for Chemical Biology, The Scripps Research Institute, La Jolla, CA, USA

---

### ZifNN 

<p align="justify">Predicts high throughput of optimal **zinc finger protein** for 9 bp DNA sequences of choice. ZifNN is inspired from an ensemble machine learning approach, and incorporates the predictions made by 100 parallel neural networks. It assumes synergistic mode of binding, thus capturing the molecular interactions between the DNA sequence and the zinc finger protein (ZFP) helices in greater detail. The tool is capable of domain adaptation, which allows it to make predictions about data points from a domain other than the one used for training the model.

[**Official Website**](http://web.iitd.ac.in/~sundar/ZifNN/)

[**Documentation**](http://web.iitd.ac.in/~sundar/ZifNN/Home.html#services)

**Publications**:

* (Dutta, 2016) [An ensemble micro neural network approach for elucidating interactions between zinc finger proteins and their target DNA](https://www.ncbi.nlm.nih.gov/pubmed/28155662).  BMC Genomics. 

**Institutions(s)**

Department of Biochemical Engineering and Biotechnology

---

### ZFN-Site

<p align="justify">ZFN-Site

A web interface that searches multiple genomes for ZFN off-target sites.

[**Official Website**](https://ccg.vital-it.ch/tagger/targetsearch.html)

**Publications**:

* (Cradick et al., 2011) [ZFN-site searches genomes for zinc finger nuclease target sites and off-target sites](https://www.ncbi.nlm.nih.gov/pubmed/21569489).  BMC Bioinformatics.  

**Institutions(s)**

University of Iowa School of Medicine, Department of Internal Medicine, Iowa City, IA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">CRISPR/Cas9 Screen Analysis</font>

### CREATE | CRISPR-enabled trackable genome engineering

<p align="justify">Links each guide RNA to homologous repair cassettes that both edit loci and function as barcodes to track genotype-phenotype relationships. **CREATE** combines automated design of CREATE cassettes (modular guide RNA-editing oligos), arraybased CREATE cassette synthesis, and sequencing in a streamlined workflow for genome engineering. CREATE was applied to site saturation mutagenesis for protein engineering, reconstruction of adaptive laboratory evolution experiments, and identification of stress tolerance and antibiotic resistance genes in bacteria.

[**Official Website**](http://www.thebioverse.org/)

**Publications**:

* (Garst et al., 2017) [Genome-wide mapping of mutations at single-nucleotide resolution for protein, metabolic and genome engineering](https://www.ncbi.nlm.nih.gov/pubmed/27941803).  Nat Biotechnol.   

**Institution(s)**

Department of Chemical and Biological Engineering, University of Colorado Boulder, Boulder, CO, USA; Muse Biotechnology Inc., Boulder, CO, USA

---

### MAGeCK | Model-based Analysis of Genome-wide CRISPR/Cas9 Knockout

<p align="justify">Identifies positively and negatively selected sgRNAs and genes in genome-scale CRISPR/Cas9 knockout experiments. **MAGeCK** consists of four steps: read count normalization, mean-variance modeling, sgRNA ranking and gene ranking. The software results are robust across different sequencing depths and numbers of sgRNAs per gene. It is also able to perform both positive and negative selection screens simultaneously, and identify biologically meaningful and cell type-specific essential genes and pathways.

[**Official Website**](https://sourceforge.net/projects/mageck/)

**Publications**:

* (Li et al., 2014) [MAGeCK enables robust identification of essential genes from genome-scale CRISPR/Cas9 knockout screens](https://www.ncbi.nlm.nih.gov/pubmed/25476604). Genome Biol. 
* (Li et al., 2015) [Quality control, modeling, and visualization of CRISPR screens with MAGeCK-VISPR](https://www.ncbi.nlm.nih.gov/pubmed/26673418).  Genome Biol. 
* (Wu et al., 2018) [Reducing False Positives in CRISPR/Cas9 Screens from Copy Number Variations](https://www.biorxiv.org/content/early/2018/01/11/247031).  BioRxiv.  


**Institutions(s)**: 

Department of Biostatistics and Computational Biology, Dana-Farber Cancer Institute and Harvard School of Public Health, Boston, MA, USA;

---

### MAGeCK-VISPR 

<p align="justify">Allows users to estimate the effects of **gene knockouts** (KO) in clustered regularly interspaced short palindromic repeats (CRISPR) screens. MAGeCK-VISPR consists of an algorithm named “MAGeCK-MLE” that contains the following functions: (1) define a set of quality control (QC) measurements; (2) extend the MAGeCK algorithm to call essential genes under multiple conditions while considering single guide RNA (sgRNA) knockout efficiency; and (3) provide a web-based visualization framework (VISPR) for interactive exploration of CRISPR screen QC and analysis results.

[**Official Website**](https://bitbucket.org/liulab/mageck-vispr)

[**Documentation**](https://bitbucket.org/liulab/vispr/issues?status=new&status=open)

**Publications**:

* (Li et al., 2015) [Quality control, modeling, and visualization of CRISPR screens with MAGeCK-VISPR](https://www.ncbi.nlm.nih.gov/pubmed/26673418).  Genome Biol. 
* (Wu et al., 2018) [Reducing False Positives in CRISPR/Cas9 Screens from Copy Number Variations](https://www.biorxiv.org/content/early/2018/01/11/247031).  BioRxiv. 

**Institutions(s)**: 

Department of Biostatistics and Computational Biology, Dana-Farber Cancer Institute, Harvard T.H. Chan School of Public Health, Boston, MA, USA

---

### caRpools | CRISPR-AnalyzeR for pooled screens

<p align="justify">An R package for exploratory data analysis that provides a complete workflow to analyze **CRISPR/Cas9 screens**. To further support the analysis of large-scale screens, caRpools integrates screening documentation and generation of standardized analysis reports. It is designed to be user-friendly for novice and expert users: caRpools’ open virtual appliance allows analysis without prior programming knowledge.

[**Official Website**](https://github.com/boutroslab/caRpools)

[**Documentation**](https://github.com/boutroslab/caRpools/wiki)

**Publications**:

* (Winter et al., 2016) [caRpools: an R package for exploratory data analysis and documentation of pooled CRISPR/Cas9 screens](https://www.ncbi.nlm.nih.gov/pubmed/26508755). Bioinformatics. 

**Institutions(s)**: 

German Cancer Research Center (DKFZ), Division Signaling and Functional Genomics and Heidelberg University, Heidelberg, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Genome Editing Database</font>

<p align="justify">Genome edition uses the properties of bacterial clustered regularly interspaced short palindromic repeat (CRISPR) to elicit targeted genetic modifications in cultured cells, as well as in whole animals and plants. Genome editing databases gather CRISPR/cas9 screening experiments, target sequences, and more, to help design gene editing experiments.

Find Meganuclease/CRISPR/Cas9/TALEN/ZEN database in [HERE](https://omictools.com/genome-editing-databases-category)


[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMICTOOLS**](https://omictools.com/genomics2-category)

[*Image Citation*](https://naturwissenschaften.ch/service/news/95331-genome-editing-science-policy-and-security-experts-call-for-proactive-international-dialogue-about-security---and-benefits)

---