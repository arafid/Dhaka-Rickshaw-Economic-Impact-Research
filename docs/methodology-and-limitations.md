# Methodology and limitations

## Original research design

This project began as a 4,000-word IB Economics Extended Essay asking:

> To what extent has COVID-19 impacted the livelihood of rickshaw-pullers in Dhaka, Bangladesh?

The original study collected primary data from **90 rickshaw pullers**: 30 in Dhanmondi, 30 in Malibagh, and 30 in Mirpur. Interviews were conducted on March 12-14, 2021 using a questionnaire covering work patterns, income, expenses, health, COVID-19 awareness, PPE use, borrowing, and perceived changes during the pandemic.

The paper combined those interviews with secondary sources on Bangladesh's informal economy, poverty, health, and COVID-19 policy impacts.

## Quantitative work in the original paper

The paper summarized before/after income and expense ranges and constructed a six-month series of average monthly income and expenses from October 2020 through March 2021.

It then used a linear regression with monthly income as the independent variable and monthly expenses as the dependent variable. The original paper reported:

- Multiple R: approximately 0.9904
- R-squared: approximately 0.9809
- Standard error: approximately 64.4
- Fitted equation: `Expenses = 0.71 × Income - 795.867`

These are historical results reported in the original submission and are preserved for transparency; this repository does not present them as independently revalidated causal or predictive estimates.

## Important retrospective limitations

1. **Self-reported financial data.** Income and expense values were recalled by interviewees rather than taken from transaction records. The original paper itself notes that the figures should be treated as estimates rather than exact measurements.
2. **Grouped and reconstructed values.** Some monthly averages were derived from the means of grouped ranges. This limits precision.
3. **Small regression series.** The regression uses six monthly aggregate observations, so a high R-squared should not be interpreted as broad predictive validity.
4. **Sampling scope.** The 90 interviews came from three Dhaka areas selected for high rickshaw activity. The sample is useful for the investigation but is not a probability sample of every rickshaw puller in Dhaka.
5. **Mental-health measurement.** The original paper explicitly notes that mental strain cannot be professionally diagnosed from the interview process used.
6. **Pandemic timing.** The study captures a specific period of the COVID-19 shock. Conditions, restrictions, aid, and labor-market behavior changed rapidly.
7. **Causality.** The study documents patterns and reported changes during COVID-19; it does not establish that every observed change was caused solely by the pandemic.

## Why keep this project public

The value of the project is not that every early analytical choice would be made the same way today. Its value is the end-to-end research process: framing a question, designing interviews, collecting original data, organizing evidence, applying quantitative analysis, interpreting findings, and documenting limitations.
