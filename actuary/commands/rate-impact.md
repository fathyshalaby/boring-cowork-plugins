# Command: /actuary:rate-impact

Generate a rate impact analysis showing how a proposed rate change affects different customer segments.

## Output Format
```
RATE IMPACT ANALYSIS
Proposed Change: [+/- X.X%] overall | Effective: [date]

IMPACT BY SEGMENT:
Segment              Policies    Current Prem    Change %    $ Impact
────────────────────────────────────────────────────────────────────
[Segment 1]          [X]         $[X]            [+/- X]%    $[X]
[Segment 2]          [X]         $[X]            [+/- X]%    $[X]
[etc.]

DISTRIBUTION OF INDIVIDUAL IMPACTS:
Decrease >10%:    [X]% of policies
Decrease 0-10%:   [X]% of policies
Increase 0-10%:   [X]% of policies
Increase 10-25%:  [X]% of policies
Increase >25%:    [X]% of policies

MAXIMUM INDIVIDUAL INCREASE: [X]% (capped at [X]%)
MAXIMUM INDIVIDUAL DECREASE: [X]%

COMPETITIVE POSITIONING:
[How the proposed rates compare to market competitors]
```
