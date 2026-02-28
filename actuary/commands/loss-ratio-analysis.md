# Command: /actuary:loss-ratio-analysis

Generate a detailed loss ratio analysis by segment.

## Output Format
```
LOSS RATIO ANALYSIS
Line: [name] | State: [state] | Period: [years]

OVERALL RESULTS:
                     CY [Year]   CY [Year]   CY [Year]   3-Year
─────────────────────────────────────────────────────────────────
Earned Premium       $[X]M       $[X]M       $[X]M       $[X]M
Incurred Losses      $[X]M       $[X]M       $[X]M       $[X]M
Loss Ratio           [X]%        [X]%        [X]%        [X]%
LAE Ratio            [X]%        [X]%        [X]%        [X]%
Expense Ratio        [X]%        [X]%        [X]%        [X]%
Combined Ratio       [X]%        [X]%        [X]%        [X]%

LOSS RATIO BY SEGMENT:
[Profitability heat map by class, territory, or coverage]

FREQUENCY & SEVERITY TRENDS:
[Trend data showing direction of claim frequency and average severity]

KEY OBSERVATIONS:
1. [Most significant finding]
2. [Second finding]
3. [Third finding]

RECOMMENDED ACTIONS:
[Specific pricing, underwriting, or claims actions to improve results]
```
