# Final Project 
#**Watching marine Zooplankton with effects from terrestrial wildfire smokescreens on the Oregon shelf**

**Leo Couchon, 2301141, lcouchon, OCN 215**

**Objective:** This assignment synthesizes many data analysis and plotting skills you have learned this quarter including reading text files, Numpy, Pandas, SciPy, and plotting.

## Brief Abstract 
   Looking at the impact of an event with the focus around understanding one parameter could potentially give key insight into ecosystem adaptability in a changing climate. To begin this observational study I looked at the Oregon Offshore site through the lens of how far the parameters of a single event can cause impact with the focus of zooplankton. All equipment recorded events at time of the smokescreen on September 9-10 2022 with abnormal zooplankton behavior, oxygen spikes and drops, temperature drop and slight salinity increase with anomalous readings. With further study community changes could be studied and seasonal variations could be accommodated for. 



## Scientific Question 
1. How does wildfire smoke from the Cedar Creek Fire during an offshore push on Semptember 9 covering equipment on the regional cabled array affect the diel vertical migration patterns of zooplankton?

## Hypothesis 
1. Hypothesis 1 -If the Cedar Creek fire's smokescreen affects the water's environment then marine zooplankton will no longer abide by their usual migration patterns; there will be increased surface activity from productivity bloom and smokescreen darkness. 

2. Null Hypothesis 1- The wildfire smokescreen will not change the diel vertical patterns of the zooplankton and the water's parameters during the offshore push of smoke at the observed cabled array site. 

2. Null Hypothesis 2 - The Cedar Creek fire will not create any data anomalies at the observed cabled array site during the offshore push of smoke. 

## Equipment Information and Credit of Data 
All data was taken from Oregon Offshore Site of the Regional Cabled Array(RCA) from the Oceans Observations Initiative(OOI). All equipment is cabled to a fiber-optic array and serviced once a year at most. 

1. Echograms - Data for this project used longterm EK60 sonar(subsite Mj01c). The two EK60s along the RCA was replaced 2024 with EK80s that can be used in a very similar manner(resolution can be dimmed to resemble EK60 if need be to compare in the future). Due to large file sizes the EK60 biosonar data was taken from mean weeks of data to limit file size, noise, and to avoid complex echopype package. Requested data used was averaged and calibrated by data team at OOI. Data observed ranged from August 28th 2022 to October 2nd 2022 to better center the smoke cover during September 9th (and partially 10th) of 2022. Information and knowledge on Echopype package to further understand data manipualtion practices was learned from

2. The dissolved oxygen, PC02, and CTD parameters were taken from a subsite very closely located to the EK60 subsite(subsitePC01B) -both are within Oregon Offshore on RCA. Dissolved oxygen(DO) was calibrated to account for known equipment drift in normal conditions by OOI data team prior to data request. Times taken spanned August 25th 2022 to October 2nd 2022 and was cleaned to match the temporal space of other insturment data from August 28th 2022 - October 2nd 2022. CTD and DO are from shallow profiler associated with site (directly above the fixed 200 meter platform for the shallow profiler)

Data from OOInet for above instruments
https://ooinet.oceanobservatories.org/platformnav?id=Q0UwMlNIQlA=&array=PHNwYW4+Q29hc3RhbCBFbmR1cmFuY2U8L3NwYW4+&lat=NDQuNjM3MjE=&lng=LTEyNC4zMDU3Mg==

3. Video - Satellite GOES-18, 2 video timespans to illustrate location (09/9/2022-09/10/2022, 09/10/2022-09/11/2022), Satellite GOES-16, 1 video timespan to illustrate intensity (09/09/2022-09/10/2022). In order to locate the offshore push anomoly I began my research by looking at wind vector data during large oregon fires that ranged in the timespan I knew the EK60 and EK80 were in the water actively collecting data. This was largely fruitless and I ended up largely leaning on NOAA satellite data used to track risk assesments for fires in Oregon. Cross referenced found data with map of site to understand when offshore push of Easterly winds during fires corresponded with equipment locations. CIRA Satellite Library from the NOAA site was essential for this, linked and creddited in immediacy here. https://satlib.cira.colostate.edu/event/cedar-creek-fire/ **GOES imagery:Imagery from any GOES satellite, credit the Cooperative Institute for Research in the Atmosphere at Colorado State University and the National Oceanic and Atmospheric Administration (CSU/CIRA & NOAA).**

OSSHORE SITE - CE02SHBP 
Raw Data for PC01B subsite (used to understand site equipment and locate bio-sonar)
https://rawdata.oceanobservatories.org/files/CE02SHBP/MJ01C/
Raw Data for ZPLSCB101
https://rawdata.oceanobservatories.org/files/CE02SHBP/MJ01C/ZPLSCB101_10.33.13.7/

OFFSHORE SITE 
Raw Data for PC01B subsite (used to understand site equipment and locate bio-sonar/ ended up not being used)
https://rawdata.oceanobservatories.org/files/CE04OSPS/PC01B/
 
Raw Data for ZPLSCB102 (huge data gaps for all fires found, became unsuable for this project but was an important first step in understanding project parameters and learning perseverance)
https://rawdata.oceanobservatories.org/files/CE04OSPS/PC01B/05-ZPLSCB102/


****

