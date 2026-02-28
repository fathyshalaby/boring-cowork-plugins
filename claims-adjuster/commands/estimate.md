# Command: /claims:estimate

Generate a structured damage estimate summary for a property or auto claim.

## Output Format
```
DAMAGE ESTIMATE SUMMARY
Claim #: [number] | Date of Loss: [date]
Insured: [name] | Property: [address or vehicle]

SCOPE OF DAMAGE:
[Description of all damaged areas/components]

ESTIMATE DETAIL:
Item                        Qty    Unit Cost    Total
──────────────────────────────────────────────────────
[Line item]                 [X]    $[X]         $[X]
[Line item]                 [X]    $[X]         $[X]
[etc.]

Subtotal:                                       $[X]
Overhead & Profit ([X]%):                       $[X]
Sales Tax:                                      $[X]

GROSS ESTIMATE (RCV):                           $[X]
Less Depreciation:                             ($[X])
NET ESTIMATE (ACV):                             $[X]
Less Deductible:                               ($[X])
PAYMENT AMOUNT:                                 $[X]
Recoverable Depreciation (upon completion):     $[X]

NOTES:
[Any limitations, exclusions, or supplemental claim provisions]
```
