# SAP HANA WebIDE Project for UK / England covid-nhs

To use this project
1. Clone Project

2. Specify Space - Project Setting -> Space

2. The db/src/.hdiconfig is platform specific, the default is for HANA Cloud, you can rename the appropirate

    HANA2.hdicconfig.txt - For HANA 2.x 
    HC.hdiconfig.txt - For Hana Cloud

3. Execute FlowGraph CCG_LAD2019

## Pubic DataSources
Updated via Python script England-Covid-Sources.ipynb

### NHS England Datasets

https://www.england.nhs.uk/statistics/statistical-work-areas/covid-19-daily-deaths/

### NHS Pathways & 111
https://digital.nhs.uk/data-and-information/publications/statistical/mi-potential-covid-19-symptoms-reported-through-nhs-pathways-and-111-online/latest

### Cases
https://coronavirus.data.gov.uk/#local-authorities

### Testing
https://www.gov.uk/guidance/coronavirus-covid-19-information-for-the-public

### Office National Statistics Deaths
https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/causesofdeath/datasets/deathregistrationsandoccurrencesbylocalauthorityandhealthboard

### Fixed Data - Local Authority Geo 
http://geoportal.statistics.gov.uk/datasets/ae90afc385c04d869bc8cf8890bd1bcd_1

### UK Population
https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/populationestimatesforukenglandandwalesscotlandandnorthernireland
