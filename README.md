# BIOMD0000000261: Tiago2010_FeMetabolism_FeLoaded

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000261.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000261.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000261 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Systems analysis of iron metabolism: the network of iron pools and fluxes **   
Tiago JS Lopes, Tatyana Luganskaja, Maja Vujic-Spasic, Matthias W Hentze,
Martina U Muckenthaler, Klaus Schumann and Jens G Reich _BMC Systems
Biology_2010, Aug 13;4(1):112.
[20704761](http://www.ncbi.nlm.nih.gov/pubmed/20704761),  
**Abstract:**   
Background  
Every cell of the mammalian organism needs iron in numerous oxido-reductive
processes as well as for transport and storage of oxygen. The versatility of
ionic iron makes it a toxic entity which can catalyze the production of
radicals that damage vital membranous and macromolecular assemblies in the
cell. The mammalian organism maintains therefore a complex regulatory network
of iron uptake, excretion and intra-body distribution. Intracellular
regulation in different cell types is intertwined with a global hormonal
signaling structure. Iron deficiency as well as excess of iron are frequent
and serious human disorders. They can affect every cell, but also the organism
as a whole.  
Results  
Here, we present a kinematic model of the dynamic system of iron pools and
fluxes. It is based on ferrokinetic data and chemical measurements in C57BL6
wild-type mice maintained on iron-deficient, iron-adequate, or iron-loaded
diet. The tracer iron levels in major tissues and organs (16 compartment) were
followed for 28 days. The evaluation resulted in a whole-body model of
fractional clearance rates. The analysis permits calculation of absolute flux
rates in the steady-state, of iron distribution into different organs, of
tracer-accessible pool sizes and of residence times of iron in the different
compartments in response to three states of iron-repletion induced by the
dietary regime.  
Conclusions  
This mathematical model presents a comprehensive physiological picture of mice
under three different diets with varying iron contents. The quantitative
results reflect systemic properties of iron metabolism: dynamic closedness,
hierarchy of time scales, switch-over response and dynamics of iron storage in
parenchymal organs. Therefore, we could assess which parameters will change
under dietary perturbations and study in quantitative terms when those changes
take place.

** This model corresponds to the Iron Loaded condition - Mice **

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


