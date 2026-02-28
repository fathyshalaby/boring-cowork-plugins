# Command: /fleet:tco-calc

Generate a TCO analysis for a vehicle purchase/lease decision.

## Output Format
```
TOTAL COST OF OWNERSHIP ANALYSIS
Vehicle: [Year Make Model] | Holding Period: [X years]

                    PURCHASE        LEASE
─────────────────────────────────────────────
Acquisition Cost    $[X]            N/A
Monthly Payment     N/A             $[X]/mo
Total Payments      N/A             $[X]
Fuel Cost           $[X]            $[X]
Maintenance         $[X]            $[X]
Insurance           $[X]            $[X]
Resale/Residual    ($[X])           $0

TOTAL COST          $[X]            $[X]
Cost Per Mile       $[X]            $[X]
Cost Per Month      $[X]            $[X]

RECOMMENDATION: [Purchase/Lease] — [rationale]
```
