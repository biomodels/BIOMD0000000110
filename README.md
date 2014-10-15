# BIOMD0000000110: Qu2003_CellCycle

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000110.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000110.git@20140916`


# Model Notes


This model is from the article:  
**Dynamics of the cell cycle: checkpoints, sizers, and timers.**   
Qu Z, MacLellan WR, Weiss JN _Biophys. J._ 2003 Dec; 85(6): 3600-11
[14645053](http://www.ncbi.nlm.nih.gov/pubmed/14645053) ,  
**Abstract:**   
We have developed a generic mathematical model of a cell cycle signaling
network in higher eukaryotes that can be used to simulate both the G1/S and
G2/M transitions. In our model, the positive feedback facilitated by CDC25 and
wee1 causes bistability in cyclin-dependent kinase activity, whereas the
negative feedback facilitated by SKP2 or anaphase-promoting-complex turns this
bistable behavior into limit cycle behavior. The cell cycle checkpoint is a
Hopf bifurcation point. These behaviors are coordinated by growth and division
to maintain normal cell cycle and size homeostasis. This model successfully
reproduces sizer, timer, and the restriction point features of the eukaryotic
cell cycle, in addition to other experimental findings.

  

Figure6B has been reproduced by both SBMLodeSolver online and MathSBML. We do
not include the synthesis of cyclins is proportional to cell size (Equation 2
in Page3604 of the paper) in this model. The author of the paper keep all the
variables and parameters dimensionless. But in the model, we choose to use
default units of SBML.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


