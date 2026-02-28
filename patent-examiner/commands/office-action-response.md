# Command: /patent:office-action-response

Generate a framework for responding to a USPTO office action.

## Output Format
```
OFFICE ACTION RESPONSE
Application: [number] | Filing Date: [date]
Office Action Date: [date] | Type: [Non-Final/Final]
Due Date: [date]

REJECTIONS:
#  Claims    Basis     References            Status
─────────────────────────────────────────────────────────
1  [claims]  §102/103  [reference(s)]         [strategy]

RESPONSE STRATEGY:
Claim Amendments:
[Proposed claim language changes]

Arguments:
[Key arguments distinguishing prior art]

INTERVIEW RECOMMENDED: ☐ Yes ☐ No
[If yes: topic and proposed discussion points]
```
