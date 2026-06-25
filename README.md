# The Analysis

## 1. What are the most in demand skills for the jobs we are looking at?

I chose to filter the top 5 most in demand skills for each of my three positions. It is worth noting that Machine Learning Engineers had significantly less postings than the other 2 positions, likely due to it being a relatively new position in most companies.

View my notebook with the detailed steps on this here: [Skills_count.ipynb](Project\Skills_count.ipynb)


### Results

![Visualisation of top skills for our jobs](Project\Figures\Skills_Required.png)

### Insights

- Python is extremely in demand for Data Scientists and , especially, Machine Learning Engineers, featuring in 53% and 67% of postings respectively. While not as prevalent, it still features in just under a third of postings for Data Analysts.

- SQL features in the top 3 most wanted skills for all 3 jobs and is the most in demand skill for Data Analysts, although this is quite closely followed by Excel, Power BI and Python.

- Each job role is more likely to require skills based on: 
    - Visualisation and cleaning of data - Power BI, Tableau (Data Analysts)
    - Cloud Technology - AWS, Azure (Data Scientists)
    - Machine Learning libraries - Pytorch, Tensorflow (Machine Learning Engineers)

## 2. How are in-demand skills trending for our jobs?

To find how these skills were trending, I filtered my data into 3 separate dataframes for my 3 separate job roles and plotted this data on a quarterly basis from the start of 2023 to
the end of 2025.

View my notebook with the detailed steps on this here: [skills_distribution.ipynb](Project\skills_distribution.ipynb)

## 2.1 Data Analysts