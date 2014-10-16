# MODEL1202270001: Lee2012_GeneExpression_tTAdoxInteraction

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1202270001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1202270001.git@20140916`

## Usage

Importing the model package.

`import MODEL1202270001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**A regulatory role for repeated decoy transcription factor binding sites in target gene expression.**   
Lee TH, Maheshri N. _Mol Syst Biol._ 2012 Mar 27;8:576.
[22453733](http://www.ncbi.nlm.nih.gov/pubmed/22453733) ,  
**Abstract:**   
Tandem repeats of DNA that contain transcription factor (TF) binding sites
could serve as decoys, competitively binding to TFs and affecting target gene
expression. Using a synthetic system in budding yeast, we demonstrate that
repeated decoy sites inhibit gene expression by sequestering a transcriptional
activator and converting the graded dose-response of target promoters to a
sharper, sigmoidal-like response. On the basis of both modeling and chromatin
immunoprecipitation measurements, we attribute the altered response to TF
binding decoy sites more tightly than promoter binding sites. Tight TF binding
to arrays of contiguous repeated decoy sites only occurs when the arrays are
mostly unoccupied. Finally, we show that the altered sigmoidal-like response
can convert the graded response of a transcriptional positive-feedback loop to
a bimodal response. Together, these results show how changing numbers of
repeated TF binding sites lead to qualitative changes in behavior and raise
new questions about the stability of TF/promoter binding.

**Note:** This model corresponds to the comprehensive model encompassing the basic model (MODEL1202270000) as well as the tTA/dox (tet-transcriptional activator/doxycycline) interaction, described in the paper. 

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


