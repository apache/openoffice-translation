# Apache OpenOffice Translation Repository

## Overview
The apache/openoffice-translation repository is dedicated to managing translations for Apache OpenOffice. 
This is part of a semi automatic process to deploy translations from the translation website into the application repository.
The Files presented here are useable for Apache OpenOffice trunk (and 4.2.0)

# Repository Structure. 
The repository contains several key directories organized for translation workflow:
## Main Directories:
| Name         | Description |
| :---         | :----  |
| PO-Files     | Contains Portable Object files, which are standard translation file formats used in localization|
| POT-HELP     | Houses template files for help content translation, specifically under helpcontent2/source/text|
| POT-UI       | Stores user interface translation templates |
| aoo40, aoo40help | Copies of the Pootle project directories for UI and help |

## Key Files:
| Name       | Description |
| :---       | :----  |
| en-US.sdf  | The English (United States) source string definition file|
| header.txt | License header that goes at the top of each generated localize.sdf |

SDF files generated from the PO files (mksdf.sh) go to SDF-Files/, which is not tracked.

The 2024-10-27 commit (c8b6ea9c8f) reverts some uk and pl translations to older text. The state before it is commit c1358ae8ce.

# Project Governance
This project operates under the Apache Software Foundation guidelines and follows the ASF Code of Conduct.

The repository maintains strict community standards, with clear reporting guidelines for any conduct violations.

# Purpose & Significance
This repository serves as the central hub for:  
    - Coordinating multilingual translations of Apache OpenOffice  
    - Managing translation files in standardized formats (PO/POT files)  
    - Maintaining source strings and translated content  
    - Enabling collaboration among international translation contributors via translation hub  
&ensp;&ensp;https://translate.apache.org/projects/aoo40/  
      
For more information about Apache OpenOffice itself, you can visit the official website at openoffice.apache.org.

# Licensing
This Repo is using the Apache License, Version 2.0
