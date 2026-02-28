# Command: /customs:hts-classification

Generate a tariff classification analysis for an imported product.

## Output Format
```
HTS CLASSIFICATION WORKSHEET
Date: [date] | Broker: [name]
Product: [description]

PRODUCT ANALYSIS:
Material: [composition]
Function: [primary use]
Country of Origin: [country]

CLASSIFICATION:
HTS Code: [10-digit code]
Description: [tariff description]
Duty Rate: [X]% ad valorem
Section 301: [Y/N, additional rate if applicable]
AD/CVD: [Y/N, case number if applicable]

GRI APPLIED: [which GRI rule(s) and rationale]

FTA ELIGIBILITY:
☐ USMCA – Origin criterion: [A/B/C/D]
☐ GSP – Qualifying country: [Y/N]
☐ Other: [specify]

ESTIMATED DUTY: $[X] (value: $[X] × rate: [X]%)
```
