+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Computational Neuroinformatics"

weight = 30
# Project summary to display on homepage.
summary = "Including: Realistic Neuronal Network Modelling, Compartment Neuron Modelling, Model Files Conversion, Model Files Visualization, Model Building, Database."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/pheno/neuro.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["phenomics"]

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

<img src="/img/tools/pheno/neuro.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

<p align="justify">**Modelling in computational neuroscience** is becoming a crucial tool for understanding how experimentally observed properties of neural systems emerge from lower-level biophysical processes. In the same way that processing of information happens at multiple physical scales in the nervous system, software applications have been created which specialize in modelling different aspects of neurons and networks. [Source](https://doi.org/10.1007/978-1-4614-7320-6_93-1)

---

# Biological Steps

## <font color=#CD5555 face="黑体">Realistic Neuronal Network Modelling</font>

<p align="justify">Realistic modeling is a new advanced methodology for investigating brain functions. Realistic modeling is based on a detailed biophysical description of neurons and synapses, which can be integrated into microcircuits.

---

### The Virtual Brain

<p align="justify">Simulates the dynamics of large-scale brain networks with biologically realistic connectivity. The Virtual Brain uses tractographic data (DTI/DSI) to generate connectivity matrices and build cortical and subcortical brain networks. The connectivity matrix defines the connection strengths and time delays via signal transmission between all network nodes. Various neural mass models are available in the repertoire of The Virtual Brain and define the dynamics of a network node. Together, the neural mass models at the network nodes and the connectivity matrix define the Virtual Brain. The Virtual Brain simulates and generates the time courses of various forms of neural activity including Local Field Potentials (LFP) and firing rate, as well as brain imaging data such as EEG, MEG and BOLD activations as observed in fMRI.

[**Official Website**](https://thevirtualbrain.org/tvb/zwei)

**Publications**:

* (2015 Trends Cogn Sci) [The Rediscovery of Slowness: Exploring the Timing of Cognition.](https://www.ncbi.nlm.nih.gov/pubmed/26412099)

* (2015 Nat Rev Neurosci) [
Rethinking segregation and integration: contributions of whole-brain modelling.](https://www.ncbi.nlm.nih.gov/pubmed/26081790)

**Institutions(s)**:

Institut de Neurosciences des Systèmes, Aix Marseille Université, Marseille, France;

Department of Neurology, BrainModes Group, Charité University of Medicine, Berlin, Germany;

---

### Brian 

<p align="justify">Provides a simulator for spiking neural networks. Brian can be used to create a network of neurons and synapses connected with a network of astrocytes. This method permits user to focus mainly on the details of their models than on their implementation. Neuron models are defined by writing differential equations in standard mathematical notation, or facilitating scientific communication. This tool is useful for teaching computational neuroscience and for neuroscientific modelling at the systems level.

[**Official Website**](http://briansimulator.org/)

**Publications**:

* (2017 BioRxiv) [Modeling neuron-glia interactions with the Brian 2 simulator.](https://www.biorxiv.org/content/early/2017/10/05/198366)

**Institutions(s)**:

Sorbonne Universites, UPMC Univ Paris 06, INSERM, CNRS, Institut de la Vision, Paris, France

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Compartment Neuron modelling</font>

<p align="justify">The electrical properties of single neurons can be acurately modeled using multicompartmental modeling. Such models are biologically motivated and have a close correspondence with the underlying biophysical properties of neurons and their ion channels. These multicompartment models are also important as building blocks for detailed network models.

---

### NEURON 

<p align="justify">Provides a simulation environment for modeling individual neurons and networks of neurons. NEURON provides tools for conveniently building, managing, and using models in a way that is numerically sound and computationally efficient. It is particularly well-suited to problems that are closely linked to experimental data, especially those that involve cells with complex anatomical and biophysical properties. NEURON is designed to let the users deal directly with familiar neuroscience concepts. Consequently, they can think in terms of the biophysical properties of membrane and cytoplasm, the branched architecture of neurons, and the effects of synaptic communication between cells.

[**Official Website**](https://neuron.yale.edu/neuron/)

**Publications**:

* (2016 Comput Intell Neurosci) [Optimizing NEURON Simulation Environment Using Remote Memory Access with Recursive Doubling on Distributed Memory Systems.](https://www.ncbi.nlm.nih.gov/pubmed/27413363)

* (2009 Front Neuroinform) [NEURON and Python.](https://www.ncbi.nlm.nih.gov/pubmed/19198661)

**Institutions(s)**:

Computer Science, Yale University New Haven, CT, USA

---

### neuroConstruct 

<p align="justify">Facilitates the creation, visualization, and analysis of networks of multicompartmental neurons in 3D space. neuroConstruct provides a graphical user interface (GUI) which allows model generation and modification without programming. Models within neuroConstruct are based on new simulator-independent NeuroML standards, allowing automatic generation of code for NEURON or GENESIS simulators. neuroConstruct was tested by reproducing published models and its simulator independence verified by comparing the same model on two simulators. neuroConstruct can be used for teaching network function in health and disease. The 3D models generated will allow simulations of increased biological realism, enabling more direct comparisons with results from new experimental methods for measuring neural activity in 3D at high spatial and temporal resolution.

[**Official Website**](http://www.neuroconstruct.org/)

**Publications**:

* (2007 Neuron) [neuroConstruct: a tool for modeling networks of neurons in 3D space.](https://www.ncbi.nlm.nih.gov/pubmed/17442244)

**Institutions(s)**:

Department of Physiology, University College London, Gower Street, London, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# File Manipulation

## <font color=#CD5555 face="黑体">Model Files Conversion</font>

### SBML2LaTeX

<p align="justify">Facilitates the complicated and cumbersome model development process by providing a simple method to translate such models to human-readable reports. SBML2LaTeX is a Java-based stand-alone program to fill this gap. A convenient web service also allows users to directly convert SBML to various formats, including DVI, LATEX and PDF, and provides many settings for customization. It covers all constructs defined in the latest specification of SBML (Level 2 Version 4) and is able to typeset complex kinetic formulas.

[**Official Website**](http://www.cogsys.cs.uni-tuebingen.de/software/SBML2LaTeX/index.html)

**Publications**:

* (2009 Bioinformatics) [SBML2L(A)T(E)X: conversion of SBML files into human-readable reports.](https://www.ncbi.nlm.nih.gov/pubmed/19307240)

**Institutions(s)**:

Center for Bioinformatics Tübingen (ZBIT), University of Tübingen, Tübingen, Germany;

Beckman Institute BNMC, California Institute of Technology, Pasadena, CA, USA

---

### Sbmlharvester 

<p align="justify">Converts Systems Biology Markup Language (SBML) models into OWL. Sbmlharvester allows to check SBML model structure and complex by querying across biomedicals ontologies and models. The software couples levels of granularity, validates models and provides a way to establish a basic qualitative layer for expressing the semantics of biosimulation models.

[**Official Website**](https://code.google.com/archive/p/sbmlharvester/)

**Publications**:

* (2011 BMC Syst Biol) [Integrating systems biology models and biomedical ontologies.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3170340/)

**Institutions(s)**:

Department of Genetics, University of Cambridge, Downing Street, Cambridge, UK;

Department of Biology, Carleton University, Ottawa, ON, Canada

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Model Files Visualization</font>

### SBMLToolbox

<p align="justify">A toolbox that facilitates importing and exporting models represented in the Systems Biology Markup Language (SBML) in and out of the MATLAB environment and provides functionality that enables an experienced user of either SBML or MATLAB to combine the computing power of MATLAB with the portability and exchangeability of an SBML model. SBMLToolbox supports all levels and versions of SBML.

[**Official Website**](http://sbml.org/Downloads)

**Publications**:

* (2006 Bioinformatics) [SBMLToolbox: an SBML toolbox for MATLAB users.](https://www.ncbi.nlm.nih.gov/pubmed/16574696)

**Institutions(s)**:

Science and Technology Research Institute, University of Hertfordshire Hatfield, UK

---

### SBMLEditor

<p align="justify">Simplifies creation and edition of correct SBML files. SBMLEditor is an editor of SBML files allowing user to create and remove all the necessary bits and pieces of SBML in a controlled way. This tool can be useful for scientists who need to read an SBML model generated by another tool.

[**Official Website**](https://www.ebi.ac.uk/compneur-srv/SBMLeditor.html)

**Publications**:

* (2007 BMC Bioinformatics) [SBMLeditor: effective creation of models in the Systems Biology Markup language (SBML).](https://www.ncbi.nlm.nih.gov/pubmed/17341299)

**Institutions(s)**:

European Bioinformatics Institute, Wellcome Trust Genome Campus, Hinxton, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Model Building</font>

### NeuroManager

<p align="justify">Automates the workflow of simulation job submissions when using heterogeneous computational resources, simulators, and simulation tasks. NeuroManager is an object-oriented simulation management software engine for computational neuroscience. This method (i) provides flexibility to adapt a variety of neuroscience simulators, (ii) simplifies the use of heterogeneous computational resources, from desktops to super computer clusters, and (iii) improves tracking of simulation evolution.

[**Official Website**](https://github.com/SantamariaLab/NeuroManager)

**Publications**:

* (2017 Neuroinformatics) [Integrating the Allen Brain Institute Cell Types Database into Automated Neuroscience Workflow.](https://doi.org/10.1007/s12021-017-9337-x)

**Institutions(s)**:

Department of Biomedical Engineering, The University of Texas at San Antonio, San Antonio, TX, USA;

Department of Biology, The University of Texas at San Antonio, San Antonio, TX, USA

---

### PyNN

<p align="justify">Proposes a simulator-independent language for building neuronal network models. PyNN makes it possible to write a simulation script once, using the Python programming language, and run it without modification on any supported simulator (currently NEURON, NEST, PCSIM, Brian and the Heidelberg VLSI neuromorphic hardware). PyNN increases the productivity of neuronal network modelling by providing high-level abstraction, by promoting code sharing and reuse, and by providing a foundation for simulator-agnostic analysis, visualization and data-management tools. PyNN increases the reliability of modelling studies by making it much easier to check results on multiple simulators.

[**Official Website**](http://neuralensemble.org/PyNN/)

**Publications**:

* (2009 Front Neuroinform) [PyNN: A Common Interface for Neuronal Network Simulators.](https://www.ncbi.nlm.nih.gov/pubmed/19194529)

**Institutions(s)**:

Unité de Neurosciences Intégratives et Computationelles, CNRS Gif sur Yvette, France

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/phenomics-category)

[*Image Citation*](http://www.medicalimagingtalk.com/radiology-imaging/test-follow-medical-imaging-appropriateness-criteria/)

---