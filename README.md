![GitHub Dark](img/logo_white.svg#gh-dark-mode-only)
![GitHub Light](img/logo_blue.svg#gh-light-mode-only)

# XO Sector Files
+ Melbourne, Brisbane, Auckland, Christchurch, Moresby
+ An open repository where all members can contribute to the Oceanic Sector Files

+ https://wiki.ivao.aero/en/home/devops/manuals/SectorFile_Definition
+ https://wiki.ivao.aero/en/home/atcoperations/tools

## Aims
+ :airplane: **Timely AIRAC updates.**  
  *AIRAC updates including fixes, VORs, NDBs and airports published monthly alongside releases from the respective aviation authorities.*
+ :airplane: **SMR**  
  *Surface Movement Radar for airports within our regions.*
+ :airplane: **SIDs/ STARs**  
  *Adding SIDs & STARs for all airports.*
+ :airplane: **Updating sectors and airspace boundaries**  
  *Keeping up to date sector boundaries and airspace maps for radar controllers.*

## How to Contribute
### Overview
Any member of the community may contribute this sector file so long as:
+ The data provided is factual and realistic.

### Adding airports layouts ("SMRs")
Ground layouts can be created by anyone simply by using Google Earth's polygon and line tools (see ATC Operations tools link above).

Create each feature of the airport individually in the following order, first = lowest:

+ Boundary/grass outline - (encompass the entire airfield with this)
+ Parking positions
+ Taxiways
+ Runways
+ Aprons
+ Buildings
These Polygon drawings create the TFL file

+ Stands lines
+ Taxiway lines
+ Stop bar lines
The create the GEO file

You do not need to add taxiway or holding point labels.

# Do not update:
+ Fixes, NDBs, VORs
+ SIDs, STARs, IAPs
+ Airways
+ ARPs
+ Airport Gates

We get this information automatically from AIRAC updates.

### Contribution Agreement
By contributing to this repository you agree that the ownership of any alteration(s) and/or addition(s) you make are transferred to IVAO Oceanic in its entirety and cannot be recalled.
