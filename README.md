# BIOMD0000000377: Bertram2000_PancreaticBetaCells_Oscillations

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000377.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000377.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000377 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** The phantom burster model for pancreatic beta-cells. **   
Bertram R, Previte J, Sherman A, Kinard TA, Satin LS. _Biophys J_2000
Dec;79(6):2880-92 [11106596](http://www.ncbi.nlm.nih.gov/pubmed/11106596),  
**Abstract:**   
Pancreatic beta-cells exhibit bursting oscillations with a wide range of
periods. Whereas periods in isolated cells are generally either a few seconds
or a few minutes, in intact islets of Langerhans they are intermediate (10-60
s). We develop a mathematical model for beta-cell electrical activity capable
of generating this wide range of bursting oscillations. Unlike previous
models, bursting is driven by the interaction of two slow processes, one with
a relatively small time constant (1-5 s) and the other with a much larger time
constant (1-2 min). Bursting on the intermediate time scale is generated
without need for a slow process having an intermediate time constant, hence
phantom bursting. The model suggests that isolated cells exhibiting a fast
pattern may nonetheless possess slower processes that can be brought out by
injecting suitable exogenous currents. Guided by this, we devise an
experimental protocol using the dynamic clamp technique that reliably elicits
islet-like, medium period oscillations from isolated cells. Finally, we show
that strong electrical coupling between a fast burster and a slow burster can
produce synchronized medium bursting, suggesting that islets may be composed
of cells that are intrinsically either fast or slow, with few or none that are
intrinsically medium.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Bertram R, Previte J, Sherman A, Kinard TA, Satin
LS. (2000) - version02** ](http://www.cellml.org/models/bertram_previte_sherma
n_kinard_satin_2000_version02)

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


