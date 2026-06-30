# The Analysis

## 1. What are the most in demand skills for the jobs we are looking at?

I chose to filter the top 5 most in demand skills for each of my three positions. It is worth noting that Machine Learning Engineers had significantly less postings than the other 2 positions, likely due to it being a relatively new position in most companies.

View my notebook with the detailed steps on this here: [Skills_count.ipynb](Project/Skills_count.ipynb)


### Results

![Visualisation of top skills for our jobs](Project/Figures/skills_required.png)

*Bar graph visualising the salary for data analyst, data scientist and machine learning engineer roles and their top 5 skills associated with each*

### Insights

- SQL is an essential skill across all three roles, being the most in-demand skill for both Data Analysts and Data Engineers, and the second most in-demand skill for Data Scientists.

- Python features in at least 30% of job postings for all three roles, increasing to over 50% for both Data Scientists and Data Engineers. It is the single most requested skill for Data Scientists.

- Data Analyst roles focus more on data manipulation and presentation tools like Power BI and Excel, whereas Data Scientist and Data Engineer roles prioritise programming languages and cloud technologies, with Python, SQL, Azure and AWS featuring prominently.

-Data Scientists and Data Engineers share a much more similar technical skill set than either does with Data Analysts. Four of their top five skills (Python, SQL, Azure and AWS) overlap, whereas Data Analysts uniquely require business intelligence and spreadsheet tools such as Excel, Power BI and Tableau.

## 2. How are in-demand skills trending for our jobs?

To find how these skills were trending, I filtered my data into 3 separate dataframes for my 3 separate job roles and plotted this data on a quarterly basis from the start of 2023 to
the end of 2025.

View my notebook with the detailed steps on this here: [skills_distribution.ipynb](Project/skills_distribution.ipynb)

## 2.1 Data Analysts

### Results

![Visualisation of the demand of top skills for Data Analysts](Project/Figures/top_skills_DA.png)

*Line graph visualising the trending top skills for data analysts in the UK from 2023 to 2025*

### Insights

- Apart from Tableau, the four most requested skills all declined in demand from Q2 2024 until Q1 2025, before rising sharply to a peak in Q3 2025. 

- SQL is consistently the most in-demand skill for UK Data Analysts, appearing in the highest proportion of job postings in every quarter analysed.

- Python exhibits the strongest long-term growth in demand. Aside from the broad decline observed between Q3 and Q4 2025 across several skills, Python's demand remains comparatively stable from quarter to quarter.

- Through 2023 and 2024, Excel showed a gradual decline in demand. Although demand recovered during 2025, the gap between Excel and emerging tools such as Python and Power BI narrowed considerably over the three-year period.

- Tableau doesn't exhibit the same cyclical behaviour as our other skills. It's demand remains stable and it doesn't experience the pronounced Q3 2025 spike seen with other skills.

## 2.2 Data Scientists

### Results

![Visualisation of the demand of top skills for Data Scientist](Project/Figures/top_skills_DS.png)

*Line graph visualising the trending top skills for data scientists in the UK from 2023 to 2025*

### Insights

- Python, SQL and R all generally declined in demand throughout 2023 and 2024. Python experienced its largest drop in Q3 2024, while R during Q4 2024.

- Python remained by far the most in-demand skill, appearing in over 50% of postings across all 12 quarters. Although demand never returned to its peak of ≈ 70%, it displayed steady growth throughout 2025, ending at nearly 60% in Q4.

- SQL showed a more gradual decline than Python and appeared in over 40% of job postings during eight of the twelve quarters analysed. The gap between Python and SQL narrowed from approximately 24 percentage points in Q1 2023 to around 16–18 percentage points by Q4 2025.

- R exhibited a gradual downward trend throughout the three-year period. Unlike Python and SQL, which recovered during 2025, R continued to decline and ended only marginally ahead of Azure, suggesting that Azure may become more prevalent if these trends continue.

- Azure was the only one of the five skills to finish 2025 above its Q1 2023 level. Both Azure and AWS both displayed the most stable figures of the five skills.

## 2.3 Machine Learning Engineers

### Results

![Visualisation of the demand of top skills for Data Engineers](Project/Figures/top_skills_DE.png)

*Line graph visualising the trending top skills for data engineers in the UK across from 2023 to 2025*

### Insights

- The ranking of the five most in-demand skills remains highly consistent throughout the three-year period. SQL and Python dominate demand in every quarter, only briefly exchanging first place during Q3 2024 and Q2 2025. Neither skill establishes a sustained lead over the other.

- Databricks shows the clearest long-term increase, rising from roughly 15% of postings in early 2023 to around 23% by the end of 2025. Although still the least requested of the five skills, its demand increases gradually over the period.

-Overall, the required technical skill set for Data Engineers remains remarkably stable over the three-year period, suggesting that employer demand for the core technologies associated with the role changed relatively little between 2023 and 2025.

## 3. How well do our three roles pay?

To compare the salary distributions of the three selected job roles, box plots were used. Box plots provide a clear visual summary of the median salary, interquartile range (IQR), and any potential outliers, making them well suited for comparing salary distributions across multiple groups.

Before constructing the plots, rows containing missing values (NaN) in the salary_year_avg column were removed. Since these entries do not contain salary information, including them would not contribute to the analysis and could affect the accuracy of the results.

View my notebook with the detailed steps on this here: [job_salaries.ipynb](Project/job_salaries.ipynb)

### Results

![Visualisation of salary distributions for our three roles](Project\Figures\salary_boxplots.png)

*Box plots visualising the salaries for our three job roles*

### Insights

- Data Engineers recorded the highest median salary, approximately £38k higher than that of Data Scientists. The role also exhibited several outliers exceeding £200k, suggesting that senior or highly specialised positions can command substantially higher salaries than the typical advertised role.

- Data Scientists and Data Analysts shared identical lower quartile and median salaries, indicating that a large proportion of advertised salaries were concentrated at the lower end of their respective salary distributions.

- Data Analysts exhibited the narrowest interquartile range (IQR), implying that the middle 50% of advertised salaries were more consistent than those of the other two occupations.

- All three roles contain high-salary outliers, although these are considerably more pronounced for Data Engineers. This suggests that exceptional salaries are possible across the data profession, but are more common in engineering-focused roles.

## 4 What are the most optimal skills to learn for data roles?









