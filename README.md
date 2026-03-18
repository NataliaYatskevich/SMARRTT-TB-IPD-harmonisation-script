README

This script was developed as part of the SMARRTT operational research
project (Belarus cohort) to provide a reproducible workflow 
for harmonising RedCap data into the TB-IPD data dictionary v1.0 format.

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

The script also includes several basic data consistency checks 
(e.g. date logic) to help identify potential data issues before harmonisation.
