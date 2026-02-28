# Command: /billing:aging-report

Generate an accounts receivable aging analysis with action items.

## Output Format
```
ACCOUNTS RECEIVABLE AGING REPORT
Practice: [name] | As of: [date]

SUMMARY BY AGING BUCKET:
Aging Bucket        Claims    Amount        % of Total
────────────────────────────────────────────────────────
0-30 Days           [X]       $[X]          [X]%
31-60 Days          [X]       $[X]          [X]%
61-90 Days          [X]       $[X]          [X]%
91-120 Days         [X]       $[X]          [X]%
121+ Days           [X]       $[X]          [X]%
────────────────────────────────────────────────────────
TOTAL A/R:          [X]       $[X]          100%

DAYS IN A/R: [X] days (Target: <35)

TOP PAYERS BY OUTSTANDING A/R:
Payer               Amount    Avg Days    Action Needed
────────────────────────────────────────────────────────
[Payer 1]           $[X]      [X]         [action]
[Payer 2]           $[X]      [X]         [action]
[Payer 3]           $[X]      [X]         [action]

PRIORITY ACTION ITEMS:
1. [High-value claims requiring immediate follow-up]
2. [Payer with systematic denial pattern to address]
3. [Timely filing deadlines approaching]
```
