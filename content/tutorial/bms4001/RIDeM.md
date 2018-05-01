+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Repository for Informed Decision Making (RIDeM)"

weight = 100
# Project summary to display on homepage.
summary = "**Repository for Informed Decision Making** (RIDeM). The long-term goal of the Repository for Informed Decision Making is to provide access to key facts needed to support clinical decision making."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tutorial/4001/ridem3.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["bms4001_p2"]

# Optional external URL for project (replaces project detail page).
#external_link = "https://cityu-bioinformatics.netlify.com/tools/seq_new/sequence alignment/"


# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

#*[citation:](http://www.sequence-alignment.com/)*

+++
---
<img src="/img/tutorial/4001/ridem3.jpg" alt="clinvar" align="center">

<span id="top"></span>

<p align="justify">[**RIDeM**](https://ceb.nlm.nih.gov/ridem/) is one of the LHNCBC Clinical Decision Support projects. The long-term goal of the Repository for Informed Decision Making is to provide access to key facts needed to support clinical decision making. The facts are extracted from biomedical literature and clinical text sources. The development of the Repository is guided by the Evidence Based Medicine (EBM) principles for finding and appraising information. 

* One of the LHNCBC Clinical Decision Support projects
* Provide access to key factors to support clinical decision making. <br>Biomedical literature. <br>Clinical text sources.
* Current prototype implementation:<br>iMEDLINE. <br>CQA1.0.<br>PubMed Central Open Access Subset  <br>InfoBot. <br>MetaMap. <br>HDiscovery. <br> UMLS.


<img src="/img/tutorial/4001/ridem2.png" alt="clinvar" align="center">
[**Official Website**](https://ceb.nlm.nih.gov/ridem/)

### Prototype Description

1. <p align="justify">A **literature database**, for example, MEDLINE, is searched for all articles pertaining to the disease. This is done automatically using tools developed at National Library Medicine (NLM), provided someone, for example a medical librarian, starts the search. Search tools currently available at NLM are E-Utilities, developed at [NCBI](http://eutils.ncbi.nlm.nih.gov/entrez/query/static/eutils_help.html) and Essie, an experimental probabilistic search engine developed at the Lister Hill National Center for Biomedical Communications, NLM.

2. <p align="justify">**Diseases and treatment options** are identified in each article automatically using the MetaMap and SemRep tools developed at NLM.

3. Outcome Extraction tool:<br>	Automatically verifies that an article is about the disease.<br><br> Automatically identifies strength of evidence in the article (as Grade I, II, III, or no evidence), based on the type of the study, for example, clinical trial, reputation of the journal, and the number of participants in the study.<br><br> Automatically estimates the likelihood of a sentence being an outcome statement in an article. Any number of top ranking sentences, for example 2-3, could be extracted as a summary.

4. The extracted outcomes could be stored in a database (with or without human curation.)

### Operational System Development

<p align="justify">The currently **working prototype** is limited in its processing capabilities. Due to complex natural language processing that takes place in MetaMap and SemRep, the prototype processes on the order of a 100 new abstracts for approximately 15 queries per day. To make it serve larger numbers of questions and provide outcomes for a Patient Outcomes Database the following tasks have to be accomplished:

* Use the results of MetaMap and SemRep processing of MEDLINE abstracts that is conducted at NLM for purposes unrelated to outcomes. Using the results of this processing for outcome extraction will require additional programmer effort and storage capacity. 
* Develop the outcomes database
* Develop tools to insert extracted outcome statements into the database
*	Develop a user interface for database curation, if needed
*	Update the database regularly with respect to new treatment options and new evidence for existing treatment options.

<img src="/img/tutorial/4001/ridem.jpg" alt="clinvar" align="center">

<br>
**How to use** could be found [here](https://www.ncbi.nlm.nih.gov/clinvar/docs/help/) or **the student work** below.

### BMS4001 2018 Semester B Student Work

* Lau Ching Man              
* Au Ming Wai, Astrid               
* Kwan Yuk Tip                       
* Chan Man Chung          

[**Download**](https://drive.google.com/open?id=1OMw8wx2Hs5ZHVpLGEI32eZE8VbqHjjY9)

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---