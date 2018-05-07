+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "DNA Structure"

weight = 20
# Project summary to display on homepage.
 summary = "Including: DNA structure analysis, DNA structure Database, Small-angle scattering."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/geno/dnastr.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["genomics"]

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

<img src="/img/tools/geno/dnastr.jpg"  width="400", height="600" alt="dnastr" align="center">

<span id="top"></span>

{{% toc %}}

# DNA Structure 

<p align="justify">DNA molecules exist in many different conformations, including A-DNA, B-DNA, or Z-DNA forms, which depend on the nucleotide sequence, hydratation level, presence of metal ions, etc. **Structure analysis** software tools help predict and model nucleic acid structure and conformation variations according to specific parameters.

## <font color=#CD5555 face="黑体">Shape prediction</font>

### do_x3dna

<p align="justify">Analyzes the structural fluctuations of DNA or RNA during molecular dynamics simulations. do_x3dna extends the capability of the 3DNA package to GROMACS MD trajectories and includes new methods to calculate the global-helical axis of DNA and bending fluctuations during simulations. The package also includes a Python module dnaMD to perform and visualize statistical analyses of complex data obtained from the trajectories.

[**Official Website**](https://github.com/rjdkmr/do_x3dna)

[**Documentation**](http://do-x3dna.readthedocs.io/en/latest/)

[**Github**](https://github.com/rjdkmr/do_x3dna/issues)

**Publications**

* (Kumar and Grubmüller, 2015) [do_x3dna: a tool to analyze structural fluctuations of dsDNA or dsRNA from molecular dynamics simulations](https://www.ncbi.nlm.nih.gov/pubmed/25838463).  Bioinformatics. 
* (Lu and Olson, 2003) [3DNA: a software package for the analysis, rebuilding and visualization of three-dimensional nucleic acid structures](https://www.ncbi.nlm.nih.gov/pubmed/12930962).  Nucleic Acids Res. 

**Institution(s)**

Department of Theoretical and Computational Biophysics, Max Planck Institute for Biophysical Chemistry, Göttingen, Germany

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

### 3DNA

<p align="justify">A comprehensive software package for the analysis, reconstruction and visualization of three-dimensional nucleic acid structures. **3DNA** can be applied to parallel and antiparallel double helices, single-stranded forms, multi-stranded helices and complex tertiary folding motifs found in both DNA and RNA structures. The rebuilding module of 3DNA can be used to generate sequence-dependent atomic structures of nucleic acids, with or without the sugar–phosphate backbone. These structures provide a useful starting point for molecular mechanics and molecular dynamics calculations.

[**Official Website**](http://x3dna.org/)

[**Documentation**]( http://x3dna.bio.columbia.edu/docs/dssr-manual.pdf)

[**Forum**](http://forum.x3dna.org/)

**Publications**:

* (Lu and Olson, 2003) [3DNA: a software package for the analysis, rebuilding and visualization of three-dimensional nucleic acid structures](https://www.ncbi.nlm.nih.gov/pubmed/12930962).  Nucleic Acids Res. 

**Institutions(s)**: Department of Chemistry and Chemical Biology, Wright-Rieman Laboratories, The State University of New Jersey, Piscataway, NJ, USA

### DINAMelt

<p align="justify">Provides a platform for allowing the simulation single-stranded nucleic acids melt in a solution. DINAMelt is a web application that calculates features such as ultraviolet (UV) absorbance, or concentrations of various dimer as a function of temperature. The interface allows users to set the temperature range, the nucleic acid type; the initial concentration as well as the salt conditions.

[**Official Website**](http://unafold.rna.albany.edu/?q=DINAMelt)

**Publications**:

* (Markham and Zuker, 2005) [DINAMelt web server for nucleic acid melting prediction](https://www.ncbi.nlm.nih.gov/pubmed/15980540).  Nucleic Acids Res. 

**Institutions(s)**: Department of Computer Science, Rensselaer Polytechnic Institute, Troy, NY, USA; Department of Mathematical Sciences, Rensselaer Polytechnic Institute, Troy, NY, USA

### DNAshape

<p align="justify">A method and web server for predicting **DNA structural features** in a high-throughput (HT) manner for massive sequence data. DNAshape provides the framework for the integration of DNA sequence and shape analyses in genome-wide studies. The HT methodology uses a sliding-window approach to mine DNA structural information obtained from Monte Carlo simulations. It requires only nucleotide sequence as input and instantly predicts multiple structural features of DNA (minor groove width, roll, propeller twist and helix twist).

[**Official Website**](http://rohslab.cmb.usc.edu/DNAshape/)

[**Documentation**](http://rohslab.cmb.usc.edu/DNAshape/serverManual.html)

**Publications**:

* (Zhou et al., 2013) [DNAshape: a method for the high-throughput prediction of DNA structural features on a genomic scale](https://www.ncbi.nlm.nih.gov/pubmed/23703209).  Nucleic Acids Res.  

**Institutions(s)**: Molecular and Computational Biology Program, Department of Biological Sciences; Department of Physics and Astronomy; Department of Chemistry; Department of Computer Science; Norris Comprehensive Cancer Center, University of Southern California, Los Angeles, CA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## <font color=#CD5555 face="黑体">R-loop forming sequence prediction</font>

### QmRLFS-finder

<p align="justify">**Predicts R-loop Forming Sequences** (RLFSs) in nucleic acid sequences based on experimentally supported structural models of RLFSs. This tool identifies and visualizes RLFS coordinates from any natural or artificial DNA or RNA input sequences and creates standards-compliant output files for further annotation and analysis. QmRLFS-finder demonstrates highly accurate predictions of the detected RLFSs, proposing new perspective to further discoveries in R-loop biology, biotechnology and molecular therapy.

[**Official Website**](http://rloop.bii.a-star.edu.sg/?pg=qmrlfs-finder)

**Publications**:

* (Jenjaroenpun et al., 2015) [QmRLFS-finder: a model, web server and stand-alone tool for prediction and analysis of R-loop forming sequences](https://www.ncbi.nlm.nih.gov/pubmed/25883153).  Nucleic Acids Res.

**Institutions(s)**: Department of Genome and Gene Expression Data Analysis, Bioinformatics Institute, Agency for Science, Technology and Research (A*STAR), Singapore

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## <font color=#CD5555 face="黑体">DNA Structure Database</font>

### R-loopDB | R-loop forming sequence databases

<p align="justify">A collection of computationally predicted **R-loop forming sequences** (RLFSs). R-loopDB is a comprehensive database of RLFSs in eight organisms, i.e. human, chimp, mouse, rat, chicken, frog, fruit fly and yeast, that offers benefits for the researchers who study R-loop related human diseases using these species. The combination of several other data resources, such as RLFS strand, GC skew value and experimental R-loop detection data, could provide more information for advanced analyses and predictions. R-loopDB allows searching of RLFSs in the genes and in the 2 kb upstream and downstream flanking sequences of any gene. R-loopDB exploits the Ensembl gene annotation system, providing users with chromosome coordinates, sequences, gene and genomic data of the 1,565,795 RLFSs distributed in 121,056 genic or proximal gene regions of the covered organisms.

[**Official Website**](http://rloop.bii.a-star.edu.sg/)

[**Documentation**]( http://rloop.bii.a-star.edu.sg/?pg2=help)

**Publications**:

* (Jenjaroenpun et al., 2017) [R-loopDB: a database for R-loop forming sequences (RLFS) and R-loops](https://www.ncbi.nlm.nih.gov/pubmed/27899586).  Nucleic Acids Res.  

**Institutions(s)**: Department of Genome and Gene Expression Data Analysis, Bioinformatics Institute, Agency for Science, Technology and Research (A*STAR), Singapore

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

## <font color=#CD5555 face="黑体">Small-angle Scattering</font>

### AXES

<p align="justify">Fits **small angle X-ray scattering** (SAXS) data to macromolecular structures and ensembles of structures. AXES is a web application using a Powell minimization of the penalty function against the adjustable parameters for both experimental and predicted data. The software allows the prediction of solution X-ray scattering data for a macromolecule in explicit aqueous solvent and calculation of the best fit between the experimental scattering data and a structural model.

[**Official Website**](https://spin.niddk.nih.gov/bax/nmrserver/saxs1/about.html)

[**Documentation**](https://spin.niddk.nih.gov/bax/nmrserver/saxs1/about.html)

**Publications**:

* (Grishaev et al., 2010) [Improved fitting of solution X-ray scattering data to macromolecular structures and structural ensembles by explicit water modeling](https://www.ncbi.nlm.nih.gov/pubmed/20958032). J Am Chem Soc.  

**Institution(s)**: Laboratory of Chemical Physics, National Institute of Diabetes and DigestiVe and Kidney Diseases, National Institutes of Health, Bethesda, MD, USA

### FoXS

<p align="justify">A rapid method for computing a SAXS profile of a given structure and for matching of the computed and experimental profiles. FoXS also provides an optimization of the hydration layer density as well as the excluded volume of the protein, to maximize the fit of the computed profile to the experimental profile. Additional optimization is achieved by adjusting the ‘background’ of the experimental profile for wider scattering angles.

[**Official Website**](https://modbase.compbio.ucsf.edu/foxs/index.html)

**Publications**:

* (Schneidman-Duhovny et al., 2013) [Accurate SAXS profile computation and its assessment by contrast variation experiments](https://www.ncbi.nlm.nih.gov/pubmed/23972848). Biophys J. 
* (Schneidman-Duhovny et al., 2010) [FoXS: a web server for rapid computation and fitting of SAXS profiles](https://www.ncbi.nlm.nih.gov/pubmed/20507903).  Nucleic Acids Res. 


**Institutions(s)**: Department of Bioengineering and Therapeutic Sciences, Department of Pharmaceutical Chemistry, and California Institute for Quantitative Biosciences (QB3), University of California at San Francisco, CA, USA

### AquaSAXS

<p align="justify">Allows structural biologists to compare their SAXS data to the theoretical one for a model given as a PDB or PQR file. **AquaSAXS** takes advantage of recently developed methods, such as AquaSol, that give the equilibrium solvent density map around macromolecules, to compute an accurate SAXS/WAXS profile of a given structure and to compare it to the experimental one. AquaSAXS provides a way for the user to check and/or tune the atomic types and the corresponding parameters that are used for computing the solute and the solvent-excluded-volume contribution to the SAXS profile.

[**Official Website**](http://chaconlab.org/modeling/dalai-ga)

**Publications**:

* Poitevin et al., 2011) [AquaSAXS: a web server for computation and fitting of SAXS profiles with non-uniformally hydrated atomic models](https://www.ncbi.nlm.nih.gov/pubmed/21665925).  Nucleic Acids Res. 


**Institutions(s)**: Institut Pasteur, Unit of Structural Dynamics of Macromolecules, CNRS, URA 2185, Paris, France

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMICTOOLS**](https://omictools.com/genomics2-category)

[*Image Citation*](https://visual.ly/community/infographic/health/dna-structure)

---