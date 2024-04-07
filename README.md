# Impact of the Affordable Care Act (ACA) on Coverage: A-Five-Year-Post-Implementation-Analysis
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

