# USAID-Funding-Cut-Analysis
This project analyzes the official USAID funding cut document released by the U.S. government. The analysis highlights the key sectors and vendors most affected, along with insights into the broader impact of these funding reductions. Visualizations and data transformations were created to make the findings clear and actionable.

##Background To The Analysis
On January 20, President Donald Trump sanctioned a 90-day halt on foreign aid, a decision that affected all financial support distributed by the United States Agency for International Development (USAID). On the 10th of March, Majority of the USAID funded programs were cut down. 

## Dataset
The dataset used for this analysis was a pdf document that contained all of the programs runned by USAID. It had a list of the terminated contracts and the active contracts

## Data Cleaning and Transformation
Due to the nature and form of the dataset, I had to do some data transformation and cleaning to ensure the dataset was usable for analysis sake. 
  1. The dataset was loaded on Power BI.
  2. The dataset was then loaded to power query for data transformation.
  3. I extracted the data I needed from the pdf by pages
  4. Then the ones that didn't work with  pages, I extracted by tables.
  5. I removed irrelevant columns to the analysis
  6. I also created new columns with conditional column formatting (Project status...)
  7. Once my data was cleaned and ready to use, I loaded it back to my powerBI.

## Creation of Measures
 
1.	Percentage of terminated contract
2.	Percentage of total contract
3.	Total active contracts
4.	Total Active Vendor
5.	Total contract awarded
6.	Total estimated cost
7.	Total Number of vendors
8.	Total obligated cost
9.	Total contracts total terminated vendor

## Creation of Columns
1.	Contract Period (This was derived by getting the difference in year between the contract start date and the expected end date)
2.	Cost Saved (The difference in estimated cost and obligated cost)
3.	Contract Duration (I did a grouping of contract periods to enable better visualization)
4.	Project Status (This was to show the status of the projects as at when the policy came up . I grouped to ongoing and completed)

## Insights and Recommendations
1.	86% of all of USAID contracts were terminated.
2.	Out of the estimated cost totaling about $153bn, only about $118bn has been obligated
3.	As at 24th of January, only 37 of USAID contracts duration were completed. this accounted for less than 1% of all it's project.
4.	United Nations World Food Program is the vendor with the highest amount of contracts closely followed my Chemonics.  
5.	USAID retained all of the 140 contracts handled by United Nations World Food Programs. This is an indication for it's commitment in solving world food problem.
6.	2024 is the year USAID awarded the highest number of contracts totaling 2332
7.	A total of 14 vendors resulted to an overshoot of it's initial estimated cost. This resulted to an additional cost of $79.8mn
8.	The international bank for reconstruction and development is the highest funded project by USAID.
