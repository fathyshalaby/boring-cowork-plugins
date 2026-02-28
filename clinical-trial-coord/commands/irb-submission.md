# Command: /trial:irb-submission

Generate an IRB submission tracking document.

## Output Format
```
IRB SUBMISSION TRACKER
Protocol: [name/number] | IRB: [name]

SUBMISSION LOG:
Type          Date Submitted   Date Approved   Expiration   Status
──────────────────────────────────────────────────────────────────────
Initial       [date]           [date]          [date]       Approved
Amendment 1   [date]           [date]          N/A          Approved
Cont. Review  [date]           [date]          [date]       Approved
[etc.]

CURRENT STATUS:
IRB Approval Valid Through: [date]
⚠️ Renewal Due: [date - 6 weeks before expiration]

PENDING SUBMISSIONS:
• [Description of pending submission and target date]
```
