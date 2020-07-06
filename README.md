# SAP HANA WebIDE Project for UK / England covid-nhs

To use this project
1. Clone Project
2. The db/src/.hdiconfig is platform specific, the default is for HANA Cloud, you can rename the appropirate
HANA2.hdicconfig.txt - For HANA 2.x 
HC.hdiconfig.txt - For Hana Cloud
3. Execute FlowGraph CCG_LAD2019

## Pubic DataSources
### NHS England Datasets
Updated via Python
https://www.england.nhs.uk/statistics/statistical-work-areas/covid-19-daily-deaths/

Hospital deathregistrationsandoccurrencesbylocalauthorityandhealthboard

### NHS Pathtways
https://digital.nhs.uk/data-and-information/publications/statistical/mi-potential-covid-19-symptoms-reported-through-nhs-pathways-and-111-online/latest

### Cases
https://coronavirus.data.gov.uk/#local-authorities

### Office National Statistics Deaths
https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/causesofdeath/datasets/deathregistrationsandoccurrencesbylocalauthorityandhealthboard


### Fixed Data - Local Authority Geo 
http://geoportal.statistics.gov.uk/datasets/ae90afc385c04d869bc8cf8890bd1bcd_1

### UK Population
https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/populationestimatesforukenglandandwalesscotlandandnorthernireland
