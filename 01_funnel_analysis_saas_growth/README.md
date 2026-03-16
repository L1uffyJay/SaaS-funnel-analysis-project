# SaaS Funnel Analysis for Growth & Revenue

This project simulates a **real B2B SaaS funnel analysis** project a business analyst might own for a growth, product, or revenue operations team.

## Business problem
A SaaS company is seeing strong top-of-funnel traffic but inconsistent free-trial and paid conversion. Leadership wants to know:

- Where users are dropping out of the funnel
- Which acquisition channels generate the best downstream conversion
- Whether device, region, or lead quality influence activation and paid conversion
- How long users take to move between stages

## Files
- `data/leads.csv` — messy CRM-style lead table
- `data/product_events.csv` — messy product event log
- `notebooks/funnel_analysis.ipynb` — end-to-end notebook
- `data_dictionary.md` — column definitions and known data quality issues
- `requirements.txt` — Python dependencies

## Why this looks realistic
The source data intentionally includes:
- missing values
- duplicated users/events
- inconsistent category labels
- mixed datetime formats
- out-of-order events
- impossible revenue values

## Suggested GitHub pitch
> Built an end-to-end SaaS funnel analysis project from messy CRM and product event data. Cleaned inconsistent source data, reconstructed funnel stages, quantified stage-by-stage conversion and time-to-convert, and identified channel and cohort drivers of paid subscription conversion.

