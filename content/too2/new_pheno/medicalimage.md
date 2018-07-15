+++
# Date this page was created.
date = "2018-04-11"

# Project title.
title = "Medical Imaging"

weight = 20
# Project summary to display on homepage.
summary = "Including: Medical Imaging Analysis, Magnetic Resonance Imaging, Computerized Tomography Scan Imaging, Nuclear Medicine Imaging, Ultrasonic Imaging."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/pheno/medical.jpg"

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

<img src="/img/tools/pheno/medical.jpg"  width="500" height="400" alt="anno" align="center">

<span id="top"></span>

{{% toc %}}

# Medical Phrnotype Analysis

<p align="justify">**Macroscopic phenotype analysis** deals with all tools usefull for describing, identifying or classifying phenotypes at macroscopic scale. Macroscopic sample can, for example, be plants or mammalians (human, mouse..) imaged by all kinds of macroscopic devices (from medical imaging to basic digital camera).

## <font color=#CD5555 face="黑体">Clinical Risk Prediction</font>

<p align="justify">A risk prediction model aims to predict the probability or risk of a condition or event among individuals, or occasionally groups, based on a combination of known or measured characteristics. Risk prediction tools are the means by which risk prediction models, scores or algorithms are implemented in clinical practice. Numerous risk tools are now available, which predict either current or future risk of a cancer diagnosis. In theory, these tools have the potential to improve patient outcomes through enhancing the consistency and quality of clinical decision-making, facilitating equitable and cost-effective distribution of finite resources and encouraging behaviour change.

---

### RICORDO | Researching Interoperability using Core Reference Datasets

<p align="justify">Gathers functions for real-time reasoning over very large ontologies to express complex ontology concepts. RICORDO is designed for biomedical resources, and related ontologies, relevant to a number of communities including the physiology modeling, the pharmacology modeling, and the medical education community. It permits to find and annotate resources with both terms from reference ontologies and composites of those terms.

[**Official Website**](http://www.ricordo.eu/relevant-resources)

**Publications**:

* (2012 Bioinformatics) [An infrastructure for ontology-based information systems in biomedicine: RICORDO case study.](https://www.ncbi.nlm.nih.gov/pubmed/22130590)

**Institutions(s)**:

European Bioinformatics Institute, Wellcome Trust Genome Campus, Cambridge, UK;

Department of Genetics, University of Cambridge, Cambridge, UK
---

### comoRbidity 

<p align="justify">Provides an analysis of disease comorbidities from both the clinical and molecular perspectives. comoRbidity is an R package that leverages from clinical data obtained from electronic health records (EHR) databases or health registries (the clinical comorbidity analysis), and from genotype-phenotype information of the diseases under study (the molecular comorbidity analysis), or provided by the user.

[**Official Website**](https://bitbucket.org/ibi_group/comorbidity)

**Publications**:

* (2018 Bioinformatics) [comoRbidity: An R package for the systematic analysis of disease comorbidities.](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/bty315/4979545)

**Institutions(s)**:

Research Programme on Biomedical Informatics (GRIB), Hospital del Mar Medical Research Institute (IMIM), Department of Experimental and Health Sciences (DCEXS), Universitat Pompeu Fabra (UPF), Barcelona, Spain

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Clinical Simulation</font>

### LMG | Lumbar Model Generator

<p align="justify">Builds a population of anatomically representative models in a semi-automatic manner. LMG assists users to assess the effects of spinal implants on distinct anatomical features of the spine. It provides surfaces and solid regions that are meshed allowing for direct use in finite-element (FE) models. The models constructed by the tool include the five vertebral bodies (L1–L5) and the four intervertebral discs (IVDs) interposed between them.

[**Official Website**](https://github.com/CELavecchia/LMG/tree/v1.1)

**Publications**:

* (2018 J R Soc Interface) [Lumbar model generator: a tool for the automated generation of a parametric scalable model of the lumbar spine.](https://www.ncbi.nlm.nih.gov/pubmed/29298959)

**Institutions(s)**:

Department of Mechanical Engineering, University of Birmingham, Birmingham, UK;

Department of Biomechanical Engineering, University of Melbourne, Melbourne, VIC, Australia

---

### PIPER Child HBM

<p align="justify">Allows users to perform a series of child accident reconstruction. PIPER Child HBM is an approach combining two methods: (1) the PIPER tool and (2) the PIPER scalable HBM. It enables users to realize computer simulations with human body models (HBMs) of different ages and in different positions. It assists users in the prediction of the injury severity and location for the reconstructions.

[**Official Website**](https://gitlab.inria.fr/piper/child/tree/master/PIPER_ChildModel_6YO)

**Publications**:

* (2017 PLoS One) [Performances of the PIPER scalable child human body model in accident reconstruction.](https://www.ncbi.nlm.nih.gov/pubmed/29135997)

**Institutions(s)**:

Division of Neuronic Engineering, School of Technology and Health, KTH Royal Institute of Technology, Stockholm, Sweden

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Magnetic Resonance Imaging (MRI)

<p align="justify">Magnetic resonance imaging (MRI) has become firmly established as an essential imaging tool. Two characteristics of MRI--its ability to image soft tissue and its avoidance of harmful ionizing radiation--more than compensate for the costs, complexity, safety issues, and patient discomfort associated with it. Today, MRI is the modality of choice for a number of neurological and musculoskeletal indications and is being used for more applications than ever before. [Source](https://www.ncbi.nlm.nih.gov/pubmed/15945465)

<p align="justify">Magnetic resonance imaging (MRI) is a powerful, non-invasive diagnostic medical imaging technique widely used to acquire detailed information about anatomy and function of different organs in the body, in both health and disease. It utilizes electromagnetic fields of three different frequency bands: static magnetic field (SMF), time-varying gradient magnetic fields (GMF) in the kHz range and pulsed radiofrequency fields (RF) in the MHz range. [Source](https://www.ncbi.nlm.nih.gov/pubmed/26041266)

Image preprocessing, processing, Structural analysis could be found in [Bioimaging]{{< ref "too2/new_pheno/bioimaging.md" >}}

---

## <font color=#CD5555 face="黑体">DICOM files management</font>

<p align="justify">The digital imaging and communications in medicine (DICOM) protocol is the leading standard for image data management in healthcare. Imaging biomarkers and image-based surrogate endpoints in clinical trials and medical registries require DICOM viewer software with advanced functionality for visualization and interfaces for integration.

---

### DicomBrowser | DICOM files management : Magnetic resonance imaging

<p align="justify">Allows users to view and modify digital imaging and communications in medicine (DICOM) metadata. DicomBrowser is designed to simplify the transition between clinically oriented DICOM tools and the specialized workflows of research imaging. Metadata changes can be specified manually in the DicomBrowser GUI, in a spreadsheet generated by DicomSummarize, or via scripts written in the DicomEdit language.

[**Official Website**](http://nrg.wustl.edu/software/dicom-browser/)

**Publications**:

* (2012 J Digit Imaging) [DicomBrowser: software for viewing and modifying DICOM metadata.](https://www.ncbi.nlm.nih.gov/pubmed/22349992)

**Institutions(s)**:

Mallinckrodt Institute of Radiology, Washington University School of Medicine, Saint Louis, MO, USA

---

### MIPAV | Medical Image Processing Analysis and Visualization

<p align="justify">Enables quantitative analysis and visualization of medical images of numerous modalities such as PET (positron emission tomography), MRI (magnetic resonance imaging), CT (computerized tomography), or microscopy. Using MIPAV's standard user-interface and analysis tools, researchers at remote sites (via the internet) can easily share research data and analyses, thereby enhancing their ability to research, diagnose, monitor, and treat medical disorders.

[**Official Website**](https://mipav.cit.nih.gov/)

**Publications**:

* [Medical Image Processing, Analysis and Visualization in clinical research.](https://doi.org/10.1109/CBMS.2001.941749)

**Institutions(s)**:

CBEL, Center for Information Technology, National Institutes of Health, Bethesda, MD, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Computerized Tomography Scan Imaging (CT)

<p align="justify">Utilization of computed tomography (CT) has increased dramatically over the past several decades. The total number of CT examinations performed annually in the United States has risen from approximately 3 million in 1980 to nearly 70 million in 2007. Integrating CT into routine care has improved patient health care dramatically, and CT is widely considered among the most important advances in medicine. [Source](https://www.ncbi.nlm.nih.gov/pubmed/20008690)

Image preprocessing, processing, Structural analysis could be found in [Bioimaging]{{< ref "too2/new_pheno/bioimaging.md" >}}

## <font color=#CD5555 face="黑体">Phantom Imaging</font>

### CTSim | Computed Tomography Simulator

<p align="justify">Simulates the process of transmitting X-rays through phantom objects. CTSim is a method that reconstructs the original phantom image from the projections using a variety of algorithms. Additionally, this package has a wide array of image analysis and image processing functions. CTSim uses geometrical objects to describe the object being scanned. A phantom is composed of one or more phantom elements: simple geometric shapes, specifically, rectangles, triangles, ellipses, sectors and segments.

[**Official Website**](http://www.ctsim.org/)

**Documentation**:

http://files.kpe.io/ctsim/ctsim-manual-latest.pdf

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Image Format Management</font>

### NiBabel

<p align="justify">Furnishes a neuroimaging viewer. NiBabel provides an access to a wide range of imaging formats. Besides, it contains functionality for writing annotation and morphometry files. The software allows users to access to header information and image data.

[**Official Website**](http://nipy.org/nibabel/)

**Issues**:

https://github.com/nipy/nibabel/issues

**Maintainer(s)**:

Michael Hanke <michael.hanke@gmail.com>

person_outline Matthew Brett <matthew.brett@gmail.com>

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Nuclear Medicine Imaging

<p align="justify">Nuclear medicine is a multidisciplinary field that develops and uses instrumentation and tracers (radiopharmaceuticals) to study physiological processes and noninvasively diagnose, stage, and treat diseases. Particularly, it offers a unique means to study cancer biology in vivo and to optimize cancer therapy for individual patients. [Source](https://www.ncbi.nlm.nih.gov/pubmed/22446937)

## <font color=#CD5555 face="黑体">3D Image Reconstruction</font>

<p align="justify">Computer technologies can produce 3D representations of interesting human tissue and organs that have been serial-sectioned, dyed or stained, imaged, and segmented for 3D visualization. 3D reconstruction also has great potential in the fields of tissue engineering and 3D printing.

---

### STIR | Software for Tomographic Image Reconstruction

<p align="justify">Provides a Platform-independent Object-Oriented framework for all data manipulations in tomographic imaging. STIR can be used to study existing and/or new reconstruction algorithms for a wide variety of cylindrical scanners. It enables the research community to study the performance of several algorithms on Single Photon Emission Computed Tomography (SPECT) data, and potentially implement new algorithms by expanding the existing framework. The tool offers the prospect to compare different Positron Emission Tomography (PET) scanners using identical correction and reconstruction software.

[**Official Website**](https://sourceforge.net/projects/stir/)

**Publications**:

* (2013 Med Phys) [Integration of advanced 3D SPECT modeling into the open-source STIR framework.](https://www.ncbi.nlm.nih.gov/pubmed/24007178)

**Institutions(s)**:

Department of Physiological Sciences I - Biophysics and Bioengineering Unit, University of Barcelona, Barcelona, Spain;

Grupo de Imagen Biomédica de la Universidad de Barcelona (GIB-UB), Biomedical Research Networking Center in Bioengineering, Biomaterials and Nanomedicine (CIBER-BBN), Barcelona, Spain

---

### NiftyPET

<p align="justify">Reconstructs images and can conduct analysis facilitating high-throughput parallel processing. NiftyPET determines the distributions of regional and voxel value uncertainties through the use of list-mode bootstrapping. It supports dynamic list-mode (LM) processing and reconstruction. This tool permits to ascertain the impact of limited counting statistics in positron-emission tomography (PET) on all the different stages of image reconstruction and analysis.

[**Official Website**](https://cmiclab.cs.ucl.ac.uk/pmarkiew/NiftyPET)

**Publications**:

* (2017 Neuroinformatics) [NiftyPET: a High-throughput Software Platform for High Quantitative Accuracy and Precision PET Imaging and Analysis.](https://www.ncbi.nlm.nih.gov/pubmed/29280050)

**Institutions(s)**:

Translational Imaging Group, CMIC, Department of Medical Physics, Biomedical Engineering, University College London, London, UK;

Department for Applied Mathematics and Theoretical Physics, University of Cambridge, Cambridge, UK

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Kinetic Analysis</font>

### QModeling | Kinetic analysis : Nuclear medicine imaging

<p align="justify">Assists users for the kinetic analysis of PET pharmacokinetic analysis and the generation of parametric images. QModeling is a multiplatform software developed as a toolbox of statistical parametric mapping (SPM) that assists users in neuroimaging studies. It works locally, without the need of uploading sensitive data to online servers. It also facilitates the inclusion of kinetic modeling into flexible neuroimaging pipelines.

[**Official Website**](http://www.uimcimes.es/contenidos/general.action?idsupersection=3&idselectedsection=10&selectedsection=QModeling&idparentmenu=7&idpage=7&idcomission=0&typetable=opcionescursos)

**Publications**:

* (2018 Neuroinformatics) [QModeling: a Multiplatform, Easy-to-Use and Open-Source Toolbox for PET Kinetic Analysis.](https://doi.org/10.1007/s12021-018-9384-y)

**Institutions(s)**:

Molecular Imaging Unit, Centro de Investigaciones Médico-Sanitarias, Fundación General de la Universidad de Málaga, Málaga, Spain

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# Find more tools: [**OMICTOOLS**](https://omictools.com/phenomics-category)

[*Image Citation*](http://www.medicalimagingtalk.com/radiology-imaging/test-follow-medical-imaging-appropriateness-criteria/)

---