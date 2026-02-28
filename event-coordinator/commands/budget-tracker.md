# Command: /events:budget-tracker

Generate a detailed event budget template with estimated vs. actual tracking.

## Output Format
```
EVENT BUDGET TRACKER
Event: [name] | Date: [date] | Target Budget: $[X]

CATEGORY              ESTIMATED   ACTUAL    VARIANCE   PAID?
──────────────────────────────────────────────────────────────
VENUE
  Room Rental          $[X]        $[X]      $[X]       ☐
  Security Deposit     $[X]        $[X]      $[X]       ☐

FOOD & BEVERAGE
  Catering             $[X]        $[X]      $[X]       ☐
  Bar Service          $[X]        $[X]      $[X]       ☐
  Service Charge       $[X]        $[X]      $[X]       ☐

[etc. for all categories]

CONTINGENCY (10%)     $[X]        $[X]      $[X]

TOTAL                 $[X]        $[X]      $[X]

REVENUE:
Ticket Sales          $[X]
Sponsorships          $[X]
TOTAL REVENUE         $[X]

NET PROFIT/(LOSS)     $[X]
```
