# Command: /osha:osha-risk-assessment

Generate a safety risk assessment for a task or work area.

## Output Format
```
SAFETY RISK ASSESSMENT
Task/Area: [description] | Date: [date]
Assessor: [name]

HAZARD ANALYSIS:
#  Hazard        Type     L(1-5) S(1-5) Risk   Controls
────────────────────────────────────────────────────────────
1  [hazard]     [S/H/E]   [X]    [X]    [X]    [controls]
2  [hazard]     [type]    [X]    [X]    [X]    [controls]

RISK LEVELS: 1-6 Low | 7-12 Medium | 13-19 High | 20-25 Critical

REQUIRED PPE: [list]
TRAINING REQUIRED: [list]
PERMITS REQUIRED: [list]

RESIDUAL RISK (after controls): [Low/Med/High]
Review Date: [next review]
```
