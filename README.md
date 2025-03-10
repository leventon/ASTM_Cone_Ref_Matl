# ASTM_Cone_Ref_Matl
This is a repository for the measurement data and associated processing scripts, analysis, and summary reports developed by the ASTM E05.32 E1354 Standard Task Group. This data and associated reports should be considered as a 'predecisional draft copy' prepared for subject matter experts to provide critical review and to ensure the integrity of the measurement data and related analysis submitted to the Working Group.

#### How to Submit Experimental Data

Experimental and Modeling Results will be submitted, stored, and made publicly available on the [ASTM Cone Reference Material Repository](https://github.com/NIST-FRG/ASTM_Cone_Ref_Matl/). Experimental data may be shared by submitting pull requests to this repository or by sending data via email to [Dr. Isaac Leventon](mailto:Isaac.Leventon@NIST.gov).

##### File Format 
Experimental and Model results should be organized in simple ASCII comma-delimited files (*.csv files) with clear header names.  Note: For all submitted measurement data, please ensure that results are obtained with a data acquisition rate of 1 Hz. Examples of how to format data submissions, which may be used as templates, are included [here](https://github.com/NIST-FRG/ASTM_Cone_Ref_Matl/DATA).

##### File Naming
For simplicity, please collect your files in a single folder with your INSTITUTE name [INSTITUTE]. Please save measurement results with a name indicating your INSTITUTE, the experimental apparatus used, test conditions, and test repetition number. For example: Institute\_Cone\_25kW\_hor\_r1.csv.  

##### File Organization
###### Measurement data
Measurement data from repeated experiments should be saved and submitted as separate files, numbered sequentially (e.g.,Institute\_Material-ID\_Cone\_25kW\_hor\_r1.csv and Institute\_Material-ID\_Cone\_25kW\_hor\_r2.csv). 

Measurement data of Interest includes:
time (s), Mass (g), HRR (kW/m2), CO2 (Vol. %), CO (Vol. %), O2 (Vol. %), k_smoke (1/m)

###### Metadata
Metadata data from repeated experiments should be saved and submitted as separate files, numbered sequentially: Institute\_Material-ID\_Cone\_50kW\_hor\_r1.json and Institute\_Material-ID\_Cone\_50kW\_hor\_r2.json

Metadata files contain additional test setup information not included in the filename, including: 
* Test Conditions (Heater Temperature [K], Separation (to heater) [mm], Spark Ignitor [yes/no]; Holder Dimensions, Retainer frame [yes/no], Retaining grid [yes/no])
* Sample Information (Thickness [mm], Initial mass [g], Final mass [g], surface area [cm2])
* Test Results (Time to ignition [s], Time to flameout [s])
* Test Notes


##### File Description

\******


### Disclaimer
Parts of this work were prepared by the National Institute of Standards and Technology (NIST), an agency of the US government, and is not subject to copyright in the USA. Not all of the measurement data presented here has been through a formal review process. The identification of any commercial product or trade name does not imply endorsement or recommendation by NIST (or any other contributing institution). The policy of NIST is to use metric units of measurement in all its publications, and to provide statements of uncertainty for all original measurements. In this document, however, data from organizations outside NIST are shown, which may include measurements in non-metric units or measurements without uncertainty statements.
