# Scottish Local Government Benchmark Framework Indicator Data Made Computer Accessible.

This repository contains the Jupyter Notebook used to transform the LGBF raw data file on the Improvement Services Public Website into a more computer friendly format meant for data/performance analysts to use with Business Intelligence tools such as PowerBI. It also contains the resulting data in csv format. 

All data provided here is publicly available on the Improvement Service's website. Any users should verify the validity of this data independently. There is no guarantee that the data transformations applied in the Notebook are correct (although I believe they are and have done some limited verification of this).

Data will be refreshed each time a new file is publically available on the Improvement Services Website.

The data files and the descriptors for the fields within are as follows.

### Indicator Data.csv
Main data file containing values, numerators, denominators, rankings and percentiles along with changes first and previous as json objects.

<details><summary>Field Details</summary>
    
- Key_CodePeriod
    >Concatenated Code and Period to create relationships to Scottish Averages and Scottish Values.
- Key_CodePeriodFamilyGroup
    >Concatenated Code, Period and Family Group to create a relationship to Family Averages.
- Local_Authority
- Code 
- Period
- Real_Value
- Real_Numerator
- Real_Denominator
- Cash_Value
- Cash_Numerator
- Cash_Denominator
- ScotRank
    >Scottish Ranking for each Local Authority within code and Period group based on the aim outlined in Indicator Information.csv. Goldilocks indicators are calculated as rank based on distance from mid point.
- ScotPct
    >Scottish Percentile calculated using the same methodology above.
- FamilyRank
    >Family Group Ranking for each Local Authority within code, Period and family group group based on the aim outlined in Indicator Information.csv. Goldilocks indicators are calculated as rank based on distance from mid point.
- FamilyPct
    >Family Group Percentile calculated using the same methodology above.
- Previous
    >Json object containing the previous rows value fields only; including ranks and percentiles (the first row of each local authority and code combination will be blank). Can be expanded by transforming the column type to Json within PowerQuery or PowerBI.
- First
    >Json object containing the first rows value fields only; including ranks and percentiles (the first row of each local authority and code combination will be blank). Can be expanded by transforming the column type to Json within PowerQuery or PowerBI.
- Changes
    >Json object containing changes from first and previous values as outlined below:
    - ScotRank_ChangeSincePrevious
    - ScotPct_ChangeSincePrevious
    - FamilyRank_ChangeSincePrevious
    - FamilyPct_ChangeSincePrevious
    - ScotRank_ChangeSinceFirst
    - ScotPct_ChangeSinceFirst
    - FamilyRank_ChangeSinceFirst
    - FamilyPct_ChangeSinceFirst
    - Real_Value_ChangeSincePrevious
    - Real_Numerator_ChangeSincePrevious
    - Real_Denominator_ChangeSincePrevious
    - Real_Value_ChangeSinceFirst
    - Real_Numerator_ChangeSinceFirst
    - Real_Denominator_ChangeSinceFirst
    - PercentChange_AimAdjusted_SincePrevious
        >An aim adjusted percentage change between two indicator values. There are two niche cases here. One where previous and current values are both 0 resulting in 0% in all cases. Another where only the previous value is 0 resulting in None being returned as it is not possible to calculate % change from 0. Having looked at the dataset this has only occured 3 times and only affects Orkney and Eilean Siar for CHN20b. Further to this changes in percentage indicators are calculated using 100 as a denominator rather than previous. This is to avodi situations where very small percentages return 1000% or more change (which for our purposes seemed unreasonable to report). Goldilocks indicators are handled by calculating distance from midpoint for current and previous and using these to calculate the percentage.
    - PercentChange_AimAdjusted_SinceFirst
        > An aim adjusted percentage change between two indicator values. There are two niche cases here. One where first and current values are both 0 resulting in 0% in all cases. Another where only the previous value is 0 resulting in None being returned as it is not possible to calculate % change from 0. Having looked at the dataset this has only occured 3 times and only affects Orkney and Eilean Siar for CHN20b. Further to this changes in percentage indicators are calculated using 100 as a denominator rather than previous. This is to avodi situations where very small percentages return 1000% or more change (which for our purposes seemed unreasonable to report). Goldilocks indicators are handled by calculating distance from midpoint for first and current and using these to calculate the percentage.
</details>

### Latest Values.csv
Slice of the main data file containing only rows for the most recent period of each Local Authority and Code combination.

<details><summary>Field Details</summary>
    
- Key_CodePeriod
    >Concatenated Code and Period to create relationships to Scottish Averages and Scottish Values.
- Key_CodePeriodLA
    >Concatenated Code Period and Local Authority to create relationships to the main data file.
- Key_CodePeriodFamilyGroup
    >Concatenated Code, Period and Family Group to create a relationship to Family Averages.
- LocalAuthority
- Code 
- Period
- Real_Value
- Real_Numerator
- Real_Denominator
- ScotRank
    >Scottish Ranking for each Local Authority within code and Period group based on the aim outlined in Indicator Information.csv. Goldilocks indicators are calculated as rank based on distance from mid point.
- ScotPct
    >Scottish Percentile calculated using the same methodology above.
- FamilyRank
    >Family Group Ranking for each Local Authority within code, Period and family group group based on the aim outlined in Indicator Information.csv. Goldilocks indicators are calculated as rank based on distance from mid point.
- FamilyPct
    >Family Group Percentile calculated using the same methodology above.
- Previous
    >Json object containing the previous rows value fields only; including ranks and percentiles (the first row of each local authority and code combination will be blank). Can be expanded by transforming the column type to Json within PowerQuery or PowerBI.
- First
    >Json object containing the first rows value fields only; including ranks and percentiles (the first row of each local authority and code combination will be blank). Can be expanded by transforming the column type to Json within PowerQuery or PowerBI.
- Changes
    >Json object containing changes from first and previous values as outlined below:
    - ScotRank_ChangeSincePrevious
    - ScotPct_ChangeSincePrevious
    - FamilyRank_ChangeSincePrevious
    - FamilyPct_ChangeSincePrevious
    - ScotRank_ChangeSinceFirst
    - ScotPct_ChangeSinceFirst
    - FamilyRank_ChangeSinceFirst
    - FamilyPct_ChangeSinceFirst
    - Real_Value_ChangeSincePrevious
    - Real_Numerator_ChangeSincePrevious
    - Real_Denominator_ChangeSincePrevious
    - Real_Value_ChangeSinceFirst
    - Real_Numerator_ChangeSinceFirst
    - Real_Denominator_ChangeSinceFirst
    - PercentChange_AimAdjusted_SincePrevious
        >An aim adjusted percentage change between two indicator values. There are two niche cases here. One where previous and current values are both 0 resulting in 0% in all cases. Another where only the previous value is 0 resulting in None being returned as it is not possible to calculate % change from 0. Having looked at the dataset this has only occured 3 times and only affects Orkney and Eilean Siar for CHN20b. Further to this changes in percentage indicators are calculated using 100 as a denominator rather than previous. This is to avoid situations where very small percentages return 1000% or more change (which for our purposes seemed unreasonable to report). Goldilocks indicators are handled by calculating distance from midpoint for current and previous and using these to calculate the percentage.
    - PercentChange_AimAdjusted_SinceFirst
        > An aim adjusted percentage change between two indicator values. There are two niche cases here. One where first and current values are both 0 resulting in 0% in all cases. Another where only the previous value is 0 resulting in None being returned as it is not possible to calculate % change from 0. Having looked at the dataset this has only occured 3 times and only affects Orkney and Eilean Siar for CHN20b. Further to this changes in percentage indicators are calculated using 100 as a denominator rather than previous. This is to avoid situations where very small percentages return 1000% or more change (which for our purposes seemed unreasonable to report). Goldilocks indicators are handled by calculating distance from midpoint for first and current and using these to calculate the percentage.
</details>

### Family Averages.csv
All Family Group Average types for all data fields avalilable

<details><summary>Field Details</summary>
    
- Key_CodePeriodFamily_Group
    > Concatenated Code, Period and Family Group to create a relationship to Indicator Data.
- Code
- Period
- Family_Group
    >Family Group Number for each data row. This is set up to select from the correct grouping type as per the indicator code.
- Real_Value_FG_Mean
    > Mean of Local Authority real values within each Family Group, Code and Period combination
- Real_Numerator_FG_Mean
    > Mean  of Local Authority real numerator values within each Family Group, Code and Period combination
- Real_Denominator_FG_Mean
    > Mean of Local Authority real denominator values within each Family Group, Code and Period combination
- Real_Value_FG_Median
    > Median of Local Authority real values within each Family Group, Code and Period combination
- Real_Numerator_FG_Median
    > Median of Local Authority real numerator values within each Family Group, Code and Period combination
- Real_Denominator_FG_Median
    > Median of Local Authority real denominator values within each Family Group, Code and Period combination
- Real_FG_NumDenAv
    > Average created by summing the real numerator values and denominator values for each Family Group, Code and Period combination and dividing them together appropriately.

</details>

### Scottish Averages.csv
All Family Group Average types for all data fields avalilable

<details><summary>Field Details</summary>
- Key_CodePeriod
    > Concatenated Code and Period to create a relationship to Indicator Data.
- Code
    > Corrected to be A-Z sortable.
- Period
- Real_Value_Scot_Mean
    > Mean of Local Authority real values within each Code and Period combination
- Real_Numerator_Scot_Mean
    > Mean of Local Authority real numerator values within each Code and Period combination
- Real_Denominator_Scot_Mean
    > Mean of Local Authority real denominator values within each Code and Period combination
- Real_Value_Scot_Median
    > Median of Local Authority real values within each Code and Period combination
- Real_Numerator_Scot_Median
    > Median of Local Authority real numerator values within each Code and Period combination
- Real_Denominator_Scot_Median
    > Median of Local Authority real denominator values within each Code and Period combination
- ScotAv_NumDen_Real
    > Average created by summing the real numerator values and denominator values for each Code and Period combination and dividing them together appropriately.

</details>

### Scottish Values.csv
Real and Cash values as provided by the Improvement Service. These have been removed from the raw data file for graphing purposes and included here separately. They can be joined back in any data model used for performance reporting if required.#

<details><summary>Field Details</summary>
    
- Key_CodePeriod
    > Concatenated Code and Period to create a relationship to Indicator Data.
- Code
    > Corrected to be A-Z sortable.
- Period
- Scot_Real_Value
- Scot_Real_Numerator
- Scot_Real_Denominator
</details>

### Family Groups.csv
Family Groups in a row based format. This was used within the transformation steps and may be useful when defining models.

<details><summary>Field Details</summary>

- Local_Authority
- Type
    > Type of grouping. Either "Environmental, Culture & Leisure, Economic Development, Corporate and Property indicators" or "Children, Social Work and Housing indicators"
- Family_Group
    > Family Group Number
</details>

### Indicator Information.csv
Indicator information used throughout transformation steps. Some of this information is from the LGBF metadata file where other parts are additional information necessary to transform the data that is not supplied by the Improvement Service.

<details><summary>Fields Details</summary>

- Title
    > Indicator title copied from the metadata file
- Code
    > Original code as provided in the raw data file
- Code_Sortable
    > A-Z sortable version of the code including a space for formatting in reports etc. e.g original : Env04a, sortable : Env 04a
- ReportingPeriod
    > Period data is reported over e.g Annual, 3 Yearly Aggregate etc.
- MeasureType
    > Measure type e.g Percentage, Rate per 100 etc.
- NumberFormat
    > Number format for use to create a user friendly text string that represents the number. e.g value : 1.23, value with number format applied : 1.23 Weeks. Can be used with Number.ToText in powerquery or powerbi to format the raw numbers in the data file.
- YMin
    > For graphing purposes the minimum value shown on the y axis - doesn't work with plotly but works for PowerBI and Excel based reporting
- YMax
    > For graphing purposes the maximum value shown on the y axis - doesn't work with plotly but works for PowerBI and Excel based reporting
- ISCategory
    > Category as supplied by the improvement service
- Committee
    > Stirling Council's reportable committee. Change these values as appropriate for your own council
- FamilyGrouping
    > Family group type for the indicator.
- StirlingService
    > Stirling Council's reportable service structure (semicolon delimited)
- Ranking_Type
    > Either Ascending (aim to minimise), Descending (aim to maximise) or Goldilocks (aim closest to defined mid-point)
- NumberFormat_NoText
    > Number format that can be used to round the value appropriately without adding string elements - doesn't work with plotly but works for PowerBI and Excel based reporting
- Source
    > Text Field containing the information from the LGBF metadata for the source of the data.
- Numerator_Multipier
    > Multiplier required to convert back numerator values that have been truncated into £000 or similar. These truncations do not provide valid data to create averages or to verify that the value is equal to the numerator divided by the denominator.
- Denominator_Multiplier
    > Multiplier required to convert back denominator values that have been truncated into £000 or similar. These truncations do not provide valid data to create averagesor or to verify that the value is equal to the numerator divided by the denominator.
- Ranking_GoldilocksMidpoint
    > Mid point for any goldilocks ranking or percentile calculations (if applicable)
- NumberFormat_Axis
- Format_Python
- FormatAxis_Python
- AdditionalAxisDenominator_Python
- FormatAxis_Plotly_Prefix
- FormatAxis_Plotly_Suffix
- ImgPxlWidth_Plotly
- ImgPxlHeight_Plotly
- SubGroup_PythonReport
- YMin_Plotly
- YMax_Plotly
</details>
<br>

# Notes on Further Development and Contributing
Example files will be provided that demonstrate how this data can be used within PowerBI to automate report creationn (both digital interactive reporting and A4 paginated reporting). In addition to this there will also be an excel file with a predefined datamodel using links to the files hosted here.

Any users who would like to contribute and improve this dataset should contact corporateperformance@stirling.gov.uk.

If any users have additional fields they would like to be added again please contact corporateperformance@stirling.gov.uk and we will attempt to provide these (if resource allows).