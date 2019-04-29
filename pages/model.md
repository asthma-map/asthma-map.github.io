---
layout: default
title: Model
permalink: /model
---

# Modelling asthma mechanisms

### Mast cell in asthma: large-scale mechanistic model

The project employs the AsthmaMap Process Description layer to build a mechanistic model of mast cell dynamics aiming at improving our understanding of the disease and offering a tool for predicting the efficacy of medications. The objective is to develop a predictive model which integrates qualitative knowledge about the pathway topology and quantitative experimental data available in the literature.  

The SBML model is derived from the [Mast Cell Module 0.0.40](/pd/) of the AsthmaMap Process Description and additionaly refined using information from literature. For the simulation and parameterizations of the SBML model we use the MATLAB toolboxes AMICI (Fröhlich et al., 2017, [PMID 28114351](https://www.ncbi.nlm.nih.gov/pubmed/28114351)) and PESTO (Stapor et al., 2018, [PMID 29069312](https://www.ncbi.nlm.nih.gov/pubmed/29069312)). Quantitative experimental data are extracted from several published studies (e.g., Parravicini et al., 2002, [PMID 12089510](https://www.ncbi.nlm.nih.gov/pubmed/12089510)).  

The model has more than 300 species and 400 parameters, and includes kinetic laws for all reactions. We established a pipeline for building a data repository which is used for the model parameterization. The current model already captures several aspects of the mast cell response to allergens.  

### Availability

The mast cell model was produced in CellDesigner and is available in the default CellDesigner's format, pure SBML and also provided for browsing in the MINERVA platform.  

[CellDesigner](/downloads/models/ASTHMA_V40_M07NoRules.xml) &ensp; 
[SBML]() &ensp;  
[MINERVA](https://asthma.uni.lu/minerva/index.xhtml?id=ASTHMA_V40_M07NoRules) &ensp; 

### Contributors

Thomas Ligon, Irina Balaur, Alexander Mazein, Charles Auffray, Jan Hasenauer



