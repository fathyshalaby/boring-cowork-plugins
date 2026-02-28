# Command: /osha:incident-report

Generate a workplace incident investigation report.

## Output Format
```
INCIDENT INVESTIGATION REPORT
Date/Time: [X] | Location: [X]
Injured Employee: [name] | Job Title: [title]
Supervisor: [name]

INJURY: [Description, body part, severity]
Medical Treatment: ☐ First Aid ☐ Beyond First Aid ☐ Hospitalization

INCIDENT DESCRIPTION:
[Detailed narrative of events]

ROOT CAUSE ANALYSIS (5 Whys):
1. Why: [immediate cause]
2. Why: [contributing factor]
3. Why: [system failure]
4. Why: [deeper cause]
5. Why: [root cause]

CORRECTIVE ACTIONS:
#  Action                    Owner      Due Date    Status
────────────────────────────────────────────────────────────
1  [corrective action]       [name]     [date]      [status]

OSHA RECORDABLE: ☐ Yes ☐ No
OSHA REPORTABLE: ☐ Yes (reported [date/time])
Investigator: _____________ Date: _________
```
