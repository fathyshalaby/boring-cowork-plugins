# Command: /hoa:reserve-planner

Generate a reserve fund projection summary.

## Output Format
```
RESERVE FUND PROJECTION
Association: [name] | Date: [date]
Current Balance: $[X] | Percent Funded: [X]%

UPCOMING EXPENDITURES:
Component              Replace Year    Est. Cost
───────────────────────────────────────────────────
[component]            [year]          $[X]
[component]            [year]          $[X]

5-YEAR PROJECTION:
Year    Contribution    Expenditures    Balance    % Funded
────────────────────────────────────────────────────────────
[year]  $[X]            $[X]            $[X]       [X]%

RECOMMENDATION:
[Increase/maintain contributions at $[X]/unit/month]
```
