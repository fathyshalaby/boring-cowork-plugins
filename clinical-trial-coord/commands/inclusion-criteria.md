# Command: /trial:inclusion-criteria

Generate a subject eligibility verification worksheet.

## Output Format
```
SUBJECT ELIGIBILITY VERIFICATION
Protocol: [name/number] | Subject ID: [X]
Screening Date: [date] | Verified By: [name]

INCLUSION CRITERIA:
#   Criterion                        Source Document    Met?
──────────────────────────────────────────────────────────────
1   [criterion text]                 [source]           ☐ Yes ☐ No
2   [criterion text]                 [source]           ☐ Yes ☐ No
[etc.]

EXCLUSION CRITERIA:
#   Criterion                        Source Document    Present?
──────────────────────────────────────────────────────────────────
1   [criterion text]                 [source]           ☐ Yes ☐ No
2   [criterion text]                 [source]           ☐ Yes ☐ No
[etc.]

ELIGIBILITY DETERMINATION:
☐ ALL inclusion criteria met AND NO exclusion criteria present → ELIGIBLE
☐ Subject NOT eligible → Reason: [specify]

Investigator Signature: _____________  Date: __________
```
