# Bank marketing campaigns analysis
#### by Jyoti K


## Dataset

We will be analyzing [Bank marketing campaigns dataset](https://www.kaggle.com/volodymyrgavrysh/bank-marketing-campaigns-dataset#bank-additional-full.csv) which is publicly available on Kaggle. This dataset describes Portugal bank marketing campaigns results. Conducted campaigns were based mostly on direct phone calls, offering bank client to place a term deposit. If the client says yes to opening the term deposit account, the target variable `'y'` is marked as 'yes', else 'no'.

Sourse of the data:
https://archive.ics.uci.edu/ml/datasets/bank+marketing

<br>

## Summary of Findings

> - We noticed that when euribor 3 month rate is less than 2, success rate of the campaign increases to 24.46%. This is significant increase from 11.3% success rate in overall data.
- Number of calls placed when euribor is less than 2 are half of those place when euribor is 2 or more. This is a very significant difference in numbers and highlights an area where we can work upon to get more positive results.
- Statistically, 22.93% of young people(upto age 60) open term deposits when euribor < 2. This is more than the average of 10.49% over the whole dataset for the same age group. Therefore, we can conclude that clients upto 60 years of age open considerably higher percentage of accounts when euribor 3 month rate is less than 2. However, clients with more than 60 years of age, follow almost the same trend as in overall data.

<br>

## Key Insights for Presentation

> - We observed that when euribor 3 month rate is less than 2, clients under the age of 60 are twice more likely to open a term deposit. We should noticed that bank called only half the number of customers when euribor was less than 2 as compared to otherwise. So, we should target to call more customers during this period for better success rate. 
- In overall data, [students and retirees](#job-prop) are much more likely to open term deposit. [45%](#above_60) of clients above 60 years of age agreed to open term deposit. But we have only [2.5%](#age-distribution) of customers in this range. It is recommended to include more of students, retirees and clients older than 60 years of age to get a better success rate in overall dataset.
- Clients for whom previous campaign outcome was successful, agreed to [65%](#p-poutcome) of the calls. This is significant figure and can be used to target customers in further campaigns.

<br>


## Software used
- Jupyter Notebook
- Python 3.7
    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn

<br>

## Pre-requsites:
> - pip install pandas
> - pip install seaborn
> - pip install matplotlib
