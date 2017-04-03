# FRED-Populations
## The Population Files used by the FRED Application


We have synthetic population files available for States and Counties. You can access files for a particular county in a state or you can access the full population files for a state. Note: These (the state files) can be from ~18MB (Wyoming) to ~1GB (California) in size.

Note: The county files are named by a five-digit fips code (two-digit state code + three-digit county code). The state files  are named only by the two-digit state code.

**The files should be copied into $FRED_HOME/populations to enable FRED to access the data.**

These population files are used by the following versions of FRED:
- FRED-v2.9.1
- FRED-v2.10.0
- FRED-v2.11.0
- FRED-v2.12.0
- FRED_HAZEL_2.0
- FRED-SickLeave-v1.2
- FRED-SickLeave-v2.0

FRED's U.S. synthetic populations uses the 2010 Decennial census and the 2007-2011 American Community Survey (ACS) as its sources of population counts and characteristics. This version also uses the Integrated Climate and Land Use System (ICLUS) gridded population dataset to place households across the landscape.

This work was supported by the Models of Infectious Disease Agency Study (MIDAS) from the National Institute of General Medical Sciences (NIGMS), grant number U24GM087704.

Please cite the following in any publication using this data:

Wheaton, W.D., *U.S. Synthetic Population 2010 Version 1.0 Quick Start Guide*, RTI International, May 2014.
