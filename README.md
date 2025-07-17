# megaline-tariff-analysis
Data analysis &amp; statistical testing of Megaline prepaid tariffs
# Telecom Tariff Revenue Analysis – Megaline

## Overview

This project presents a preliminary data analysis for the telecom operator **Megaline**, which offers two prepaid plans: **Surf** and **Ultimate**. The commercial department wants to determine which plan generates more revenue, to better allocate the advertising budget.

You will analyze data from 500 Megaline clients, including demographic information, plan type, and usage behavior (calls, messages, and data consumption) over the year 2018.

## Objective

The goal is to identify which plan, on average, brings more revenue to the company by analyzing client behavior and applying statistical hypothesis testing.

## Dataset

The dataset contains:

- Client ID and location
- Assigned plan (Surf or Ultimate)
- Number of calls and total minutes used per month
- Number of text messages sent per month
- Amount of internet data used per month (in MB)

### Tariff Details

**Surf Plan**  
- Monthly fee: $20  
- Includes: 500 min, 50 SMS, 15 GB  
- Extra usage fees:  
  - $0.03 per extra minute  
  - $0.03 per extra SMS  
  - $10 per extra GB  

**Ultimate Plan**  
- Monthly fee: $70  
- Includes: 3000 min, 1000 SMS, 30 GB  
- Extra usage fees:  
  - $0.01 per extra minute  
  - $0.01 per extra SMS  
  - $7 per extra GB  

> Note: Call durations are rounded **up to the nearest minute per call**, and total monthly data usage is **rounded up to the nearest GB**.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- SciPy (for statistical tests)
- Jupyter Notebook
