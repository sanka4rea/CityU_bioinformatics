+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Prediction of Protein Structure"

weight = 20
# Project summary to display on homepage.
summary = "Protein structure prediction is the inference of the three-dimensional structure of a protein from its amino acid sequence—that is, the prediction of its folding and its secondary and tertiary structure from its primary structure."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/protein/structure.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["proteomics"]

# Optional external URL for project (replaces project detail page).
external_link = ""


# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"


+++
---
<img src="/img/tools/protein/structure.jpg" alt="blast" align="center">

<span id="top"></span>

{{% toc %}}

# Primary structure

<p align="justify">Protein primary structure is the linear sequence of amino acids in a peptide or protein. By convention, the primary structure of a protein is reported starting from the amino-terminal (N) end to the carboxyl-terminal (C) end. Protein biosynthesis is most commonly performed by ribosomes in cells. Peptides can also be synthesized in the laboratory.[citation needed] Protein primary structures can be directly sequenced, or inferred from DNA sequences.

### ProtParam

<p align="justify">ProtParam (References / Documentation) is a tool which allows the computation of various physical and chemical parameters for a given protein stored in Swiss-Prot or TrEMBL or for a user entered protein sequence. The computed parameters include the molecular weight, theoretical pI, amino acid composition, atomic composition, extinction coefficient, estimated half-life, instability index, aliphatic index and grand average of hydropathicity (GRAVY) (Disclaimer).

[**Official Website**](https://web.expasy.org/protparam/)


**Publications**

* [Protein Identification and Analysis Tools on the ExPASy Server](https://www.ncbi.nlm.nih.gov/pubmed/10027275) (In) John M. Walker (ed): The Proteomics Protocols Handbook, Humana Press (2005).  

<p align="justify">ProtParam computes various physico-chemical properties that can be deduced from a protein sequence. No additional information is required about the protein under consideration. The protein can either be specified as a Swiss-Prot/TrEMBL accession number or ID, or in form of a raw sequence. White space and numbers are ignored. If you provide the accession number of a Swiss-Prot/TrEMBL entry, you will be prompted with an intermediary page that allows you to select the portion of the sequence on which you would like to perform the analysis. The choice includes a selection of mature chains or peptides and domains from the Swiss-Prot feature table (which can be chosen by clicking on the positions), as well as the possibility to enter start and end position in two boxes. By default (i.e. if you leave the two boxes empty) the complete sequence will be analyzed. 


### COILS

<p align="justify">COILS is a program that compares a sequence to a database of known parallel two-stranded coiled-coils and derives a similarity score. By comparing this score to the distribution of scores in globular and coiled-coil proteins, the program then calculates the probability that the sequence will adopt a coiled-coil conformation.

[**Official Website**](https://embnet.vital-it.ch/software/COILS_form.html)

**Publications**

* Lupas, A., Van Dyke, M., and Stock, J. (1991) [Predicting Coiled Coils from Protein Sequences](https://www.researchgate.net/profile/Andrei_Lupas/publication/6042403_Predicting_Coled_Coils_from_Protein_Sequences/links/00b4951710268a2a2d000000.pdf)

[**Tutorial**](https://embnet.vital-it.ch/software/coils/COILS_doc.html)

<p align="justify">COILS is specific for solvent-exposed, left-handed coiled coils. Other types of coiled-coil structure, such as buried coiled coils (e.g the central coiled coil in catabolite repressor protein, or some transmembrane domains) and right-handed coiled coils, are not detected by the program.

<p align="justify">COILS does not reach yes-or-no decisions based on a threshold value. Rather, it yields a set of probabilities that presumably reflect the coiled-coil forming potential of a sequence. This means that even at high probabilities (e.g. >90%), there will be (and should be) sequences that in fact do not form a coiled coil, though they may have the potential to do so in a different context.

<p align="justify">COILS is biased towards hydrophilic, highly charged sequences. For this reason, all scans should be performed with a weighted and an unweighted matrix, and the results compared. Differences of more than 20-30 percentage points in the probabilities should be taken to indicate that a coiled-coil structure is unlikely, the elevated scores being mainly due to the high incidence of charged residues (note, though, that this would have marked human mannose-binding protein as a false positive).

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Secondary structure

<p align="justify">The secondary structure is the pattern of hydrogen bonds in a biopolymer. These determine the general three-dimensional form of local segments of the biopolymers, but does not describe the global structure of specific atomic positions in three-dimensional space, which are considered to be tertiary structure. Secondary structure is formally defined by the hydrogen bonds of the biopolymer, as observed in an atomic-resolution structure. In proteins, the secondary structure is defined by patterns of hydrogen bonds between backbone amine and carboxyl groups (sidechain–mainchain and sidechain–sidechain hydrogen bonds are irrelevant), where the DSSP definition of a hydrogen bond is used. In nucleic acids, the secondary structure is defined by the hydrogen bonding between the nitrogenous bases.

### PredictProtein

<p align="justify">PredictProtein (PP) went online as one of the first Internet servers in molecular biology in 1992. Ever since, it has been driven by the commitment to include whatever can reasonably be predicted from protein sequence with respect to the annotation of protein function and structure. Our goal has been a service that bridges the annotation gap created by the explosion of sequencing data. Today hunderds of users from over 110 countries access the site daily and submit thousands of sequences.

[**Official Website**](https://www.predictprotein.org/)

**Publications**

* [The PredictProtein server](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC441515/)

<p align="justify">PredictProtein started out by predicting secondary structure and returning families of related proteins. Solvent accessibility and transmembrane helix prediction followed suit shortly thereafter. Over the two decades that PredictProtein has been operating, we have substantially expanded the breadth of structural annotations, e.g. by adding predictions of non-regular secondary structure and intrinsically disordered regions, disulphide bridges and inter-residue contacts, and finally by also covering trans-membrane beta barrels structures. We have also added important resources for the prediction of protein function, e.g. assisting in the annotation of subcellular localization (LocTree, LocTree2, NLSpred), identifying protein-protein interaction sites (ISIS) and protein-DNA binding sites (DISIS & SomeNA to be released shortly). We have added a few simple tools to predict enzymatic activity (unfortunately, this method did not survive the move from New York to Munich) and to infer GeneOntology numbers through sequence homology (MetaStudent). Another major addition are the tools that predict the effect of amino acid changes upon protein function (SNAP & SNAP2), and directly upon protein structure (in preparation).

### PSIPRED

<p align="justify">PSI-blast based secondary structure PREDiction (PSIPRED) is a method used to investigate protein structure. It uses artificial neural network machine learning methods in its algorithm.It is a server-side program, featuring a website serving as a front-end interface, which can predict a protein's secondary structure (beta sheets, alpha helixes and coils) from the primary sequence.

[**Official Website**](http://bioinf.cs.ucl.ac.uk/psipred/)

**Publications**

* Buchan DWA, Minneci F, Nugent TCO, Bryson K, Jones DT. (2013). [Scalable web services for the PSIPRED Protein Analysis Workbench . Nucleic Acids Research .](https://www.ncbi.nlm.nih.gov/pubmed/23748958)

<p align="justify">PSIPRED is available as a web service and as software. The software is distributed as source code, licensed technically as proprietary software. It allows modifying, but enforces freeware provisions by forbidding for-profit distribution of the software and its results.

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# tertiary structure

<p align="justify">The tertiary structure of a protein or any other macromolecule is its three-dimensional structure, as defined by the atomic coordinates. Proteins and nucleic acids fold into complex three-dimensional structures which result in the molecules' functions. While such structures are diverse and complex, they are often composed of recurring, recognizable tertiary structure motifs and domains that serve as molecular building blocks. Tertiary structure is considered to be largely determined by the biomolecule's primary structure (its sequence of amino acids or nucleotides).

### Phyre

<p align="justify">Phyre and Phyre2 (Protein Homology/AnalogY Recognition Engine; pronounced as 'fire') are web-based services for protein structure prediction that are free for non-commercial use.

<p align="justify">Phyre is among the most popular methods for protein structure prediction having been cited over 1500 times. Like other remote homology recognition techniques (see protein threading), it is able to regularly generate reliable protein models when other widely used methods such as PSI-BLAST cannot. Phyre2 has been designed (funded by the BBSRC)[citation needed] to ensure a user-friendly interface for users inexpert in protein structure prediction methods.

[**Official Website**](http://www.sbg.bio.ic.ac.uk/phyre2/html/page.cgi?id=index)

**Publications**

* [The Phyre2 web portal for protein modeling, prediction and analysis](https://www.nature.com/articles/nprot.2015.053)

<p align="justify">The Phyre and Phyre2 servers predict the three-dimensional structure of a protein sequence using the principles and techniques of homology modeling. Because the structure of a protein is more conserved in evolution than its amino acid sequence, a protein sequence of interest (the target) can be modeled with reasonable accuracy on a very distantly related sequence of known structure (the template), provided that the relationship between target and template can be discerned through sequence alignment. Currently the most powerful and accurate methods for detecting and aligning remotely related sequences rely on profiles or hidden Markov models (HMMs). These profiles/HMMs capture the mutational propensity of each position in an amino acid sequence based on observed mutations in related sequences and can be thought of as an 'evolutionary fingerprint' of a particular protein.

### Swiss-PdbViewer

<p align="justify">Swiss-PdbViewer (aka DeepView) is an application that provides a user friendly interface allowing to analyze several proteins at the same time. The proteins can be superimposed in order to deduce structural alignments and compare their active sites or any other relevant parts. Amino acid mutations, H-bonds, angles and distances between atoms are easy to obtain thanks to the intuitive graphic and menu interface.

[**Official Website**](https://spdbv.vital-it.ch/)

**Publications**

* Guex, N. and Peitsch, M.C. (1997) [SWISS-MODEL and the Swiss-PdbViewer: An environment for comparative protein modeling](https://www.ncbi.nlm.nih.gov/pubmed/9504803).

<p align="justify">Swiss-PdbViewer (aka DeepView) has been developped since 1994 by Nicolas Guex. Swiss-PdbViewer is tightly linked to SWISS-MODEL, an automated homology modeling server developed within the Swiss Institute of Bioinformatics (SIB) at the Structural Bioinformatics Group at the Biozentrum in Basel.

<p align="justify">Working with these two programs greatly reduces the amount of work necessary to generate models, as it is possible to thread a protein primary sequence onto a 3D template and get an immediate feedback of how well the threaded protein will be accepted by the reference structure before submitting a request to build missing loops and refine sidechain packing.

<p align="justify">Swiss-PdbViewer can also read electron density maps, and provides various tools to build into the density. In addition, various modeling tools are integrated and residues can be mutated.

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMICTOOLS**](https://omictools.com/proteomics-category)

[*Image Citation*](https://www.slideshare.net/karamveer37/methods-for-protein-structure-prediction)

---