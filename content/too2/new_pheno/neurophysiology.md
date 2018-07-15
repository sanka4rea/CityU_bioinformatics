+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Neorophysiology"

weight = 40
# Project summary to display on homepage.
summary = "Including: Neurophysiology Analysis, Clinical Eletrophysiology, Patch-clamp."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/pheno/physiology.jpg"

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

<img src="/img/tools/pheno/physiology.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}


# Neurophysiology Analysis

<p align="justify">The techniques used in experimental neurophysiology have grown in complexity with the development of new technology. In particular, neuroscientists often combine traditional electrophysiological recordings with multiple types of imaging, photostimulation, and behavioral interactions. These new techniques allow the collection of data with greater resolution, precision, and throughput than ever before. At the same time, they pose new challenges in their technical complexity. Increasingly, experimenters rely on computer automation to orchestrate these experiments and analyze the resulting data. Thus, software is a key component in integrating new technologies into experimental neurophysiology.

---

## PyNWB

<p align="justify">Offers a platform for optimizing the handling of data stored in Neurodata Without Borders (NWB) format. PyNWB is a software providing an API allowing users to read and create NWB formatted HDF5 files. The application was developed in support to the NWB project with the aim of spreading a standardized data format for cellular-based neurophysiology information.

[**Official Website**](https://github.com/NeurodataWithoutBorders/pynwb)

**Publications**:

* (2015 Neuron) [Neurodata Without Borders: Creating a Common Data Format for Neurophysiology.](https://www.ncbi.nlm.nih.gov/pubmed/26590340)

**Institutions(s)**:

Redwood Center for Theoretical Neuroscience & Helen Wills Neuroscience Institute, University of California, Berkeley, CA, USA; 

Allen Institute for Brain Science, Seattle, WA, USA

---

## VERTEX | Virtual Electrode Recording Tool for EXtracellular potentials

<p align="justify">Aims to simulate extracellular potential recordings in spiking neural network (SNN) models, and Local field potentials (LFPs) in large neuronal populations. VERTEX computes extracellular potentials in a model given the position of the neurons relative to the virtual electrodes. It calculates extracellular potentials by summing the membrane currents of each compartment, weighted by distance from the electrode tips.

[**Official Website**](http://vertexsimulator.org/)

**Publications**:

* (2015 Brain Struct Funct) [Virtual Electrode Recording Tool for EXtracellular potentials (VERTEX): comparing multi-electrode recordings from simulated and biological mammalian cortical tissue.](https://www.ncbi.nlm.nih.gov/pubmed/24863422)

**Institutions(s)**:

School of Computing Science, Newcastle University, Claremont Tower, Newcastle, UK;

Institute of Ageing and Health, Newcastle University, Newcastle, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Clinical Eletrophysiology

<p align="justify">**Electrophysiology**, the 'gold standard' for investigating neuronal signalling, is being challenged by a new generation of optical probes. Together with new forms of microscopy, these probes allow us to measure and control neuronal signals with spatial resolution and genetic specificity that already greatly surpass those of electrophysiology. We predict that the photon will progressively replace the electron for probing neuronal function, particularly for targeted stimulation and silencing of neuronal populations. Although electrophysiological characterization of channels, cells and neural circuits will remain necessary, new combinations of electrophysiology and imaging should lead to transformational discoveries in neuroscience. [Source](https://www.ncbi.nlm.nih.gov/pubmed/19829373)

Image preprocessing, processing, simulation could be found in [Bioimaging]({{< ref "too2/new_pheno/bioimaging.md" >}})

## <font color=#CD5555 face="黑体">Spike Sorting</font>

<p align="justify">the development of spike sorting algorithms has always been a key issue in the analysis of electrophysiological recordings. Ever since the beginning of extracellular recordings, several efforts have been made to develop such techniques . In general, the number of simultaneously recorded neurons has grown exponentially since the 1950s, doubling every 7 years, and currently allowing electrical observation of hundreds of neurons at sub-millisecond timescales

---

### NEV2lkit

<p align="justify">A preprocessor for the analysis of intra- or extracellular neuronal recordings. NEV2lkit’s main objective is to supply a friendly user interface that links the experimental data to a basic set of routines for analysis, visualization and classification of spikes in a consistent framework. It performs fast unit sorting in single or multiple experiments and allows the extraction of spikes from over large time intervals in continuously recorded data streams.

[**Official Website**](https://sourceforge.net/projects/nev2lkit/)

**Publications**:

* (2014 Int J Neural Syst) [NEV2lkit: a new open source tool for handling neuronal event files from multi-electrode recordings.](https://www.ncbi.nlm.nih.gov/pubmed/24694167)

**Institutions(s)**:

Institute of Bioengineering, Universidad Miguel Hernández, Alicante, Spain; CIBER BBN, Instituto de Salud Carlos III, Madrid, Spain

---

### Spyke Viewer

<p align="justify">Analyzes, browses and analyzes data from electrophysiology experiments or neural simulations. Spyke Viewer is built on an object model for electrophysiology data: the Neo library. This software furnishes a central graphic user interface from which independently developed analysis can be executed. It provides a flexible plugin architecture that permits creation of new plugins to allow extensibility.

[**Official Website**](http://spyke-viewer.readthedocs.io/en/latest/)

**Publications**:

* (2013 Front Neuroinform) [Spyke Viewer: a flexible and extensible platform for electrophysiological data analysis.](https://www.ncbi.nlm.nih.gov/pubmed/24273510)

**Institutions(s)**:

Department of Software Engineering and Theoretical Computer Science, Neural Information Processing Group, TU Berlin, Berlin, Germany;

Bernstein Center for Computational Neuroscience, Berlin, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Image Data Analysis</font>


### MNE-Python

<p align="justify">Assists in visualizing results of processing steps and final outputs. MNE-Python is a scripting-based package with many visualization capabilities. It covers multiple methods of data preprocessing, source localization, statistical analysis, and estimation of functional connectivity between distributed brain regions. It offers some unique capabilities, in a coherent package facilitating the combination of standard and advanced techniques in a single environment.

[**Official Website**](http://martinos.org/mne/stable/index.html)

**Publications**:

* (2017 BioRxiv) [MEG/EEG group study with MNE: recommendations, quality assessments and best practices.](https://www.biorxiv.org/content/early/2017/12/28/240044)

**Institutions(s)**:

Télécom ParisTech, Université Paris-Saclay, France; 

University of Washington, Institute for Learning and Brain Sciences, Seattle WA, USA

---

### EEGLAB 

<p align="justify">Processes continuous and event-related EEG (electro-encephalography) and MEG (magneto-encephalography). EEGLAB also processes other electrophysiological data incorporating independent component analysis (ICA), time/frequency analysis, artifact rejection, event-related statistics, and several useful modes of visualization of the averaged and single-trial data. EEGLAB provides an interactive graphic user interface (GUI) allowing users to flexibly and interactively process their high-density EEG and other dynamic brain data using ICA and/or time/frequency analysis, as well as standard averaging methods.

[**Official Website**](https://sccn.ucsd.edu/eeglab/index.php)

**Publications**:

* (2004 J Neurosci Methods) [EEGLAB: an open source toolbox for analysis of single-trial EEG dynamics including independent component analysis.](https://www.ncbi.nlm.nih.gov/pubmed/15102499)

**Institutions(s)**:

Swartz Center for Computational Neuroscience, Institute for Neural Computation, University of California San Diego, La Jolla, CA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Data Management and Annotation</font>

<p align="justify">Find and compare the best bioinformatics software tools for navigating, sharing and collaboratively annotating image data sets of biological specimens obtained by electrophysiological devices. Tools are ranked by the biomedical research community.

---

### NDManager  

<p align="justify">Uses as a simple graphical application designed to help neurophysiologists manage their experimental recording parameters (e.g., number of channels and sampling rate of the acquisition system) and process their data (data filtering, spike extraction, PCA, etc.). NDManager is a part of the Neurosuite, a package designed to help neurophysiologists process and view recorded data in an efficient and user-friendly manner.

[**Official Website**](http://neurosuite.sourceforge.net/)

**Publications**:

* (2006 J Neurosci Methods) [Klusters, NeuroScope, NDManager: a free software suite for neurophysiological data processing and visualization.](https://www.ncbi.nlm.nih.gov/pubmed/16580733)

**Institutions(s)**:

Center for Molecular and Behavioral Neuroscience, Rutgers, The State University of New Jersey, Newark, NJ, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Patch-clamp

<p align="justify">The patch clamp technique permits high-resolution recording of the ionic currents flowing through a cell's plasma membrane. In different configurations, this technique has allowed experimenters to record and manipulate the currents that flow either through single ion channels or those that flow across the whole plasma membrane.

---

## RTXI | Real-Time eXperiment Interface

<p align="justify">Achieves hard real-time data acquisition and closed-loop control in biological experiments. RTXI is based on a Real-Time Operating System (RTOS) that modifies the operating system's native kernel architecture. It allows users to move developed and tested modules, algorithms, and entire closed-loop protocols from one computer to another without significant overhead. The tool is compatible with a wide range of experimentation hardware.

[**Official Website**](http://rtxi.org/)

**Publications**:

* (2017 PLoS Comput Biol) [Hard real-time closed-loop electrophysiology with the Real-Time eXperiment Interface (RTXI).](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005430)

**Institutions(s)**:

Bioengineering Graduate Program, Georgia Institute of Technology, Atlanta, GA, USA;

Department of Biomedical Engineering, Georgia Institute of Technology and Emory University, Atlanta, GA, USA

---

## NeuroMatic 

<p align="justify">Offers an assortment of tools allowing users to perform data analysis, data acquisition and simulation of electrophysiological data. NeuroMatic provides an extensible toolkit that have to be run through the Igor platform software. It provides a wide range of functionalities including triggered stimulation, spike detection, simulations of stochastic synaptic transmission as well as voltage and current clamp.

[**Official Website**](http://www.neuromatic.thinkrandom.com/)

**Publications**:

* (2018 Front Neuroinform) [NeuroMatic: An Integrated Open-Source Software Toolkit for Acquisition, Analysis and Simulation of Electrophysiological Data.](https://www.ncbi.nlm.nih.gov/pubmed/29670519)

**Institutions(s)**:

Department of Neuroscience, Physiology and Pharmacology, University College London, London, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/phenomics-category)

[*Image Citation*](https://blogs.aalto.fi/brainweb/2016/10/09/first-excursion-department-of-clinical-neurophysiology-helsinki-university-central-hospital-meilahti/)


---