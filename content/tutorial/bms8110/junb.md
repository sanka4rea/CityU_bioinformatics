+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "JUNB is involved in TGFβ induced cancer invasion"

weight = 10
# Project summary to display on homepage.
summary = "In breast cancer, SMAD has rare mutation and weak capability of DNA binding, usually interact with other co-factors or transcription factors to bind to DNA."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tutorial/8110/junb1.jpg"

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

HUANG Hao (54893350)

The slides can be downloaded [**here**](https://drive.google.com/file/d/1RoJ9JOslU_CKqCjUbgLyu86vCYJy9Gys/view?usp=sharing)

<p align="justify"> In breast cancer, SMAD has rare mutation and weak capability of DNA binding, usually interact with other co-factors or transcription factors to bind to DNA.

## Background

* <p align="justify">In breast cancer, SMAD has rare mutation and weak capability of DNA binding, usually interact with other co-factors or transcription factors to bind to DNA. 
* <p align="justify">Transforming growth factor-β (TGFβ) plays dual role during tumor progression——tumor suppressor or tumor promoter.
* <p align="justify">Identification of key signaling molecules or pathway related the switch TGFβ/SMAD signaling from tumor suppression to tumor promotion is important for the development of therapies for TGFβ associated signaling pathway. 

## High-throughput data

<img src="/img/tutorial/8110/junb2.jpg" width= 800 alt="clinvar" align="center">

<p align="justify">ChIP-seq was applied after 1.5 h TGFβ3 treatment, 16 h treatment and Input data for breast cancer cell line MCF10A MII

## Bioinformatics

<img src="/img/tutorial/8110/junb1.jpg" width= 900 alt="clinvar" align="center">

**Quanlity Control**

* TGFβ3 treatment 1.5 hours raw data
* Filters reads based on quality scores

<img src="/img/tutorial/8110/junb3.png" width= 900 alt="clinvar" align="center">


### SMAD is redirected to different binding sites after prolonged TGFβ treatment 

<img src="/img/tutorial/8110/junb4.png" width= 900 alt="clinvar" align="center">

<p align="justify">Activator protein (AP)1 motif as the most significant consensus sequences in 1.5 hours and 16 hours TGFβ treatment.

### SMAD binding sites annotation

<img src="/img/tutorial/8110/junb5.png" width= 900 alt="clinvar" align="center">

### Hypergeometric test with SMAD target genes

<img src="/img/tutorial/8110/junb6.png" width= 900 alt="clinvar" align="center">

More genes were activated after 16 hours TGFβ treatment and related to cancer invasion.   


## Testable hypotheses

* JUNB is a well-known major AP1 component, and it was bound by SMAD2/3 after 16 hours TGFβ treatment. 
* According to the ChIP-seq analysis, JUNB may play important roles in TGFβ-induced cell invasion. 
* Cell adhesion was significantly enriched after 16 hours TGFβ treatment than 1.5 hours treatment, it may be JUNB-dependent and involved in TGFβ-induced invasion.

<img src="/img/tutorial/8110/junb7.png" width= 900 alt="clinvar" align="center">

## In silico validations

<img src="/img/tutorial/8110/junb8.png" width= 900 alt="clinvar" align="center">

<p align="center">16 hours treatment

<img src="/img/tutorial/8110/junb9.png" width= 900 alt="clinvar" align="center">

**AP1 motif was most significant (5.9e-303) than samd3 motif (2.2e-029).**

<img src="/img/tutorial/8110/junb10.png" width= 900 alt="clinvar" align="center">

**Genes were enriched in function categories related to cancer invasion.**

### Experimental validations

1. **Western blots**

  (1) no TGFβ treatment (–)
  
  (2) TGFβ treatment for 1.5 hours and 16 hours


2. **Collagen invasion assays**

  (1)TGFβ type I kinase receptor (TGFβRI) inhibitor SB505124 
  
  (2)cell adhesion inhibitor KF38789


3. **RNA-seq for breast cell line**

   (1) before treatment
   
   (2) 1.5 hours TGFβ treatment
   
   (3) 16 hours treatment 

<br>


[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---