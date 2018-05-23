+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Population Genomics"

weight = 40
# Project summary to display on homepage.
 summary = "Including: Population genetic analysis, GBS analysis, RAD-seq analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/geno/popu.jpg"

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

<img src="/img/tools/geno/popu.jpg" width="500", height="300" alt="dnastr" align="center">

{{% toc %}}

<span id="top"></span>

<p align="justify">Population genomics is the large-scale comparison of DNA sequences of populations. Population genomics is a neologism that is associated with population genetics. Population genomics studies genome-wide effects to improve our understanding of microevolution so that we may learn the phylogenetic history and demography of a population.

# Popilation Genetic Analysis

<p align="justify">Genetic diversity is the amount of variation observed between DNA sequences from distinct individuals of a given species. This pivotal concept of population genetics has implications for species health, domestication, management and conservation. Levels of genetic diversity seem to vary greatly in natural populations and species, but the determinants of this variation, and particularly the relative influences of species biology and ecology versus population history, are still largely mysterious.

## <font color=#CD5555 face="黑体">Pedigree Reconstruction</font>

### Prest-plus   

<p align="justify">Detects pedigree errors, cryptic relatedness and relationship mispecification in genome-wide association study (GWAS) or linkage data. Using an optimized maximum likelihood estimation (MLE) estimator for identity by descent (IBD) probabilities, prest-plus computes accurate estimates for IBD0/1/2 using any number and combination of single nucleotide polymorphism (SNP) or microsatellite marker data. It can work as efficiently and accurately with a microsatellite linkage panel or SNP data from a GWAS study.

[**Official Website**](http://www.utstat.toronto.edu/sun/Software/Prest/index.html) 

[**Documentation**](http://www.utstat.toronto.edu/sun/Software/Prest/media/PREST-plus%20v4.09.pdf) 

**Publications**

* (Sun and Dimitromanolakis,2014)[PREST-plus identifies pedigree errors and cryptic relatedness in the GAW18 sample using genome-wide SNP data]( https://www.ncbi.nlm.nih.gov/pubmed/25519375). BMC Proc.
* (Sun et al.,2002) [Enhanced pedigree error detection]( https://www.ncbi.nlm.nih.gov/pubmed/12566741).Hum Hered.
(McPeek and Sun, 2000) [Statistical tests for detection of misspecified relationships by use of genome-screen data]( https://www.ncbi.nlm.nih.gov/pubmed/10712219). Am J Hum Genet.

**Institution(s)**   

Division of Biostatistics, Dalla Lana School of Public Health, University of Toronto, Toronto, ON, Canada; Department of Statistical Sciences, University of Toronto, Toronto, ON, Canada; Department of Clinical Biochemistry, University Health Network, Toronto, ON, Canada

---

### FRANz   

<p align="justify">A package for pedigree reconstruction in natural populations using co-dominant genomic markers such as microsatellites and single nucleotide polymorphisms (SNPs). FRANz makes use of prior information such as known relationships (sub-pedigrees) or the age and sex of individuals. The accuracy of the algorithm is demonstrated for simulated data as well as an empirical dataset with known pedigree. The parentage inference is robust even in the presence of genotyping errors.

[**Official Website**](http://www.bioinf.uni-leipzig.de/Software/FRANz/About.html)  

[**Documentation**](https://www.bioinf.uni-leipzig.de/Software/FRANz/FRANz2.pdf) 

**Publications**

* (Riester et al., 2010) [Reconstruction of pedigrees in clonal plant populations]( https://www.ncbi.nlm.nih.gov/pubmed/20566407). Theor Popul Biol.
* (Riester et al., 2009) [FRANz: reconstruction of wild multi-generation pedigrees]( https://www.ncbi.nlm.nih.gov/pubmed/19202194).Bioinformatics.  

**Institution(s)**   

Bioinformatics Group, Department of Computer Science, and Interdisciplinary Center for Bioinformatics, University of Leipzig, Leipzig, Germany; RNomics Group, Fraunhofer Institut for Cell Therapy and Immunology (IZI), Leipzig, Germany; Institute for Theoretical Chemistry, University of Vienna, Währingerstrasse, Vienna, Austria; The Santa Fe Institute, Santa Fe, NM, USA

---

### RELPAIR 

<p align="justify">Infers the most likely relationship of a pair of putative sibs. RELPER consider all possible pairs of individuals in the sample, to test for additional relationships, to allow explicitly for genotyping error, and to include X-linked data. Using autosomal genome scan data, our method has excellent power to differentiate monozygotic twins, full sibs, parent-offspring pairs, second-degree (27) relatives, first cousins, and unrelated pairs but is unable to distinguish accurately among the 27 relationships of half sibs, avuncular pairs, and grandparent-grandchild pairs.

[**Official Website**](https:// https://csg.sph.umich.edu/boehnke/relpair.php) 

**Publications**

* (Epstein et al., 2000)[ Improved inference of relationship for pairs of individuals]( https://www.ncbi.nlm.nih.gov/pubmed/11032786).  Am J Hum Genet.
**Institution(s)**  

Department of Biostatistics, University of Michigan, Ann Arbor, MI, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Forward Simulation</font>

### SeqSIMLA   

<p align="justify">A simulation tool that can simulate sequence data with user-specified disease and quantitative trait models. SeqSIMLA can efficiently simulate sequence data with disease or quantitative trait models specified by the user. It is useful for evaluating statistical properties for new study designs and new statistical methods using NGS.

[**Official Website**](http://seqsimla.sourceforge.net/) 

**Publications**

* (Yao and Chung, 2016) [SeqSIMLA2_exact: simulate multiple disease sites in large pedigrees with given disease status for diseases with low prevalence]( https://www.ncbi.nlm.nih.gov/pubmed/26515824). Bioinformatics. 

* (Chung et al., 2015) [SeqSIMLA2: simulating correlated quantitative traits accounting for shared environmental effects in user-specified pedigree structure]( https://www.ncbi.nlm.nih.gov/pubmed/25250827). Genet Epidemiol.

* (Chung and Shih, 2013) [SeqSIMLA: a sequence and phenotype simulation tool for complex disease studies]( https://www.ncbi.nlm.nih.gov/pubmed/23782512). BMC Bioinformatics.

**Institution(s)**   

Division of Biostatistics and Bioinformatics, Institute of Population Health Sciences, National Health Research Institutes, Zhunan, Miaoli, Taiwan

---

### SeDuS  

<p align="justify">A flexible and user-friendly forward-in-time simulator of patterns of molecular evolution within segmental duplications undergoing interlocus gene conversion and crossover. SeDuS introduces known features of interlocus gene conversion such as biased directionality and dependence on local sequence identity. Additionally, it includes aspects such as different selective pressures acting upon copy number and flexible crossover distributions. A graphical user interface allows fast fine-tuning of relevant parameters and straightforward real-time analysis of the evolution of duplicates.

[**Official Website**](http://www.biologiaevolutiva.org/sedus/) 

[**Documentation**]( http://www.biologiaevolutiva.org/sedus/documentation.html) 

**Publications**

* (Hartasánchez et al., 2016) [SeDuS: segmental duplication simulator]( https://www.ncbi.nlm.nih.gov/pubmed/26358728).  Bioinformatics. 

* (Hartasánchez et al., 2014) [Interplay of interlocus gene conversion and crossover in segmental duplications under a neutral scenario]( https://www.ncbi.nlm.nih.gov/pubmed/24906640).  G3.

**Institution(s)**  

Institute of Evolutionary Biology (Universitat Pompeu Fabra – CSIC), PRBB, Barcelona, Spain

---

### SFS_CODE   

<p align="justify">Generates samples from populations with complex demographic histories under various models of natural selection. SFS_CODE performs simulations under a general Wright-Fisher model with arbitrary demographic, selective, and mutational effects. It allows the user to simulate realistic genomic regions with several loci evolving according to a variety of mutation models (from simple to context-dependent), and takes into account insertions and deletions. Each locus can be annotated as either coding or non-coding, sex-linked or autosomal, selected or neutral, and have an arbitrary linkage structure.

[**Official Website**](http://sfscode.sourceforge.net/SFS_CODE/index/index.html)  

[**Documentation**]( http://sfscode.sourceforge.net/SFS_CODE_doc.pdf) 

**Publications**

* (Hernandez, 2016) [SFS_CODE: More Efficient and Flexible Forward Simulations]( https://doi.org/10.1101/025064). BioRxiv. 
* (Hernandez, 2008) [A flexible forward simulator for populations subject to selection and demography]( https://www.ncbi.nlm.nih.gov/pubmed/18842601). Bioinformatics.

**Institution(s)**   

Department of Bioengineering and Therapeutic Sciences, Institute for Human Genetics, Institute for Quantitative Biosciences, University of California San Francisco, CA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Population Structure Inference</font>

### STRUCTURE  

<p align="justify">A free software package for using multi-locus genotype data to investigate population structure. Its uses include inferring the presence of distinct populations, assigning individuals to populations, studying hybrid zones, identifying migrants and admixed individuals, and estimating population allele frequencies in situations where many individuals are migrants or admixed. It can be applied to most of the commonly-used genetic markers, including SNPS, microsatellites, RFLPs and AFLPs. fastSTRUCTURE estimates approximate posterior distributions on ancestry proportions 2 orders of magnitude faster than STRUCTURE, with ancestry estimates and prediction accuracies that are comparable to those of ADMIXTURE.

[**Official Website**](https://rajanil.github.io/fastStructure/)  

**Publications**

* (Hubisz et al., 2009) [Inferring weak population structure with the assistance of sample group information]( https://www.ncbi.nlm.nih.gov/pubmed/21564903).  Mol Ecol Resour. 
* (Falush et al., 2007) [Inference of population structure using multilocus genotype data: dominant markers and null alleles]( https://www.ncbi.nlm.nih.gov/pubmed/18784791).Mol Ecol Notes.
* (Pritchard et al., 2000) [Inference of population structure using multilocus genotype data]( https://www.ncbi.nlm.nih.gov/pubmed/10835412) .Genetics.
* (Raj et al., 2014) [fastSTRUCTURE: variational inference of population structure in large SNP data sets]( https://www.ncbi.nlm.nih.gov/pubmed/24700103).  Genetics.
* (Evanno et al., 2005) [Detecting the number of clusters of individuals using the software STRUCTURE: a simulation study](https://www.ncbi.nlm.nih.gov/pubmed/15969739). Mol Ecol.

**Institution(s)**   

Department of Genetics, Stanford University, Stanford, CA, USA

---

### PCAngsd

<p align="justify">Aims to infer population structure and admixture proportions in low depth next generation sequencing (NGS) data. PCAngsd utilizes genotype likelihoods to iteratively estimate individual allele frequencies. This tool is able to overcome the observed bias of low and variable sequencing depth by using individual allele frequencies as prior information. Moreover, it can push the lower boundaries of sequencing depth required to perform population genetic analyses using NGS data of large-scale genetic studies.

[**Official Website**](https://github.com/Rosemeis/pcangsd) 

**Publications**

* (Meisner and Albrechtsen, ) [Inferring Population Structure and Admixture Proportions in Low Depth Next-Generation Sequencing Data]( https://doi.org/10.1101/302463).  BioRxiv.

**Institution(s)** 

Department of Biology, Section for Computational and RNA Biology, University of Copenhagen, Copenhagen, Denmark

---

### PSIKO  

<p align="justify">A software tool written in C++ for quick and accurate estimation of individual ancestry coefficients of a dataset exhibiting population structure. PSIKO takes as input file in the .geno format, with each row consisting of a SNP, and each column consisting of an individual. It then estimates the number of founder populations, outputs ancestry estimates as well as the principal components of the dataset for subsequent use in association studies.

[**Official Website**](https://www.uea.ac.uk/computing/psiko)  

**Publications**

* (Popescu and Huber, 2015) [PSIKO2: a fast and versatile tool to infer population stratification on various levels in GWAS]( https://www.ncbi.nlm.nih.gov/pubmed/26142187). Bioinformatics. 
* (Popescu et al., 2014) [A novel and fast approach for population structure inference using kernel-PCA and optimization]( https://www.ncbi.nlm.nih.gov/pubmed/25326237).  Genetics.

**Institution(s)**   

School of Computing Sciences, University of East Anglia, Norwich Research Park, Norwich, Norfolk, UK; Centre for Novel Agricultural Products, Department of Biology, University of York, York, UK; Department of Computational and Systems Biology, John Innes Centre, Norwich Research Park, Norwich, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---


# Genotyping by Sequencing data analysis (GBS Analysis) 

<p align="justify">Genotyping by sequencing (GBS) is a next generation sequencing based method that takes advantage of reduced representation to enable high throughput genotyping of large numbers of individuals at a large number of SNP markers. The relatively straightforward, robust, and cost-effective GBS protocol is currently being applied in numerous species by a large number of researchers.

## <font color=#CD5555 face="黑体">Base Callling</font>

### PyroBayes

<p align="justify">Consists of a base calling program for pyrosequencing reads from the 454 Life Sciences sequencing machines. PyroBayes enables single-nucleotide polymorphism (SNP) calling in resequencing applications, including in shallow read coverage.

[**Official Website**](https://urgi.versailles.inra.fr/Tools/PyroBayes) 

**Publications**

* (Quinlan et al., 2008) [Pyrobayes: an improved base caller for SNP discovery in pyrosequences]( https://www.ncbi.nlm.nih.gov/pubmed/18193056).  Nat Methods.

**Institution(s)**  

Department of Biology, Boston College,Chestnut Hill, MA, USA

---

### Alta-Cyclic   

<p align="justify">Provides an Illumina genome-analyzer base caller. Alta-Cyclic is an application that uses machine learning to compensate for noise factors. It was developed to improve the number of accurate reads for sequencing runs up to 70 bases. It also permits users to reduce systematic biases, simplifying confident identification of sequence variants. This method works in two stages: the training stage and the base-calling stage.

[**Official Website**](http://hannonlab.cshl.edu/Alta-Cyclic/main.html)  

**Publications**

* (Erlich et al., 2008)[ Alta-Cyclic: a self-optimizing base caller for next-generation sequencing]( https://www.ncbi.nlm.nih.gov/pubmed/18604217).  Nat Methods. 

**Institution(s)**   

Watson School of Biological Sciences, Cold Spring Harbor, NY, USA; Howard Hughes Medical Institute, Cold Spring Harbor Laboratory, Cold Spring Harbor, NY, USA

---

### freeIbis  

<p align="justify">An efficient basecaller for Illumina sequencers with calibrated quality scores. freeIbis offers significant improvements in sequence accuracy owing to the use of a novel multiclass support vector machine (SVM) algorithm. This approach produces more accurate basecalls than the default Illumina basecaller. freeIbis can use the control sequences to calibrate the output of the SVM to produce directly calibrated quality scores. For instance, freeIbis can produce quality scores that correlate highly with observed ones.

[**Official Website**](http://grenaud.github.io/freeIbis/)  

**Publications**

* (Renaud et al., 2013) [freeIbis: an efficient basecaller with calibrated quality scores for Illumina sequencers]( https://www.ncbi.nlm.nih.gov/pubmed/23471300).  Bioinformatics.

**Institution(s)**   

Department of Evolutionary Genetics, Max Planck Institute for Evolutionary Anthropology, Leipzig, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Read Quality Contorl</font>

### Trim Galore!
<p align="justify">Assists in automating quality, adapter trimming and quality control (QC). Trim Galore! is a wrapper script that provides functionalities to remove biased methylation positions for reduced representation bisulfite sequencing (RRBS) sequence files (for directional, non-directional (or paired-end) sequencing). It can remove sequences if they become too short during the trimming process.

[**Official Website**](http://www.bioinformatics.babraham.ac.uk/projects/trim_galore/) 

**Publications**

* (Wu et al., 2011) [Using non-uniform read distribution models to improve isoform expression inference in RNA-Seq]( https://www.ncbi.nlm.nih.gov/pubmed/21169371).  Bioinformatics. 

**Institution(s)**   

TNLIST/Department of Automation, Tsinghua University, Beijing, China

---

### MultiQC   

<p align="justify">A tool to create a single report visualizing output from multiple tools across many samples, enabling global trends and biases to be quickly identified. MultiQC allows accurate comparison between samples, allowing detection of subtle differences not noticeable when switching between different files. Data visualization aids batch effect detection and minimizes the risk of confounding factors affecting the results of the study.

[**Official Website**](https://github.com/ewels/MultiQC)  

[**Github**](https://github.com/ewels/MultiQC/issues)  

**Publications**

* (Ewels et al., 2016) [MultiQC: summarize analysis results for multiple tools and samples in a single report]( https://www.ncbi.nlm.nih.gov/pubmed/27312411).  Bioinformatics.

**Institution(s)**   

Department of Biochemistry and Biophysics, Science for Life Laboratory, Stockholm University, Stockholm, Sweden; Department of Molecular Medicine and Surgery, Science for Life Laboratory, Center for Molecular Medicine, Karolinska Institute, Stockholm, Sweden; Science for Life Laboratory, School of Biotechnology, Division of Gene Technology, Royal Institute of Technology, Stockholm, Sweden

---

### Octopus-toolkit   

<p align="justify">Examines epigenomic and transcriptomic next generation sequencing (NGS) data. Octopus-toolkit can be used for antibody- or enzyme-mediated experiments and studies for the quantification of gene expression. It can accelerate the data mining of public epigenomic and transcriptomic NGS data for basic biomedical research. This tool provides a private and a public mode: one to process the user’s own data, and the other to analyze public NGS data by retrieving raw files from the GEO database.

[**Official Website**](http://octopus-toolkit2.readthedocs.io/en/latest/) 

[**Documentation**]( http://octopus-toolkit2.readthedocs.io/en/latest/guide.html) 

**Publications**

* (Kim et al., 2018) [Octopus-toolkit: a workflow to automate mining of public epigenomic and transcriptomic next-generation sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/29420797).  Nucleic Acids Res.

**Institution(s)**  

Department of Biological Sciences, Korea Advanced Institute of Science and Technology, Daejeon, Korea; Laboratory of Genetics and Physiology, National Institute of Diabetes, Digestive and Kidney Diseases, National Institutes of Health, Bethesda, MD, USA; Department of Microbiology, Dankook University, Cheonan, Korea

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Adapter trimming</font>

###Trimmomatic

<p align="justify">Performs a variety of trimming tasks for Illumina paired-end and single ended data. Trimmomatic is a flexible, pair-aware preprocessing tool, optimized for Illumina next-generation sequencing (NGS) data. The software includes several processing steps for read trimming and filtering. It uses a pipeline-based architecture, allowing individual ‘steps’ (adapter removal, quality filtering, etc.) to be applied to each read/read pair, in the order specified by user.

[**Official Website**](http://www.usadellab.org/cms/index.php?page=trimmomatic) 

[**Documentation**](http://www.usadellab.org/cms/uploads/supplementary/Trimmomatic/TrimmomaticManual_V0.32.pdf) 

**Publications**

* (Bolger et al., 2014) [Trimmomatic: a flexible trimmer for Illumina sequence data]( https://www.ncbi.nlm.nih.gov/pubmed/24695404).  Bioinformatics.

**Institution(s)**  

Department Metabolic Networks, Max Planck Institute of Molecular Plant Physiology, Golm,Institut für Biologie I, RWTH Aachen, Aachen and Institute of Bio- and Geosciences: Plant Sciences, Forschungszentrum Jülich, Jülich, Germany

---

### Trim Galore!

<p align="justify">Assists in automating quality, adapter trimming and quality control (QC). Trim Galore! is a wrapper script that provides functionalities to remove biased methylation positions for reduced representation bisulfite sequencing (RRBS) sequence files (for directional, non-directional (or paired-end) sequencing). It can remove sequences if they become too short during the trimming process.

[**Official Website**](http://www.bioinformatics.babraham.ac.uk/projects/trim_galore/) 

**Publications**

* (Wu et al., 2011) [Using non-uniform read distribution models to improve isoform expression inference in RNA-Seq]( https://www.ncbi.nlm.nih.gov/pubmed/21169371).  Bioinformatics.

**Institution(s)**  

TNLIST/Department of Automation, Tsinghua University, Beijing, China

---

### dDocent

<p align="justify">Offers a platform for population-level analyses. dDocent is an open-source software dedicated to individually barcoded restriction-site associated DNA sequencing (RADseq) data processing. The application employs data reduction techniques and interact with other programs to propose features such as de novo assembly of RAD loci, single nucleotides polymorphisms (SNPs) and indel calling as well as quality trimming or baseline data filtering.

[**Official Website**](http://ddocent.com/)  

[**Documentation**](https://groups.google.com/forum/embed/?place=forum%2Fddocent&showsearch=true&showtabs=false&parenturl=http%3A%2F%2Fddocent.com%2Fhelp%2F&theme=default#!forum/ddocent) 

[**Github**](https://github.com/jpuritz/dDocent/issues)  

**Publications**

* (Puritz et al., 2014) [dDocent: a RADseq, variant-calling pipeline designed for population genomics of non-model organisms]( https://www.ncbi.nlm.nih.gov/pubmed/24949246).  PeerJ.

**Institution(s)**   

Marine Genomics Laboratory, Harte Research Institute, Texas A&M University-Corpus Christi, Corpus Christi, TX, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Gerline SNP Detection</font>

### GATK

<p align="justify">Focuses on variant discovery and genotyping. GATK provides a toolkit, developed at the Broad Institute, composed of several tools and ables to support projects of any size. The application compiles an assortment of command line allowing one to analyze of high-throughput sequencing (HTS) data in various formats such as SAM, BAM, CRAM or VCF. The website includes multiple documentation for guiding users.

[**Official Website**]https://software.broadinstitute.org/gatk/)  

[**Forum**](https://gatkforums.broadinstitute.org/gatk/) 

**Publications**

* (van der Auwera et al., 2013) [From FastQ data to high confidence variant calls: the Genome Analysis Toolkit best practices pipeline]( https://www.ncbi.nlm.nih.gov/pubmed/25431634). Curr Protoc Bioinformatics.
* (DePristo et al., 2011) [A framework for variation discovery and genotyping using next-generation DNA sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/21478889).  Nat Genet.
* (McKenna et al., 2010) [The Genome Analysis Toolkit: a MapReduce framework for analyzing next-generation DNA sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/20644199). Genome Res.
* (Francioli et al., 2017) [A framework for the detection of de novo mutations in family-based sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/27876817).  Eur J Hum Genet.
* (Poplin et al., 2017) [Scaling accurate genetic variant discovery to tens of thousands of samples](https://doi.org/10.1101/201178).  BioRxiv.

**Institution(s)**  

Broad Institute, Cambridge, MA, USA; Massachusetts General Hospital, Boston, MA, USA

---

### SAMtools

<p align="justify">Allows users to interact with high-throughput sequencing data. SAMtools permits the manipulation of alignments in the SAM/BAM/CRAM formats: reading, writing, editing, indexing, viewing and converting SAM/BAM/CRAM format. It limits the mapping quality of reads with excessive mismatches and applies base alignment quality to fix alignment errors. This tool can sort and merge alignments, remove polymerase chain reaction (PCR) duplicates or generate per-position information.

[**Official Website**](http://www.htslib.org/)  

**Publications**

* (Li, 2011) [A statistical framework for SNP calling, mutation discovery, association mapping and population genetical parameter estimation from sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/21903627). Bioinformatics.
* (Li, 2011) [Improving SNP discovery by base alignment quality]( https://www.ncbi.nlm.nih.gov/pubmed/21320865). Bioinformatics. 
* (Li et al., 2009) [The Sequence Alignment/Map format and SAMtools]( https://www.ncbi.nlm.nih.gov/pubmed/19505943).  Bioinformatics.

**Institution(s)** 

Medical Population Genetics Program, Broad Institute, Cambridge Center, Cambridge, MA, USA

---

### dDocent

<p align="justify">Offers a platform for population-level analyses. dDocent is an open-source software dedicated to individually barcoded restriction-site associated DNA sequencing (RADseq) data processing. The application employs data reduction techniques and interact with other programs to propose features such as de novo assembly of RAD loci, single nucleotides polymorphisms (SNPs) and indel calling as well as quality trimming or baseline data filtering.

[**Official Website**](http://ddocent.com/)  

[**Documentation**](https://groups.google.com/forum/embed/?place=forum%2Fddocent&showsearch=true&showtabs=false&parenturl=http%3A%2F%2Fddocent.com%2Fhelp%2F&theme=default#!forum/ddocent) 

[**Github**](https://github.com/jpuritz/dDocent/issues)  

**Publications**

* (Puritz et al., 2014) [dDocent: a RADseq, variant-calling pipeline designed for population genomics of non-model organisms]( https://www.ncbi.nlm.nih.gov/pubmed/24949246).  PeerJ.

**Institution(s)**   

Marine Genomics Laboratory, Harte Research Institute, Texas A&M University-Corpus Christi, Corpus Christi, TX, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Somatic SNV detection</font>

### GATK

<p align="justify">Focuses on variant discovery and genotyping. GATK provides a toolkit, developed at the Broad Institute, composed of several tools and ables to support projects of any size. The application compiles an assortment of command line allowing one to analyze of high-throughput sequencing (HTS) data in various formats such as SAM, BAM, CRAM or VCF. The website includes multiple documentation for guiding users.

[**Official Website**]https://software.broadinstitute.org/gatk/)  

[**Forum**](https://gatkforums.broadinstitute.org/gatk/) 

**Publications**

* (van der Auwera et al., 2013) [From FastQ data to high confidence variant calls: the Genome Analysis Toolkit best practices pipeline]( https://www.ncbi.nlm.nih.gov/pubmed/25431634). Curr Protoc Bioinformatics.
* (DePristo et al., 2011) [A framework for variation discovery and genotyping using next-generation DNA sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/21478889).  Nat Genet.
* (McKenna et al., 2010) [The Genome Analysis Toolkit: a MapReduce framework for analyzing next-generation DNA sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/20644199). Genome Res.
* (Francioli et al., 2017) [A framework for the detection of de novo mutations in family-based sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/27876817).  Eur J Hum Genet.
* (Poplin et al., 2017) [Scaling accurate genetic variant discovery to tens of thousands of samples](https://doi.org/10.1101/201178).  BioRxiv.

**Institution(s)**  

Broad Institute, Cambridge, MA, USA; Massachusetts General Hospital, Boston, MA, USA

---

### SAMtools

<p align="justify">Allows users to interact with high-throughput sequencing data. SAMtools permits the manipulation of alignments in the SAM/BAM/CRAM formats: reading, writing, editing, indexing, viewing and converting SAM/BAM/CRAM format. It limits the mapping quality of reads with excessive mismatches and applies base alignment quality to fix alignment errors. This tool can sort and merge alignments, remove polymerase chain reaction (PCR) duplicates or generate per-position information.

[**Official Website**](http://www.htslib.org/)  

**Publications**

* (Li, 2011) [A statistical framework for SNP calling, mutation discovery, association mapping and population genetical parameter estimation from sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/21903627). Bioinformatics.
* (Li, 2011) [Improving SNP discovery by base alignment quality]( https://www.ncbi.nlm.nih.gov/pubmed/21320865). Bioinformatics. 
* (Li et al., 2009) [The Sequence Alignment/Map format and SAMtools]( https://www.ncbi.nlm.nih.gov/pubmed/19505943).  Bioinformatics.

**Institution(s)** 

Medical Population Genetics Program, Broad Institute, Cambridge Center, Cambridge, MA, USA

---

### SNooPer

<p align="justify">A versatile machine learning approach that uses Random Forest classification models to accurately call somatic variants in low-depth sequencing data. SNooPer uses a subset of variant positions from the sequencing output for which the class, true variation or sequencing error, is known to train the data-specific model. During the training phase, using a real dataset of 40 childhood acute lymphoblastic leukemia patients, it was shown how the SNooPer algorithm is not affected by low coverage or low variant allele frequencies, and can be used to reduce overall sequencing costs while maintaining high specificity and sensitivity to somatic variant calling.

[**Official Website**](https://sourceforge.net/projects/snooper/)  

**Publications**

* (Spinella et al., 2016) [SNooPer: a machine learning-based method for somatic variant identification from low-pass next-generation sequencing]( https://www.ncbi.nlm.nih.gov/pubmed/27842494). BMC Genomics.

**Institution(s)** 

CHU Sainte-Justine Research Center, Université de Montréal, Montreal, Canada; Department of Pediatrics, Faculty of Medicine, Université de Montréal, Montreal, Canada; Division of Hematology-Oncology, CHU Sainte-Justine Research Center, Montreal, Canada

---

# Restriction Site Associated DNA Sequencing Data Analysis (RAD-seq Analysis) 

<p align="justify">RAD markers were first implemented using microarrays (Miller et al., 2007) and later adapted for NGS (Baird et al., 2008). RAD-seq could generate a genome-wide density of genetic markers. RAD-seq has been used to study population differentiation and selection (Emerson et al., 2010; Hohenlohe et al., 2011).

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Phylogenetic Inference</font>

### MEGA

<p align="justify">An integrated tool for conducting sequence alignment, inferring phylogenetic trees, estimating divergence times, mining online databases, estimating rates of molecular evolution, inferring ancestral sequences, and testing evolutionary hypotheses.

[**Official Website**](https://www.megasoftware.net/)  

**Publications**

* (Kumar et al., 1994) [MEGA: Molecular Evolutionary Genetics Analysis software for microcomputers]( https://www.ncbi.nlm.nih.gov/pubmed/8019868). Comput Appl Biosci.
* (Kumar et al., 2001)[MEGA2: molecular evolutionary genetics analysis software]( https://www.ncbi.nlm.nih.gov/pubmed/11751241).  Bioinformatics.
* (Tamura et al., 2011) [MEGA5: molecular evolutionary genetics analysis using maximum likelihood, evolutionary distance, and maximum parsimony methods]( https://www.ncbi.nlm.nih.gov/pubmed/21546353). Mol Biol Evol.
* (Kumar et al., 2016) [MEGA7: Molecular Evolutionary Genetics Analysis Version 7.0 for Bigger Datasets]( https://www.ncbi.nlm.nih.gov/pubmed/27004904).  Mol Biol Evol.

**Institution(s)**  

Institute for Genomics and Evolutionary Medicine, Temple University Department of Biology, Temple University Center for Excellence in Genome Medicine and Research, King Abdulaziz University, Jeddah, Saudi Arabia.

---

### GPSit

<p align="justify">Facilitates phylogenomic analyses on microeukaryotes. GPSit is an automated method that is compatible with data from genome sequencing and transcriptome sequencing, including that from single cells. The software can contribute to the automated process and scalability of collection of extended DNA barcodes and specimen identification after genome skimming or single-cell sequencing. It is useful for molecular systematics and molecular ecological investigations.

[**Official Website**](https://github.com/seanchen607/GPSit)  

**Publications**

* (Chen et al., 2018) [GPSit: An Automated Method for Evolutionary Analysis of Nonculturable Ciliated Microeukaryotes]( https://doi.org/10.1111/1755-0998.12750).  Mol Ecol Resour.

**Institution(s)**   

Institute of Evolution & Marine Biodiversity, Ocean University of China, Qingdao, China; Laboratory for Marine Biology and Biotechnology, Qingdao National Laboratory for Marine Science and Technology, Qingdao, China; Department of Life Sciences, Natural History Museum, London, UK; College of Marine Life Sciences, Ocean University of China, Qingdao, China

---

### AnGST

<p align="justify">Allows analysis of gene and species trees. AnGST is a phylogenomic method comparing individual gene phylogenies with the phylogeny of organisms. This tool uses the topology of the genealogy tree to function, and can infer the direction of gene transfer in addition to gene duplication. It accounts for uncertainty in gene trees by incorporating reconciliation into the tree-building process.

[**Official Website**](http://almlab.mit.edu/angst.html)  

[**Documentation**](https://github.com/almlab/angst/blob/master/doc/manual.pdf) 

[**Github**](https://github.com/almlab/angst/issues)  

**Publications**

* (David and Alm, 2011) [Rapid evolutionary innovation during an Archaean genetic expansion](https://www.ncbi.nlm.nih.gov/pubmed/21170026).  Nature.

**Institution(s)**  

Computational & Systems Biology Initiative, Massachusetts Institute of Technology, Cambridge, MA, USA; Departments of Biological Engineering & Civil and Environmental Engineering, Massachusetts Institute of Technology, Cambridge, MA, USA; The Broad Institute, Cambridge, MA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">SNP/SNV Annotation</font>

### ANNOVAR

<p align="justify">An efficient software tool to utilize update-to-date information to functionally annotate genetic variants detected from diverse genomes (including human genome hg18, hg19, hg38, as well as mouse, worm, fly, yeast and many others). Using a desktop computer, ANNOVAR requires ∼4 min to perform gene-based annotation and ∼15 min to perform variants reduction on 4.7 million variants, making it practical to handle hundreds of human genomes in a day.

[**Official Website**](http://annovar.openbioinformatics.org/en/latest/)  

**Publications**

* (Wang et al., 2010) [ANNOVAR: functional annotation of genetic variants from high-throughput sequencing data]( https://www.ncbi.nlm.nih.gov/pubmed/20601685).  Nucleic Acids Res.
* (Yang and Wang, 2015)[ Genomic variant annotation and prioritization with ANNOVAR and wANNOVAR]( https://www.ncbi.nlm.nih.gov/pubmed/26379229).  Nat Protoc.
* (Chang and Wang, 2012)[ wANNOVAR: annotating genetic variants for personal genomes via the web]( https://www.ncbi.nlm.nih.gov/pubmed/22717648).  J Med Genet.

**Institution(s)**   

Center for Applied Genomics, Children’s Hospital of Philadelphia, Department of Biostatistics and Epidemiology and Department of Pediatrics, University of Pennsylvania, Philadelphia, PA, USA

---

### wANNOVAR

<p align="justify">ANNOVAR is a rapid, efficient tool to annotate functional consequences of genetic variation from high-throughput sequencing data. wANNOVAR provides easy and intuitive web-based access to the most popular functionalities of the ANNOVAR software. It provides simple and intuitive interface to help users determine the functional significance of variants. These include annotating single nucleotide variants and insertions/deletions for their effects on genes, reporting their conservation levels (such as PhyloP and GERP++ scores), calculating their predicted functional importance scores (such as SIFT and PolyPhen scores), retrieving allele frequencies in public databases (such as the 1000 Genomes Project and NHLBI-ESP 5400 exomes), and implementing a 'variants reduction' protocol to identify a subset of potentially deleterious variants/genes.

[**Official Website**]http://wannovar.wglab.org/)  

**Publications**

* (Chang and Wang, 2012)[ wANNOVAR: annotating genetic variants for personal genomes via the web]( https://www.ncbi.nlm.nih.gov/pubmed/22717648).  J Med Genet.

**Institution(s)**   

Zilkha Neurogenetic Institute, Keck School of Medicine, University of Southern California, Los Angeles, CA, USA

---

### DNAscan

<p align="justify">Offers a platform dedicated to DNA next-generation sequencing (NGS) data analysis, annotation and visualization. DNAscan can be set for running on various mode to adapt its performance to focus on a specific subregion or material. The application is able to detect a wide range of genetic material including single nucleotides variants (SNVs), repeat expansions and structural variants (SVs). The application can be run through Docker and Singularity.

[**Official Website**](https://github.com/KHP-Informatics/DNAscan) 

**Publications**

* (Iacoangeli et al., ) [DNAscan: a fast, computationally and memory efficient bioinformatics pipeline for the analysis of DNA next-generation-sequencing data]( https://doi.org/10.1101/267195). BioRxiv.

**Institution(s)**   

Department of Biostatistics and Health Informatics, King’s College London, London, UK; Maurice Wohl Clinical Neuroscience Institute, King’s College London, London, UK.

---

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMICTOOLS**](https://omictools.com/genomics2-category)

[*Image Citation*](http://www.cnag.crg.eu/news/new-research-team-population-genomics)

---