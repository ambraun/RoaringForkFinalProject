# Salinizatin in the Roaring Fork Watershed 
Final Project for Environmental Data Analytics 872 with Kateri Salk-Gunderson, Spring 2020 

<General notes: add as much information as is relevant for your repository. Some overarching guidelines are provided, but feel free to expand on these guidelines.>
<More resources found here: https://www.dataone.org/all-best-practices>
<Delete the text inside the brackets when formatting your file.>

## Summary


<describe the purpose of this repository, the information it contains, and any relevant analysis goals. What, why, where, when, how?>

The effects of salinity have been studied extensively in the lower Colorado River Basin. This data analysis seeks to understand the salinity of the Roaring Fork River, a tributary basin to the Colorado River in the Upper Colorado River Basin. This analysis seeks to understand salinity over time and through the upper, middle and outlet portions of the Roaring Fork River. This repository contains hydrologic surface water characteristics of salinity, alkalinity, and specific conductance of the Roaring Fork River in Pitkin, Eagle and Garfield Counties, Colorado collected by the USGS from 1975 to 2020.  


## Investigators

Amanda Braun MEM/MBA, Principal Investigator, Duke University, amanda.m.braun@duke.edu, 

## Keywords

Specific Conductance - measure a water sample's ability to conduct electricity. A water's conductivity depends on the total number of ions in it, so it is a proxy for how many salts are in the water sample, and generally saltier water has a higher specific conductance. Specificic conductance reflects the total amount of ions in te water sample. The unit of specific conductance in freshwater is microsiemens per centimeter at 25 degrees Celsius (77 degrees Faranheit)

More information on Specific Conductance published by USGS can be found at:  https://pubs.usgs.gov/tm/09/a6.3/tm9-a6_3.pdf

pH - pH is a measure of acidity. Most freshwater rivers have a neutral pH (close to (7) dependent on the watershed geology. 

Alakalinity 


## Database Information

This surface water data was collected by the United States Geological Survey, USGS Colorado Water Science Center and accessed via National Water Quality Monitoring Council's Water Quality Portal <https://www.waterqualitydata.us/> on April 14th, 2020. The data was pulled from the National Water Information System (NWIS) database for seven 12-digit HUCs that encompoass the length of the Roaring Fork River: 140100040102, 140100040104,140100040106,140100040602, 140100040603,140100040802, 140100041003.


## Folder structure, file formats, and naming conventions 

Within the RFR There is a "Data"" folder containing both "R"
There are three raw data files in the "Raw " subfolder .

There are three 

## Metadata

<For each data file in the repository, describe the data contained in each column. Include the column name, a description of the information, the class of data, and any units associated with the data. Create a list or table for each data file.> 
RFR_Alakalinity.csv

Alkalinity - 40 sites - 478 sample results ResultMeasure/MeasureUnitCode, mg/l CaCO3
Activity Start Date - The date the sample was collected. Class: Date  
Conductance - measured in uS/cm
LocationIdentifier - USGS-09072550; USGS-09073300; USGS-09073400; USGS-09076520; USGS-09081000;USGS-09085000; USGS-390421106533400; USGS-390810106463000; USGS-390835106485500; USGS-391050106550000; USGS-391140106492001;USGS-391220106573800; USGS-391239106501900; USGS-391345106550000; USGS-391531106525200; USGS-391740106550701; USGS-391755106542401; USGS-392032107001900; USGS-392110107011300; USGS-392155107050800; USGS-392158107020000; USGS-392233107050100; USGS-392337107052200; USGS-392350107111400; USGS-392404107070900; USGS-392428107064500; USGS-392447107091000; USGS-392449107091800; USGS-392449107111400; USGS-392453107131100; USGS-392502107090600; USGS-392503107122400;
USGS-392522107052900; USGS-392535107224600; USGS-392555107042700; USGS-392557107085100; USGS-392747107154201
USGS-392814107145100; USGS-392826107160800; USGS-392828107161301; USGS-392844107170900; USGS-392847107171100
USGS-392946107182100

Hydrologic Condition: Not determined, Stable normal stage, Rising stage; Stable, low stage; Stable, high stage;
Falling stage, Peak stage, Not applicable 

RFR_SpecificConductance.csv

Specific Conductance - National Water Information Systems - 2,148 sample results from 45 sites.  USGSP Code: 00095, ResultMeasure/MeasureUnitCode uS/cm @25C, 25 degrees celsius US DH-81 Depth integrating suspended hand line sampler




## Scripts and code

<list any software scripts/code contained in the repository and a description of their purpose.>

## Quality assurance/quality  

Deleted Quality Control Sample-Field Replicate from the specific conductance data set. 
<describe any relevant QA/QC procedures taken with your data. Some ideas can be found here:>
<https://www.dataone.org/best-practices/develop-quality-assurance-and-quality-control-plan>
<https://www.dataone.org/best-practices/ensure-basic-quality-control>
<https://www.dataone.org/best-practices/communicate-data-quality>
<https://www.dataone.org/best-practices/identify-outliers>
<https://www.dataone.org/best-practices/identify-values-are-estimated>
