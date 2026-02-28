# Command: /realestate:net-sheet

Generate a seller's estimated net proceeds worksheet.

## Required Input
- Sale price
- Existing mortgage balance(s)
- Commission percentage(s)
- Known closing costs

## Output Format
```
SELLER'S ESTIMATED NET PROCEEDS
Property: [Address] | Estimated Sale Price: $[X]

GROSS PROCEEDS:                              $[sale price]

LESS COSTS OF SALE:
  Listing Agent Commission ([X]%)            ($[X])
  Buyer Agent Commission ([X]%)              ($[X])
  Title Insurance (owner's policy)           ($[X])
  Escrow/Closing Fee                         ($[X])
  Recording Fees                             ($[X])
  Transfer Tax/Excise Tax                    ($[X])
  Home Warranty (if offered)                 ($[X])
  Repair Credits/Concessions                 ($[X])
  Prorated Property Taxes                    ($[X])
  HOA Prorations/Transfer Fee                ($[X])
                                             ──────────
TOTAL COSTS OF SALE:                         ($[X])

LESS MORTGAGE PAYOFF(S):
  First Mortgage Balance                     ($[X])
  Second Mortgage/HELOC                      ($[X])
                                             ──────────

ESTIMATED NET PROCEEDS:                      $[X]

⚠️ This is an ESTIMATE. Actual figures will be determined
by the title company at closing.
```
