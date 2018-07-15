+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Metabolic Engineering"

weight = 40
# Project summary to display on homepage.
summary = "Including: Constraint based methods, Metabolic pathway prediction, Strain design, Thermodynamics, Network analysis, 13C-fluxomics."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/meta/engineer.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["metabolomics"]

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

<img src="/img/tools/meta/engineer.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

<p align="justify">Growing concerns over limited fossil resources and associated environmental problems are motivating the development of sustainable processes for the production of chemicals, fuels and materials from renewable resources. Metabolic engineering is a key enabling technology for transforming microorganisms into efficient cell factories for these compounds.

---

# Biological Steps

## <font color=#CD5555 face="黑体">Constraint based methods</font>

<p align="justify">Flux balance analysis (FBA) is a widely used computational method for characterizing and engineering intrinsic cellular metabolism. The increasing number of its successful applications and growing popularity are possibly attributable to the availability of specific software tools for FBA. Each tool has its unique features and limitations with respect to operational environment, user-interface and supported analysis algorithms.

---

### fastcore

<p align="justify">A generic algorithm for reconstructing context-specific metabolic network models from global genome-wide metabolic network models such as Recon X. fastcore takes as input a core set of reactions that are known to be active in the context of interest (e.g., cell or tissue), and it searches for a flux consistent subnetwork of the global network that contains all reactions from the core set and a minimal set of additional reactions.

[**Official Website**](http://wwwen.uni.lu/recherche/fstc/life_sciences_research_unit/research_areas/systems_biology/software)

**Publications**:

* (2014 PLoS Comput Biol) [Fast reconstruction of compact context-specific metabolic network models.](https://www.ncbi.nlm.nih.gov/pubmed/24453953)

**Institutions(s)**:

Luxembourg Centre for Systems Biomedicine, University of Luxembourg, Luxembourg City, Luxembourg; 

Life Sciences Research Unit, University of Luxembourg, Luxembourg City, Luxembourg

---

### COBRA Toolbox | COnstraints Based Reconstruction and Analysis

<p align="justify">Offers a framework for prediction of cellular behavior. COBRA Toolbox gathers numerous algorithms intending to be applied to any biochemical system with prior mechanistic information, including those with incomplete one. The application proposes more than 30 functions divided into five sections: (i) analysis, that includes features for coupling or deletion; (ii) data integration; (iii) design; (iv) reconstruction and (v) base that includes solvers and utilities.

[**Official Website**](https://opencobra.github.io/cobratoolbox/)

**Publications**:

* (2018 BioRxiv) [The Microbiome Modeling Toolbox: from microbial interactions to personalized microbial communities.](https://www.biorxiv.org/content/early/2018/05/10/318485)

* (2017 ArXiv) [Creation and analysis of biochemical constraint-based models: the COBRA Toolbox v3.0.](https://arxiv.org/abs/1710.04038v2)

**Institutions(s)**:

Luxembourg Centre for Systems Biomedicine, University of Luxembourg, Campus Belval, Esch-sur-Alzette, Luxembourg

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Metabolic pathway prediction</font>

<p align="justify">Construction of synthetic metabolic pathways promises sustainable production of diverse chemicals and materials. In order to design synthetic metabolic pathways of high value, computational methods are needed to expand present knowledge by mining comprehensive chemical and enzymatic information databases.

---

### EC-BLAST 

<p align="justify">Allows users to compare enzyme reactions. EC-BLAST comprises a set of algorithms to handle reactions automatically. The software allows rapid comparisons between reactions at bond change level, reaction center level and reaction structure similarity level.

[**Official Website**](https://www.ebi.ac.uk/thornton-srv/software/rbl/)

**Publications**:

* (2014 Nat Methods) [EC-BLAST: a tool to automatically search and compare enzyme reactions.](https://www.ncbi.nlm.nih.gov/pubmed/24412978)

**Institutions(s)**:

European Molecular Biology Laboratory - European Bioinformatics Institute (EMBL-EBI), Wellcome Trust Genome Campus, Hinxton, Cambridge, UK ;

European Molecular Biology Laboratory - European Bioinformatics Institute (EMBL-EBI), Wellcome Trust Genome Campus, Hinxton, Cambridge, UK

---

### RetroPath

<p align="justify">Allows retrosynthetic design of metabolic pathways. RetroPath is a webserver that integrates several techniques. RetroPath workflow is a versatile reaction network tool, built to be modular enough to answer most metabolic engineering needs. The software was developed to answer the need for a tool to predict reaction networks.

[**Official Website**](http://www.jfaulon.com/category/retropath/)

**Publications**:

* (2017 BioRxiv) [RetroPath2.0: A retrosynthesis workflow for metabolic engineers.](https://www.biorxiv.org/content/early/2017/06/29/141721)

* (2014 Biotechnol J) [Validation of RetroPath, a computer-aided design tool for metabolic pathway engineering.](https://www.ncbi.nlm.nih.gov/pubmed/25224453)

**Institutions(s)**:

CNRS-UMR8030 / Laboratoire iSSB, Université Paris-Saclay, Evry, France; CEA, DRF, IG, Genoscope, Evry, France

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Strain design</font>

Computational strain design protocols aim at the system-wide identification of intervention strategies for the enhanced production of biochemicals in microorganisms. Existing approaches relying solely on stoichiometry and rudimentary constraint-based regulation overlook the effects of metabolite concentrations and substrate-level enzyme regulation while identifying metabolic interventions. 

---

### Biopathway Predictor

<p align="justify">A computational tool implemented in Genomatica's SimPheny platform for enumerating and evaluating networks of enzyme-catalyzed reactions, with the goal of identifying novel pathways for producing a chemical of interest. Reactions in a BioPathway network are generated by a defined set of reaction rules that operate repeatedly on a specified starting material and its derivatives.

[**Official Website**](https://www.genomatica.com/)

**Publications**:

* (2011 Nat Chem Biol) [Metabolic engineering of Escherichia coli for direct production of 1,4-butanediol.](https://www.ncbi.nlm.nih.gov/pubmed/21602812)

**Institutions(s)**:

Genomatica, Inc, San Diego, CA, USA

---

### cRegMCSs | constrained regulatory MCSs

<p align="justify">Generalizes the minimal cut sets (MCS)-based framework to constrained regulatory MCSs. cRegMCSs has been integrated as a new functionality in the CellNetAnalyzer package, a MATLAB toolbox for biological network analysis. In comparison to constrained MCSs (cMCSs) involving only reaction deletions, it can lead to (i) a lower number of required modifications and (ii) an increased number of possible intervention strategies. The approach was applied to (i) to a small illustrative network and (ii) to a genome-scale metabolic model of E.coli.

[**Official Website**](http://www2.mpi-magdeburg.mpg.de/projects/cna/etcdownloads.html)

**Publications**:

* (2015 Bioinformatics) [Genome-scale strain designs based on regulatory minimal cut sets.](https://www.ncbi.nlm.nih.gov/pubmed/25913205)

**Institutions(s)**:

Department of Chemical Engineering and Applied Chemistry, University of Toronto, Toronto, ON, Canada; 

Institute of Biomaterials and Biomedical Engineering, Toronto, ON, Canada

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Thermodynamics</font>

<p align="justify">The laws of thermodynamics describe a direct, quantitative relationship between metabolite concentrations and reaction directionality. Despite great efforts, thermodynamic data suffer from limited coverage, scattered accessibility and non-standard annotations.

---

### SSTMap | Solvation Structure and Thermodynamic Mapping

<p align="justify">Maps out measures of water structure and thermodynamics on solute surfaces. SSTMap is a computational tool that combines thermodynamic analysis with structural analysis, which can aid in understanding and evaluating the displacement of active-site water molecules. The software provides access to individual functions, such as identification of hydration site clusters, calculation of voxel occupancies, energy, entropy, and hydrogen bonding calculations.

[**Official Website**](https://github.com/KurtzmanLab/SSTMap)

**Publications**:

* (2017 J Chem Theory Comput) [Solvation Structure and Thermodynamic Mapping (SSTMap): An open-source, flexible package for the analysis of water in molecular dynamics trajectories.](https://www.ncbi.nlm.nih.gov/pubmed/29161510)

**Institutions(s)**:

Department of Physics, City College of New York, The City University of New York, New York, NY, USA; 

Department of Chemistry, Lehman College, The City University of New York, NY, USA

---

### von Bertalanffy

<p align="justify">An algorithmic pipeline for quantitative assignment of reaction directionality in multi-compartmental genome scale models based on an application of the second law of thermodynamics to each reaction. Given experimental or computationally estimated standard metabolite species Gibbs energy and metabolite concentrations, the algorithms bounds reaction Gibbs energy, which is transformed to in vivo pH, temperature, ionic strength and electrical potential. This cross-platform MATLAB extension to the COnstraint-Based Reconstruction and Analysis (COBRA) toolbox is computationally efficient, extensively documented and open source.

[**Official Website**](https://opencobra.github.io/)

**Publications**:

* (2011 Bioinformatics) [von Bertalanffy 1.0: a COBRA toolbox extension to thermodynamically constrain metabolic models.](https://www.ncbi.nlm.nih.gov/pubmed/21115436)

**Institutions(s)**:

Science Institute, University of Iceland, Reykjavik, Iceland

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# 13C-fluxomics

<p align="justify">13C-fluxomics is a new area that involves experimentally quantifying the rates of metabolic reactions within the central carbon metabolism through 13C metabolic fluxomics. This method enables the resolution of paralleled and reversible reactions

---

## COBRA Toolbox | COnstraints Based Reconstruction and Analysis

<p align="justify">Offers a framework for prediction of cellular behavior. COBRA Toolbox gathers numerous algorithms intending to be applied to any biochemical system with prior mechanistic information, including those with incomplete one. The application proposes more than 30 functions divided into five sections: (i) analysis, that includes features for coupling or deletion; (ii) data integration; (iii) design; (iv) reconstruction and (v) base that includes solvers and utilities.

[**Official Website**](https://opencobra.github.io/cobratoolbox/stable/)

**Publications**:

* (2018 BioRxiv) [The Microbiome Modeling Toolbox: from microbial interactions to personalized microbial communities.](https://www.biorxiv.org/content/early/2018/05/10/318485)

* (2017 ArXiv) [Creation and analysis of biochemical constraint-based models: the COBRA Toolbox v3.0.](https://arxiv.org/abs/1710.04038v2)

**Institutions(s)**:

Luxembourg Centre for Systems Biomedicine, University of Luxembourg, Campus Belval, Esch-sur-Alzette, Luxembourg; 

Division of Analytical Biosciences, Leiden Academic Centre for Drug Research, Faculty of Science, University of Leiden, Leiden, The Netherlands

---

## C13 | 13C-fluxomics : Metabolomics

<p align="justify">A tool for quantification of in vivo metabolic fluxes, from carbon labelling experiments. The underlying approach is metabolic flux analysis based on stationary carbon isotope labelling experiments, using fractional enrichment data.

[**Official Website**](http://biomet-toolbox.org/index.php?page=downtools-c13)

**Publications**:

* (2014 Nucleic Acids Res) [BioMet Toolbox 2.0: genome-wide analysis of metabolism and omics data.](https://www.ncbi.nlm.nih.gov/pubmed/24792167)

**Institutions(s)**:

Department of Chemical and Biological Engineering, Chalmers University of Technology, Göteborg, Sweden

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/metabolomics-category)

[*Image Citation*](https://www.sciencedirect.com/science/article/pii/S0958166915001056)

---