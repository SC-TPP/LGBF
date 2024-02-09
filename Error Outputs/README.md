# Known Errors
There are a number of know errors that will be present in these files. These errors exist within the original data and are not a result of the code used to transform it. Small variances due to rounding errors present in the raw data file provided by the Improvement Service have been filtered out. Only differences >2% will be contained in this output file.

## Corp 03c
> The calculation used to create corp 03c value is not simply a/b the values the Improvement Service provides for numerator and denominator are not numerators or denominators they are instead values used in a more complicated calculation. This will appear in the error output but is not a valid entry.

## Corp 04
### Clackmannanshire - Cash and Real - Annual - 2019-20
> There is a ∼75% difference between the result of dividing the numerator and denominator and the value stated. This is existant in the raw data file provided by the Improvement Service.

## C&L 03
### Argyll & Bute - Cash and Real - Annual - 2018-19,2019-21,2021-22
> Differences between the result of dividing the numerator and denominator and the value stated as below. Possibly the result of rounding but is outside the 2% tollerance set.

|DataType   |Period |LGBF Value|Numerator|Denominator|Calulation Value|Percent Difference|
|-----------|-------|----------|---------|-----------|----------------|------------------|
|Cash_Annual|2018-19|0.06      |16000    |289218     |0.055321591     |∼7.8%             |
|Cash_Annual|2019-20|0.05      |16000    |305841     |0.052314765     |∼-4.63%           |
|Cash_Annual|2021-22|0.1       |16000    |164337     |0.097360911     |∼2.64%            |
|Real_Annual|2018-19|0.0685    |18275.5  |289218     |0.063189359     |∼7.75%            |
|Real_Annual|2019-20|0.0558    |17854    |305841     |0.058376738     |∼-4.62%           |
|Real_Annual|2021-22|0.1066    |17052.2  |164337     |0.103763608     |∼2.66%            |

### West Dunbartonshire - Cash and Real - 2022-23
> Difference between the result of dividing the numerator and denominator and the value stated as below. Possibly the result of rounding but is outside the 2% tollerance set.

|DataType   |Period |LGBF Value|Numerator|Denominator|Calulation Value|Percent Difference|
|-----------|-------|----------|---------|-----------|----------------|------------------|
|Cash_Annual|2022-23|0.01      |1000     |104942     |0.009529073     |∼4.71%            |
|Real_Annual|2022-23|0.01      |1000     |104942     |0.009529073     |∼4.71%            |

## CLIM 05 - Various Local Authority Areas - Cash and Real - Annual - 2017-18, 2018-19
> Various Local Authority Areas have differences between the result of dividing the numerator and denominator and the value stated as below. Some significant.

|DataType   |Period |Local Authority    |LGBF Value|Numerator  |Denominator|Calculation Value|Percent Difference|
|-----------|-------|-------------------|----------|-----------|-----------|-----------------|------------------|
|Cash_Annual|2017-18|Aberdeen City      |51.8      |13592600   |228800     |59.40821678      |-14.69%           |
|Cash_Annual|2018-19|Aberdeen City      |52.3      |13125900   |227560     |57.68105115      |-10.29%           |
|Cash_Annual|2017-18|Aberdeenshire      |52.2      |14292830   |261800     |54.59446142      |-4.59%            |
|Cash_Annual|2018-19|Aberdeenshire      |56.8      |19798655.01|261470     |75.72056071      |-33.31%           |
|Cash_Annual|2018-19|Angus              |64.5      |6044610    |116040     |52.09074457      |19.24%            |
|Cash_Annual|2018-19|Argyll & Bute      |86.8      |6044610    |86260      |70.07431022      |19.27%            |
|Cash_Annual|2017-18|Clackmannanshire   |48.2      |2811450    |51450      |54.64431487      |-13.37%           |
|Cash_Annual|2018-19|Clackmannanshire   |41.5      |2473750    |51400      |48.12743191      |-15.97%           |
|Cash_Annual|2017-18|Dumfries & Galloway|45.6      |7137240    |149200     |47.83672922      |-4.91%            |
|Cash_Annual|2018-19|Dumfries & Galloway|49.4      |6570350    |148790     |44.1585456       |10.61%            |
|Cash_Annual|2018-19|Dundee City        |98.8      |11920150   |148750     |80.13546218      |18.89%            |
|Cash_Annual|2017-18|East Ayrshire      |67.8      |8459630    |121940     |69.37534853      |-2.32%            |
|Cash_Annual|2017-18|East Dunbartonshire|54.5      |6376740    |108130     |58.97290299      |-8.21%            |
|Cash_Annual|2018-19|East Dunbartonshire|57.1      |5783920    |108330     |53.39167359      |6.49%             |
|Cash_Annual|2018-19|East Lothian       |54.1      |5453160    |105790     |51.54702713      |4.72%             |
|Cash_Annual|2017-18|East Renfrewshire  |116.4     |7821890    |94760      |82.54421697      |29.09%            |
|Cash_Annual|2018-19|East Renfrewshire  |86.9      |7155980    |95170      |75.19155196      |13.47%            |
|Cash_Annual|2017-18|Edinburgh City     |57.7      |32292030   |513210     |62.92166949      |-9.05%            |
|Cash_Annual|2017-18|Falkirk            |62.2      |11834670   |160130     |73.90663836      |-18.82%           |
|Cash_Annual|2018-19|Falkirk            |66.3      |11281900   |160340     |70.362355        |-6.13%            |
|Cash_Annual|2017-18|Fife               |47.2      |22697590   |371410     |61.11195175      |-29.47%           |
|Cash_Annual|2017-18|Glasgow City       |68.2      |51111930   |621020     |82.30319474      |-20.68%           |
|Cash_Annual|2017-18|Highland           |25.4      |6890240    |235180     |29.2977294       |-15.35%           |
|Cash_Annual|2018-19|Highland           |22.3      |6299350    |235540     |26.74428972      |-19.93%           |
|Cash_Annual|2017-18|Inverclyde         |62.8      |5270230    |78760      |66.91505841      |-6.55%            |
|Cash_Annual|2018-19|Inverclyde         |69.4      |4950700    |78150      |63.34868842      |8.72%             |
|Cash_Annual|2017-18|Midlothian         |94.6      |9094370    |90090      |100.9476079      |-6.71%            |
|Cash_Annual|2018-19|Midlothian         |96.6      |7929730    |91340      |86.81552441      |10.13%            |
|Cash_Annual|2017-18|Moray              |45.1      |4612280    |95780      |48.1549384       |-6.77%            |
|Cash_Annual|2018-19|Moray              |49        |4197190    |95520      |43.94043132      |10.33%            |
|Cash_Annual|2017-18|North Ayrshire     |69.5      |11862910   |135790     |87.36217689      |-25.70%           |
|Cash_Annual|2018-19|North Ayrshire     |74.3      |9765040    |135280     |72.18391484      |2.85%             |
|Cash_Annual|2017-18|North Lanarkshire  |73.1      |30438340   |339960     |89.53506295      |-22.48%           |
|Cash_Annual|2017-18|Perth & Kinross    |47.2      |7601540    |151100     |50.30800794      |-6.58%            |
|Cash_Annual|2018-19|Perth & Kinross    |48.7      |6627030    |151290     |43.80348999      |10.05%            |
|Cash_Annual|2018-19|Renfrewshire       |46        |7967360    |177790     |44.81331908      |2.58%             |
|Cash_Annual|2017-18|Scottish Borders   |39.3      |3324220    |115020     |28.90123457      |26.46%            |
|Cash_Annual|2018-19|Scottish Borders   |40        |3423480    |115270     |29.69966166      |25.75%            |
|Cash_Annual|2017-18|South Ayrshire     |74.2      |8144240    |112680     |72.27760028      |2.59%             |
|Cash_Annual|2018-19|South Ayrshire     |65.5      |8232800    |112550     |73.14793425      |-11.68%           |
|Cash_Annual|2018-19|Stirling           |48.1      |4301040    |94330      |45.59567476      |5.21%             |
|Cash_Annual|2017-18|West Dunbartonshire|56        |4885420    |89610      |54.51869211      |2.65%             |
|Cash_Annual|2018-19|West Dunbartonshire|54.5      |4635200    |89130      |52.00493661      |4.58%             |
|Cash_Annual|2017-18|West Lothian       |66.3      |12647590   |181310     |69.75671502      |-5.21%            |
|Cash_Annual|2018-19|West Lothian       |64.2      |11301250   |182140     |62.04705172      |3.35%             |
|Real_Annual|2017-18|Aberdeen City      |51.8      |13592600   |228800     |59.40821678      |-14.69%           |
|Real_Annual|2018-19|Aberdeen City      |52.3      |13125900   |227560     |57.68105115      |-10.29%           |
|Real_Annual|2017-18|Aberdeenshire      |52.2      |14292830   |261800     |54.59446142      |-4.59%            |
|Real_Annual|2018-19|Aberdeenshire      |56.8      |19798655.01|261470     |75.72056071      |-33.31%           |
|Real_Annual|2018-19|Angus              |64.5      |6044610    |116040     |52.09074457      |19.24%            |
|Real_Annual|2018-19|Argyll & Bute      |86.8      |6044610    |86260      |70.07431022      |19.27%            |
|Real_Annual|2017-18|Clackmannanshire   |48.2      |2811450    |51450      |54.64431487      |-13.37%           |
|Real_Annual|2018-19|Clackmannanshire   |41.5      |2473750    |51400      |48.12743191      |-15.97%           |
|Real_Annual|2017-18|Dumfries & Galloway|45.6      |7137240    |149200     |47.83672922      |-4.91%            |
|Real_Annual|2018-19|Dumfries & Galloway|49.4      |6570350    |148790     |44.1585456       |10.61%            |
|Real_Annual|2018-19|Dundee City        |98.8      |11920150   |148750     |80.13546218      |18.89%            |
|Real_Annual|2017-18|East Ayrshire      |67.8      |8459630    |121940     |69.37534853      |-2.32%            |
|Real_Annual|2017-18|East Dunbartonshire|54.5      |6376740    |108130     |58.97290299      |-8.21%            |
|Real_Annual|2018-19|East Dunbartonshire|57.1      |5783920    |108330     |53.39167359      |6.49%             |
|Real_Annual|2018-19|East Lothian       |54.1      |5453160    |105790     |51.54702713      |4.72%             |
|Real_Annual|2017-18|East Renfrewshire  |116.4     |7821890    |94760      |82.54421697      |29.09%            |
|Real_Annual|2018-19|East Renfrewshire  |86.9      |7155980    |95170      |75.19155196      |13.47%            |
|Real_Annual|2017-18|Edinburgh City     |57.7      |32292030   |513210     |62.92166949      |-9.05%            |
|Real_Annual|2017-18|Falkirk            |62.2      |11834670   |160130     |73.90663836      |-18.82%           |
|Real_Annual|2018-19|Falkirk            |66.3      |11281900   |160340     |70.362355        |-6.13%            |
|Real_Annual|2017-18|Fife               |47.2      |22697590   |371410     |61.11195175      |-29.47%           |
|Real_Annual|2017-18|Glasgow City       |68.2      |51111930   |621020     |82.30319474      |-20.68%           |
|Real_Annual|2017-18|Highland           |25.4      |6890240    |235180     |29.2977294       |-15.35%           |
|Real_Annual|2018-19|Highland           |22.3      |6299350    |235540     |26.74428972      |-19.93%           |
|Real_Annual|2017-18|Inverclyde         |62.8      |5270230    |78760      |66.91505841      |-6.55%            |
|Real_Annual|2018-19|Inverclyde         |69.4      |4950700    |78150      |63.34868842      |8.72%             |
|Real_Annual|2017-18|Midlothian         |94.6      |9094370    |90090      |100.9476079      |-6.71%            |
|Real_Annual|2018-19|Midlothian         |96.6      |7929730    |91340      |86.81552441      |10.13%            |
|Real_Annual|2017-18|Moray              |45.1      |4612280    |95780      |48.1549384       |-6.77%            |
|Real_Annual|2018-19|Moray              |49        |4197190    |95520      |43.94043132      |10.33%            |
|Real_Annual|2017-18|North Ayrshire     |69.5      |11862910   |135790     |87.36217689      |-25.70%           |
|Real_Annual|2018-19|North Ayrshire     |74.3      |9765040    |135280     |72.18391484      |2.85%             |
|Real_Annual|2017-18|North Lanarkshire  |73.1      |30438340   |339960     |89.53506295      |-22.48%           |
|Real_Annual|2017-18|Perth & Kinross    |47.2      |7601540    |151100     |50.30800794      |-6.58%            |
|Real_Annual|2018-19|Perth & Kinross    |48.7      |6627030    |151290     |43.80348999      |10.05%            |
|Real_Annual|2018-19|Renfrewshire       |46        |7967360    |177790     |44.81331908      |2.58%             |
|Real_Annual|2017-18|Scottish Borders   |39.3      |3324220    |115020     |28.90123457      |26.46%            |
|Real_Annual|2018-19|Scottish Borders   |40        |3423480    |115270     |29.69966166      |25.75%            |
|Real_Annual|2017-18|South Ayrshire     |74.2      |8144240    |112680     |72.27760028      |2.59%             |
|Real_Annual|2018-19|South Ayrshire     |65.5      |8232800    |112550     |73.14793425      |-11.68%           |
|Real_Annual|2018-19|Stirling           |48.1      |4301040    |94330      |45.59567476      |5.21%             |
|Real_Annual|2017-18|West Dunbartonshire|56        |4885420    |89610      |54.51869211      |2.65%             |
|Real_Annual|2018-19|West Dunbartonshire|54.5      |4635200    |89130      |52.00493661      |4.58%             |
|Real_Annual|2017-18|West Lothian       |66.3      |12647590   |181310     |69.75671502      |-5.21%            |
|Real_Annual|2018-19|West Lothian       |64.2      |11301250   |182140     |62.04705172      |3.35%             |

## CORP 09 - Cash and Real - Quarterly - 2018-19 (Q2,Q3,Q4), 2019-20 (Q1,Q2,Q3,Q4), 2020-21 (Q1,Q2,Q3,Q4), 2021-22 (Q1,Q2,Q3,Q4), 2022-23 (Q1,Q2,Q3,Q4), 2023-24 (Q1)
> Various Local Authority Areas have differences between the result of dividing the numerator and denominator and the value stated as below. Some significant. Possibly due to obfuscated Numerator and Denominator values for data confidentiality reasons.

|DataType      |Period    |Local Authority  |LGBF Value|Numerator|Denominator|Calculation Value|Percent Difference|
|--------------|----------|-----------------|----------|---------|-----------|-----------------|------------------|
|Cash_Quarterly|2018-19;Q2|Orkney Islands   |0.94      |15       |20         |0.75             |20.21%            |
|Cash_Quarterly|2018-19;Q2|Shetland Islands |0.76      |25       |35         |0.714285714      |6.02%             |
|Cash_Quarterly|2018-19;Q3|East Renfrewshire|0.96      |130      |140        |0.928571429      |3.27%             |
|Cash_Quarterly|2018-19;Q4|Orkney Islands   |0.96      |25       |25         |1                |-4.17%            |
|Cash_Quarterly|2019-20;Q1|Eilean Siar      |0.91      |30       |35         |0.857142857      |5.81%             |
|Cash_Quarterly|2019-20;Q1|Shetland Islands |0.54      |30       |60         |0.5              |7.41%             |
|Cash_Quarterly|2019-20;Q2|Eilean Siar      |0.98      |45       |45         |1                |-2.04%            |
|Cash_Quarterly|2019-20;Q2|Shetland Islands |0.47      |30       |60         |0.5              |-6.38%            |
|Cash_Quarterly|2019-20;Q3|East Renfrewshire|0.99      |160      |165        |0.96969697       |2.05%             |
|Cash_Quarterly|2019-20;Q3|Eilean Siar      |0.98      |60       |60         |1                |-2.04%            |
|Cash_Quarterly|2019-20;Q3|Shetland Islands |0.57      |30       |55         |0.545454545      |4.31%             |
|Cash_Quarterly|2019-20;Q4|Shetland Islands |0.63      |30       |50         |0.6              |4.76%             |
|Cash_Quarterly|2020-21;Q1|Eilean Siar      |1         |65       |70         |0.928571429      |7.14%             |
|Cash_Quarterly|2020-21;Q1|Shetland Islands |0.43      |15       |30         |0.5              |-16.28%           |
|Cash_Quarterly|2020-21;Q2|East Renfrewshire|1         |150      |155        |0.967741935      |3.23%             |
|Cash_Quarterly|2020-21;Q2|Eilean Siar      |0.98      |65       |65         |1                |-2.04%            |
|Cash_Quarterly|2020-21;Q2|Shetland Islands |0.62      |15       |20         |0.75             |-20.97%           |
|Cash_Quarterly|2020-21;Q3|Eilean Siar      |0.98      |60       |65         |0.923076923      |5.81%             |
|Cash_Quarterly|2020-21;Q3|Shetland Islands |0.45      |10       |20         |0.5              |-11.11%           |
|Cash_Quarterly|2020-21;Q4|Eilean Siar      |0.99      |80       |85         |0.941176471      |4.93%             |
|Cash_Quarterly|2020-21;Q4|Shetland Islands |0.7       |25       |35         |0.714285714      |-2.04%            |
|Cash_Quarterly|2021-22;Q1|Eilean Siar      |1         |75       |80         |0.9375           |6.25%             |
|Cash_Quarterly|2021-22;Q1|Shetland Islands |0.68      |25       |35         |0.714285714      |-5.04%            |
|Cash_Quarterly|2021-22;Q2|Eilean Siar      |0.97      |60       |60         |1                |-3.09%            |
|Cash_Quarterly|2021-22;Q2|Shetland Islands |0.64      |15       |30         |0.5              |21.88%            |
|Cash_Quarterly|2021-22;Q3|Shetland Islands |0.85      |20       |25         |0.8              |5.88%             |
|Cash_Quarterly|2021-22;Q4|Orkney Islands   |0.96      |25       |25         |1                |-4.17%            |
|Cash_Quarterly|2022-23;Q1|Orkney Islands   |0.95      |20       |20         |1                |-5.26%            |
|Cash_Quarterly|2022-23;Q1|Shetland Islands |0.6       |25       |40         |0.625            |-4.17%            |
|Cash_Quarterly|2022-23;Q2|Shetland Islands |0.54      |15       |30         |0.5              |7.41%             |
|Cash_Quarterly|2022-23;Q3|Eilean Siar      |0.98      |60       |60         |1                |-2.04%            |
|Cash_Quarterly|2022-23;Q3|Shetland Islands |0.82      |30       |40         |0.75             |8.54%             |
|Cash_Quarterly|2022-23;Q4|Shetland Islands |0.81      |25       |30         |0.833333333      |-2.88%            |
|Cash_Quarterly|2023-24;Q1|Orkney Islands   |0.88      |15       |15         |1                |-13.64%           |
|Cash_Quarterly|2023-24;Q1|Shetland Islands |1         |10       |15         |0.666666667      |33.33%            |
|Real_Quarterly|2018-19;Q2|Orkney Islands   |0.94      |15       |20         |0.75             |20.21%            |
|Real_Quarterly|2018-19;Q2|Shetland Islands |0.76      |25       |35         |0.714285714      |6.02%             |
|Real_Quarterly|2018-19;Q3|East Renfrewshire|0.96      |130      |140        |0.928571429      |3.27%             |
|Real_Quarterly|2018-19;Q4|Orkney Islands   |0.96      |25       |25         |1                |-4.17%            |
|Real_Quarterly|2019-20;Q1|Eilean Siar      |0.91      |30       |35         |0.857142857      |5.81%             |
|Real_Quarterly|2019-20;Q1|Shetland Islands |0.54      |30       |60         |0.5              |7.41%             |
|Real_Quarterly|2019-20;Q2|Eilean Siar      |0.98      |45       |45         |1                |-2.04%            |
|Real_Quarterly|2019-20;Q2|Shetland Islands |0.47      |30       |60         |0.5              |-6.38%            |
|Real_Quarterly|2019-20;Q3|East Renfrewshire|0.99      |160      |165        |0.96969697       |2.05%             |
|Real_Quarterly|2019-20;Q3|Eilean Siar      |0.98      |60       |60         |1                |-2.04%            |
|Real_Quarterly|2019-20;Q3|Shetland Islands |0.57      |30       |55         |0.545454545      |4.31%             |
|Real_Quarterly|2019-20;Q4|Shetland Islands |0.63      |30       |50         |0.6              |4.76%             |
|Real_Quarterly|2020-21;Q1|Eilean Siar      |1         |65       |70         |0.928571429      |7.14%             |
|Real_Quarterly|2020-21;Q1|Shetland Islands |0.43      |15       |30         |0.5              |-16.28%           |
|Real_Quarterly|2020-21;Q2|East Renfrewshire|1         |150      |155        |0.967741935      |3.23%             |
|Real_Quarterly|2020-21;Q2|Eilean Siar      |0.98      |65       |65         |1                |-2.04%            |
|Real_Quarterly|2020-21;Q2|Shetland Islands |0.62      |15       |20         |0.75             |-20.97%           |
|Real_Quarterly|2020-21;Q3|Eilean Siar      |0.98      |60       |65         |0.923076923      |5.81%             |
|Real_Quarterly|2020-21;Q3|Shetland Islands |0.45      |10       |20         |0.5              |-11.11%           |
|Real_Quarterly|2020-21;Q4|Eilean Siar      |0.99      |80       |85         |0.941176471      |4.93%             |
|Real_Quarterly|2020-21;Q4|Shetland Islands |0.7       |25       |35         |0.714285714      |-2.04%            |
|Real_Quarterly|2021-22;Q1|Eilean Siar      |1         |75       |80         |0.9375           |6.25%             |
|Real_Quarterly|2021-22;Q1|Shetland Islands |0.68      |25       |35         |0.714285714      |-5.04%            |
|Real_Quarterly|2021-22;Q2|Eilean Siar      |0.97      |60       |60         |1                |-3.09%            |
|Real_Quarterly|2021-22;Q2|Shetland Islands |0.64      |15       |30         |0.5              |21.88%            |
|Real_Quarterly|2021-22;Q3|Shetland Islands |0.85      |20       |25         |0.8              |5.88%             |
|Real_Quarterly|2021-22;Q4|Orkney Islands   |0.96      |25       |25         |1                |-4.17%            |
|Real_Quarterly|2022-23;Q1|Orkney Islands   |0.95      |20       |20         |1                |-5.26%            |
|Real_Quarterly|2022-23;Q1|Shetland Islands |0.6       |25       |40         |0.625            |-4.17%            |
|Real_Quarterly|2022-23;Q2|Shetland Islands |0.54      |15       |30         |0.5              |7.41%             |
|Real_Quarterly|2022-23;Q3|Eilean Siar      |0.98      |60       |60         |1                |-2.04%            |
|Real_Quarterly|2022-23;Q3|Shetland Islands |0.82      |30       |40         |0.75             |8.54%             |
|Real_Quarterly|2022-23;Q4|Shetland Islands |0.81      |25       |30         |0.833333333      |-2.88%            |
|Real_Quarterly|2023-24;Q1|Orkney Islands   |0.88      |15       |15         |1                |-13.64%           |
|Real_Quarterly|2023-24;Q1|Shetland Islands |1         |10       |15         |0.666666667      |33.33%            |

## CORP 10 - Cash and Real - Quarterly - 2018-19 (Q2,Q3,Q4), 2019-20 (Q1,Q2,Q3,Q4), 2020-21 (Q1,Q2,Q3,Q4), 2021-22 (Q1,Q2,Q3,Q4), 2022-23 (Q1,Q2,Q3,Q4), 2023-24 (Q1)
> Various Local Authority Areas have differences between the result of dividing the numerator and denominator and the value stated as below. Some significant. Possibly due to obfuscated Numerator and Denominator values for data confidentiality reasons.

|DataType      |Period    |Local Authority    |LGBF Value|Numerator|Denominator|Calculation Value|Percent Difference|
|--------------|----------|-------------------|----------|---------|-----------|-----------------|------------------|
|Cash_Quarterly|2018-19;Q1|East Renfrewshire  |0.88      |90       |105        |0.857142857      |2.60%             |
|Cash_Quarterly|2018-19;Q1|Orkney Islands     |0.75      |5        |10         |0.5              |33.33%            |
|Cash_Quarterly|2018-19;Q1|Shetland Islands   |0.86      |25       |30         |0.833333333      |3.10%             |
|Cash_Quarterly|2018-19;Q1|Stirling           |0.67      |180      |275        |0.654545455      |2.31%             |
|Cash_Quarterly|2018-19;Q2|Orkney Islands     |0.61      |10       |20         |0.5              |18.03%            |
|Cash_Quarterly|2018-19;Q2|Shetland Islands   |0.88      |20       |25         |0.8              |9.09%             |
|Cash_Quarterly|2018-19;Q3|Clackmannanshire   |1         |215      |220        |0.977272727      |2.27%             |
|Cash_Quarterly|2018-19;Q3|Eilean Siar        |0.96      |20       |25         |0.8              |16.67%            |
|Cash_Quarterly|2018-19;Q3|Orkney Islands     |0.77      |25       |30         |0.833333333      |-8.23%            |
|Cash_Quarterly|2018-19;Q4|Orkney Islands     |0.68      |15       |20         |0.75             |-10.29%           |
|Cash_Quarterly|2018-19;Q4|Shetland Islands   |0.71      |20       |30         |0.666666667      |6.10%             |
|Cash_Quarterly|2019-20;Q1|Eilean Siar        |0.96      |25       |25         |1                |-4.17%            |
|Cash_Quarterly|2019-20;Q1|Shetland Islands   |0.91      |20       |25         |0.8              |12.09%            |
|Cash_Quarterly|2019-20;Q2|Orkney Islands     |0.94      |15       |15         |1                |-6.38%            |
|Cash_Quarterly|2019-20;Q2|Shetland Islands   |0.69      |20       |30         |0.666666667      |3.38%             |
|Cash_Quarterly|2019-20;Q3|Shetland Islands   |0.77      |25       |30         |0.833333333      |-8.23%            |
|Cash_Quarterly|2019-20;Q4|East Dunbartonshire|0.99      |160      |165        |0.96969697       |2.05%             |
|Cash_Quarterly|2019-20;Q4|Eilean Siar        |0.82      |20       |20         |1                |-21.95%           |
|Cash_Quarterly|2019-20;Q4|Orkney Islands     |0.93      |25       |30         |0.833333333      |10.39%            |
|Cash_Quarterly|2019-20;Q4|Shetland Islands   |0.9       |25       |30         |0.833333333      |7.41%             |
|Cash_Quarterly|2020-21;Q1|Orkney Islands     |0.96      |25       |30         |0.833333333      |13.19%            |
|Cash_Quarterly|2020-21;Q1|Shetland Islands   |0.79      |10       |15         |0.666666667      |15.61%            |
|Cash_Quarterly|2020-21;Q2|East Dunbartonshire|0.98      |155      |155        |1                |-2.04%            |
|Cash_Quarterly|2020-21;Q2|East Renfrewshire  |0.98      |90       |90         |1                |-2.04%            |
|Cash_Quarterly|2020-21;Q2|Orkney Islands     |0.96      |25       |25         |1                |-4.17%            |
|Cash_Quarterly|2020-21;Q2|Shetland Islands   |0.8       |10       |15         |0.666666667      |16.67%            |
|Cash_Quarterly|2020-21;Q3|Eilean Siar        |0.93      |25       |30         |0.833333333      |10.39%            |
|Cash_Quarterly|2020-21;Q3|Orkney Islands     |0.98      |40       |45         |0.888888889      |9.30%             |
|Cash_Quarterly|2020-21;Q4|Argyll & Bute      |1         |235      |240        |0.979166667      |2.08%             |
|Cash_Quarterly|2020-21;Q4|Eilean Siar        |0.95      |35       |35         |1                |-5.26%            |
|Cash_Quarterly|2020-21;Q4|Shetland Islands   |0.71      |25       |40         |0.625            |11.97%            |
|Cash_Quarterly|2021-22;Q1|Orkney Islands     |0.97      |30       |30         |1                |-3.09%            |
|Cash_Quarterly|2021-22;Q1|Shetland Islands   |0.77      |15       |20         |0.75             |2.60%             |
|Cash_Quarterly|2021-22;Q2|Dumfries & Galloway|0.36      |200      |570        |0.350877193      |2.53%             |
|Cash_Quarterly|2021-22;Q2|East Dunbartonshire|0.98      |160      |160        |1                |-2.04%            |
|Cash_Quarterly|2021-22;Q2|Eilean Siar        |0.97      |35       |35         |1                |-3.09%            |
|Cash_Quarterly|2021-22;Q2|Shetland Islands   |0.76      |25       |35         |0.714285714      |6.02%             |
|Cash_Quarterly|2021-22;Q3|Eilean Siar        |0.98      |40       |45         |0.888888889      |9.30%             |
|Cash_Quarterly|2021-22;Q3|Shetland Islands   |0.74      |25       |35         |0.714285714      |3.47%             |
|Cash_Quarterly|2022-23;Q1|Orkney Islands     |0.95      |35       |35         |1                |-5.26%            |
|Cash_Quarterly|2022-23;Q1|Shetland Islands   |0.58      |20       |30         |0.666666667      |-14.94%           |
|Cash_Quarterly|2022-23;Q2|East Dunbartonshire|0.98      |165      |165        |1                |-2.04%            |
|Cash_Quarterly|2022-23;Q2|Shetland Islands   |0.74      |25       |35         |0.714285714      |3.47%             |
|Cash_Quarterly|2022-23;Q3|Eilean Siar        |0.94      |35       |35         |1                |-6.38%            |
|Cash_Quarterly|2022-23;Q3|Shetland Islands   |0.69      |20       |30         |0.666666667      |3.38%             |
|Cash_Quarterly|2022-23;Q4|East Renfrewshire  |0.98      |175      |175        |1                |-2.04%            |
|Cash_Quarterly|2022-23;Q4|Eilean Siar        |0.97      |35       |35         |1                |-3.09%            |
|Cash_Quarterly|2022-23;Q4|Shetland Islands   |0.67      |10       |20         |0.5              |25.37%            |
|Real_Quarterly|2018-19;Q1|East Renfrewshire  |0.88      |90       |105        |0.857142857      |2.60%             |
|Real_Quarterly|2018-19;Q1|Orkney Islands     |0.75      |5        |10         |0.5              |33.33%            |
|Real_Quarterly|2018-19;Q1|Shetland Islands   |0.86      |25       |30         |0.833333333      |3.10%             |
|Real_Quarterly|2018-19;Q1|Stirling           |0.67      |180      |275        |0.654545455      |2.31%             |
|Real_Quarterly|2018-19;Q2|Orkney Islands     |0.61      |10       |20         |0.5              |18.03%            |
|Real_Quarterly|2018-19;Q2|Shetland Islands   |0.88      |20       |25         |0.8              |9.09%             |
|Real_Quarterly|2018-19;Q3|Clackmannanshire   |1         |215      |220        |0.977272727      |2.27%             |
|Real_Quarterly|2018-19;Q3|Eilean Siar        |0.96      |20       |25         |0.8              |16.67%            |
|Real_Quarterly|2018-19;Q3|Orkney Islands     |0.77      |25       |30         |0.833333333      |-8.23%            |
|Real_Quarterly|2018-19;Q4|Orkney Islands     |0.68      |15       |20         |0.75             |-10.29%           |
|Real_Quarterly|2018-19;Q4|Shetland Islands   |0.71      |20       |30         |0.666666667      |6.10%             |
|Real_Quarterly|2019-20;Q1|Eilean Siar        |0.96      |25       |25         |1                |-4.17%            |
|Real_Quarterly|2019-20;Q1|Shetland Islands   |0.91      |20       |25         |0.8              |12.09%            |
|Real_Quarterly|2019-20;Q2|Orkney Islands     |0.94      |15       |15         |1                |-6.38%            |
|Real_Quarterly|2019-20;Q2|Shetland Islands   |0.69      |20       |30         |0.666666667      |3.38%             |
|Real_Quarterly|2019-20;Q3|Shetland Islands   |0.77      |25       |30         |0.833333333      |-8.23%            |
|Real_Quarterly|2019-20;Q4|East Dunbartonshire|0.99      |160      |165        |0.96969697       |2.05%             |
|Real_Quarterly|2019-20;Q4|Eilean Siar        |0.82      |20       |20         |1                |-21.95%           |
|Real_Quarterly|2019-20;Q4|Orkney Islands     |0.93      |25       |30         |0.833333333      |10.39%            |
|Real_Quarterly|2019-20;Q4|Shetland Islands   |0.9       |25       |30         |0.833333333      |7.41%             |
|Real_Quarterly|2020-21;Q1|Orkney Islands     |0.96      |25       |30         |0.833333333      |13.19%            |
|Real_Quarterly|2020-21;Q1|Shetland Islands   |0.79      |10       |15         |0.666666667      |15.61%            |
|Real_Quarterly|2020-21;Q2|East Dunbartonshire|0.98      |155      |155        |1                |-2.04%            |
|Real_Quarterly|2020-21;Q2|East Renfrewshire  |0.98      |90       |90         |1                |-2.04%            |
|Real_Quarterly|2020-21;Q2|Orkney Islands     |0.96      |25       |25         |1                |-4.17%            |
|Real_Quarterly|2020-21;Q2|Shetland Islands   |0.8       |10       |15         |0.666666667      |16.67%            |
|Real_Quarterly|2020-21;Q3|Eilean Siar        |0.93      |25       |30         |0.833333333      |10.39%            |
|Real_Quarterly|2020-21;Q3|Orkney Islands     |0.98      |40       |45         |0.888888889      |9.30%             |
|Real_Quarterly|2020-21;Q4|Argyll & Bute      |1         |235      |240        |0.979166667      |2.08%             |
|Real_Quarterly|2020-21;Q4|Eilean Siar        |0.95      |35       |35         |1                |-5.26%            |
|Real_Quarterly|2020-21;Q4|Shetland Islands   |0.71      |25       |40         |0.625            |11.97%            |
|Real_Quarterly|2021-22;Q1|Orkney Islands     |0.97      |30       |30         |1                |-3.09%            |
|Real_Quarterly|2021-22;Q1|Shetland Islands   |0.77      |15       |20         |0.75             |2.60%             |
|Real_Quarterly|2021-22;Q2|Dumfries & Galloway|0.36      |200      |570        |0.350877193      |2.53%             |
|Real_Quarterly|2021-22;Q2|East Dunbartonshire|0.98      |160      |160        |1                |-2.04%            |
|Real_Quarterly|2021-22;Q2|Eilean Siar        |0.97      |35       |35         |1                |-3.09%            |
|Real_Quarterly|2021-22;Q2|Shetland Islands   |0.76      |25       |35         |0.714285714      |6.02%             |
|Real_Quarterly|2021-22;Q3|Eilean Siar        |0.98      |40       |45         |0.888888889      |9.30%             |
|Real_Quarterly|2021-22;Q3|Shetland Islands   |0.74      |25       |35         |0.714285714      |3.47%             |
|Real_Quarterly|2022-23;Q1|Orkney Islands     |0.95      |35       |35         |1                |-5.26%            |
|Real_Quarterly|2022-23;Q1|Shetland Islands   |0.58      |20       |30         |0.666666667      |-14.94%           |
|Real_Quarterly|2022-23;Q2|East Dunbartonshire|0.98      |165      |165        |1                |-2.04%            |
|Real_Quarterly|2022-23;Q2|Shetland Islands   |0.74      |25       |35         |0.714285714      |3.47%             |
|Real_Quarterly|2022-23;Q3|Eilean Siar        |0.94      |35       |35         |1                |-6.38%            |
|Real_Quarterly|2022-23;Q3|Shetland Islands   |0.69      |20       |30         |0.666666667      |3.38%             |
|Real_Quarterly|2022-23;Q4|East Renfrewshire  |0.98      |175      |175        |1                |-2.04%            |
|Real_Quarterly|2022-23;Q4|Eilean Siar        |0.97      |35       |35         |1                |-3.09%            |
|Real_Quarterly|2022-23;Q4|Shetland Islands   |0.67      |10       |20         |0.5              |25.37%            |

## ECON 01 - Aberdeen City - Cash and Real - Annual - 2021-22
> There is a ∼85% difference between the result of dividing the numerator and denominator and the value stated.

|DataType   |Period |Local Authority|LGBF Value |Numerator|Denominator|Calculation Value|Percent Difference|
|-----------|-------|---------------|-----------|---------|-----------|-----------------|------------------|
|Cash_Annual|2021-22|Aberdeen City  |0.593409091|378      |4400       |0.085909091      |85.52%            |
|Real_Annual|2021-22|Aberdeen City  |0.593409091|378      |4400       |0.085909091      |85.52%            |

## ECON 12a - Various LA - Cash and Real - Monthly - Various Periods
> Various Local Authority Areas have differences between the result of dividing the numerator and denominator and the value stated as below. Some significant some slightly outwith the 2% rounding tolerance set.

|DataType    |Period |Local Authority    |LGBF Value|Numerator|Denominator|Calculation Value|Percent Difference|
|------------|-------|-------------------|----------|---------|-----------|-----------------|------------------|
|Cash_Monthly|2010;04|Angus              |0.03      |2135     |73125      |0.029196581      |2.68%             |
|Cash_Monthly|2010;04|East Lothian       |0.032     |2005     |64063      |0.031297317      |2.20%             |
|Cash_Monthly|2010;04|Scottish Borders   |0.029     |2065     |69688      |0.029632074      |-2.18%            |
|Cash_Monthly|2010;05|Aberdeen City      |0.022     |3350     |157391     |0.021284572      |3.25%             |
|Cash_Monthly|2010;05|Aberdeenshire      |0.014     |2220     |162188     |0.013687819      |2.23%             |
|Cash_Monthly|2010;05|Angus              |0.029     |2065     |73125      |0.028239316      |2.62%             |
|Cash_Monthly|2010;05|East Lothian       |0.03      |1880     |64063      |0.029346112      |2.18%             |
|Cash_Monthly|2010;05|Orkney Islands     |0.011     |155      |13529      |0.01145687       |-4.15%            |
|Cash_Monthly|2010;05|Shetland Islands   |0.015     |225      |15313      |0.014693398      |2.04%             |
|Cash_Monthly|2010;06|Aberdeen City      |0.021     |3235     |157391     |0.020553907      |2.12%             |
|Cash_Monthly|2010;06|Aberdeenshire      |0.013     |2055     |162188     |0.012670481      |2.53%             |
|Cash_Monthly|2010;06|Orkney Islands     |0.011     |145      |13529      |0.010717717      |2.57%             |
|Cash_Monthly|2010;06|Shetland Islands   |0.014     |205      |15313      |0.013387318      |4.38%             |
|Cash_Monthly|2010;07|East Lothian       |0.03      |1875     |64063      |0.029268064      |2.44%             |
|Cash_Monthly|2010;07|Orkney Islands     |0.014     |185      |13529      |0.013674329      |2.33%             |
|Cash_Monthly|2010;07|Perth & Kinross    |0.022     |1975     |92308      |0.021395762      |2.75%             |
|Cash_Monthly|2010;07|Shetland Islands   |0.014     |205      |15313      |0.013387318      |4.38%             |
|Cash_Monthly|2010;08|Aberdeen City      |0.022     |3350     |157391     |0.021284572      |3.25%             |
|Cash_Monthly|2010;08|Angus              |0.032     |2280     |73125      |0.031179487      |2.56%             |
|Cash_Monthly|2010;08|East Lothian       |0.03      |1875     |64063      |0.029268064      |2.44%             |
|Cash_Monthly|2010;08|Highland           |0.025     |3615     |147581     |0.024495023      |2.02%             |
|Cash_Monthly|2010;08|Shetland Islands   |0.014     |210      |15313      |0.013713838      |2.04%             |
|Cash_Monthly|2010;09|Aberdeen City      |0.021     |3215     |157391     |0.020426835      |2.73%             |
|Cash_Monthly|2010;09|Aberdeenshire      |0.013     |2065     |162188     |0.012732138      |2.06%             |
|Cash_Monthly|2010;09|Dumfries & Galloway|0.031     |2845     |93971      |0.030275298      |2.34%             |
|Cash_Monthly|2010;09|Dundee City        |0.05      |4825     |98661      |0.048904836      |2.19%             |
|Cash_Monthly|2010;09|South Lanarkshire  |0.042     |8510     |207444     |0.041023119      |2.33%             |
|Cash_Monthly|2010;10|Aberdeenshire      |0.012     |2035     |162188     |0.012547167      |-4.56%            |
|Cash_Monthly|2010;10|East Lothian       |0.028     |1740     |64063      |0.027160764      |3.00%             |
|Cash_Monthly|2010;10|Moray              |0.019     |1150     |59286      |0.019397497      |-2.09%            |
|Cash_Monthly|2010;10|Shetland Islands   |0.014     |200      |15313      |0.013060798      |6.71%             |
|Cash_Monthly|2010;11|East Lothian       |0.028     |1755     |64063      |0.027394908      |2.16%             |
|Cash_Monthly|2010;11|Orkney Islands     |0.014     |195      |13529      |0.014413482      |-2.95%            |
|Cash_Monthly|2010;11|Shetland Islands   |0.014     |210      |15313      |0.013713838      |2.04%             |
|Cash_Monthly|2010;12|Eilean Siar        |0.032     |540      |17258      |0.031289837      |2.22%             |
|Cash_Monthly|2010;12|Moray              |0.023     |1405     |59286      |0.023698681      |-3.04%            |
|Cash_Monthly|2010;12|Scottish Borders   |0.028     |2005     |69688      |0.028771094      |-2.75%            |
|Cash_Monthly|2010;12|South Lanarkshire  |0.044     |8940     |207444     |0.043095968      |2.05%             |
|Cash_Monthly|2011;01|Eilean Siar        |0.034     |575      |17258      |0.033317882      |2.01%             |
|Cash_Monthly|2011;01|Orkney Islands     |0.017     |235      |13529      |0.017370094      |-2.18%            |
|Cash_Monthly|2011;01|West Lothian       |0.039     |4570     |114634     |0.039866008      |-2.22%            |
|Cash_Monthly|2011;02|Shetland Islands   |0.016     |235      |15313      |0.015346438      |4.08%             |
|Cash_Monthly|2011;04|Argyll & Bute      |0.034     |1855     |52179      |0.0355507        |-4.56%            |
|Cash_Monthly|2011;04|Dumfries & Galloway|0.034     |3185     |91154      |0.034940869      |-2.77%            |
|Cash_Monthly|2011;04|East Renfrewshire  |0.025     |1420     |55577      |0.025550138      |-2.20%            |
|Cash_Monthly|2011;04|Orkney Islands     |0.014     |185      |13611      |0.013591948      |2.91%             |
|Cash_Monthly|2011;04|Scottish Borders   |0.03      |2125     |68971      |0.030810051      |-2.70%            |
|Cash_Monthly|2011;04|Shetland Islands   |0.014     |215      |14375      |0.014956522      |-6.83%            |
|Cash_Monthly|2011;05|Aberdeen City      |0.022     |3550     |158043     |0.022462241      |-2.10%            |
|Cash_Monthly|2011;05|Aberdeenshire      |0.014     |2390     |163667     |0.014602822      |-4.31%            |
|Cash_Monthly|2011;05|Argyll & Bute      |0.032     |1750     |52179      |0.033538397      |-4.81%            |
|Cash_Monthly|2011;05|East Renfrewshire  |0.024     |1375     |55577      |0.02474045       |-3.09%            |
|Cash_Monthly|2011;05|Eilean Siar        |0.029     |495      |16618      |0.029786978      |-2.71%            |
|Cash_Monthly|2011;05|Perth & Kinross    |0.024     |2210     |90185      |0.024505184      |-2.10%            |
|Cash_Monthly|2011;05|Shetland Islands   |0.014     |215      |14375      |0.014956522      |-6.83%            |
|Cash_Monthly|2011;06|Argyll & Bute      |0.032     |1780     |52179      |0.034113341      |-6.60%            |
|Cash_Monthly|2011;06|Dumfries & Galloway|0.033     |3105     |91154      |0.034063234      |-3.22%            |
|Cash_Monthly|2011;06|East Lothian       |0.03      |1930     |62714      |0.030774628      |-2.58%            |
|Cash_Monthly|2011;06|East Renfrewshire  |0.025     |1425     |55577      |0.025640103      |-2.56%            |
|Cash_Monthly|2011;06|Eilean Siar        |0.027     |460      |16618      |0.027680828      |-2.52%            |
|Cash_Monthly|2011;06|Moray              |0.024     |1445     |58214      |0.024822208      |-3.43%            |
|Cash_Monthly|2011;06|Orkney Islands     |0.014     |185      |13611      |0.013591948      |2.91%             |
|Cash_Monthly|2011;06|Scottish Borders   |0.028     |1975     |68971      |0.028635223      |-2.27%            |
|Cash_Monthly|2011;07|Argyll & Bute      |0.033     |1840     |52179      |0.035263229      |-6.86%            |
|Cash_Monthly|2011;07|Eilean Siar        |0.028     |475      |16618      |0.028583464      |-2.08%            |
|Cash_Monthly|2011;07|Orkney Islands     |0.014     |195      |13611      |0.014326648      |-2.33%            |
|Cash_Monthly|2011;07|Scottish Borders   |0.03      |2150     |68971      |0.031172522      |-3.91%            |
|Cash_Monthly|2011;07|Shetland Islands   |0.012     |180      |14375      |0.012521739      |-4.35%            |
|Cash_Monthly|2011;08|Aberdeenshire      |0.015     |2515     |163667     |0.015366567      |-2.44%            |
|Cash_Monthly|2011;08|Argyll & Bute      |0.034     |1890     |52179      |0.036221468      |-6.53%            |
|Cash_Monthly|2011;08|Dumfries & Galloway|0.035     |3265     |91154      |0.035818505      |-2.34%            |
|Cash_Monthly|2011;08|East Dunbartonshire|0.03      |1955     |66607      |0.029351269      |2.16%             |
|Cash_Monthly|2011;08|East Renfrewshire  |0.026     |1480     |55577      |0.026629721      |-2.42%            |
|Cash_Monthly|2011;08|Edinburgh City     |0.033     |11240    |333750     |0.033677903      |-2.05%            |
|Cash_Monthly|2011;08|Eilean Siar        |0.028     |480      |16618      |0.028884342      |-3.16%            |
|Cash_Monthly|2011;08|Moray              |0.025     |1495     |58214      |0.025681108      |-2.72%            |
|Cash_Monthly|2011;08|Perth & Kinross    |0.025     |2315     |90185      |0.025669457      |-2.68%            |
|Cash_Monthly|2011;08|Scottish Borders   |0.031     |2205     |68971      |0.031969958      |-3.13%            |
|Cash_Monthly|2011;09|Angus              |0.03      |2210     |71875      |0.030747826      |-2.49%            |
|Cash_Monthly|2011;09|Argyll & Bute      |0.033     |1810     |52179      |0.034688285      |-5.12%            |
|Cash_Monthly|2011;09|East Dunbartonshire|0.028     |1820     |66607      |0.027324455      |2.41%             |
|Cash_Monthly|2011;09|East Renfrewshire  |0.025     |1420     |55577      |0.025550138      |-2.20%            |
|Cash_Monthly|2011;09|Edinburgh City     |0.032     |10930    |333750     |0.032749064      |-2.34%            |
|Cash_Monthly|2011;09|Eilean Siar        |0.028     |475      |16618      |0.028583464      |-2.08%            |
|Cash_Monthly|2011;09|Moray              |0.022     |1320     |58214      |0.022674958      |-3.07%            |
|Cash_Monthly|2011;09|North Ayrshire     |0.061     |5375     |86343      |0.062251717      |-2.05%            |
|Cash_Monthly|2011;09|Scottish Borders   |0.029     |2050     |68971      |0.029722637      |-2.49%            |
|Cash_Monthly|2011;09|Shetland Islands   |0.011     |170      |14375      |0.011826087      |-7.51%            |
|Cash_Monthly|2011;10|Argyll & Bute      |0.033     |1840     |52179      |0.035263229      |-6.86%            |
|Cash_Monthly|2011;10|Eilean Siar        |0.028     |480      |16618      |0.028884342      |-3.16%            |
|Cash_Monthly|2011;10|Moray              |0.021     |1270     |58214      |0.021816058      |-3.89%            |
|Cash_Monthly|2011;10|Perth & Kinross    |0.022     |2060     |90185      |0.022841936      |-3.83%            |
|Cash_Monthly|2011;10|Scottish Borders   |0.028     |1980     |68971      |0.028707718      |-2.53%            |
|Cash_Monthly|2011;10|Shetland Islands   |0.012     |180      |14375      |0.012521739      |-4.35%            |
|Cash_Monthly|2011;11|Argyll & Bute      |0.035     |1910     |52179      |0.036604764      |-4.59%            |
|Cash_Monthly|2011;11|Eilean Siar        |0.03      |520      |16618      |0.031291371      |-4.30%            |
|Cash_Monthly|2011;11|Orkney Islands     |0.018     |250      |13611      |0.018367497      |-2.04%            |
|Cash_Monthly|2011;11|Perth & Kinross    |0.023     |2135     |90185      |0.02367356       |-2.93%            |
|Cash_Monthly|2011;12|Aberdeen City      |0.021     |3395     |158043     |0.021481496      |-2.29%            |
|Cash_Monthly|2011;12|Aberdeenshire      |0.013     |2225     |163667     |0.013594677      |-4.57%            |
|Cash_Monthly|2011;12|Argyll & Bute      |0.036     |1995     |52179      |0.038233772      |-6.20%            |
|Cash_Monthly|2011;12|East Lothian       |0.032     |2055     |62714      |0.032767803      |-2.40%            |
|Cash_Monthly|2011;12|Eilean Siar        |0.031     |530      |16618      |0.031893128      |-2.88%            |
|Cash_Monthly|2011;12|Perth & Kinross    |0.024     |2225     |90185      |0.024671509      |-2.80%            |
|Cash_Monthly|2011;12|Shetland Islands   |0.012     |185      |14375      |0.012869565      |-7.25%            |
|Cash_Monthly|2012;01|Aberdeenshire      |0.014     |2360     |163667     |0.014419523      |-3.00%            |
|Cash_Monthly|2012;01|East Renfrewshire  |0.025     |1425     |55577      |0.025640103      |-2.56%            |
|Cash_Monthly|2012;01|Edinburgh City     |0.034     |11650    |333750     |0.034906367      |-2.67%            |
|Cash_Monthly|2012;01|Orkney Islands     |0.02      |265      |13611      |0.019469547      |2.65%             |
|Cash_Monthly|2012;02|Orkney Islands     |0.019     |250      |13611      |0.018367497      |3.33%             |
|Cash_Monthly|2012;02|Shetland Islands   |0.014     |210      |14375      |0.014608696      |-4.35%            |
|Cash_Monthly|2012;04|Aberdeen City      |0.022     |3510     |162895     |0.021547623      |2.06%             |
|Cash_Monthly|2012;04|Eilean Siar        |0.032     |545      |16667      |0.032699346      |-2.19%            |
|Cash_Monthly|2012;04|Moray              |0.025     |1435     |59167      |0.024253384      |2.99%             |
|Cash_Monthly|2012;04|Orkney Islands     |0.015     |205      |13214      |0.015513849      |-3.43%            |
|Cash_Monthly|2012;04|Scottish Borders   |0.031     |2195     |69219      |0.031710946      |-2.29%            |
|Cash_Monthly|2012;04|Shetland Islands   |0.015     |225      |14375      |0.015652174      |-4.35%            |
|Cash_Monthly|2012;05|Aberdeenshire      |0.013     |2220     |166250     |0.013353383      |-2.72%            |
|Cash_Monthly|2012;05|Scottish Borders   |0.029     |2055     |69219      |0.02968838       |-2.37%            |
|Cash_Monthly|2012;05|Shetland Islands   |0.015     |225      |14375      |0.015652174      |-4.35%            |
|Cash_Monthly|2012;06|Aberdeen City      |0.021     |3340     |162895     |0.020504006      |2.36%             |
|Cash_Monthly|2012;06|East Lothian       |0.031     |1935     |64242      |0.030120482      |2.84%             |
|Cash_Monthly|2012;06|Eilean Siar        |0.032     |545      |16667      |0.032699346      |-2.19%            |
|Cash_Monthly|2012;06|Orkney Islands     |0.015     |205      |13214      |0.015513849      |-3.43%            |
|Cash_Monthly|2012;07|Aberdeenshire      |0.013     |2225     |166250     |0.013383459      |-2.95%            |
|Cash_Monthly|2012;07|West Lothian       |0.038     |4445     |114535     |0.038809098      |-2.13%            |
|Cash_Monthly|2012;08|Stirling           |0.033     |1970     |58281      |0.033801754      |-2.43%            |
|Cash_Monthly|2012;09|Aberdeenshire      |0.012     |1925     |166250     |0.011578947      |3.51%             |
|Cash_Monthly|2012;09|East Dunbartonshire|0.025     |1680     |65800      |0.025531915      |-2.13%            |
|Cash_Monthly|2012;09|Orkney Islands     |0.012     |155      |13214      |0.011729983      |2.25%             |
|Cash_Monthly|2012;09|Scottish Borders   |0.028     |1980     |69219      |0.028604863      |-2.16%            |
|Cash_Monthly|2012;10|Aberdeen City      |0.02      |3180     |162895     |0.019521778      |2.39%             |
|Cash_Monthly|2012;10|Eilean Siar        |0.027     |460      |16667      |0.027599448      |-2.22%            |
|Cash_Monthly|2012;10|Shetland Islands   |0.013     |195      |14375      |0.013565217      |-4.35%            |
|Cash_Monthly|2012;10|Stirling           |0.031     |1845     |58281      |0.031656972      |-2.12%            |
|Cash_Monthly|2012;10|West Lothian       |0.034     |3980     |114535     |0.034749203      |-2.20%            |
|Cash_Monthly|2012;11|East Dunbartonshire|0.024     |1615     |65800      |0.024544073      |-2.27%            |
|Cash_Monthly|2012;11|Eilean Siar        |0.026     |445      |16667      |0.026699466      |-2.69%            |
|Cash_Monthly|2012;12|Aberdeen City      |0.019     |2990     |162895     |0.018355382      |3.39%             |
|Cash_Monthly|2012;12|Aberdeenshire      |0.011     |1875     |166250     |0.011278195      |-2.53%            |
|Cash_Monthly|2012;12|Eilean Siar        |0.027     |460      |16667      |0.027599448      |-2.22%            |
|Cash_Monthly|2012;12|Moray              |0.022     |1275     |59167      |0.021549174      |2.05%             |
|Cash_Monthly|2012;12|Scottish Borders   |0.028     |1985     |69219      |0.028677097      |-2.42%            |
|Cash_Monthly|2013;01|Shetland Islands   |0.014     |215      |14375      |0.014956522      |-6.83%            |
|Cash_Monthly|2013;02|Aberdeen City      |0.02      |3135     |162895     |0.019245526      |3.77%             |
|Cash_Monthly|2013;02|Aberdeenshire      |0.013     |2070     |166250     |0.012451128      |4.22%             |
|Cash_Monthly|2013;02|Argyll & Bute      |0.037     |2005     |53056      |0.037790259      |-2.14%            |
|Cash_Monthly|2013;02|Orkney Islands     |0.014     |190      |13214      |0.014378689      |-2.70%            |
|Cash_Monthly|2013;02|Shetland Islands   |0.014     |210      |14375      |0.014608696      |-4.35%            |
|Cash_Monthly|2013;04|Aberdeen City      |0.018     |2945     |156667     |0.018797832      |-4.43%            |
|Cash_Monthly|2013;04|Aberdeenshire      |0.012     |1935     |173750     |0.011136691      |7.19%             |
|Cash_Monthly|2013;04|Falkirk            |0.043     |4420     |100694     |0.043895366      |-2.08%            |
|Cash_Monthly|2013;04|Highland           |0.025     |3705     |142826     |0.025940655      |-3.76%            |
|Cash_Monthly|2013;04|Shetland Islands   |0.015     |225      |14500      |0.015517241      |-3.45%            |
|Cash_Monthly|2013;05|Aberdeenshire      |0.011     |1850     |173750     |0.010647482      |3.20%             |
|Cash_Monthly|2013;05|Fife               |0.045     |10580    |229459     |0.046108455      |-2.46%            |
|Cash_Monthly|2013;05|Perth & Kinross    |0.022     |2000     |93947      |0.021288599      |3.23%             |
|Cash_Monthly|2013;05|Renfrewshire       |0.047     |5340     |111154     |0.048041456      |-2.22%            |
|Cash_Monthly|2013;05|Scottish Borders   |0.029     |2025     |67692      |0.029914909      |-3.15%            |
|Cash_Monthly|2013;05|Shetland Islands   |0.013     |195      |14500      |0.013448276      |-3.45%            |
|Cash_Monthly|2013;05|Stirling           |0.029     |1700     |60000      |0.028333333      |2.30%             |
|Cash_Monthly|2013;06|Aberdeen City      |0.017     |2760     |156667     |0.017616984      |-3.63%            |
|Cash_Monthly|2013;06|Aberdeenshire      |0.011     |1790     |173750     |0.010302158      |6.34%             |
|Cash_Monthly|2013;06|East Dunbartonshire|0.022     |1475     |65588      |0.02248887       |-2.22%            |
|Cash_Monthly|2013;06|Eilean Siar        |0.026     |440      |16333      |0.026939325      |-3.61%            |
|Cash_Monthly|2013;06|Moray              |0.021     |1255     |58421      |0.021482001      |-2.30%            |
|Cash_Monthly|2013;06|Orkney Islands     |0.01      |140      |13636      |0.01026694       |-2.67%            |
|Cash_Monthly|2013;06|Perth & Kinross    |0.022     |1980     |93947      |0.021075713      |4.20%             |
|Cash_Monthly|2013;07|Aberdeen City      |0.017     |2755     |156667     |0.017585069      |-3.44%            |
|Cash_Monthly|2013;07|Aberdeenshire      |0.011     |1790     |173750     |0.010302158      |6.34%             |
|Cash_Monthly|2013;07|Edinburgh City     |0.031     |10430    |346923     |0.030064308      |3.02%             |
|Cash_Monthly|2013;07|Fife               |0.046     |10785    |229459     |0.047001861      |-2.18%            |
|Cash_Monthly|2013;07|Midlothian         |0.035     |1845     |54000      |0.034166667      |2.38%             |
|Cash_Monthly|2013;07|Perth & Kinross    |0.022     |1970     |93947      |0.02096927       |4.69%             |
|Cash_Monthly|2013;07|Renfrewshire       |0.046     |5225     |111154     |0.047006855      |-2.19%            |
|Cash_Monthly|2013;07|Scottish Borders   |0.028     |1955     |67692      |0.028880813      |-3.15%            |
|Cash_Monthly|2013;08|Aberdeen City      |0.017     |2725     |156667     |0.01739358       |-2.32%            |
|Cash_Monthly|2013;08|Eilean Siar        |0.027     |450      |16333      |0.027551583      |-2.04%            |
|Cash_Monthly|2013;08|Fife               |0.045     |10560    |229459     |0.046021294      |-2.27%            |
|Cash_Monthly|2013;08|Moray              |0.019     |1145     |58421      |0.019599117      |-3.15%            |
|Cash_Monthly|2013;08|Orkney Islands     |0.01      |140      |13636      |0.01026694       |-2.67%            |
|Cash_Monthly|2013;08|Perth & Kinross    |0.021     |1900     |93947      |0.020224169      |3.69%             |
|Cash_Monthly|2013;08|Renfrewshire       |0.045     |5125     |111154     |0.046107203      |-2.46%            |
|Cash_Monthly|2013;08|Scottish Borders   |0.027     |1890     |67692      |0.027920581      |-3.41%            |
|Cash_Monthly|2013;09|Aberdeen City      |0.015     |2460     |156667     |0.015702094      |-4.68%            |
|Cash_Monthly|2013;09|Aberdeenshire      |0.009     |1455     |173750     |0.008374101      |6.95%             |
|Cash_Monthly|2013;09|Argyll & Bute      |0.026     |1415     |53214      |0.026590747      |-2.27%            |
|Cash_Monthly|2013;09|Orkney Islands     |0.011     |145      |13636      |0.010633617      |3.33%             |
|Cash_Monthly|2013;09|Perth & Kinross    |0.019     |1710     |93947      |0.018201752      |4.20%             |
|Cash_Monthly|2013;09|Renfrewshire       |0.04      |4560     |111154     |0.041024165      |-2.56%            |
|Cash_Monthly|2013;09|Scottish Borders   |0.025     |1745     |67692      |0.025778526      |-3.11%            |
|Cash_Monthly|2013;09|Shetland Islands   |0.008     |120      |14500      |0.008275862      |-3.45%            |
|Cash_Monthly|2013;09|Stirling           |0.027     |1575     |60000      |0.02625          |2.78%             |
|Cash_Monthly|2013;10|Aberdeen City      |0.014     |2320     |156667     |0.014808479      |-5.77%            |
|Cash_Monthly|2013;10|East Dunbartonshire|0.019     |1220     |65588      |0.018600964      |2.10%             |
|Cash_Monthly|2013;10|East Renfrewshire  |0.018     |990      |56875      |0.017406593      |3.30%             |
|Cash_Monthly|2013;10|Edinburgh City     |0.027     |9130     |346923     |0.026317079      |2.53%             |
|Cash_Monthly|2013;10|Highland           |0.018     |2640     |142826     |0.01848403       |-2.69%            |
|Cash_Monthly|2013;10|Moray              |0.015     |915      |58421      |0.015662176      |-4.41%            |
|Cash_Monthly|2013;10|Orkney Islands     |0.011     |145      |13636      |0.010633617      |3.33%             |
|Cash_Monthly|2013;10|Perth & Kinross    |0.018     |1615     |93947      |0.017190544      |4.50%             |
|Cash_Monthly|2013;10|Scottish Borders   |0.024     |1685     |67692      |0.024892159      |-3.72%            |
|Cash_Monthly|2013;10|Shetland Islands   |0.007     |110      |14500      |0.007586207      |-8.37%            |
|Cash_Monthly|2013;10|Stirling           |0.026     |1525     |60000      |0.025416667      |2.24%             |
|Cash_Monthly|2013;11|Aberdeen City      |0.014     |2315     |156667     |0.014776564      |-5.55%            |
|Cash_Monthly|2013;11|Aberdeenshire      |0.008     |1320     |173750     |0.007597122      |5.04%             |
|Cash_Monthly|2013;11|Angus              |0.022     |1550     |72619      |0.021344276      |2.98%             |
|Cash_Monthly|2013;11|East Renfrewshire  |0.017     |940      |56875      |0.016527473      |2.78%             |
|Cash_Monthly|2013;11|Moray              |0.015     |915      |58421      |0.015662176      |-4.41%            |
|Cash_Monthly|2013;11|Perth & Kinross    |0.018     |1650     |93947      |0.017563094      |2.43%             |
|Cash_Monthly|2013;11|Shetland Islands   |0.01      |140      |14500      |0.009655172      |3.45%             |
|Cash_Monthly|2013;11|Stirling           |0.026     |1510     |60000      |0.025166667      |3.21%             |
|Cash_Monthly|2013;12|Aberdeen City      |0.014     |2270     |156667     |0.014489331      |-3.50%            |
|Cash_Monthly|2013;12|Aberdeenshire      |0.008     |1340     |173750     |0.00771223       |3.60%             |
|Cash_Monthly|2013;12|Angus              |0.022     |1545     |72619      |0.021275424      |3.29%             |
|Cash_Monthly|2013;12|Edinburgh City     |0.026     |8820     |346923     |0.025423509      |2.22%             |
|Cash_Monthly|2013;12|Eilean Siar        |0.028     |475      |16333      |0.029082226      |-3.87%            |
|Cash_Monthly|2013;12|Moray              |0.016     |975      |58421      |0.016689204      |-4.31%            |
|Cash_Monthly|2013;12|Shetland Islands   |0.009     |140      |14500      |0.009655172      |-7.28%            |
|Cash_Monthly|2013;12|Stirling           |0.026     |1510     |60000      |0.025166667      |3.21%             |
|Cash_Monthly|2014;01|Aberdeenshire      |0.009     |1430     |173750     |0.008230216      |8.55%             |
|Cash_Monthly|2014;01|East Dunbartonshire|0.018     |1150     |65588      |0.017533695      |2.59%             |
|Cash_Monthly|2014;01|Edinburgh City     |0.027     |9105     |346923     |0.026245017      |2.80%             |
|Cash_Monthly|2014;01|Fife               |0.036     |8465     |229459     |0.036891122      |-2.48%            |
|Cash_Monthly|2014;01|Highland           |0.022     |3220     |142826     |0.022544915      |-2.48%            |
|Cash_Monthly|2014;01|Orkney Islands     |0.011     |145      |13636      |0.010633617      |3.33%             |
|Cash_Monthly|2014;01|Perth & Kinross    |0.02      |1800     |93947      |0.019159739      |4.20%             |
|Cash_Monthly|2014;01|Shetland Islands   |0.009     |135      |14500      |0.009310345      |-3.45%            |
|Cash_Monthly|2014;01|Stirling           |0.027     |1565     |60000      |0.026083333      |3.40%             |
|Cash_Monthly|2014;02|Aberdeen City      |0.015     |2430     |156667     |0.015510605      |-3.40%            |
|Cash_Monthly|2014;02|Aberdeenshire      |0.009     |1470     |173750     |0.008460432      |6.00%             |
|Cash_Monthly|2014;02|Inverclyde         |0.042     |2120     |51625      |0.041065375      |2.23%             |
|Cash_Monthly|2014;02|Orkney Islands     |0.012     |155      |13636      |0.01136697       |5.28%             |
|Cash_Monthly|2014;02|Perth & Kinross    |0.02      |1815     |93947      |0.019319403      |3.40%             |
|Cash_Monthly|2014;02|Scottish Borders   |0.027     |1870     |67692      |0.027625126      |-2.32%            |
|Cash_Monthly|2014;02|Shetland Islands   |0.008     |120      |14500      |0.008275862      |-3.45%            |
|Cash_Monthly|2014;04|Aberdeen City      |0.014     |2195     |161667     |0.013577292      |3.02%             |
|Cash_Monthly|2014;04|Aberdeenshire      |0.008     |1365     |156250     |0.008736         |-9.20%            |
|Cash_Monthly|2014;04|East Lothian       |0.024     |1560     |63421      |0.024597531      |-2.49%            |
|Cash_Monthly|2014;04|Edinburgh City     |0.026     |8830     |349722     |0.025248626      |2.89%             |
|Cash_Monthly|2014;04|Moray              |0.018     |1075     |61333      |0.017527269      |2.63%             |
|Cash_Monthly|2014;04|Orkney Islands     |0.009     |125      |14286      |0.008749825      |2.78%             |
|Cash_Monthly|2014;04|Shetland Islands   |0.01      |145      |15000      |0.009666667      |3.33%             |
|Cash_Monthly|2014;04|South Lanarkshire  |0.034     |6815     |204630     |0.033304012      |2.05%             |
|Cash_Monthly|2014;04|Stirling           |0.024     |1405     |61176      |0.022966523      |4.31%             |
|Cash_Monthly|2014;04|West Lothian       |0.029     |3320     |118500     |0.028016878      |3.39%             |
|Cash_Monthly|2014;05|Aberdeenshire      |0.007     |1245     |156250     |0.007968         |-13.83%           |
|Cash_Monthly|2014;05|East Dunbartonshire|0.015     |995      |64286      |0.015477709      |-3.18%            |
|Cash_Monthly|2014;05|East Renfrewshire  |0.015     |865      |55714      |0.015525721      |-3.50%            |
|Cash_Monthly|2014;05|Edinburgh City     |0.025     |8485     |349722     |0.024262128      |2.95%             |
|Cash_Monthly|2014;05|Glasgow City       |0.042     |17475    |424595     |0.041156867      |2.01%             |
|Cash_Monthly|2014;05|Moray              |0.017     |1000     |61333      |0.016304436      |4.09%             |
|Cash_Monthly|2014;05|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Cash_Monthly|2014;05|Scottish Borders   |0.022     |1530     |67500      |0.022666667      |-3.03%            |
|Cash_Monthly|2014;05|Shetland Islands   |0.008     |125      |15000      |0.008333333      |-4.17%            |
|Cash_Monthly|2014;05|Stirling           |0.023     |1335     |61176      |0.021822283      |5.12%             |
|Cash_Monthly|2014;06|Aberdeenshire      |0.007     |1205     |156250     |0.007712         |-10.17%           |
|Cash_Monthly|2014;06|Angus              |0.02      |1410     |71944      |0.019598577      |2.01%             |
|Cash_Monthly|2014;06|Argyll & Bute      |0.02      |1070     |52000      |0.020576923      |-2.88%            |
|Cash_Monthly|2014;06|East Ayrshire      |0.042     |3305     |76579      |0.043158046      |-2.76%            |
|Cash_Monthly|2014;06|East Dunbartonshire|0.014     |935      |64286      |0.01454438       |-3.89%            |
|Cash_Monthly|2014;06|East Lothian       |0.022     |1430     |63421      |0.022547737      |-2.49%            |
|Cash_Monthly|2014;06|East Renfrewshire  |0.014     |805      |55714      |0.014448792      |-3.21%            |
|Cash_Monthly|2014;06|Eilean Siar        |0.022     |365      |16250      |0.022461538      |-2.10%            |
|Cash_Monthly|2014;06|Fife               |0.032     |7330     |234444     |0.031265462      |2.30%             |
|Cash_Monthly|2014;06|Moray              |0.016     |930      |61333      |0.015163126      |5.23%             |
|Cash_Monthly|2014;06|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Cash_Monthly|2014;06|Stirling           |0.021     |1255     |61176      |0.020514581      |2.31%             |
|Cash_Monthly|2014;06|West Dunbartonshire|0.043     |2535     |57500      |0.044086957      |-2.53%            |
|Cash_Monthly|2014;07|Aberdeen City      |0.012     |1990     |161667     |0.012309253      |-2.58%            |
|Cash_Monthly|2014;07|Aberdeenshire      |0.007     |1165     |156250     |0.007456         |-6.51%            |
|Cash_Monthly|2014;07|Argyll & Bute      |0.02      |1070     |52000      |0.020576923      |-2.88%            |
|Cash_Monthly|2014;07|East Renfrewshire  |0.015     |855      |55714      |0.015346233      |-2.31%            |
|Cash_Monthly|2014;07|Falkirk            |0.03      |3000     |103400     |0.02901354       |3.29%             |
|Cash_Monthly|2014;07|Fife               |0.033     |7580     |234444     |0.032331815      |2.02%             |
|Cash_Monthly|2014;07|Highland           |0.016     |2260     |147353     |0.015337319      |4.14%             |
|Cash_Monthly|2014;07|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Cash_Monthly|2014;07|Shetland Islands   |0.006     |95       |15000      |0.006333333      |-5.56%            |
|Cash_Monthly|2014;07|Stirling           |0.021     |1235     |61176      |0.020187655      |3.87%             |
|Cash_Monthly|2014;07|West Lothian       |0.025     |2835     |118500     |0.023924051      |4.30%             |
|Cash_Monthly|2014;08|Aberdeen City      |0.012     |1880     |161667     |0.011628842      |3.09%             |
|Cash_Monthly|2014;08|Argyll & Bute      |0.019     |1010     |52000      |0.019423077      |-2.23%            |
|Cash_Monthly|2014;08|Eilean Siar        |0.021     |350      |16250      |0.021538462      |-2.56%            |
|Cash_Monthly|2014;08|Highland           |0.015     |2165     |147353     |0.014692609      |2.05%             |
|Cash_Monthly|2014;08|Moray              |0.015     |880      |61333      |0.014347904      |4.35%             |
|Cash_Monthly|2014;08|Orkney Islands     |0.007     |95       |14286      |0.006649867      |5.00%             |
|Cash_Monthly|2014;08|Scottish Borders   |0.021     |1450     |67500      |0.021481481      |-2.29%            |
|Cash_Monthly|2014;08|Stirling           |0.02      |1195     |61176      |0.019533804      |2.33%             |
|Cash_Monthly|2014;08|West Lothian       |0.024     |2760     |118500     |0.023291139      |2.95%             |
|Cash_Monthly|2014;09|Aberdeen City      |0.011     |1725     |161667     |0.010670081      |3.00%             |
|Cash_Monthly|2014;09|Argyll & Bute      |0.017     |910      |52000      |0.0175           |-2.94%            |
|Cash_Monthly|2014;09|East Dunbartonshire|0.013     |870      |64286      |0.013533273      |-4.10%            |
|Cash_Monthly|2014;09|East Renfrewshire  |0.013     |760      |55714      |0.013641096      |-4.93%            |
|Cash_Monthly|2014;09|Fife               |0.028     |6415     |234444     |0.027362611      |2.28%             |
|Cash_Monthly|2014;09|Highland           |0.014     |1980     |147353     |0.01343712       |4.02%             |
|Cash_Monthly|2014;09|Moray              |0.013     |745      |61333      |0.012146805      |6.56%             |
|Cash_Monthly|2014;09|Orkney Islands     |0.007     |90       |14286      |0.006299874      |10.00%            |
|Cash_Monthly|2014;09|Perth & Kinross    |0.013     |1240     |93077      |0.013322303      |-2.48%            |
|Cash_Monthly|2014;09|Shetland Islands   |0.005     |70       |15000      |0.004666667      |6.67%             |
|Cash_Monthly|2014;09|West Lothian       |0.021     |2405     |118500     |0.020295359      |3.36%             |
|Cash_Monthly|2014;10|Aberdeen City      |0.01      |1665     |161667     |0.010298948      |-2.99%            |
|Cash_Monthly|2014;10|Aberdeenshire      |0.006     |915      |156250     |0.005856         |2.40%             |
|Cash_Monthly|2014;10|East Renfrewshire  |0.012     |700      |55714      |0.012564167      |-4.70%            |
|Cash_Monthly|2014;10|Edinburgh City     |0.02      |6725     |349722     |0.019229559      |3.85%             |
|Cash_Monthly|2014;10|Falkirk            |0.026     |2595     |103400     |0.025096712      |3.47%             |
|Cash_Monthly|2014;10|Highland           |0.013     |1955     |147353     |0.01326746       |-2.06%            |
|Cash_Monthly|2014;10|Midlothian         |0.021     |1115     |54211      |0.020567781      |2.06%             |
|Cash_Monthly|2014;10|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Cash_Monthly|2014;10|Perth & Kinross    |0.013     |1175     |93077      |0.012623957      |2.89%             |
|Cash_Monthly|2014;10|Scottish Borders   |0.017     |1180     |67500      |0.017481481      |-2.83%            |
|Cash_Monthly|2014;10|Shetland Islands   |0.006     |85       |15000      |0.005666667      |5.56%             |
|Cash_Monthly|2014;10|West Dunbartonshire|0.038     |2230     |57500      |0.038782609      |-2.06%            |
|Cash_Monthly|2014;11|Angus              |0.018     |1250     |71944      |0.017374625      |3.47%             |
|Cash_Monthly|2014;11|East Ayrshire      |0.036     |2820     |76579      |0.036824717      |-2.29%            |
|Cash_Monthly|2014;11|East Dunbartonshire|0.013     |875      |64286      |0.013611051      |-4.70%            |
|Cash_Monthly|2014;11|East Lothian       |0.018     |1165     |63421      |0.01836931       |-2.05%            |
|Cash_Monthly|2014;11|East Renfrewshire  |0.012     |700      |55714      |0.012564167      |-4.70%            |
|Cash_Monthly|2014;11|Edinburgh City     |0.019     |6410     |349722     |0.018328844      |3.53%             |
|Cash_Monthly|2014;11|Highland           |0.015     |2160     |147353     |0.014658677      |2.28%             |
|Cash_Monthly|2014;11|Moray              |0.012     |695      |61333      |0.011331583      |5.57%             |
|Cash_Monthly|2014;11|Orkney Islands     |0.008     |100      |14286      |0.00699986       |12.50%            |
|Cash_Monthly|2014;11|Shetland Islands   |0.006     |85       |15000      |0.005666667      |5.56%             |
|Cash_Monthly|2014;11|South Ayrshire     |0.029     |2015     |68036      |0.029616674      |-2.13%            |
|Cash_Monthly|2014;11|West Lothian       |0.019     |2180     |118500     |0.018396624      |3.18%             |
|Cash_Monthly|2014;12|Aberdeen City      |0.009     |1525     |161667     |0.00943297       |-4.81%            |
|Cash_Monthly|2014;12|Aberdeenshire      |0.006     |960      |156250     |0.006144         |-2.40%            |
|Cash_Monthly|2014;12|Clackmannanshire   |0.031     |1030     |32500      |0.031692308      |-2.23%            |
|Cash_Monthly|2014;12|East Dunbartonshire|0.013     |855      |64286      |0.013299941      |-2.31%            |
|Cash_Monthly|2014;12|East Lothian       |0.018     |1175     |63421      |0.018526986      |-2.93%            |
|Cash_Monthly|2014;12|East Renfrewshire  |0.012     |695      |55714      |0.012474423      |-3.95%            |
|Cash_Monthly|2014;12|Edinburgh City     |0.018     |6070     |349722     |0.017356643      |3.57%             |
|Cash_Monthly|2014;12|Eilean Siar        |0.021     |350      |16250      |0.021538462      |-2.56%            |
|Cash_Monthly|2014;12|Highland           |0.017     |2410     |147353     |0.016355283      |3.79%             |
|Cash_Monthly|2014;12|Moray              |0.013     |760      |61333      |0.012391372      |4.68%             |
|Cash_Monthly|2014;12|Orkney Islands     |0.008     |110      |14286      |0.007699846      |3.75%             |
|Cash_Monthly|2014;12|Stirling           |0.017     |1010     |61176      |0.016509742      |2.88%             |
|Cash_Monthly|2014;12|West Lothian       |0.018     |2015     |118500     |0.017004219      |5.53%             |
|Cash_Monthly|2015;01|Aberdeenshire      |0.006     |1080     |156250     |0.006912         |-15.20%           |
|Cash_Monthly|2015;01|Angus              |0.019     |1325     |71944      |0.018417102      |3.07%             |
|Cash_Monthly|2015;01|Argyll & Bute      |0.019     |1015     |52000      |0.019519231      |-2.73%            |
|Cash_Monthly|2015;01|Dumfries & Galloway|0.021     |1850     |90238      |0.020501341      |2.37%             |
|Cash_Monthly|2015;01|East Lothian       |0.018     |1185     |63421      |0.018684663      |-3.80%            |
|Cash_Monthly|2015;01|Moray              |0.015     |865      |61333      |0.014103338      |5.98%             |
|Cash_Monthly|2015;01|Orkney Islands     |0.009     |115      |14286      |0.008049839      |10.56%            |
|Cash_Monthly|2015;01|Scottish Borders   |0.018     |1260     |67500      |0.018666667      |-3.70%            |
|Cash_Monthly|2015;01|West Lothian       |0.02      |2280     |118500     |0.019240506      |3.80%             |
|Cash_Monthly|2015;02|Aberdeen City      |0.011     |1850     |161667     |0.011443275      |-4.03%            |
|Cash_Monthly|2015;02|Aberdeenshire      |0.007     |1215     |156250     |0.007776         |-11.09%           |
|Cash_Monthly|2015;02|East Dunbartonshire|0.014     |930      |64286      |0.014466602      |-3.33%            |
|Cash_Monthly|2015;02|Moray              |0.016     |930      |61333      |0.015163126      |5.23%             |
|Cash_Monthly|2015;02|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Cash_Monthly|2015;02|Perth & Kinross    |0.013     |1235     |93077      |0.013268584      |-2.07%            |
|Cash_Monthly|2015;02|Shetland Islands   |0.007     |95       |15000      |0.006333333      |9.52%             |
|Cash_Monthly|2015;02|Stirling           |0.019     |1120     |61176      |0.018307833      |3.64%             |
|Cash_Monthly|2015;02|West Lothian       |0.021     |2405     |118500     |0.020295359      |3.36%             |
|Cash_Monthly|2015;04|Aberdeen City      |0.012     |2010     |163500     |0.012293578      |-2.45%            |
|Cash_Monthly|2015;04|Aberdeenshire      |0.008     |1270     |165667     |0.007665981      |4.18%             |
|Cash_Monthly|2015;04|East Dunbartonshire|0.013     |865      |63333      |0.013657967      |-5.06%            |
|Cash_Monthly|2015;04|Fife               |0.027     |6195     |234400     |0.026429181      |2.11%             |
|Cash_Monthly|2015;04|Glasgow City       |0.036     |15315    |439219     |0.03486871       |3.14%             |
|Cash_Monthly|2015;04|Moray              |0.014     |850      |58947      |0.014419733      |-3.00%            |
|Cash_Monthly|2015;04|Orkney Islands     |0.007     |95       |12778      |0.007434653      |-6.21%            |
|Cash_Monthly|2015;04|Perth & Kinross    |0.012     |1115     |95000      |0.011736842      |2.19%             |
|Cash_Monthly|2015;04|Scottish Borders   |0.017     |1140     |69211      |0.01647137       |3.11%             |
|Cash_Monthly|2015;04|South Ayrshire     |0.025     |1720     |67200      |0.025595238      |-2.38%            |
|Cash_Monthly|2015;04|West Dunbartonshire|0.039     |2280     |57179      |0.039874779      |-2.24%            |
|Cash_Monthly|2015;04|West Lothian       |0.02      |2260     |118056     |0.019143457      |4.28%             |
|Cash_Monthly|2015;05|Aberdeen City      |0.013     |2185     |163500     |0.013363914      |-2.80%            |
|Cash_Monthly|2015;05|Aberdeenshire      |0.008     |1265     |165667     |0.0076358        |4.55%             |
|Cash_Monthly|2015;05|Edinburgh City     |0.016     |5725     |344375     |0.016624319      |-3.90%            |
|Cash_Monthly|2015;05|Falkirk            |0.023     |2380     |99783      |0.023851758      |-3.70%            |
|Cash_Monthly|2015;05|Fife               |0.027     |6175     |234400     |0.026343857      |2.43%             |
|Cash_Monthly|2015;05|Glasgow City       |0.035     |14965    |439219     |0.034071841      |2.65%             |
|Cash_Monthly|2015;05|Highland           |0.014     |2075     |140833     |0.014733763      |-5.24%            |
|Cash_Monthly|2015;05|Midlothian         |0.017     |925      |56471      |0.016380089      |3.65%             |
|Cash_Monthly|2015;05|North Lanarkshire  |0.03      |6640     |216034     |0.030735903      |-2.45%            |
|Cash_Monthly|2015;05|Orkney Islands     |0.005     |70       |12778      |0.005478166      |-9.56%            |
|Cash_Monthly|2015;05|Shetland Islands   |0.006     |90       |14500      |0.006206897      |-3.45%            |
|Cash_Monthly|2015;05|South Ayrshire     |0.024     |1650     |67200      |0.024553571      |-2.31%            |
|Cash_Monthly|2015;05|West Lothian       |0.019     |2175     |118056     |0.01842346       |3.03%             |
|Cash_Monthly|2015;06|Aberdeen City      |0.014     |2205     |163500     |0.013486239      |3.67%             |
|Cash_Monthly|2015;06|Angus              |0.018     |1305     |69524      |0.018770497      |-4.28%            |
|Cash_Monthly|2015;06|Argyll & Bute      |0.016     |830      |53056      |0.015643848      |2.23%             |
|Cash_Monthly|2015;06|East Dunbartonshire|0.013     |865      |63333      |0.013657967      |-5.06%            |
|Cash_Monthly|2015;06|East Renfrewshire  |0.012     |700      |56818      |0.012320039      |-2.67%            |
|Cash_Monthly|2015;06|Falkirk            |0.021     |2185     |99783      |0.021897518      |-4.27%            |
|Cash_Monthly|2015;06|Fife               |0.026     |5965     |234400     |0.025447952      |2.12%             |
|Cash_Monthly|2015;06|Glasgow City       |0.035     |14830    |439219     |0.033764477      |3.53%             |
|Cash_Monthly|2015;06|Midlothian         |0.017     |905      |56471      |0.016025925      |5.73%             |
|Cash_Monthly|2015;06|Moray              |0.013     |795      |58947      |0.013486691      |-3.74%            |
|Cash_Monthly|2015;06|Orkney Islands     |0.004     |60       |12778      |0.004695571      |-17.39%           |
|Cash_Monthly|2015;06|Perth & Kinross    |0.012     |1070     |95000      |0.011263158      |6.14%             |
|Cash_Monthly|2015;06|Scottish Borders   |0.016     |1075     |69211      |0.015532213      |2.92%             |
|Cash_Monthly|2015;06|Shetland Islands   |0.006     |90       |14500      |0.006206897      |-3.45%            |
|Cash_Monthly|2015;06|West Lothian       |0.018     |2070     |118056     |0.017534052      |2.59%             |
|Cash_Monthly|2015;07|East Dunbartonshire|0.013     |880      |63333      |0.01389481       |-6.88%            |
|Cash_Monthly|2015;07|East Renfrewshire  |0.013     |715      |56818      |0.01258404       |3.20%             |
|Cash_Monthly|2015;07|Glasgow City       |0.036     |15185    |439219     |0.03457273       |3.96%             |
|Cash_Monthly|2015;07|Highland           |0.014     |2015     |140833     |0.014307726      |-2.20%            |
|Cash_Monthly|2015;07|Midlothian         |0.018     |960      |56471      |0.016999876      |5.56%             |
|Cash_Monthly|2015;07|Moray              |0.013     |785      |58947      |0.013317048      |-2.44%            |
|Cash_Monthly|2015;07|Orkney Islands     |0.005     |70       |12778      |0.005478166      |-9.56%            |
|Cash_Monthly|2015;07|Shetland Islands   |0.006     |85       |14500      |0.005862069      |2.30%             |
|Cash_Monthly|2015;07|Stirling           |0.015     |885      |62188      |0.014231041      |5.13%             |
|Cash_Monthly|2015;08|Aberdeen City      |0.014     |2350     |163500     |0.014373089      |-2.66%            |
|Cash_Monthly|2015;08|Aberdeenshire      |0.009     |1430     |165667     |0.008631773      |4.09%             |
|Cash_Monthly|2015;08|Argyll & Bute      |0.017     |865      |53056      |0.016303528      |4.10%             |
|Cash_Monthly|2015;08|Dumfries & Galloway|0.019     |1740     |88889      |0.019574976      |-3.03%            |
|Cash_Monthly|2015;08|East Dunbartonshire|0.013     |855      |63333      |0.013500071      |-3.85%            |
|Cash_Monthly|2015;08|East Lothian       |0.017     |1080     |65294      |0.01654057       |2.70%             |
|Cash_Monthly|2015;08|Edinburgh City     |0.015     |5325     |344375     |0.015462795      |-3.09%            |
|Cash_Monthly|2015;08|Eilean Siar        |0.02      |325      |15870      |0.020478891      |-2.39%            |
|Cash_Monthly|2015;08|Falkirk            |0.022     |2280     |99783      |0.022849584      |-3.86%            |
|Cash_Monthly|2015;08|Glasgow City       |0.036     |15135    |439219     |0.034458892      |4.28%             |
|Cash_Monthly|2015;08|Highland           |0.013     |1940     |140833     |0.013775181      |-5.96%            |
|Cash_Monthly|2015;08|North Ayrshire     |0.044     |3745     |83372      |0.044919158      |-2.09%            |
|Cash_Monthly|2015;08|Perth & Kinross    |0.012     |1060     |95000      |0.011157895      |7.02%             |
|Cash_Monthly|2015;08|Scottish Borders   |0.017     |1140     |69211      |0.01647137       |3.11%             |
|Cash_Monthly|2015;08|Shetland Islands   |0.005     |80       |14500      |0.005517241      |-10.34%           |
|Cash_Monthly|2015;08|Stirling           |0.015     |875      |62188      |0.014070239      |6.20%             |
|Cash_Monthly|2015;09|Aberdeenshire      |0.009     |1420     |165667     |0.008571411      |4.76%             |
|Cash_Monthly|2015;09|East Dunbartonshire|0.012     |785      |63333      |0.012394802      |-3.29%            |
|Cash_Monthly|2015;09|Highland           |0.013     |1875     |140833     |0.013313641      |-2.41%            |
|Cash_Monthly|2015;09|Midlothian         |0.017     |930      |56471      |0.01646863       |3.13%             |
|Cash_Monthly|2015;09|Moray              |0.012     |690      |58947      |0.01170543       |2.45%             |
|Cash_Monthly|2015;09|North Lanarkshire  |0.029     |6450     |216034     |0.029856411      |-2.95%            |
|Cash_Monthly|2015;09|Orkney Islands     |0.006     |80       |12778      |0.006260761      |-4.35%            |
|Cash_Monthly|2015;09|Perth & Kinross    |0.011     |980      |95000      |0.010315789      |6.22%             |
|Cash_Monthly|2015;09|Shetland Islands   |0.006     |90       |14500      |0.006206897      |-3.45%            |
|Cash_Monthly|2015;09|Stirling           |0.014     |835      |62188      |0.013427028      |4.09%             |
|Cash_Monthly|2015;09|West Dunbartonshire|0.037     |2175     |57179      |0.038038441      |-2.81%            |
|Cash_Monthly|2015;09|West Lothian       |0.017     |1940     |118056     |0.016432879      |3.34%             |
|Cash_Monthly|2015;10|Aberdeenshire      |0.009     |1530     |165667     |0.009235394      |-2.62%            |
|Cash_Monthly|2015;10|Angus              |0.016     |1145     |69524      |0.016469133      |-2.93%            |
|Cash_Monthly|2015;10|Argyll & Bute      |0.016     |815      |53056      |0.015361128      |3.99%             |
|Cash_Monthly|2015;10|Dumfries & Galloway|0.017     |1545     |88889      |0.017381228      |-2.24%            |
|Cash_Monthly|2015;10|East Renfrewshire  |0.01      |590      |56818      |0.010384033      |-3.84%            |
|Cash_Monthly|2015;10|Glasgow City       |0.032     |13675    |439219     |0.03113481       |2.70%             |
|Cash_Monthly|2015;10|Highland           |0.013     |1925     |140833     |0.013668671      |-5.14%            |
|Cash_Monthly|2015;10|Moray              |0.011     |680      |58947      |0.011535786      |-4.87%            |
|Cash_Monthly|2015;10|Orkney Islands     |0.006     |85       |12778      |0.006652058      |-10.87%           |
|Cash_Monthly|2015;10|Scottish Borders   |0.015     |1010     |69211      |0.014593056      |2.71%             |
|Cash_Monthly|2015;10|Shetland Islands   |0.006     |95       |14500      |0.006551724      |-9.20%            |
|Cash_Monthly|2015;11|Aberdeen City      |0.016     |2530     |163500     |0.015474006      |3.29%             |
|Cash_Monthly|2015;11|Angus              |0.016     |1175     |69524      |0.016900639      |-5.63%            |
|Cash_Monthly|2015;11|East Dunbartonshire|0.01      |665      |63333      |0.010500055      |-5.00%            |
|Cash_Monthly|2015;11|Fife               |0.021     |4795     |234400     |0.020456485      |2.59%             |
|Cash_Monthly|2015;11|Glasgow City       |0.031     |13140    |439219     |0.029916739      |3.49%             |
|Cash_Monthly|2015;11|Highland           |0.014     |2020     |140833     |0.014343229      |-2.45%            |
|Cash_Monthly|2015;11|Inverclyde         |0.027     |1345     |51000      |0.026372549      |2.32%             |
|Cash_Monthly|2015;11|Midlothian         |0.016     |875      |56471      |0.015494679      |3.16%             |
|Cash_Monthly|2015;11|Orkney Islands     |0.006     |80       |12778      |0.006260761      |-4.35%            |
|Cash_Monthly|2015;11|Perth & Kinross    |0.01      |925      |95000      |0.009736842      |2.63%             |
|Cash_Monthly|2015;11|Shetland Islands   |0.007     |105      |14500      |0.007241379      |-3.45%            |
|Cash_Monthly|2015;11|South Lanarkshire  |0.02      |4110     |200652     |0.020483225      |-2.42%            |
|Cash_Monthly|2015;11|Stirling           |0.014     |845      |62188      |0.01358783       |2.94%             |
|Cash_Monthly|2015;11|West Lothian       |0.016     |1820     |118056     |0.015416413      |3.65%             |
|Cash_Monthly|2015;12|Aberdeen City      |0.016     |2525     |163500     |0.015443425      |3.48%             |
|Cash_Monthly|2015;12|Aberdeenshire      |0.011     |1760     |165667     |0.010623721      |3.42%             |
|Cash_Monthly|2015;12|Angus              |0.017     |1230     |69524      |0.017691732      |-4.07%            |
|Cash_Monthly|2015;12|Argyll & Bute      |0.017     |875      |53056      |0.016492008      |2.99%             |
|Cash_Monthly|2015;12|East Dunbartonshire|0.01      |670      |63333      |0.010579003      |-5.79%            |
|Cash_Monthly|2015;12|East Lothian       |0.016     |1000     |65294      |0.015315343      |4.28%             |
|Cash_Monthly|2015;12|Falkirk            |0.02      |2065     |99783      |0.020694908      |-3.47%            |
|Cash_Monthly|2015;12|Glasgow City       |0.03      |12670    |439219     |0.028846657      |3.84%             |
|Cash_Monthly|2015;12|Highland           |0.015     |2230     |140833     |0.015834357      |-5.56%            |
|Cash_Monthly|2015;12|Moray              |0.013     |750      |58947      |0.012723294      |2.13%             |
|Cash_Monthly|2015;12|North Lanarkshire  |0.026     |5770     |216034     |0.026708759      |-2.73%            |
|Cash_Monthly|2015;12|Orkney Islands     |0.006     |85       |12778      |0.006652058      |-10.87%           |
|Cash_Monthly|2015;12|Scottish Borders   |0.016     |1070     |69211      |0.01545997       |3.38%             |
|Cash_Monthly|2015;12|Shetland Islands   |0.009     |125      |14500      |0.00862069       |4.21%             |
|Cash_Monthly|2015;12|Stirling           |0.014     |845      |62188      |0.01358783       |2.94%             |
|Cash_Monthly|2016;01|Aberdeenshire      |0.012     |2055     |165667     |0.012404402      |-3.37%            |
|Cash_Monthly|2016;01|Dumfries & Galloway|0.018     |1635     |88889      |0.018393727      |-2.19%            |
|Cash_Monthly|2016;01|East Dunbartonshire|0.011     |725      |63333      |0.011447429      |-4.07%            |
|Cash_Monthly|2016;01|East Lothian       |0.016     |1020     |65294      |0.01562165       |2.36%             |
|Cash_Monthly|2016;01|Falkirk            |0.021     |2185     |99783      |0.021897518      |-4.27%            |
|Cash_Monthly|2016;01|Glasgow City       |0.031     |13240    |439219     |0.030144415      |2.76%             |
|Cash_Monthly|2016;01|Highland           |0.016     |2365     |140833     |0.016792939      |-4.96%            |
|Cash_Monthly|2016;01|Midlothian         |0.016     |885      |56471      |0.015671761      |2.05%             |
|Cash_Monthly|2016;01|North Lanarkshire  |0.027     |6030     |216034     |0.027912273      |-3.38%            |
|Cash_Monthly|2016;01|Orkney Islands     |0.008     |105      |12778      |0.008217248      |-2.72%            |
|Cash_Monthly|2016;01|Perth & Kinross    |0.012     |1090     |95000      |0.011473684      |4.39%             |
|Cash_Monthly|2016;01|Renfrewshire       |0.025     |2885     |112222     |0.025707972      |-2.83%            |
|Cash_Monthly|2016;01|Shetland Islands   |0.008     |125      |14500      |0.00862069       |-7.76%            |
|Cash_Monthly|2016;01|Stirling           |0.015     |890      |62188      |0.014311443      |4.59%             |
|Cash_Monthly|2016;02|Aberdeen City      |0.019     |3025     |163500     |0.018501529      |2.62%             |
|Cash_Monthly|2016;02|Clackmannanshire   |0.028     |895      |32679      |0.027387619      |2.19%             |
|Cash_Monthly|2016;02|Dumfries & Galloway|0.019     |1655     |88889      |0.018618727      |2.01%             |
|Cash_Monthly|2016;02|East Renfrewshire  |0.011     |650      |56818      |0.011440037      |-4.00%            |
|Cash_Monthly|2016;02|Edinburgh City     |0.015     |5415     |344375     |0.015724138      |-4.83%            |
|Cash_Monthly|2016;02|Highland           |0.017     |2520     |140833     |0.017893533      |-5.26%            |
|Cash_Monthly|2016;02|Orkney Islands     |0.008     |105      |12778      |0.008217248      |-2.72%            |
|Cash_Monthly|2016;02|Scottish Borders   |0.02      |1345     |69211      |0.019433327      |2.83%             |
|Cash_Monthly|2016;02|Shetland Islands   |0.009     |135      |14500      |0.009310345      |-3.45%            |
|Cash_Monthly|2016;02|Stirling           |0.017     |1005     |62188      |0.016160674      |4.94%             |
|Cash_Monthly|2016;02|West Lothian       |0.018     |2065     |118056     |0.017491699      |2.82%             |
|Cash_Monthly|2016;04|Argyll & Bute      |0.016     |865      |51111      |0.01692395       |-5.77%            |
|Cash_Monthly|2016;04|East Renfrewshire  |0.011     |635      |55769      |0.011386254      |-3.51%            |
|Cash_Monthly|2016;04|Falkirk            |0.022     |2260     |100417     |0.022506149      |-2.30%            |
|Cash_Monthly|2016;04|Fife               |0.024     |5660     |229444     |0.024668329      |-2.78%            |
|Cash_Monthly|2016;04|Highland           |0.016     |2385     |146000     |0.016335616      |-2.10%            |
|Cash_Monthly|2016;04|Midlothian         |0.018     |975      |56944      |0.017122085      |4.88%             |
|Cash_Monthly|2016;04|Orkney Islands     |0.009     |115      |13182      |0.008724018      |3.07%             |
|Cash_Monthly|2016;04|Perth & Kinross    |0.012     |1080     |93077      |0.011603296      |3.31%             |
|Cash_Monthly|2016;04|Shetland Islands   |0.01      |150      |14500      |0.010344828      |-3.45%            |
|Cash_Monthly|2016;04|South Lanarkshire  |0.022     |4560     |198913     |0.022924595      |-4.20%            |
|Cash_Monthly|2016;04|Stirling           |0.015     |910      |59412      |0.015316771      |-2.11%            |
|Cash_Monthly|2016;05|Aberdeenshire      |0.015     |2555     |166875     |0.015310861      |-2.07%            |
|Cash_Monthly|2016;05|Argyll & Bute      |0.016     |850      |51111      |0.016630471      |-3.94%            |
|Cash_Monthly|2016;05|Dumfries & Galloway|0.017     |1540     |86579      |0.017787223      |-4.63%            |
|Cash_Monthly|2016;05|Dundee City        |0.035     |3430     |100152     |0.034247943      |2.15%             |
|Cash_Monthly|2016;05|East Dunbartonshire|0.012     |760      |64643      |0.01175688       |2.03%             |
|Cash_Monthly|2016;05|East Lothian       |0.016     |1025     |66250      |0.015471698      |3.30%             |
|Cash_Monthly|2016;05|East Renfrewshire  |0.011     |630      |55769      |0.011296598      |-2.70%            |
|Cash_Monthly|2016;05|Eilean Siar        |0.021     |340      |15455      |0.021999353      |-4.76%            |
|Cash_Monthly|2016;05|Falkirk            |0.022     |2265     |100417     |0.022555942      |-2.53%            |
|Cash_Monthly|2016;05|Highland           |0.016     |2250     |146000     |0.015410959      |3.68%             |
|Cash_Monthly|2016;05|Moray              |0.018     |1060     |60476      |0.017527614      |2.62%             |
|Cash_Monthly|2016;05|Orkney Islands     |0.008     |100      |13182      |0.007586102      |5.17%             |
|Cash_Monthly|2016;05|Perth & Kinross    |0.011     |1050     |93077      |0.011280982      |-2.55%            |
|Cash_Monthly|2016;05|South Lanarkshire  |0.022     |4485     |198913     |0.022547546      |-2.49%            |
|Cash_Monthly|2016;05|West Lothian       |0.018     |2115     |114500     |0.018471616      |-2.62%            |
|Cash_Monthly|2016;06|Aberdeenshire      |0.016     |2575     |166875     |0.015430712      |3.56%             |
|Cash_Monthly|2016;06|Argyll & Bute      |0.016     |845      |51111      |0.016532645      |-3.33%            |
|Cash_Monthly|2016;06|Dumfries & Galloway|0.017     |1525     |86579      |0.017613971      |-3.61%            |
|Cash_Monthly|2016;06|East Dunbartonshire|0.011     |750      |64643      |0.011602184      |-5.47%            |
|Cash_Monthly|2016;06|East Renfrewshire  |0.011     |640      |55769      |0.01147591       |-4.33%            |
|Cash_Monthly|2016;06|Edinburgh City     |0.015     |5285     |359667     |0.014694148      |2.04%             |
|Cash_Monthly|2016;06|Fife               |0.024     |5625     |229444     |0.024515786      |-2.15%            |
|Cash_Monthly|2016;06|Midlothian         |0.016     |885      |56944      |0.015541585      |2.87%             |
|Cash_Monthly|2016;06|Perth & Kinross    |0.011     |1060     |93077      |0.01138842       |-3.53%            |
|Cash_Monthly|2016;06|Scottish Borders   |0.016     |1120     |66842      |0.016755932      |-4.72%            |
|Cash_Monthly|2016;06|Shetland Islands   |0.009     |135      |14500      |0.009310345      |-3.45%            |
|Cash_Monthly|2016;07|Aberdeenshire      |0.016     |2565     |166875     |0.015370787      |3.93%             |
|Cash_Monthly|2016;07|Argyll & Bute      |0.016     |840      |51111      |0.016434818      |-2.72%            |
|Cash_Monthly|2016;07|Clackmannanshire   |0.026     |835      |32931      |0.025356047      |2.48%             |
|Cash_Monthly|2016;07|Dumfries & Galloway|0.017     |1515     |86579      |0.01749847       |-2.93%            |
|Cash_Monthly|2016;07|East Lothian       |0.017     |1080     |66250      |0.016301887      |4.11%             |
|Cash_Monthly|2016;07|East Renfrewshire  |0.012     |690      |55769      |0.012372465      |-3.10%            |
|Cash_Monthly|2016;07|Edinburgh City     |0.015     |5255     |359667     |0.014610737      |2.60%             |
|Cash_Monthly|2016;07|Falkirk            |0.021     |2185     |100417     |0.021759264      |-3.62%            |
|Cash_Monthly|2016;07|Midlothian         |0.016     |885      |56944      |0.015541585      |2.87%             |
|Cash_Monthly|2016;07|Moray              |0.017     |985      |60476      |0.016287453      |4.19%             |
|Cash_Monthly|2016;07|Orkney Islands     |0.008     |110      |13182      |0.008344712      |-4.31%            |
|Cash_Monthly|2016;07|Perth & Kinross    |0.012     |1075     |93077      |0.011549577      |3.75%             |
|Cash_Monthly|2016;07|Scottish Borders   |0.016     |1120     |66842      |0.016755932      |-4.72%            |
|Cash_Monthly|2016;07|Shetland Islands   |0.009     |125      |14500      |0.00862069       |4.21%             |
|Cash_Monthly|2016;07|South Ayrshire     |0.025     |1670     |68269      |0.024462055      |2.15%             |
|Cash_Monthly|2016;07|Stirling           |0.015     |935      |59412      |0.015737561      |-4.92%            |
|Cash_Monthly|2016;08|Aberdeen City      |0.023     |3635     |161458     |0.022513595      |2.11%             |
|Cash_Monthly|2016;08|Aberdeenshire      |0.015     |2560     |166875     |0.015340824      |-2.27%            |
|Cash_Monthly|2016;08|Angus              |0.022     |1580     |70227      |0.022498469      |-2.27%            |
|Cash_Monthly|2016;08|Dumfries & Galloway|0.017     |1520     |86579      |0.01755622       |-3.27%            |
|Cash_Monthly|2016;08|East Ayrshire      |0.034     |2640     |76000      |0.034736842      |-2.17%            |
|Cash_Monthly|2016;08|East Dunbartonshire|0.013     |820      |64643      |0.012685055      |2.42%             |
|Cash_Monthly|2016;08|East Lothian       |0.017     |1075     |66250      |0.016226415      |4.55%             |
|Cash_Monthly|2016;08|East Renfrewshire  |0.013     |740      |55769      |0.01326902       |-2.07%            |
|Cash_Monthly|2016;08|Edinburgh City     |0.015     |5235     |359667     |0.01455513       |2.97%             |
|Cash_Monthly|2016;08|Falkirk            |0.022     |2255     |100417     |0.022456357      |-2.07%            |
|Cash_Monthly|2016;08|Fife               |0.026     |6125     |229444     |0.026694967      |-2.67%            |
|Cash_Monthly|2016;08|Highland           |0.014     |2100     |146000     |0.014383562      |-2.74%            |
|Cash_Monthly|2016;08|Midlothian         |0.016     |885      |56944      |0.015541585      |2.87%             |
|Cash_Monthly|2016;08|Moray              |0.016     |935      |60476      |0.015460679      |3.37%             |
|Cash_Monthly|2016;08|Scottish Borders   |0.016     |1110     |66842      |0.016606325      |-3.79%            |
|Cash_Monthly|2016;08|South Ayrshire     |0.026     |1735     |68269      |0.02541417       |2.25%             |
|Cash_Monthly|2016;08|Stirling           |0.015     |925      |59412      |0.015569245      |-3.79%            |
|Cash_Monthly|2016;08|West Lothian       |0.019     |2230     |114500     |0.019475983      |-2.51%            |
|Cash_Monthly|2016;09|Angus              |0.02      |1440     |70227      |0.020504934      |-2.52%            |
|Cash_Monthly|2016;09|Argyll & Bute      |0.016     |850      |51111      |0.016630471      |-3.94%            |
|Cash_Monthly|2016;09|Clackmannanshire   |0.026     |830      |32931      |0.025204215      |3.06%             |
|Cash_Monthly|2016;09|Dumfries & Galloway|0.016     |1440     |86579      |0.016632209      |-3.95%            |
|Cash_Monthly|2016;09|Dundee City        |0.037     |3600     |100152     |0.035945363      |2.85%             |
|Cash_Monthly|2016;09|East Ayrshire      |0.032     |2495     |76000      |0.032828947      |-2.59%            |
|Cash_Monthly|2016;09|East Dunbartonshire|0.012     |805      |64643      |0.012453011      |-3.78%            |
|Cash_Monthly|2016;09|East Lothian       |0.017     |1100     |66250      |0.016603774      |2.33%             |
|Cash_Monthly|2016;09|Eilean Siar        |0.018     |290      |15455      |0.018764154      |-4.25%            |
|Cash_Monthly|2016;09|Falkirk            |0.021     |2180     |100417     |0.021709472      |-3.38%            |
|Cash_Monthly|2016;09|Fife               |0.024     |5620     |229444     |0.024493994      |-2.06%            |
|Cash_Monthly|2016;09|Midlothian         |0.016     |870      |56944      |0.015278168      |4.51%             |
|Cash_Monthly|2016;09|Moray              |0.015     |870      |60476      |0.014385872      |4.09%             |
|Cash_Monthly|2016;09|Perth & Kinross    |0.011     |985      |93077      |0.010582636      |3.79%             |
|Cash_Monthly|2016;09|Shetland Islands   |0.009     |125      |14500      |0.00862069       |4.21%             |
|Cash_Monthly|2016;09|South Ayrshire     |0.025     |1670     |68269      |0.024462055      |2.15%             |
|Cash_Monthly|2016;10|Aberdeen City      |0.022     |3460     |161458     |0.021429722      |2.59%             |
|Cash_Monthly|2016;10|Clackmannanshire   |0.026     |830      |32931      |0.025204215      |3.06%             |
|Cash_Monthly|2016;10|East Dunbartonshire|0.012     |795      |64643      |0.012298315      |-2.49%            |
|Cash_Monthly|2016;10|East Lothian       |0.018     |1150     |66250      |0.017358491      |3.56%             |
|Cash_Monthly|2016;10|East Renfrewshire  |0.013     |710      |55769      |0.012731087      |2.07%             |
|Cash_Monthly|2016;10|Eilean Siar        |0.019     |305      |15455      |0.019734714      |-3.87%            |
|Cash_Monthly|2016;10|Fife               |0.023     |5415     |229444     |0.02360053       |-2.61%            |
|Cash_Monthly|2016;10|Orkney Islands     |0.008     |115      |13182      |0.008724018      |-9.05%            |
|Cash_Monthly|2016;10|Perth & Kinross    |0.01      |970      |93077      |0.010421479      |-4.21%            |
|Cash_Monthly|2016;10|Stirling           |0.015     |940      |59412      |0.01582172       |-5.48%            |
|Cash_Monthly|2016;11|Angus              |0.02      |1435     |70227      |0.020433736      |-2.17%            |
|Cash_Monthly|2016;11|Argyll & Bute      |0.016     |835      |51111      |0.016336992      |-2.11%            |
|Cash_Monthly|2016;11|East Dunbartonshire|0.011     |750      |64643      |0.011602184      |-5.47%            |
|Cash_Monthly|2016;11|East Lothian       |0.019     |1225     |66250      |0.018490566      |2.68%             |
|Cash_Monthly|2016;11|East Renfrewshire  |0.012     |710      |55769      |0.012731087      |-6.09%            |
|Cash_Monthly|2016;11|Eilean Siar        |0.019     |310      |15455      |0.020058234      |-5.57%            |
|Cash_Monthly|2016;11|Highland           |0.016     |2250     |146000     |0.015410959      |3.68%             |
|Cash_Monthly|2016;11|Midlothian         |0.016     |870      |56944      |0.015278168      |4.51%             |
|Cash_Monthly|2016;11|Moray              |0.015     |880      |60476      |0.014551227      |2.99%             |
|Cash_Monthly|2016;11|Perth & Kinross    |0.011     |990      |93077      |0.010636355      |3.31%             |
|Cash_Monthly|2016;11|Scottish Borders   |0.015     |1050     |66842      |0.015708686      |-4.72%            |
|Cash_Monthly|2016;11|South Ayrshire     |0.025     |1670     |68269      |0.024462055      |2.15%             |
|Cash_Monthly|2016;11|South Lanarkshire  |0.021     |4315     |198913     |0.021692901      |-3.30%            |
|Cash_Monthly|2016;11|Stirling           |0.016     |975      |59412      |0.016410826      |-2.57%            |
|Cash_Monthly|2016;12|Argyll & Bute      |0.016     |855      |51111      |0.016728297      |-4.55%            |
|Cash_Monthly|2016;12|Dumfries & Galloway|0.016     |1455     |86579      |0.016805461      |-5.03%            |
|Cash_Monthly|2016;12|Dundee City        |0.033     |3215     |100152     |0.032101206      |2.72%             |
|Cash_Monthly|2016;12|East Lothian       |0.02      |1270     |66250      |0.019169811      |4.15%             |
|Cash_Monthly|2016;12|East Renfrewshire  |0.012     |685      |55769      |0.012282809      |-2.36%            |
|Cash_Monthly|2016;12|Edinburgh City     |0.014     |4930     |359667     |0.013707124      |2.09%             |
|Cash_Monthly|2016;12|Eilean Siar        |0.019     |305      |15455      |0.019734714      |-3.87%            |
|Cash_Monthly|2016;12|Fife               |0.023     |5445     |229444     |0.023731281      |-3.18%            |
|Cash_Monthly|2016;12|Midlothian         |0.016     |860      |56944      |0.015102557      |5.61%             |
|Cash_Monthly|2016;12|North Lanarkshire  |0.026     |5610     |220714     |0.025417509      |2.24%             |
|Cash_Monthly|2016;12|Perth & Kinross    |0.011     |995      |93077      |0.010690074      |2.82%             |
|Cash_Monthly|2016;12|Shetland Islands   |0.008     |120      |14500      |0.008275862      |-3.45%            |
|Cash_Monthly|2016;12|West Lothian       |0.016     |1875     |114500     |0.016375546      |-2.35%            |
|Cash_Monthly|2017;01|Aberdeen City      |0.023     |3605     |161458     |0.022327788      |2.92%             |
|Cash_Monthly|2017;01|Argyll & Bute      |0.017     |890      |51111      |0.017413081      |-2.43%            |
|Cash_Monthly|2017;01|Dumfries & Galloway|0.017     |1515     |86579      |0.01749847       |-2.93%            |
|Cash_Monthly|2017;01|East Dunbartonshire|0.012     |760      |64643      |0.01175688       |2.03%             |
|Cash_Monthly|2017;01|East Lothian       |0.021     |1350     |66250      |0.020377358      |2.96%             |
|Cash_Monthly|2017;01|Eilean Siar        |0.019     |305      |15455      |0.019734714      |-3.87%            |
|Cash_Monthly|2017;01|Falkirk            |0.022     |2285     |100417     |0.022755111      |-3.43%            |
|Cash_Monthly|2017;01|Fife               |0.025     |5880     |229444     |0.025627168      |-2.51%            |
|Cash_Monthly|2017;01|Highland           |0.019     |2700     |146000     |0.018493151      |2.67%             |
|Cash_Monthly|2017;01|Midlothian         |0.016     |890      |56944      |0.01562939       |2.32%             |
|Cash_Monthly|2017;01|Moray              |0.019     |1125     |60476      |0.018602421      |2.09%             |
|Cash_Monthly|2017;01|Perth & Kinross    |0.012     |1075     |93077      |0.011549577      |3.75%             |
|Cash_Monthly|2017;01|Shetland Islands   |0.01      |140      |14500      |0.009655172      |3.45%             |
|Cash_Monthly|2017;01|South Ayrshire     |0.026     |1735     |68269      |0.02541417       |2.25%             |
|Cash_Monthly|2017;01|Stirling           |0.016     |985      |59412      |0.016579142      |-3.62%            |
|Cash_Monthly|2017;01|West Lothian       |0.017     |2010     |114500     |0.017554585      |-3.26%            |
|Cash_Monthly|2017;02|Aberdeen City      |0.024     |3785     |161458     |0.023442629      |2.32%             |
|Cash_Monthly|2017;02|Aberdeenshire      |0.016     |2610     |166875     |0.015640449      |2.25%             |
|Cash_Monthly|2017;02|Clackmannanshire   |0.029     |930      |32931      |0.028240867      |2.62%             |
|Cash_Monthly|2017;02|Dumfries & Galloway|0.018     |1620     |86579      |0.018711235      |-3.95%            |
|Cash_Monthly|2017;02|East Ayrshire      |0.034     |2640     |76000      |0.034736842      |-2.17%            |
|Cash_Monthly|2017;02|East Dunbartonshire|0.013     |820      |64643      |0.012685055      |2.42%             |
|Cash_Monthly|2017;02|East Renfrewshire  |0.012     |710      |55769      |0.012731087      |-6.09%            |
|Cash_Monthly|2017;02|Edinburgh City     |0.015     |5285     |359667     |0.014694148      |2.04%             |
|Cash_Monthly|2017;02|Eilean Siar        |0.02      |320      |15455      |0.020705273      |-3.53%            |
|Cash_Monthly|2017;02|Falkirk            |0.023     |2365     |100417     |0.023551789      |-2.40%            |
|Cash_Monthly|2017;02|Fife               |0.026     |6140     |229444     |0.026760342      |-2.92%            |
|Cash_Monthly|2017;02|Highland           |0.02      |2845     |146000     |0.019486301      |2.57%             |
|Cash_Monthly|2017;02|Moray              |0.021     |1215     |60476      |0.020090614      |4.33%             |
|Cash_Monthly|2017;02|Orkney Islands     |0.01      |140      |13182      |0.010620543      |-6.21%            |
|Cash_Monthly|2017;02|Perth & Kinross    |0.013     |1165     |93077      |0.012516519      |3.72%             |
|Cash_Monthly|2017;02|Renfrewshire       |0.026     |3005     |112407     |0.026733211      |-2.82%            |
|Cash_Monthly|2017;02|Scottish Borders   |0.018     |1235     |66842      |0.018476407      |-2.65%            |
|Cash_Monthly|2017;02|Shetland Islands   |0.01      |135      |14500      |0.009310345      |6.90%             |
|Cash_Monthly|2017;02|South Ayrshire     |0.027     |1785     |68269      |0.026146567      |3.16%             |
|Cash_Monthly|2017;02|South Lanarkshire  |0.022     |4480     |198913     |0.022522409      |-2.37%            |
|Cash_Monthly|2017;02|Stirling           |0.016     |990      |59412      |0.0166633        |-4.15%            |
|Cash_Monthly|2017;04|Aberdeen City      |0.024     |3825     |156136     |0.024497874      |-2.07%            |
|Cash_Monthly|2017;04|Dundee City        |0.034     |3320     |99730      |0.033289883      |2.09%             |
|Cash_Monthly|2017;04|East Ayrshire      |0.033     |2550     |75375      |0.033830846      |-2.52%            |
|Cash_Monthly|2017;04|East Dunbartonshire|0.015     |980      |63333      |0.015473766      |-3.16%            |
|Cash_Monthly|2017;04|Eilean Siar        |0.02      |320      |15526      |0.020610589      |-3.05%            |
|Cash_Monthly|2017;04|Glasgow City       |0.033     |14385    |445000     |0.032325843      |2.04%             |
|Cash_Monthly|2017;04|Orkney Islands     |0.011     |145      |13889      |0.010439916      |5.09%             |
|Cash_Monthly|2017;04|Shetland Islands   |0.01      |140      |13333      |0.010500263      |-5.00%            |
|Cash_Monthly|2017;04|West Dunbartonshire|0.036     |2095     |56410      |0.037138805      |-3.16%            |
|Cash_Monthly|2017;04|West Lothian       |0.019     |2275     |115263     |0.01973747       |-3.88%            |
|Cash_Monthly|2017;05|Aberdeenshire      |0.015     |2500     |158214     |0.015801383      |-5.34%            |
|Cash_Monthly|2017;05|Argyll & Bute      |0.017     |885      |50833      |0.01740995       |-2.41%            |
|Cash_Monthly|2017;05|Dumfries & Galloway|0.017     |1525     |87105      |0.017507606      |-2.99%            |
|Cash_Monthly|2017;05|East Ayrshire      |0.032     |2480     |75375      |0.032902156      |-2.82%            |
|Cash_Monthly|2017;05|East Dunbartonshire|0.015     |1005     |63333      |0.015868505      |-5.79%            |
|Cash_Monthly|2017;05|East Renfrewshire  |0.012     |665      |57917      |0.011481948      |4.32%             |
|Cash_Monthly|2017;05|Glasgow City       |0.033     |14250    |445000     |0.032022472      |2.96%             |
|Cash_Monthly|2017;05|Highland           |0.02      |2945     |143846     |0.020473284      |-2.37%            |
|Cash_Monthly|2017;05|North Lanarkshire  |0.028     |6065     |221071     |0.027434625      |2.02%             |
|Cash_Monthly|2017;05|Orkney Islands     |0.01      |130      |13889      |0.009359925      |6.40%             |
|Cash_Monthly|2017;05|Perth & Kinross    |0.012     |1135     |91154      |0.012451456      |-3.76%            |
|Cash_Monthly|2017;05|Scottish Borders   |0.017     |1180     |67353      |0.017519635      |-3.06%            |
|Cash_Monthly|2017;05|Shetland Islands   |0.009     |130      |13333      |0.009750244      |-8.34%            |
|Cash_Monthly|2017;06|Aberdeen City      |0.023     |3700     |156136     |0.02369729       |-3.03%            |
|Cash_Monthly|2017;06|Angus              |0.022     |1570     |69231      |0.022677702      |-3.08%            |
|Cash_Monthly|2017;06|Argyll & Bute      |0.017     |885      |50833      |0.01740995       |-2.41%            |
|Cash_Monthly|2017;06|Dumfries & Galloway|0.017     |1545     |87105      |0.017737214      |-4.34%            |
|Cash_Monthly|2017;06|Edinburgh City     |0.015     |5240     |359286     |0.014584481      |2.77%             |
|Cash_Monthly|2017;06|Eilean Siar        |0.018     |290      |15526      |0.018678346      |-3.77%            |
|Cash_Monthly|2017;06|Moray              |0.018     |1060     |57619      |0.018396709      |-2.20%            |
|Cash_Monthly|2017;06|Shetland Islands   |0.008     |115      |13333      |0.008625216      |-7.82%            |
|Cash_Monthly|2017;06|South Lanarkshire  |0.021     |4325     |200714     |0.021548073      |-2.61%            |
|Cash_Monthly|2017;06|Stirling           |0.016     |945      |61304      |0.015414981      |3.66%             |
|Cash_Monthly|2017;06|West Dunbartonshire|0.034     |1980     |56410      |0.03510016       |-3.24%            |
|Cash_Monthly|2017;07|Aberdeenshire      |0.014     |2340     |158214     |0.014790094      |-5.64%            |
|Cash_Monthly|2017;07|East Ayrshire      |0.033     |2555     |75375      |0.033897181      |-2.72%            |
|Cash_Monthly|2017;07|East Dunbartonshire|0.017     |1100     |63333      |0.017368512      |-2.17%            |
|Cash_Monthly|2017;07|East Renfrewshire  |0.012     |660      |57917      |0.011395618      |5.04%             |
|Cash_Monthly|2017;07|Eilean Siar        |0.018     |290      |15526      |0.018678346      |-3.77%            |
|Cash_Monthly|2017;07|Glasgow City       |0.033     |14270    |445000     |0.032067416      |2.83%             |
|Cash_Monthly|2017;07|Moray              |0.018     |1060     |57619      |0.018396709      |-2.20%            |
|Cash_Monthly|2017;07|Perth & Kinross    |0.012     |1120     |91154      |0.012286899      |-2.39%            |
|Cash_Monthly|2017;07|Scottish Borders   |0.016     |1125     |67353      |0.016703042      |-4.39%            |
|Cash_Monthly|2017;07|Shetland Islands   |0.008     |110      |13333      |0.008250206      |-3.13%            |
|Cash_Monthly|2017;07|West Dunbartonshire|0.035     |2035     |56410      |0.036075164      |-3.07%            |
|Cash_Monthly|2017;07|West Lothian       |0.018     |2130     |115263     |0.018479477      |-2.66%            |
|Cash_Monthly|2017;08|Aberdeen City      |0.022     |3535     |156136     |0.022640519      |-2.91%            |
|Cash_Monthly|2017;08|Aberdeenshire      |0.014     |2290     |158214     |0.014474067      |-3.39%            |
|Cash_Monthly|2017;08|Argyll & Bute      |0.016     |850      |50833      |0.016721421      |-4.51%            |
|Cash_Monthly|2017;08|East Dunbartonshire|0.017     |1105     |63333      |0.01744746       |-2.63%            |
|Cash_Monthly|2017;08|Edinburgh City     |0.014     |4920     |359286     |0.013693826      |2.19%             |
|Cash_Monthly|2017;08|Eilean Siar        |0.017     |275      |15526      |0.017712225      |-4.19%            |
|Cash_Monthly|2017;08|Falkirk            |0.023     |2390     |101346     |0.023582578      |-2.53%            |
|Cash_Monthly|2017;08|Scottish Borders   |0.016     |1110     |67353      |0.016480335      |-3.00%            |
|Cash_Monthly|2017;08|West Dunbartonshire|0.035     |2025     |56410      |0.03589789       |-2.57%            |
|Cash_Monthly|2017;09|Clackmannanshire   |0.031     |1020     |32195      |0.031681938      |-2.20%            |
|Cash_Monthly|2017;09|East Dunbartonshire|0.017     |1100     |63333      |0.017368512      |-2.17%            |
|Cash_Monthly|2017;09|East Renfrewshire  |0.012     |670      |57917      |0.011568279      |3.60%             |
|Cash_Monthly|2017;09|Edinburgh City     |0.013     |4550     |359286     |0.012664006      |2.58%             |
|Cash_Monthly|2017;09|Midlothian         |0.022     |1255     |55741      |0.022514845      |-2.34%            |
|Cash_Monthly|2017;09|Moray              |0.016     |970      |57619      |0.016834725      |-5.22%            |
|Cash_Monthly|2017;09|Orkney Islands     |0.007     |100      |13889      |0.007199942      |-2.86%            |
|Cash_Monthly|2017;09|Renfrewshire       |0.026     |3010     |112759     |0.0266941        |-2.67%            |
|Cash_Monthly|2017;09|Shetland Islands   |0.006     |85       |13333      |0.006375159      |-6.25%            |
|Cash_Monthly|2017;09|South Ayrshire     |0.024     |1580     |67400      |0.023442136      |2.32%             |
|Cash_Monthly|2017;09|South Lanarkshire  |0.021     |4345     |200714     |0.021647718      |-3.08%            |
|Cash_Monthly|2017;09|West Dunbartonshire|0.033     |1915     |56410      |0.033947882      |-2.87%            |
|Cash_Monthly|2017;10|Aberdeen City      |0.02      |3205     |156136     |0.020526976      |-2.63%            |
|Cash_Monthly|2017;10|Aberdeenshire      |0.012     |2025     |158214     |0.01279912       |-6.66%            |
|Cash_Monthly|2017;10|East Ayrshire      |0.031     |2385     |75375      |0.031641791      |-2.07%            |
|Cash_Monthly|2017;10|East Renfrewshire  |0.011     |615      |57917      |0.010618644      |3.47%             |
|Cash_Monthly|2017;10|Edinburgh City     |0.012     |4470     |359286     |0.012441342      |-3.68%            |
|Cash_Monthly|2017;10|Falkirk            |0.021     |2190     |101346     |0.021609141      |-2.90%            |
|Cash_Monthly|2017;10|Midlothian         |0.023     |1315     |55741      |0.023591252      |-2.57%            |
|Cash_Monthly|2017;10|North Ayrshire     |0.037     |3110     |82111      |0.037875559      |-2.37%            |
|Cash_Monthly|2017;10|Orkney Islands     |0.008     |105      |13889      |0.00755994       |5.50%             |
|Cash_Monthly|2017;10|Perth & Kinross    |0.01      |965      |91154      |0.01058648       |-5.86%            |
|Cash_Monthly|2017;10|Shetland Islands   |0.005     |75       |13333      |0.005625141      |-12.50%           |
|Cash_Monthly|2017;10|West Dunbartonshire|0.032     |1865     |56410      |0.033061514      |-3.32%            |
|Cash_Monthly|2017;10|West Lothian       |0.016     |1910     |115263     |0.016570799      |-3.57%            |
|Cash_Monthly|2017;11|Aberdeenshire      |0.012     |1965     |158214     |0.012419887      |-3.50%            |
|Cash_Monthly|2017;11|Argyll & Bute      |0.016     |850      |50833      |0.016721421      |-4.51%            |
|Cash_Monthly|2017;11|Dumfries & Galloway|0.016     |1455     |87105      |0.016703978      |-4.40%            |
|Cash_Monthly|2017;11|East Dunbartonshire|0.016     |1060     |63333      |0.01673693       |-4.61%            |
|Cash_Monthly|2017;11|East Lothian       |0.026     |1715     |64310      |0.026667703      |-2.57%            |
|Cash_Monthly|2017;11|Edinburgh City     |0.012     |4470     |359286     |0.012441342      |-3.68%            |
|Cash_Monthly|2017;11|Glasgow City       |0.031     |13430    |445000     |0.030179775      |2.65%             |
|Cash_Monthly|2017;11|Midlothian         |0.023     |1315     |55741      |0.023591252      |-2.57%            |
|Cash_Monthly|2017;11|North Lanarkshire  |0.026     |5605     |221071     |0.025353846      |2.49%             |
|Cash_Monthly|2017;11|Orkney Islands     |0.008     |115      |13889      |0.008279934      |-3.50%            |
|Cash_Monthly|2017;11|Perth & Kinross    |0.011     |980      |91154      |0.010751037      |2.26%             |
|Cash_Monthly|2017;11|Renfrewshire       |0.026     |3015     |112759     |0.026738442      |-2.84%            |
|Cash_Monthly|2017;11|Shetland Islands   |0.006     |85       |13333      |0.006375159      |-6.25%            |
|Cash_Monthly|2017;11|West Dunbartonshire|0.033     |1920     |56410      |0.034036518      |-3.14%            |
|Cash_Monthly|2017;12|Aberdeenshire      |0.012     |2045     |158214     |0.012925531      |-7.71%            |
|Cash_Monthly|2017;12|Argyll & Bute      |0.017     |900      |50833      |0.017705034      |-4.15%            |
|Cash_Monthly|2017;12|East Dunbartonshire|0.016     |1070     |63333      |0.016894826      |-5.59%            |
|Cash_Monthly|2017;12|Edinburgh City     |0.013     |4480     |359286     |0.012469175      |4.08%             |
|Cash_Monthly|2017;12|Eilean Siar        |0.017     |270      |15526      |0.017390184      |-2.30%            |
|Cash_Monthly|2017;12|Falkirk            |0.021     |2190     |101346     |0.021609141      |-2.90%            |
|Cash_Monthly|2017;12|Fife               |0.024     |5635     |229194     |0.024586158      |-2.44%            |
|Cash_Monthly|2017;12|Glasgow City       |0.031     |13455    |445000     |0.030235955      |2.46%             |
|Cash_Monthly|2017;12|Highland           |0.023     |3380     |143846     |0.023497351      |-2.16%            |
|Cash_Monthly|2017;12|Moray              |0.017     |1010     |57619      |0.01752894       |-3.11%            |
|Cash_Monthly|2017;12|Orkney Islands     |0.009     |115      |13889      |0.008279934      |8.00%             |
|Cash_Monthly|2017;12|West Dunbartonshire|0.034     |1970     |56410      |0.034922886      |-2.71%            |
|Cash_Monthly|2018;01|Aberdeenshire      |0.013     |2150     |158214     |0.013589189      |-4.53%            |
|Cash_Monthly|2018;01|East Renfrewshire  |0.012     |670      |57917      |0.011568279      |3.60%             |
|Cash_Monthly|2018;01|Fife               |0.025     |5905     |229194     |0.0257642        |-3.06%            |
|Cash_Monthly|2018;01|Highland           |0.024     |3525     |143846     |0.024505374      |-2.11%            |
|Cash_Monthly|2018;01|Moray              |0.019     |1140     |57619      |0.01978514       |-4.13%            |
|Cash_Monthly|2018;01|Orkney Islands     |0.009     |120      |13889      |0.008639931      |4.00%             |
|Cash_Monthly|2018;01|Perth & Kinross    |0.012     |1065     |91154      |0.011683525      |2.64%             |
|Cash_Monthly|2018;01|Shetland Islands   |0.007     |105      |13333      |0.007875197      |-12.50%           |
|Cash_Monthly|2018;01|South Ayrshire     |0.025     |1640     |67400      |0.024332344      |2.67%             |
|Cash_Monthly|2018;01|West Dunbartonshire|0.036     |2080     |56410      |0.036872895      |-2.42%            |
|Cash_Monthly|2018;02|Argyll & Bute      |0.018     |940      |50833      |0.018491925      |-2.73%            |
|Cash_Monthly|2018;02|Dumfries & Galloway|0.019     |1700     |87105      |0.019516675      |-2.72%            |
|Cash_Monthly|2018;02|East Lothian       |0.028     |1850     |64310      |0.02876691       |-2.74%            |
|Cash_Monthly|2018;02|Orkney Islands     |0.01      |130      |13889      |0.009359925      |6.40%             |
|Cash_Monthly|2018;02|Perth & Kinross    |0.012     |1130     |91154      |0.012396604      |-3.31%            |
|Cash_Monthly|2018;02|Renfrewshire       |0.028     |3245     |112759     |0.028778191      |-2.78%            |
|Cash_Monthly|2018;02|Shetland Islands   |0.008     |110      |13333      |0.008250206      |-3.13%            |
|Cash_Monthly|2018;02|Stirling           |0.022     |1310     |61304      |0.021368916      |2.87%             |
|Cash_Monthly|2018;04|Aberdeen City      |0.022     |3430     |160714     |0.02134226       |2.99%             |
|Cash_Monthly|2018;04|Argyll & Bute      |0.017     |890      |50926      |0.017476338      |-2.80%            |
|Cash_Monthly|2018;04|East Renfrewshire  |0.012     |700      |55667      |0.012574775      |-4.79%            |
|Cash_Monthly|2018;04|Edinburgh City     |0.014     |5040     |368333     |0.01368327       |2.26%             |
|Cash_Monthly|2018;04|Eilean Siar        |0.018     |280      |15217      |0.018400473      |-2.22%            |
|Cash_Monthly|2018;04|Fife               |0.034     |7790     |233974     |0.033294298      |2.08%             |
|Cash_Monthly|2018;04|Moray              |0.019     |1145     |58846      |0.019457567      |-2.41%            |
|Cash_Monthly|2018;04|Perth & Kinross    |0.013     |1165     |92632      |0.012576647      |3.26%             |
|Cash_Monthly|2018;04|Renfrewshire       |0.029     |3270     |115938     |0.02820473       |2.74%             |
|Cash_Monthly|2018;04|Shetland Islands   |0.009     |130      |13571      |0.00957925       |-6.44%            |
|Cash_Monthly|2018;04|West Dunbartonshire|0.038     |2175     |55952      |0.038872605      |-2.30%            |
|Cash_Monthly|2018;05|Aberdeen City      |0.021     |3295     |160714     |0.020502259      |2.37%             |
|Cash_Monthly|2018;05|East Dunbartonshire|0.017     |1140     |63684      |0.017900886      |-5.30%            |
|Cash_Monthly|2018;05|East Renfrewshire  |0.012     |685      |55667      |0.012305316      |-2.54%            |
|Cash_Monthly|2018;05|Edinburgh City     |0.014     |4940     |368333     |0.013411777      |4.20%             |
|Cash_Monthly|2018;05|Glasgow City       |0.032     |13935    |446944     |0.031178403      |2.57%             |
|Cash_Monthly|2018;05|Orkney Islands     |0.008     |100      |13929      |0.007179266      |10.26%            |
|Cash_Monthly|2018;05|Perth & Kinross    |0.012     |1135     |92632      |0.012252785      |-2.11%            |
|Cash_Monthly|2018;05|Scottish Borders   |0.016     |1110     |66923      |0.016586226      |-3.66%            |
|Cash_Monthly|2018;05|Shetland Islands   |0.008     |120      |13571      |0.008842384      |-10.53%           |
|Cash_Monthly|2018;05|Stirling           |0.023     |1420     |59423      |0.023896471      |-3.90%            |
|Cash_Monthly|2018;05|West Dunbartonshire|0.038     |2175     |55952      |0.038872605      |-2.30%            |
|Cash_Monthly|2018;06|Aberdeenshire      |0.013     |2050     |163438     |0.012542983      |3.52%             |
|Cash_Monthly|2018;06|Argyll & Bute      |0.016     |840      |50926      |0.016494521      |-3.09%            |
|Cash_Monthly|2018;06|East Dunbartonshire|0.017     |1130     |63684      |0.01774386       |-4.38%            |
|Cash_Monthly|2018;06|East Renfrewshire  |0.012     |690      |55667      |0.012395135      |-3.29%            |
|Cash_Monthly|2018;06|Moray              |0.017     |1030     |58846      |0.017503314      |-2.96%            |
|Cash_Monthly|2018;06|Orkney Islands     |0.007     |100      |13929      |0.007179266      |-2.56%            |
|Cash_Monthly|2018;06|Perth & Kinross    |0.012     |1075     |92632      |0.011605061      |3.29%             |
|Cash_Monthly|2018;06|Shetland Islands   |0.009     |125      |13571      |0.009210817      |-2.34%            |
|Cash_Monthly|2018;06|Stirling           |0.023     |1405     |59423      |0.023644044      |-2.80%            |
|Cash_Monthly|2018;06|West Dunbartonshire|0.037     |2130     |55952      |0.038068344      |-2.89%            |
|Cash_Monthly|2018;06|West Lothian       |0.018     |2080     |118393     |0.017568606      |2.40%             |
|Cash_Monthly|2018;07|Aberdeenshire      |0.012     |2015     |163438     |0.012328834      |-2.74%            |
|Cash_Monthly|2018;07|Argyll & Bute      |0.016     |835      |50926      |0.01639634       |-2.48%            |
|Cash_Monthly|2018;07|Dumfries & Galloway|0.02      |1705     |88000      |0.019375         |3.13%             |
|Cash_Monthly|2018;07|East Renfrewshire  |0.012     |700      |55667      |0.012574775      |-4.79%            |
|Cash_Monthly|2018;07|Highland           |0.024     |3520     |142222     |0.024750039      |-3.13%            |
|Cash_Monthly|2018;07|Moray              |0.017     |1030     |58846      |0.017503314      |-2.96%            |
|Cash_Monthly|2018;07|Renfrewshire       |0.028     |3160     |115938     |0.027255947      |2.66%             |
|Cash_Monthly|2018;07|Shetland Islands   |0.009     |130      |13571      |0.00957925       |-6.44%            |
|Cash_Monthly|2018;07|West Dunbartonshire|0.036     |2065     |55952      |0.036906634      |-2.52%            |
|Cash_Monthly|2018;07|West Lothian       |0.019     |2190     |118393     |0.018497715      |2.64%             |
|Cash_Monthly|2018;08|Argyll & Bute      |0.016     |840      |50926      |0.016494521      |-3.09%            |
|Cash_Monthly|2018;08|Dumfries & Galloway|0.021     |1800     |88000      |0.020454545      |2.60%             |
|Cash_Monthly|2018;08|East Renfrewshire  |0.012     |700      |55667      |0.012574775      |-4.79%            |
|Cash_Monthly|2018;08|Edinburgh City     |0.013     |4670     |368333     |0.012678745      |2.47%             |
|Cash_Monthly|2018;08|Eilean Siar        |0.015     |235      |15217      |0.015443254      |-2.96%            |
|Cash_Monthly|2018;08|Orkney Islands     |0.006     |80       |13929      |0.005743413      |4.28%             |
|Cash_Monthly|2018;08|Shetland Islands   |0.009     |135      |13571      |0.009947683      |-10.53%           |
|Cash_Monthly|2018;08|West Dunbartonshire|0.036     |2060     |55952      |0.036817272      |-2.27%            |
|Cash_Monthly|2018;08|West Lothian       |0.02      |2295     |118393     |0.019384592      |3.08%             |
|Cash_Monthly|2018;09|Aberdeenshire      |0.012     |2015     |163438     |0.012328834      |-2.74%            |
|Cash_Monthly|2018;09|East Dunbartonshire|0.017     |1120     |63684      |0.017586835      |-3.45%            |
|Cash_Monthly|2018;09|East Renfrewshire  |0.011     |645      |55667      |0.011586757      |-5.33%            |
|Cash_Monthly|2018;09|Eilean Siar        |0.014     |225      |15217      |0.014786094      |-5.61%            |
|Cash_Monthly|2018;09|Midlothian         |0.024     |1380     |56154      |0.024575275      |-2.40%            |
|Cash_Monthly|2018;09|Orkney Islands     |0.005     |65       |13929      |0.004666523      |6.67%             |
|Cash_Monthly|2018;09|Renfrewshire       |0.025     |2835     |115938     |0.024452725      |2.19%             |
|Cash_Monthly|2018;09|Shetland Islands   |0.009     |125      |13571      |0.009210817      |-2.34%            |
|Cash_Monthly|2018;09|South Ayrshire     |0.034     |2295     |66000      |0.034772727      |-2.27%            |
|Cash_Monthly|2018;09|Stirling           |0.023     |1420     |59423      |0.023896471      |-3.90%            |
|Cash_Monthly|2018;09|West Dunbartonshire|0.034     |1960     |55952      |0.035030026      |-3.03%            |
|Cash_Monthly|2018;09|West Lothian       |0.021     |2405     |118393     |0.020313701      |3.27%             |
|Cash_Monthly|2018;10|East Dunbartonshire|0.017     |1120     |63684      |0.017586835      |-3.45%            |
|Cash_Monthly|2018;10|East Renfrewshire  |0.011     |630      |55667      |0.011317298      |-2.88%            |
|Cash_Monthly|2018;10|Eilean Siar        |0.015     |240      |15217      |0.015771834      |-5.15%            |
|Cash_Monthly|2018;10|Highland           |0.023     |3385     |142222     |0.023800818      |-3.48%            |
|Cash_Monthly|2018;10|Moray              |0.019     |1145     |58846      |0.019457567      |-2.41%            |
|Cash_Monthly|2018;10|Orkney Islands     |0.006     |75       |13929      |0.00538445       |10.26%            |
|Cash_Monthly|2018;10|Perth & Kinross    |0.014     |1255     |92632      |0.013548234      |3.23%             |
|Cash_Monthly|2018;10|Renfrewshire       |0.025     |2805     |115938     |0.024193966      |3.22%             |
|Cash_Monthly|2018;10|Scottish Borders   |0.018     |1260     |66923      |0.018827608      |-4.60%            |
|Cash_Monthly|2018;10|Shetland Islands   |0.008     |120      |13571      |0.008842384      |-10.53%           |
|Cash_Monthly|2018;11|Aberdeen City      |0.018     |2790     |160714     |0.017360031      |3.56%             |
|Cash_Monthly|2018;11|East Dunbartonshire|0.017     |1110     |63684      |0.01742981       |-2.53%            |
|Cash_Monthly|2018;11|Perth & Kinross    |0.015     |1335     |92632      |0.014411866      |3.92%             |
|Cash_Monthly|2018;11|Scottish Borders   |0.02      |1370     |66923      |0.020471288      |-2.36%            |
|Cash_Monthly|2018;11|Shetland Islands   |0.009     |125      |13571      |0.009210817      |-2.34%            |
|Cash_Monthly|2018;11|Stirling           |0.023     |1410     |59423      |0.023728186      |-3.17%            |
|Cash_Monthly|2018;11|West Dunbartonshire|0.034     |1945     |55952      |0.034761939      |-2.24%            |
|Cash_Monthly|2018;12|Aberdeen City      |0.018     |2760     |160714     |0.017173364      |4.59%             |
|Cash_Monthly|2018;12|Aberdeenshire      |0.013     |2180     |163438     |0.013338391      |-2.60%            |
|Cash_Monthly|2018;12|Dumfries & Galloway|0.026     |2230     |88000      |0.025340909      |2.53%             |
|Cash_Monthly|2018;12|East Dunbartonshire|0.017     |1105     |63684      |0.017351297      |-2.07%            |
|Cash_Monthly|2018;12|East Renfrewshire  |0.012     |710      |55667      |0.012754415      |-6.29%            |
|Cash_Monthly|2018;12|Eilean Siar        |0.018     |290      |15217      |0.019057633      |-5.88%            |
|Cash_Monthly|2018;12|Highland           |0.024     |3510     |142222     |0.024679726      |-2.83%            |
|Cash_Monthly|2018;12|Orkney Islands     |0.01      |135      |13929      |0.009692009      |3.08%             |
|Cash_Monthly|2018;12|Perth & Kinross    |0.016     |1445     |92632      |0.015599361      |2.50%             |
|Cash_Monthly|2018;12|Shetland Islands   |0.01      |150      |13571      |0.011052981      |-10.53%           |
|Cash_Monthly|2019;01|Aberdeenshire      |0.014     |2335     |163438     |0.014286763      |-2.05%            |
|Cash_Monthly|2019;01|East Lothian       |0.027     |1800     |65172      |0.027619223      |-2.29%            |
|Cash_Monthly|2019;01|East Renfrewshire  |0.013     |745      |55667      |0.013383153      |-2.95%            |
|Cash_Monthly|2019;01|Orkney Islands     |0.012     |155      |13929      |0.011127863      |7.27%             |
|Cash_Monthly|2019;01|Shetland Islands   |0.011     |155      |13571      |0.011421413      |-3.83%            |
|Cash_Monthly|2019;01|Stirling           |0.024     |1460     |59423      |0.024569611      |-2.37%            |
|Cash_Monthly|2019;02|Aberdeen City      |0.021     |3270     |160714     |0.020346703      |3.11%             |
|Cash_Monthly|2019;02|Midlothian         |0.025     |1440     |56154      |0.025643765      |-2.58%            |
|Cash_Monthly|2019;02|Orkney Islands     |0.014     |185      |13929      |0.013281643      |5.13%             |
|Cash_Monthly|2019;02|Perth & Kinross    |0.019     |1700     |92632      |0.018352189      |3.41%             |
|Cash_Monthly|2019;02|Shetland Islands   |0.013     |185      |13571      |0.013632009      |-4.86%            |
|Cash_Monthly|2019;04|East Renfrewshire  |0.015     |835      |57353      |0.014558959      |2.94%             |
|Cash_Monthly|2019;04|Highland           |0.026     |3725     |146400     |0.025443989      |2.14%             |
|Cash_Monthly|2019;04|Shetland Islands   |0.015     |205      |13947      |0.014698501      |2.01%             |
|Cash_Monthly|2019;05|Highland           |0.025     |3535     |146400     |0.024146175      |3.42%             |
|Cash_Monthly|2019;05|Midlothian         |0.025     |1400     |57500      |0.024347826      |2.61%             |
|Cash_Monthly|2019;05|Moray              |0.025     |1490     |58333      |0.025543003      |-2.17%            |
|Cash_Monthly|2019;05|Perth & Kinross    |0.019     |1725     |93000      |0.018548387      |2.38%             |
|Cash_Monthly|2019;05|Shetland Islands   |0.014     |200      |13947      |0.014340001      |-2.43%            |
|Cash_Monthly|2019;05|Stirling           |0.025     |1485     |61200      |0.024264706      |2.94%             |
|Cash_Monthly|2019;05|West Lothian       |0.028     |3225     |118966     |0.027108586      |3.18%             |
|Cash_Monthly|2019;06|Aberdeen City      |0.022     |3470     |154259     |0.022494636      |-2.25%            |
|Cash_Monthly|2019;06|Aberdeenshire      |0.017     |2665     |164167     |0.01623347       |4.51%             |
|Cash_Monthly|2019;06|East Renfrewshire  |0.016     |890      |57353      |0.015517933      |3.01%             |
|Cash_Monthly|2019;06|Highland           |0.024     |3440     |146400     |0.023497268      |2.09%             |
|Cash_Monthly|2019;06|Shetland Islands   |0.014     |200      |13947      |0.014340001      |-2.43%            |
|Cash_Monthly|2019;07|Aberdeen City      |0.023     |3650     |154259     |0.023661504      |-2.88%            |
|Cash_Monthly|2019;07|Highland           |0.024     |3425     |146400     |0.023394809      |2.52%             |
|Cash_Monthly|2019;07|Moray              |0.025     |1495     |58333      |0.025628718      |-2.51%            |
|Cash_Monthly|2019;07|Perth & Kinross    |0.02      |1790     |93000      |0.019247312      |3.76%             |
|Cash_Monthly|2019;08|Aberdeen City      |0.024     |3830     |154259     |0.024828373      |-3.45%            |
|Cash_Monthly|2019;08|Aberdeenshire      |0.018     |2820     |164167     |0.01717763       |4.57%             |
|Cash_Monthly|2019;08|Angus              |0.033     |2255     |70000      |0.032214286      |2.38%             |
|Cash_Monthly|2019;08|East Dunbartonshire|0.02      |1270     |65000      |0.019538462      |2.31%             |
|Cash_Monthly|2019;08|Edinburgh City     |0.017     |6375     |364250     |0.017501716      |-2.95%            |
|Cash_Monthly|2019;08|Falkirk            |0.032     |3310     |100758     |0.032850989      |-2.66%            |
|Cash_Monthly|2019;08|Moray              |0.025     |1495     |58333      |0.025628718      |-2.51%            |
|Cash_Monthly|2019;08|Orkney Islands     |0.012     |165      |13333      |0.012375309      |-3.13%            |
|Cash_Monthly|2019;09|Aberdeen City      |0.024     |3815     |154259     |0.024731134      |-3.05%            |
|Cash_Monthly|2019;09|Aberdeenshire      |0.017     |2715     |164167     |0.016538037      |2.72%             |
|Cash_Monthly|2019;09|Dumfries & Galloway|0.031     |2670     |88182      |0.030278288      |2.33%             |
|Cash_Monthly|2019;09|East Dunbartonshire|0.018     |1200     |65000      |0.018461538      |-2.56%            |
|Cash_Monthly|2019;09|East Lothian       |0.026     |1685     |66154      |0.025470871      |2.04%             |
|Cash_Monthly|2019;09|Edinburgh City     |0.017     |6380     |364250     |0.017515443      |-3.03%            |
|Cash_Monthly|2019;09|Highland           |0.023     |3240     |146400     |0.022131148      |3.78%             |
|Cash_Monthly|2019;09|Midlothian         |0.024     |1350     |57500      |0.023478261      |2.17%             |
|Cash_Monthly|2019;09|Stirling           |0.024     |1430     |61200      |0.023366013      |2.64%             |
|Cash_Monthly|2019;09|West Lothian       |0.028     |3225     |118966     |0.027108586      |3.18%             |
|Cash_Monthly|2019;10|Aberdeen City      |0.024     |3820     |154259     |0.024763547      |-3.18%            |
|Cash_Monthly|2019;10|East Lothian       |0.026     |1675     |66154      |0.025319709      |2.62%             |
|Cash_Monthly|2019;10|East Renfrewshire  |0.017     |945      |57353      |0.016476906      |3.08%             |
|Cash_Monthly|2019;10|Orkney Islands     |0.014     |180      |13333      |0.013500338      |3.57%             |
|Cash_Monthly|2019;10|Shetland Islands   |0.017     |230      |13947      |0.016491002      |2.99%             |
|Cash_Monthly|2019;11|Aberdeen City      |0.025     |3965     |154259     |0.025703525      |-2.81%            |
|Cash_Monthly|2019;11|Aberdeenshire      |0.018     |2825     |164167     |0.017208087      |4.40%             |
|Cash_Monthly|2019;11|Argyll & Bute      |0.026     |1340     |50333      |0.026622693      |-2.39%            |
|Cash_Monthly|2019;11|East Lothian       |0.027     |1740     |66154      |0.026302264      |2.58%             |
|Cash_Monthly|2019;11|Midlothian         |0.025     |1400     |57500      |0.024347826      |2.61%             |
|Cash_Monthly|2019;11|Moray              |0.024     |1435     |58333      |0.024600141      |-2.50%            |
|Cash_Monthly|2019;11|Orkney Islands     |0.013     |180      |13333      |0.013500338      |-3.85%            |
|Cash_Monthly|2019;11|Perth & Kinross    |0.02      |1820     |93000      |0.019569892      |2.15%             |
|Cash_Monthly|2019;12|East Lothian       |0.027     |1750     |66154      |0.026453427      |2.02%             |
|Cash_Monthly|2019;12|Falkirk            |0.032     |3300     |100758     |0.032751742      |-2.35%            |
|Cash_Monthly|2019;12|Highland           |0.025     |3540     |146400     |0.024180328      |3.28%             |
|Cash_Monthly|2019;12|Perth & Kinross    |0.02      |1810     |93000      |0.019462366      |2.69%             |
|Cash_Monthly|2019;12|Shetland Islands   |0.017     |245      |13947      |0.017566502      |-3.33%            |
|Cash_Monthly|2020;01|Angus              |0.03      |2045     |70000      |0.029214286      |2.62%             |
|Cash_Monthly|2020;01|Dumfries & Galloway|0.033     |2830     |88182      |0.032092717      |2.75%             |
|Cash_Monthly|2020;01|East Lothian       |0.027     |1750     |66154      |0.026453427      |2.02%             |
|Cash_Monthly|2020;01|Highland           |0.026     |3705     |146400     |0.025307377      |2.66%             |
|Cash_Monthly|2020;01|Inverclyde         |0.046     |2200     |49222      |0.044695461      |2.84%             |
|Cash_Monthly|2020;01|North Lanarkshire  |0.037     |8030     |222297     |0.036122845      |2.37%             |
|Cash_Monthly|2020;01|Perth & Kinross    |0.02      |1815     |93000      |0.019516129      |2.42%             |
|Cash_Monthly|2020;01|Shetland Islands   |0.017     |230      |13947      |0.016491002      |2.99%             |
|Cash_Monthly|2020;01|Stirling           |0.025     |1495     |61200      |0.024428105      |2.29%             |
|Cash_Monthly|2020;01|West Lothian       |0.028     |3260     |118966     |0.027402787      |2.13%             |
|Cash_Monthly|2020;02|Aberdeen City      |0.026     |4150     |154259     |0.026902806      |-3.47%            |
|Cash_Monthly|2020;02|Aberdeenshire      |0.019     |2975     |164167     |0.018121791      |4.62%             |
|Cash_Monthly|2020;02|Angus              |0.03      |2040     |70000      |0.029142857      |2.86%             |
|Cash_Monthly|2020;02|East Renfrewshire  |0.017     |950      |57353      |0.016564086      |2.56%             |
|Cash_Monthly|2020;02|Edinburgh City     |0.019     |7105     |364250     |0.019505834      |-2.66%            |
|Cash_Monthly|2020;02|Falkirk            |0.032     |3300     |100758     |0.032751742      |-2.35%            |
|Cash_Monthly|2020;02|Highland           |0.026     |3715     |146400     |0.025375683      |2.40%             |
|Cash_Monthly|2020;02|Inverclyde         |0.047     |2255     |49222      |0.045812848      |2.53%             |
|Cash_Monthly|2020;02|Moray              |0.026     |1550     |58333      |0.02657158       |-2.20%            |
|Cash_Monthly|2020;02|North Lanarkshire  |0.038     |8230     |222297     |0.037022542      |2.57%             |
|Cash_Monthly|2020;02|Orkney Islands     |0.014     |195      |13333      |0.014625366      |-4.47%            |
|Cash_Monthly|2020;02|Scottish Borders   |0.028     |1860     |67857      |0.027410584      |2.11%             |
|Cash_Monthly|2020;02|Stirling           |0.026     |1540     |61200      |0.025163399      |3.22%             |
|Cash_Monthly|2020;03|Dumfries & Galloway|0.034     |2910     |88182      |0.032999932      |2.94%             |
|Cash_Monthly|2020;03|Highland           |0.026     |3660     |146400     |0.025            |3.85%             |
|Cash_Monthly|2020;03|Inverclyde         |0.046     |2215     |49222      |0.045000203      |2.17%             |
|Cash_Monthly|2020;03|North Lanarkshire  |0.038     |8225     |222297     |0.037000049      |2.63%             |
|Cash_Monthly|2020;04|East Dunbartonshire|0.037     |2360     |65513      |0.036023385      |2.64%             |
|Cash_Monthly|2020;04|East Renfrewshire  |0.033     |1855     |57432      |0.032299067      |2.12%             |
|Cash_Monthly|2020;04|Orkney Islands     |0.028     |380      |13276      |0.028623079      |-2.23%            |
|Cash_Monthly|2020;06|East Dunbartonshire|0.042     |2690     |65513      |0.041060553      |2.24%             |
|Cash_Monthly|2020;06|Orkney Islands     |0.028     |380      |13276      |0.028623079      |-2.23%            |
|Cash_Monthly|2020;07|East Dunbartonshire|0.045     |2885     |65513      |0.044037061      |2.14%             |
|Cash_Monthly|2020;08|Orkney Islands     |0.031     |420      |13276      |0.031636035      |-2.05%            |
|Cash_Monthly|2020;09|Perth & Kinross    |0.049     |4435     |92667      |0.04785954       |2.33%             |
|Cash_Monthly|2020;10|Orkney Islands     |0.027     |370      |13276      |0.02786984       |-3.22%            |
|Cash_Monthly|2020;10|Perth & Kinross    |0.046     |4160     |92667      |0.044891925      |2.41%             |
|Cash_Monthly|2021;01|Midlothian         |0.05      |2920     |57222      |0.051029324      |-2.06%            |
|Cash_Monthly|2021;01|Stirling           |0.045     |2660     |60667      |0.043845913      |2.56%             |
|Cash_Monthly|2021;01|West Dunbartonshire|0.082     |4525     |56438      |0.080176477      |2.22%             |
|Cash_Monthly|2021;02|Dundee City        |0.072     |7015     |99710      |0.070354027      |2.29%             |
|Cash_Monthly|2021;02|East Dunbartonshire|0.04      |2560     |65513      |0.039076214      |2.31%             |
|Cash_Monthly|2021;02|Inverclyde         |0.063     |2995     |48871      |0.061283788      |2.72%             |
|Cash_Monthly|2021;02|Midlothian         |0.052     |3070     |57222      |0.053650694      |-3.17%            |
|Cash_Monthly|2021;03|East Dunbartonshire|0.04      |2555     |65513      |0.038999893      |2.50%             |
|Cash_Monthly|2021;03|Stirling           |0.046     |2730     |60667      |0.044999753      |2.17%             |
|Cash_Monthly|2021;06|Orkney Islands     |0.021     |290      |13447      |0.021566149      |-2.70%            |
|Cash_Monthly|2021;08|Shetland Islands   |0.025     |340      |13912      |0.024439333      |2.24%             |
|Cash_Monthly|2021;10|East Renfrewshire  |0.023     |1340     |57033      |0.023495169      |-2.15%            |
|Cash_Monthly|2021;11|Shetland Islands   |0.022     |315      |13912      |0.022642323      |-2.92%            |
|Cash_Monthly|2021;12|Orkney Islands     |0.019     |250      |13447      |0.018591507      |2.15%             |
|Cash_Monthly|2021;12|Shetland Islands   |0.022     |315      |13912      |0.022642323      |-2.92%            |
|Cash_Monthly|2022;01|East Dunbartonshire|0.024     |1575     |64307      |0.02449189       |-2.05%            |
|Cash_Monthly|2022;01|Orkney Islands     |0.019     |250      |13447      |0.018591507      |2.15%             |
|Cash_Monthly|2022;03|East Renfrewshire  |0.019     |1110     |57033      |0.019462416      |-2.43%            |
|Cash_Monthly|2022;04|East Renfrewshire  |0.018     |1050     |57033      |0.018410394      |-2.28%            |
|Cash_Monthly|2022;05|East Renfrewshire  |0.017     |995      |57033      |0.01744604       |-2.62%            |
|Cash_Monthly|2022;05|Shetland Islands   |0.021     |285      |13912      |0.020485911      |2.45%             |
|Cash_Monthly|2022;06|East Renfrewshire  |0.017     |995      |57033      |0.01744604       |-2.62%            |
|Cash_Monthly|2022;07|East Renfrewshire  |0.017     |990      |57033      |0.017358371      |-2.11%            |
|Cash_Monthly|2022;07|Highland           |0.022     |3255     |144706     |0.022493884      |-2.24%            |
|Cash_Monthly|2022;09|East Dunbartonshire|0.02      |1255     |64307      |0.01951576       |2.42%             |
|Cash_Monthly|2022;09|Shetland Islands   |0.017     |230      |13912      |0.01653249       |2.75%             |
|Cash_Monthly|2022;10|East Lothian       |0.022     |1440     |66893      |0.021526916      |2.15%             |
|Cash_Monthly|2022;10|Midlothian         |0.022     |1260     |58532      |0.021526686      |2.15%             |
|Cash_Monthly|2022;10|Perth & Kinross    |0.022     |1995     |92594      |0.021545673      |2.07%             |
|Cash_Monthly|2022;10|Shetland Islands   |0.018     |245      |13912      |0.017610696      |2.16%             |
|Cash_Monthly|2022;11|Aberdeenshire      |0.018     |2970     |160495     |0.018505249      |-2.81%            |
|Cash_Monthly|2022;11|East Renfrewshire  |0.017     |950      |57033      |0.016657023      |2.02%             |
|Cash_Monthly|2022;11|Orkney Islands     |0.015     |210      |13447      |0.015616866      |-4.11%            |
|Cash_Monthly|2022;11|Perth & Kinross    |0.021     |1985     |92594      |0.021437674      |-2.08%            |
|Cash_Monthly|2022;12|Aberdeenshire      |0.019     |2985     |160495     |0.01859871       |2.11%             |
|Cash_Monthly|2022;12|East Dunbartonshire|0.019     |1250     |64307      |0.019438008      |-2.31%            |
|Cash_Monthly|2023;01|East Dunbartonshire|0.018     |1190     |64130      |0.018556058      |-3.09%            |
|Cash_Monthly|2023;01|East Renfrewshire  |0.017     |970      |55500      |0.017477477      |-2.81%            |
|Cash_Monthly|2023;01|Edinburgh City     |0.024     |8645     |371852     |0.023248497      |3.13%             |
|Cash_Monthly|2023;01|Midlothian         |0.023     |1330     |56667      |0.02347045       |-2.05%            |
|Cash_Monthly|2023;01|Moray              |0.024     |1430     |58000      |0.024655172      |-2.73%            |
|Cash_Monthly|2023;01|Perth & Kinross    |0.023     |2160     |91481      |0.02361146       |-2.66%            |
|Cash_Monthly|2023;01|Shetland Islands   |0.017     |240      |13636      |0.017600469      |-3.53%            |
|Cash_Monthly|2023;01|Stirling           |0.025     |1475     |60400      |0.02442053       |2.32%             |
|Cash_Monthly|2023;02|Aberdeenshire      |0.02      |3145     |160495     |0.019595626      |2.02%             |
|Cash_Monthly|2023;02|East Renfrewshire  |0.017     |995      |57033      |0.01744604       |-2.62%            |
|Cash_Monthly|2023;02|Moray              |0.023     |1385     |58935      |0.023500467      |-2.18%            |
|Cash_Monthly|2023;03|Angus              |0.031     |2070     |69017      |0.029992611      |3.25%             |
|Cash_Monthly|2023;03|Clackmannanshire   |0.039     |1220     |31945      |0.03819064       |2.08%             |
|Cash_Monthly|2023;03|Dumfries & Galloway|0.029     |2585     |86346      |0.029937693      |-3.23%            |
|Cash_Monthly|2023;03|East Dunbartonshire|0.019     |1275     |64307      |0.019826768      |-4.35%            |
|Cash_Monthly|2023;03|East Lothian       |0.024     |1570     |66893      |0.023470318      |2.21%             |
|Cash_Monthly|2023;03|Eilean Siar        |0.021     |315      |15508      |0.020312097      |3.28%             |
|Cash_Monthly|2023;03|Glasgow City       |0.05      |21910    |448645     |0.048835939      |2.33%             |
|Cash_Monthly|2023;03|Midlothian         |0.023     |1375     |58532      |0.023491423      |-2.14%            |
|Cash_Monthly|2023;03|South Ayrshire     |0.037     |2490     |65844      |0.037816658      |-2.21%            |
|Cash_Monthly|2023;03|Stirling           |0.024     |1490     |59731      |0.024945171      |-3.94%            |
|Cash_Monthly|2023;05|East Dunbartonshire|0.019     |1255     |64307      |0.01951576       |-2.71%            |
|Cash_Monthly|2023;05|Eilean Siar        |0.018     |285      |15508      |0.018377612      |-2.10%            |
|Cash_Monthly|2023;05|Highland           |0.023     |3400     |144706     |0.023495916      |-2.16%            |
|Cash_Monthly|2023;05|Orkney Islands     |0.016     |220      |13447      |0.016360527      |-2.25%            |
|Cash_Monthly|2023;06|Edinburgh City     |0.023     |8605     |366367     |0.023487377      |-2.12%            |
|Cash_Monthly|2023;06|Moray              |0.022     |1325     |58935      |0.022482396      |-2.19%            |
|Cash_Monthly|2023;06|Orkney Islands     |0.016     |220      |13447      |0.016360527      |-2.25%            |
|Cash_Monthly|2023;07|Clackmannanshire   |0.024     |8725     |31945      |0.273125685      |-1038.02%         |
|Cash_Monthly|2023;07|Dumfries & Galloway|0.037     |1195     |86346      |0.013839668      |62.60%            |
|Cash_Monthly|2023;07|Dundee City        |0.029     |2540     |97773      |0.025978542      |10.42%            |
|Cash_Monthly|2023;07|East Ayrshire      |0.045     |4435     |75654      |0.058622148      |-30.27%           |
|Cash_Monthly|2023;07|East Dunbartonshire|0.042     |3175     |64307      |0.049372541      |-17.55%           |
|Cash_Monthly|2023;07|East Lothian       |0.02      |1275     |66893      |0.01906029       |4.70%             |
|Cash_Monthly|2023;07|East Renfrewshire  |0.023     |1555     |57033      |0.027264917      |-18.54%           |
|Cash_Monthly|2023;07|Edinburgh City     |0.018     |1015     |366367     |0.002770446      |84.61%            |
|Cash_Monthly|2023;07|Eilean Siar        |0.03      |3010     |15508      |0.194093371      |-546.98%          |
|Cash_Monthly|2023;07|Falkirk            |0.035     |8060     |102021     |0.079003342      |-125.72%          |
|Cash_Monthly|2023;07|Fife               |0.048     |21630    |231635     |0.093379671      |-94.54%           |
|Cash_Monthly|2023;07|Glasgow City       |0.022     |3220     |448645     |0.007177167      |67.38%            |
|Cash_Monthly|2023;07|Highland           |0.04      |1890     |144706     |0.013060965      |67.35%            |
|Cash_Monthly|2023;07|Inverclyde         |0.024     |1405     |47782      |0.029404378      |-22.52%           |
|Cash_Monthly|2023;07|Moray              |0.019     |290      |58935      |0.004920675      |74.10%            |
|Cash_Monthly|2023;07|Orkney Islands     |0.015     |195      |13447      |0.014501376      |3.32%             |
|Cash_Monthly|2023;07|Shetland Islands   |0.016     |230      |13912      |0.01653249       |-3.33%            |
|Cash_Monthly|2023;08|Clackmannanshire   |0.023     |8535     |31945      |0.267177962      |-1061.64%         |
|Cash_Monthly|2023;08|Dumfries & Galloway|0.037     |1175     |86346      |0.013608042      |63.22%            |
|Cash_Monthly|2023;08|Dundee City        |0.028     |2455     |97773      |0.025109181      |10.32%            |
|Cash_Monthly|2023;08|East Ayrshire      |0.044     |4275     |75654      |0.056507257      |-28.43%           |
|Cash_Monthly|2023;08|East Dunbartonshire|0.04      |3060     |64307      |0.047584244      |-18.96%           |
|Cash_Monthly|2023;08|East Lothian       |0.02      |1275     |66893      |0.01906029       |4.70%             |
|Cash_Monthly|2023;08|East Renfrewshire  |0.023     |1530     |57033      |0.026826574      |-16.64%           |
|Cash_Monthly|2023;08|Edinburgh City     |0.018     |1025     |366367     |0.002797741      |84.46%            |
|Cash_Monthly|2023;08|Eilean Siar        |0.029     |3010     |15508      |0.194093371      |-569.29%          |
|Cash_Monthly|2023;08|Falkirk            |0.034     |7820     |102021     |0.076650886      |-125.44%          |
|Cash_Monthly|2023;08|Fife               |0.047     |21200    |231635     |0.091523302      |-94.73%           |
|Cash_Monthly|2023;08|Glasgow City       |0.022     |3140     |448645     |0.006998852      |68.19%            |
|Cash_Monthly|2023;08|Highland           |0.038     |1840     |144706     |0.012715437      |66.54%            |
|Cash_Monthly|2023;08|Inverclyde         |0.023     |1345     |47782      |0.028148675      |-22.39%           |
|Cash_Monthly|2023;08|Moray              |0.018     |280      |58935      |0.004750997      |73.61%            |
|Cash_Monthly|2023;08|Orkney Islands     |0.016     |210      |13447      |0.015616866      |2.39%             |
|Cash_Monthly|2023;09|East Renfrewshire  |0.018     |1005     |57033      |0.017621377      |2.10%             |
|Cash_Monthly|2023;09|Highland           |0.02      |2960     |144706     |0.020455268      |-2.28%            |
|Cash_Monthly|2023;09|Moray              |0.021     |1210     |58935      |0.020531094      |2.23%             |
|Cash_Monthly|2023;10|Aberdeenshire      |0.017     |2785     |160495     |0.017352566      |-2.07%            |
|Cash_Monthly|2023;10|East Renfrewshire  |0.018     |1000     |57033      |0.017533709      |2.59%             |
|Cash_Monthly|2023;10|Highland           |0.021     |2975     |144706     |0.020558926      |2.10%             |
|Cash_Monthly|2023;10|Orkney Islands     |0.015     |195      |13447      |0.014501376      |3.32%             |
|Cash_Monthly|2023;11|Aberdeenshire      |0.018     |2820     |160495     |0.017570641      |2.39%             |
|Cash_Monthly|2023;11|East Renfrewshire  |0.018     |1000     |57033      |0.017533709      |2.59%             |
|Cash_Monthly|2023;12|East Lothian       |0.023     |1570     |66893      |0.023470318      |-2.04%            |
|Cash_Monthly|2023;12|East Renfrewshire  |0.018     |1000     |57033      |0.017533709      |2.59%             |
|Cash_Monthly|2023;12|Eilean Siar        |0.018     |285      |15508      |0.018377612      |-2.10%            |
|Cash_Monthly|2023;12|Orkney Islands     |0.015     |210      |13447      |0.015616866      |-4.11%            |
|Cash_Monthly|2023;12|Perth & Kinross    |0.021     |1990     |92594      |0.021491673      |-2.34%            |
|Real_Monthly|2010;04|Angus              |0.03      |2135     |73125      |0.029196581      |2.68%             |
|Real_Monthly|2010;04|East Lothian       |0.032     |2005     |64063      |0.031297317      |2.20%             |
|Real_Monthly|2010;04|Scottish Borders   |0.029     |2065     |69688      |0.029632074      |-2.18%            |
|Real_Monthly|2010;05|Aberdeen City      |0.022     |3350     |157391     |0.021284572      |3.25%             |
|Real_Monthly|2010;05|Aberdeenshire      |0.014     |2220     |162188     |0.013687819      |2.23%             |
|Real_Monthly|2010;05|Angus              |0.029     |2065     |73125      |0.028239316      |2.62%             |
|Real_Monthly|2010;05|East Lothian       |0.03      |1880     |64063      |0.029346112      |2.18%             |
|Real_Monthly|2010;05|Orkney Islands     |0.011     |155      |13529      |0.01145687       |-4.15%            |
|Real_Monthly|2010;05|Shetland Islands   |0.015     |225      |15313      |0.014693398      |2.04%             |
|Real_Monthly|2010;06|Aberdeen City      |0.021     |3235     |157391     |0.020553907      |2.12%             |
|Real_Monthly|2010;06|Aberdeenshire      |0.013     |2055     |162188     |0.012670481      |2.53%             |
|Real_Monthly|2010;06|Orkney Islands     |0.011     |145      |13529      |0.010717717      |2.57%             |
|Real_Monthly|2010;06|Shetland Islands   |0.014     |205      |15313      |0.013387318      |4.38%             |
|Real_Monthly|2010;07|East Lothian       |0.03      |1875     |64063      |0.029268064      |2.44%             |
|Real_Monthly|2010;07|Orkney Islands     |0.014     |185      |13529      |0.013674329      |2.33%             |
|Real_Monthly|2010;07|Perth & Kinross    |0.022     |1975     |92308      |0.021395762      |2.75%             |
|Real_Monthly|2010;07|Shetland Islands   |0.014     |205      |15313      |0.013387318      |4.38%             |
|Real_Monthly|2010;08|Aberdeen City      |0.022     |3350     |157391     |0.021284572      |3.25%             |
|Real_Monthly|2010;08|Angus              |0.032     |2280     |73125      |0.031179487      |2.56%             |
|Real_Monthly|2010;08|East Lothian       |0.03      |1875     |64063      |0.029268064      |2.44%             |
|Real_Monthly|2010;08|Highland           |0.025     |3615     |147581     |0.024495023      |2.02%             |
|Real_Monthly|2010;08|Shetland Islands   |0.014     |210      |15313      |0.013713838      |2.04%             |
|Real_Monthly|2010;09|Aberdeen City      |0.021     |3215     |157391     |0.020426835      |2.73%             |
|Real_Monthly|2010;09|Aberdeenshire      |0.013     |2065     |162188     |0.012732138      |2.06%             |
|Real_Monthly|2010;09|Dumfries & Galloway|0.031     |2845     |93971      |0.030275298      |2.34%             |
|Real_Monthly|2010;09|Dundee City        |0.05      |4825     |98661      |0.048904836      |2.19%             |
|Real_Monthly|2010;09|South Lanarkshire  |0.042     |8510     |207444     |0.041023119      |2.33%             |
|Real_Monthly|2010;10|Aberdeenshire      |0.012     |2035     |162188     |0.012547167      |-4.56%            |
|Real_Monthly|2010;10|East Lothian       |0.028     |1740     |64063      |0.027160764      |3.00%             |
|Real_Monthly|2010;10|Moray              |0.019     |1150     |59286      |0.019397497      |-2.09%            |
|Real_Monthly|2010;10|Shetland Islands   |0.014     |200      |15313      |0.013060798      |6.71%             |
|Real_Monthly|2010;11|East Lothian       |0.028     |1755     |64063      |0.027394908      |2.16%             |
|Real_Monthly|2010;11|Orkney Islands     |0.014     |195      |13529      |0.014413482      |-2.95%            |
|Real_Monthly|2010;11|Shetland Islands   |0.014     |210      |15313      |0.013713838      |2.04%             |
|Real_Monthly|2010;12|Eilean Siar        |0.032     |540      |17258      |0.031289837      |2.22%             |
|Real_Monthly|2010;12|Moray              |0.023     |1405     |59286      |0.023698681      |-3.04%            |
|Real_Monthly|2010;12|Scottish Borders   |0.028     |2005     |69688      |0.028771094      |-2.75%            |
|Real_Monthly|2010;12|South Lanarkshire  |0.044     |8940     |207444     |0.043095968      |2.05%             |
|Real_Monthly|2011;01|Eilean Siar        |0.034     |575      |17258      |0.033317882      |2.01%             |
|Real_Monthly|2011;01|Orkney Islands     |0.017     |235      |13529      |0.017370094      |-2.18%            |
|Real_Monthly|2011;01|West Lothian       |0.039     |4570     |114634     |0.039866008      |-2.22%            |
|Real_Monthly|2011;02|Shetland Islands   |0.016     |235      |15313      |0.015346438      |4.08%             |
|Real_Monthly|2011;04|Argyll & Bute      |0.034     |1855     |52179      |0.0355507        |-4.56%            |
|Real_Monthly|2011;04|Dumfries & Galloway|0.034     |3185     |91154      |0.034940869      |-2.77%            |
|Real_Monthly|2011;04|East Renfrewshire  |0.025     |1420     |55577      |0.025550138      |-2.20%            |
|Real_Monthly|2011;04|Orkney Islands     |0.014     |185      |13611      |0.013591948      |2.91%             |
|Real_Monthly|2011;04|Scottish Borders   |0.03      |2125     |68971      |0.030810051      |-2.70%            |
|Real_Monthly|2011;04|Shetland Islands   |0.014     |215      |14375      |0.014956522      |-6.83%            |
|Real_Monthly|2011;05|Aberdeen City      |0.022     |3550     |158043     |0.022462241      |-2.10%            |
|Real_Monthly|2011;05|Aberdeenshire      |0.014     |2390     |163667     |0.014602822      |-4.31%            |
|Real_Monthly|2011;05|Argyll & Bute      |0.032     |1750     |52179      |0.033538397      |-4.81%            |
|Real_Monthly|2011;05|East Renfrewshire  |0.024     |1375     |55577      |0.02474045       |-3.09%            |
|Real_Monthly|2011;05|Eilean Siar        |0.029     |495      |16618      |0.029786978      |-2.71%            |
|Real_Monthly|2011;05|Perth & Kinross    |0.024     |2210     |90185      |0.024505184      |-2.10%            |
|Real_Monthly|2011;05|Shetland Islands   |0.014     |215      |14375      |0.014956522      |-6.83%            |
|Real_Monthly|2011;06|Argyll & Bute      |0.032     |1780     |52179      |0.034113341      |-6.60%            |
|Real_Monthly|2011;06|Dumfries & Galloway|0.033     |3105     |91154      |0.034063234      |-3.22%            |
|Real_Monthly|2011;06|East Lothian       |0.03      |1930     |62714      |0.030774628      |-2.58%            |
|Real_Monthly|2011;06|East Renfrewshire  |0.025     |1425     |55577      |0.025640103      |-2.56%            |
|Real_Monthly|2011;06|Eilean Siar        |0.027     |460      |16618      |0.027680828      |-2.52%            |
|Real_Monthly|2011;06|Moray              |0.024     |1445     |58214      |0.024822208      |-3.43%            |
|Real_Monthly|2011;06|Orkney Islands     |0.014     |185      |13611      |0.013591948      |2.91%             |
|Real_Monthly|2011;06|Scottish Borders   |0.028     |1975     |68971      |0.028635223      |-2.27%            |
|Real_Monthly|2011;07|Argyll & Bute      |0.033     |1840     |52179      |0.035263229      |-6.86%            |
|Real_Monthly|2011;07|Eilean Siar        |0.028     |475      |16618      |0.028583464      |-2.08%            |
|Real_Monthly|2011;07|Orkney Islands     |0.014     |195      |13611      |0.014326648      |-2.33%            |
|Real_Monthly|2011;07|Scottish Borders   |0.03      |2150     |68971      |0.031172522      |-3.91%            |
|Real_Monthly|2011;07|Shetland Islands   |0.012     |180      |14375      |0.012521739      |-4.35%            |
|Real_Monthly|2011;08|Aberdeenshire      |0.015     |2515     |163667     |0.015366567      |-2.44%            |
|Real_Monthly|2011;08|Argyll & Bute      |0.034     |1890     |52179      |0.036221468      |-6.53%            |
|Real_Monthly|2011;08|Dumfries & Galloway|0.035     |3265     |91154      |0.035818505      |-2.34%            |
|Real_Monthly|2011;08|East Dunbartonshire|0.03      |1955     |66607      |0.029351269      |2.16%             |
|Real_Monthly|2011;08|East Renfrewshire  |0.026     |1480     |55577      |0.026629721      |-2.42%            |
|Real_Monthly|2011;08|Edinburgh City     |0.033     |11240    |333750     |0.033677903      |-2.05%            |
|Real_Monthly|2011;08|Eilean Siar        |0.028     |480      |16618      |0.028884342      |-3.16%            |
|Real_Monthly|2011;08|Moray              |0.025     |1495     |58214      |0.025681108      |-2.72%            |
|Real_Monthly|2011;08|Perth & Kinross    |0.025     |2315     |90185      |0.025669457      |-2.68%            |
|Real_Monthly|2011;08|Scottish Borders   |0.031     |2205     |68971      |0.031969958      |-3.13%            |
|Real_Monthly|2011;09|Angus              |0.03      |2210     |71875      |0.030747826      |-2.49%            |
|Real_Monthly|2011;09|Argyll & Bute      |0.033     |1810     |52179      |0.034688285      |-5.12%            |
|Real_Monthly|2011;09|East Dunbartonshire|0.028     |1820     |66607      |0.027324455      |2.41%             |
|Real_Monthly|2011;09|East Renfrewshire  |0.025     |1420     |55577      |0.025550138      |-2.20%            |
|Real_Monthly|2011;09|Edinburgh City     |0.032     |10930    |333750     |0.032749064      |-2.34%            |
|Real_Monthly|2011;09|Eilean Siar        |0.028     |475      |16618      |0.028583464      |-2.08%            |
|Real_Monthly|2011;09|Moray              |0.022     |1320     |58214      |0.022674958      |-3.07%            |
|Real_Monthly|2011;09|North Ayrshire     |0.061     |5375     |86343      |0.062251717      |-2.05%            |
|Real_Monthly|2011;09|Scottish Borders   |0.029     |2050     |68971      |0.029722637      |-2.49%            |
|Real_Monthly|2011;09|Shetland Islands   |0.011     |170      |14375      |0.011826087      |-7.51%            |
|Real_Monthly|2011;10|Argyll & Bute      |0.033     |1840     |52179      |0.035263229      |-6.86%            |
|Real_Monthly|2011;10|Eilean Siar        |0.028     |480      |16618      |0.028884342      |-3.16%            |
|Real_Monthly|2011;10|Moray              |0.021     |1270     |58214      |0.021816058      |-3.89%            |
|Real_Monthly|2011;10|Perth & Kinross    |0.022     |2060     |90185      |0.022841936      |-3.83%            |
|Real_Monthly|2011;10|Scottish Borders   |0.028     |1980     |68971      |0.028707718      |-2.53%            |
|Real_Monthly|2011;10|Shetland Islands   |0.012     |180      |14375      |0.012521739      |-4.35%            |
|Real_Monthly|2011;11|Argyll & Bute      |0.035     |1910     |52179      |0.036604764      |-4.59%            |
|Real_Monthly|2011;11|Eilean Siar        |0.03      |520      |16618      |0.031291371      |-4.30%            |
|Real_Monthly|2011;11|Orkney Islands     |0.018     |250      |13611      |0.018367497      |-2.04%            |
|Real_Monthly|2011;11|Perth & Kinross    |0.023     |2135     |90185      |0.02367356       |-2.93%            |
|Real_Monthly|2011;12|Aberdeen City      |0.021     |3395     |158043     |0.021481496      |-2.29%            |
|Real_Monthly|2011;12|Aberdeenshire      |0.013     |2225     |163667     |0.013594677      |-4.57%            |
|Real_Monthly|2011;12|Argyll & Bute      |0.036     |1995     |52179      |0.038233772      |-6.20%            |
|Real_Monthly|2011;12|East Lothian       |0.032     |2055     |62714      |0.032767803      |-2.40%            |
|Real_Monthly|2011;12|Eilean Siar        |0.031     |530      |16618      |0.031893128      |-2.88%            |
|Real_Monthly|2011;12|Perth & Kinross    |0.024     |2225     |90185      |0.024671509      |-2.80%            |
|Real_Monthly|2011;12|Shetland Islands   |0.012     |185      |14375      |0.012869565      |-7.25%            |
|Real_Monthly|2012;01|Aberdeenshire      |0.014     |2360     |163667     |0.014419523      |-3.00%            |
|Real_Monthly|2012;01|East Renfrewshire  |0.025     |1425     |55577      |0.025640103      |-2.56%            |
|Real_Monthly|2012;01|Edinburgh City     |0.034     |11650    |333750     |0.034906367      |-2.67%            |
|Real_Monthly|2012;01|Orkney Islands     |0.02      |265      |13611      |0.019469547      |2.65%             |
|Real_Monthly|2012;02|Orkney Islands     |0.019     |250      |13611      |0.018367497      |3.33%             |
|Real_Monthly|2012;02|Shetland Islands   |0.014     |210      |14375      |0.014608696      |-4.35%            |
|Real_Monthly|2012;04|Aberdeen City      |0.022     |3510     |162895     |0.021547623      |2.06%             |
|Real_Monthly|2012;04|Eilean Siar        |0.032     |545      |16667      |0.032699346      |-2.19%            |
|Real_Monthly|2012;04|Moray              |0.025     |1435     |59167      |0.024253384      |2.99%             |
|Real_Monthly|2012;04|Orkney Islands     |0.015     |205      |13214      |0.015513849      |-3.43%            |
|Real_Monthly|2012;04|Scottish Borders   |0.031     |2195     |69219      |0.031710946      |-2.29%            |
|Real_Monthly|2012;04|Shetland Islands   |0.015     |225      |14375      |0.015652174      |-4.35%            |
|Real_Monthly|2012;05|Aberdeenshire      |0.013     |2220     |166250     |0.013353383      |-2.72%            |
|Real_Monthly|2012;05|Scottish Borders   |0.029     |2055     |69219      |0.02968838       |-2.37%            |
|Real_Monthly|2012;05|Shetland Islands   |0.015     |225      |14375      |0.015652174      |-4.35%            |
|Real_Monthly|2012;06|Aberdeen City      |0.021     |3340     |162895     |0.020504006      |2.36%             |
|Real_Monthly|2012;06|East Lothian       |0.031     |1935     |64242      |0.030120482      |2.84%             |
|Real_Monthly|2012;06|Eilean Siar        |0.032     |545      |16667      |0.032699346      |-2.19%            |
|Real_Monthly|2012;06|Orkney Islands     |0.015     |205      |13214      |0.015513849      |-3.43%            |
|Real_Monthly|2012;07|Aberdeenshire      |0.013     |2225     |166250     |0.013383459      |-2.95%            |
|Real_Monthly|2012;07|West Lothian       |0.038     |4445     |114535     |0.038809098      |-2.13%            |
|Real_Monthly|2012;08|Stirling           |0.033     |1970     |58281      |0.033801754      |-2.43%            |
|Real_Monthly|2012;09|Aberdeenshire      |0.012     |1925     |166250     |0.011578947      |3.51%             |
|Real_Monthly|2012;09|East Dunbartonshire|0.025     |1680     |65800      |0.025531915      |-2.13%            |
|Real_Monthly|2012;09|Orkney Islands     |0.012     |155      |13214      |0.011729983      |2.25%             |
|Real_Monthly|2012;09|Scottish Borders   |0.028     |1980     |69219      |0.028604863      |-2.16%            |
|Real_Monthly|2012;10|Aberdeen City      |0.02      |3180     |162895     |0.019521778      |2.39%             |
|Real_Monthly|2012;10|Eilean Siar        |0.027     |460      |16667      |0.027599448      |-2.22%            |
|Real_Monthly|2012;10|Shetland Islands   |0.013     |195      |14375      |0.013565217      |-4.35%            |
|Real_Monthly|2012;10|Stirling           |0.031     |1845     |58281      |0.031656972      |-2.12%            |
|Real_Monthly|2012;10|West Lothian       |0.034     |3980     |114535     |0.034749203      |-2.20%            |
|Real_Monthly|2012;11|East Dunbartonshire|0.024     |1615     |65800      |0.024544073      |-2.27%            |
|Real_Monthly|2012;11|Eilean Siar        |0.026     |445      |16667      |0.026699466      |-2.69%            |
|Real_Monthly|2012;12|Aberdeen City      |0.019     |2990     |162895     |0.018355382      |3.39%             |
|Real_Monthly|2012;12|Aberdeenshire      |0.011     |1875     |166250     |0.011278195      |-2.53%            |
|Real_Monthly|2012;12|Eilean Siar        |0.027     |460      |16667      |0.027599448      |-2.22%            |
|Real_Monthly|2012;12|Moray              |0.022     |1275     |59167      |0.021549174      |2.05%             |
|Real_Monthly|2012;12|Scottish Borders   |0.028     |1985     |69219      |0.028677097      |-2.42%            |
|Real_Monthly|2013;01|Shetland Islands   |0.014     |215      |14375      |0.014956522      |-6.83%            |
|Real_Monthly|2013;02|Aberdeen City      |0.02      |3135     |162895     |0.019245526      |3.77%             |
|Real_Monthly|2013;02|Aberdeenshire      |0.013     |2070     |166250     |0.012451128      |4.22%             |
|Real_Monthly|2013;02|Argyll & Bute      |0.037     |2005     |53056      |0.037790259      |-2.14%            |
|Real_Monthly|2013;02|Orkney Islands     |0.014     |190      |13214      |0.014378689      |-2.70%            |
|Real_Monthly|2013;02|Shetland Islands   |0.014     |210      |14375      |0.014608696      |-4.35%            |
|Real_Monthly|2013;04|Aberdeen City      |0.018     |2945     |156667     |0.018797832      |-4.43%            |
|Real_Monthly|2013;04|Aberdeenshire      |0.012     |1935     |173750     |0.011136691      |7.19%             |
|Real_Monthly|2013;04|Falkirk            |0.043     |4420     |100694     |0.043895366      |-2.08%            |
|Real_Monthly|2013;04|Highland           |0.025     |3705     |142826     |0.025940655      |-3.76%            |
|Real_Monthly|2013;04|Shetland Islands   |0.015     |225      |14500      |0.015517241      |-3.45%            |
|Real_Monthly|2013;05|Aberdeenshire      |0.011     |1850     |173750     |0.010647482      |3.20%             |
|Real_Monthly|2013;05|Fife               |0.045     |10580    |229459     |0.046108455      |-2.46%            |
|Real_Monthly|2013;05|Perth & Kinross    |0.022     |2000     |93947      |0.021288599      |3.23%             |
|Real_Monthly|2013;05|Renfrewshire       |0.047     |5340     |111154     |0.048041456      |-2.22%            |
|Real_Monthly|2013;05|Scottish Borders   |0.029     |2025     |67692      |0.029914909      |-3.15%            |
|Real_Monthly|2013;05|Shetland Islands   |0.013     |195      |14500      |0.013448276      |-3.45%            |
|Real_Monthly|2013;05|Stirling           |0.029     |1700     |60000      |0.028333333      |2.30%             |
|Real_Monthly|2013;06|Aberdeen City      |0.017     |2760     |156667     |0.017616984      |-3.63%            |
|Real_Monthly|2013;06|Aberdeenshire      |0.011     |1790     |173750     |0.010302158      |6.34%             |
|Real_Monthly|2013;06|East Dunbartonshire|0.022     |1475     |65588      |0.02248887       |-2.22%            |
|Real_Monthly|2013;06|Eilean Siar        |0.026     |440      |16333      |0.026939325      |-3.61%            |
|Real_Monthly|2013;06|Moray              |0.021     |1255     |58421      |0.021482001      |-2.30%            |
|Real_Monthly|2013;06|Orkney Islands     |0.01      |140      |13636      |0.01026694       |-2.67%            |
|Real_Monthly|2013;06|Perth & Kinross    |0.022     |1980     |93947      |0.021075713      |4.20%             |
|Real_Monthly|2013;07|Aberdeen City      |0.017     |2755     |156667     |0.017585069      |-3.44%            |
|Real_Monthly|2013;07|Aberdeenshire      |0.011     |1790     |173750     |0.010302158      |6.34%             |
|Real_Monthly|2013;07|Edinburgh City     |0.031     |10430    |346923     |0.030064308      |3.02%             |
|Real_Monthly|2013;07|Fife               |0.046     |10785    |229459     |0.047001861      |-2.18%            |
|Real_Monthly|2013;07|Midlothian         |0.035     |1845     |54000      |0.034166667      |2.38%             |
|Real_Monthly|2013;07|Perth & Kinross    |0.022     |1970     |93947      |0.02096927       |4.69%             |
|Real_Monthly|2013;07|Renfrewshire       |0.046     |5225     |111154     |0.047006855      |-2.19%            |
|Real_Monthly|2013;07|Scottish Borders   |0.028     |1955     |67692      |0.028880813      |-3.15%            |
|Real_Monthly|2013;08|Aberdeen City      |0.017     |2725     |156667     |0.01739358       |-2.32%            |
|Real_Monthly|2013;08|Eilean Siar        |0.027     |450      |16333      |0.027551583      |-2.04%            |
|Real_Monthly|2013;08|Fife               |0.045     |10560    |229459     |0.046021294      |-2.27%            |
|Real_Monthly|2013;08|Moray              |0.019     |1145     |58421      |0.019599117      |-3.15%            |
|Real_Monthly|2013;08|Orkney Islands     |0.01      |140      |13636      |0.01026694       |-2.67%            |
|Real_Monthly|2013;08|Perth & Kinross    |0.021     |1900     |93947      |0.020224169      |3.69%             |
|Real_Monthly|2013;08|Renfrewshire       |0.045     |5125     |111154     |0.046107203      |-2.46%            |
|Real_Monthly|2013;08|Scottish Borders   |0.027     |1890     |67692      |0.027920581      |-3.41%            |
|Real_Monthly|2013;09|Aberdeen City      |0.015     |2460     |156667     |0.015702094      |-4.68%            |
|Real_Monthly|2013;09|Aberdeenshire      |0.009     |1455     |173750     |0.008374101      |6.95%             |
|Real_Monthly|2013;09|Argyll & Bute      |0.026     |1415     |53214      |0.026590747      |-2.27%            |
|Real_Monthly|2013;09|Orkney Islands     |0.011     |145      |13636      |0.010633617      |3.33%             |
|Real_Monthly|2013;09|Perth & Kinross    |0.019     |1710     |93947      |0.018201752      |4.20%             |
|Real_Monthly|2013;09|Renfrewshire       |0.04      |4560     |111154     |0.041024165      |-2.56%            |
|Real_Monthly|2013;09|Scottish Borders   |0.025     |1745     |67692      |0.025778526      |-3.11%            |
|Real_Monthly|2013;09|Shetland Islands   |0.008     |120      |14500      |0.008275862      |-3.45%            |
|Real_Monthly|2013;09|Stirling           |0.027     |1575     |60000      |0.02625          |2.78%             |
|Real_Monthly|2013;10|Aberdeen City      |0.014     |2320     |156667     |0.014808479      |-5.77%            |
|Real_Monthly|2013;10|East Dunbartonshire|0.019     |1220     |65588      |0.018600964      |2.10%             |
|Real_Monthly|2013;10|East Renfrewshire  |0.018     |990      |56875      |0.017406593      |3.30%             |
|Real_Monthly|2013;10|Edinburgh City     |0.027     |9130     |346923     |0.026317079      |2.53%             |
|Real_Monthly|2013;10|Highland           |0.018     |2640     |142826     |0.01848403       |-2.69%            |
|Real_Monthly|2013;10|Moray              |0.015     |915      |58421      |0.015662176      |-4.41%            |
|Real_Monthly|2013;10|Orkney Islands     |0.011     |145      |13636      |0.010633617      |3.33%             |
|Real_Monthly|2013;10|Perth & Kinross    |0.018     |1615     |93947      |0.017190544      |4.50%             |
|Real_Monthly|2013;10|Scottish Borders   |0.024     |1685     |67692      |0.024892159      |-3.72%            |
|Real_Monthly|2013;10|Shetland Islands   |0.007     |110      |14500      |0.007586207      |-8.37%            |
|Real_Monthly|2013;10|Stirling           |0.026     |1525     |60000      |0.025416667      |2.24%             |
|Real_Monthly|2013;11|Aberdeen City      |0.014     |2315     |156667     |0.014776564      |-5.55%            |
|Real_Monthly|2013;11|Aberdeenshire      |0.008     |1320     |173750     |0.007597122      |5.04%             |
|Real_Monthly|2013;11|Angus              |0.022     |1550     |72619      |0.021344276      |2.98%             |
|Real_Monthly|2013;11|East Renfrewshire  |0.017     |940      |56875      |0.016527473      |2.78%             |
|Real_Monthly|2013;11|Moray              |0.015     |915      |58421      |0.015662176      |-4.41%            |
|Real_Monthly|2013;11|Perth & Kinross    |0.018     |1650     |93947      |0.017563094      |2.43%             |
|Real_Monthly|2013;11|Shetland Islands   |0.01      |140      |14500      |0.009655172      |3.45%             |
|Real_Monthly|2013;11|Stirling           |0.026     |1510     |60000      |0.025166667      |3.21%             |
|Real_Monthly|2013;12|Aberdeen City      |0.014     |2270     |156667     |0.014489331      |-3.50%            |
|Real_Monthly|2013;12|Aberdeenshire      |0.008     |1340     |173750     |0.00771223       |3.60%             |
|Real_Monthly|2013;12|Angus              |0.022     |1545     |72619      |0.021275424      |3.29%             |
|Real_Monthly|2013;12|Edinburgh City     |0.026     |8820     |346923     |0.025423509      |2.22%             |
|Real_Monthly|2013;12|Eilean Siar        |0.028     |475      |16333      |0.029082226      |-3.87%            |
|Real_Monthly|2013;12|Moray              |0.016     |975      |58421      |0.016689204      |-4.31%            |
|Real_Monthly|2013;12|Shetland Islands   |0.009     |140      |14500      |0.009655172      |-7.28%            |
|Real_Monthly|2013;12|Stirling           |0.026     |1510     |60000      |0.025166667      |3.21%             |
|Real_Monthly|2014;01|Aberdeenshire      |0.009     |1430     |173750     |0.008230216      |8.55%             |
|Real_Monthly|2014;01|East Dunbartonshire|0.018     |1150     |65588      |0.017533695      |2.59%             |
|Real_Monthly|2014;01|Edinburgh City     |0.027     |9105     |346923     |0.026245017      |2.80%             |
|Real_Monthly|2014;01|Fife               |0.036     |8465     |229459     |0.036891122      |-2.48%            |
|Real_Monthly|2014;01|Highland           |0.022     |3220     |142826     |0.022544915      |-2.48%            |
|Real_Monthly|2014;01|Orkney Islands     |0.011     |145      |13636      |0.010633617      |3.33%             |
|Real_Monthly|2014;01|Perth & Kinross    |0.02      |1800     |93947      |0.019159739      |4.20%             |
|Real_Monthly|2014;01|Shetland Islands   |0.009     |135      |14500      |0.009310345      |-3.45%            |
|Real_Monthly|2014;01|Stirling           |0.027     |1565     |60000      |0.026083333      |3.40%             |
|Real_Monthly|2014;02|Aberdeen City      |0.015     |2430     |156667     |0.015510605      |-3.40%            |
|Real_Monthly|2014;02|Aberdeenshire      |0.009     |1470     |173750     |0.008460432      |6.00%             |
|Real_Monthly|2014;02|Inverclyde         |0.042     |2120     |51625      |0.041065375      |2.23%             |
|Real_Monthly|2014;02|Orkney Islands     |0.012     |155      |13636      |0.01136697       |5.28%             |
|Real_Monthly|2014;02|Perth & Kinross    |0.02      |1815     |93947      |0.019319403      |3.40%             |
|Real_Monthly|2014;02|Scottish Borders   |0.027     |1870     |67692      |0.027625126      |-2.32%            |
|Real_Monthly|2014;02|Shetland Islands   |0.008     |120      |14500      |0.008275862      |-3.45%            |
|Real_Monthly|2014;04|Aberdeen City      |0.014     |2195     |161667     |0.013577292      |3.02%             |
|Real_Monthly|2014;04|Aberdeenshire      |0.008     |1365     |156250     |0.008736         |-9.20%            |
|Real_Monthly|2014;04|East Lothian       |0.024     |1560     |63421      |0.024597531      |-2.49%            |
|Real_Monthly|2014;04|Edinburgh City     |0.026     |8830     |349722     |0.025248626      |2.89%             |
|Real_Monthly|2014;04|Moray              |0.018     |1075     |61333      |0.017527269      |2.63%             |
|Real_Monthly|2014;04|Orkney Islands     |0.009     |125      |14286      |0.008749825      |2.78%             |
|Real_Monthly|2014;04|Shetland Islands   |0.01      |145      |15000      |0.009666667      |3.33%             |
|Real_Monthly|2014;04|South Lanarkshire  |0.034     |6815     |204630     |0.033304012      |2.05%             |
|Real_Monthly|2014;04|Stirling           |0.024     |1405     |61176      |0.022966523      |4.31%             |
|Real_Monthly|2014;04|West Lothian       |0.029     |3320     |118500     |0.028016878      |3.39%             |
|Real_Monthly|2014;05|Aberdeenshire      |0.007     |1245     |156250     |0.007968         |-13.83%           |
|Real_Monthly|2014;05|East Dunbartonshire|0.015     |995      |64286      |0.015477709      |-3.18%            |
|Real_Monthly|2014;05|East Renfrewshire  |0.015     |865      |55714      |0.015525721      |-3.50%            |
|Real_Monthly|2014;05|Edinburgh City     |0.025     |8485     |349722     |0.024262128      |2.95%             |
|Real_Monthly|2014;05|Glasgow City       |0.042     |17475    |424595     |0.041156867      |2.01%             |
|Real_Monthly|2014;05|Moray              |0.017     |1000     |61333      |0.016304436      |4.09%             |
|Real_Monthly|2014;05|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Real_Monthly|2014;05|Scottish Borders   |0.022     |1530     |67500      |0.022666667      |-3.03%            |
|Real_Monthly|2014;05|Shetland Islands   |0.008     |125      |15000      |0.008333333      |-4.17%            |
|Real_Monthly|2014;05|Stirling           |0.023     |1335     |61176      |0.021822283      |5.12%             |
|Real_Monthly|2014;06|Aberdeenshire      |0.007     |1205     |156250     |0.007712         |-10.17%           |
|Real_Monthly|2014;06|Angus              |0.02      |1410     |71944      |0.019598577      |2.01%             |
|Real_Monthly|2014;06|Argyll & Bute      |0.02      |1070     |52000      |0.020576923      |-2.88%            |
|Real_Monthly|2014;06|East Ayrshire      |0.042     |3305     |76579      |0.043158046      |-2.76%            |
|Real_Monthly|2014;06|East Dunbartonshire|0.014     |935      |64286      |0.01454438       |-3.89%            |
|Real_Monthly|2014;06|East Lothian       |0.022     |1430     |63421      |0.022547737      |-2.49%            |
|Real_Monthly|2014;06|East Renfrewshire  |0.014     |805      |55714      |0.014448792      |-3.21%            |
|Real_Monthly|2014;06|Eilean Siar        |0.022     |365      |16250      |0.022461538      |-2.10%            |
|Real_Monthly|2014;06|Fife               |0.032     |7330     |234444     |0.031265462      |2.30%             |
|Real_Monthly|2014;06|Moray              |0.016     |930      |61333      |0.015163126      |5.23%             |
|Real_Monthly|2014;06|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Real_Monthly|2014;06|Stirling           |0.021     |1255     |61176      |0.020514581      |2.31%             |
|Real_Monthly|2014;06|West Dunbartonshire|0.043     |2535     |57500      |0.044086957      |-2.53%            |
|Real_Monthly|2014;07|Aberdeen City      |0.012     |1990     |161667     |0.012309253      |-2.58%            |
|Real_Monthly|2014;07|Aberdeenshire      |0.007     |1165     |156250     |0.007456         |-6.51%            |
|Real_Monthly|2014;07|Argyll & Bute      |0.02      |1070     |52000      |0.020576923      |-2.88%            |
|Real_Monthly|2014;07|East Renfrewshire  |0.015     |855      |55714      |0.015346233      |-2.31%            |
|Real_Monthly|2014;07|Falkirk            |0.03      |3000     |103400     |0.02901354       |3.29%             |
|Real_Monthly|2014;07|Fife               |0.033     |7580     |234444     |0.032331815      |2.02%             |
|Real_Monthly|2014;07|Highland           |0.016     |2260     |147353     |0.015337319      |4.14%             |
|Real_Monthly|2014;07|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Real_Monthly|2014;07|Shetland Islands   |0.006     |95       |15000      |0.006333333      |-5.56%            |
|Real_Monthly|2014;07|Stirling           |0.021     |1235     |61176      |0.020187655      |3.87%             |
|Real_Monthly|2014;07|West Lothian       |0.025     |2835     |118500     |0.023924051      |4.30%             |
|Real_Monthly|2014;08|Aberdeen City      |0.012     |1880     |161667     |0.011628842      |3.09%             |
|Real_Monthly|2014;08|Argyll & Bute      |0.019     |1010     |52000      |0.019423077      |-2.23%            |
|Real_Monthly|2014;08|Eilean Siar        |0.021     |350      |16250      |0.021538462      |-2.56%            |
|Real_Monthly|2014;08|Highland           |0.015     |2165     |147353     |0.014692609      |2.05%             |
|Real_Monthly|2014;08|Moray              |0.015     |880      |61333      |0.014347904      |4.35%             |
|Real_Monthly|2014;08|Orkney Islands     |0.007     |95       |14286      |0.006649867      |5.00%             |
|Real_Monthly|2014;08|Scottish Borders   |0.021     |1450     |67500      |0.021481481      |-2.29%            |
|Real_Monthly|2014;08|Stirling           |0.02      |1195     |61176      |0.019533804      |2.33%             |
|Real_Monthly|2014;08|West Lothian       |0.024     |2760     |118500     |0.023291139      |2.95%             |
|Real_Monthly|2014;09|Aberdeen City      |0.011     |1725     |161667     |0.010670081      |3.00%             |
|Real_Monthly|2014;09|Argyll & Bute      |0.017     |910      |52000      |0.0175           |-2.94%            |
|Real_Monthly|2014;09|East Dunbartonshire|0.013     |870      |64286      |0.013533273      |-4.10%            |
|Real_Monthly|2014;09|East Renfrewshire  |0.013     |760      |55714      |0.013641096      |-4.93%            |
|Real_Monthly|2014;09|Fife               |0.028     |6415     |234444     |0.027362611      |2.28%             |
|Real_Monthly|2014;09|Highland           |0.014     |1980     |147353     |0.01343712       |4.02%             |
|Real_Monthly|2014;09|Moray              |0.013     |745      |61333      |0.012146805      |6.56%             |
|Real_Monthly|2014;09|Orkney Islands     |0.007     |90       |14286      |0.006299874      |10.00%            |
|Real_Monthly|2014;09|Perth & Kinross    |0.013     |1240     |93077      |0.013322303      |-2.48%            |
|Real_Monthly|2014;09|Shetland Islands   |0.005     |70       |15000      |0.004666667      |6.67%             |
|Real_Monthly|2014;09|West Lothian       |0.021     |2405     |118500     |0.020295359      |3.36%             |
|Real_Monthly|2014;10|Aberdeen City      |0.01      |1665     |161667     |0.010298948      |-2.99%            |
|Real_Monthly|2014;10|Aberdeenshire      |0.006     |915      |156250     |0.005856         |2.40%             |
|Real_Monthly|2014;10|East Renfrewshire  |0.012     |700      |55714      |0.012564167      |-4.70%            |
|Real_Monthly|2014;10|Edinburgh City     |0.02      |6725     |349722     |0.019229559      |3.85%             |
|Real_Monthly|2014;10|Falkirk            |0.026     |2595     |103400     |0.025096712      |3.47%             |
|Real_Monthly|2014;10|Highland           |0.013     |1955     |147353     |0.01326746       |-2.06%            |
|Real_Monthly|2014;10|Midlothian         |0.021     |1115     |54211      |0.020567781      |2.06%             |
|Real_Monthly|2014;10|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Real_Monthly|2014;10|Perth & Kinross    |0.013     |1175     |93077      |0.012623957      |2.89%             |
|Real_Monthly|2014;10|Scottish Borders   |0.017     |1180     |67500      |0.017481481      |-2.83%            |
|Real_Monthly|2014;10|Shetland Islands   |0.006     |85       |15000      |0.005666667      |5.56%             |
|Real_Monthly|2014;10|West Dunbartonshire|0.038     |2230     |57500      |0.038782609      |-2.06%            |
|Real_Monthly|2014;11|Angus              |0.018     |1250     |71944      |0.017374625      |3.47%             |
|Real_Monthly|2014;11|East Ayrshire      |0.036     |2820     |76579      |0.036824717      |-2.29%            |
|Real_Monthly|2014;11|East Dunbartonshire|0.013     |875      |64286      |0.013611051      |-4.70%            |
|Real_Monthly|2014;11|East Lothian       |0.018     |1165     |63421      |0.01836931       |-2.05%            |
|Real_Monthly|2014;11|East Renfrewshire  |0.012     |700      |55714      |0.012564167      |-4.70%            |
|Real_Monthly|2014;11|Edinburgh City     |0.019     |6410     |349722     |0.018328844      |3.53%             |
|Real_Monthly|2014;11|Highland           |0.015     |2160     |147353     |0.014658677      |2.28%             |
|Real_Monthly|2014;11|Moray              |0.012     |695      |61333      |0.011331583      |5.57%             |
|Real_Monthly|2014;11|Orkney Islands     |0.008     |100      |14286      |0.00699986       |12.50%            |
|Real_Monthly|2014;11|Shetland Islands   |0.006     |85       |15000      |0.005666667      |5.56%             |
|Real_Monthly|2014;11|South Ayrshire     |0.029     |2015     |68036      |0.029616674      |-2.13%            |
|Real_Monthly|2014;11|West Lothian       |0.019     |2180     |118500     |0.018396624      |3.18%             |
|Real_Monthly|2014;12|Aberdeen City      |0.009     |1525     |161667     |0.00943297       |-4.81%            |
|Real_Monthly|2014;12|Aberdeenshire      |0.006     |960      |156250     |0.006144         |-2.40%            |
|Real_Monthly|2014;12|Clackmannanshire   |0.031     |1030     |32500      |0.031692308      |-2.23%            |
|Real_Monthly|2014;12|East Dunbartonshire|0.013     |855      |64286      |0.013299941      |-2.31%            |
|Real_Monthly|2014;12|East Lothian       |0.018     |1175     |63421      |0.018526986      |-2.93%            |
|Real_Monthly|2014;12|East Renfrewshire  |0.012     |695      |55714      |0.012474423      |-3.95%            |
|Real_Monthly|2014;12|Edinburgh City     |0.018     |6070     |349722     |0.017356643      |3.57%             |
|Real_Monthly|2014;12|Eilean Siar        |0.021     |350      |16250      |0.021538462      |-2.56%            |
|Real_Monthly|2014;12|Highland           |0.017     |2410     |147353     |0.016355283      |3.79%             |
|Real_Monthly|2014;12|Moray              |0.013     |760      |61333      |0.012391372      |4.68%             |
|Real_Monthly|2014;12|Orkney Islands     |0.008     |110      |14286      |0.007699846      |3.75%             |
|Real_Monthly|2014;12|Stirling           |0.017     |1010     |61176      |0.016509742      |2.88%             |
|Real_Monthly|2014;12|West Lothian       |0.018     |2015     |118500     |0.017004219      |5.53%             |
|Real_Monthly|2015;01|Aberdeenshire      |0.006     |1080     |156250     |0.006912         |-15.20%           |
|Real_Monthly|2015;01|Angus              |0.019     |1325     |71944      |0.018417102      |3.07%             |
|Real_Monthly|2015;01|Argyll & Bute      |0.019     |1015     |52000      |0.019519231      |-2.73%            |
|Real_Monthly|2015;01|Dumfries & Galloway|0.021     |1850     |90238      |0.020501341      |2.37%             |
|Real_Monthly|2015;01|East Lothian       |0.018     |1185     |63421      |0.018684663      |-3.80%            |
|Real_Monthly|2015;01|Moray              |0.015     |865      |61333      |0.014103338      |5.98%             |
|Real_Monthly|2015;01|Orkney Islands     |0.009     |115      |14286      |0.008049839      |10.56%            |
|Real_Monthly|2015;01|Scottish Borders   |0.018     |1260     |67500      |0.018666667      |-3.70%            |
|Real_Monthly|2015;01|West Lothian       |0.02      |2280     |118500     |0.019240506      |3.80%             |
|Real_Monthly|2015;02|Aberdeen City      |0.011     |1850     |161667     |0.011443275      |-4.03%            |
|Real_Monthly|2015;02|Aberdeenshire      |0.007     |1215     |156250     |0.007776         |-11.09%           |
|Real_Monthly|2015;02|East Dunbartonshire|0.014     |930      |64286      |0.014466602      |-3.33%            |
|Real_Monthly|2015;02|Moray              |0.016     |930      |61333      |0.015163126      |5.23%             |
|Real_Monthly|2015;02|Orkney Islands     |0.008     |105      |14286      |0.007349853      |8.13%             |
|Real_Monthly|2015;02|Perth & Kinross    |0.013     |1235     |93077      |0.013268584      |-2.07%            |
|Real_Monthly|2015;02|Shetland Islands   |0.007     |95       |15000      |0.006333333      |9.52%             |
|Real_Monthly|2015;02|Stirling           |0.019     |1120     |61176      |0.018307833      |3.64%             |
|Real_Monthly|2015;02|West Lothian       |0.021     |2405     |118500     |0.020295359      |3.36%             |
|Real_Monthly|2015;04|Aberdeen City      |0.012     |2010     |163500     |0.012293578      |-2.45%            |
|Real_Monthly|2015;04|Aberdeenshire      |0.008     |1270     |165667     |0.007665981      |4.18%             |
|Real_Monthly|2015;04|East Dunbartonshire|0.013     |865      |63333      |0.013657967      |-5.06%            |
|Real_Monthly|2015;04|Fife               |0.027     |6195     |234400     |0.026429181      |2.11%             |
|Real_Monthly|2015;04|Glasgow City       |0.036     |15315    |439219     |0.03486871       |3.14%             |
|Real_Monthly|2015;04|Moray              |0.014     |850      |58947      |0.014419733      |-3.00%            |
|Real_Monthly|2015;04|Orkney Islands     |0.007     |95       |12778      |0.007434653      |-6.21%            |
|Real_Monthly|2015;04|Perth & Kinross    |0.012     |1115     |95000      |0.011736842      |2.19%             |
|Real_Monthly|2015;04|Scottish Borders   |0.017     |1140     |69211      |0.01647137       |3.11%             |
|Real_Monthly|2015;04|South Ayrshire     |0.025     |1720     |67200      |0.025595238      |-2.38%            |
|Real_Monthly|2015;04|West Dunbartonshire|0.039     |2280     |57179      |0.039874779      |-2.24%            |
|Real_Monthly|2015;04|West Lothian       |0.02      |2260     |118056     |0.019143457      |4.28%             |
|Real_Monthly|2015;05|Aberdeen City      |0.013     |2185     |163500     |0.013363914      |-2.80%            |
|Real_Monthly|2015;05|Aberdeenshire      |0.008     |1265     |165667     |0.0076358        |4.55%             |
|Real_Monthly|2015;05|Edinburgh City     |0.016     |5725     |344375     |0.016624319      |-3.90%            |
|Real_Monthly|2015;05|Falkirk            |0.023     |2380     |99783      |0.023851758      |-3.70%            |
|Real_Monthly|2015;05|Fife               |0.027     |6175     |234400     |0.026343857      |2.43%             |
|Real_Monthly|2015;05|Glasgow City       |0.035     |14965    |439219     |0.034071841      |2.65%             |
|Real_Monthly|2015;05|Highland           |0.014     |2075     |140833     |0.014733763      |-5.24%            |
|Real_Monthly|2015;05|Midlothian         |0.017     |925      |56471      |0.016380089      |3.65%             |
|Real_Monthly|2015;05|North Lanarkshire  |0.03      |6640     |216034     |0.030735903      |-2.45%            |
|Real_Monthly|2015;05|Orkney Islands     |0.005     |70       |12778      |0.005478166      |-9.56%            |
|Real_Monthly|2015;05|Shetland Islands   |0.006     |90       |14500      |0.006206897      |-3.45%            |
|Real_Monthly|2015;05|South Ayrshire     |0.024     |1650     |67200      |0.024553571      |-2.31%            |
|Real_Monthly|2015;05|West Lothian       |0.019     |2175     |118056     |0.01842346       |3.03%             |
|Real_Monthly|2015;06|Aberdeen City      |0.014     |2205     |163500     |0.013486239      |3.67%             |
|Real_Monthly|2015;06|Angus              |0.018     |1305     |69524      |0.018770497      |-4.28%            |
|Real_Monthly|2015;06|Argyll & Bute      |0.016     |830      |53056      |0.015643848      |2.23%             |
|Real_Monthly|2015;06|East Dunbartonshire|0.013     |865      |63333      |0.013657967      |-5.06%            |
|Real_Monthly|2015;06|East Renfrewshire  |0.012     |700      |56818      |0.012320039      |-2.67%            |
|Real_Monthly|2015;06|Falkirk            |0.021     |2185     |99783      |0.021897518      |-4.27%            |
|Real_Monthly|2015;06|Fife               |0.026     |5965     |234400     |0.025447952      |2.12%             |
|Real_Monthly|2015;06|Glasgow City       |0.035     |14830    |439219     |0.033764477      |3.53%             |
|Real_Monthly|2015;06|Midlothian         |0.017     |905      |56471      |0.016025925      |5.73%             |
|Real_Monthly|2015;06|Moray              |0.013     |795      |58947      |0.013486691      |-3.74%            |
|Real_Monthly|2015;06|Orkney Islands     |0.004     |60       |12778      |0.004695571      |-17.39%           |
|Real_Monthly|2015;06|Perth & Kinross    |0.012     |1070     |95000      |0.011263158      |6.14%             |
|Real_Monthly|2015;06|Scottish Borders   |0.016     |1075     |69211      |0.015532213      |2.92%             |
|Real_Monthly|2015;06|Shetland Islands   |0.006     |90       |14500      |0.006206897      |-3.45%            |
|Real_Monthly|2015;06|West Lothian       |0.018     |2070     |118056     |0.017534052      |2.59%             |
|Real_Monthly|2015;07|East Dunbartonshire|0.013     |880      |63333      |0.01389481       |-6.88%            |
|Real_Monthly|2015;07|East Renfrewshire  |0.013     |715      |56818      |0.01258404       |3.20%             |
|Real_Monthly|2015;07|Glasgow City       |0.036     |15185    |439219     |0.03457273       |3.96%             |
|Real_Monthly|2015;07|Highland           |0.014     |2015     |140833     |0.014307726      |-2.20%            |
|Real_Monthly|2015;07|Midlothian         |0.018     |960      |56471      |0.016999876      |5.56%             |
|Real_Monthly|2015;07|Moray              |0.013     |785      |58947      |0.013317048      |-2.44%            |
|Real_Monthly|2015;07|Orkney Islands     |0.005     |70       |12778      |0.005478166      |-9.56%            |
|Real_Monthly|2015;07|Shetland Islands   |0.006     |85       |14500      |0.005862069      |2.30%             |
|Real_Monthly|2015;07|Stirling           |0.015     |885      |62188      |0.014231041      |5.13%             |
|Real_Monthly|2015;08|Aberdeen City      |0.014     |2350     |163500     |0.014373089      |-2.66%            |
|Real_Monthly|2015;08|Aberdeenshire      |0.009     |1430     |165667     |0.008631773      |4.09%             |
|Real_Monthly|2015;08|Argyll & Bute      |0.017     |865      |53056      |0.016303528      |4.10%             |
|Real_Monthly|2015;08|Dumfries & Galloway|0.019     |1740     |88889      |0.019574976      |-3.03%            |
|Real_Monthly|2015;08|East Dunbartonshire|0.013     |855      |63333      |0.013500071      |-3.85%            |
|Real_Monthly|2015;08|East Lothian       |0.017     |1080     |65294      |0.01654057       |2.70%             |
|Real_Monthly|2015;08|Edinburgh City     |0.015     |5325     |344375     |0.015462795      |-3.09%            |
|Real_Monthly|2015;08|Eilean Siar        |0.02      |325      |15870      |0.020478891      |-2.39%            |
|Real_Monthly|2015;08|Falkirk            |0.022     |2280     |99783      |0.022849584      |-3.86%            |
|Real_Monthly|2015;08|Glasgow City       |0.036     |15135    |439219     |0.034458892      |4.28%             |
|Real_Monthly|2015;08|Highland           |0.013     |1940     |140833     |0.013775181      |-5.96%            |
|Real_Monthly|2015;08|North Ayrshire     |0.044     |3745     |83372      |0.044919158      |-2.09%            |
|Real_Monthly|2015;08|Perth & Kinross    |0.012     |1060     |95000      |0.011157895      |7.02%             |
|Real_Monthly|2015;08|Scottish Borders   |0.017     |1140     |69211      |0.01647137       |3.11%             |
|Real_Monthly|2015;08|Shetland Islands   |0.005     |80       |14500      |0.005517241      |-10.34%           |
|Real_Monthly|2015;08|Stirling           |0.015     |875      |62188      |0.014070239      |6.20%             |
|Real_Monthly|2015;09|Aberdeenshire      |0.009     |1420     |165667     |0.008571411      |4.76%             |
|Real_Monthly|2015;09|East Dunbartonshire|0.012     |785      |63333      |0.012394802      |-3.29%            |
|Real_Monthly|2015;09|Highland           |0.013     |1875     |140833     |0.013313641      |-2.41%            |
|Real_Monthly|2015;09|Midlothian         |0.017     |930      |56471      |0.01646863       |3.13%             |
|Real_Monthly|2015;09|Moray              |0.012     |690      |58947      |0.01170543       |2.45%             |
|Real_Monthly|2015;09|North Lanarkshire  |0.029     |6450     |216034     |0.029856411      |-2.95%            |
|Real_Monthly|2015;09|Orkney Islands     |0.006     |80       |12778      |0.006260761      |-4.35%            |
|Real_Monthly|2015;09|Perth & Kinross    |0.011     |980      |95000      |0.010315789      |6.22%             |
|Real_Monthly|2015;09|Shetland Islands   |0.006     |90       |14500      |0.006206897      |-3.45%            |
|Real_Monthly|2015;09|Stirling           |0.014     |835      |62188      |0.013427028      |4.09%             |
|Real_Monthly|2015;09|West Dunbartonshire|0.037     |2175     |57179      |0.038038441      |-2.81%            |
|Real_Monthly|2015;09|West Lothian       |0.017     |1940     |118056     |0.016432879      |3.34%             |
|Real_Monthly|2015;10|Aberdeenshire      |0.009     |1530     |165667     |0.009235394      |-2.62%            |
|Real_Monthly|2015;10|Angus              |0.016     |1145     |69524      |0.016469133      |-2.93%            |
|Real_Monthly|2015;10|Argyll & Bute      |0.016     |815      |53056      |0.015361128      |3.99%             |
|Real_Monthly|2015;10|Dumfries & Galloway|0.017     |1545     |88889      |0.017381228      |-2.24%            |
|Real_Monthly|2015;10|East Renfrewshire  |0.01      |590      |56818      |0.010384033      |-3.84%            |
|Real_Monthly|2015;10|Glasgow City       |0.032     |13675    |439219     |0.03113481       |2.70%             |
|Real_Monthly|2015;10|Highland           |0.013     |1925     |140833     |0.013668671      |-5.14%            |
|Real_Monthly|2015;10|Moray              |0.011     |680      |58947      |0.011535786      |-4.87%            |
|Real_Monthly|2015;10|Orkney Islands     |0.006     |85       |12778      |0.006652058      |-10.87%           |
|Real_Monthly|2015;10|Scottish Borders   |0.015     |1010     |69211      |0.014593056      |2.71%             |
|Real_Monthly|2015;10|Shetland Islands   |0.006     |95       |14500      |0.006551724      |-9.20%            |
|Real_Monthly|2015;11|Aberdeen City      |0.016     |2530     |163500     |0.015474006      |3.29%             |
|Real_Monthly|2015;11|Angus              |0.016     |1175     |69524      |0.016900639      |-5.63%            |
|Real_Monthly|2015;11|East Dunbartonshire|0.01      |665      |63333      |0.010500055      |-5.00%            |
|Real_Monthly|2015;11|Fife               |0.021     |4795     |234400     |0.020456485      |2.59%             |
|Real_Monthly|2015;11|Glasgow City       |0.031     |13140    |439219     |0.029916739      |3.49%             |
|Real_Monthly|2015;11|Highland           |0.014     |2020     |140833     |0.014343229      |-2.45%            |
|Real_Monthly|2015;11|Inverclyde         |0.027     |1345     |51000      |0.026372549      |2.32%             |
|Real_Monthly|2015;11|Midlothian         |0.016     |875      |56471      |0.015494679      |3.16%             |
|Real_Monthly|2015;11|Orkney Islands     |0.006     |80       |12778      |0.006260761      |-4.35%            |
|Real_Monthly|2015;11|Perth & Kinross    |0.01      |925      |95000      |0.009736842      |2.63%             |
|Real_Monthly|2015;11|Shetland Islands   |0.007     |105      |14500      |0.007241379      |-3.45%            |
|Real_Monthly|2015;11|South Lanarkshire  |0.02      |4110     |200652     |0.020483225      |-2.42%            |
|Real_Monthly|2015;11|Stirling           |0.014     |845      |62188      |0.01358783       |2.94%             |
|Real_Monthly|2015;11|West Lothian       |0.016     |1820     |118056     |0.015416413      |3.65%             |
|Real_Monthly|2015;12|Aberdeen City      |0.016     |2525     |163500     |0.015443425      |3.48%             |
|Real_Monthly|2015;12|Aberdeenshire      |0.011     |1760     |165667     |0.010623721      |3.42%             |
|Real_Monthly|2015;12|Angus              |0.017     |1230     |69524      |0.017691732      |-4.07%            |
|Real_Monthly|2015;12|Argyll & Bute      |0.017     |875      |53056      |0.016492008      |2.99%             |
|Real_Monthly|2015;12|East Dunbartonshire|0.01      |670      |63333      |0.010579003      |-5.79%            |
|Real_Monthly|2015;12|East Lothian       |0.016     |1000     |65294      |0.015315343      |4.28%             |
|Real_Monthly|2015;12|Falkirk            |0.02      |2065     |99783      |0.020694908      |-3.47%            |
|Real_Monthly|2015;12|Glasgow City       |0.03      |12670    |439219     |0.028846657      |3.84%             |
|Real_Monthly|2015;12|Highland           |0.015     |2230     |140833     |0.015834357      |-5.56%            |
|Real_Monthly|2015;12|Moray              |0.013     |750      |58947      |0.012723294      |2.13%             |
|Real_Monthly|2015;12|North Lanarkshire  |0.026     |5770     |216034     |0.026708759      |-2.73%            |
|Real_Monthly|2015;12|Orkney Islands     |0.006     |85       |12778      |0.006652058      |-10.87%           |
|Real_Monthly|2015;12|Scottish Borders   |0.016     |1070     |69211      |0.01545997       |3.38%             |
|Real_Monthly|2015;12|Shetland Islands   |0.009     |125      |14500      |0.00862069       |4.21%             |
|Real_Monthly|2015;12|Stirling           |0.014     |845      |62188      |0.01358783       |2.94%             |
|Real_Monthly|2016;01|Aberdeenshire      |0.012     |2055     |165667     |0.012404402      |-3.37%            |
|Real_Monthly|2016;01|Dumfries & Galloway|0.018     |1635     |88889      |0.018393727      |-2.19%            |
|Real_Monthly|2016;01|East Dunbartonshire|0.011     |725      |63333      |0.011447429      |-4.07%            |
|Real_Monthly|2016;01|East Lothian       |0.016     |1020     |65294      |0.01562165       |2.36%             |
|Real_Monthly|2016;01|Falkirk            |0.021     |2185     |99783      |0.021897518      |-4.27%            |
|Real_Monthly|2016;01|Glasgow City       |0.031     |13240    |439219     |0.030144415      |2.76%             |
|Real_Monthly|2016;01|Highland           |0.016     |2365     |140833     |0.016792939      |-4.96%            |
|Real_Monthly|2016;01|Midlothian         |0.016     |885      |56471      |0.015671761      |2.05%             |
|Real_Monthly|2016;01|North Lanarkshire  |0.027     |6030     |216034     |0.027912273      |-3.38%            |
|Real_Monthly|2016;01|Orkney Islands     |0.008     |105      |12778      |0.008217248      |-2.72%            |
|Real_Monthly|2016;01|Perth & Kinross    |0.012     |1090     |95000      |0.011473684      |4.39%             |
|Real_Monthly|2016;01|Renfrewshire       |0.025     |2885     |112222     |0.025707972      |-2.83%            |
|Real_Monthly|2016;01|Shetland Islands   |0.008     |125      |14500      |0.00862069       |-7.76%            |
|Real_Monthly|2016;01|Stirling           |0.015     |890      |62188      |0.014311443      |4.59%             |
|Real_Monthly|2016;02|Aberdeen City      |0.019     |3025     |163500     |0.018501529      |2.62%             |
|Real_Monthly|2016;02|Clackmannanshire   |0.028     |895      |32679      |0.027387619      |2.19%             |
|Real_Monthly|2016;02|Dumfries & Galloway|0.019     |1655     |88889      |0.018618727      |2.01%             |
|Real_Monthly|2016;02|East Renfrewshire  |0.011     |650      |56818      |0.011440037      |-4.00%            |
|Real_Monthly|2016;02|Edinburgh City     |0.015     |5415     |344375     |0.015724138      |-4.83%            |
|Real_Monthly|2016;02|Highland           |0.017     |2520     |140833     |0.017893533      |-5.26%            |
|Real_Monthly|2016;02|Orkney Islands     |0.008     |105      |12778      |0.008217248      |-2.72%            |
|Real_Monthly|2016;02|Scottish Borders   |0.02      |1345     |69211      |0.019433327      |2.83%             |
|Real_Monthly|2016;02|Shetland Islands   |0.009     |135      |14500      |0.009310345      |-3.45%            |
|Real_Monthly|2016;02|Stirling           |0.017     |1005     |62188      |0.016160674      |4.94%             |
|Real_Monthly|2016;02|West Lothian       |0.018     |2065     |118056     |0.017491699      |2.82%             |
|Real_Monthly|2016;04|Argyll & Bute      |0.016     |865      |51111      |0.01692395       |-5.77%            |
|Real_Monthly|2016;04|East Renfrewshire  |0.011     |635      |55769      |0.011386254      |-3.51%            |
|Real_Monthly|2016;04|Falkirk            |0.022     |2260     |100417     |0.022506149      |-2.30%            |
|Real_Monthly|2016;04|Fife               |0.024     |5660     |229444     |0.024668329      |-2.78%            |
|Real_Monthly|2016;04|Highland           |0.016     |2385     |146000     |0.016335616      |-2.10%            |
|Real_Monthly|2016;04|Midlothian         |0.018     |975      |56944      |0.017122085      |4.88%             |
|Real_Monthly|2016;04|Orkney Islands     |0.009     |115      |13182      |0.008724018      |3.07%             |
|Real_Monthly|2016;04|Perth & Kinross    |0.012     |1080     |93077      |0.011603296      |3.31%             |
|Real_Monthly|2016;04|Shetland Islands   |0.01      |150      |14500      |0.010344828      |-3.45%            |
|Real_Monthly|2016;04|South Lanarkshire  |0.022     |4560     |198913     |0.022924595      |-4.20%            |
|Real_Monthly|2016;04|Stirling           |0.015     |910      |59412      |0.015316771      |-2.11%            |
|Real_Monthly|2016;05|Aberdeenshire      |0.015     |2555     |166875     |0.015310861      |-2.07%            |
|Real_Monthly|2016;05|Argyll & Bute      |0.016     |850      |51111      |0.016630471      |-3.94%            |
|Real_Monthly|2016;05|Dumfries & Galloway|0.017     |1540     |86579      |0.017787223      |-4.63%            |
|Real_Monthly|2016;05|Dundee City        |0.035     |3430     |100152     |0.034247943      |2.15%             |
|Real_Monthly|2016;05|East Dunbartonshire|0.012     |760      |64643      |0.01175688       |2.03%             |
|Real_Monthly|2016;05|East Lothian       |0.016     |1025     |66250      |0.015471698      |3.30%             |
|Real_Monthly|2016;05|East Renfrewshire  |0.011     |630      |55769      |0.011296598      |-2.70%            |
|Real_Monthly|2016;05|Eilean Siar        |0.021     |340      |15455      |0.021999353      |-4.76%            |
|Real_Monthly|2016;05|Falkirk            |0.022     |2265     |100417     |0.022555942      |-2.53%            |
|Real_Monthly|2016;05|Highland           |0.016     |2250     |146000     |0.015410959      |3.68%             |
|Real_Monthly|2016;05|Moray              |0.018     |1060     |60476      |0.017527614      |2.62%             |
|Real_Monthly|2016;05|Orkney Islands     |0.008     |100      |13182      |0.007586102      |5.17%             |
|Real_Monthly|2016;05|Perth & Kinross    |0.011     |1050     |93077      |0.011280982      |-2.55%            |
|Real_Monthly|2016;05|South Lanarkshire  |0.022     |4485     |198913     |0.022547546      |-2.49%            |
|Real_Monthly|2016;05|West Lothian       |0.018     |2115     |114500     |0.018471616      |-2.62%            |
|Real_Monthly|2016;06|Aberdeenshire      |0.016     |2575     |166875     |0.015430712      |3.56%             |
|Real_Monthly|2016;06|Argyll & Bute      |0.016     |845      |51111      |0.016532645      |-3.33%            |
|Real_Monthly|2016;06|Dumfries & Galloway|0.017     |1525     |86579      |0.017613971      |-3.61%            |
|Real_Monthly|2016;06|East Dunbartonshire|0.011     |750      |64643      |0.011602184      |-5.47%            |
|Real_Monthly|2016;06|East Renfrewshire  |0.011     |640      |55769      |0.01147591       |-4.33%            |
|Real_Monthly|2016;06|Edinburgh City     |0.015     |5285     |359667     |0.014694148      |2.04%             |
|Real_Monthly|2016;06|Fife               |0.024     |5625     |229444     |0.024515786      |-2.15%            |
|Real_Monthly|2016;06|Midlothian         |0.016     |885      |56944      |0.015541585      |2.87%             |
|Real_Monthly|2016;06|Perth & Kinross    |0.011     |1060     |93077      |0.01138842       |-3.53%            |
|Real_Monthly|2016;06|Scottish Borders   |0.016     |1120     |66842      |0.016755932      |-4.72%            |
|Real_Monthly|2016;06|Shetland Islands   |0.009     |135      |14500      |0.009310345      |-3.45%            |
|Real_Monthly|2016;07|Aberdeenshire      |0.016     |2565     |166875     |0.015370787      |3.93%             |
|Real_Monthly|2016;07|Argyll & Bute      |0.016     |840      |51111      |0.016434818      |-2.72%            |
|Real_Monthly|2016;07|Clackmannanshire   |0.026     |835      |32931      |0.025356047      |2.48%             |
|Real_Monthly|2016;07|Dumfries & Galloway|0.017     |1515     |86579      |0.01749847       |-2.93%            |
|Real_Monthly|2016;07|East Lothian       |0.017     |1080     |66250      |0.016301887      |4.11%             |
|Real_Monthly|2016;07|East Renfrewshire  |0.012     |690      |55769      |0.012372465      |-3.10%            |
|Real_Monthly|2016;07|Edinburgh City     |0.015     |5255     |359667     |0.014610737      |2.60%             |
|Real_Monthly|2016;07|Falkirk            |0.021     |2185     |100417     |0.021759264      |-3.62%            |
|Real_Monthly|2016;07|Midlothian         |0.016     |885      |56944      |0.015541585      |2.87%             |
|Real_Monthly|2016;07|Moray              |0.017     |985      |60476      |0.016287453      |4.19%             |
|Real_Monthly|2016;07|Orkney Islands     |0.008     |110      |13182      |0.008344712      |-4.31%            |
|Real_Monthly|2016;07|Perth & Kinross    |0.012     |1075     |93077      |0.011549577      |3.75%             |
|Real_Monthly|2016;07|Scottish Borders   |0.016     |1120     |66842      |0.016755932      |-4.72%            |
|Real_Monthly|2016;07|Shetland Islands   |0.009     |125      |14500      |0.00862069       |4.21%             |
|Real_Monthly|2016;07|South Ayrshire     |0.025     |1670     |68269      |0.024462055      |2.15%             |
|Real_Monthly|2016;07|Stirling           |0.015     |935      |59412      |0.015737561      |-4.92%            |
|Real_Monthly|2016;08|Aberdeen City      |0.023     |3635     |161458     |0.022513595      |2.11%             |
|Real_Monthly|2016;08|Aberdeenshire      |0.015     |2560     |166875     |0.015340824      |-2.27%            |
|Real_Monthly|2016;08|Angus              |0.022     |1580     |70227      |0.022498469      |-2.27%            |
|Real_Monthly|2016;08|Dumfries & Galloway|0.017     |1520     |86579      |0.01755622       |-3.27%            |
|Real_Monthly|2016;08|East Ayrshire      |0.034     |2640     |76000      |0.034736842      |-2.17%            |
|Real_Monthly|2016;08|East Dunbartonshire|0.013     |820      |64643      |0.012685055      |2.42%             |
|Real_Monthly|2016;08|East Lothian       |0.017     |1075     |66250      |0.016226415      |4.55%             |
|Real_Monthly|2016;08|East Renfrewshire  |0.013     |740      |55769      |0.01326902       |-2.07%            |
|Real_Monthly|2016;08|Edinburgh City     |0.015     |5235     |359667     |0.01455513       |2.97%             |
|Real_Monthly|2016;08|Falkirk            |0.022     |2255     |100417     |0.022456357      |-2.07%            |
|Real_Monthly|2016;08|Fife               |0.026     |6125     |229444     |0.026694967      |-2.67%            |
|Real_Monthly|2016;08|Highland           |0.014     |2100     |146000     |0.014383562      |-2.74%            |
|Real_Monthly|2016;08|Midlothian         |0.016     |885      |56944      |0.015541585      |2.87%             |
|Real_Monthly|2016;08|Moray              |0.016     |935      |60476      |0.015460679      |3.37%             |
|Real_Monthly|2016;08|Scottish Borders   |0.016     |1110     |66842      |0.016606325      |-3.79%            |
|Real_Monthly|2016;08|South Ayrshire     |0.026     |1735     |68269      |0.02541417       |2.25%             |
|Real_Monthly|2016;08|Stirling           |0.015     |925      |59412      |0.015569245      |-3.79%            |
|Real_Monthly|2016;08|West Lothian       |0.019     |2230     |114500     |0.019475983      |-2.51%            |
|Real_Monthly|2016;09|Angus              |0.02      |1440     |70227      |0.020504934      |-2.52%            |
|Real_Monthly|2016;09|Argyll & Bute      |0.016     |850      |51111      |0.016630471      |-3.94%            |
|Real_Monthly|2016;09|Clackmannanshire   |0.026     |830      |32931      |0.025204215      |3.06%             |
|Real_Monthly|2016;09|Dumfries & Galloway|0.016     |1440     |86579      |0.016632209      |-3.95%            |
|Real_Monthly|2016;09|Dundee City        |0.037     |3600     |100152     |0.035945363      |2.85%             |
|Real_Monthly|2016;09|East Ayrshire      |0.032     |2495     |76000      |0.032828947      |-2.59%            |
|Real_Monthly|2016;09|East Dunbartonshire|0.012     |805      |64643      |0.012453011      |-3.78%            |
|Real_Monthly|2016;09|East Lothian       |0.017     |1100     |66250      |0.016603774      |2.33%             |
|Real_Monthly|2016;09|Eilean Siar        |0.018     |290      |15455      |0.018764154      |-4.25%            |
|Real_Monthly|2016;09|Falkirk            |0.021     |2180     |100417     |0.021709472      |-3.38%            |
|Real_Monthly|2016;09|Fife               |0.024     |5620     |229444     |0.024493994      |-2.06%            |
|Real_Monthly|2016;09|Midlothian         |0.016     |870      |56944      |0.015278168      |4.51%             |
|Real_Monthly|2016;09|Moray              |0.015     |870      |60476      |0.014385872      |4.09%             |
|Real_Monthly|2016;09|Perth & Kinross    |0.011     |985      |93077      |0.010582636      |3.79%             |
|Real_Monthly|2016;09|Shetland Islands   |0.009     |125      |14500      |0.00862069       |4.21%             |
|Real_Monthly|2016;09|South Ayrshire     |0.025     |1670     |68269      |0.024462055      |2.15%             |
|Real_Monthly|2016;10|Aberdeen City      |0.022     |3460     |161458     |0.021429722      |2.59%             |
|Real_Monthly|2016;10|Clackmannanshire   |0.026     |830      |32931      |0.025204215      |3.06%             |
|Real_Monthly|2016;10|East Dunbartonshire|0.012     |795      |64643      |0.012298315      |-2.49%            |
|Real_Monthly|2016;10|East Lothian       |0.018     |1150     |66250      |0.017358491      |3.56%             |
|Real_Monthly|2016;10|East Renfrewshire  |0.013     |710      |55769      |0.012731087      |2.07%             |
|Real_Monthly|2016;10|Eilean Siar        |0.019     |305      |15455      |0.019734714      |-3.87%            |
|Real_Monthly|2016;10|Fife               |0.023     |5415     |229444     |0.02360053       |-2.61%            |
|Real_Monthly|2016;10|Orkney Islands     |0.008     |115      |13182      |0.008724018      |-9.05%            |
|Real_Monthly|2016;10|Perth & Kinross    |0.01      |970      |93077      |0.010421479      |-4.21%            |
|Real_Monthly|2016;10|Stirling           |0.015     |940      |59412      |0.01582172       |-5.48%            |
|Real_Monthly|2016;11|Angus              |0.02      |1435     |70227      |0.020433736      |-2.17%            |
|Real_Monthly|2016;11|Argyll & Bute      |0.016     |835      |51111      |0.016336992      |-2.11%            |
|Real_Monthly|2016;11|East Dunbartonshire|0.011     |750      |64643      |0.011602184      |-5.47%            |
|Real_Monthly|2016;11|East Lothian       |0.019     |1225     |66250      |0.018490566      |2.68%             |
|Real_Monthly|2016;11|East Renfrewshire  |0.012     |710      |55769      |0.012731087      |-6.09%            |
|Real_Monthly|2016;11|Eilean Siar        |0.019     |310      |15455      |0.020058234      |-5.57%            |
|Real_Monthly|2016;11|Highland           |0.016     |2250     |146000     |0.015410959      |3.68%             |
|Real_Monthly|2016;11|Midlothian         |0.016     |870      |56944      |0.015278168      |4.51%             |
|Real_Monthly|2016;11|Moray              |0.015     |880      |60476      |0.014551227      |2.99%             |
|Real_Monthly|2016;11|Perth & Kinross    |0.011     |990      |93077      |0.010636355      |3.31%             |
|Real_Monthly|2016;11|Scottish Borders   |0.015     |1050     |66842      |0.015708686      |-4.72%            |
|Real_Monthly|2016;11|South Ayrshire     |0.025     |1670     |68269      |0.024462055      |2.15%             |
|Real_Monthly|2016;11|South Lanarkshire  |0.021     |4315     |198913     |0.021692901      |-3.30%            |
|Real_Monthly|2016;11|Stirling           |0.016     |975      |59412      |0.016410826      |-2.57%            |
|Real_Monthly|2016;12|Argyll & Bute      |0.016     |855      |51111      |0.016728297      |-4.55%            |
|Real_Monthly|2016;12|Dumfries & Galloway|0.016     |1455     |86579      |0.016805461      |-5.03%            |
|Real_Monthly|2016;12|Dundee City        |0.033     |3215     |100152     |0.032101206      |2.72%             |
|Real_Monthly|2016;12|East Lothian       |0.02      |1270     |66250      |0.019169811      |4.15%             |
|Real_Monthly|2016;12|East Renfrewshire  |0.012     |685      |55769      |0.012282809      |-2.36%            |
|Real_Monthly|2016;12|Edinburgh City     |0.014     |4930     |359667     |0.013707124      |2.09%             |
|Real_Monthly|2016;12|Eilean Siar        |0.019     |305      |15455      |0.019734714      |-3.87%            |
|Real_Monthly|2016;12|Fife               |0.023     |5445     |229444     |0.023731281      |-3.18%            |
|Real_Monthly|2016;12|Midlothian         |0.016     |860      |56944      |0.015102557      |5.61%             |
|Real_Monthly|2016;12|North Lanarkshire  |0.026     |5610     |220714     |0.025417509      |2.24%             |
|Real_Monthly|2016;12|Perth & Kinross    |0.011     |995      |93077      |0.010690074      |2.82%             |
|Real_Monthly|2016;12|Shetland Islands   |0.008     |120      |14500      |0.008275862      |-3.45%            |
|Real_Monthly|2016;12|West Lothian       |0.016     |1875     |114500     |0.016375546      |-2.35%            |
|Real_Monthly|2017;01|Aberdeen City      |0.023     |3605     |161458     |0.022327788      |2.92%             |
|Real_Monthly|2017;01|Argyll & Bute      |0.017     |890      |51111      |0.017413081      |-2.43%            |
|Real_Monthly|2017;01|Dumfries & Galloway|0.017     |1515     |86579      |0.01749847       |-2.93%            |
|Real_Monthly|2017;01|East Dunbartonshire|0.012     |760      |64643      |0.01175688       |2.03%             |
|Real_Monthly|2017;01|East Lothian       |0.021     |1350     |66250      |0.020377358      |2.96%             |
|Real_Monthly|2017;01|Eilean Siar        |0.019     |305      |15455      |0.019734714      |-3.87%            |
|Real_Monthly|2017;01|Falkirk            |0.022     |2285     |100417     |0.022755111      |-3.43%            |
|Real_Monthly|2017;01|Fife               |0.025     |5880     |229444     |0.025627168      |-2.51%            |
|Real_Monthly|2017;01|Highland           |0.019     |2700     |146000     |0.018493151      |2.67%             |
|Real_Monthly|2017;01|Midlothian         |0.016     |890      |56944      |0.01562939       |2.32%             |
|Real_Monthly|2017;01|Moray              |0.019     |1125     |60476      |0.018602421      |2.09%             |
|Real_Monthly|2017;01|Perth & Kinross    |0.012     |1075     |93077      |0.011549577      |3.75%             |
|Real_Monthly|2017;01|Shetland Islands   |0.01      |140      |14500      |0.009655172      |3.45%             |
|Real_Monthly|2017;01|South Ayrshire     |0.026     |1735     |68269      |0.02541417       |2.25%             |
|Real_Monthly|2017;01|Stirling           |0.016     |985      |59412      |0.016579142      |-3.62%            |
|Real_Monthly|2017;01|West Lothian       |0.017     |2010     |114500     |0.017554585      |-3.26%            |
|Real_Monthly|2017;02|Aberdeen City      |0.024     |3785     |161458     |0.023442629      |2.32%             |
|Real_Monthly|2017;02|Aberdeenshire      |0.016     |2610     |166875     |0.015640449      |2.25%             |
|Real_Monthly|2017;02|Clackmannanshire   |0.029     |930      |32931      |0.028240867      |2.62%             |
|Real_Monthly|2017;02|Dumfries & Galloway|0.018     |1620     |86579      |0.018711235      |-3.95%            |
|Real_Monthly|2017;02|East Ayrshire      |0.034     |2640     |76000      |0.034736842      |-2.17%            |
|Real_Monthly|2017;02|East Dunbartonshire|0.013     |820      |64643      |0.012685055      |2.42%             |
|Real_Monthly|2017;02|East Renfrewshire  |0.012     |710      |55769      |0.012731087      |-6.09%            |
|Real_Monthly|2017;02|Edinburgh City     |0.015     |5285     |359667     |0.014694148      |2.04%             |
|Real_Monthly|2017;02|Eilean Siar        |0.02      |320      |15455      |0.020705273      |-3.53%            |
|Real_Monthly|2017;02|Falkirk            |0.023     |2365     |100417     |0.023551789      |-2.40%            |
|Real_Monthly|2017;02|Fife               |0.026     |6140     |229444     |0.026760342      |-2.92%            |
|Real_Monthly|2017;02|Highland           |0.02      |2845     |146000     |0.019486301      |2.57%             |
|Real_Monthly|2017;02|Moray              |0.021     |1215     |60476      |0.020090614      |4.33%             |
|Real_Monthly|2017;02|Orkney Islands     |0.01      |140      |13182      |0.010620543      |-6.21%            |
|Real_Monthly|2017;02|Perth & Kinross    |0.013     |1165     |93077      |0.012516519      |3.72%             |
|Real_Monthly|2017;02|Renfrewshire       |0.026     |3005     |112407     |0.026733211      |-2.82%            |
|Real_Monthly|2017;02|Scottish Borders   |0.018     |1235     |66842      |0.018476407      |-2.65%            |
|Real_Monthly|2017;02|Shetland Islands   |0.01      |135      |14500      |0.009310345      |6.90%             |
|Real_Monthly|2017;02|South Ayrshire     |0.027     |1785     |68269      |0.026146567      |3.16%             |
|Real_Monthly|2017;02|South Lanarkshire  |0.022     |4480     |198913     |0.022522409      |-2.37%            |
|Real_Monthly|2017;02|Stirling           |0.016     |990      |59412      |0.0166633        |-4.15%            |
|Real_Monthly|2017;04|Aberdeen City      |0.024     |3825     |156136     |0.024497874      |-2.07%            |
|Real_Monthly|2017;04|Dundee City        |0.034     |3320     |99730      |0.033289883      |2.09%             |
|Real_Monthly|2017;04|East Ayrshire      |0.033     |2550     |75375      |0.033830846      |-2.52%            |
|Real_Monthly|2017;04|East Dunbartonshire|0.015     |980      |63333      |0.015473766      |-3.16%            |
|Real_Monthly|2017;04|Eilean Siar        |0.02      |320      |15526      |0.020610589      |-3.05%            |
|Real_Monthly|2017;04|Glasgow City       |0.033     |14385    |445000     |0.032325843      |2.04%             |
|Real_Monthly|2017;04|Orkney Islands     |0.011     |145      |13889      |0.010439916      |5.09%             |
|Real_Monthly|2017;04|Shetland Islands   |0.01      |140      |13333      |0.010500263      |-5.00%            |
|Real_Monthly|2017;04|West Dunbartonshire|0.036     |2095     |56410      |0.037138805      |-3.16%            |
|Real_Monthly|2017;04|West Lothian       |0.019     |2275     |115263     |0.01973747       |-3.88%            |
|Real_Monthly|2017;05|Aberdeenshire      |0.015     |2500     |158214     |0.015801383      |-5.34%            |
|Real_Monthly|2017;05|Argyll & Bute      |0.017     |885      |50833      |0.01740995       |-2.41%            |
|Real_Monthly|2017;05|Dumfries & Galloway|0.017     |1525     |87105      |0.017507606      |-2.99%            |
|Real_Monthly|2017;05|East Ayrshire      |0.032     |2480     |75375      |0.032902156      |-2.82%            |
|Real_Monthly|2017;05|East Dunbartonshire|0.015     |1005     |63333      |0.015868505      |-5.79%            |
|Real_Monthly|2017;05|East Renfrewshire  |0.012     |665      |57917      |0.011481948      |4.32%             |
|Real_Monthly|2017;05|Glasgow City       |0.033     |14250    |445000     |0.032022472      |2.96%             |
|Real_Monthly|2017;05|Highland           |0.02      |2945     |143846     |0.020473284      |-2.37%            |
|Real_Monthly|2017;05|North Lanarkshire  |0.028     |6065     |221071     |0.027434625      |2.02%             |
|Real_Monthly|2017;05|Orkney Islands     |0.01      |130      |13889      |0.009359925      |6.40%             |
|Real_Monthly|2017;05|Perth & Kinross    |0.012     |1135     |91154      |0.012451456      |-3.76%            |
|Real_Monthly|2017;05|Scottish Borders   |0.017     |1180     |67353      |0.017519635      |-3.06%            |
|Real_Monthly|2017;05|Shetland Islands   |0.009     |130      |13333      |0.009750244      |-8.34%            |
|Real_Monthly|2017;06|Aberdeen City      |0.023     |3700     |156136     |0.02369729       |-3.03%            |
|Real_Monthly|2017;06|Angus              |0.022     |1570     |69231      |0.022677702      |-3.08%            |
|Real_Monthly|2017;06|Argyll & Bute      |0.017     |885      |50833      |0.01740995       |-2.41%            |
|Real_Monthly|2017;06|Dumfries & Galloway|0.017     |1545     |87105      |0.017737214      |-4.34%            |
|Real_Monthly|2017;06|Edinburgh City     |0.015     |5240     |359286     |0.014584481      |2.77%             |
|Real_Monthly|2017;06|Eilean Siar        |0.018     |290      |15526      |0.018678346      |-3.77%            |
|Real_Monthly|2017;06|Moray              |0.018     |1060     |57619      |0.018396709      |-2.20%            |
|Real_Monthly|2017;06|Shetland Islands   |0.008     |115      |13333      |0.008625216      |-7.82%            |
|Real_Monthly|2017;06|South Lanarkshire  |0.021     |4325     |200714     |0.021548073      |-2.61%            |
|Real_Monthly|2017;06|Stirling           |0.016     |945      |61304      |0.015414981      |3.66%             |
|Real_Monthly|2017;06|West Dunbartonshire|0.034     |1980     |56410      |0.03510016       |-3.24%            |
|Real_Monthly|2017;07|Aberdeenshire      |0.014     |2340     |158214     |0.014790094      |-5.64%            |
|Real_Monthly|2017;07|East Ayrshire      |0.033     |2555     |75375      |0.033897181      |-2.72%            |
|Real_Monthly|2017;07|East Dunbartonshire|0.017     |1100     |63333      |0.017368512      |-2.17%            |
|Real_Monthly|2017;07|East Renfrewshire  |0.012     |660      |57917      |0.011395618      |5.04%             |
|Real_Monthly|2017;07|Eilean Siar        |0.018     |290      |15526      |0.018678346      |-3.77%            |
|Real_Monthly|2017;07|Glasgow City       |0.033     |14270    |445000     |0.032067416      |2.83%             |
|Real_Monthly|2017;07|Moray              |0.018     |1060     |57619      |0.018396709      |-2.20%            |
|Real_Monthly|2017;07|Perth & Kinross    |0.012     |1120     |91154      |0.012286899      |-2.39%            |
|Real_Monthly|2017;07|Scottish Borders   |0.016     |1125     |67353      |0.016703042      |-4.39%            |
|Real_Monthly|2017;07|Shetland Islands   |0.008     |110      |13333      |0.008250206      |-3.13%            |
|Real_Monthly|2017;07|West Dunbartonshire|0.035     |2035     |56410      |0.036075164      |-3.07%            |
|Real_Monthly|2017;07|West Lothian       |0.018     |2130     |115263     |0.018479477      |-2.66%            |
|Real_Monthly|2017;08|Aberdeen City      |0.022     |3535     |156136     |0.022640519      |-2.91%            |
|Real_Monthly|2017;08|Aberdeenshire      |0.014     |2290     |158214     |0.014474067      |-3.39%            |
|Real_Monthly|2017;08|Argyll & Bute      |0.016     |850      |50833      |0.016721421      |-4.51%            |
|Real_Monthly|2017;08|East Dunbartonshire|0.017     |1105     |63333      |0.01744746       |-2.63%            |
|Real_Monthly|2017;08|Edinburgh City     |0.014     |4920     |359286     |0.013693826      |2.19%             |
|Real_Monthly|2017;08|Eilean Siar        |0.017     |275      |15526      |0.017712225      |-4.19%            |
|Real_Monthly|2017;08|Falkirk            |0.023     |2390     |101346     |0.023582578      |-2.53%            |
|Real_Monthly|2017;08|Scottish Borders   |0.016     |1110     |67353      |0.016480335      |-3.00%            |
|Real_Monthly|2017;08|West Dunbartonshire|0.035     |2025     |56410      |0.03589789       |-2.57%            |
|Real_Monthly|2017;09|Clackmannanshire   |0.031     |1020     |32195      |0.031681938      |-2.20%            |
|Real_Monthly|2017;09|East Dunbartonshire|0.017     |1100     |63333      |0.017368512      |-2.17%            |
|Real_Monthly|2017;09|East Renfrewshire  |0.012     |670      |57917      |0.011568279      |3.60%             |
|Real_Monthly|2017;09|Edinburgh City     |0.013     |4550     |359286     |0.012664006      |2.58%             |
|Real_Monthly|2017;09|Midlothian         |0.022     |1255     |55741      |0.022514845      |-2.34%            |
|Real_Monthly|2017;09|Moray              |0.016     |970      |57619      |0.016834725      |-5.22%            |
|Real_Monthly|2017;09|Orkney Islands     |0.007     |100      |13889      |0.007199942      |-2.86%            |
|Real_Monthly|2017;09|Renfrewshire       |0.026     |3010     |112759     |0.0266941        |-2.67%            |
|Real_Monthly|2017;09|Shetland Islands   |0.006     |85       |13333      |0.006375159      |-6.25%            |
|Real_Monthly|2017;09|South Ayrshire     |0.024     |1580     |67400      |0.023442136      |2.32%             |
|Real_Monthly|2017;09|South Lanarkshire  |0.021     |4345     |200714     |0.021647718      |-3.08%            |
|Real_Monthly|2017;09|West Dunbartonshire|0.033     |1915     |56410      |0.033947882      |-2.87%            |
|Real_Monthly|2017;10|Aberdeen City      |0.02      |3205     |156136     |0.020526976      |-2.63%            |
|Real_Monthly|2017;10|Aberdeenshire      |0.012     |2025     |158214     |0.01279912       |-6.66%            |
|Real_Monthly|2017;10|East Ayrshire      |0.031     |2385     |75375      |0.031641791      |-2.07%            |
|Real_Monthly|2017;10|East Renfrewshire  |0.011     |615      |57917      |0.010618644      |3.47%             |
|Real_Monthly|2017;10|Edinburgh City     |0.012     |4470     |359286     |0.012441342      |-3.68%            |
|Real_Monthly|2017;10|Falkirk            |0.021     |2190     |101346     |0.021609141      |-2.90%            |
|Real_Monthly|2017;10|Midlothian         |0.023     |1315     |55741      |0.023591252      |-2.57%            |
|Real_Monthly|2017;10|North Ayrshire     |0.037     |3110     |82111      |0.037875559      |-2.37%            |
|Real_Monthly|2017;10|Orkney Islands     |0.008     |105      |13889      |0.00755994       |5.50%             |
|Real_Monthly|2017;10|Perth & Kinross    |0.01      |965      |91154      |0.01058648       |-5.86%            |
|Real_Monthly|2017;10|Shetland Islands   |0.005     |75       |13333      |0.005625141      |-12.50%           |
|Real_Monthly|2017;10|West Dunbartonshire|0.032     |1865     |56410      |0.033061514      |-3.32%            |
|Real_Monthly|2017;10|West Lothian       |0.016     |1910     |115263     |0.016570799      |-3.57%            |
|Real_Monthly|2017;11|Aberdeenshire      |0.012     |1965     |158214     |0.012419887      |-3.50%            |
|Real_Monthly|2017;11|Argyll & Bute      |0.016     |850      |50833      |0.016721421      |-4.51%            |
|Real_Monthly|2017;11|Dumfries & Galloway|0.016     |1455     |87105      |0.016703978      |-4.40%            |
|Real_Monthly|2017;11|East Dunbartonshire|0.016     |1060     |63333      |0.01673693       |-4.61%            |
|Real_Monthly|2017;11|East Lothian       |0.026     |1715     |64310      |0.026667703      |-2.57%            |
|Real_Monthly|2017;11|Edinburgh City     |0.012     |4470     |359286     |0.012441342      |-3.68%            |
|Real_Monthly|2017;11|Glasgow City       |0.031     |13430    |445000     |0.030179775      |2.65%             |
|Real_Monthly|2017;11|Midlothian         |0.023     |1315     |55741      |0.023591252      |-2.57%            |
|Real_Monthly|2017;11|North Lanarkshire  |0.026     |5605     |221071     |0.025353846      |2.49%             |
|Real_Monthly|2017;11|Orkney Islands     |0.008     |115      |13889      |0.008279934      |-3.50%            |
|Real_Monthly|2017;11|Perth & Kinross    |0.011     |980      |91154      |0.010751037      |2.26%             |
|Real_Monthly|2017;11|Renfrewshire       |0.026     |3015     |112759     |0.026738442      |-2.84%            |
|Real_Monthly|2017;11|Shetland Islands   |0.006     |85       |13333      |0.006375159      |-6.25%            |
|Real_Monthly|2017;11|West Dunbartonshire|0.033     |1920     |56410      |0.034036518      |-3.14%            |
|Real_Monthly|2017;12|Aberdeenshire      |0.012     |2045     |158214     |0.012925531      |-7.71%            |
|Real_Monthly|2017;12|Argyll & Bute      |0.017     |900      |50833      |0.017705034      |-4.15%            |
|Real_Monthly|2017;12|East Dunbartonshire|0.016     |1070     |63333      |0.016894826      |-5.59%            |
|Real_Monthly|2017;12|Edinburgh City     |0.013     |4480     |359286     |0.012469175      |4.08%             |
|Real_Monthly|2017;12|Eilean Siar        |0.017     |270      |15526      |0.017390184      |-2.30%            |
|Real_Monthly|2017;12|Falkirk            |0.021     |2190     |101346     |0.021609141      |-2.90%            |
|Real_Monthly|2017;12|Fife               |0.024     |5635     |229194     |0.024586158      |-2.44%            |
|Real_Monthly|2017;12|Glasgow City       |0.031     |13455    |445000     |0.030235955      |2.46%             |
|Real_Monthly|2017;12|Highland           |0.023     |3380     |143846     |0.023497351      |-2.16%            |
|Real_Monthly|2017;12|Moray              |0.017     |1010     |57619      |0.01752894       |-3.11%            |
|Real_Monthly|2017;12|Orkney Islands     |0.009     |115      |13889      |0.008279934      |8.00%             |
|Real_Monthly|2017;12|West Dunbartonshire|0.034     |1970     |56410      |0.034922886      |-2.71%            |
|Real_Monthly|2018;01|Aberdeenshire      |0.013     |2150     |158214     |0.013589189      |-4.53%            |
|Real_Monthly|2018;01|East Renfrewshire  |0.012     |670      |57917      |0.011568279      |3.60%             |
|Real_Monthly|2018;01|Fife               |0.025     |5905     |229194     |0.0257642        |-3.06%            |
|Real_Monthly|2018;01|Highland           |0.024     |3525     |143846     |0.024505374      |-2.11%            |
|Real_Monthly|2018;01|Moray              |0.019     |1140     |57619      |0.01978514       |-4.13%            |
|Real_Monthly|2018;01|Orkney Islands     |0.009     |120      |13889      |0.008639931      |4.00%             |
|Real_Monthly|2018;01|Perth & Kinross    |0.012     |1065     |91154      |0.011683525      |2.64%             |
|Real_Monthly|2018;01|Shetland Islands   |0.007     |105      |13333      |0.007875197      |-12.50%           |
|Real_Monthly|2018;01|South Ayrshire     |0.025     |1640     |67400      |0.024332344      |2.67%             |
|Real_Monthly|2018;01|West Dunbartonshire|0.036     |2080     |56410      |0.036872895      |-2.42%            |
|Real_Monthly|2018;02|Argyll & Bute      |0.018     |940      |50833      |0.018491925      |-2.73%            |
|Real_Monthly|2018;02|Dumfries & Galloway|0.019     |1700     |87105      |0.019516675      |-2.72%            |
|Real_Monthly|2018;02|East Lothian       |0.028     |1850     |64310      |0.02876691       |-2.74%            |
|Real_Monthly|2018;02|Orkney Islands     |0.01      |130      |13889      |0.009359925      |6.40%             |
|Real_Monthly|2018;02|Perth & Kinross    |0.012     |1130     |91154      |0.012396604      |-3.31%            |
|Real_Monthly|2018;02|Renfrewshire       |0.028     |3245     |112759     |0.028778191      |-2.78%            |
|Real_Monthly|2018;02|Shetland Islands   |0.008     |110      |13333      |0.008250206      |-3.13%            |
|Real_Monthly|2018;02|Stirling           |0.022     |1310     |61304      |0.021368916      |2.87%             |
|Real_Monthly|2018;04|Aberdeen City      |0.022     |3430     |160714     |0.02134226       |2.99%             |
|Real_Monthly|2018;04|Argyll & Bute      |0.017     |890      |50926      |0.017476338      |-2.80%            |
|Real_Monthly|2018;04|East Renfrewshire  |0.012     |700      |55667      |0.012574775      |-4.79%            |
|Real_Monthly|2018;04|Edinburgh City     |0.014     |5040     |368333     |0.01368327       |2.26%             |
|Real_Monthly|2018;04|Eilean Siar        |0.018     |280      |15217      |0.018400473      |-2.22%            |
|Real_Monthly|2018;04|Fife               |0.034     |7790     |233974     |0.033294298      |2.08%             |
|Real_Monthly|2018;04|Moray              |0.019     |1145     |58846      |0.019457567      |-2.41%            |
|Real_Monthly|2018;04|Perth & Kinross    |0.013     |1165     |92632      |0.012576647      |3.26%             |
|Real_Monthly|2018;04|Renfrewshire       |0.029     |3270     |115938     |0.02820473       |2.74%             |
|Real_Monthly|2018;04|Shetland Islands   |0.009     |130      |13571      |0.00957925       |-6.44%            |
|Real_Monthly|2018;04|West Dunbartonshire|0.038     |2175     |55952      |0.038872605      |-2.30%            |
|Real_Monthly|2018;05|Aberdeen City      |0.021     |3295     |160714     |0.020502259      |2.37%             |
|Real_Monthly|2018;05|East Dunbartonshire|0.017     |1140     |63684      |0.017900886      |-5.30%            |
|Real_Monthly|2018;05|East Renfrewshire  |0.012     |685      |55667      |0.012305316      |-2.54%            |
|Real_Monthly|2018;05|Edinburgh City     |0.014     |4940     |368333     |0.013411777      |4.20%             |
|Real_Monthly|2018;05|Glasgow City       |0.032     |13935    |446944     |0.031178403      |2.57%             |
|Real_Monthly|2018;05|Orkney Islands     |0.008     |100      |13929      |0.007179266      |10.26%            |
|Real_Monthly|2018;05|Perth & Kinross    |0.012     |1135     |92632      |0.012252785      |-2.11%            |
|Real_Monthly|2018;05|Scottish Borders   |0.016     |1110     |66923      |0.016586226      |-3.66%            |
|Real_Monthly|2018;05|Shetland Islands   |0.008     |120      |13571      |0.008842384      |-10.53%           |
|Real_Monthly|2018;05|Stirling           |0.023     |1420     |59423      |0.023896471      |-3.90%            |
|Real_Monthly|2018;05|West Dunbartonshire|0.038     |2175     |55952      |0.038872605      |-2.30%            |
|Real_Monthly|2018;06|Aberdeenshire      |0.013     |2050     |163438     |0.012542983      |3.52%             |
|Real_Monthly|2018;06|Argyll & Bute      |0.016     |840      |50926      |0.016494521      |-3.09%            |
|Real_Monthly|2018;06|East Dunbartonshire|0.017     |1130     |63684      |0.01774386       |-4.38%            |
|Real_Monthly|2018;06|East Renfrewshire  |0.012     |690      |55667      |0.012395135      |-3.29%            |
|Real_Monthly|2018;06|Moray              |0.017     |1030     |58846      |0.017503314      |-2.96%            |
|Real_Monthly|2018;06|Orkney Islands     |0.007     |100      |13929      |0.007179266      |-2.56%            |
|Real_Monthly|2018;06|Perth & Kinross    |0.012     |1075     |92632      |0.011605061      |3.29%             |
|Real_Monthly|2018;06|Shetland Islands   |0.009     |125      |13571      |0.009210817      |-2.34%            |
|Real_Monthly|2018;06|Stirling           |0.023     |1405     |59423      |0.023644044      |-2.80%            |
|Real_Monthly|2018;06|West Dunbartonshire|0.037     |2130     |55952      |0.038068344      |-2.89%            |
|Real_Monthly|2018;06|West Lothian       |0.018     |2080     |118393     |0.017568606      |2.40%             |
|Real_Monthly|2018;07|Aberdeenshire      |0.012     |2015     |163438     |0.012328834      |-2.74%            |
|Real_Monthly|2018;07|Argyll & Bute      |0.016     |835      |50926      |0.01639634       |-2.48%            |
|Real_Monthly|2018;07|Dumfries & Galloway|0.02      |1705     |88000      |0.019375         |3.13%             |
|Real_Monthly|2018;07|East Renfrewshire  |0.012     |700      |55667      |0.012574775      |-4.79%            |
|Real_Monthly|2018;07|Highland           |0.024     |3520     |142222     |0.024750039      |-3.13%            |
|Real_Monthly|2018;07|Moray              |0.017     |1030     |58846      |0.017503314      |-2.96%            |
|Real_Monthly|2018;07|Renfrewshire       |0.028     |3160     |115938     |0.027255947      |2.66%             |
|Real_Monthly|2018;07|Shetland Islands   |0.009     |130      |13571      |0.00957925       |-6.44%            |
|Real_Monthly|2018;07|West Dunbartonshire|0.036     |2065     |55952      |0.036906634      |-2.52%            |
|Real_Monthly|2018;07|West Lothian       |0.019     |2190     |118393     |0.018497715      |2.64%             |
|Real_Monthly|2018;08|Argyll & Bute      |0.016     |840      |50926      |0.016494521      |-3.09%            |
|Real_Monthly|2018;08|Dumfries & Galloway|0.021     |1800     |88000      |0.020454545      |2.60%             |
|Real_Monthly|2018;08|East Renfrewshire  |0.012     |700      |55667      |0.012574775      |-4.79%            |
|Real_Monthly|2018;08|Edinburgh City     |0.013     |4670     |368333     |0.012678745      |2.47%             |
|Real_Monthly|2018;08|Eilean Siar        |0.015     |235      |15217      |0.015443254      |-2.96%            |
|Real_Monthly|2018;08|Orkney Islands     |0.006     |80       |13929      |0.005743413      |4.28%             |
|Real_Monthly|2018;08|Shetland Islands   |0.009     |135      |13571      |0.009947683      |-10.53%           |
|Real_Monthly|2018;08|West Dunbartonshire|0.036     |2060     |55952      |0.036817272      |-2.27%            |
|Real_Monthly|2018;08|West Lothian       |0.02      |2295     |118393     |0.019384592      |3.08%             |
|Real_Monthly|2018;09|Aberdeenshire      |0.012     |2015     |163438     |0.012328834      |-2.74%            |
|Real_Monthly|2018;09|East Dunbartonshire|0.017     |1120     |63684      |0.017586835      |-3.45%            |
|Real_Monthly|2018;09|East Renfrewshire  |0.011     |645      |55667      |0.011586757      |-5.33%            |
|Real_Monthly|2018;09|Eilean Siar        |0.014     |225      |15217      |0.014786094      |-5.61%            |
|Real_Monthly|2018;09|Midlothian         |0.024     |1380     |56154      |0.024575275      |-2.40%            |
|Real_Monthly|2018;09|Orkney Islands     |0.005     |65       |13929      |0.004666523      |6.67%             |
|Real_Monthly|2018;09|Renfrewshire       |0.025     |2835     |115938     |0.024452725      |2.19%             |
|Real_Monthly|2018;09|Shetland Islands   |0.009     |125      |13571      |0.009210817      |-2.34%            |
|Real_Monthly|2018;09|South Ayrshire     |0.034     |2295     |66000      |0.034772727      |-2.27%            |
|Real_Monthly|2018;09|Stirling           |0.023     |1420     |59423      |0.023896471      |-3.90%            |
|Real_Monthly|2018;09|West Dunbartonshire|0.034     |1960     |55952      |0.035030026      |-3.03%            |
|Real_Monthly|2018;09|West Lothian       |0.021     |2405     |118393     |0.020313701      |3.27%             |
|Real_Monthly|2018;10|East Dunbartonshire|0.017     |1120     |63684      |0.017586835      |-3.45%            |
|Real_Monthly|2018;10|East Renfrewshire  |0.011     |630      |55667      |0.011317298      |-2.88%            |
|Real_Monthly|2018;10|Eilean Siar        |0.015     |240      |15217      |0.015771834      |-5.15%            |
|Real_Monthly|2018;10|Highland           |0.023     |3385     |142222     |0.023800818      |-3.48%            |
|Real_Monthly|2018;10|Moray              |0.019     |1145     |58846      |0.019457567      |-2.41%            |
|Real_Monthly|2018;10|Orkney Islands     |0.006     |75       |13929      |0.00538445       |10.26%            |
|Real_Monthly|2018;10|Perth & Kinross    |0.014     |1255     |92632      |0.013548234      |3.23%             |
|Real_Monthly|2018;10|Renfrewshire       |0.025     |2805     |115938     |0.024193966      |3.22%             |
|Real_Monthly|2018;10|Scottish Borders   |0.018     |1260     |66923      |0.018827608      |-4.60%            |
|Real_Monthly|2018;10|Shetland Islands   |0.008     |120      |13571      |0.008842384      |-10.53%           |
|Real_Monthly|2018;11|Aberdeen City      |0.018     |2790     |160714     |0.017360031      |3.56%             |
|Real_Monthly|2018;11|East Dunbartonshire|0.017     |1110     |63684      |0.01742981       |-2.53%            |
|Real_Monthly|2018;11|Perth & Kinross    |0.015     |1335     |92632      |0.014411866      |3.92%             |
|Real_Monthly|2018;11|Scottish Borders   |0.02      |1370     |66923      |0.020471288      |-2.36%            |
|Real_Monthly|2018;11|Shetland Islands   |0.009     |125      |13571      |0.009210817      |-2.34%            |
|Real_Monthly|2018;11|Stirling           |0.023     |1410     |59423      |0.023728186      |-3.17%            |
|Real_Monthly|2018;11|West Dunbartonshire|0.034     |1945     |55952      |0.034761939      |-2.24%            |
|Real_Monthly|2018;12|Aberdeen City      |0.018     |2760     |160714     |0.017173364      |4.59%             |
|Real_Monthly|2018;12|Aberdeenshire      |0.013     |2180     |163438     |0.013338391      |-2.60%            |
|Real_Monthly|2018;12|Dumfries & Galloway|0.026     |2230     |88000      |0.025340909      |2.53%             |
|Real_Monthly|2018;12|East Dunbartonshire|0.017     |1105     |63684      |0.017351297      |-2.07%            |
|Real_Monthly|2018;12|East Renfrewshire  |0.012     |710      |55667      |0.012754415      |-6.29%            |
|Real_Monthly|2018;12|Eilean Siar        |0.018     |290      |15217      |0.019057633      |-5.88%            |
|Real_Monthly|2018;12|Highland           |0.024     |3510     |142222     |0.024679726      |-2.83%            |
|Real_Monthly|2018;12|Orkney Islands     |0.01      |135      |13929      |0.009692009      |3.08%             |
|Real_Monthly|2018;12|Perth & Kinross    |0.016     |1445     |92632      |0.015599361      |2.50%             |
|Real_Monthly|2018;12|Shetland Islands   |0.01      |150      |13571      |0.011052981      |-10.53%           |
|Real_Monthly|2019;01|Aberdeenshire      |0.014     |2335     |163438     |0.014286763      |-2.05%            |
|Real_Monthly|2019;01|East Lothian       |0.027     |1800     |65172      |0.027619223      |-2.29%            |
|Real_Monthly|2019;01|East Renfrewshire  |0.013     |745      |55667      |0.013383153      |-2.95%            |
|Real_Monthly|2019;01|Orkney Islands     |0.012     |155      |13929      |0.011127863      |7.27%             |
|Real_Monthly|2019;01|Shetland Islands   |0.011     |155      |13571      |0.011421413      |-3.83%            |
|Real_Monthly|2019;01|Stirling           |0.024     |1460     |59423      |0.024569611      |-2.37%            |
|Real_Monthly|2019;02|Aberdeen City      |0.021     |3270     |160714     |0.020346703      |3.11%             |
|Real_Monthly|2019;02|Midlothian         |0.025     |1440     |56154      |0.025643765      |-2.58%            |
|Real_Monthly|2019;02|Orkney Islands     |0.014     |185      |13929      |0.013281643      |5.13%             |
|Real_Monthly|2019;02|Perth & Kinross    |0.019     |1700     |92632      |0.018352189      |3.41%             |
|Real_Monthly|2019;02|Shetland Islands   |0.013     |185      |13571      |0.013632009      |-4.86%            |
|Real_Monthly|2019;04|East Renfrewshire  |0.015     |835      |57353      |0.014558959      |2.94%             |
|Real_Monthly|2019;04|Highland           |0.026     |3725     |146400     |0.025443989      |2.14%             |
|Real_Monthly|2019;04|Shetland Islands   |0.015     |205      |13947      |0.014698501      |2.01%             |
|Real_Monthly|2019;05|Highland           |0.025     |3535     |146400     |0.024146175      |3.42%             |
|Real_Monthly|2019;05|Midlothian         |0.025     |1400     |57500      |0.024347826      |2.61%             |
|Real_Monthly|2019;05|Moray              |0.025     |1490     |58333      |0.025543003      |-2.17%            |
|Real_Monthly|2019;05|Perth & Kinross    |0.019     |1725     |93000      |0.018548387      |2.38%             |
|Real_Monthly|2019;05|Shetland Islands   |0.014     |200      |13947      |0.014340001      |-2.43%            |
|Real_Monthly|2019;05|Stirling           |0.025     |1485     |61200      |0.024264706      |2.94%             |
|Real_Monthly|2019;05|West Lothian       |0.028     |3225     |118966     |0.027108586      |3.18%             |
|Real_Monthly|2019;06|Aberdeen City      |0.022     |3470     |154259     |0.022494636      |-2.25%            |
|Real_Monthly|2019;06|Aberdeenshire      |0.017     |2665     |164167     |0.01623347       |4.51%             |
|Real_Monthly|2019;06|East Renfrewshire  |0.016     |890      |57353      |0.015517933      |3.01%             |
|Real_Monthly|2019;06|Highland           |0.024     |3440     |146400     |0.023497268      |2.09%             |
|Real_Monthly|2019;06|Shetland Islands   |0.014     |200      |13947      |0.014340001      |-2.43%            |
|Real_Monthly|2019;07|Aberdeen City      |0.023     |3650     |154259     |0.023661504      |-2.88%            |
|Real_Monthly|2019;07|Highland           |0.024     |3425     |146400     |0.023394809      |2.52%             |
|Real_Monthly|2019;07|Moray              |0.025     |1495     |58333      |0.025628718      |-2.51%            |
|Real_Monthly|2019;07|Perth & Kinross    |0.02      |1790     |93000      |0.019247312      |3.76%             |
|Real_Monthly|2019;08|Aberdeen City      |0.024     |3830     |154259     |0.024828373      |-3.45%            |
|Real_Monthly|2019;08|Aberdeenshire      |0.018     |2820     |164167     |0.01717763       |4.57%             |
|Real_Monthly|2019;08|Angus              |0.033     |2255     |70000      |0.032214286      |2.38%             |
|Real_Monthly|2019;08|East Dunbartonshire|0.02      |1270     |65000      |0.019538462      |2.31%             |
|Real_Monthly|2019;08|Edinburgh City     |0.017     |6375     |364250     |0.017501716      |-2.95%            |
|Real_Monthly|2019;08|Falkirk            |0.032     |3310     |100758     |0.032850989      |-2.66%            |
|Real_Monthly|2019;08|Moray              |0.025     |1495     |58333      |0.025628718      |-2.51%            |
|Real_Monthly|2019;08|Orkney Islands     |0.012     |165      |13333      |0.012375309      |-3.13%            |
|Real_Monthly|2019;09|Aberdeen City      |0.024     |3815     |154259     |0.024731134      |-3.05%            |
|Real_Monthly|2019;09|Aberdeenshire      |0.017     |2715     |164167     |0.016538037      |2.72%             |
|Real_Monthly|2019;09|Dumfries & Galloway|0.031     |2670     |88182      |0.030278288      |2.33%             |
|Real_Monthly|2019;09|East Dunbartonshire|0.018     |1200     |65000      |0.018461538      |-2.56%            |
|Real_Monthly|2019;09|East Lothian       |0.026     |1685     |66154      |0.025470871      |2.04%             |
|Real_Monthly|2019;09|Edinburgh City     |0.017     |6380     |364250     |0.017515443      |-3.03%            |
|Real_Monthly|2019;09|Highland           |0.023     |3240     |146400     |0.022131148      |3.78%             |
|Real_Monthly|2019;09|Midlothian         |0.024     |1350     |57500      |0.023478261      |2.17%             |
|Real_Monthly|2019;09|Stirling           |0.024     |1430     |61200      |0.023366013      |2.64%             |
|Real_Monthly|2019;09|West Lothian       |0.028     |3225     |118966     |0.027108586      |3.18%             |
|Real_Monthly|2019;10|Aberdeen City      |0.024     |3820     |154259     |0.024763547      |-3.18%            |
|Real_Monthly|2019;10|East Lothian       |0.026     |1675     |66154      |0.025319709      |2.62%             |
|Real_Monthly|2019;10|East Renfrewshire  |0.017     |945      |57353      |0.016476906      |3.08%             |
|Real_Monthly|2019;10|Orkney Islands     |0.014     |180      |13333      |0.013500338      |3.57%             |
|Real_Monthly|2019;10|Shetland Islands   |0.017     |230      |13947      |0.016491002      |2.99%             |
|Real_Monthly|2019;11|Aberdeen City      |0.025     |3965     |154259     |0.025703525      |-2.81%            |
|Real_Monthly|2019;11|Aberdeenshire      |0.018     |2825     |164167     |0.017208087      |4.40%             |
|Real_Monthly|2019;11|Argyll & Bute      |0.026     |1340     |50333      |0.026622693      |-2.39%            |
|Real_Monthly|2019;11|East Lothian       |0.027     |1740     |66154      |0.026302264      |2.58%             |
|Real_Monthly|2019;11|Midlothian         |0.025     |1400     |57500      |0.024347826      |2.61%             |
|Real_Monthly|2019;11|Moray              |0.024     |1435     |58333      |0.024600141      |-2.50%            |
|Real_Monthly|2019;11|Orkney Islands     |0.013     |180      |13333      |0.013500338      |-3.85%            |
|Real_Monthly|2019;11|Perth & Kinross    |0.02      |1820     |93000      |0.019569892      |2.15%             |
|Real_Monthly|2019;12|East Lothian       |0.027     |1750     |66154      |0.026453427      |2.02%             |
|Real_Monthly|2019;12|Falkirk            |0.032     |3300     |100758     |0.032751742      |-2.35%            |
|Real_Monthly|2019;12|Highland           |0.025     |3540     |146400     |0.024180328      |3.28%             |
|Real_Monthly|2019;12|Perth & Kinross    |0.02      |1810     |93000      |0.019462366      |2.69%             |
|Real_Monthly|2019;12|Shetland Islands   |0.017     |245      |13947      |0.017566502      |-3.33%            |
|Real_Monthly|2020;01|Angus              |0.03      |2045     |70000      |0.029214286      |2.62%             |
|Real_Monthly|2020;01|Dumfries & Galloway|0.033     |2830     |88182      |0.032092717      |2.75%             |
|Real_Monthly|2020;01|East Lothian       |0.027     |1750     |66154      |0.026453427      |2.02%             |
|Real_Monthly|2020;01|Highland           |0.026     |3705     |146400     |0.025307377      |2.66%             |
|Real_Monthly|2020;01|Inverclyde         |0.046     |2200     |49222      |0.044695461      |2.84%             |
|Real_Monthly|2020;01|North Lanarkshire  |0.037     |8030     |222297     |0.036122845      |2.37%             |
|Real_Monthly|2020;01|Perth & Kinross    |0.02      |1815     |93000      |0.019516129      |2.42%             |
|Real_Monthly|2020;01|Shetland Islands   |0.017     |230      |13947      |0.016491002      |2.99%             |
|Real_Monthly|2020;01|Stirling           |0.025     |1495     |61200      |0.024428105      |2.29%             |
|Real_Monthly|2020;01|West Lothian       |0.028     |3260     |118966     |0.027402787      |2.13%             |
|Real_Monthly|2020;02|Aberdeen City      |0.026     |4150     |154259     |0.026902806      |-3.47%            |
|Real_Monthly|2020;02|Aberdeenshire      |0.019     |2975     |164167     |0.018121791      |4.62%             |
|Real_Monthly|2020;02|Angus              |0.03      |2040     |70000      |0.029142857      |2.86%             |
|Real_Monthly|2020;02|East Renfrewshire  |0.017     |950      |57353      |0.016564086      |2.56%             |
|Real_Monthly|2020;02|Edinburgh City     |0.019     |7105     |364250     |0.019505834      |-2.66%            |
|Real_Monthly|2020;02|Falkirk            |0.032     |3300     |100758     |0.032751742      |-2.35%            |
|Real_Monthly|2020;02|Highland           |0.026     |3715     |146400     |0.025375683      |2.40%             |
|Real_Monthly|2020;02|Inverclyde         |0.047     |2255     |49222      |0.045812848      |2.53%             |
|Real_Monthly|2020;02|Moray              |0.026     |1550     |58333      |0.02657158       |-2.20%            |
|Real_Monthly|2020;02|North Lanarkshire  |0.038     |8230     |222297     |0.037022542      |2.57%             |
|Real_Monthly|2020;02|Orkney Islands     |0.014     |195      |13333      |0.014625366      |-4.47%            |
|Real_Monthly|2020;02|Scottish Borders   |0.028     |1860     |67857      |0.027410584      |2.11%             |
|Real_Monthly|2020;02|Stirling           |0.026     |1540     |61200      |0.025163399      |3.22%             |
|Real_Monthly|2020;03|Dumfries & Galloway|0.034     |2910     |88182      |0.032999932      |2.94%             |
|Real_Monthly|2020;03|Highland           |0.026     |3660     |146400     |0.025            |3.85%             |
|Real_Monthly|2020;03|Inverclyde         |0.046     |2215     |49222      |0.045000203      |2.17%             |
|Real_Monthly|2020;03|North Lanarkshire  |0.038     |8225     |222297     |0.037000049      |2.63%             |
|Real_Monthly|2020;04|East Dunbartonshire|0.037     |2360     |65513      |0.036023385      |2.64%             |
|Real_Monthly|2020;04|East Renfrewshire  |0.033     |1855     |57432      |0.032299067      |2.12%             |
|Real_Monthly|2020;04|Orkney Islands     |0.028     |380      |13276      |0.028623079      |-2.23%            |
|Real_Monthly|2020;06|East Dunbartonshire|0.042     |2690     |65513      |0.041060553      |2.24%             |
|Real_Monthly|2020;06|Orkney Islands     |0.028     |380      |13276      |0.028623079      |-2.23%            |
|Real_Monthly|2020;07|East Dunbartonshire|0.045     |2885     |65513      |0.044037061      |2.14%             |
|Real_Monthly|2020;08|Orkney Islands     |0.031     |420      |13276      |0.031636035      |-2.05%            |
|Real_Monthly|2020;09|Perth & Kinross    |0.049     |4435     |92667      |0.04785954       |2.33%             |
|Real_Monthly|2020;10|Orkney Islands     |0.027     |370      |13276      |0.02786984       |-3.22%            |
|Real_Monthly|2020;10|Perth & Kinross    |0.046     |4160     |92667      |0.044891925      |2.41%             |
|Real_Monthly|2021;01|Midlothian         |0.05      |2920     |57222      |0.051029324      |-2.06%            |
|Real_Monthly|2021;01|Stirling           |0.045     |2660     |60667      |0.043845913      |2.56%             |
|Real_Monthly|2021;01|West Dunbartonshire|0.082     |4525     |56438      |0.080176477      |2.22%             |
|Real_Monthly|2021;02|Dundee City        |0.072     |7015     |99710      |0.070354027      |2.29%             |
|Real_Monthly|2021;02|East Dunbartonshire|0.04      |2560     |65513      |0.039076214      |2.31%             |
|Real_Monthly|2021;02|Inverclyde         |0.063     |2995     |48871      |0.061283788      |2.72%             |
|Real_Monthly|2021;02|Midlothian         |0.052     |3070     |57222      |0.053650694      |-3.17%            |
|Real_Monthly|2021;03|East Dunbartonshire|0.04      |2555     |65513      |0.038999893      |2.50%             |
|Real_Monthly|2021;03|Stirling           |0.046     |2730     |60667      |0.044999753      |2.17%             |
|Real_Monthly|2021;06|Orkney Islands     |0.021     |290      |13447      |0.021566149      |-2.70%            |
|Real_Monthly|2021;08|Shetland Islands   |0.025     |340      |13912      |0.024439333      |2.24%             |
|Real_Monthly|2021;10|East Renfrewshire  |0.023     |1340     |57033      |0.023495169      |-2.15%            |
|Real_Monthly|2021;11|Shetland Islands   |0.022     |315      |13912      |0.022642323      |-2.92%            |
|Real_Monthly|2021;12|Orkney Islands     |0.019     |250      |13447      |0.018591507      |2.15%             |
|Real_Monthly|2021;12|Shetland Islands   |0.022     |315      |13912      |0.022642323      |-2.92%            |
|Real_Monthly|2022;01|East Dunbartonshire|0.024     |1575     |64307      |0.02449189       |-2.05%            |
|Real_Monthly|2022;01|Orkney Islands     |0.019     |250      |13447      |0.018591507      |2.15%             |
|Real_Monthly|2022;03|East Renfrewshire  |0.019     |1110     |57033      |0.019462416      |-2.43%            |
|Real_Monthly|2022;04|East Renfrewshire  |0.018     |1050     |57033      |0.018410394      |-2.28%            |
|Real_Monthly|2022;05|East Renfrewshire  |0.017     |995      |57033      |0.01744604       |-2.62%            |
|Real_Monthly|2022;05|Shetland Islands   |0.021     |285      |13912      |0.020485911      |2.45%             |
|Real_Monthly|2022;06|East Renfrewshire  |0.017     |995      |57033      |0.01744604       |-2.62%            |
|Real_Monthly|2022;07|East Renfrewshire  |0.017     |990      |57033      |0.017358371      |-2.11%            |
|Real_Monthly|2022;07|Highland           |0.022     |3255     |144706     |0.022493884      |-2.24%            |
|Real_Monthly|2022;09|East Dunbartonshire|0.02      |1255     |64307      |0.01951576       |2.42%             |
|Real_Monthly|2022;09|Shetland Islands   |0.017     |230      |13912      |0.01653249       |2.75%             |
|Real_Monthly|2022;10|East Lothian       |0.022     |1440     |66893      |0.021526916      |2.15%             |
|Real_Monthly|2022;10|Midlothian         |0.022     |1260     |58532      |0.021526686      |2.15%             |
|Real_Monthly|2022;10|Perth & Kinross    |0.022     |1995     |92594      |0.021545673      |2.07%             |
|Real_Monthly|2022;10|Shetland Islands   |0.018     |245      |13912      |0.017610696      |2.16%             |
|Real_Monthly|2022;11|Aberdeenshire      |0.018     |2970     |160495     |0.018505249      |-2.81%            |
|Real_Monthly|2022;11|East Renfrewshire  |0.017     |950      |57033      |0.016657023      |2.02%             |
|Real_Monthly|2022;11|Orkney Islands     |0.015     |210      |13447      |0.015616866      |-4.11%            |
|Real_Monthly|2022;11|Perth & Kinross    |0.021     |1985     |92594      |0.021437674      |-2.08%            |
|Real_Monthly|2022;12|Aberdeenshire      |0.019     |2985     |160495     |0.01859871       |2.11%             |
|Real_Monthly|2022;12|East Dunbartonshire|0.019     |1250     |64307      |0.019438008      |-2.31%            |
|Real_Monthly|2023;01|East Dunbartonshire|0.018     |1190     |64130      |0.018556058      |-3.09%            |
|Real_Monthly|2023;01|East Renfrewshire  |0.017     |970      |55500      |0.017477477      |-2.81%            |
|Real_Monthly|2023;01|Edinburgh City     |0.024     |8645     |371852     |0.023248497      |3.13%             |
|Real_Monthly|2023;01|Midlothian         |0.023     |1330     |56667      |0.02347045       |-2.05%            |
|Real_Monthly|2023;01|Moray              |0.024     |1430     |58000      |0.024655172      |-2.73%            |
|Real_Monthly|2023;01|Perth & Kinross    |0.023     |2160     |91481      |0.02361146       |-2.66%            |
|Real_Monthly|2023;01|Shetland Islands   |0.017     |240      |13636      |0.017600469      |-3.53%            |
|Real_Monthly|2023;01|Stirling           |0.025     |1475     |60400      |0.02442053       |2.32%             |
|Real_Monthly|2023;02|Aberdeenshire      |0.02      |3145     |160495     |0.019595626      |2.02%             |
|Real_Monthly|2023;02|East Renfrewshire  |0.017     |995      |57033      |0.01744604       |-2.62%            |
|Real_Monthly|2023;02|Moray              |0.023     |1385     |58935      |0.023500467      |-2.18%            |
|Real_Monthly|2023;03|Angus              |0.031     |2070     |69017      |0.029992611      |3.25%             |
|Real_Monthly|2023;03|Clackmannanshire   |0.039     |1220     |31945      |0.03819064       |2.08%             |
|Real_Monthly|2023;03|Dumfries & Galloway|0.029     |2585     |86346      |0.029937693      |-3.23%            |
|Real_Monthly|2023;03|East Dunbartonshire|0.019     |1275     |64307      |0.019826768      |-4.35%            |
|Real_Monthly|2023;03|East Lothian       |0.024     |1570     |66893      |0.023470318      |2.21%             |
|Real_Monthly|2023;03|Eilean Siar        |0.021     |315      |15508      |0.020312097      |3.28%             |
|Real_Monthly|2023;03|Glasgow City       |0.05      |21910    |448645     |0.048835939      |2.33%             |
|Real_Monthly|2023;03|Midlothian         |0.023     |1375     |58532      |0.023491423      |-2.14%            |
|Real_Monthly|2023;03|South Ayrshire     |0.037     |2490     |65844      |0.037816658      |-2.21%            |
|Real_Monthly|2023;03|Stirling           |0.024     |1490     |59731      |0.024945171      |-3.94%            |
|Real_Monthly|2023;05|East Dunbartonshire|0.019     |1255     |64307      |0.01951576       |-2.71%            |
|Real_Monthly|2023;05|Eilean Siar        |0.018     |285      |15508      |0.018377612      |-2.10%            |
|Real_Monthly|2023;05|Highland           |0.023     |3400     |144706     |0.023495916      |-2.16%            |
|Real_Monthly|2023;05|Orkney Islands     |0.016     |220      |13447      |0.016360527      |-2.25%            |
|Real_Monthly|2023;06|Edinburgh City     |0.023     |8605     |366367     |0.023487377      |-2.12%            |
|Real_Monthly|2023;06|Moray              |0.022     |1325     |58935      |0.022482396      |-2.19%            |
|Real_Monthly|2023;06|Orkney Islands     |0.016     |220      |13447      |0.016360527      |-2.25%            |
|Real_Monthly|2023;07|Clackmannanshire   |0.024     |8725     |31945      |0.273125685      |-1038.02%         |
|Real_Monthly|2023;07|Dumfries & Galloway|0.037     |1195     |86346      |0.013839668      |62.60%            |
|Real_Monthly|2023;07|Dundee City        |0.029     |2540     |97773      |0.025978542      |10.42%            |
|Real_Monthly|2023;07|East Ayrshire      |0.045     |4435     |75654      |0.058622148      |-30.27%           |
|Real_Monthly|2023;07|East Dunbartonshire|0.042     |3175     |64307      |0.049372541      |-17.55%           |
|Real_Monthly|2023;07|East Lothian       |0.02      |1275     |66893      |0.01906029       |4.70%             |
|Real_Monthly|2023;07|East Renfrewshire  |0.023     |1555     |57033      |0.027264917      |-18.54%           |
|Real_Monthly|2023;07|Edinburgh City     |0.018     |1015     |366367     |0.002770446      |84.61%            |
|Real_Monthly|2023;07|Eilean Siar        |0.03      |3010     |15508      |0.194093371      |-546.98%          |
|Real_Monthly|2023;07|Falkirk            |0.035     |8060     |102021     |0.079003342      |-125.72%          |
|Real_Monthly|2023;07|Fife               |0.048     |21630    |231635     |0.093379671      |-94.54%           |
|Real_Monthly|2023;07|Glasgow City       |0.022     |3220     |448645     |0.007177167      |67.38%            |
|Real_Monthly|2023;07|Highland           |0.04      |1890     |144706     |0.013060965      |67.35%            |
|Real_Monthly|2023;07|Inverclyde         |0.024     |1405     |47782      |0.029404378      |-22.52%           |
|Real_Monthly|2023;07|Moray              |0.019     |290      |58935      |0.004920675      |74.10%            |
|Real_Monthly|2023;07|Orkney Islands     |0.015     |195      |13447      |0.014501376      |3.32%             |
|Real_Monthly|2023;07|Shetland Islands   |0.016     |230      |13912      |0.01653249       |-3.33%            |
|Real_Monthly|2023;08|Clackmannanshire   |0.023     |8535     |31945      |0.267177962      |-1061.64%         |
|Real_Monthly|2023;08|Dumfries & Galloway|0.037     |1175     |86346      |0.013608042      |63.22%            |
|Real_Monthly|2023;08|Dundee City        |0.028     |2455     |97773      |0.025109181      |10.32%            |
|Real_Monthly|2023;08|East Ayrshire      |0.044     |4275     |75654      |0.056507257      |-28.43%           |
|Real_Monthly|2023;08|East Dunbartonshire|0.04      |3060     |64307      |0.047584244      |-18.96%           |
|Real_Monthly|2023;08|East Lothian       |0.02      |1275     |66893      |0.01906029       |4.70%             |
|Real_Monthly|2023;08|East Renfrewshire  |0.023     |1530     |57033      |0.026826574      |-16.64%           |
|Real_Monthly|2023;08|Edinburgh City     |0.018     |1025     |366367     |0.002797741      |84.46%            |
|Real_Monthly|2023;08|Eilean Siar        |0.029     |3010     |15508      |0.194093371      |-569.29%          |
|Real_Monthly|2023;08|Falkirk            |0.034     |7820     |102021     |0.076650886      |-125.44%          |
|Real_Monthly|2023;08|Fife               |0.047     |21200    |231635     |0.091523302      |-94.73%           |
|Real_Monthly|2023;08|Glasgow City       |0.022     |3140     |448645     |0.006998852      |68.19%            |
|Real_Monthly|2023;08|Highland           |0.038     |1840     |144706     |0.012715437      |66.54%            |
|Real_Monthly|2023;08|Inverclyde         |0.023     |1345     |47782      |0.028148675      |-22.39%           |
|Real_Monthly|2023;08|Moray              |0.018     |280      |58935      |0.004750997      |73.61%            |
|Real_Monthly|2023;08|Orkney Islands     |0.016     |210      |13447      |0.015616866      |2.39%             |
|Real_Monthly|2023;09|East Renfrewshire  |0.018     |1005     |57033      |0.017621377      |2.10%             |
|Real_Monthly|2023;09|Highland           |0.02      |2960     |144706     |0.020455268      |-2.28%            |
|Real_Monthly|2023;09|Moray              |0.021     |1210     |58935      |0.020531094      |2.23%             |
|Real_Monthly|2023;10|Aberdeenshire      |0.017     |2785     |160495     |0.017352566      |-2.07%            |
|Real_Monthly|2023;10|East Renfrewshire  |0.018     |1000     |57033      |0.017533709      |2.59%             |
|Real_Monthly|2023;10|Highland           |0.021     |2975     |144706     |0.020558926      |2.10%             |
|Real_Monthly|2023;10|Orkney Islands     |0.015     |195      |13447      |0.014501376      |3.32%             |
|Real_Monthly|2023;11|Aberdeenshire      |0.018     |2820     |160495     |0.017570641      |2.39%             |
|Real_Monthly|2023;11|East Renfrewshire  |0.018     |1000     |57033      |0.017533709      |2.59%             |
|Real_Monthly|2023;12|East Lothian       |0.023     |1570     |66893      |0.023470318      |-2.04%            |
|Real_Monthly|2023;12|East Renfrewshire  |0.018     |1000     |57033      |0.017533709      |2.59%             |
|Real_Monthly|2023;12|Eilean Siar        |0.018     |285      |15508      |0.018377612      |-2.10%            |
|Real_Monthly|2023;12|Orkney Islands     |0.015     |210      |13447      |0.015616866      |-4.11%            |
|Real_Monthly|2023;12|Perth & Kinross    |0.021     |1990     |92594      |0.021491673      |-2.34%            |

## ECON 12b - Various LA - Cash and Real - Monthly - Various Periods
> Various Local Authority Areas have differences between the result of dividing the numerator and denominator and the value stated as below.

|DataType    |Period |Local Authority    |LGBF Value |Numerator|Denominator|Calculation Value|Percent Difference|
|------------|-------|-------------------|-----------|---------|-----------|-----------------|------------------|
|Cash_Monthly|2010;05|Aberdeen City      |0.026410249|960      |34267      |0.028015292      |-6.08%            |
|Cash_Monthly|2010;05|Angus              |0.063896375|610      |11503      |0.053029644      |17.01%            |
|Cash_Monthly|2010;05|Argyll & Bute      |0.0547339  |460      |8587       |0.053569349      |2.13%             |
|Cash_Monthly|2010;05|Clackmannanshire   |0.100935952|505      |5449       |0.092677556      |8.18%             |
|Cash_Monthly|2010;05|Dumfries & Galloway|0.068140731|920      |14382      |0.06396885       |6.12%             |
|Cash_Monthly|2010;05|Dundee City        |0.070275565|1385     |23479      |0.058988884      |16.06%            |
|Cash_Monthly|2010;05|East Ayrshire      |0.108537296|1285     |13728      |0.093604312      |13.76%            |
|Cash_Monthly|2010;05|East Dunbartonshire|0.05241548 |535      |11447      |0.046737136      |10.83%            |
|Cash_Monthly|2010;05|East Lothian       |0.059318791|605      |10452      |0.057883659      |2.42%             |
|Cash_Monthly|2010;05|East Renfrewshire  |0.044651918|370      |9854       |0.037548204      |15.91%            |
|Cash_Monthly|2010;05|Falkirk            |0.076243981|1205     |16198      |0.0743919        |2.43%             |
|Cash_Monthly|2010;05|Fife               |0.076976571|2850     |41701      |0.068343685      |11.21%            |
|Cash_Monthly|2010;05|Glasgow City       |0.083750086|6650     |87582      |0.075928844      |9.34%             |
|Cash_Monthly|2010;05|Highland           |0.048640333|990      |22101      |0.044794353      |7.91%             |
|Cash_Monthly|2010;05|Inverclyde         |0.095444685|760      |9220       |0.082429501      |13.64%            |
|Cash_Monthly|2010;05|Midlothian         |0.074746092|710      |8763       |0.081022481      |-8.40%            |
|Cash_Monthly|2010;05|Moray              |0.046805047|430      |9828       |0.043752544      |6.52%             |
|Cash_Monthly|2010;05|North Ayrshire     |0.120975872|1615     |14879      |0.108542241      |10.28%            |
|Cash_Monthly|2010;05|North Lanarkshire  |0.095738837|3460     |38229      |0.090507207      |5.46%             |
|Cash_Monthly|2010;05|Orkney Islands     |0.028449502|45       |2109       |0.021337127      |25.00%            |
|Cash_Monthly|2010;05|Perth & Kinross    |0.03997195 |530      |14260      |0.0371669        |7.02%             |
|Cash_Monthly|2010;05|Renfrewshire       |0.082424615|1520     |19533      |0.077817028      |5.59%             |
|Cash_Monthly|2010;05|Shetland Islands   |0.024660912|65       |2433       |0.026715988      |-8.33%            |
|Cash_Monthly|2010;05|South Ayrshire     |0.082271762|820      |11304      |0.072540694      |11.83%            |
|Cash_Monthly|2010;05|South Lanarkshire  |0.080773265|2630     |33365      |0.078825116      |2.41%             |
|Cash_Monthly|2010;05|Stirling           |0.046189376|505      |12124      |0.04165292       |9.82%             |
|Cash_Monthly|2010;05|West Dunbartonshire|0.095827039|955      |10592      |0.090162387      |5.91%             |
|Cash_Monthly|2014;04|Angus              |0.036077545|415      |11791      |0.035196336      |2.44%             |
|Cash_Monthly|2014;04|East Ayrshire      |0.067380536|925      |13196      |0.070096999      |-4.03%            |
|Cash_Monthly|2014;04|East Lothian       |0.041140452|430      |10731      |0.040070823      |2.60%             |
|Cash_Monthly|2014;04|East Renfrewshire  |0.025370408|250      |10179      |0.024560369      |3.19%             |
|Cash_Monthly|2014;04|Edinburgh City     |0.026635951|1850     |67809      |0.027282514      |-2.43%            |
|Cash_Monthly|2014;04|Eilean Siar        |0.028022418|70       |2315       |0.030237581      |-7.90%            |
|Cash_Monthly|2014;04|Glasgow City       |0.046870361|4105     |83781      |0.048996789      |-4.54%            |
|Cash_Monthly|2014;04|Inverclyde         |0.053687636|495      |8725       |0.056733524      |-5.67%            |
|Cash_Monthly|2014;04|Midlothian         |0.0536346  |470      |8993       |0.052262871      |2.56%             |
|Cash_Monthly|2014;04|Perth & Kinross    |0.03085554 |440      |15132      |0.029077452      |5.76%             |
|Cash_Monthly|2014;04|Stirling           |0.031755196|385      |12805      |0.03006638       |5.32%             |
|Cash_Monthly|2014;04|West Dunbartonshire|0.067975831|720      |10042      |0.071698865      |-5.48%            |
|Cash_Monthly|2014;05|Angus              |0.035208207|405      |11791      |0.034348232      |2.44%             |
|Cash_Monthly|2014;05|East Ayrshire      |0.063374126|870      |13196      |0.065929069      |-4.03%            |
|Cash_Monthly|2014;05|East Lothian       |0.03779181 |395      |10731      |0.036809244      |2.60%             |
|Cash_Monthly|2014;05|East Renfrewshire  |0.024863   |245      |10179      |0.024069162      |3.19%             |
|Cash_Monthly|2014;05|Edinburgh City     |0.025628105|1780     |67809      |0.026250203      |-2.43%            |
|Cash_Monthly|2014;05|Eilean Siar        |0.022017614|55       |2315       |0.023758099      |-7.90%            |
|Cash_Monthly|2014;05|Glasgow City       |0.045785664|4010     |83781      |0.047862881      |-4.54%            |
|Cash_Monthly|2014;05|Inverclyde         |0.04989154 |460      |8725       |0.052722063      |-5.67%            |
|Cash_Monthly|2014;05|Midlothian         |0.051922857|455      |8993       |0.050594907      |2.56%             |
|Cash_Monthly|2014;05|Perth & Kinross    |0.026647966|380      |15132      |0.025112345      |5.76%             |
|Cash_Monthly|2014;05|Stirling           |0.029693171|360      |12805      |0.028114018      |5.32%             |
|Cash_Monthly|2014;05|West Dunbartonshire|0.061839124|655      |10042      |0.065226051      |-5.48%            |
|Cash_Monthly|2014;06|Angus              |0.036077545|415      |11791      |0.035196336      |2.44%             |
|Cash_Monthly|2014;06|East Ayrshire      |0.061188811|840      |13196      |0.063655653      |-4.03%            |
|Cash_Monthly|2014;06|East Lothian       |0.037313433|390      |10731      |0.036343304      |2.60%             |
|Cash_Monthly|2014;06|East Renfrewshire  |0.024863   |245      |10179      |0.024069162      |3.19%             |
|Cash_Monthly|2014;06|Edinburgh City     |0.023612411|1640     |67809      |0.02418558       |-2.43%            |
|Cash_Monthly|2014;06|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Cash_Monthly|2014;06|Glasgow City       |0.044415519|3890     |83781      |0.046430575      |-4.54%            |
|Cash_Monthly|2014;06|Inverclyde         |0.046095445|425      |8725       |0.048710602      |-5.67%            |
|Cash_Monthly|2014;06|Midlothian         |0.045075887|395      |8993       |0.043923051      |2.56%             |
|Cash_Monthly|2014;06|Perth & Kinross    |0.025596073|365      |15132      |0.024121068      |5.76%             |
|Cash_Monthly|2014;06|Stirling           |0.029280765|355      |12805      |0.027723545      |5.32%             |
|Cash_Monthly|2014;06|West Dunbartonshire|0.053814199|570      |10042      |0.056761601      |-5.48%            |
|Cash_Monthly|2014;07|Angus              |0.041728245|480      |11791      |0.040709015      |2.44%             |
|Cash_Monthly|2014;07|East Ayrshire      |0.075757576|1040     |13196      |0.078811761      |-4.03%            |
|Cash_Monthly|2014;07|East Lothian       |0.038748565|405      |10731      |0.037741124      |2.60%             |
|Cash_Monthly|2014;07|East Renfrewshire  |0.027907449|275      |10179      |0.027016406      |3.19%             |
|Cash_Monthly|2014;07|Edinburgh City     |0.024764236|1720     |67809      |0.025365364      |-2.43%            |
|Cash_Monthly|2014;07|Eilean Siar        |0.022017614|55       |2315       |0.023758099      |-7.90%            |
|Cash_Monthly|2014;07|Glasgow City       |0.046756183|4095     |83781      |0.04887743       |-4.54%            |
|Cash_Monthly|2014;07|Inverclyde         |0.055856833|515      |8725       |0.059025788      |-5.67%            |
|Cash_Monthly|2014;07|Midlothian         |0.04678763 |410      |8993       |0.045591015      |2.56%             |
|Cash_Monthly|2014;07|Perth & Kinross    |0.02769986 |395      |15132      |0.026103621      |5.76%             |
|Cash_Monthly|2014;07|Stirling           |0.02886836 |350      |12805      |0.027333073      |5.32%             |
|Cash_Monthly|2014;07|West Dunbartonshire|0.05711858 |605      |10042      |0.060246963      |-5.48%            |
|Cash_Monthly|2014;08|Angus              |0.03868556 |445      |11791      |0.03774065       |2.44%             |
|Cash_Monthly|2014;08|East Ayrshire      |0.074300699|1020     |13196      |0.07729615       |-4.03%            |
|Cash_Monthly|2014;08|East Lothian       |0.035878301|375      |10731      |0.034945485      |2.60%             |
|Cash_Monthly|2014;08|East Renfrewshire  |0.025370408|250      |10179      |0.024560369      |3.19%             |
|Cash_Monthly|2014;08|Edinburgh City     |0.023108488|1605     |67809      |0.023669424      |-2.43%            |
|Cash_Monthly|2014;08|Eilean Siar        |0.024019215|60       |2315       |0.025917927      |-7.90%            |
|Cash_Monthly|2014;08|Glasgow City       |0.045100591|3950     |83781      |0.047146728      |-4.54%            |
|Cash_Monthly|2014;08|Inverclyde         |0.054772234|505      |8725       |0.057879656      |-5.67%            |
|Cash_Monthly|2014;08|Midlothian         |0.045075887|395      |8993       |0.043923051      |2.56%             |
|Cash_Monthly|2014;08|Perth & Kinross    |0.026998597|385      |15132      |0.02544277       |5.76%             |
|Cash_Monthly|2014;08|Stirling           |0.02804355 |340      |12805      |0.026552128      |5.32%             |
|Cash_Monthly|2014;08|West Dunbartonshire|0.055702417|590      |10042      |0.058753236      |-5.48%            |
|Cash_Monthly|2014;09|Angus              |0.028688168|330      |11791      |0.027987448      |2.44%             |
|Cash_Monthly|2014;09|East Ayrshire      |0.058275058|800      |13196      |0.060624432      |-4.03%            |
|Cash_Monthly|2014;09|East Lothian       |0.033964791|355      |10731      |0.033081726      |2.60%             |
|Cash_Monthly|2014;09|East Renfrewshire  |0.020803735|205      |10179      |0.020139503      |3.19%             |
|Cash_Monthly|2014;09|Edinburgh City     |0.020732849|1440     |67809      |0.021236119      |-2.43%            |
|Cash_Monthly|2014;09|Eilean Siar        |0.024019215|60       |2315       |0.025917927      |-7.90%            |
|Cash_Monthly|2014;09|Glasgow City       |0.040362175|3535     |83781      |0.042193337      |-4.54%            |
|Cash_Monthly|2014;09|Inverclyde         |0.048806941|450      |8725       |0.051575931      |-5.67%            |
|Cash_Monthly|2014;09|Midlothian         |0.037087755|325      |8993       |0.036139219      |2.56%             |
|Cash_Monthly|2014;09|Perth & Kinross    |0.022440393|320      |15132      |0.021147238      |5.76%             |
|Cash_Monthly|2014;09|Stirling           |0.024744309|300      |12805      |0.023428348      |5.32%             |
|Cash_Monthly|2014;09|West Dunbartonshire|0.04956571 |525      |10042      |0.052280422      |-5.48%            |
|Cash_Monthly|2014;10|Angus              |0.028688168|330      |11791      |0.027987448      |2.44%             |
|Cash_Monthly|2014;10|East Ayrshire      |0.055725524|765      |13196      |0.057972113      |-4.03%            |
|Cash_Monthly|2014;10|East Lothian       |0.032051282|335      |10731      |0.031217967      |2.60%             |
|Cash_Monthly|2014;10|East Renfrewshire  |0.018266694|180      |10179      |0.017683466      |3.19%             |
|Cash_Monthly|2014;10|Edinburgh City     |0.020012958|1390     |67809      |0.020498754      |-2.43%            |
|Cash_Monthly|2014;10|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Cash_Monthly|2014;10|Glasgow City       |0.038535315|3375     |83781      |0.040283597      |-4.54%            |
|Cash_Monthly|2014;10|Inverclyde         |0.043926247|405      |8725       |0.046418338      |-5.67%            |
|Cash_Monthly|2014;10|Midlothian         |0.034234851|300      |8993       |0.033359279      |2.56%             |
|Cash_Monthly|2014;10|Perth & Kinross    |0.021037868|300      |15132      |0.019825535      |5.76%             |
|Cash_Monthly|2014;10|Stirling           |0.023919499|290      |12805      |0.022647403      |5.32%             |
|Cash_Monthly|2014;10|West Dunbartonshire|0.046261329|490      |10042      |0.048795061      |-5.48%            |
|Cash_Monthly|2014;11|Angus              |0.029557507|340      |11791      |0.028835553      |2.44%             |
|Cash_Monthly|2014;11|East Ayrshire      |0.051354895|705      |13196      |0.05342528       |-4.03%            |
|Cash_Monthly|2014;11|East Lothian       |0.031094527|325      |10731      |0.030286087      |2.60%             |
|Cash_Monthly|2014;11|East Renfrewshire  |0.017251877|170      |10179      |0.016701051      |3.19%             |
|Cash_Monthly|2014;11|Edinburgh City     |0.018213232|1265     |67809      |0.018655341      |-2.43%            |
|Cash_Monthly|2014;11|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Cash_Monthly|2014;11|Glasgow City       |0.037336439|3270     |83781      |0.039030329      |-4.54%            |
|Cash_Monthly|2014;11|Inverclyde         |0.039045553|360      |8725       |0.041260745      |-5.67%            |
|Cash_Monthly|2014;11|Midlothian         |0.030811366|270      |8993       |0.030023351      |2.56%             |
|Cash_Monthly|2014;11|Perth & Kinross    |0.019635344|280      |15132      |0.018503833      |5.76%             |
|Cash_Monthly|2014;11|Stirling           |0.021857473|265      |12805      |0.020695041      |5.32%             |
|Cash_Monthly|2014;11|West Dunbartonshire|0.045789275|485      |10042      |0.048297152      |-5.48%            |
|Cash_Monthly|2014;12|Angus              |0.030861514|355      |11791      |0.030107709      |2.44%             |
|Cash_Monthly|2014;12|East Ayrshire      |0.050262238|690      |13196      |0.052288572      |-4.03%            |
|Cash_Monthly|2014;12|East Lothian       |0.030137773|315      |10731      |0.029354207      |2.60%             |
|Cash_Monthly|2014;12|East Renfrewshire  |0.015222245|150      |10179      |0.014736222      |3.19%             |
|Cash_Monthly|2014;12|Edinburgh City     |0.01677345 |1165     |67809      |0.01718061       |-2.43%            |
|Cash_Monthly|2014;12|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Cash_Monthly|2014;12|Glasgow City       |0.035338312|3095     |83781      |0.03694155       |-4.54%            |
|Cash_Monthly|2014;12|Inverclyde         |0.037960954|350      |8725       |0.040114613      |-5.67%            |
|Cash_Monthly|2014;12|Midlothian         |0.029670204|260      |8993       |0.028911376      |2.56%             |
|Cash_Monthly|2014;12|Perth & Kinross    |0.019635344|280      |15132      |0.018503833      |5.76%             |
|Cash_Monthly|2014;12|Stirling           |0.020620257|250      |12805      |0.019523624      |5.32%             |
|Cash_Monthly|2014;12|West Dunbartonshire|0.049093656|520      |10042      |0.051782513      |-5.48%            |
|Cash_Monthly|2015;01|Angus              |0.029992176|345      |11791      |0.029259605      |2.44%             |
|Cash_Monthly|2015;01|East Ayrshire      |0.05354021 |735      |13196      |0.055698697      |-4.03%            |
|Cash_Monthly|2015;01|East Lothian       |0.029181018|305      |10731      |0.028422328      |2.60%             |
|Cash_Monthly|2015;01|East Renfrewshire  |0.018266694|180      |10179      |0.017683466      |3.19%             |
|Cash_Monthly|2015;01|Edinburgh City     |0.017709308|1230     |67809      |0.018139185      |-2.43%            |
|Cash_Monthly|2015;01|Eilean Siar        |0.024019215|60       |2315       |0.025917927      |-7.90%            |
|Cash_Monthly|2015;01|Glasgow City       |0.036423009|3190     |83781      |0.038075459      |-4.54%            |
|Cash_Monthly|2015;01|Inverclyde         |0.048264642|445      |8725       |0.051002865      |-5.67%            |
|Cash_Monthly|2015;01|Midlothian         |0.030811366|270      |8993       |0.030023351      |2.56%             |
|Cash_Monthly|2015;01|Perth & Kinross    |0.020687237|295      |15132      |0.01949511       |5.76%             |
|Cash_Monthly|2015;01|Stirling           |0.022682283|275      |12805      |0.021475986      |5.32%             |
|Cash_Monthly|2015;01|West Dunbartonshire|0.051925982|550      |10042      |0.054769966      |-5.48%            |
|Cash_Monthly|2015;02|Angus              |0.029992176|345      |11791      |0.029259605      |2.44%             |
|Cash_Monthly|2015;02|East Ayrshire      |0.054997086|755      |13196      |0.057214307      |-4.03%            |
|Cash_Monthly|2015;02|East Lothian       |0.031572905|330      |10731      |0.030752027      |2.60%             |
|Cash_Monthly|2015;02|East Renfrewshire  |0.018774102|185      |10179      |0.018174673      |3.19%             |
|Cash_Monthly|2015;02|Edinburgh City     |0.018501188|1285     |67809      |0.018950287      |-2.43%            |
|Cash_Monthly|2015;02|Eilean Siar        |0.022017614|55       |2315       |0.023758099      |-7.90%            |
|Cash_Monthly|2015;02|Glasgow City       |0.037621886|3295     |83781      |0.039328726      |-4.54%            |
|Cash_Monthly|2015;02|Inverclyde         |0.047722343|440      |8725       |0.050429799      |-5.67%            |
|Cash_Monthly|2015;02|Midlothian         |0.032523109|285      |8993       |0.031691315      |2.56%             |
|Cash_Monthly|2015;02|Perth & Kinross    |0.022089762|315      |15132      |0.020816812      |5.76%             |
|Cash_Monthly|2015;02|Stirling           |0.024331904|295      |12805      |0.023037876      |5.32%             |
|Cash_Monthly|2015;02|West Dunbartonshire|0.053342145|565      |10042      |0.056263692      |-5.48%            |
|Cash_Monthly|2015;03|Angus              |0.029557507|340      |11791      |0.028835553      |2.44%             |
|Cash_Monthly|2015;03|East Ayrshire      |0.054632867|750      |13196      |0.056835405      |-4.03%            |
|Cash_Monthly|2015;03|East Lothian       |0.030137773|315      |10731      |0.029354207      |2.60%             |
|Cash_Monthly|2015;03|East Renfrewshire  |0.018774102|185      |10179      |0.018174673      |3.19%             |
|Cash_Monthly|2015;03|Edinburgh City     |0.017493341|1215     |67809      |0.017917975      |-2.43%            |
|Cash_Monthly|2015;03|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Cash_Monthly|2015;03|Glasgow City       |0.037450618|3280     |83781      |0.039149688      |-4.54%            |
|Cash_Monthly|2015;03|Inverclyde         |0.044468547|410      |8725       |0.046991404      |-5.67%            |
|Cash_Monthly|2015;03|Midlothian         |0.033093689|290      |8993       |0.032247303      |2.56%             |
|Cash_Monthly|2015;03|Perth & Kinross    |0.021388499|305      |15132      |0.020155961      |5.76%             |
|Cash_Monthly|2015;03|Stirling           |0.021445068|260      |12805      |0.020304569      |5.32%             |
|Cash_Monthly|2015;03|West Dunbartonshire|0.050981873|540      |10042      |0.053774149      |-5.48%            |
|Cash_Monthly|2023;01|Dumfries & Galloway|0.034166796|450      |12878      |0.034943314      |-2.27%            |
|Cash_Monthly|2023;01|East Dunbartonshire|0.01998002 |210      |10010      |0.020979021      |-5.00%            |
|Cash_Monthly|2023;01|North Ayrshire     |0.05422745 |695      |13093      |0.053081799      |2.11%             |
|Cash_Monthly|2023;01|Perth & Kinross    |0.025653996|340      |13838      |0.024570025      |4.23%             |
|Cash_Monthly|2023;01|South Ayrshire     |0.043898589|455      |10137      |0.044885074      |-2.25%            |
|Cash_Monthly|2023;04|East Dunbartonshire|0.02       |205      |10010      |0.02047952       |-2.40%            |
|Cash_Monthly|2023;05|East Dunbartonshire|0.02       |205      |10010      |0.02047952       |-2.40%            |
|Cash_Monthly|2023;05|East Renfrewshire  |0.019      |180      |9682       |0.0185912        |2.15%             |
|Cash_Monthly|2023;06|East Dunbartonshire|0.021      |215      |10010      |0.021478521      |-2.28%            |
|Cash_Monthly|2023;07|East Renfrewshire  |0.018      |170      |9682       |0.017558356      |2.45%             |
|Cash_Monthly|2023;08|Edinburgh City     |0.021      |1255     |61017      |0.020568038      |2.06%             |
|Cash_Monthly|2023;09|East Dunbartonshire|0.02       |205      |10010      |0.02047952       |-2.40%            |
|Real_Monthly|2010;05|Aberdeen City      |0.026410249|960      |34267      |0.028015292      |-6.08%            |
|Real_Monthly|2010;05|Angus              |0.063896375|610      |11503      |0.053029644      |17.01%            |
|Real_Monthly|2010;05|Argyll & Bute      |0.0547339  |460      |8587       |0.053569349      |2.13%             |
|Real_Monthly|2010;05|Clackmannanshire   |0.100935952|505      |5449       |0.092677556      |8.18%             |
|Real_Monthly|2010;05|Dumfries & Galloway|0.068140731|920      |14382      |0.06396885       |6.12%             |
|Real_Monthly|2010;05|Dundee City        |0.070275565|1385     |23479      |0.058988884      |16.06%            |
|Real_Monthly|2010;05|East Ayrshire      |0.108537296|1285     |13728      |0.093604312      |13.76%            |
|Real_Monthly|2010;05|East Dunbartonshire|0.05241548 |535      |11447      |0.046737136      |10.83%            |
|Real_Monthly|2010;05|East Lothian       |0.059318791|605      |10452      |0.057883659      |2.42%             |
|Real_Monthly|2010;05|East Renfrewshire  |0.044651918|370      |9854       |0.037548204      |15.91%            |
|Real_Monthly|2010;05|Falkirk            |0.076243981|1205     |16198      |0.0743919        |2.43%             |
|Real_Monthly|2010;05|Fife               |0.076976571|2850     |41701      |0.068343685      |11.21%            |
|Real_Monthly|2010;05|Glasgow City       |0.083750086|6650     |87582      |0.075928844      |9.34%             |
|Real_Monthly|2010;05|Highland           |0.048640333|990      |22101      |0.044794353      |7.91%             |
|Real_Monthly|2010;05|Inverclyde         |0.095444685|760      |9220       |0.082429501      |13.64%            |
|Real_Monthly|2010;05|Midlothian         |0.074746092|710      |8763       |0.081022481      |-8.40%            |
|Real_Monthly|2010;05|Moray              |0.046805047|430      |9828       |0.043752544      |6.52%             |
|Real_Monthly|2010;05|North Ayrshire     |0.120975872|1615     |14879      |0.108542241      |10.28%            |
|Real_Monthly|2010;05|North Lanarkshire  |0.095738837|3460     |38229      |0.090507207      |5.46%             |
|Real_Monthly|2010;05|Orkney Islands     |0.028449502|45       |2109       |0.021337127      |25.00%            |
|Real_Monthly|2010;05|Perth & Kinross    |0.03997195 |530      |14260      |0.0371669        |7.02%             |
|Real_Monthly|2010;05|Renfrewshire       |0.082424615|1520     |19533      |0.077817028      |5.59%             |
|Real_Monthly|2010;05|Shetland Islands   |0.024660912|65       |2433       |0.026715988      |-8.33%            |
|Real_Monthly|2010;05|South Ayrshire     |0.082271762|820      |11304      |0.072540694      |11.83%            |
|Real_Monthly|2010;05|South Lanarkshire  |0.080773265|2630     |33365      |0.078825116      |2.41%             |
|Real_Monthly|2010;05|Stirling           |0.046189376|505      |12124      |0.04165292       |9.82%             |
|Real_Monthly|2010;05|West Dunbartonshire|0.095827039|955      |10592      |0.090162387      |5.91%             |
|Real_Monthly|2014;04|Angus              |0.036077545|415      |11791      |0.035196336      |2.44%             |
|Real_Monthly|2014;04|East Ayrshire      |0.067380536|925      |13196      |0.070096999      |-4.03%            |
|Real_Monthly|2014;04|East Lothian       |0.041140452|430      |10731      |0.040070823      |2.60%             |
|Real_Monthly|2014;04|East Renfrewshire  |0.025370408|250      |10179      |0.024560369      |3.19%             |
|Real_Monthly|2014;04|Edinburgh City     |0.026635951|1850     |67809      |0.027282514      |-2.43%            |
|Real_Monthly|2014;04|Eilean Siar        |0.028022418|70       |2315       |0.030237581      |-7.90%            |
|Real_Monthly|2014;04|Glasgow City       |0.046870361|4105     |83781      |0.048996789      |-4.54%            |
|Real_Monthly|2014;04|Inverclyde         |0.053687636|495      |8725       |0.056733524      |-5.67%            |
|Real_Monthly|2014;04|Midlothian         |0.0536346  |470      |8993       |0.052262871      |2.56%             |
|Real_Monthly|2014;04|Perth & Kinross    |0.03085554 |440      |15132      |0.029077452      |5.76%             |
|Real_Monthly|2014;04|Stirling           |0.031755196|385      |12805      |0.03006638       |5.32%             |
|Real_Monthly|2014;04|West Dunbartonshire|0.067975831|720      |10042      |0.071698865      |-5.48%            |
|Real_Monthly|2014;05|Angus              |0.035208207|405      |11791      |0.034348232      |2.44%             |
|Real_Monthly|2014;05|East Ayrshire      |0.063374126|870      |13196      |0.065929069      |-4.03%            |
|Real_Monthly|2014;05|East Lothian       |0.03779181 |395      |10731      |0.036809244      |2.60%             |
|Real_Monthly|2014;05|East Renfrewshire  |0.024863   |245      |10179      |0.024069162      |3.19%             |
|Real_Monthly|2014;05|Edinburgh City     |0.025628105|1780     |67809      |0.026250203      |-2.43%            |
|Real_Monthly|2014;05|Eilean Siar        |0.022017614|55       |2315       |0.023758099      |-7.90%            |
|Real_Monthly|2014;05|Glasgow City       |0.045785664|4010     |83781      |0.047862881      |-4.54%            |
|Real_Monthly|2014;05|Inverclyde         |0.04989154 |460      |8725       |0.052722063      |-5.67%            |
|Real_Monthly|2014;05|Midlothian         |0.051922857|455      |8993       |0.050594907      |2.56%             |
|Real_Monthly|2014;05|Perth & Kinross    |0.026647966|380      |15132      |0.025112345      |5.76%             |
|Real_Monthly|2014;05|Stirling           |0.029693171|360      |12805      |0.028114018      |5.32%             |
|Real_Monthly|2014;05|West Dunbartonshire|0.061839124|655      |10042      |0.065226051      |-5.48%            |
|Real_Monthly|2014;06|Angus              |0.036077545|415      |11791      |0.035196336      |2.44%             |
|Real_Monthly|2014;06|East Ayrshire      |0.061188811|840      |13196      |0.063655653      |-4.03%            |
|Real_Monthly|2014;06|East Lothian       |0.037313433|390      |10731      |0.036343304      |2.60%             |
|Real_Monthly|2014;06|East Renfrewshire  |0.024863   |245      |10179      |0.024069162      |3.19%             |
|Real_Monthly|2014;06|Edinburgh City     |0.023612411|1640     |67809      |0.02418558       |-2.43%            |
|Real_Monthly|2014;06|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Real_Monthly|2014;06|Glasgow City       |0.044415519|3890     |83781      |0.046430575      |-4.54%            |
|Real_Monthly|2014;06|Inverclyde         |0.046095445|425      |8725       |0.048710602      |-5.67%            |
|Real_Monthly|2014;06|Midlothian         |0.045075887|395      |8993       |0.043923051      |2.56%             |
|Real_Monthly|2014;06|Perth & Kinross    |0.025596073|365      |15132      |0.024121068      |5.76%             |
|Real_Monthly|2014;06|Stirling           |0.029280765|355      |12805      |0.027723545      |5.32%             |
|Real_Monthly|2014;06|West Dunbartonshire|0.053814199|570      |10042      |0.056761601      |-5.48%            |
|Real_Monthly|2014;07|Angus              |0.041728245|480      |11791      |0.040709015      |2.44%             |
|Real_Monthly|2014;07|East Ayrshire      |0.075757576|1040     |13196      |0.078811761      |-4.03%            |
|Real_Monthly|2014;07|East Lothian       |0.038748565|405      |10731      |0.037741124      |2.60%             |
|Real_Monthly|2014;07|East Renfrewshire  |0.027907449|275      |10179      |0.027016406      |3.19%             |
|Real_Monthly|2014;07|Edinburgh City     |0.024764236|1720     |67809      |0.025365364      |-2.43%            |
|Real_Monthly|2014;07|Eilean Siar        |0.022017614|55       |2315       |0.023758099      |-7.90%            |
|Real_Monthly|2014;07|Glasgow City       |0.046756183|4095     |83781      |0.04887743       |-4.54%            |
|Real_Monthly|2014;07|Inverclyde         |0.055856833|515      |8725       |0.059025788      |-5.67%            |
|Real_Monthly|2014;07|Midlothian         |0.04678763 |410      |8993       |0.045591015      |2.56%             |
|Real_Monthly|2014;07|Perth & Kinross    |0.02769986 |395      |15132      |0.026103621      |5.76%             |
|Real_Monthly|2014;07|Stirling           |0.02886836 |350      |12805      |0.027333073      |5.32%             |
|Real_Monthly|2014;07|West Dunbartonshire|0.05711858 |605      |10042      |0.060246963      |-5.48%            |
|Real_Monthly|2014;08|Angus              |0.03868556 |445      |11791      |0.03774065       |2.44%             |
|Real_Monthly|2014;08|East Ayrshire      |0.074300699|1020     |13196      |0.07729615       |-4.03%            |
|Real_Monthly|2014;08|East Lothian       |0.035878301|375      |10731      |0.034945485      |2.60%             |
|Real_Monthly|2014;08|East Renfrewshire  |0.025370408|250      |10179      |0.024560369      |3.19%             |
|Real_Monthly|2014;08|Edinburgh City     |0.023108488|1605     |67809      |0.023669424      |-2.43%            |
|Real_Monthly|2014;08|Eilean Siar        |0.024019215|60       |2315       |0.025917927      |-7.90%            |
|Real_Monthly|2014;08|Glasgow City       |0.045100591|3950     |83781      |0.047146728      |-4.54%            |
|Real_Monthly|2014;08|Inverclyde         |0.054772234|505      |8725       |0.057879656      |-5.67%            |
|Real_Monthly|2014;08|Midlothian         |0.045075887|395      |8993       |0.043923051      |2.56%             |
|Real_Monthly|2014;08|Perth & Kinross    |0.026998597|385      |15132      |0.02544277       |5.76%             |
|Real_Monthly|2014;08|Stirling           |0.02804355 |340      |12805      |0.026552128      |5.32%             |
|Real_Monthly|2014;08|West Dunbartonshire|0.055702417|590      |10042      |0.058753236      |-5.48%            |
|Real_Monthly|2014;09|Angus              |0.028688168|330      |11791      |0.027987448      |2.44%             |
|Real_Monthly|2014;09|East Ayrshire      |0.058275058|800      |13196      |0.060624432      |-4.03%            |
|Real_Monthly|2014;09|East Lothian       |0.033964791|355      |10731      |0.033081726      |2.60%             |
|Real_Monthly|2014;09|East Renfrewshire  |0.020803735|205      |10179      |0.020139503      |3.19%             |
|Real_Monthly|2014;09|Edinburgh City     |0.020732849|1440     |67809      |0.021236119      |-2.43%            |
|Real_Monthly|2014;09|Eilean Siar        |0.024019215|60       |2315       |0.025917927      |-7.90%            |
|Real_Monthly|2014;09|Glasgow City       |0.040362175|3535     |83781      |0.042193337      |-4.54%            |
|Real_Monthly|2014;09|Inverclyde         |0.048806941|450      |8725       |0.051575931      |-5.67%            |
|Real_Monthly|2014;09|Midlothian         |0.037087755|325      |8993       |0.036139219      |2.56%             |
|Real_Monthly|2014;09|Perth & Kinross    |0.022440393|320      |15132      |0.021147238      |5.76%             |
|Real_Monthly|2014;09|Stirling           |0.024744309|300      |12805      |0.023428348      |5.32%             |
|Real_Monthly|2014;09|West Dunbartonshire|0.04956571 |525      |10042      |0.052280422      |-5.48%            |
|Real_Monthly|2014;10|Angus              |0.028688168|330      |11791      |0.027987448      |2.44%             |
|Real_Monthly|2014;10|East Ayrshire      |0.055725524|765      |13196      |0.057972113      |-4.03%            |
|Real_Monthly|2014;10|East Lothian       |0.032051282|335      |10731      |0.031217967      |2.60%             |
|Real_Monthly|2014;10|East Renfrewshire  |0.018266694|180      |10179      |0.017683466      |3.19%             |
|Real_Monthly|2014;10|Edinburgh City     |0.020012958|1390     |67809      |0.020498754      |-2.43%            |
|Real_Monthly|2014;10|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Real_Monthly|2014;10|Glasgow City       |0.038535315|3375     |83781      |0.040283597      |-4.54%            |
|Real_Monthly|2014;10|Inverclyde         |0.043926247|405      |8725       |0.046418338      |-5.67%            |
|Real_Monthly|2014;10|Midlothian         |0.034234851|300      |8993       |0.033359279      |2.56%             |
|Real_Monthly|2014;10|Perth & Kinross    |0.021037868|300      |15132      |0.019825535      |5.76%             |
|Real_Monthly|2014;10|Stirling           |0.023919499|290      |12805      |0.022647403      |5.32%             |
|Real_Monthly|2014;10|West Dunbartonshire|0.046261329|490      |10042      |0.048795061      |-5.48%            |
|Real_Monthly|2014;11|Angus              |0.029557507|340      |11791      |0.028835553      |2.44%             |
|Real_Monthly|2014;11|East Ayrshire      |0.051354895|705      |13196      |0.05342528       |-4.03%            |
|Real_Monthly|2014;11|East Lothian       |0.031094527|325      |10731      |0.030286087      |2.60%             |
|Real_Monthly|2014;11|East Renfrewshire  |0.017251877|170      |10179      |0.016701051      |3.19%             |
|Real_Monthly|2014;11|Edinburgh City     |0.018213232|1265     |67809      |0.018655341      |-2.43%            |
|Real_Monthly|2014;11|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Real_Monthly|2014;11|Glasgow City       |0.037336439|3270     |83781      |0.039030329      |-4.54%            |
|Real_Monthly|2014;11|Inverclyde         |0.039045553|360      |8725       |0.041260745      |-5.67%            |
|Real_Monthly|2014;11|Midlothian         |0.030811366|270      |8993       |0.030023351      |2.56%             |
|Real_Monthly|2014;11|Perth & Kinross    |0.019635344|280      |15132      |0.018503833      |5.76%             |
|Real_Monthly|2014;11|Stirling           |0.021857473|265      |12805      |0.020695041      |5.32%             |
|Real_Monthly|2014;11|West Dunbartonshire|0.045789275|485      |10042      |0.048297152      |-5.48%            |
|Real_Monthly|2014;12|Angus              |0.030861514|355      |11791      |0.030107709      |2.44%             |
|Real_Monthly|2014;12|East Ayrshire      |0.050262238|690      |13196      |0.052288572      |-4.03%            |
|Real_Monthly|2014;12|East Lothian       |0.030137773|315      |10731      |0.029354207      |2.60%             |
|Real_Monthly|2014;12|East Renfrewshire  |0.015222245|150      |10179      |0.014736222      |3.19%             |
|Real_Monthly|2014;12|Edinburgh City     |0.01677345 |1165     |67809      |0.01718061       |-2.43%            |
|Real_Monthly|2014;12|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Real_Monthly|2014;12|Glasgow City       |0.035338312|3095     |83781      |0.03694155       |-4.54%            |
|Real_Monthly|2014;12|Inverclyde         |0.037960954|350      |8725       |0.040114613      |-5.67%            |
|Real_Monthly|2014;12|Midlothian         |0.029670204|260      |8993       |0.028911376      |2.56%             |
|Real_Monthly|2014;12|Perth & Kinross    |0.019635344|280      |15132      |0.018503833      |5.76%             |
|Real_Monthly|2014;12|Stirling           |0.020620257|250      |12805      |0.019523624      |5.32%             |
|Real_Monthly|2014;12|West Dunbartonshire|0.049093656|520      |10042      |0.051782513      |-5.48%            |
|Real_Monthly|2015;01|Angus              |0.029992176|345      |11791      |0.029259605      |2.44%             |
|Real_Monthly|2015;01|East Ayrshire      |0.05354021 |735      |13196      |0.055698697      |-4.03%            |
|Real_Monthly|2015;01|East Lothian       |0.029181018|305      |10731      |0.028422328      |2.60%             |
|Real_Monthly|2015;01|East Renfrewshire  |0.018266694|180      |10179      |0.017683466      |3.19%             |
|Real_Monthly|2015;01|Edinburgh City     |0.017709308|1230     |67809      |0.018139185      |-2.43%            |
|Real_Monthly|2015;01|Eilean Siar        |0.024019215|60       |2315       |0.025917927      |-7.90%            |
|Real_Monthly|2015;01|Glasgow City       |0.036423009|3190     |83781      |0.038075459      |-4.54%            |
|Real_Monthly|2015;01|Inverclyde         |0.048264642|445      |8725       |0.051002865      |-5.67%            |
|Real_Monthly|2015;01|Midlothian         |0.030811366|270      |8993       |0.030023351      |2.56%             |
|Real_Monthly|2015;01|Perth & Kinross    |0.020687237|295      |15132      |0.01949511       |5.76%             |
|Real_Monthly|2015;01|Stirling           |0.022682283|275      |12805      |0.021475986      |5.32%             |
|Real_Monthly|2015;01|West Dunbartonshire|0.051925982|550      |10042      |0.054769966      |-5.48%            |
|Real_Monthly|2015;02|Angus              |0.029992176|345      |11791      |0.029259605      |2.44%             |
|Real_Monthly|2015;02|East Ayrshire      |0.054997086|755      |13196      |0.057214307      |-4.03%            |
|Real_Monthly|2015;02|East Lothian       |0.031572905|330      |10731      |0.030752027      |2.60%             |
|Real_Monthly|2015;02|East Renfrewshire  |0.018774102|185      |10179      |0.018174673      |3.19%             |
|Real_Monthly|2015;02|Edinburgh City     |0.018501188|1285     |67809      |0.018950287      |-2.43%            |
|Real_Monthly|2015;02|Eilean Siar        |0.022017614|55       |2315       |0.023758099      |-7.90%            |
|Real_Monthly|2015;02|Glasgow City       |0.037621886|3295     |83781      |0.039328726      |-4.54%            |
|Real_Monthly|2015;02|Inverclyde         |0.047722343|440      |8725       |0.050429799      |-5.67%            |
|Real_Monthly|2015;02|Midlothian         |0.032523109|285      |8993       |0.031691315      |2.56%             |
|Real_Monthly|2015;02|Perth & Kinross    |0.022089762|315      |15132      |0.020816812      |5.76%             |
|Real_Monthly|2015;02|Stirling           |0.024331904|295      |12805      |0.023037876      |5.32%             |
|Real_Monthly|2015;02|West Dunbartonshire|0.053342145|565      |10042      |0.056263692      |-5.48%            |
|Real_Monthly|2015;03|Angus              |0.029557507|340      |11791      |0.028835553      |2.44%             |
|Real_Monthly|2015;03|East Ayrshire      |0.054632867|750      |13196      |0.056835405      |-4.03%            |
|Real_Monthly|2015;03|East Lothian       |0.030137773|315      |10731      |0.029354207      |2.60%             |
|Real_Monthly|2015;03|East Renfrewshire  |0.018774102|185      |10179      |0.018174673      |3.19%             |
|Real_Monthly|2015;03|Edinburgh City     |0.017493341|1215     |67809      |0.017917975      |-2.43%            |
|Real_Monthly|2015;03|Eilean Siar        |0.020016013|50       |2315       |0.021598272      |-7.90%            |
|Real_Monthly|2015;03|Glasgow City       |0.037450618|3280     |83781      |0.039149688      |-4.54%            |
|Real_Monthly|2015;03|Inverclyde         |0.044468547|410      |8725       |0.046991404      |-5.67%            |
|Real_Monthly|2015;03|Midlothian         |0.033093689|290      |8993       |0.032247303      |2.56%             |
|Real_Monthly|2015;03|Perth & Kinross    |0.021388499|305      |15132      |0.020155961      |5.76%             |
|Real_Monthly|2015;03|Stirling           |0.021445068|260      |12805      |0.020304569      |5.32%             |
|Real_Monthly|2015;03|West Dunbartonshire|0.050981873|540      |10042      |0.053774149      |-5.48%            |
|Real_Monthly|2023;01|Dumfries & Galloway|0.034166796|450      |12878      |0.034943314      |-2.27%            |
|Real_Monthly|2023;01|East Dunbartonshire|0.01998002 |210      |10010      |0.020979021      |-5.00%            |
|Real_Monthly|2023;01|North Ayrshire     |0.05422745 |695      |13093      |0.053081799      |2.11%             |
|Real_Monthly|2023;01|Perth & Kinross    |0.025653996|340      |13838      |0.024570025      |4.23%             |
|Real_Monthly|2023;01|South Ayrshire     |0.043898589|455      |10137      |0.044885074      |-2.25%            |
|Real_Monthly|2023;04|East Dunbartonshire|0.02       |205      |10010      |0.02047952       |-2.40%            |
|Real_Monthly|2023;05|East Dunbartonshire|0.02       |205      |10010      |0.02047952       |-2.40%            |
|Real_Monthly|2023;05|East Renfrewshire  |0.019      |180      |9682       |0.0185912        |2.15%             |
|Real_Monthly|2023;06|East Dunbartonshire|0.021      |215      |10010      |0.021478521      |-2.28%            |
|Real_Monthly|2023;07|East Renfrewshire  |0.018      |170      |9682       |0.017558356      |2.45%             |
|Real_Monthly|2023;08|Edinburgh City     |0.021      |1255     |61017      |0.020568038      |2.06%             |
|Real_Monthly|2023;09|East Dunbartonshire|0.02       |205      |10010      |0.02047952       |-2.40%            |

## FINSUS 05 - East Renfrewshire - Cash and Real - Annual - 2015-16,2016-17
> Difference between the result of dividing the numerator and denominator and the value stated as below. Possibly the result of rounding but is outside the 2% tollerance set.

|DataType   |Period |Local Authority  |LGBF Value|Numerator  |Denominator|Calculation Value|Percent Difference|
|-----------|-------|-----------------|----------|-----------|-----------|-----------------|------------------|
|Cash_Annual|2015-16|East Renfrewshire|0.947     |220428000  |223293000  |0.987169325      |-4.24%            |
|Cash_Annual|2016-17|East Renfrewshire|0.965     |217214000  |219651000  |0.988905127      |-2.48%            |
|Real_Annual|2015-16|East Renfrewshire|0.947     |267053061  |270524067.5|0.987169325      |-4.24%            |
|Real_Annual|2016-17|East Renfrewshire|0.965     |257306768.8|260193583.6|0.988905127      |-2.48%            |