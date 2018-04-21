+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Sequence Alignment"

weight = 10
# Project summary to display on homepage.
summary = "Amino acid **sequence alignment and analysis** is central to most biochemical and molecular biology applications. "

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/seq.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["sequence_related"]

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
<img src="/img/tools/sequence-alignment.jpg" alt="blast" align="center">
*[citation:](http://www.sequence-alignment.com/)*
<span id="top"></span>

{{% toc %}}

<p align="justify">In bioinformatics, a sequence alignment is a way of arranging the sequences of DNA, RNA, or protein to identify regions of similarity that may be a consequence of functional, structural, or evolutionary relationships between the sequences. Aligned sequences of nucleotide or amino acid residues are typically represented as rows within a matrix. Gaps are inserted between the residues so that identical or similar characters are aligned in successive columns.

## Sequence Alignment
### Blast

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

*citation:* [Sequence Similarity Searching](https://www.ebi.ac.uk/Tools/sss/)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

### FASTA/SSEARCH/PSI-Search/GGSEARCH/GLSEARCH

<p align="justify">**FASTA (pronounced FAST-AYE)** is a suite of programs for searching nucleotide or protein databases with a query sequence. FASTA itself performs a local heuristic search of a protein or nucleotide database for a query of the same type. FASTX and FASTY translate a nucleotide query for searching a protein database. TFASTX and TFASTY translate a nucleotide database to be searched with a protein query. Optimal searches are available with the programs SSEARCH (local), GGSEARCH (global) and GLSEARCH (global query against local database).

* <p align="justify">**SSEARCH** is an optimal (as opposed to heuristics-based) local alignment search tool using the Smith-Waterman algorithm. Optimal searches guarantee you find the best alignment score for your given parameters.
* <p align="justify">**PSI-Search** combines the sensitivity of the Smith-Waterman search algorithm (SSEARCH) with the PSI-BLAST profile construction strategy to find distantly related protein sequences.
* <p align="justify">**GGSEARCH** performs optimal global-global alignment searches using the Needleman-Wunsch algorithm.
* <p align="justify">**GLSEARCH** performs an optimal sequence search using alignments that are global in the query but local in the database sequence. This can be useful when you want to match all of a short query sequence to part of a larger database sequence.

This tools can be used in the following contexts:

* [Protein Databases](https://www.ebi.ac.uk/Tools/sss/fasta/index.html)
* [Nucleotide Databases](https://www.ebi.ac.uk/Tools/sss/fasta/nucleotide.html)
* [Genomes Databases](https://www.ebi.ac.uk/Tools/sss/fasta/genomes.html)
* [Proteomes Databases](https://www.ebi.ac.uk/Tools/sss/fasta/proteomes.html)
* [Whole Genome Shotgun Databases](https://www.ebi.ac.uk/Tools/sss/fasta/wgs.html)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## Multiple Sequence Alignment

### Clustal Omega

<p align="justify">**Clustal Omega** is the latest addition to the Clustal family. It offers a significant increase in scalability over previous versions, allowing hundreds of thousands of sequences to be aligned in only a few hours. It will also make use of multiple processors, where present. In addition, the quality of alignments is superior to previous versions, as measured by a range of popular benchmarks.

Clustal Omega is currently a **command line-only** tool.

<p align="justify">A full description of the **algorithms** used by Clustal Omega is available in the Molecular Systems Biology paper [Fast, scalable generation of high-quality protein multiple sequence alignments using Clustal Omega](http://msb.embopress.org/content/7/1/539).

Clustal Omega can be run local or online at the following websites:

* [EBI web server](https://www.ebi.ac.uk/Tools/msa/clustalo/)
* [Mobyle@Pasteur](https://galaxy.pasteur.fr/forms::clustalO-multialign)

### Clustal W / Clustal X

<p align="justify">Clustal 2 comes in two flavors: the command-line version Clustal W and the graphical version Clustal X. Precompiled executables for Linux, Mac OS X and Windows (incl. XP and Vista) of the most recent version (currently 2.1) along with the source code are [available for download](http://www.clustal.org/download/current/) here. You can also browse for [older versions](http://www.clustal.org/download/) (Clustal W 1.81, Clustal V etc). 

<img src="/img/tools/clustal.png" width= 800 height= 500 alt="blast" align="center">

[More detials and official website](http://www.clustal.org/)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---