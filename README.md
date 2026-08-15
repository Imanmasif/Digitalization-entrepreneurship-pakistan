# Digitalization and Entrepreneurial Engagement in Developing Economies

**Evidence from Pakistan | IEEE IMCOM 2026 | Research paper companion repository**

## Overview

This repository accompanies the paper **Digitalization and Entrepreneurial Engagement in Developing Economies Based on Evidence from Pakistan**, presented at the 2026 20th International Conference on Ubiquitous Information Management and Communication (IMCOM).

The study examines whether access to digital technologies is associated with entrepreneurial engagement in Pakistan's non-agricultural sector. It focuses on three forms of digital access — mobile phones, personal computers, and internet connectivity — and examines how their relationships with entrepreneurship vary across gender and rural/urban settings.

The repository is intended as a research companion to the published paper. It documents the study design, data source, econometric approach, key findings, and limitations. It does not claim to contain the original survey microdata or the original statistical analysis code.

## Research question

The central question is how different forms of digital access relate to the likelihood of entrepreneurial engagement in Pakistan, and whether those relationships differ across demographic and geographic groups.

Rather than treating digitalization as a single measure, the study separates mobile, computer, and internet access so their distinct relationships with entrepreneurship can be examined.

## Data

The research uses the **Pakistan Social and Living Standards Measurement (PSLM) Survey 2020–2021**, made available by the Pakistan Bureau of Statistics (PBS). The analysis focuses on the non-agricultural sector and uses a final sample of **192,670 individuals**.

The paper reports the following descriptive characteristics for the analytical sample:

- 26.2% are classified as entrepreneurs
- 77.1% have mobile access
- 8.8% have personal computer access
- 25.1% have internet access
- 66.0% of the sample is rural
- 15.1% of the sample is female

The underlying survey microdata are **not included in this repository**. Users should obtain any data directly from the appropriate official source and comply with its access conditions and terms of use.

## Methodology

The study models entrepreneurial engagement as a binary outcome and uses **binary logistic regression**. The main explanatory variables are mobile access, computer access, and internet access, with controls including province, region, gender, age, education, and household income.

Five model specifications are discussed in the paper, including separate models for the main digital-access measures and models examining their combined effects.

The logistic formulation allows the results to be interpreted using odds ratios, making it possible to compare how different forms of digital access are associated with entrepreneurial engagement while accounting for relevant individual and regional characteristics.

Detailed methodology: [Econometric Methodology](methodology/logistic-regression.md) | [Model Specification](methodology/model-specification.md)

## Main findings

The analysis identifies different relationships for different forms of digital access.

### Mobile access

Mobile access has the strongest positive association with entrepreneurship. In the baseline specification, the reported odds ratio is **1.968**, corresponding to approximately **96.8% higher odds** of entrepreneurial engagement among individuals with mobile access, holding the other model factors constant.

### Computer access

Computer access shows a statistically significant negative association with entrepreneurship. The reported odds ratio in the corresponding model is **0.546**, indicating approximately **45.4% lower odds** of entrepreneurial engagement relative to those without computer access in that specification.

The paper discusses the possibility that computer access is more closely associated with formal employment, education, and administrative activities than with informal or self-directed enterprise.

### Internet access

Internet access has a positive but more modest association with entrepreneurship. The paper reports stronger effects in rural settings than in urban settings and a clear difference between male and female respondents.

For example, internet access is associated with an odds ratio of **1.244** in the rural subgroup and **1.198** among male respondents. For female respondents, the reported odds ratio is **0.712**, highlighting a substantial gender difference in the relationship between connectivity and entrepreneurial engagement.

These results are associations from cross-sectional survey data and should not be interpreted as proof of causal effects.

## Gender and regional differences

A major part of the study is its heterogeneity analysis. The results indicate that digital access does not translate into entrepreneurial opportunity equally across all groups.

The paper reports positive associations for mobile access across all reported subgroups. Internet access is positive in the overall, rural, urban and male models but has a reported odds ratio below 1 in the female subgroup. These differences are discussed in the context of digital skills, access to markets and finance, mobility, safety, infrastructure, and other structural barriers.

## Interpretation

Taken together, the findings suggest that **mobile connectivity is particularly important for entrepreneurial engagement in a resource-constrained environment**, while internet connectivity provides a more modest positive association. Computer access behaves differently and is negatively associated with entrepreneurship in the reported models.

The study therefore argues for digital-inclusion policies that reflect how different technologies are actually used, rather than assuming that expanding access to every type of device will produce the same economic outcome.

## Documentation

- [Research summary](docs/research-summary.md)
- [Dataset documentation](data/README.md)
- [Econometric methodology](methodology/logistic-regression.md)
- [Model specification](methodology/model-specification.md)
- [Main results](results/main-results.md)
- [Results interpretation](results/interpretation.md)
- [Study limitations](docs/limitations.md)

## Limitations

The study has several important limitations that should be kept in mind when interpreting the results:

- the analysis uses self-reported measures of digital access
- the PSLM data are cross-sectional, limiting causal interpretation
- unobserved factors may influence both digital access and entrepreneurial engagement
- the study focuses on non-agricultural economic activity
- digital access does not necessarily measure digital skills or the quality and intensity of technology use

## Repository scope

This is a **research companion repository**, not a reproduction package. The public repository documents the published study without adding fabricated code, survey microdata, or unverified numerical results. The published paper remains the primary source for the complete statistical tables, variable definitions, literature review, regression specifications, subgroup analyses, references, and discussion.

## Publication

**Digitalization and Entrepreneurial Engagement in Developing Economies Based on Evidence from Pakistan**  
Faisal Umar, Iman Muhammad Asif, Mehar Tahir Farid  
2026 20th International Conference on Ubiquitous Information Management and Communication (IMCOM), IEEE, 2026.

## Citation

```text
F. Umar, I. M. Asif, and M. T. Farid,
"Digitalization and Entrepreneurial Engagement in Developing Economies Based on Evidence from Pakistan,"
2026 20th International Conference on Ubiquitous Information Management and Communication (IMCOM), IEEE, 2026.
```

## Repository note

This repository is maintained as a research companion to the publication. The published paper remains the authoritative source for the complete statistical tables, variable definitions, literature review, regression specifications, subgroup analyses, references, and discussion.
