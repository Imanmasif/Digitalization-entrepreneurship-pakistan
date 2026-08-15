# Econometric Methodology

## Outcome variable

Entrepreneurial engagement is binary. The paper classifies an individual as an entrepreneur when engaged as an employer or self-employed in a non-agricultural sector; otherwise the outcome is coded as non-entrepreneur.

## Logistic model

The study uses binary logistic regression because the dependent variable is binary. The specification includes:

- Mobile access
- Computer access
- Internet connectivity
- Province
- Rural/urban region
- Gender
- Age
- Education
- Household income

The paper expresses the model as a logit of the probability of entrepreneurial engagement and reports exponentiated coefficients as odds ratios.

## Variable coding reported in the paper

| Variable | Role | Coding / measurement |
| --- | --- | --- |
| Entrepreneur | Dependent | 1 = employer or non-agricultural self-employed; 0 = otherwise |
| Mobile Access | Main predictor | 1 = yes; 0 = no |
| Computer Access | Main predictor | 1 = yes; 0 = no |
| Internet Connectivity | Main predictor | 1 = yes; 0 = no |
| Province | Control | Khyber Pakhtunkhwa, Punjab, Sindh, Balochistan |
| Region | Control | Rural / Urban |
| Gender | Control | Male / Female |
| Age | Control | Completed years |
| Education | Control | Scale from 0 to 21 in the paper |
| Household Income | Control | Household earnings, modelled in logarithmic form |

## Model structure

```text
Entrepreneurial engagement
        ↑
Mobile + Computer + Internet
        +
Province + Region + Gender
        + Age + Education + Income
        ↓
Binary logistic regression
        ↓
Odds ratios and statistical significance
```

## Interpretation

An odds ratio above 1 indicates higher odds of entrepreneurial engagement associated with the predictor, while an odds ratio below 1 indicates lower odds, holding the other variables in the model constant.

The study is cross-sectional. The coefficients therefore describe statistical associations and do not establish causality.
