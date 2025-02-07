![course card](images/MS-course-card.png)

# X-Ray Crystallography & Molecular Energies
**Authors: Christopher Jurgenson, Joe Bently**

## Contents

+ [Introduction](#introduction)
+ [Overview](#overview)
+ [Software Requirements](#software-requirements)
+ [Funding](#funding)

## Introduction

This cloud-based learning module teaches x-ray crystallography basics using the Phenix software as well as molecular energy fundamentals. After going through this the user should be comfortable with the process of determining the protein structure. Additionally, the user should be comfortable with basic quantum chemistry concepts used to perform biochemistry modeling.

The course is structured in four submodules, allowing us to:
1. Gain a basic understanding of proteins and x-ray diffraction/crystallography
2. Solve protein structure using SAD/MAD phasing in Phenix
3. Solve protein structure using molecular replacement in Phenix
4. Carry out protein modeling using COOT


## Overview

The course content is organized in Jupyter Notebooks. The first three notebooks cover x-ray crystallography while the fourth discusses various molecular interactions.

The overall structure of the modules is explained below:

+ [**Submodule 0**](Submodule_0_Phenix.ipynb) Used to launch the Phenix GUI
+ [**Submodule 1**](Submodule_1_protein_crystallography_background.ipynb) Provides fundamentals of protein structure and x-ray crystallography. 
+ [**Submodule 2**](Submodule_2_solving_protein_structure.ipynb)  Solving protein structure using SAD/MAD phasing and Molecular replacement methods.
+ [**Submodule 3**](Submodule_3_protein_modeling_COOT.ipynb) Perform protein modeling using coot. 
+ [**Submodule 4**](Submodule_4_molecular_interactions.ipynb) Aims to introduce basics of molecular energies providing basics of schrodingers equation and quantum chemistry.
  
## Requirements
Users need a Phenix account, Amazon account, sufficient internet access, and a standard web browser (e.g., Chrome, Edge, Firefox; Chrome is recommended) to create a SageMaker Notebook for analysis.  It is recommended to execute the Jupyter Notebook using a Python kernel (version > 3.10) on a standard machine with a minimum configuration of 4 vCPUs, 16 GB RAM, and 10 GB of HDD.

The following are the Packages and versions used during development:

```
Python version 4.2.2 (2025-1-30)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Debian GNU/Linux 10 (buster)

Packages:
 pandas
 numpy 
 matplotlib
 scipy
 IPython
 ipywidgets
 ase

```

In addition to Python the Phenix software was used with the following specifications:

```
Phenix version 1.1.4 (2025-1-30)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Debian GNU/Linux 10 (buster)

```

## Funding

This work was fully supported by NIH NIGMS. Any opinions, findings, conclusions, or recommendations expressed in this material are those of the authors and do not necessarily reflect the views of the funding agencies.


