# banking

# About the Project

My goal is to identify characteristics for marketing analysis for individuals in banking clients.


# Project Goals
The goals for this project are to answer initial questions, and analyze the characteristics for banking clientele for marketing purposes. Business goals include which demographic of individuals to create marking improvements on.


### Initial Questions

- What is the relationship between clients and marital status?
- What is the relationship between clients and job?
- What is the relationship between x and y
- 

### Data Dictionary


| Variable    | Meaning     |
| ----------- | ----------- |
| age | age of individual (numeric)|
| job | type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services") |
| marital | marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed) |
| education | (categorical: "unknown","secondary","primary","tertiary")|
| default | has credit in default? (binary: "yes","no") |
| balance | average yearly balance, in euros (numeric) |
| housing | has housing loan? (binary: "yes","no") |
| loan    | has personal loan? (binary: "yes","no") |
| contact | contact communication type (categorical: "unknown","telephone","cellular") |
| day | last contact day of the month (numeric) |
| month | last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec") |
| duration | last contact duration, in seconds (numeric) |
| campaign | number of contacts performed during this campaign and for this client (numeric, includes last contact) |
| pdays | number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted) |
| previous | number of contacts performed before this campaign and for this client (numeric) |
| poutcome | outcome of the previous marketing campaign (categorical: "unknown","other","failure","success") |





## Steps to Reproduce

- Save CSV files for test/train locally. (test.csv, train.csv)
- Clone my repo (including an acquire.py and prepare.py) (confirm .gitignore is hiding your env.py file)
- Libraries used are pandas, matplotlib, seaborn, numpy, sklearn.
- Document conclusions, takeaways, and next steps in the Final Report Notebook.

## Plan

-