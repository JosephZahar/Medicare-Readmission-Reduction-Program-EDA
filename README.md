<img alt="Plotly" src="https://img.shields.io/badge/Plotly-3F4F75?logo=Plotly&logoColor=white&style=flat" /> <img alt="Python" src="https://img.shields.io/badge/Python%20-%2314354C.svg?style=flat-square&logo=python&logoColor=white" /> <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white&style=flat" /> 

# Medicare Readmission Reduction Program EDA
Starting in October 2012, Medicare began penalizing hospitals who had excess readmissions for each of the six readmission measures (AMI, CABG, COPD, HF, HIP-KNEE replacement, PN) reported in the Hospital Readmission Reduction Program data (more background [here](https://www.cms.gov/medicare/medicare-fee-for-service-payment/acuteinpatientpps/readmissions-reduction-program.html) and [here](http://files.kff.org/attachment/Issue-Brief-Fewer-Hospital-U-turns-The-Medicare-Hospital-Readmission-Reduction-Program)).

For each of the six readmission measures (AMI, CABG, COPD, HF, HIP-KNEE replacement, PN) reported in the Hospital Readmission Reduction Program data, what is the distribution of the excessive readmission ratio by key hospital characteristics (for example, by hospital type, hospital ownership, and state)? Using visualizations and statistical tests, are there any significant differences in each readmission rate by key hospital characteristics? 

Data: the most recent data can be downloaded from Hospital Compare.

<br>

<p align="center">
<img src="https://github.com/JosephZahar/Medicare-Readmission-Reduction-Program-EDA/assets/70657426/921a76a2-f8b3-40c5-8361-8ce824a53032" />
</p>

## Table of Contents
- [Overview](#overview)
- [Primary Task Description](#Primary-Task-Description)
- [Important Relevant Terms](#Important-Relevant-Terms)

## Overview
In the autumn of 2012, a significant shift occurred in the healthcare landscape. Medicare, a major player in the health sector, decided to hold hospitals accountable for their patient readmissions (HRRP) by introducing penalties for hospitals that saw too many of their patients returning 30 days after discharge. With a focus on six specific conditions, a question emerged: How do these readmission rates vary across hospitals with different characteristics? Are higher rated hospitals faring better than low rated ones? Does ownership play a role? And are there states that stand out, for better or worse? 

## Primary Task Description
In this study, we will systematically analyze the data, employing visualizations and statistical tests to mine the patterns and correlations between readmission rates and various hospital characteristics.

## Important Relevant Terms
- CABG: Coronary Artery Bypass Graft
- AMI: Acute Myocardial Infarction
- COPD: Chronic Obstructive Pulmonary Disease
- HF: Heart Failure
- HIP-KNEE replacement: Total Hip/Knee Arthroplasty
- PN: Pneumonia
- HRRP: Hospital Readmissions Reduction Program

## Data Sources

For hospitals with excess readmissions under the Hospital Readmissions Reduction Program (HRRP):
- Data from Hospital Readmissions Reduction Program (HRRP): [https://data.cms.gov/provider-data/dataset/9n3s-kdb3](https://data.cms.gov/provider-data/dataset/9n3s-kdb3)

For hospitals characteristics
- Data on General Hospital Information (GHI): [https://data.cms.gov/provider-data/dataset/xubh-q36u](https://data.cms.gov/provider-data/dataset/xubh-q36u)

