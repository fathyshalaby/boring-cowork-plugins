# Command: /cleaner:qa-report

Generate a QA inspection report for a client facility.

## Output Format
```
QUALITY ASSURANCE INSPECTION REPORT
Facility: [name] | Date: [date]
Inspector: [name]

AREA SCORES (1=Poor, 5=Excellent):
Area                Score    Notes
──────────────────────────────────────────
Lobby/Reception     [X]/5    [notes]
Offices             [X]/5    [notes]
Restrooms           [X]/5    [notes]
Break Room          [X]/5    [notes]
Stairwells          [X]/5    [notes]
Exterior/Entrance   [X]/5    [notes]

OVERALL SCORE: [X]/5 ([X]%)

ISSUES IDENTIFIED:
1. [Issue description, location, severity]
2. [Issue]

CORRECTIVE ACTIONS:
1. [Action to be taken, responsible person, deadline]

TREND: [Improving / Stable / Declining vs. last inspection]
```
