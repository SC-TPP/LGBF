# Scottish Local Government Benchmark Framework Indicator Data Made Computer Accessible.

This repository contains the Jupyter Notebook used to transform the LGBF raw data file on the Improvement Services Public Website into a more computer friendly format meant for data/performance analysts to use with Business Intelligence tools such as PowerBI. It also contains the resulting data in csv format. Various iterations of these files have been provided to allow any users to choose the data format they wish to use as below.

### 1. Simple Dataset (one version for formatted text values and one for unformatted numerical values)
This contains the Code, Local Authority, GSS Code, Value, Numerator (where applicable) and Denominator (where applicable) of the indicator.

### 2. Rankings and Improvement Service Supplied Scottish Averages (one version for formatted text values and one for unformatted numerical values)
This contains the data in the simple dataset but also calculated rankings (both scottish and family group) for all indicators and the Scottish Average data supplied within the original raw data file.

### 3. Full Dataset (one version for formatted text values and one for unformatted numerical values)
This contains all of the above plus numerous other data fields as below : 

- Previous row of each indicator data as an object
- First collected row of each indicator data as an object
- Ranking Change Since Previous
- Ranking Change Since First Value
- Value Change Since Previous
- % Change Since Previous - Treating %ages as absolute change
- Value Change Since First Value
- % Change Since First Value - Treating %ages as absolute change
- Quartile Movement
- Scottish Averages
  - Average of Local Authority Real Values - ScotAv_LA_Real
  - Average of Local Authority Cash Values - ScotAv_LA_Cash
  - Sum of Real Numerators Divided by Sum of Real Denominators - ScotAv_NumDen_Real
  - Sum of Cash Numerators Divided by Sum of Cash Denominators - ScotAv_NumDen_Cash
  - Average of Local Authority Real Numerator Values - ScotAv_LA_Num_Real
  - Average of Local Authority Real Denominator Values - ScotAv_LA_Den_Real
  - Average of Local Authority Cash Numerator Values - ScotAv_LA_Num_Cash
  - Average of Local Authority Cash Denominator Values - ScotAv_LA_Den_Cash
  - Average Provided by the Improvement Service as part of the original file for Real Values - ScotAv_IS_Real
  - Average Provided by the Improvement Service as part of the original file for Cash Values - ScotAv_IS_Cash
- Family Group Averages
  - Average of Local Authority Real Values - FamilyAv_LA_Real
  - Average of Local Authority Cash Values - FamilyAv_LA_Cash
  - Sum of Real Numerators Divided by Sum of Real Denominators - FamilyAv_NumDen_Real
  - Sum of Cash Numerators Divided by Sum of Cash Denominators - FamilyAv_NumDen_Cash
  - Average of Local Authority Real Numerator Values - FamilyAv_LA_Num_Real
  - Average of Local Authority Real Denominator Values - FamilyAv_LA_Den_Real
  - Average of Local Authority Cash Numerator Values - FamilyAv_LA_Num_Cash
  - Average of Local Authority Cash Denominator Values - FamilyAv_LA_Den_Cash

In addition to this example files are provided that demonstrate how this data can be used within PowerBI to automate report creationn (both digital interactive reporting and A4 paginated reporting).

Any users who would like to contribute and improve this dataset should contact corporateperformance@stirling.gov.uk.

All data provided here is publically available on the Improvement Service's website. Any users should verify the validity of this data independently. There is no guarantee that the data transformations applied in the Notebook are correct (although I believe they are and have done some limited verification of this).

Data will be refreshed each time a new file is publically available on the Improvement Services Website.
