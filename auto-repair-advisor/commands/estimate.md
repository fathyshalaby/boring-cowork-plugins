# Command: /auto:estimate

Generate an itemized repair estimate for a customer's vehicle.

## Required Input
- Vehicle year, make, model, mileage
- Diagnosed problem(s) and recommended repair(s)
- Parts needed with pricing
- Labor time and rate

## Output Format
```
REPAIR ESTIMATE
Date: [date] | RO#: [number]
Vehicle: [Year Make Model] | Mileage: [X]
VIN: [if available]
Customer: [name] | Phone: [number]

DIAGNOSIS: [Summary of findings]

PRIORITY 1 – SAFETY/IMMEDIATE:
Description              Parts    Labor    Total
──────────────────────────────────────────────────
[Repair description]     $[X]     $[X]     $[X]

PRIORITY 2 – RECOMMENDED (Next 3-6 months):
[Repair description]     $[X]     $[X]     $[X]

PRIORITY 3 – MAINTENANCE:
[Repair description]     $[X]     $[X]     $[X]

Shop Supplies:                              $[X]
Tax:                                        $[X]
                                            ──────
TOTAL ESTIMATE:                             $[X]

Warranty: [X] months / [X] miles on parts and labor
Authorization: __________ Date: __________
```
