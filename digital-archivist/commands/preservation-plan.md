# Command: /archive:preservation-plan

Generate a digital preservation plan for a collection.

## Output Format
```
DIGITAL PRESERVATION PLAN
Collection: [name] | Date: [date]

COLLECTION PROFILE:
Total Files: [X] | Total Size: [X GB]
Formats: [list with counts]
At-Risk Formats: [list]

PRESERVATION ACTIONS:
Format          Action           Priority    Timeline
────────────────────────────────────────────────────────
[format]        [migrate/monitor] [H/M/L]    [date]

STORAGE PLAN:
Copy 1: [location/media]
Copy 2: [location/media]
Copy 3: [offsite location]

FIXITY SCHEDULE: [frequency]
REVIEW SCHEDULE: [annual/biennial]
```
