Colortilt Psychophysics Experiment
==================================

This repository contains the source code for conducting and analyzing
 the "colortilt"¹ experiment, but with variable stimulus patch sizes, see

Kellner CJ, Wachtler T (2016) Stimulus size dependence of hue changes
induced by chromatic surrounds. J Opt Soc Am A 33(3):A267-A272,
[doi: 10.1364/JOSAA.33.00A267](http://dx.doi.org/10.1364/JOSAA.33.00A267)

For displaying the stimuli, the [iris](https://github.com/wachtlerlab/iris)
 software suite is used.

Analysis code is located in the `analysis` folder. Result figures
from the publication can be generated via the `paper.sh` script. For
this to work the environment variable `EXPFILE` has to be set to the
location of the main experiment control file.

More information about the experiment and the data itself
can be found under:
 [doi: 10.12751/g-node.t6vbz9](http://dx.doi.org/10.12751/g-node.t6vbz9)

If you are using this code please also cite it, using the doi above.

* [1] [Klauke and Wachtler, JoV 2015, doi: 10.1167/15.13.17](http://dx.doi.org/10.1167/15.13.17)

