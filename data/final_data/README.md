# Final Merged Dataset
After cleaning and merging our datasets, we used this final csv file for all our analysis. How we arrived at this final dataset is described below.
 
**Merged & Cleaned University Rankings**

To successfully merge these datasets, we renamed the Institution Name column from our first data source to School Name to match the second dataset. We also began cleaning the data by stripping any spacing on the School Name data values and removing any abbreviations in parentheses from the Kaggle dataset. This approach maximized the number of matching school names when performing our join. After correcting data types and merging our two datasets we were left with a data frame consisting of 125 rows and 21 columns.  

We recognized there were still many insignificant columns, so we dropped School Type, Academic Reputation Rank, Employer Reputation Rank, Faculty Student Rank, Employment Outcomes Rank, Sustainability Rank, Sustainability Score.  

Originally, we merged the two datasets using an inner join on ‘School Name.’ We manually mapped additional schools that had similar names but different formatting to get to a final count of 182 rows and 14 columns. 

