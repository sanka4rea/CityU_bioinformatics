+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "Protein Interactions"

weight = 40
# Project summary to display on homepage.
summary = "Including: Protein Interactions Analysis, FRET."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/protein/actions.png"

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

<img src="/img/tools/protein/actions.png"  width="400" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Protein Interactions Analysis

<p align="justify">**Proteins interact** with nucleic acids, other proteins, ligands, metal ions, to exert their biological functions. Mass-spectrometry and protein chips have revolutionized the field of proteomics and the study of protein interactions to a wider scale, which require specific tools for their analyses. The study of protein interactions has implications for drug discovery and design.

---

## <font color=#CD5555 face="黑体">Protein-DNA Interaction Prediction</font>

Protein-DNA complexes play vital roles in many cellular processes by the interactions of amino acids with DNA. Several computational methods have been developed for predicting the interacting residues in DNA-binding proteins using sequence and/or structural information.

---

### LigParGen | Protein-ligand docking : Protein interaction analysis

<p align="justify">Provides an intuitive interface for generating OPLS-AA/1.14*CM1A(-LBCC) force field (FF) parameters for organic ligands. LigParGen is a web server which generates ligand parameters for common simulation software packages such as NAMD, GROMACS, OpenMM, BOSS and MCPRO. The software allows the users to obtain high quality parameters for molecular mechanics (MM) simulations without extensive knowledge about MM force fields or quantum mechanics (QM) methods.

[**Official Website**](http://zarbi.chem.yale.edu/ligpargen/)

**Publications**:

* (2017 Nucleic Acids Res) [LigParGen web server: an automatic OPLS-AA parameter generator for organic ligands.](https://doi.org/10.1093/nar/gkx312)

**Institutions(s)**:

Department of Chemistry, Yale University, New Haven, CT, USA

---

### DBSI | DNA Binding Site Identifier

<p align="justify">A powerful structure-based SVM model for the prediction and visualization of DNA binding sites on protein structures. DBSI is a machine learning approach to classify surface residues as binders or non-binders of DNA. DBSI employs sequence- and structure-based features encompassing a range of physical, chemical, geometric and evolutionary properties of the protein surface. DBSI also implements microenvironment features that allow for small-scale structural perturbation and the role of non-local cooperative effects. DBSI has been shown to be a top-performing model to predict DNA binding sites on the surface of a protein or peptide and shows promise in predicting RNA binding sites.

[**Official Website**](https://mitchell-lab.biochem.wisc.edu/DBSI_Server/index.php)

**Publications**:

* (2016 Bioinformatics) [DBSI server: DNA binding site identifier.](https://www.ncbi.nlm.nih.gov/pubmed/27259543)

**Institutions(s)**:

Department of Biochemistry, University of Wisconsin-Madison, Madison, WI, USA; School of Life Sciences, Anhui University, Hefei, Anhui Province, China

---

## <font color=#CD5555 face="黑体">Protein-RNA Interaction Prediction</font>

<p align="justify">Interactions between proteins and RNA play essential roles for life. For example, protein-RNA interactions mediate RNA metabolic processes such as splicing, polyadenylation, messenger RNA stability, localization and translation. Furthermore, many of these RNA-binding proteins are involved in human diseases.

---

### HADDOCK | High Ambiguity Driven protein-protein DOCKing

<p align="justify">An information-driven flexible docking approach for the modeling of biomolecular complexes. HADDOCK distinguishes itself from ab-initio docking methods in the fact that it encodes information from identified or predicted protein interfaces in ambiguous interaction restraints (AIRs) to drive the docking process. HADDOCK can deal with a large class of modeling problems including protein-protein, protein-nucleic acids and protein-ligand complexes.

[**Official Website**](http://haddock.science.uu.nl/services/HADDOCK2.2/)

**Publications**:

* (2018 Nat Protoc) [Defining distance restraints in HADDOCK.](https://www.nature.com/articles/s41596-018-0017-6)

* (2016 J Mol Biol) [The HADDOCK2.2 Web Server: User-Friendly Integrative Modeling of Biomolecular Complexes.](https://www.ncbi.nlm.nih.gov/pubmed/26410586)

**Institutions(s)**:

Bijvoet Center for Biomolecular Research, Science Faculty, Utrecht University, Utrecht, Netherlands

---

### Global Score | Protein-RNA interactions

<p align="justify">Predicts protein interactions with transcripts > 1000nt. Global Score is an algorithm that integrates the information coming from protein and RNA fragments into an overall binding propensity value. It was applied to all RBP-RNA pairs studied by eCLIP, and the number of predicted interactions significantly increases with the read counts, while pairs that are predicted to not interact show the opposite trend. It was also used to predict physical interactions between Xist and RNA-binding proteins and identified 5 interactions with Spen, Hnrnpk, Hrnnpu/Saf-A, Lbr and Ptbp1.

[**Official Website**](http://service.tartaglialab.com/update_submission/103005/aa8e78df20)

**Publications**:

* (2016 Nat Methods) [Quantitative predictions of protein interactions with long noncoding RNAs.](https://www.ncbi.nlm.nih.gov/pubmed/28032625)


**Institutions(s)**:

Centre for Genomic Regulation (CRG), The Barcelona Institute of Science and Technology, Barcelona, Spain; Universitat Pompeu Fabra (UPF), Barcelona, Spain

---

## <font color=#CD5555 face="黑体">Drug-target Interaction Prediction</font>

<p align="justify">Identification of drug-target interactions is an important process in drug discovery. Although high-throughput screening and other biological assays are becoming available, experimental methods for drug-target interaction identification remain to be extremely costly, time-consuming and challenging even nowadays. Therefore, various computational models have been developed to predict potential drug-target associations on a large scale.

---

### Open Targets | Drug-target interaction prediction : Protein interaction analysis

<p align="justify">A data integration and visualization platform that provides evidence about the association of known and potential drug targets with diseases. Open Targets platform is designed to support identification and prioritization of biological targets for follow-up. Each drug target is linked to a disease using integrated genome-wide data from a broad range of data sources. The platform provides either a target-centric workflow to identify diseases that may be associated with a specific target, or a disease-centric workflow to identify targets that may be associated with a specific disease. Users can easily transition between these target- and disease-centric workflows. Open Targets platform provides free data access through your web browser or through an API (Application Programming Interface).

[**Official Website**](https://www.targetvalidation.org/)

**Publications**:

* (2017 Nucleic Acids Res) [Open Targets: a platform for therapeutic target identification and validation.](https://www.ncbi.nlm.nih.gov/pubmed/27899665)


**Institutions(s)**:

Open Targets, Wellcome Genome Campus, Hinxton, Cambridge, UK; GSK, Medicines Research Center, Gunnels Wood Road, Stevenage, UK; Biogen, Cambridge, MA, USA

---

### PiHelper | Drug-target interaction prediction : Protein interaction analysis

<p align="justify">A drug- and antibody-target information aggregator and provider service.

[**Official Website**](https://bitbucket.org/armish/pihelper)

**Publications**:

* (2013 Bioinformatics) [PiHelper: an open source framework for drug-target and antibody-target data.](https://www.ncbi.nlm.nih.gov/pubmed/23766416)


**Institutions(s)**:

Computational Biology Center, Memorial Sloan-Kettering Cancer Center, NY, USA

---

## <font color=#CD5555 face="黑体">Protein-protein Interaction Prediction</font>

<p align="justify">Systems biology research is like solving a puzzle: the goal is to figure out how the various parts interact and work together. The interactome of an organism is then analogous to the puzzle’s key: it describes the network of all the protein–protein interactions (PPIs). As such, identifying all the PPIs for an organism is of great value. Despite the use of high-throughput techniques in discovering PPIs, however, the coverage of experimentally determined PPI data remains poor. Such low coverage is partly because the set of possible PPIs to be verified is so large that any exhaustive experimental verification will take a long time, even with high-throughput techniques.

---

### mentha | Protein-protein interaction prediction : Protein interaction analysis

<p align="justify">Provides protein-protein interaction (PPI) data for many species, including human. mentha allows users to assemble and analyze collections of proteins and networks of interest. It focuses on experimentally demonstrated physical interactions, in order to avoid the confusion between physical and genetic interactions and between experimental and inferred interactions. The database’s information come from manually curated protein-protein interaction databases.

[**Official Website**](http://mentha.uniroma2.it/)

**Publications**:

* (2013 Nat Methods) [mentha: a resource for browsing integrated protein-interaction networks](https://www.ncbi.nlm.nih.gov/pubmed/23900247)

**Institutions(s)**:

Department of Biology, University of Rome Tor Vergata, Rome, Italy; Fondazione Santa Lucia Istituto di Ricovero e Cura a Carattere Scientifico (IRCCS), Rome, Italy

---

### compPASS | comparative proteomic analysis software suite

<p align="justify">Allows to analyze proteomic data. The compPASS method gives confidence measurements to interactions from parallel non-reciprocal proteomic datasets in using unbiased metrics. This tool is applicable to proteomic investigations ranging from focused studies on a small number of selected proteins to the analysis of entire protein families or biological regulatory networks.

[**Official Website**](https://github.com/dnusinow/cRomppass)

**Publications**:

* (2009 Cell) [Defining the human deubiquitinating enzyme interaction landscape.](https://www.ncbi.nlm.nih.gov/pubmed/19615732)

**Institutions(s)**:

Department of Pathology, Harvard Medical School, Boston, MA, USA; Department of Cell Biology, Harvard Medical School, Boston, MA, USA

---

## <font color=#CD5555 face="黑体">Protein-ligand Docking</font>

Protein-ligand docking is a key computational method in the design of starting points for the drug discovery process.

---

### UCSF Chimera

<p align="justify">Permits to interactively visualize and analyse molecular structures and related data, including density maps, supramolecular assemblies, sequence alignments, docking results, trajectories, and conformational ensembles. UCSF Chimera allows users to incorporate new features. It contains some extensions which permits to visualize large-scale molecular assemblies such as viral coats, and allows researchers to share a Chimera session interactively despite being at separate locales. Other extensions can be used for extend the tool capabilities.

[**Official Website**](http://www.cgl.ucsf.edu/chimera/)

**Publications**:

* (2004 J Comput Chem) [UCSF Chimera--a visualization system for exploratory research and analysis.](https://www.ncbi.nlm.nih.gov/pubmed/15264254)

**Institutions(s)**:

Computer Graphics Laboratory, Department of Pharmaceutical Chemistry, University of California, San Francisco, CA, USA

---

## <font color=#CD5555 face="黑体">Protein-protein Docking</font>

<p align="justify">Protein-protein interactions lie at the heart of most cellular processes. Protein-protein docking is important for understanding disease mechanisms and for drug discovery.

---

### PIPER | Protein-protein docking : Protein interaction analysis

<p align="justify">Generates accurate structures of protein-protein complexes. PIPER is a Fast Fourier Transform (FFT)-based protein docking program, extended to be used with pairwise interaction potentials and based on docking code from the Vajda lab at Boston University. The software allows to improve results docking an antigen to an antibody or docking to form a dimer or trimer.

[**Official Website**](https://www.schrodinger.com/piper)

**Publications**:

* (2006 Proteins) [PIPER: an FFT-based protein docking program with pairwise potentials.](https://www.ncbi.nlm.nih.gov/pubmed/16933295)

**Institutions(s)**:

Department of Biomedical Engineering, Boston University, Boston, MA, USA; Program in Bioinformatics, Boston University, Boston, MA, USA

---

### HADDOCK | High Ambiguity Driven protein-protein DOCKing

<p align="justify">An information-driven flexible docking approach for the modeling of biomolecular complexes. HADDOCK distinguishes itself from ab-initio docking methods in the fact that it encodes information from identified or predicted protein interfaces in ambiguous interaction restraints (AIRs) to drive the docking process. HADDOCK can deal with a large class of modeling problems including protein-protein, protein-nucleic acids and protein-ligand complexes.

[**Official Website**](http://haddock.science.uu.nl/services/HADDOCK2.2/)

**Publications**:

* (2018 Nat Protoc) [Defining distance restraints in HADDOCK.](https://www.nature.com/articles/s41596-018-0017-6)

* (2010 Nat Protoc) [The HADDOCK web server for data-driven biomolecular docking.](https://www.ncbi.nlm.nih.gov/pubmed/20431534)

**Institutions(s)**:

Bijvoet Center for Biomolecular Research, Science Faculty, Utrecht University, Utrecht, Netherlands

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/proteomics-category)

[*Image Citation*](http://pubs.rsc.org/en/content/articlelanding/2015/cc/c4cc08565e#!divAbstract)

---