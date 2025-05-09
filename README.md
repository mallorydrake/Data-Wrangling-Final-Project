# BAIS:3250 Final Project
**Author(s):** Mallory Drake, Paige Turner, Luke Weeklund
 
**Description:**
In today’s competitive global job market, higher education institutions play a crucial role in shaping graduates’ career prospects and earning potential. Prospective students often consider factors such as academic reputation, global ranking, and potential future earnings when making their college choices. However, navigating through vast amounts of data to make informed decisions can be overwhelming, especially as many students move away from home for the first time. This project aims to analyze relationships between university rankings and the factors that contribute to these rankings such as graduates’ salaries, percentage of STEM majors at the university, and faculty ratings by integrating two real-world data sources.  

Through our analysis we hope to help prospective university students understand the reasons behind institutional rankings and how it will influence their financial compensation post-graduation. Not only will this information be helpful to students, but also to company hiring managers as they are looking through resumes and seeking out qualified individuals to hire. 

## Links where we found our original datasets
* **[Kaggle Dataset](https://www.kaggle.com/datasets/joebeachcapital/qs-world-university-rankings-2024/data):** The link to the Kaggle site we downloaded one of our original datasets from
* **[Scraped Dataset](https://www.payscale.com/college-salary-report/bachelors):** The link to the website we scraped our second dataset from

## Partial Data Dictionary

| Column  | Description |
| ------ | ------ |
| 2024 Rank | Overall rank of the university in 2024 |
| School Name | Name of the university |
| Country | Country where the university is located  |
| SIZE | Size of the university (S = Small, M = Medium, L = Large, XL = Extra Large) |
| AGE | Age category of the university  |
| Academic Reputation Score | Score for Academic Reputation |
| Employer Reputation Score | Score for Employer Reputation |
| Faculty Student Score | Score for Faculty-Student Ratio |
| Employment Outcomes Score | Score for Employment Outcomes |
| Overall Score | Final score determining University ranking |
| Postgrad Salary Rank | Rank for post-grad salary of alumni |
| Early Career Pay | Median salary of alumnis with 0-5 years of experience |
| Mid-Career Pay | Median salary of alumni with 10+ years of experience |
| Percent of STEM Degrees | % degrees awarded in science, technology, engineering and/or mathematics |
 
## Folders
 
### [code](code)
Contains code used for the project
* **[Jupyter_notebooks](code/Jupyter_notebooks):** sub-folder containing Jupyter notebooks (.ipynb) used for the project
 
### [data](data)
Contains data used for the project
* **[raw data](data/raw_data):** sub-folder containing the original, unclean data for the project
* **[final data](data/final_data):** sub-folder containing the final, cleaned data for the project
 
### [results](results)
Folder where our final report and conclusions is stored

