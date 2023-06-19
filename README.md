# Metabolomics 2023: Spectra processing, functional integration and covariate adjustment of global metabolomics data using MetaboAnalyst 5.0

![alt text](https://github.com/xia-lab/Metabolomics2019/blob/master/metabolomics2022_xialab.png)

For this workshop, we will be covering three workflows: 
* Auto-Optimized LC-MS spectra processing and peak annotation;
* Statistical Analysis of One-factor experimental design;
* Functional analysis from LC-MS peaks; 
* Exploratory statistical analysis with complex metadata. 

Details for each workflow are below. 

#### <ins>Before you start, please download our Protocols for MetaboAnalyst 5.0 [here](https://www.nature.com/articles/s41596-022-00710-w) as a reference.</ins>

<br/>

# Slides Summary

- [Introduction and Key Concepts](https://github.com/xia-lab/Metabolomics2019/blob/master/Metabolomics_Stats_Intro_2022.pdf).
- [Metabolomics Raw Spectra Data and Processing](https://github.com/xia-lab/Metabolomics_2023/blob/main/section_1_LCMS_processing.pdf).
- [Metabolomics Statistical Analysis of One-factor experimental design](https://github.com/xia-lab/Metabolomics_2023/blob/main/section_1_LCMS_processing.pdf).

- [Functional analysis from LC-MS peaks](https://github.com/xia-lab/Metabolomics2019/blob/master/2022_section2_function_multiomics.pdf).
- [Statistical Analysis with Complex Meta-Data](https://github.com/xia-lab/Metabolomics2019/blob/master/2022_section3_complex_metadata.pdf).

<br/>

## 1) LC-MS Spectra Processing and Annotation

The aim of this workflow is to use **LC-MS Spectra Processing module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze the raw spectra data from a real-world experiments. This section includes raw spectral data format conversion and centroiding. Then we will show a quick demon on how to use MetaboAnalyst for raw data processing in the auto-optimized mode. The data was obtained using untargeted metabolomics (Q-Exactive Plus Orbitrap MS in positive ion mode) of blood samples from 6 malaria semi-immune patients and 6 naive controls. 6 pooled QC samples are also included. In this section, students will learn how to run the auto-optimized raw spectra processing workflow.

(Optionally) To practice raw spectral data conversion and centroiding, users could download some raw thermo-fisher spectral data (*.raw) from this [link](https://drive.google.com/file/d/17HwDYqISi60bSUEAghQYSzikkuw89n-9/view?usp=sharing).

For this workflow, users could use the 2nd example directly from the module page or optionally download [here](https://www.dropbox.com/s/ift0zrkh0rx3v80/malaria_raw.zip?dl=0). **For the learning purpose, you are strongly encouraged to use the 1st example directly to run the whole process quickly.**

The tutorial of this module is available [here](https://www.xialab.ca/api/download/metaboanalyst/1_Raw_Spectral_Processing.pdf) for further reference. Watch this [video](https://youtu.be/NSwc7Ywvbpw) to see a live demo of raw spectra data processing with MetaboAnalyst.

<br/>

## 2) Statistical Analysis of One-factor experimental design

This part needs to be updated by Jessica. <- TODO!



<br/>

## 3) Functional Analysis and Integration 

The aim of this workflow is to introduce the pathway analysis of untargeted metabolomics data using the **Functional Analysis module**. The theory and processing steps of mummichog is described. Users can use the first examples directly from the module page for practicing. 
The tutorial of this module is available [here]([https://www.xialab.ca/api/download/metaboanalyst/2_Functional_Analysis.pdf]) for further reference. Watch this [video](https://youtu.be/NSwc7Ywvbpw) to see a live demo of functional analysis with MetaboAnalyst.

<br/>

## 4) Metabolomics Statistical Analysis with Complex Metadata

The aim of this workflow is to perform statistical analysis based on complex metadata. Covariate analysis will be used to deal with a metabolomics data, which is highly affected by multiple metadata factors. This study mainly focus on a peak intensity table from a trichloroethylene (TCE) exposure [study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5100622/) for covariate analysis. The data consists of untargeted metabolomics (a peak table) of 352 known metabolites and a metadata. In details, untargeted metabolomics (LC-MS peak intensity) data from plasma samples of 175 individuals to study trichloroethylene (TCE) exposure has been included. Nine metadata - 6 categorical and 3 numeric was organized for analysis.

For this workflow, users will first need to download the example data [here](https://github.com/xia-lab/Metabolomics2019/blob/master/Statistical_analysis_metadata.zip).

<br/>

## Additional Reference Documents

To understand more background knowledge on metabolomics data analysis further, you can follow these documents/protocols below. 

#### MetaboAnalyst & other omics tools
[Using MetaboAnalyst for Metabolomics Data Analysis](https://www.dropbox.com/s/7uxzeacpgx6zjux/Metabolomics_MetaboAnalyst_Intro_2022.pptx?dl=0)

#### Key statistical concepts & approaches
[General Concepts & Workflow in Omics Data Analysis](https://www.dropbox.com/s/stsp01glned47gg/Metabolomics_Stats_Intro_2022.pptx?dl=0)

#### Protocols of Other Modules in MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpbi.86)
