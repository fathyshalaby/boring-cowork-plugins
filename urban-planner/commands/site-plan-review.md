# Command: /planning:site-plan-review

Generate a site plan review checklist for a development application.

## Output Format
```
SITE PLAN REVIEW
Project: [name] | Case #: [number]
Address: [address] | Zoning: [code]
Reviewer: [name] | Date: [date]

#   Category              Item                    C/NC/NA  Notes
──────────────────────────────────────────────────────────────────
    ZONING COMPLIANCE
1   Use                   Permitted in zone        ☐       [note]
2   Setbacks              Meet minimum             ☐       [note]
3   Height                Within limit             ☐       [note]
4   Lot coverage          Within limit             ☐       [note]

    PARKING & ACCESS
5   Count                 Meets minimum            ☐       [note]
6   ADA spaces            Required number          ☐       [note]

    LANDSCAPING
7   Buffer yards          Required screening       ☐       [note]

[Continue for all categories]

DECISION: ☐ Approve ☐ Approve w/ conditions ☐ Deny
CONDITIONS: [list]
```
