# MODEL0912887467: Demir1994_SinoatrialNode

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL0912887467.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL0912887467.git@20140916`

## Usage

Importing the model package.

`import MODEL0912887467 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A mathematical model of a rabbit sinoatrial node cell.**   
Demir SS, Clark JW, Murphey CR, Giles WR. _Am J Physiol_ 1994 Mar;266(3 Pt
1):C832-52 [8166247](http://www.ncbi.nlm.nih.gov/pubmed/8166247) ,  
**Abstract:**   
A mathematical model for the electrophysiological responses of a rabbit
sinoatrial node cell that is based on whole cell recordings from enzymatically
isolated single pacemaker cells at 37 degrees C has been developed. The ion
channels, Na(+)-K+ and Ca2+ pumps, and Na(+)-Ca2+ exchanger in the surface
membrane (sarcolemma) are described using equations for these known currents
in mammalian pacemaker cells. The extracellular environment is treated as a
diffusion-limited space, and the myoplasm contains Ca(2+)-binding proteins
(calmodulin and troponin). Original features of this model include 1) new
equations for the hyperpolarization-activated inward current, 2) assessment of
the role of the transient-type Ca2+ current during pacemaker depolarization,
3) inclusion of an Na+ current based on recent experimental data, and 4)
demonstration of the possible influence of pump and exchanger currents and
background currents on the pacemaker rate. This model provides acceptable fits
to voltage-clamp and action potential data and can be used to seek
biophysically based explanations of the electrophysiological activity in the
rabbit sinoatrial node cell.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Demir SS, Clark JW, Murphey CR, Giles WR. (1994) -
version01**
](http://www.cellml.org/models/demir_clark_giles_murphey_1994_version01)  
The original CellML model was created by:  
**Lloyd, Catherine, May**   
c.lloyd@aukland.ac.nz  
The University of Auckland  
The Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


