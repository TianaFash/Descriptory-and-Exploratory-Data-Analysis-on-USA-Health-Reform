# Post-Implementation Analysis of the Affordable Care Act (ACA) in USA: A Review of State-Specific Health Insurance Coverage
## Background
The Affordable Care Act (ACA), commonly called Obamacare, was signed into law on March 23, 2010, to advance health equity across diverse demographics in the United States. It stands as one of the most significant and debated pieces of healthcare legislation in U.S. history. Given its importance, evaluating the ACA's impact on the American populace is imperative.

Researchers, policymakers, and analysts can utilize the dataset provided in this project to gain comprehensive insights into the ACA's effectiveness in improving health insurance coverage. Furthermore, this dataset serves as a crucial resource for informing future healthcare policy decisions.
## Project Overview
This analysis explores the impact of the Affordable Care Act (ACA) over 5 years post-implementation, focusing on key metrics such as health coverage, Medicaid expansion, and marketplace-provided insurance. It aims to understand how the ACA has influenced health insurance coverage in the United States. It examines trends such as changes in insured individuals, shifts in Medicaid enrollment, and variations in uninsured rates across states.

The analysis investigates the relationship between the implementation of Medicaid expansion in 2016 and changes in uninsured rates across states by comparing the uninsured rate change trends from 2010 to 2015 with the Medicaid expansion status in 2016, insights are drawn regarding the effectiveness of Medicaid expansion in reducing the uninsured population.
Utilizing a comprehensive dataset, this analysis provides insights into health insurance coverage data for each state and the nation. This includes variables such as uninsured rates post-ACA, estimates of individuals covered by employer and marketplace healthcare plans, and enrollment in Medicare and Medicaid programs.
This project offers valuable insights for researchers, policymakers, and analysts seeking to understand the impact of the ACA on health insurance coverage and inform future healthcare policy decisions.
## Data Sources
The data source for information on the Affordable Care Act (ACA), also known as Obamacare, was compiled from reputable sources:
1.	The U.S. Department of Health & Human Services (HHS), particularly sections dedicated to ACA implementation and updates and the US Census Bureau.
2.	Reports and publications from government agencies like the Centers for Medicare & Medicaid Services (CMS), oversee ACA implementation and healthcare programs.
3.	Congressional Budget Office (CBO) reports and analyses related to the ACA's fiscal impact and coverage projections.
4.	Academic research studies and analyses published in peer-reviewed journals.
5.	Qualitative data by government agencies and non-profit organizations specializing in healthcare policy and reform – The Commonwealth Fund and The National Institute for Health.

This dataset offers comprehensive insights into health insurance coverage for each state, including uninsured rates after Obamacare, estimates of individuals covered by employer and marketplace healthcare plans, and enrollment in Medicare and Medicaid programs. These combined sources provide credible information which is essential for analyzing the impact of healthcare policy changes, such as the ACA, on coverage rates and enrollment in various healthcare programs.
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
The combination of descriptive and exploratory analysis provides valuable insights into the trends, identifies the causal relationship between new policy implementation and health outcomes across various states as well as addresses pertinent questions:

🔑 How has the Affordable Care Act changed the rate of citizens with health insurance coverage? 

🔑 Which states observed the greatest decline in their uninsured rate? 

🔑 Did those states expand Medicaid program coverage?

## Key Findings
**Significant Increase in Health Coverage:** Following the implementation of the ACA, a significant increase in health insurance coverage was seen. Specifically, approximately 20 million more individuals obtained health insurance coverage nationwide within five years demonstrating the ACA's substantial impact on coverage rates.
In 2016, the total enrollment in Medicare was 56 million and total employer healthcare coverage was 172 million, which offers a broader context to the positive impact of ACA in increasing health coverage.

**State-specific Reduction in Uninsured Rates:** The states below showed the most significant decrease in the percentage of uninsured residents reflecting the ACA's effectiveness in expanding coverage. Specifically, Nevada experienced the greatest decline in uninsured individuals between 2010 to 2015 with a percentage decrease of 10.30%. Other states with the reduction include Oregon, California and Kentucky.

  ![ACA_Significant Reductions](https://github.com/TianaFash/Impact-of-the-Affordable-Care-Act-on-Coverage-A-Five-Year-Post-Implementation-Analysis/assets/166267039/157f552a-6960-43e9-8763-434dfe569f2b)

**Impact of Medicaid Expansion Program**
- Out of the fifty states in the US and the District of Columbia, 32 states expanded their Medicaid programs to cover individuals with limited income and resources at a certain threshold level. 
- 17 million individuals were enrolled in the Medicaid program between 2013 to 2018.
- Many States that have expanded Medicaid have experienced a notable reduction in uninsured rates among their populations except Florid. The data suggests that there is a strong correlation between the expansion of the Medicaid program and the decline in the number of uninsured individuals, conversely, states with non-expanded Medicaid programs have a high number of uninsured individuals.
  
![ACA_Highest Uninsured Rate_2010_2015](https://github.com/TianaFash/Impact-of-the-Affordable-Care-Act-on-Coverage-A-Five-Year-Post-Implementation-Analysis/assets/166267039/8f6162f1-8a5c-49d2-8eba-6080c15c174c)

**Highest Marketplace Insurance**

Florida leads in Marketplace health insurance coverage, providing coverage to over 1.5 million individuals. Following closely, California tops with approximately 1.4 million individuals covered, trailed by Texas with 1.1 million, North Carolina with 545 thousand, and Georgia with 478 thousand individuals covered, respectively. The data suggests that a significant number of people in these states are utilizing the ACA marketplace for their health insurance.

![image](https://github.com/TianaFash/Impact-of-the-Affordable-Care-Act-on-Coverage-A-Five-Year-Post-Implementation-Analysis/assets/166267039/0f9111e3-b12c-4d2b-8878-962468d64a2d)

## The Final Dashboard

![image](https://github.com/TianaFash/Impact-of-the-Affordable-Care-Act-on-Coverage-A-Five-Year-Post-Implementation-Analysis/assets/166267039/76c68da1-2074-442e-a350-8ed28377e9c1)

## Recommendations
**Continue Medicaid Expansion**: States that have not yet expanded Medicaid should consider doing so, as the data indicates that expansion is associated with positive outcomes in reducing uninsured rates.

**Data-Driven Policy Making**: Policymakers should employ data-driven approaches when crafting health care policy to ensure decisions are informed by the actual impacts of previous legislation like the ACA.

**Further Research Studies**: More research is necessary to understand the causal mechanisms behind the ACA's impact. Longitudinal studies could provide deeper insights into how health outcomes and access to care have changed over time as a result of the ACA.

**Monitor and Adapt**: Health insurance markets are dynamic, and as new data becomes available, continuous monitoring and adaptation of policies will be crucial to address emerging challenges and maintain the gains in coverage.

**Increase Public Awareness**: Efforts should be made to increase public awareness about the benefits of health insurance coverage and the options available through the ACA, especially in states with high numbers of uninsured individuals.

**Address Coverage Gaps**: Identify and implement targeted strategies to address persistent coverage gaps, ensuring that vulnerable populations, including those with low income or pre-existing conditions, receive adequate coverage.

By following these recommendations, states and federal policymakers can work towards sustaining and improving the gains made in health insurance coverage, ultimately leading to a healthier population with better access to necessary medical care.

## Conclusion
The Affordable Care Act (ACA) has had a significant impact on the health insurance landscape in the United States. The descriptive analysis of the data reveals a substantial increase in overall health insurance coverage, with 20 million more individuals insured from 2010 to 2015. Additionally, Medicaid enrollment surged by 17 million from 2013 to 2016. The exploratory analysis suggests a strong correlation between states that expanded Medicaid and those that saw the largest decreases in uninsured rates. States like Washington, Colorado, Arkansas, and several others not only experienced significant reductions in their uninsured population but also took the proactive step to expand Medicaid coverage, which likely contributed to these outcomes.

---

#### Thank you for taking the time to explore this project😄. Your interest and attention are truly appreciated. Should you have any insights or suggestions to enhance this project, I am eager to engage and exchange ideas with you. I am genuinely looking forward to hearing your perspectives and collaborating further on similar projects.


  
