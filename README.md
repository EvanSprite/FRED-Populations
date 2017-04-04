# FRED-Populations
## The Population Files used by the FRED Application


We have synthetic population files available for States and Counties. You can access files for a particular county in a state or you can access the full population files for a state. Note: These (the state files) can be from ~18MB (Wyoming) to ~1GB (California) in size.

Note: The county files are named by a five-digit fips code (two-digit state code + three-digit county code). The state files  are named only by the two-digit state code.

**The files should be copied into $FRED_HOME/populations to enable FRED to access the data.**

These population files are used by the following versions of FRED:
- FRED-v2.9.0
- FRED-v2.9.1
- FRED-v2.10.0
- FRED-v2.11.0
- FRED-v2.12.0
- FRED_HAZEL_2.0
- FRED-SickLeave-v1.2
- FRED-SickLeave-v2.0

FRED's U.S. synthetic populations were generated from 2010 U.S. Decennial Census and 2007-2011 5-year American Community Survey data. The data are computer representations of the distribution of households by four demographic variables, but do not represent actual households or locations of actual households:
- Income of the household
- Number of occupants in the household
- Race of the head of household
- Age of the head of household

This version also uses the Integrated Climate and Land Use System (ICLUS) gridded population dataset to place households across the landscape.

No personally identifiable information was used to generate these data.  
Funded under the Models of Infectious Disease Agent Study (MIDAS) grant 1-U24-GM087704 from NIGMS.

Please cite the following in any publication using this data:

Wheaton, W.D., *U.S. Synthetic Population 2010 Version 1.0 Quick Start Guide*, RTI International, May 2014.
