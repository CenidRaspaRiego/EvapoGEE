# EvapoGEE
EvapoGEE is an open source implementation to calculate the reference evapotranspiration map and different time series variables. The EvapoGEE tool was developed on the GEE platform (https://earthengine.google.com/) and was coded in JavaScript.
A web application is also available (http://etocalculator.com).
EvapoGEE estimates, displays maps (Figure 1) and time series (Figure 2) of ETo based on reanalysis data, as well as, variables that influence in the ETo estimate.  EvapoGEE code can be adapted for other applications such as: irrigation using renalysis data in areas with little or no information, calculate ET to estimate the water footprint of crops, calculate Growing Degree Days (GDD), and as input in the estimation of ET using energy balance models based on remote sensing or to complete measured data. 
![image](https://github.com/CenidRaspaRiego/EvapoGEE/assets/107288420/577f165a-c0a1-459a-a5fc-4b6a4e100c3f)

![image](https://github.com/CenidRaspaRiego/EvapoGEE/assets/107288420/a3f28d67-4a9c-4483-8493-af4a676b28a0)

The design principles for EvapoGEE were that it should provide a site-specific ETo estimate for a range of dates using different reanalysis data sets (CFSv2, GLDAS, NLDAS y RTMA); dataset currently available in GEE. EvapoGEE filters the select dataset using three main criteria: (i) date range; (ii) variables shown in Table 4 (iii) location of the site indicated by the user. The Shuttle Radar Survey Mission (SRTM) was used to obtain the elevation of the site (Farr et al., 2007). The general methodology is summarized in the next figure.
![image](https://github.com/CenidRaspaRiego/EvapoGEE/assets/107288420/87eb6ad8-c91d-4fb1-a094-d63305ad19fe)

