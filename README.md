# DMRScan
R package for detection of differentially methylated regions with adjustment for multiple testing

# Important Info
## Authors
CM Page, L Vos, BK Andreasen

## Package structure
The function `dmr_scan()` requires three key inputs; 
  - a vector of test statistics for each CpG site, 
  - the corresponding positions (chromosome and bp position). 

Additional inputs are the 
  - maximum allowed distance within a region
  - the minimum number of CpGs within a region.

### Parameters


### Download & install in R
```R
library(devtools)
install_github("christpa/DMRScan")
# load package
load(DMRScan)
```
### Usage
Please see the vignette.

# Citation

To cite the DMRScan package in publications use:

*Assessing Genome-Wide Significance for the Detection of Differentially Methylated Regions*. Page CM, Vos L, Rounge TB, Harbo HF, and Andreassen BK _Submitted to BMC Bioinformatics_., (2016)

A BibTeX entry for LaTeX users is
```BibTeX
@Article{DMRScanRpackage,
title = {Assessing Genome-Wide Significance for the Detection of Differentially Methylated Regions},
author = {Christian M Page and Linda Vos and Trine B Rounge and Hanne F Harbo and Bettina K Andreassen},
journal = {BMC Bioinformatics (Submitted)},
year = {2016}}
```
End of README