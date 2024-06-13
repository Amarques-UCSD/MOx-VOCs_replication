README for data and code associated with, "Understanding the ability of low-cost MOx sensors to quantify ambient VOCs (collier-Oxandale et al., 2019).

Included in the Complete Data.mat file are two tables, one for the PrimaryUPod (the main UPod data utlized in the analysis) and the 
SecondaryUPod (or one, for which the data was used for analysis shown in the supplemental).

Opening the code files and running them will produce plots and datasets matching the results from the paper. This will also allow users to further 
explore both the results from the paper and pursue their own analysis.

Note, this data has undergone intial processing, including: the removal of sensor warm-up data, the calculation of new parameters from the raw sensor data 
(specifically: absolute humidity, and normalized resistances for the two MOx VOC sensors), five-minute averages were calculated, and the all of the sensor 
data was matched to corresponding five-minute averages of reference data (original versions of the reference data are available through the DISCOVER-AQ database). 
This processed data is what is available in the Complete Data file. Some code for additonal figures shown in the paper has been exluded here to reduce confusion, 
for additional code along with guidance using that code, please contact the main contributor of this data (i.e., the contact for the associated journal article).  

Column headers are the same for both datasets and are as follows:

Time - Time (UTC/GMT)
Temp - Temperature (deg C)
RH - Relative Humidity (%)
Fig1v - Figaro2600 sensor data (voltage values)
Fig2v - Figaro2602 sensor data (voltage values)
ELT - NDIR CO2 sensor data (voaltage values)
e2vO3 - MOx O3 sensor data (voltage values)
e2vNO2 - MOx NO2 sensor data (voltage values)
AH - absolute humidity, calculated (mole fraction of water in air)
Fig1r - Figaro2600 sensor data, calculated (in normalized resistance)
Fig2r - Figaro2602 sensor data, calculated (in normalized resistance)
Actd - Acetaldehyde, PTR-QMS (ppbv)
Acet - Acetone, PTR-QMS (ppbv)
Benz - Benzene, PTR-QMS (ppbv)
C8 - C8, PTR-QMS (ppbv)
C9 - C9, PTR-QMS (ppbv)
Form - Formaldehyde, PTR-QMS (ppbv)
Meth - Methanol, PTR-QMS (ppbv)
Tol - Toluene, PTR-QMS (ppbv)
CH4 - Methane, NATIVE (ppmv)
CO - Carbon Monoxide, NATIVE (ppmv)
O3 - Ozone, NATIVE (ppmv)
NO2 - Nitrogen Dioxide, NATIVE (ppmv)
CO2 - Carbon Dioxide, NATIVE (ppmv)
T_Plat - Temperature, NATIVE (deg C)
RH_Plat - Realtive Humidity, NATIVE (%)
H2S - Hydrogen Sulfide, NATIVE
TimeL - Time (local)


END