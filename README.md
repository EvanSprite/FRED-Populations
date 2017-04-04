# FRED-Populations
## The Population Files used by the FRED Application

We have synthetic population files available for States and Counties. You can access files for a particular county in a state or you can access the full population files for a state. Note: These (the state files) can be from ~18MB (Wyoming) to ~1GB (California) in size.

Note: The county files are named by a five-digit fips code (two-digit state code + three-digit county code). The state files  are named only by the two-digit state code.

**The files should be copied into $FRED_HOME/populations to enable FRED to access the data.**

These population files are used by FRED up to and including FRED-v2.8.1

FRED's U.S. synthetic populations were generated from 2000 U.S. Decennial Census and 2005-2009 5-year American Community Survey data. The data are computer representations of the distribution of households by four demographic variables, but do not represent actual households or locations of actual households:
- Income of the household
- Number of occupants in the household
- Race of the head of household
- Age of the head of household

This version also uses the Integrated Climate and Land Use System (ICLUS) gridded population dataset to place households across the landscape.

No personally identifiable information was used to generate these data.

Funded under the Models of Infectious Disease Agent Study (MIDAS) grant 1-U24-GM087704 from NIGMS.
