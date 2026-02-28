# Command: /agronomist:pest-risk-model

Generate a pest risk assessment for a field based on crop history, scouting data, and environmental conditions.

## Output Format
```
PEST RISK ASSESSMENT
Field: [name] | Crop: [crop] | Growth Stage: [stage]
Date: [date] | Weather: [conditions]

CURRENT PEST PRESSURES:
Pest              Population    Threshold    Status       Action
──────────────────────────────────────────────────────────────
[Pest 1]          [X per unit]  [X per unit] [Below/At/Above ET]  [None/Scout/Treat]
[Pest 2]          [X]           [X]          [status]     [action]

DISEASE RISK:
Disease           Risk Level    Conditions Favoring    Probability
──────────────────────────────────────────────────────────────────
[Disease 1]       [Low/Med/Hi]  [describe]             [X]%

WEED PRESSURES:
[Identified weeds, resistance concerns, and management notes]

RECOMMENDATIONS:
1. [Specific action with product, rate, and timing if treatment warranted]
2. [Continue monitoring schedule]
3. [Cultural management adjustments]

NEXT SCOUTING DATE: [date]
```
