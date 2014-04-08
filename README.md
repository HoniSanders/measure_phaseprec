measure_phaseprec
=================

Library for quantification of hippocampal phase precession written by Richard Kempter

described in Kempter R, Leibold C, Buzsáki G, Diba K, Schmidt R (2012) Quantifying circular-linear associations: hippocampal phase precession. J Neurosci Methods 207:113–124. http://dx.doi.org/10.1016/j.jneumeth.2012.03.007


The only function necessary for end user is cl_corr:

[circ_lin_corr pval slope_deg phi0_deg RR] = cl_corr(lin_x, circ_y_deg, min_slope, max_slope)
