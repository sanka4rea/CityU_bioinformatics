+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Sox4 ChIP-Seq data analysis"

weight = 50
# Project summary to display on homepage.
summary = "This tutorial includes CEAS analysis, BETA-minus analysis, GSEA."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tutorial/8110/sox1.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["bms8110_p1"]

# Optional external URL for project (replaces project detail page).
#external_link = "https://cityu-bioinformatics.netlify.com/tools/seq_new/sequence alignment/"


# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

#*[citation:](http://www.sequence-alignment.com/)*

+++
---

<span id="top"></span>

### Overview of ChIP-Seq analysis
 
<p align="justify">For ChIP-Seq, single-end (50bp) FASTQ reads were mapped to mouse genome mm10 (GRCm38, Dec/2011). Peaks 2,207 narrow peak regions and 2207 summits.

<img src="/img/tutorial/8110/sox1.png" width=900 alt="clinvar" align="center">

### Motif discovery and Distribution of Sox4 binding sites by CEAS analysis

<img src="/img/tutorial/8110/sox2.png" width=900 alt="clinvar" align="center">

### Sox4 Target gene’s associated peaks prediction by BETA-minus analysis

<p align="justify">1940 lines were identified using BETA-minus analysis in Galaxy/Cristrome. Among these 1940 lines and 1004 of them are located within promoter region (1000 bp upstream of TSS). Within these 1004 lines, 634 gene symbols were identified using RStudio. 

<img src="/img/tutorial/8110/sox3.png" width=900 alt="clinvar" align="center">

### Gene set overrepresentation analysis

643 genes , Hypergeometric test was used to perform the Gene set overrepresentation analysis.

<p align="justify">Molecular functions of the 634 genes are clustered into ‘protein binding’, RNA binding’, ‘nucleotide binding’, ‘cadherin binding’, ‘ATP binding’ and ‘kinase activity’. KEGG pathway : classified into ‘spliceosome’, ‘hepatocellular carcinoma’, ‘ribosome’, ‘pancreatic cancer’, ‘RNA transport’, ‘cell cycle’, ‘Hippo signalling pathway’, ‘MAPK signalling pathway’, ‘Wnt signalling pathway’ and so on.

<p align="justify">Biological processes of the genes set are mainly clustered in to ‘transcription, DNA-templated’, ‘regulation of transcription, DNA-templated’, ‘covalent chromatin modification’, ‘RNA splicing’, ‘mRNA processing’ and ‘cell cycle’ and so on.

<img src="/img/tutorial/8110/sox4.png" width=900 alt="clinvar" align="center">

### KEGG Mapper-Search Pathway analysis

12 Genes related the regulation of Hippo pathway were mapped to the pathway using KEGG Mapper online tool.

<img src="/img/tutorial/8110/sox5.png" width=900 alt="clinvar" align="center">

### Hypothesis and biological experiment plan

Step 1. Establish SOX4 overexpression and SOX4 knock-out cell lines 

Step 2. Detect whether Hippo pathway is downregulated by SOX4 overexpression and downregulated by SOX4 knockout. 
Step 3. Dissect the mechanism of SOX4’s downregulation on Hippo signalling pathway 

Step 4. Determine whether SOX4 can regulate maintenance of TNBC cancer stem cells. 

Step 5. further to investigate whether the effect of step 4 is through the SOX4-induced downregulation of Hippo signalling pathway 

<img src="/img/tutorial/8110/sox6.png" width=900 alt="clinvar" align="center">

<br>
**Case study** could be found in **the student work** below.

### BMS8110 2017 Semester B Student Work

HU, Jianyang (54863843)


[**Download**](https://drive.google.com/file/d/1dn4iuvO7vvrCouqqt6DZ9TceVGqagqIu/view?usp=sharing)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---