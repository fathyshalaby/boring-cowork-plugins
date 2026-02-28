# Command: /agronomist:yield-estimate

Generate a pre-harvest yield estimate based on field measurements.

## Required Input
Crop-specific measurements (e.g., for corn: ear count, kernel rows, kernels per row; for soybeans: pod count per plant, seeds per pod)

## Output Format
```
PRE-HARVEST YIELD ESTIMATE
Field: [name] | Crop: [crop] | Acres: [X]
Date: [date] | Growth Stage: [stage]
Estimated Harvest: [date]

FIELD MEASUREMENTS:
Sample   Location    [crop-specific measurements]    Est. Yield
──────────────────────────────────────────────────────────────
1        [GPS]       [measurements]                  [X] bu/ac
2        [GPS]       [measurements]                  [X] bu/ac
3        [GPS]       [measurements]                  [X] bu/ac
4        [GPS]       [measurements]                  [X] bu/ac
5        [GPS]       [measurements]                  [X] bu/ac

FIELD AVERAGE: [X] bu/acre ± [X] bu (std dev)
TOTAL ESTIMATED PRODUCTION: [X] bushels

METHODOLOGY:
[Describe the yield estimation formula used]

RISK FACTORS THAT COULD AFFECT FINAL YIELD:
• [Early frost risk, remaining moisture needs, disease progression]

MARKETING IMPLICATIONS:
[Comparison to APH yield, crop insurance guarantee, and forward contracts]
```
