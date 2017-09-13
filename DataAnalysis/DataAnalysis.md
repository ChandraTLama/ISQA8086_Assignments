# Data Entry Analysis

In this assignment, we are going to analyze 3 files which consists of data related to planktons especially focussed on two species - "Conochilus unicornis"
and "Conochilus hippocrepis".Since planktons might be different as per the depth from which they are collected and their dictributions also varies from 
day to night, Planktons are collected from certain depths during both day and night. The main goal of this data collection is to study day-night distribution of 2 species of zooplankton in various depth from surface water
for several years. 

## 1. Problems in data/files
* Data format is not same in all files. in file 1 "pond2010", under species column, types of planktons - Cuni or Chippo are mentioned while in other two files each species have separate columns as Cuni#/L and Chippo#/L.
* In file 1 "pond2010", column density doesn't have unit of measurement. It should be individuals/liter or individuals/millilitre. 
In 2 of 3 files, unit of measurement for depth is not given. For temperature, there is no any unit mentioned - not sure whether it is celcius or fahrenheit.
* Data seem not enough to reach any conclusions since data are collected only for one month June for 2 years 2010 and 2011.
* It is mentioned that plankton distribution changes from day to night, so it would have been better it was mentioned when the data were collected - day/night.
* In file 1 "pond2010", some data in temperature, density and diameter are missing. In file "zoop-temp-main"
* In file "zoop-temp", it is instructed to see yellow notebook for map and details but there is not any file or link for this notebook to refer.
* It is not mentioned the location from where the data are collected. One file is for stattion A, one is for station B while one file doesn't have any location/habitat information. Location can add some value to analysis and result.


## 2. New System for Organization
Problems are mentioned above and new system should be designed in such a way that above problems can be avoided.

* Data Dictionary and reference files should be provided along with data so that the data analysis will be easy.
* Missing data should be avoided as much as possible so that the data cleaning and processing will be faster and effective.


| Date                                                                                                                            	| Time                                                                        	| Depth (m)                                                             	| Cuni #/L                                                       	| Cuni Colony Size (mm)                                                            	| Chippo#/L                                                      	| Chippo Colony Size                                                              	| Chla (RFU)                                                                                                               	| Temp (celcius)                                                      	| Habitat/Location                                       	|
|---------------------------------------------------------------------------------------------------------------------------------	|-----------------------------------------------------------------------------	|-----------------------------------------------------------------------	|----------------------------------------------------------------	|----------------------------------------------------------------------------------	|----------------------------------------------------------------	|---------------------------------------------------------------------------------	|--------------------------------------------------------------------------------------------------------------------------	|---------------------------------------------------------------------	|--------------------------------------------------------	|
| This should include the date of data collected  in the form mm/dd/yyyy.  Data should be collected for several years and months. 	| It should be either day (noon) or the night (2 am) when data are collected. 	| Depth from surface  in meter should be mentioned with 0 m as surface. 	| Density of Conochilus unicornis as number of individuals/liter 	| It refers to the diameter of 5 randomly chose conochilus colonies in the sample  	| Density of Conochilus hippocrep as number of individuals/liter 	| It refers to the diameter of 5 randomly chose conochilus colonies in the sample 	| detect the fluorescence from chlorophyll using YSI probe. We can measure in RFU (Relative Fluorescence Units) or in µg/L 	| Temperature should be in one format either in celcius or fahrenheit 	| Location of lake or pond should be given specifically. 	|