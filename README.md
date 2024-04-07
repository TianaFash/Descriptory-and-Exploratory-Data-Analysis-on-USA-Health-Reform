# Post-Implementation Analysis of the Affordable Care Act (ACA): A Review of State-Specific Health Insurance Coverage
## Background
The Affordable Care Act (ACA), commonly referred to as Obamacare, was signed into law on March 23, 2010, to advance health equity across diverse demographics in the United States. It stands as one of the most significant and debated pieces of healthcare legislation in U.S. history. Given its importance, it is imperative to evaluate the ACA's impact on the American populace.

Researchers, policymakers, and analysts can utilize the dataset provided in this project to gain comprehensive insights into the ACA's effectiveness in improving health insurance coverage. Furthermore, this dataset serves as a crucial resource for informing future healthcare policy decisions.
## Project Overview
This analysis explores the impact of the Affordable Care Act (ACA) over 5 years post-implementation, focusing on key metrics such as health coverage, Medicaid expansion, and employer-provided insurance. It aims to understand how the ACA has influenced health insurance coverage in the United States, examining trends such as changes in insured individuals, shifts in Medicaid enrollment, and variations in uninsured rates across states.

The analysis investigates the relationship between the implementation of Medicaid expansion in 2016 and changes in uninsured rates across states by comparing the uninsured rate change trends from 2010 to 2015 with the Medicaid expansion status in 2016, insights are drawn regarding the effectiveness of Medicaid expansion in reducing the uninsured population.
Utilizing a comprehensive dataset, this analysis provides insights into health insurance coverage data for each state and the nation. It includes variables such as uninsured rates post-ACA, estimates of individuals covered by employer and marketplace healthcare plans, and enrollment in Medicare and Medicaid programs.
This project offers valuable insights for researchers, policymakers, and analysts seeking to understand the impact of the ACA on health insurance coverage and inform future healthcare policy decisions.
## Data Source
The data source for information on the Affordable Care Act (ACA), also known as Obamacare, was compiled from reputable sources:
1.	The U.S. Department of Health & Human Services (HHS), particularly sections dedicated to ACA implementation and updates and the and the US Census Bureau.
2.	Reports and publications from government agencies like the Centers for Medicare & Medicaid Services (CMS), oversee ACA implementation and healthcare programs.
3.	Congressional Budget Office (CBO) reports and analyses related to the ACA's fiscal impact and coverage projections.
4.	Academic research studies and analyses published in peer-reviewed journals.
5.	Qualitative data by a non-profit organization specializing in healthcare policy and reform – The Commonwealth Fund.

This dataset offers comprehensive insights into health insurance coverage for each state and the nation, including uninsured rates after Obamacare, estimates of individuals covered by employer and marketplace healthcare plans, and enrollment in Medicare and Medicaid programs. These combined sources provide credible information essential for analyzing the impact of healthcare policy changes, such as the ACA, on coverage rates and enrollment in various healthcare programs.
## Tool
Microsoft PowerBI
## Data Cleaning and Preparation
1.	**Removed Bottom Row**: The row containing the total for the entire country was excluded as it does not represent the individual states.
2.	**Removed Duplicates**: Ensured data accuracy and uniqueness by removing duplicate entries from the dataset.
3.	**Changed Data Types**: Aligned data types with their respective values, converting decimals to whole numbers where necessary for consistency and clarity.
4.	**Replaced Null Values**: Substituted missing values in text fields with "NA" and numerical fields with "0" to standardize the dataset and facilitate analysis.
5.	**Created New Column**: Introduced a new column to replace the Medicaid Enrollment Change column. This was done to categorize and sort the instances where there were blank cells identified in the Medicaid Enrollment column for the year 2013. This column enables a more complete and accurate analysis of the data points.

  	![image](https://github.com/TianaFash/Impact-of-the-Affordable-Care-Act-on-Coverage-A-Five-Year-Post-Implementation-Analysis/assets/166267039/95d78887-d530-4e25-9b42-c1a30da530b5)
## Descriptive and Exploratory Analysis
The combination of descriptive and exploratory analyses provides valuable insights into the trends, identifies the causal relationship between new policy implementation and health outcomes across various states as well as addresses pertinent questions:
- How has the Affordable Care Act changed the rate of citizens with health insurance coverage? 
- Which states observed the greatest and least decline in their uninsured rate? 
- Did those states expand Medicaid program coverage?
## Key Findings
**Significant Increase in Health Coverage:** Following the implementation of the ACA, a significant increase in health insurance coverage was seen. Specifically, approximately 20 million more individuals obtained health insurance coverage nationwide within five years demonstrating the ACA's substantial impact on coverage rates.
In 2016, the total enrollment in Medicare was 56 million and total employer healthcare coverage was 172 million, which offers a broader context to the positive impact of ACA in increasing health coverage.

**State-specific Reduction in Uninsured Rates:** The states below showed the most significant decrease in the percentage of uninsured residents reflecting the ACA's effectiveness in expanding coverage. Specifically, Nevada experienced the greatest decline in uninsured individuals between 2010 to 2015 with a percentage decrease of 10.30%. Other states with the reduction include Oregon, California and Kentucky.

  ![ACA_Significant Reductions](https://github.com/TianaFash/Impact-of-the-Affordable-Care-Act-on-Coverage-A-Five-Year-Post-Implementation-Analysis/assets/166267039/157f552a-6960-43e9-8763-434dfe569f2b)

**Impact of Medicaid Expansion Program**
-Out of the fifty states in the US, 32 states expanded their Medicaid programs to cover individuals with limited income and resources at a certain threshold point. 
- 17 million individuals were enrolled in the Medicaid program between 2013 to 2018.
- Many States that have expanded Medicaid have experienced a notable reduction in uninsured rates among their populations except Florid. The data suggests that there is a strong correlation between the expansion of the Medicaid program and the decline in the number of uninsured individuals, conversely, states with non-expanded Medicaid programs have a high number of uninsured individuals.

   ![ACA_Highest Uninsured Rate_2010_2015](https://github.com/TianaFash/Impact-of-the-Affordable-Care-Act-on-Coverage-A-Five-Year-Post-Implementation-Analysis/assets/166267039/8ec17788-8870-45b7-9eef-6832fb97186d)



