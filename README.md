# Economic Impact of COVID-19 on Dhaka Rickshaw Pullers

**Primary research · Economics · Data analysis**

An independent field study examining how the COVID-19 pandemic affected the income, expenses, health, and day-to-day livelihoods of rickshaw pullers in Dhaka, Bangladesh.

## Research question

> To what extent has COVID-19 impacted the livelihood of rickshaw-pullers in Dhaka, Bangladesh?

## Why this project stands out

This was not only a literature-based economics paper. The study collected **primary interview data from 90 rickshaw pullers** across **Dhanmondi, Malibagh, and Mirpur** in March 2021, then combined that evidence with economic theory and secondary research.

The original investigation covered:

- before/after income and expense ranges;
- a six-month series of monthly average income and expenses;
- regression analysis of income and expenditure;
- physical and mental-health observations;
- poverty-trap and informal-economy context;
- policy and social-protection discussion;
- explicit limitations of the data and methodology.

## Quantitative analysis

The original paper modeled monthly expenses as a function of monthly income using six monthly aggregate observations from October 2020 through March 2021.

Reported in the original submission:

- **R²:** approximately **0.98**
- **Regression equation:** `Expenses = 0.71 × Income - 795.867`
- **Standard error:** approximately **64.4**

These statistics are preserved as results from the historical paper. See [methodology and limitations](docs/methodology-and-limitations.md) for important context about self-reported values, grouped data, sampling, and the small regression series.

## Primary research scope

| Area | Interviews |
| --- | ---: |
| Dhanmondi | 30 |
| Malibagh | 30 |
| Mirpur | 30 |
| **Total** | **90** |

The questionnaire included questions on work patterns, rickshaw ownership/rent, income, expenses, health, COVID-19 awareness, PPE, loans, treatment access, and perceived pandemic impacts.

## Selected data

The repository includes cleaned transcriptions of selected tables from the paper:

- [`data/monthly-income-expenses.csv`](data/monthly-income-expenses.csv) — six-month income/expense series used for the regression discussion.
- [`data/interview-summary.csv`](data/interview-summary.csv) — selected grouped before/after income and expense ranges.

## Repository structure

```text
.
├── README.md
├── NOTICE.md
├── data/
│   ├── interview-summary.csv
│   └── monthly-income-expenses.csv
└── docs/
    ├── Economic-Impact-of-COVID-19-on-Dhaka-Rickshaw-Pullers.pdf
    ├── methodology-and-limitations.md
    ├── paper-guide.md
    └── SHA256SUM.txt
```

## Read the original work

- [Original 4,000-word paper](docs/Economic-Impact-of-COVID-19-on-Dhaka-Rickshaw-Pullers.pdf)
- [Methodology and limitations](docs/methodology-and-limitations.md)
- [Paper guide](docs/paper-guide.md)

## Skills demonstrated

**Research:** survey design, primary data collection, interviewing, source synthesis  
**Analytics:** regression analysis, descriptive analysis, data interpretation, data visualization  
**Economics:** informal economy, household income and expenditure, poverty, demand, policy evaluation  
**Communication:** research writing, evidence-based argument, limitations and uncertainty

## Project context

This project originated as an IB Economics Extended Essay completed during the COVID-19 pandemic. It is presented here retrospectively as an early example of my interest in using data to understand real economic and human problems.

The original submission is preserved rather than rewritten. The accompanying documentation adds current context where the original methodology should be interpreted cautiously.
