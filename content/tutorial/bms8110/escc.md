+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Functional analysis based on gene expression profiles suggested key signaling pathways in ESCC"

weight = 20
# Project summary to display on homepage.
summary = "Esophageal carcinoma arising from the esophagus—the food pipe that runs between the throat and the stomach."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tutorial/8110/escc1.png"

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
<img src="/img/tutorial/8110/escc1.png" width=300 alt="clinvar" align="center">

<span id="top"></span>

##  Esophageal carcinoma

<p align="justify"> Esophageal carcinoma arising from the esophagus—the food pipe that runs between the throat and the stomach.

### Characteristics:

* Common cancer: esophageal cancer was the eighth-most common cancer.
* Most common in China: half of all cancer cases occurring in China.
* Low survival rates: Five-year survival rates are around 13% to 18%.

### The two main sub-types of the esophageal carcinoma:

* Esophageal squamous-cell carcinoma (ESCC)
* Esophageal adenocarcinoma (EAC)

### Sample collection

* Microarray Data  
* 20 ESCC tumor tissues and a control set containing 20 normal tissues from GEO database (with the GEO accession number GSE38129)
* Diagnosed with ESCC in the Shanxi Cancer Hospital (Shanxi, China) and none of patients used local or systemic treatment.

### Quality control of samples

* Similarity among samples was measured by Pearson Correlation based on log2 “rma” signals  

<img src="/img/tutorial/8110/escc2.png" width=900 alt="clinvar" align="center">

* As shown in hierarchical clustering and PCA results. Gene expression profiles within tumor tissues are more similar then those between tumor and normal tissue.
* So, the quality of samples were sufficient for next analysis.

### Differential gene expression analysis

* Tumor tissues VS  Normal tissues
* Differential gene expression analysis was conducted by “limma” package in R. 
* Genes up- or down- regulated more than twofold with adjusted p-value less than 0.05 were considered as genes with significantly differential expression. 
* In total, there were 12,403 gene got quantified and 1,307 of them were identified showing significantly differential gene expression. 

<img src="/img/tutorial/8110/escc3.png" width=900 alt="clinvar" align="center">

### Functional analysis by HTSanalyzeR2

<img src="/img/tutorial/8110/escc4.png" width=900 alt="clinvar" align="center">

Based on the GSEA results and enrichment map, we found up-regulated genes were enriched in “human papillomavirus infection”.

### Proposing hypothesis

HPV infection is one cause of esophageal squamous cell carcinoma (ESCC) in China.

In fact, HPV infection has been known to cause more than one kind of squamous cell carcinomas, such as cervix and oropharynx. 

<img src="/img/tutorial/8110/escc5.png" width=900 alt="clinvar" align="center">

## In silico validations

### Sample collection

RNA sequencing data of 4 ESCC patient tumor tissues and 4 adjacent normal tissue samples (**GSE32424**)

These patients were from Linzhou Cancer Hospital (Henan, China) and also no prior therapy were used before operation.

### Quality check of sequencing

<img src="/img/tutorial/8110/escc6.png" width=900 alt="clinvar" align="center">

<img src="/img/tutorial/8110/escc7.png" width=900 alt="clinvar" align="center">

All samples showed available qualities of sequencing.


### Sequence alignment

<img src="/img/tutorial/8110/escc8.png" width=900 alt="clinvar" align="center">

<p align="justify">Overall, the lowest unique mapping rate is 45.48% and the highest unique mapping rate is 63.17%, which quality is available to following analyses.

### Quality check of samples

* Gene expression abundance (read counts) was quantified by STAR after alignment, and normalization was calculated by DESeq2 package in R.

<img src="/img/tutorial/8110/escc9.png" width=900 alt="clinvar" align="center">

* Hierarchical clustering and principal component analyses of totally eight samples showed, as expected, that the four ESCC samples were clustered together and four normal samples were clustered into another group.

### Differential gene expression analysis

* Because of higher throughput of RNA-Seq, there are 31,682 genes got identified and quantified. 
* 4,372 genes were regarded as significantly differential expression. 
* 982 (75.13%) of 1,307 significantly differential expression genes from the discovery set were also identified differential in this validation set.

<img src="/img/tutorial/8110/escc95.png" width=900 alt="clinvar" align="center">

### Functional analysis by HTSanalyzeR2

<img src="/img/tutorial/8110/escc10.png" width=900 alt="clinvar" align="center">

* Key biological function and pathway such as “human papillomavirus infection”, “keratinocyte differentiation”, “DNA replication” and “cell division” also enriched genes with same alterative expression pattern.
* These results showed the robustness of our results and the validity of our hypothesis.

## Experimental validations

### Identification of HPV presence

* There are different types of HPV such as HPV-16, -18 and – 58.
* Use real-time PCR to quantify HPV DNA.
* Use streptavidinperoxidase (SP) IHC staining to detect expression of different HPV types in tissue samples. 

### Etiological role of ESCC specific HPV in clinical application

* Use the p16/INK4A (p16) biomarker to predict HPV oncoprotein activity. 
* The relationship between overall survival and biomarker status need further investigation.

## Summary

* The analysis of ESCC gene expression profiles showed the gene differential expressions. Significantly up- or down- regulated gene patterns suggested potential molecular mechanism of ESCC. 
* The analysis of functional enrichment showed the key roles of HPV infection pathway and this result got validated by another datasets. 
* After reviewing researches of ESCC, we found it is still insufficient for clinical diagnose application of HPV, so further specific research are needed for this pathway.

<br>
**Case study** could be found in **the student work** below.

### BMS8110 2017 Semester B Student Work

LI Ying (54952422)


[**Download**](https://drive.google.com/file/d/17kYfQYNKRZ_NPGJ9UMNs2axvxzaMO9Gl/view?usp=sharing)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---