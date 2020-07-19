---
layout: default
title: Tools
permalink: /tools/
---

# Tools

## MINERVA

The [MINERVA](https://minerva.pages.uni.lu/) platform (Gawron et al., 2016, [PMID 28725475](https://www.ncbi.nlm.nih.gov/pubmed/28725475)) allows interactive visualisation and exploration functionalities based on Google Maps API, and provides a suite of advanced tools for data exploration. The platform allows the upload and the visualisation of custom experimental datasets, including multi-omic entries and user-defined color-coding of elements and interactions. A dedicated query system allows displaying targets for drugs of interest on hosted maps. The commenting system enables users to directly annotate the explored content and pin their remarks to specific elements or interactions. Finally, a set of export options allows downloading the parts, or the entirety of the hosted maps as models in SBGN-compliant format, tab-delimited network format, or images.  

## CellDesigner

[CellDesigner](http://www.celldesigner.org) is a diagram editor developed by the Systems Biology Institute for drawing process diagrams (Kitano et al., 2005, [PMID 19668183](https://www.ncbi.nlm.nih.gov/pubmed/?term=19668183)) using the graphical notation proposed by Prof. Hiroaki Kitano, and stored in [SBML](http://sbml.org/) format. CellDesigner supports the development of mathematical models and is integrated with SBML ODE Solver, SBML Simulation Core and Copasi. The entities on a diagram can be annotated and linked to various databases.  
        
CellDesigner supports a system of symbols based on a draft of the Systems Biology Graphical Notation (SBGN) Process Description language Level 1 proposed in 2008 (more information can be found [here](http://www.celldesigner.org/features.html)). [SBGN Viewer](http://www.celldesigner.org/help/CDH_View_08.html) tool in CellDesigner can be used to see a diagram in the current version of [SBGN](http://sbgn.org/) (Le Novère et al., 2009, [PMID 19668183](https://www.ncbi.nlm.nih.gov/pubmed/?term=19668183)).  

## yEd Graph Editor
        
[yEd Graph Editor](https://www.yworks.com/products/yed) from yWorks GmbH is a freely available graph editor written in Java that runs on Windows, macOS, and Linux/Unix. It is a powerful desktop application that can be used to quickly and effectively generate high-quality diagrams.  
        
yEd uses the XML-based GraphML format to load/save diagrams and additionally supports import from Excel spreadsheets (.xls, .xlsx) and arbitrary XML (via XSLT). Creating diagrams manually is easy and fun with the intuitive user interface, and a large collection of powerful layout algorithms allows to automatically arrange nodes and edges. Diagrams can be exported to bitmap and vector formats: PNG, JPG, and SVG, PDF.  
        
Since [version 3.17.1](https://www.yworks.com/products/yed/download#ReleaseNotes) yEd provides a palette section for Systems Biology Graphical Notation.   

## ySBGN

[ySBGN](https://github.com/sbgn/ySBGN) is a standalone Java application, a bidirectional converter between GraphML format of the [yEd Graph Editor](https://www.yworks.com/yed) and the SBGN Process Description or Activity Flow languages. 

Now diagrams can be created in the intuitive general-purpose [yEd Graph Editor](https://www.yworks.com/yed) using the SBGN Palette available since [version 3.17.1](https://www.yworks.com/products/yed/download#ReleaseNotes), and, thanks to the converter, the outcome could be offered in the standard Systems Biology format. The ySBGN tool supports keeping annotation information in the SBGN-ML format.

For reporting issues please use [ySBGN GitHub Issues](https://github.com/sbgn/ySBGN/issues) page.
        
## Newt Editor

<a href="http://newteditor.org/" target="_blank">Newt Editor</a> is a free, web-based, open-source viewer and editor for pathways in Systems Biology Graphical Notation.  It is written with a series of libraries and extensions based on <a href="http://js.cytoscape.org/" target="_blank">Cytoscape.js</a>.  
        
Newt is developed to make it easy to design SBGN diagrams: rich yet minimalistic user-friendly IU; support for developing maps from scratch; automatic layout facilities; full support for complexes, compartments and submaps; state-of-the-art complexity management through hide-show and collapse-expand functionalities; advanced diagramming with grid and alignment support, resizing and styling map objects, and more.  
