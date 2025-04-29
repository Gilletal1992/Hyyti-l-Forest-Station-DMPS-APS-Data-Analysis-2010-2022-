This directory contains the APS data
from Hyytiälä. 

The sum-files contain:
-First column: number of day since the beginning of the year, first day is one
-Second column: total concentration over the measurement range
-First line: Particle diameter (aerodynamic) (m)
-Everything else dN/dlogDp (cm-3)

You can look the data with apsplot program (for example apsplot('000101',16)). 


Before 17/3/2005 sample line was not heated. During fogs concentrations were very high.
Data is filtered so, that spectras with aerosol masses larger than 50ug/m3 are removed. Now the
sample is heated to 40degC before analysis.

