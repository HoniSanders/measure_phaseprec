measure_phaseprec
=================

Library for quantification of hippocampal phase precession written by Richard Kempter (https://itb.biologie.hu-berlin.de/~kempter/)

The only function necessary for the end user is cl_corr:  
`[circ_lin_corr pval slope_deg phi0_deg RR] = cl_corr(lin_x, circ_y_deg, min_slope, max_slope)`


## Original Citation
Kempter R, Leibold C, Buzsáki G, Diba K, Schmidt R (2012) Quantifying circular-linear associations: hippocampal phase precession. J Neurosci Methods 207:113–124. http://dx.doi.org/10.1016/j.jneumeth.2012.03.007


## Other relevant sources
Also, see Philipp Beren's CircStat toolbox, which this is based on.  
https://github.com/circstat/circstat-matlab or  
http://www.mathworks.com/matlabcentral/fileexchange/10676-circular-statistics-toolbox--directional-statistics- or  
https://philippberens.wordpress.com/code/circstats/

You may wish to also cite:  
Sanders, H., Ji, D., Sasaki, T., Leutgeb, J. K., Wilson, M. A., & Lisman, J. E. (2019). Temporal coding and rate remapping: Representation of nonspatial information in the hippocampus. Hippocampus, 29(2), 111-127.  https://doi.org/10.1002/hipo.23020
