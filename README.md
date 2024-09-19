# Communities and Crime Dataset

### Abstract
This dataset covers socio-economic, law enforcement, and crime data from US communities, combining information from the 1990 US Census, the 1990 US LEMAS (Law Enforcement Management and Administrative Statistics) survey, and crime data from the 1995 FBI UCR (Uniform Crime Reporting). The dataset consists of **1994 instances** and **128 attributes**. It is intended for use in regression tasks and is useful for exploring crime patterns and their socio-economic and law enforcement correlations.

---

### Dataset Characteristics
- **Type**: Multivariate
- **Attributes**: Real-valued
- **Associated Task**: Regression
- **Number of Instances**: 1,994
- **Number of Attributes**: 128 (122 predictive, 5 non-predictive, and 1 target)
- **Missing Values**: Yes
- **Area**: Social Studies
- **Date Donated**: July 13, 2009

---

### Source
- **Creator**: Michael Redmond, Computer Science, La Salle University, Philadelphia, PA, USA.
- **Data Origin**:
  - 1990 US Census
  - 1990 US Law Enforcement Management and Administrative Statistics Survey
  - 1995 US FBI Uniform Crime Reporting
  - Available from ICPSR at the University of Michigan.

---

### Data Information
The dataset includes 122 predictive variables related to communities (e.g., demographics, income, education) and law enforcement (e.g., police resources, drug unit deployments), plus 6 non-predictive attributes, and the target variable, **ViolentCrimesPerPop** (violent crimes per 100,000 population).

The target variable was computed using crime statistics like murder, rape, robbery, and assault. Note that some states reported missing or incorrect rape data, leading to excluded communities, primarily from the Midwest.

All numeric data is normalized to a 0.00-1.00 range using an unsupervised equal-interval binning method. The normalization preserves the distribution within an attribute but does not maintain relationships across different attributes.

---

### Attribute Information
The dataset includes 128 attributes in total, broken down as follows:

- **state**: US state code (nominal)
- **county**: Numeric code for county (numeric)
- **community**: Numeric code for community (numeric)
- **communityname**: Name of the community (string)
- **fold**: Cross-validation fold number (numeric)
- **population**: Population of the community (numeric)
- **householdsize**: Mean people per household (numeric)
- **racepctblack**: Percentage of African American residents (numeric)
- **racePctWhite**: Percentage of Caucasian residents (numeric)
- **racePctAsian**: Percentage of Asian residents (numeric)
- **racePctHisp**: Percentage of Hispanic residents (numeric)
- **agePct12t21**: Percentage of the population aged 12-21 (numeric)
- **agePct12t29**: Percentage of the population aged 12-29 (numeric)
- **agePct16t24**: Percentage of the population aged 16-24 (numeric)
- **agePct65up**: Percentage of the population aged 65 and over (numeric)
- **numbUrban**: Number of people living in urban areas (numeric)
- **pctUrban**: Percentage of urban population (numeric)
- **medIncome**: Median household income (numeric)
- **pctWWage**: Percentage of households with wage/salary income in 1989 (numeric)
- **pctWFarmSelf**: Percentage of households with farm or self-employment income in 1989 (numeric)
- **pctWInvInc**: Percentage of households with investment income (numeric)
- **pctWSocSec**: Percentage of households with social security income (numeric)
- **pctWPubAsst**: Percentage of households with public assistance (numeric)
- **pctWRetire**: Percentage of households with retirement income (numeric)
- **medFamInc**: Median family income (numeric)
- **perCapInc**: Per capita income (numeric)
- **whitePerCap**: Per capita income for Caucasians (numeric)
- **blackPerCap**: Per capita income for African Americans (numeric)
- **indianPerCap**: Per capita income for Native Americans (numeric)
- **AsianPerCap**: Per capita income for Asians (numeric)
- **OtherPerCap**: Per capita income for other races (numeric)
- **HispPerCap**: Per capita income for Hispanics (numeric)
- **NumUnderPov**: Number of people under the poverty level (numeric)
- **PctPopUnderPov**: Percentage of population under the poverty level (numeric)
- **PctLess9thGrade**: Percentage of people with less than a 9th-grade education (numeric)
- **PctNotHSGrad**: Percentage of people who did not graduate high school (numeric)
- **PctBSorMore**: Percentage of people with a bachelor's degree or higher (numeric)
- **PctUnemployed**: Percentage of unemployed individuals (numeric)
- **PctEmploy**: Percentage of employed individuals (numeric)
- **PctEmplManu**: Percentage of people employed in manufacturing (numeric)
- **PctEmplProfServ**: Percentage of people employed in professional services (numeric)
- **PctOccupManu**: Percentage of workforce in manufacturing (numeric)
- **PctOccupMgmtProf**: Percentage of workforce in management or professional roles (numeric)
- **MalePctDivorce**: Percentage of divorced males (numeric)
- **MalePctNevMarr**: Percentage of never-married males (numeric)
- **FemalePctDiv**: Percentage of divorced females (numeric)
- **TotalPctDiv**: Total percentage of divorced individuals (numeric)
- **PersPerFam**: Mean number of people per family (numeric)
- **PctFam2Par**: Percentage of two-parent families (numeric)
- **PctKids2Par**: Percentage of children in two-parent households (numeric)
- **PctYoungKids2Par**: Percentage of children aged 0-4 in two-parent households (numeric)
- **PctTeen2Par**: Percentage of teenagers in two-parent households (numeric)
- **PctWorkMomYoungKids**: Percentage of working mothers with children under 6 (numeric)
- **PctWorkMom**: Percentage of working mothers with children under 18 (numeric)
- **NumIlleg**: Number of illegitimate births (numeric)
- **PctIlleg**: Percentage of illegitimate births (numeric)
- **NumImmig**: Number of immigrants (numeric)
- **PctImmigRecent**: Percentage of recent immigrants (within 3 years) (numeric)
- **PctImmigRec5**: Percentage of immigrants within the last 5 years (numeric)
- **PctImmigRec8**: Percentage of immigrants within the last 8 years (numeric)
- **PctImmigRec10**: Percentage of immigrants within the last 10 years (numeric)
- **PctRecentImmig**: Percentage of recent immigrants in the population (numeric)
- **PctRecImmig5**: Percentage of population who immigrated within the last 5 years (numeric)
- **PctRecImmig8**: Percentage of population who immigrated within the last 8 years (numeric)
- **PctRecImmig10**: Percentage of population who immigrated within the last 10 years (numeric)
- **PctSpeakEnglOnly**: Percentage of people who speak only English (numeric)
- **PctNotSpeakEnglWell**: Percentage of people who do not speak English well (numeric)
- **PctLargHouseFam**: Percentage of large family households (6+ members) (numeric)
- **PctLargHouseOccup**: Percentage of large occupied households (6+ members) (numeric)
- **PersPerOccupHous**: Mean number of people per occupied household (numeric)
- **PersPerOwnOccHous**: Mean number of people per owner-occupied household (numeric)
- **PersPerRentOccHous**: Mean number of people per rental household (numeric)
- **PctPersOwnOccup**: Percentage of people in owner-occupied households (numeric)
- **PctPersDenseHous**: Percentage of people living in dense housing (numeric)
- **PctHousLess3BR**: Percentage of housing units with fewer than 3 bedrooms (numeric)
- **MedNumBR**: Median number of bedrooms per household (numeric)
- **HousVacant**: Number of vacant households (numeric)
- **PctHousOccup**: Percentage of occupied housing (numeric)
- **PctHousOwnOcc**: Percentage of owner-occupied households (numeric)
- **PctVacantBoarded**: Percentage of vacant housing that is boarded up (numeric)
- **PctVacMore6Mos**: Percentage of housing vacant for more than 6 months (numeric)
- **MedYrHousBuilt**: Median year housing units were built (numeric)
- **PctHousNoPhone**: Percentage of housing units without a phone (numeric)
- **PctWOFullPlumb**: Percentage of housing units without complete plumbing (numeric)
- **OwnOccLowQuart**: Lower quartile value of owner-occupied homes (numeric)
- **OwnOccMedVal**: Median value of owner-occupied homes (numeric)
- **OwnOccHiQuart**: Upper quartile value of owner-occupied homes (numeric)
- **RentLowQ**: Lower quartile rent value (numeric)
- **RentMedian**: Median rent value (

numeric)
- **RentHighQ**: Upper quartile rent value (numeric)
- **MedRent**: Median gross rent (numeric)
- **MedRentPctHousInc**: Median rent as a percentage of household income (numeric)
- **MedOwnCostPctInc**: Median homeowner costs as a percentage of income (with a mortgage) (numeric)
- **MedOwnCostPctIncNoMtg**: Median homeowner costs as a percentage of income (no mortgage) (numeric)
- **NumInShelters**: Number of people in homeless shelters (numeric)
- **NumStreet**: Number of homeless people living on the street (numeric)
- **PctForeignBorn**: Percentage of foreign-born population (numeric)
- **PctBornSameState**: Percentage of people born in the same state as currently residing (numeric)
- **PctSameHouse85**: Percentage of people living in the same house since 1985 (numeric)
- **PctSameCity85**: Percentage of people living in the same city since 1985 (numeric)
- **PctSameState85**: Percentage of people living in the same state since 1985 (numeric)
- **LemasSwornFT**: Number of full-time sworn police officers (numeric)
- **LemasSwFTPerPop**: Full-time sworn police officers per 100,000 population (numeric)
- **LemasSwFTFieldOps**: Number of full-time sworn police officers in field operations (numeric)
- **LemasSwFTFieldPerPop**: Full-time sworn police officers in field operations per 100,000 population (numeric)
- **LemasTotalReq**: Total police requests (numeric)
- **LemasTotReqPerPop**: Total police requests per 100,000 population (numeric)
- **PolicReqPerOffic**: Police requests per officer (numeric)
- **PolicPerPop**: Police officers per 100,000 population (numeric)
- **RacialMatchCommPol**: Racial match between community and police force (numeric)
- **PctPolicWhite**: Percentage of Caucasian police officers (numeric)
- **PctPolicBlack**: Percentage of African American police officers (numeric)
- **PctPolicHisp**: Percentage of Hispanic police officers (numeric)
- **PctPolicAsian**: Percentage of Asian police officers (numeric)
- **PctPolicMinor**: Percentage of minority police officers (numeric)
- **OfficAssgnDrugUnits**: Number of officers assigned to drug units (numeric)
- **NumKindsDrugsSeiz**: Number of different kinds of drugs seized (numeric)
- **PolicAveOTWorked**: Average overtime worked by police officers (numeric)
- **LandArea**: Land area in square miles (numeric)
- **PopDens**: Population density per square mile (numeric)
- **PctUsePubTrans**: Percentage of people using public transportation for commuting (numeric)
- **PolicCars**: Number of police cars (numeric)
- **PolicOperBudg**: Police operating budget (numeric)
- **LemasPctPolicOnPatr**: Percentage of full-time sworn officers on patrol (numeric)
- **LemasGangUnitDeploy**: Gang unit deployment (0 = No, 1 = Yes, 0.5 = Part-time) (ordinal)
- **LemasPctOfficDrugUn**: Percentage of officers assigned to drug units (numeric)
- **PolicBudgPerPop**: Police budget per population (numeric)
- **ViolentCrimesPerPop**: Target variable: violent crimes per 100,000 population (numeric)

---

### Summary Statistics (For Key Variables)
Here are some summary statistics for key variables:
- **Population**: Min: 0, Max: 1, Mean: 0.06
- **Median Income**: Min: 0, Max: 1, Mean: 0.36
- **Percentage Unemployed**: Min: 0, Max: 1, Mean: 0.36
- **Violent Crimes Per Pop**: Min: 0, Max: 1, Mean: 0.24

---

### Citation Request
Please cite the following sources if you use this dataset:

- U. S. Department of Commerce, Bureau of the Census, **Census of Population and Housing 1990**.
- U.S. Department of Justice, Bureau of Justice Statistics, **Law Enforcement Management and Administrative Statistics (1992)**.
- U.S. Department of Justice, Federal Bureau of Investigation, **Crime in the United States (1995)**.
- Redmond, M.A. & Baveja, A. **A Data-Driven Software Tool for Enabling Cooperative Information Sharing Among Police Departments**. European Journal of Operational Research, 141 (2002), 660-678.
