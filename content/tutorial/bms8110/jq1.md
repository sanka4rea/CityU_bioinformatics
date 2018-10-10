+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Genome-wide analysis of gene expression profiles for prioritization of dysregulated genes and pathways associated with the JQ1 treated lymphoblastic leukemia"

weight = 30
# Project summary to display on homepage.
summary = "JQ1 is a thienotriazolodiazepine and a prevailing inhibitor of the BET group of bromodomain proteins which incorporate BRD2, BRD3, BRD4, and the testis-particular protein BRDT in vertebrates."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tutorial/8110/jq1.png"

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

### Student Project done by:

Abhimanyu Thakur (54163550)

The slides can be downloaded [**here**](https://drive.google.com/file/d/1tB_3FNcdmKiP2wDXtuWdrRhTgYMJJxu1/view?usp=sharing)

## Acute Lymphoblastic Leukemia

* Neoplastic disease which results from a mutation in a single lymphoid progenitor cell at one of several discrete stages of development
* B Cell or T Cell
* Most common childhood acute leukemia, ~80%
* Incidence in adults ~20%
* Bimodal distribution of occurrence:
* Peak at age 2-5 & Second augmented incidence after age 50

### Pathogenesis

**Acquired Genetic Change in Chromosome**

* Change in number, i.e., ploidy
* Change in structure
* Translocations (most common)
* Inversions
* Deletions
* Point mutations
* Amplifications
* Changes in cell differentiation, proliferation, and survival

### Significance of JQ1 treatment

* JQ1 is a thienotriazolodiazepine and a prevailing inhibitor of the BET group of bromodomain proteins which incorporate BRD2, BRD3, BRD4, and the testis-particular protein BRDT in vertebrates. 

* BET inhibitors fundamentally like JQ1 are being tried in clinical trials for an assortment of malignancies including NUT midline carcinoma.

**Why cell death occurs post JQ1 treatment in Acute Lymphoblastic Leukemia?**

### Dataset

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE79253 

<img src="/img/tutorial/8110/jq2.png" width=900 alt="clinvar" align="center">

### Quality Control 

**Check of RNA-seq data (DMSO treatment Replicate 1)**

<img src="/img/tutorial/8110/jq3.png" width=900 alt="clinvar" align="center">

### Differential gene expression analysis and prioritization of top significantly up- or down-regulated genes 

<img src="/img/tutorial/8110/jq4.png" width=900 alt="clinvar" align="center">

### Proposed hypothesis

<img src="/img/tutorial/8110/jq1.png" width=900 alt="clinvar" align="center">

<p align="justify">After JQ1 treatment, PP2R1B has been upregulated. It suggests that cell division and cell growth will be stopped. In addition, KLC4 and HSPA6 have been downregulated, which suggest that it will enhance intracellular stress, because of the hindrance to intracellular trafficking as well as mitochondrial transport. Moreover, HSPA6 corrects the protein misfolding and causes proteasomal degradation of unwanted proteins. Therefore, their scarcity will cause the development of unwanted stress, and reactive oxygen species (ROS). Consequently, their overall cumulative effect will result into cell death.

## Plan for Biological Experiments

Genes from RNA-seq data and their functions based on literature search:

### PPP2R1B- upregulated

**PPP2R1B- upregulated** - Protein phosphatase 2- Negative regulation of cell growth and cell division.

**Experimental plan:**

* Overexpress using lentivirus overexpression vectors and transfect into cell line MOLT4 cells and test in other cell line too. Whichever you like.
* Check for following by western blot or immunohistochemistry- Caspase-3 apoptosis, cell division markers (you might have to check) and cell cycle arrest markers.

### KLC-4- downregulated

**KLC-4- downregulated**- It facilitates the intracellular cargo loading onto motor protein defective. Improper transport of materials and mitochondria within the cell. Also might cause cell death.

### 88HSPA6-Downregulated88

**88HSPA6-Downregulated88**- It removes misfolded proteins from cell cytoplasm and reduces stress from the cell. Decrease in Hsp70 might lead to cell death due to high stress in the cells because of inclusion bodies accumulation inside the cells.

**Experimental plan:**

* Knockdown those two gene using siRNA one by one in different cell lines. Cancerous cell lines.
* Check for – following by western blot or immunohistochemistry- cytoskeleton assembly proteins (may look for phalloidin-growth cone collapse), may also look for actin polymerization kit , may also check for mitochondria movement within the cells using mitotracker, can also look for overall energy inside the cell using glucose or lactose. 
* Check for proteasome degradation machinery E3 ligase enzyme amount, Caspase3, Reactive oxygen species (ROS dyes are available- do immunohistochemistry) 

**Phenotype experimental plan:**

* Cell viability test by MTT cell proliferation assay, BrdU cell proliferation assay.


<br>


[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---