README

This script was developed as part of the SMARRTT operational research project
(Belarus cohort) to harmonise the Belarus SMARRTT dataset 
from the RedCap export format to the TB-IPD data dictionary v1.0 format.

Some sections of the script contain dataset-specific transformations 
based on how variables were recorded in the Belarus database. 
These include handling of:

• baseline sputum culture negative cases
• pregnancy and infant indicators
• some variables on the BASELINE tab
• linezolid dose reductions
• adverse event (AE) recording structure
• treatment interruption variables

Therefore, the script may require adaptation when applied to datasets 
from other sites, depending on differences in database structure, 
variable naming, and data entry practices.

Users are encouraged to review each transformation step before 
applying the script to their own dataset.
