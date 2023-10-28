# Food-Claims-Process-Analysis
![close-up-delicious-fast-food-meal (1)](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/f9acff85-3368-41a7-911a-1f230185a944)


## Table of contents 
- [Project Overview](#project-Overview)
- [Data Source](#Data-Source)
- [Tools](#Tools)
- [Data Cleaning / Preparation](#Data-Cleaning-Preparation)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Results/Findings](#Results-Findings)
- [Recommendations](#Recommendations)

  Recommendations
## Project Overview
Vivendo, a major fast-food chain in Brazil, faces frequent food poisoning claims. Its legal team from four locations aims to improve response times and streamline claim closures, prompting a project to compare each location's efficiency in resolving these claims.




###  Data Source
Customer Claims: the primary dataset used for this analysis is the “food_claims_222_a.csv” file, containing detailed information about each claim sent to the company.

## Tools 
- Excel - Data Cleaning
   - - [Download here](https://docs.google.com/spreadsheets/d/1n_zkpd_ejAqG5APHvrkp8wVMdNnjwqY-DKZMPyfcVQs/edit?usp=sharing)
  
- Excel - Data Analysis




### Data Cleaning Preparation 

 In the initial data preparation phase, we performed the following tasks:

1- Data loading and inspection.

2- Handling missing values.

3- Data cleaning and formatting.






### Exploratory Data Analysis
 EDA involves exploring the claims data to answer key questions, such as:

- What is the number of claims in each location?
- What is the distribution of time to close for all claims?
- What is the relationship between time to close and location?




### Results Findings
The analysis results are summarized as follows:

1- There are four locations for claims included in this data. The most common location listed is a RECIFE for Claims, with SAO LUIS being second although with half the number of locations. The locations are unbalanced, with most observations being either RECIFE or SAO LUIS. The team should focus on distributing their team employees in RECIFE as they are more common.



![visualization](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/d4de4357-e01c-4126-8462-c1a374ca948f)






2- The distribution of time to close all claims is right-skewed, with the majority of claims being closed within a relatively short period. However, there is a notable peak between 176-188 days, indicating a cluster of claims that take longer to close.

This suggests potential areas for improvement in the claims processing timeline. Please refer to the attached histogram visualization for a clear representation. To reduce claim closure times, consider process optimization, additional resources, and training while focusing on workload balance.




![Task 3](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/3144c61e-71a5-472c-85b9-bb9460e5db2b)








3- The box plot shows below that there is a difference in the time to close claims by location. The median time to close claims is the shortest in FORTALEZA, followed by NATAL, RECIFE, and SAO LUIS. The interquartile range (IQR) is also the smallest in FORTALEZA, followed by NATAL, RECIFE, and SAO LUIS. This means that there is less variability in the time to close claims in FORTALEZA and NATAL than in RECIFE and SAO LUIS.

There are a number of possible explanations for the difference in time to close claims by location. One possibility is that there are differences in the efficiency of the claims processing systems in each location. Another possibility is that there are differences in the complexity of the claims that are processed in each location. For example, if a location receives a higher proportion of complex claims, this could lead to a longer median time to close claims.


The box plot also shows that there are some outliers in the data for each location. This means that there are some claims that took a much longer time to close than the majority of claims.




![Box Plot Task 4](https://github.com/aliabdulelah/Food-Claims-Process-Analysis/assets/129835709/66c43ab1-797f-4d5f-a3f1-3e3219e54191)






### Recommendations
Based on the analysis, we recommend the following actions:


1- Review the claims processing procedures in RECIFE and SAO LUIS to identify potential areas for improvement, such as eliminating unnecessary steps.

2- Implement additional training for claims adjusters in RECIFE and SAO LUIS to enhance their efficiency in handling claims.

3- Regularly monitor the time taken to close claims in RECIFE and SAO LUIS to track progress and pinpoint areas requiring further improvement.

4- Evaluate the feasibility of centralizing the processing of complex claims in a single location to leverage the expertise of experienced claims adjusters for more efficient resolution.


