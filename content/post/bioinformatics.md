+++
title = "Bioinformatics FAQ"

date = 2016-04-20
lastmod = 2018-04-11
draft = false

tags = ["bio"]

summary = "**Bioinformatics is an interdisciplinary field that develops methods and software tools for understanding biological data.** <br/>This part we will focus on below list of questions: <br/> 1. What is bioinformatics? <br/> 2. What are the origins of bioinformatics? <br/> 3. What are the most common bioinformatics programs? <br/> 4. What are the most common bioinformatics technologies? <br/> 5. How are data analyzed in bioinformatics? <br/> 6. Fields related to bioinformatics <br/> "

[header]
image = "headers/faqs1.png"
caption = "Image credit: [**FAQs**](http://animallawsource.org/faq/)"

+++
---
### What is bioinformatics?

<p align="justify">**Bioinformatics** has been defined many different ways, since practitioners do not always agree upon the scope of its use within the biological and computer sciences, but it is always considered a combination of both sciences, along with other contributing disciplines.

<p align="justify"> As an interdisciplinary field of science, bioinformatics combines Computer Science, Biology, Mathematics, Statistics and Engineering to analyze and interpret biological data. Bioinformatics has been used for in silico analyses of biological queries using mathematical and statistical techniques. More broadly, bioinformatics is applied statistics and computing to biological science.

### What are the origins of bioinformatics?

<p align="justify">The origins of bioinformatics are disputed.

<p align="justify">From `T.K. Attwood` and `D.J. Parry-Smith's` [Introduction to Bioinformatics, Prentice-Hall 1999](https://www.bioinformatics.org/wiki/Introduction_to_Bioinformatics_(Attwood)) (Longman Higher Education; ISBN 0582327881):

* <p align="justify">"The term bioinformatics is used to encompass almost all computer applications in biological sciences, but was originally coined in the mid-1980s for the analysis of biological sequence data."

<p align="justify">From `Mark S. Boguski's` article in the "Trends Guide to Bioinformatics" Elsevier, Trends Supplement 1998 p1:

* <p align="justify">"The term "bioinformatics" is a relatively recent invention, not appearing in the literature until 1991 and then only in the context of the emergence of electronic publishing... "...However, some of my role models when I was a graduate student (Margaret O. Dayhoff, Russell F. Doolittle, Walter M. Fitch and Andrew D. McLachlan) had been building databases, developing algorithms and making biological discoveries by sequence analysis since the 1960s---long before anyone thought to label this activity with a special term (if anything it was called `molecular evolution'). Even a relatively new kid on the block, the National Center for Biotechnology Information (NCBI), is celebrating its 10th anniversary this year, having been written into existence by US Congressman Claude Pepper and President Ronald Reagan in 1988. So bioinformatics has, in fact, been in existence for more than 30 years and is now middle-aged."

**History**

<p align="justify">Historically, the term bioinformatics did not mean what it means today. Paulien Hogeweg and Ben Hesper coined it in 1970 to refer to the study of information processes in biotic systems. This definition placed bioinformatics as a field parallel to biophysics (the study of physical processes in biological systems) or biochemistry (the study of chemical processes in biological systems).

### The goals of bioinformatics

<p align="justify">The primary goal of bioinformatics is to increase the understanding of biological processes. What sets it apart from other approaches, however, is its focus on developing and applying computationally intensive techniques to achieve this goal. Examples include: **pattern recognition, data mining, machine learning algorithms, and visualization**. Major research efforts in the field include sequence alignment, gene finding, genome assembly, drug design, drug discovery, protein structure alignment, protein structure prediction, prediction of gene expression and protein–protein interactions, genome-wide association studies, the modeling of evolution and cell division/mitosis.

<p align="justify">Bioinformatics now entails the creation and advancement of databases, algorithms, computational and statistical techniques, and theory to solve formal and practical problems arising from the management and analysis of biological data.

<p align="justify">Over the past few decades, rapid developments in genomic and other molecular research technologies and developments in information technologies have combined to produce a tremendous amount of information related to molecular biology. Bioinformatics is the name given to these mathematical and computing approaches used to glean understanding of biological processes.

<p align="justify">Common activities in bioinformatics include mapping and analyzing DNA and protein sequences, aligning DNA and protein sequences to compare them, and creating and viewing 3-D models of protein structures.

### What are the most common bioinformatics programs?

**Popular software for bioinformatics**

<p align="justify">Everyday bioinformatics is done with sequence search programs like [BLAST](), sequence analysis programs, like the `EMBOSS` and `Staden` packages, structure prediction programs like THREADER or PHD or molecular imaging/modelling programs like [RasMol](https://www.bioinformatics.org/wiki/RasMol) and WHAT [IF](https://www.bioinformatics.org/wiki/WHAT_IF).

More:

* [NetSurfP](http://www.cbs.dtu.dk/services/NetSurfP/) - Protein Surface Accessibility and Secondary Structure Predictions
* [NetTurnP](http://www.cbs.dtu.dk/services/NetTurnP/) - Prediction of Beta-turn regions in protein sequences
* [MODELLER](https://www.bioinformatics.org/wiki/MODELLER) - Used for homology or comparative modeling of protein three-dimensional structures
* [AutoDock](http://autodock.scripps.edu/) - Suite of Automated Docking Tools
* [Gromacs](http://www.gromacs.org/) - A molecular dynamics package primarily designed for biomolecular systems such as proteins and lipids
* [OrfPredictor](http://proteomics.ysu.edu/tools/OrfPredictor.html) - The OrfPredictor (ORF-Predictor) server is designed for ORF prediction and translation of a batch of EST or cDNA sequences

### What are the most common bioinformatics technologies?

<p align="justify">Currently, a lot of bioinformatics work is concerned with the technology of [databases](http://biodatabases.com/whitepaper01.html). These databases include both "public" repositories of gene data like [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) or the [Protein DataBank](https://www.rcsb.org/) (the PDB), and private databases, like those used by research groups involved in gene mapping projects or those held by biotech companies. Making such databases accessible via open standards is very important. Consumers of bioinformatics data use a range of computer platforms: from the more powerful and forbidding UNIX boxes favoured by the developers and curators to the far friendlier Macs often found populating the labs of computer-wary biologists.

<p align="justify">Databases of existing sequencing data can be used to identify homologues of new molecules that have been amplified and sequenced in the lab. The property of sharing a common ancestor, homology, can be a very powerful indicator in bioinformatics.

### How are data analyzed in bioinformatics?

<p align="justify">Bioinformatics tools can be used to obtain sequences of genes or proteins of interest, either from material obtained, labeled, prepared and examined in electric fields by individual researchers/groups or from repositories of sequences from previously investigated material.

<p align="justify">Both types of sequence can then be analyzed in many ways with bioinformatics tools. They can be `assembled`. Note that this is one of the occasions when the meaning of a biological term differs markedly from a computational one. Sequencing can only be performed for relatively short stretches of a biomolecule and finished sequences are therefore prepared by arranging overlapping "reads" of monomers. This is the bioinformatic sense of assembly.

<p align="justify">They can be `mapped`---that is, their sequences can be parsed to find sites where so-called "restriction enzymes" will cut them.

<p align="justify">They can be `compared`, usually by aligning corresponding segments and looking for matching and mismatching letters in their sequences. Genes or proteins that are sufficiently similar are likely to be related and are therefore said to be "homologous" to each other---the whole truth is rather more complicated than this. Such cousins are called "homologs".

<p align="justify">Bioinformatics is used in primer design. Primers are short sequences needed to make many copies of (amplify) a piece of DNA as used in PCR (the Polymerase Chain Reaction). Bioinformatics is used to attempt to predict the function of actual gene products.

<p align="justify">Information about the similarity, and, by implication, the relatedness of proteins is used to trace the "family trees" of different molecules through evolutionary time.

<p align="justify">[Molecular modelling](https://www.bioinformatics.org/wiki/Molecular_modelling) / [structural biology](https://www.bioinformatics.org/wiki/Structural_biology) is a growing field which can be considered part of bioinformatics. There are, for example, tools which allow you (often via the Net) to make pretty good predictions of the secondary structure of proteins arising from a given `amino acid sequence`, often based on known "solved" structures and other sequenced molecules acquired by structural biologists.

### Fields related to bioinformatics

* [Biophysics](https://www.bioinformatics.org/wiki/Biophysics)
* [Computational biology](https://www.bioinformatics.org/wiki/Computational_biology)
* [Medical informatics](https://www.bioinformatics.org/wiki/Medical_informatics)
* [Cheminformatics](https://www.bioinformatics.org/wiki/Cheminformatics)
* [Genomics](https://www.bioinformatics.org/wiki/Genomics)
* [Mathematical biology](https://www.bioinformatics.org/wiki/Mathematical_biology)
* [Proteomics](https://www.bioinformatics.org/wiki/Proteomics)
* [Pharmacogenomics](https://www.bioinformatics.org/wiki/Pharmacogenomics)
* [Pharmacogenetics](https://www.bioinformatics.org/wiki/Pharmacogenetics)

### Citation： 

[More details](https://www.bioinformatics.org/wiki/Bioinformatics_FAQ) could be found.


---