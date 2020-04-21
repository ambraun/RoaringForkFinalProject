# Salinizatin in the Roaring Fork Watershed 
Final Project for Environmental Data Analytics 872 with Kateri Salk-Gunderson, Spring 2020 

## Summary
The effects of salinity have been studied extensively in the lower Colorado River Basin. This data analysis seeks to understand the salinity of the Roaring Fork River, a tributary basin to the Colorado River in the Upper Colorado River Basin. This analysis seeks to understand salinity over time and through the upper, middle and outlet portions of the Roaring Fork River. This repository contains hydrologic surface water characteristics of salinity, alkalinity, and specific conductance of the Roaring Fork River in Pitkin, Eagle and Garfield Counties, Colorado collected by the USGS from 1975 to 2020.  

## Investigators
Amanda Braun MEM/MBA, Principal Investigator, Duke University, amanda.m.braun@duke.edu, 

## Keywords
**Specific Conductance** - measure a water sample's ability to conduct electricity. A water's conductivity depends on the total number of ions in it, so it is a proxy for how many salts are in the water sample, and generally saltier water has a higher specific conductance. Specificic conductance reflects the total amount of ions in te water sample. The unit of specific conductance in freshwater is microsiemens per centimeter at 25 degrees Celsius.

More information on Specific Conductance published by USGS can be found at:  https://pubs.usgs.gov/tm/09/a6.3/tm9-a6_3.pdf

**pH** - Expressing the acidity or alkalinity of a solution on a logarithmic scale on which 7 is neutral, lower values are more acidic and higher values more alkaline. The pH is equal to −log10 c, where c is the hydrogen ion concentration in moles per liter. Most freshwater rivers have a neutral pH (close to (7) dependent on the watershed geology, and most organisms cannot survive under a pH of 6. 

**Alakalinity** - The capacity of water to resist changes in pH that would make the water more acidic. Total alkalinity is measured by the amount of acid needed to bring the awater sample to a pH of 4.2. At this pH all the alkaline compounds in the sample are "used up." Alakalinity is reported as milligrams per liter (mg/l) of calcium carbonate (CaCO3) .


## Database Information

This surface water data was collected by the United States Geological Survey, USGS Colorado Water Science Center and accessed via National Water Quality Monitoring Council's Water Quality Portal <https://www.waterqualitydata.us/> on April 14th, 2020. The data was pulled from the National Water Information System (NWIS) database for seven 12-digit HUCs that encompoass the length of the Roaring Fork River: 140100040102, 140100040104,140100040106,140100040602,140100040603,140100040802, and 140100041003.

The 7 HUCs are divided into upper, middle and outlet portions of the Roaring Fork River to enable analysis of salinity along the length of the river. 

*Headwaters*
Headwaters Roaring Fork River - 140100040102
Weller Lake-Roaring Fork River - 140100040104

*Upper Roaring Fork HUCs*
Roaring Fork River above Aspen - 140100040106
Brush Creek-Roaring Fork River - 140100040602

*Middle Roaring Fork HUCs*
Dry Woody Creek-Roaring Fork River - 140100040603
Blue Creek-Roaring Fork River - 140100040802

*Outlet Roaring Fork HUCs*
Outlet Roaring Fork River - 140100041003

*Specific conductance* data was collected 45 sites within the 7 HUCs with 2148 samples results. 

*pH* data was collected from 43 sites within the 7 HUCs, reported in total standard units. 

*Alkalinity* data was collected from 40 sites with 478 sample results within the HUCs. 

## Folder structure, file formats, and naming conventions 
Within the RFR There is a "Data"" folder containing a "Raw" data folder and a "Processed" data folder. 
The "Raw" data folder contains raw data in CSV format for the seven HUCS of the Roaring Fork River watershed for alkalinity named "RoaringForkAlkalinityRaw", pH named "RoaringForkpHRaw", and specific conductance named "RoaringForkSpecificConductanceRaw".

The "Processed" data folder WILL contains processed data in CSV format for the seven HUCS of the Roaring Fork River watershed for alkalinity named "RoaringForkAlkalinityProcessed", pH named "RoaringForkpHProcessed", and specific conductance named "RoaringForkSpecificConductanceProcessed".

## Metadata
**Specific Conductance** 
**Columns**
  *Activity Start Date*: The date the sample was collected. 
  
  Data Class: Date  

  *Conductance:* Reported in uS/cm (microSeimins per centimeter). 
      
   Data Class: Numeric

  *LocationIdentifier:* USGS Colorado Water Science Center site identification number.
      Respults: USGS-09072550; USGS-09073300; USGS-09073400; USGS-09076520; USGS-09081000;USGS-09085000;      
      USGS-390421106533400; USGS-390810106463000; USGS-390835106485500; USGS-391050106550000;                 
      USGS-391140106492001;USGS-391220106573800; USGS-391239106501900; USGS-391345106550000; 
      USGS-391531106525200; USGS-391740106550701; USGS-391755106542401; USGS-392032107001900; 
      USGS-392110107011300; USGS-392155107050800; USGS-392158107020000; USGS-392233107050100; 
      USGS-392337107052200; USGS-392350107111400; USGS-392404107070900; USGS-392428107064500; 
      USGS-392447107091000; USGS-392449107091800; USGS-392449107111400; USGS-392453107131100; 
      USGS-392502107090600; USGS-392503107122400;USGS-392522107052900; USGS-392535107224600; 
      USGS-392555107042700; USGS-392557107085100; USGS-392747107154201USGS-392814107145100; 
      USGS-392826107160800; USGS-392828107161301; USGS-392844107170900; USGS-392847107171100; 
      USGS-392946107182100. 

  *HydrologicCondition:* The stage of the river in which the water sample was collected. 
      Results: Not determined, Stable normal stage, Rising stage; Stable, low stage; Stable, high stage;
         Falling stage, Peak stage, Not applicable.
      Data Class: Character Vector 

*HydrologicEvent:* The climactic condition of the water sampled.
      Results:Routine sample, Snowmelt, Under ice cover, Drought, Not applicable, Regulated flow, Spring   
         breakup
      Data class: Character Vector 
      
**pH**

**Columns**

*Activity Identifier:* Sample identification provided to the National Water Information System. 
Data Class: 

*Activity Start Date:* Date the sample was collected.
Data Class:

*Monitoring Location Identifier:* USGS site of the sample collected. 
Data Class:

*HydrologicCondition:* The stage of the river in which the water sample was collected. 
      Results: Not determined, Stable normal stage, Rising stage; Stable, low stage; Stable, high stage;
         Falling stage, Peak stage, Not applicable.
      Data Class: Character Vector 

*Hydrologic Event:* The climactic condition of the water sampled.
      Results:Routine sample, Snowmelt, Under ice cover, Drought, Not applicable, Regulated flow, Spring   
         breakup
      Data Class: Character Vector 

*Measure:* pH of the measured sample. 
Data Class: 

*Sample Aquifer:* A few of the samples have the type of aquifer the surrounding geology is a part of. Results: Alluvium, Flood Plain; Maroon Formation; Pennsylvanian System; Permian-Pennsylvanian Systems; Quaternary System; Valley-Fill Deposits.
Data Class: 

## Quality assurance/quality  
Data samples that were "quality control sample-field replicate" lab tested  were removed from the alkalinity and specific conductance and pH raw data. 

